# Completed React App

You need [node](https://nodejs.org/en/) version 6 or higher. Check your node version:

```
node -v
```

If your node version is version 5 or lower, you can [install `nvm`](https://github.com/creationix/nvm#install-script) to manage multiple versions of node.

Clone the [`react-workshop`](https://github.com/schneidenbach/react-workshop) repo:

```sh
git clone https://github.com/schneidenbach/react-workshop.git
```

Install all of the dependencies ([`yarn`](https://yarnpkg.com/en/) is preferred):

```sh
# Yarn
yarn install

# ...or NPM
npm install
```

Update [`src/index.js`](../../index.js#L3) to point to the `end` App:

```js
import App from './react/end/App';
```

Start the API server (running at [http://localhost:9090/](http://localhost:9090/)):

```sh
# Yarn
yarn run start:api

# ...or NPM
npm run start:api
```

In a **separate terminal window/tab**, making sure you're still in the repo root, start the app:

```sh
# Yarn
yarn start

# ...or NPM
npm start
```

After the app is initially built, a new browser window should open up at [http://localhost:3000/](http://localhost:3000/).
