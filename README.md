# TypeScript-Node-Webpack-Starter
This starter projects help you quickly build a web server using Node and TypeScript.
It is configured with the following:

- As the name suggests, [TypeScript](https://www.typescriptlang.org/) is used in this project. TypeScript comes with a list of features that are not available to vanilla JavaScript developers.
- The lightweight [Koa](https://koajs.com/) web framework is used for the server.
- [WebPack](https://webpack.js.org/guides/) is used to bundle source files, both client and server. 
- [Jest](https://jestjs.io/) (from Facebook) is used for testing.
- [Pug](https://pugjs.org/api/getting-started.html) is used for HTML templating

In addition, the project has the following features:

- WebPack is already configured for both client-side and server-side code.
- [dotenv](https://www.npmjs.com/package/dotenv) is configured to allow the user to store configurations in the `env` file.
- When the app is run locally, changes to local files automatically initiate a rebuild, so you don't have to restart the server.
- Unlike many other template/starter projects, the code is minimal so it is to start building on top of it, perhaps some little cleaning.
- [tslint](https://palantir.github.io/tslint/) is used to reduce common problems in your TypeScript code.

To try it out, create a file named `.env` at the root and put the following content in it:
```
PORT=5000
```
then run the following at the project's root directory after cloning it:
```shell
npm install
npm run start
```
Then you should be able to open the website at http://localhost:5000

To bundle the code, execute:
```
npm run build
```
You should now see a folder called `dist`. To execute the bundled server code:
```
node dist/server.js
```

For more information on the other available commands, check the [package.json](package.json)

If you have any problem, feel free to create an issue and I will try to address it. If you would like to make a contribution, please fork and send a PR.

