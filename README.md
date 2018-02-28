# React Starter Kit for HA

## This starter kit includes:
- Production libraries
  - [react-bootstrap](https://github.com/react-bootstrap/react-bootstrap/)
  - [redux](https://redux.js.org/)
  - [react-router](https://github.com/ReactTraining/react-router)
- Development libraries
  - [Jest](https://github.com/facebook/jest)
  - [Enzyme](https://github.com/airbnb/enzyme)
  - [Flow](https://github.com/facebook/flow)
  - [Storybook](https://storybook.js.org/)
  - [Prettier](https://github.com/prettier/prettier)

Sample code: https://github.com/haitlc/react-admin-demo

## Getting Started

1. Clone Repo

```sh 
git clone https://github.com/haitlc/ha-react-starter-kit.git
cd ha-react-starter-kit
```

2. Remove git history and start a brand new repository:

Mac
```sh
rm -rf .git
git init
```

Windows
```sh
rd /s /q .git
git init
```

3. Install dependencies

````
yarn
````

4. Start development server
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

## Production Build

Webpack will be used for packing the production build

````
yarn build
````

The optimized and minified files will be generated in */build* folder