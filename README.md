# Webpack Boilerplate

Forked from <https://github.com/marharyta/webpack-boilerplate>.

This is a project that provides [Webpack v4](https://webpack.js.org/) boilerplates for out-of-box to quickstart development. Read the blog post about it here: <https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1>

I don't believe in universal configurations and boilerplates when it comes to configuration files. I believe every project should be treated and configured individually. Yet, there is a set of good practices that can help with minimal project setup.

This project is a collection of webpack setups I find useful that you can copy directly and start using on your project. They are not limited to webpack only, but also have ESLint and Stylelint configured too. Every setup is based on webpack v4 and some are 100% framework agnostic.

## Run the code

1. `cd` into the project folder
1. `npm install`
1. `npm run dev`

This will either compile the web assets and/or run a [Webpack dev server](https://github.com/webpack/webpack-dev-server) in order to serve up the Webpack app.

### `basic-setup` folder

This is the bare minimum webpack setup to start writing websites.

### `sass-setup` folder

This is the `basic-setup` plus support for SASS.

### `development-setup` folder

This is a development process oriented setup. It includes the `basic-setup` and some development features and settings.
