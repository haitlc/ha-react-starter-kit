# React Starter Kit for HA

## Features

## This starter kit includes:
- Libraries
  - [react-bootstrap](https://github.com/react-bootstrap/react-bootstrap/)
  - [redux]
- Unit test examples with [Jest](https://github.com/facebook/jest) and [Enzyme](https://github.com/airbnb/enzyme)
- Static type checking with [Flow](https://github.com/facebook/flow)
- Style management using CSS-in-JS library, [styled-components](https://github.com/styled-components/styled-components)
- UI component development environment using [Storybook](https://storybook.js.org/)
- Code formatting using [Prettier](https://github.com/prettier/prettier)

Sample code: https://github.com/haitlc/react-admin-demo

## Getting Started

### 1. Clone Repo

````bash 
git clone https://github.com/haitlc/ha-react-starter-kit.git
cd ha-react-starter-kit
````

### 2. Install dependencies

````
yarn
````

### 3. Start development server
````
yarn start
````

Browse to http://localhost:3000

## Storybook
```
yarn storybook
```

browse http://localhost:9001/

## Unit test
Run in watch mode
```
yarn test
```

Test Coverage
```
yarn test --coverage
```

## Format code
The format configuration is in `/.prettierrc`.
You may need to install this [Visual Studio Code plugin](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) first, and press `Alt+Shift+F` to format the code.

### Production Build

Webpack will be used for packing the production build

````
yarn build
````

The optimized and minified files will be generated in */build* folder