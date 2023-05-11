
<p align="center">
  <a href="https://vitejs.dev" target="_blank" rel="noopener noreferrer">
    <img width="180" src="https://vitejs.dev/logo.svg" alt="Vite logo">
  </a>
</p>
<br/>
<p align="center">
  <a href="https://npmjs.com/package/vite"><img src="https://img.shields.io/npm/v/vite.svg" alt="npm package"></a>
  <a href="https://nodejs.org/en/about/releases/"><img src="https://img.shields.io/node/v/vite.svg" alt="node compatibility"></a>
  <a href="https://github.com/vitejs/vite/actions/workflows/ci.yml"><img src="https://github.com/vitejs/vite/actions/workflows/ci.yml/badge.svg?branch=main" alt="build status"></a>
  <a href="https://chat.vitejs.dev"><img src="https://img.shields.io/badge/chat-discord-blue?style=flat&logo=discord" alt="discord chat"></a>
</p>
<br/>

# Vite ⚡

> Next Generation Frontend Tooling

- 💡 Instant Server Start
- ⚡️ Lightning Fast HMR
- 🛠️ Rich Features
- 📦 Optimized Build
- 🔩 Universal Plugin Interface
- 🔑 Fully Typed APIs

Vite (French word for "quick", pronounced [`/vit/`](https://cdn.jsdelivr.net/gh/vitejs/vite@main/docs/public/vite.mp3), like "veet") is a new breed of frontend build tooling that significantly improves the frontend development experience. It consists of two major parts:

- A dev server that serves your source files over [native ES modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules), with [rich built-in features](https://vitejs.dev/guide/features.html) and astonishingly fast [Hot Module Replacement (HMR)](https://vitejs.dev/guide/features.html#hot-module-replacement).

- A [build command](https://vitejs.dev/guide/build.html) that bundles your code with [Rollup](https://rollupjs.org), pre-configured to output highly optimized static assets for production.

In addition, Vite is highly extensible via its [Plugin API](https://vitejs.dev/guide/api-plugin.html) and [JavaScript API](https://vitejs.dev/guide/api-javascript.html) with full typing support.

[Read the Docs to Learn More](https://vitejs.dev).

## Packages

| Package                                           | Version (click for changelogs)                                                                                                       |
| ------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------- |
| [vite](packages/vite)                             | [![vite version](https://img.shields.io/npm/v/vite.svg?label=%20)](packages/vite/CHANGELOG.md)                                       |
| [@vitejs/plugin-vue](packages/plugin-vue)         | [![plugin-vue version](https://img.shields.io/npm/v/@vitejs/plugin-vue.svg?label=%20)](packages/plugin-vue/CHANGELOG.md)             |
| [@vitejs/plugin-vue-jsx](packages/plugin-vue-jsx) | [![plugin-vue-jsx version](https://img.shields.io/npm/v/@vitejs/plugin-vue-jsx.svg?label=%20)](packages/plugin-vue-jsx/CHANGELOG.md) |
| [@vitejs/plugin-react](packages/plugin-react)     | [![plugin-react version](https://img.shields.io/npm/v/@vitejs/plugin-react.svg?label=%20)](packages/plugin-react/CHANGELOG.md)       |
| [@vitejs/plugin-legacy](packages/plugin-legacy)   | [![plugin-legacy version](https://img.shields.io/npm/v/@vitejs/plugin-legacy.svg?label=%20)](packages/plugin-legacy/CHANGELOG.md)    |
| [create-vite](packages/create-vite)               | [![create-vite version](https://img.shields.io/npm/v/create-vite.svg?label=%20)](packages/create-vite/CHANGELOG.md)                  |

## Contribution

See [Contributing Guide](https://github.com/vitejs/vite/blob/main/CONTRIBUTING.md).

## License

MIT

## Sponsors

<p align="center">
  <a target="_blank" href="https://github.com/sponsors/yyx990803">
    <img alt="sponsors" src="https://sponsors.vuejs.org/vite.svg">
  </a>
</p>

<div align="center">
  <a href="https://github.com/webpack/webpack">
    <img width="200" height="200" src="https://webpack.js.org/assets/icon-square-big.svg">
  </a>
  <br>
  <br>

[![npm][npm]][npm-url]

[![node][node]][node-url]
[![deps][deps]][deps-url]
[![builds2][builds2]][builds2-url]
[![coverage][cover]][cover-url]
[![licenses][licenses]][licenses-url]
[![PR's welcome][prs]][prs-url]

  <br>
  <a href="https://docs.github.com/en/code-security/dependabot/dependabot-security-updates/about-dependabot-security-updates#about-compatibility-scores">
    <img src="https://api.dependabot.com/badges/compatibility_score?dependency-name=webpack&package-manager=npm_and_yarn&previous-version=5.72.1&new-version=5.73.0">
  </a>
	<a href="https://npmcharts.com/compare/webpack?minimal=true">
		<img src="https://img.shields.io/npm/dm/webpack.svg">
	</a>
	<a href="https://packagephobia.com/result?p=webpack">
		<img src="https://packagephobia.com/badge?p=webpack" alt="install size">
	</a>
	<a href="https://opencollective.com/webpack#backer">
		<img src="https://opencollective.com/webpack/backers/badge.svg">
	</a>
	<a href="https://opencollective.com/webpack#sponsors">
		<img src="https://opencollective.com/webpack/sponsors/badge.svg">
	</a>
	<a href="https://github.com/webpack/webpack/graphs/contributors">
		<img src="https://img.shields.io/github/contributors/webpack/webpack.svg">
	</a>
	<a href="https://gitter.im/webpack/webpack">
		<img src="https://badges.gitter.im/webpack/webpack.svg">
	</a>
  <h1>webpack</h1>
  <p>
    Webpack is a module bundler. Its main purpose is to bundle JavaScript files for usage in a browser, yet it is also capable of transforming, bundling, or packaging just about any resource or asset.
  </p>
</div>

## Table of Contents

1. [Install](#install)
2. [Introduction](#introduction)
3. [Concepts](#concepts)
4. [Contributing](#contributing)
5. [Support](#support)
6. [Core Team](#core-team)
7. [Sponsoring](#sponsoring)
8. [Premium Partners](#premium-partners)
9. [Other Backers and Sponsors](#other-backers-and-sponsors)
10. [Gold Sponsors](#gold-sponsors)
11. [Silver Sponsors](#silver-sponsors)
12. [Bronze Sponsors](#bronze-sponsors)
13. [Backers](#backers)
14. [Special Thanks](#special-thanks-to)

<h2 align="center">Install</h2>

Install with npm:

```bash
npm install --save-dev webpack
```

Install with yarn:

```bash
yarn add webpack --dev
```

<h2 align="center">Introduction</h2>

Webpack is a bundler for modules. The main purpose is to bundle JavaScript
files for usage in a browser, yet it is also capable of transforming, bundling,
or packaging just about any resource or asset.

**TL;DR**

- Bundles [ES Modules](https://www.2ality.com/2014/09/es6-modules-final.html), [CommonJS](http://wiki.commonjs.org/), and [AMD](https://github.com/amdjs/amdjs-api/wiki/AMD) modules (even combined).
- Can create a single bundle or multiple chunks that are asynchronously loaded at runtime (to reduce initial loading time).
- Dependencies are resolved during compilation, reducing the runtime size.
- Loaders can preprocess files while compiling, e.g. TypeScript to JavaScript, Handlebars strings to compiled functions, images to Base64, etc.
- Highly modular plugin system to do whatever else your application requires.

### Get Started

Check out webpack's quick [**Get Started**](https://webpack.js.org/guides/getting-started) guide and the [other guides](https://webpack.js.org/guides/).

### Browser Compatibility

Webpack supports all browsers that are [ES5-compliant](https://kangax.github.io/compat-table/es5/) (IE8 and below are not supported).
Webpack also needs `Promise` for `import()` and `require.ensure()`. If you want to support older browsers, you will need to [load a polyfill](https://webpack.js.org/guides/shimming/) before using these expressions.

<h2 align="center">Concepts</h2>

### [Plugins](https://webpack.js.org/plugins/)

Webpack has a [rich plugin
interface](https://webpack.js.org/plugins/). Most of the features
within webpack itself use this plugin interface. This makes webpack very
**flexible**.

|                   Name                    |       Status       |    Install Size     | Description                                                                             |
| :---------------------------------------: | :----------------: | :-----------------: | :-------------------------------------------------------------------------------------- |
|    [mini-css-extract-plugin][mini-css]    |  ![mini-css-npm]   |  ![mini-css-size]   | Extracts CSS into separate files. It creates a CSS file per JS file which contains CSS. |
| [compression-webpack-plugin][compression] | ![compression-npm] | ![compression-size] | Prepares compressed versions of assets to serve them with Content-Encoding              |
|    [html-webpack-plugin][html-plugin]     | ![html-plugin-npm] | ![html-plugin-size] | Simplifies creation of HTML files (`index.html`) to serve your bundles                  |
|         [pug-plugin][pug-plugin]          | ![pug-plugin-npm]  | ![pug-plugin-size]  | Renders Pug files to HTML, extracts JS and CSS from sources specified directly in Pug.  |

[common-npm]: https://img.shields.io/npm/v/webpack.svg
[mini-css]: https://github.com/webpack-contrib/mini-css-extract-plugin
[mini-css-npm]: https://img.shields.io/npm/v/mini-css-extract-plugin.svg
[mini-css-size]: https://packagephobia.com/badge?p=mini-css-extract-plugin
[component]: https://github.com/webpack-contrib/component-webpack-plugin
[component-npm]: https://img.shields.io/npm/v/component-webpack-plugin.svg
[component-size]: https://packagephobia.com/badge?p=component-webpack-plugin
[compression]: https://github.com/webpack-contrib/compression-webpack-plugin
[compression-npm]: https://img.shields.io/npm/v/compression-webpack-plugin.svg
[compression-size]: https://packagephobia.com/badge?p=compression-webpack-plugin
[html-plugin]: https://github.com/jantimon/html-webpack-plugin
[html-plugin-npm]: https://img.shields.io/npm/v/html-webpack-plugin.svg
[html-plugin-size]: https://packagephobia.com/badge?p=html-webpack-plugin
[pug-plugin]: https://github.com/webdiscus/pug-plugin
[pug-plugin-npm]: https://img.shields.io/npm/v/pug-plugin.svg
[pug-plugin-size]: https://packagephobia.com/badge?p=pug-plugin

### [Loaders](https://webpack.js.org/loaders/)

Webpack enables the use of loaders to preprocess files. This allows you to bundle
**any static resource** way beyond JavaScript. You can easily [write your own
loaders](https://webpack.js.org/api/loaders/) using Node.js.

Loaders are activated by using `loadername!` prefixes in `require()` statements,
or are automatically applied via regex from your webpack configuration.

#### Files

|       Name        |   Status   | Install Size | Description                                              |
| :---------------: | :--------: | :----------: | :------------------------------------------------------- |
| [val-loader][val] | ![val-npm] | ![val-size]  | Executes code as module and considers exports as JS code |

[val]: https://github.com/webpack-contrib/val-loader
[val-npm]: https://img.shields.io/npm/v/val-loader.svg
[val-size]: https://packagephobia.com/badge?p=val-loader

#### JSON

|                                                                   Name                                                                    |   Status    | Install Size |           Description            |
| :---------------------------------------------------------------------------------------------------------------------------------------: | :---------: | :----------: | :------------------------------: |
| <a href="https://github.com/awnist/cson-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/coffeescript.svg"></a> | ![cson-npm] | ![cson-size] | Loads and transpiles a CSON file |

[cson-npm]: https://img.shields.io/npm/v/cson-loader.svg
[cson-size]: https://packagephobia.com/badge?p=cson-loader

#### Transpiling

|                                                                            Name                                                                            |    Status     |  Install Size  | Description                                                                                       |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------: | :------------: | :------------------------------------------------------------------------------------------------ |
| <a href="https://github.com/babel/babel-loader"><img width="48" height="48" title="babel-loader" src="https://worldvectorlogo.com/logos/babel-10.svg"></a> | ![babel-npm]  | ![babel-size]  | Loads ES2015+ code and transpiles to ES5 using <a href="https://github.com/babel/babel">Babel</a> |
|  <a href="https://github.com/TypeStrong/ts-loader"><img width="48" height="48" src="https://cdn.rawgit.com/Microsoft/TypeScript/master/doc/logo.svg"></a>  |  ![type-npm]  |  ![type-size]  | Loads TypeScript like JavaScript                                                                  |
|    <a href="https://github.com/webpack-contrib/coffee-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/coffeescript.svg"></a>    | ![coffee-npm] | ![coffee-size] | Loads CoffeeScript like JavaScript                                                                |

[babel-npm]: https://img.shields.io/npm/v/babel-loader.svg
[babel-size]: https://packagephobia.com/badge?p=babel-loader
[coffee-npm]: https://img.shields.io/npm/v/coffee-loader.svg
[coffee-size]: https://packagephobia.com/badge?p=coffee-loader
[type-npm]: https://img.shields.io/npm/v/ts-loader.svg
[type-size]: https://packagephobia.com/badge?p=ts-loader

#### Templating

|                                                                                   Name                                                                                    |     Status      |   Install Size   | Description                                                                             |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------: | :--------------: | :-------------------------------------------------------------------------------------- |
|                <a href="https://github.com/webpack-contrib/html-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/html5.svg"></a>                |   ![html-npm]   |   ![html-size]   | Exports HTML as string, requires references to static resources                         |
|   <a href="https://github.com/pugjs/pug-loader"><img width="48" height="48" src="https://cdn.rawgit.com/pugjs/pug-logo/master/SVG/pug-final-logo-_-colour-128.svg"></a>   |   ![pug-npm]    |   ![pug-size]    | Loads Pug templates and returns a function                                              |
| <a href="https://github.com/webdiscus/pug-loader"><img width="48" height="48" src="https://cdn.rawgit.com/pugjs/pug-logo/master/SVG/pug-final-logo-_-colour-128.svg"></a> |   ![pug3-npm]   |   ![pug3-size]   | Compiles Pug to a function or HTML string, useful for use with Vue, React, Angular      |
|                <a href="https://github.com/peerigon/markdown-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/markdown.svg"></a>                |    ![md-npm]    |    ![md-size]    | Compiles Markdown to HTML                                                               |
|                 <a href="https://github.com/posthtml/posthtml-loader"><img width="48" height="48" src="https://posthtml.github.io/posthtml/logo.svg"></a>                 | ![posthtml-npm] | ![posthtml-size] | Loads and transforms a HTML file using [PostHTML](https://github.com/posthtml/posthtml) |
|             <a href="https://github.com/pcardune/handlebars-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/handlebars-1.svg"></a>             |   ![hbs-npm]    |   ![hbs-size]    | Compiles Handlebars to HTML                                                             |

[html-npm]: https://img.shields.io/npm/v/html-loader.svg
[html-size]: https://packagephobia.com/badge?p=html-loader
[pug-npm]: https://img.shields.io/npm/v/pug-loader.svg
[pug-size]: https://packagephobia.com/badge?p=pug-loader
[pug3-npm]: https://img.shields.io/npm/v/@webdiscus/pug-loader.svg
[pug3-size]: https://packagephobia.com/badge?p=@webdiscus/pug-loader
[jade-npm]: https://img.shields.io/npm/v/jade-loader.svg
[jade-size]: https://packagephobia.com/badge?p=jade-loader
[md-npm]: https://img.shields.io/npm/v/markdown-loader.svg
[md-size]: https://packagephobia.com/badge?p=markdown-loader
[posthtml-npm]: https://img.shields.io/npm/v/posthtml-loader.svg
[posthtml-size]: https://packagephobia.com/badge?p=posthtml-loader
[hbs-npm]: https://img.shields.io/npm/v/handlebars-loader.svg
[hbs-size]: https://packagephobia.com/badge?p=handlebars-loader

#### Styling

|                                                                     Name                                                                      |     Status     |  Install Size   | Description                                                              |
| :-------------------------------------------------------------------------------------------------------------------------------------------: | :------------: | :-------------: | :----------------------------------------------------------------------- |
|                                    <a href="https://github.com/webpack-contrib/style-loader">`<style>`</a>                                    |  ![style-npm]  |  ![style-size]  | Add exports of a module as style to DOM                                  |
|  <a href="https://github.com/webpack-contrib/css-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/css-3.svg"></a>   |   ![css-npm]   |   ![css-size]   | Loads CSS file with resolved imports and returns CSS code                |
| <a href="https://github.com/webpack-contrib/less-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/less-63.svg"></a> |  ![less-npm]   |  ![less-size]   | Loads and compiles a LESS file                                           |
| <a href="https://github.com/webpack-contrib/sass-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/sass-1.svg"></a>  |  ![sass-npm]   |  ![sass-size]   | Loads and compiles a Sass/SCSS file                                      |
|     <a href="https://github.com/shama/stylus-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/stylus.svg"></a>      | ![stylus-npm]  | ![stylus-size]  | Loads and compiles a Stylus file                                         |
|   <a href="https://github.com/postcss/postcss-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/postcss.svg"></a>    | ![postcss-npm] | ![postcss-size] | Loads and transforms a CSS/SSS file using [PostCSS](https://postcss.org) |

[style-npm]: https://img.shields.io/npm/v/style-loader.svg
[style-size]: https://packagephobia.com/badge?p=style-loader
[css-npm]: https://img.shields.io/npm/v/css-loader.svg
[css-size]: https://packagephobia.com/badge?p=css-loader
[less-npm]: https://img.shields.io/npm/v/less-loader.svg
[less-size]: https://packagephobia.com/badge?p=less-loader
[sass-npm]: https://img.shields.io/npm/v/sass-loader.svg
[sass-size]: https://packagephobia.com/badge?p=sass-loader
[stylus-npm]: https://img.shields.io/npm/v/stylus-loader.svg
[stylus-size]: https://packagephobia.com/badge?p=stylus-loader
[postcss-npm]: https://img.shields.io/npm/v/postcss-loader.svg
[postcss-size]: https://packagephobia.com/badge?p=postcss-loader

#### Frameworks

|                                                                             Name                                                                             |     Status     |  Install Size   | Description                                                                                            |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------: | :-------------: | :----------------------------------------------------------------------------------------------------- |
|               <a href="https://github.com/vuejs/vue-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/vue-9.svg"></a>               |   ![vue-npm]   |   ![vue-size]   | Loads and compiles Vue Components                                                                      |
|   <a href="https://github.com/webpack-contrib/polymer-webpack-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/polymer.svg"></a>   | ![polymer-npm] | ![polymer-size] | Process HTML & CSS with preprocessor of choice and `require()` Web Components like first-class modules |
| <a href="https://github.com/TheLarkInn/angular2-template-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/angular-icon-1.svg"></a> | ![angular-npm] | ![angular-size] | Loads and compiles Angular 2 Components                                                                |
|              <a href="https://github.com/riot/webpack-loader"><img width="48" height="48" src="https://worldvectorlogo.com/logos/riot.svg"></a>              |  ![riot-npm]   |  ![riot-size]   | Riot official webpack loader                                                                           |

[vue-npm]: https://img.shields.io/npm/v/vue-loader.svg
[vue-size]: https://packagephobia.com/badge?p=vue-loader
[polymer-npm]: https://img.shields.io/npm/v/polymer-webpack-loader.svg
[polymer-size]: https://packagephobia.com/badge?p=polymer-webpack-loader
[angular-npm]: https://img.shields.io/npm/v/angular2-template-loader.svg
[angular-size]: https://packagephobia.com/badge?p=angular2-template-loader
[riot-npm]: https://img.shields.io/npm/v/riot-tag-loader.svg
[riot-size]: https://packagephobia.com/badge?p=riot-tag-loader

### Performance

Webpack uses async I/O and has multiple caching levels. This makes webpack fast
and incredibly **fast** on incremental compilations.

### Module Formats

Webpack supports ES2015+, CommonJS and AMD modules **out of the box**. It performs clever static
analysis on the AST of your code. It even has an evaluation engine to evaluate
simple expressions. This allows you to **support most existing libraries** out of the box.

### [Code Splitting](https://webpack.js.org/guides/code-splitting/)

Webpack allows you to split your codebase into multiple chunks. Chunks are
loaded asynchronously at runtime. This reduces the initial loading time.

### [Optimizations](https://webpack.js.org/guides/production-build/)

Webpack can do many optimizations to **reduce the output size of your
JavaScript** by deduplicating frequently used modules, minifying, and giving
you full control of what is loaded initially and what is loaded at runtime
through code splitting. It can also make your code chunks **cache
friendly** by using hashes.

<h2 align="center">Contributing</h2>

**We want contributing to webpack to be fun, enjoyable, and educational for anyone, and everyone.** We have a [vibrant ecosystem](https://medium.com/webpack/contributors-guide/home) that spans beyond this single repo. We welcome you to check out any of the repositories in [our organization](https://github.com/webpack) or [webpack-contrib organization](https://github.com/webpack-contrib) which houses all of our loaders and plugins.

Contributions go far beyond pull requests and commits. Although we love giving you the opportunity to put your stamp on webpack, we also are thrilled to receive a variety of other contributions including:

- [Documentation](https://github.com/webpack/webpack.js.org) updates, enhancements, designs, or bugfixes
- Spelling or grammar fixes
- README.md corrections or redesigns
- Adding unit, or functional tests
- Triaging GitHub issues -- especially determining whether an issue still persists or is reproducible.
- [Searching #webpack on twitter](https://twitter.com/search?q=webpack) and helping someone else who needs help
- Teaching others how to contribute to one of the many webpack's repos!
- [Blogging, speaking about, or creating tutorials](https://github.com/webpack-contrib/awesome-webpack) about one of webpack's many features.
- Helping others in our webpack [gitter channel](https://gitter.im/webpack/webpack).

To get started have a look at our [documentation on contributing](https://github.com/webpack/webpack/blob/main/CONTRIBUTING.md).

If you are worried or don't know where to start, you can **always** reach out to [Sean Larkin (@TheLarkInn) on Twitter](https://twitter.com/thelarkinn) or simply submit an issue and a maintainer can help give you guidance!

We have also started a series on our [Medium Publication](https://medium.com/webpack) called [The Contributor's Guide to webpack](https://medium.com/webpack/contributors-guide/home). We welcome you to read it and post any questions or responses if you still need help.

_Looking to speak about webpack?_ We'd **love** to review your talk abstract/CFP! You can email it to webpack [at] opencollective [dot] com and we can give pointers or tips!!!

<h3 align="center">Creating your own plugins and loaders</h3>

If you create a loader or plugin, we would <3 for you to open source it, and put it on npm. We follow the `x-loader`, `x-webpack-plugin` naming convention.

<h2 align="center">Support</h2>

We consider webpack to be a low-level tool used not only individually but also layered beneath other awesome tools. Because of its flexibility, webpack isn't always the _easiest_ entry-level solution, however we do believe it is the most powerful. That said, we're always looking for ways to improve and simplify the tool without compromising functionality. If you have any ideas on ways to accomplish this, we're all ears!

If you're just getting started, take a look at [our new docs and concepts page](https://webpack.js.org/concepts/). This has a high level overview that is great for beginners!!

Looking for webpack 1 docs? Please check out the old [wiki](https://github.com/webpack/docs/wiki/contents), but note that this deprecated version is no longer supported.

If you want to discuss something or just need help, [here is our Gitter room](https://gitter.im/webpack/webpack) where there are always individuals looking to help out!

If you are still having difficulty, we would love for you to post
a question to [StackOverflow with the webpack tag](https://stackoverflow.com/tags/webpack). It is much easier to answer questions that include your webpack.config.js and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

If you are twitter savvy you can tweet #webpack with your question and someone should be able to reach out and help also.

If you have discovered a 🐜 or have a feature suggestion, feel free to create an issue on Github.

### License

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fwebpack%2Fwebpack.svg?type=large)](https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fwebpack%2Fwebpack?ref=badge_large)

<h2 align="center">Core Team</h2>

<table>
  <tbody>
    <tr>
      <td align="center" valign="top">
        <img width="150" height="150" src="https://github.com/sokra.png?s=150">
        <br>
        <a href="https://github.com/sokra">Tobias Koppers</a>
        <p>Core</p>
        <br>
        <p>Founder of webpack</p>
      </td>
      <td align="center" valign="top">
        <img width="150" height="150" src="https://github.com/jhnns.png?s=150">
        <br>
        <a href="https://github.com/jhnns">Johannes Ewald</a>
        <p>Loaders &amp; Plugins</p>
        <br>
        <p>Early adopter of webpack</p>
      </td>
      <td align="center" width="20%" valign="top">
        <img width="150" height="150" src="https://github.com/TheLarkInn.png?s=150">
        <br>
        <a href="https://github.com/TheLarkInn">Sean T. Larkin</a>
        <p>Public Relations</p>
        <br>
        <p>Founder of the core team</p>
      </td>
      <td align="center" valign="top">
        <img width="150" height="150" src="https://github.com/spacek33z.png?s=150">
        <br>
        <a href="https://github.com/spacek33z">Kees Kluskens</a>
        <p>Development</p>
        <br>
        <p>Sponsor</p>
        <a href="https://codeyellow.nl/">
          <img height="15px" src="https://cloud.githubusercontent.com/assets/1365881/20286583/ad62eb04-aac7-11e6-9c14-a0fef35b9b56.png">
        </a>
		<br>
      </td>
     </tr>
  </tbody>
</table>

<h2 align="center">Sponsoring</h2>

Most of the core team members, webpack contributors and contributors in the ecosystem do this open source work in their free time. If you use webpack for a serious task, and you'd like us to invest more time on it, please donate. This project increases your income/productivity too. It makes development and applications faster and it reduces the required bandwidth.

This is how we use the donations:

- Allow the core team to work on webpack
- Thank contributors if they invested a large amount of time in contributing
- Support projects in the ecosystem that are of great value for users
- Support projects that are voted most (work in progress)
- Infrastructure cost
- Fees for money handling

<h2 align="center">Premium Partners</h2>

<div align="center">

<a href="https://www.ag-grid.com/?utm_source=webpack&utm_medium=banner&utm_campaign=sponsorship" target="_blank"><img align="center" src="https://raw.githubusercontent.com/webpack/media/2b399d58/horiz-banner-ad-ag-grid.png">
</a>

</div>

<h2 align="center">Other Backers and Sponsors</h2>

Before we started using OpenCollective, donations were made anonymously. Now that we have made the switch, we would like to acknowledge these sponsors (and the ones who continue to donate using OpenCollective). If we've missed someone, please send us a PR, and we'll add you to this list.

<div align="center">

<a href="https://angular.io/" target="_blank" title="JS framework"><img
src="https://cdn.worldvectorlogo.com/logos/angular-icon-1.svg" height="30" alt="Angular"></a>
<a href="https://moonmail.io" target="_blank" title="Email Marketing Software"><img
src="https://static.moonmail.io/moonmail-logo.svg" height="30" alt="MoonMail"></a>
<a href="https://monei.net" target="_blank" title="Best payment gateway rates"><img
src="https://static.monei.net/monei-logo.svg" height="30" alt="MONEI"></a>

</div>

<h2 align="center">Gold Sponsors</h2>

[Become a gold sponsor](https://opencollective.com/webpack#sponsor) and get your logo on our README on Github with a link to your site.

<div align="center">

<a href="https://opencollective.com/webpack/goldsponsor/0/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/0/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/1/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/1/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/2/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/2/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/3/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/3/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/4/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/4/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/5/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/5/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/6/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/6/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/7/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/7/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/8/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/8/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/9/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/9/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/10/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/10/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/11/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/11/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/12/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/12/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/13/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/13/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/14/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/14/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/15/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/15/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/16/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/16/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/17/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/17/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/18/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/18/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/19/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/19/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/20/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/20/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/21/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/21/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/22/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/22/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/23/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/23/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/24/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/24/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/25/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/25/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/26/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/26/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/27/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/27/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/28/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/28/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/goldsponsor/29/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/goldsponsor/29/avatar.svg?requireActive=false"></a>

</div>

<h2 align="center">Silver Sponsors</h2>

[Become a silver sponsor](https://opencollective.com/webpack#sponsor) and get your logo on our README on Github with a link to your site.

<div align="center">

<a href="https://opencollective.com/webpack/silversponsor/0/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/0/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/1/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/1/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/2/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/2/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/3/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/3/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/4/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/4/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/5/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/5/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/6/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/6/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/7/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/7/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/8/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/8/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/9/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/9/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/10/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/10/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/11/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/11/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/12/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/12/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/13/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/13/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/14/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/14/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/15/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/15/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/16/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/16/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/17/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/17/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/18/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/18/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/19/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/19/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/20/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/20/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/21/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/21/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/22/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/22/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/23/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/23/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/24/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/24/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/25/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/25/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/26/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/26/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/27/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/27/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/28/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/28/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/silversponsor/29/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/silversponsor/29/avatar.svg?requireActive=false"></a>

</div>

<h2 align="center">Bronze Sponsors</h2>

[Become a bronze sponsor](https://opencollective.com/webpack#sponsor) and get your logo on our README on Github with a link to your site.

<div align="center">

<a href="https://opencollective.com/webpack/sponsor/0/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/0/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/1/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/1/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/2/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/2/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/3/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/3/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/4/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/4/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/5/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/5/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/6/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/6/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/7/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/7/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/8/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/8/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/9/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/9/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/10/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/10/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/11/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/11/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/12/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/12/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/13/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/13/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/14/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/14/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/15/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/15/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/16/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/16/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/17/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/17/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/18/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/18/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/19/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/19/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/20/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/20/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/21/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/21/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/22/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/22/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/23/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/23/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/24/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/24/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/25/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/25/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/26/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/26/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/27/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/27/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/28/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/28/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/29/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/29/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/30/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/30/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/31/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/31/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/32/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/32/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/33/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/33/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/34/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/34/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/35/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/35/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/36/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/36/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/37/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/37/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/38/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/38/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/39/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/39/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/40/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/40/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/41/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/41/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/42/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/42/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/43/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/43/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/44/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/44/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/45/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/45/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/46/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/46/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/47/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/47/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/48/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/48/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/49/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/49/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/50/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/50/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/51/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/51/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/52/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/52/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/53/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/53/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/54/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/54/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/55/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/55/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/56/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/56/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/57/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/57/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/58/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/58/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/59/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/59/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/60/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/60/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/61/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/61/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/62/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/62/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/63/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/63/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/64/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/64/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/65/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/65/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/66/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/66/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/67/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/67/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/68/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/68/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/69/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/69/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/70/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/70/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/71/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/71/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/72/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/72/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/73/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/73/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/74/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/74/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/75/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/75/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/76/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/76/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/77/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/77/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/78/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/78/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/79/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/79/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/80/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/80/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/81/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/81/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/82/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/82/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/83/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/83/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/84/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/84/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/85/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/85/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/86/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/86/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/87/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/87/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/88/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/88/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/89/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/89/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/90/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/90/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/91/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/91/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/92/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/92/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/93/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/93/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/94/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/94/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/95/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/95/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/96/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/96/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/97/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/97/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/98/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/98/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/99/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/99/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/sponsor/100/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/sponsor/100/avatar.svg?requireActive=false"></a>

</div>

<h2 align="center">Backers</h2>

[Become a backer](https://opencollective.com/webpack#backer) and get your image on our README on Github with a link to your site.

<a href="https://opencollective.com/webpack/backer/0/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/0/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/1/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/1/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/2/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/2/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/3/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/3/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/4/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/4/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/5/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/5/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/6/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/6/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/7/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/7/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/8/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/8/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/9/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/9/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/10/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/10/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/11/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/11/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/12/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/12/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/13/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/13/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/14/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/14/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/15/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/15/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/16/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/16/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/17/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/17/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/18/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/18/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/19/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/19/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/20/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/20/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/21/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/21/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/22/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/22/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/23/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/23/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/24/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/24/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/25/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/25/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/26/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/26/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/27/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/27/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/28/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/28/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/29/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/29/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/30/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/30/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/31/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/31/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/32/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/32/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/33/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/33/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/34/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/34/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/35/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/35/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/36/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/36/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/37/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/37/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/38/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/38/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/39/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/39/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/40/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/40/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/41/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/41/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/42/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/42/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/43/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/43/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/44/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/44/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/45/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/45/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/46/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/46/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/47/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/47/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/48/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/48/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/49/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/49/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/50/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/50/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/51/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/51/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/52/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/52/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/53/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/53/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/54/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/54/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/55/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/55/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/56/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/56/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/57/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/57/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/58/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/58/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/59/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/59/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/60/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/60/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/61/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/61/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/62/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/62/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/63/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/63/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/64/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/64/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/65/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/65/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/66/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/66/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/67/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/67/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/68/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/68/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/69/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/69/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/70/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/70/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/71/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/71/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/72/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/72/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/73/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/73/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/74/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/74/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/75/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/75/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/76/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/76/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/77/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/77/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/78/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/78/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/79/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/79/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/80/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/80/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/81/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/81/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/82/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/82/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/83/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/83/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/84/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/84/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/85/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/85/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/86/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/86/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/87/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/87/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/88/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/88/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/89/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/89/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/90/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/90/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/91/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/91/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/92/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/92/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/93/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/93/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/94/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/94/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/95/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/95/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/96/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/96/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/97/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/97/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/98/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/98/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/99/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/99/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/webpack/backer/100/website?requireActive=false" target="_blank"><img src="https://opencollective.com/webpack/backer/100/avatar.svg?requireActive=false"></a>

<h2 align="center">Special Thanks to</h2>
<p align="center">(In chronological order)</p>

- [@google](https://github.com/google) for [Google Web Toolkit (GWT)](http://www.gwtproject.org/), which aims to compile Java to JavaScript. It features a similar [Code Splitting](http://www.gwtproject.org/doc/latest/DevGuideCodeSplitting.html) as webpack.
- [@medikoo](https://github.com/medikoo) for [modules-webmake](https://github.com/medikoo/modules-webmake), which is a similar project. webpack was born because I wanted Code Splitting for modules-webmake. Interestingly the [Code Splitting issue is still open](https://github.com/medikoo/modules-webmake/issues/7) (thanks also to @Phoscur for the discussion).
- [@substack](https://github.com/substack) for [browserify](https://browserify.org/), which is a similar project and source for many ideas.
- [@jrburke](https://github.com/jrburke) for [require.js](https://requirejs.org/), which is a similar project and source for many ideas.
- [@defunctzombie](https://github.com/defunctzombie) for the [browser-field spec](https://github.com/defunctzombie/package-browser-field-spec), which makes modules available for node.js, browserify and webpack.
- Every early webpack user, which contributed to webpack by writing issues or PRs. You influenced the direction...
- [@shama](https://github.com/shama), [@jhnns](https://github.com/jhnns) and [@sokra](https://github.com/sokra) for maintaining this project
- Everyone who has written a loader for webpack. You are the ecosystem...
- Everyone I forgot to mention here, but also influenced webpack.

[npm]: https://img.shields.io/npm/v/webpack.svg
[npm-url]: https://npmjs.com/package/webpack
[node]: https://img.shields.io/node/v/webpack.svg
[node-url]: https://nodejs.org
[deps]: https://img.shields.io/david/webpack/webpack.svg
[deps-url]: https://david-dm.org/webpack/webpack
[prs]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
[prs-url]: https://webpack.js.org/contribute/
[builds2]: https://dev.azure.com/webpack/webpack/_apis/build/status/webpack.webpack
[builds2-url]: https://dev.azure.com/webpack/webpack/_build/latest?definitionId=3
[licenses-url]: https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fwebpack%2Fwebpack?ref=badge_shield
[licenses]: https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fwebpack%2Fwebpack.svg?type=shield
[cover]: https://img.shields.io/coveralls/webpack/webpack.svg
[cover-url]: https://coveralls.io/r/webpack/webpack/

<p align="center">
  <a href="https://vuepress.vuejs.org/" target="_blank">
    <img width="180" src="https://raw.githubusercontent.com/vuejs/vuepress/master/packages/docs/docs/.vuepress/public/hero.png" alt="logo">
  </a>
</p>

<p align="center">
 <img src="https://img.shields.io/npm/dm/vuepress.svg" alt="Downloads"></a>
  <a href="https://www.npmjs.com/package/vuepress"><img src="https://img.shields.io/npm/v/vuepress.svg" alt="Version"></a>
  <a href="https://github.com/vuejs/vuepress/blob/master/LICENSE"><img src="https://img.shields.io/npm/l/vuepress.svg" alt="License"></a>
  <a href="https://discordapp.com/invite/HBherRA"><img src="https://img.shields.io/badge/Discord-join%20chat-738bd7.svg" alt="VuePress channel on Discord"></a>
</p>

## Status

> VuePress is now in maintenance mode. For a next-gen Vue-based SSG built on top of Vue 3 + Vite, check out [VitePress](https://vitepress.vuejs.org/).

## Documentation

Check out our docs at https://vuepress.vuejs.org/.

## Showcase

- [Awesome VuePress](https://github.com/vuepressjs/awesome-vuepress)
- [vuepress.tools](https://z3by.github.io/vuepress-tools/) (By [Ahmad Mostafa](https://ahmadmostafa.com))

## Contribution

Want to contribute? Check our [Contributing Guide](.github/CONTRIBUTING.md) and [issues for beginners](https://github.com/vuejs/vuepress/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22)!

```bash
yarn install # install all dependencies
yarn dev  # serves VuePress' own docs with itself
yarn test # make sure your code change pass the test
```

If you don't have a local checkout, you can also open [VuePress in Gitpod](https://gitpod.io/#https://github.com/vuejs/vuepress/blob/master/packages/docs/docs/README.md), a free online IDE for GitHub.

If you intend to make `"substantial"` changes to VuePress or its documentation, please checkout [VuePress RFCs](./rfcs/README.md).

If you have a VuePress-related project/component/tool, add it with a pull request to [this curated list](https://github.com/vuepressjs/awesome-vuepress)!

## Contributors

### Creator / Lead

<table>
  <td align="center"><a href="http://evanyou.me"><img src="https://avatars1.githubusercontent.com/u/499550?v=4" width="100px;" alt="Evan You"/><br /><sub><b>Evan You</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=yyx990803" title="Code">💻</a></td>
  <td align="center"><a href="https://github.com/ulivz"><img src="https://avatars1.githubusercontent.com/u/23133919?v=4" width="100px;" alt="ULIVZ"/><br /><sub><b>ULIVZ</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=ulivz" title="Code">💻</a> <a href="https://github.com/vuejs/vuepress/commits?author=ulivz" title="Documentation">📖</a></td>
</table>

### Active Core Team

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://billychin.netlify.com/"><img src="https://avatars0.githubusercontent.com/u/38957202?v=4" width="100px;" alt="Billyyyyy3320"/><br /><sub><b>Billyyyyy3320</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=newsbielt703" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/meteorlxy"><img src="https://avatars0.githubusercontent.com/u/18205362?s=400&v=4" width="100px;" alt="meteorlxy"/><br /><sub><b>meteorlxy</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=meteorlxy" title="Code">💻</a></td>
    <td align="center"><a href="https://twitter.com/CodesOfRa"><img src="https://avatars0.githubusercontent.com/u/945186?v=4" width="100px;" alt="Ramona"/><br /><sub><b>Ramona</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=CodesOfRa" title="Code">💻</a> <a href="https://github.com/vuejs/vuepress/commits?author=CodesOfRa" title="Documentation">📖</a></td>
    <td align="center"><a href="https://www.franck-abgrall.me/"><img src="https://avatars3.githubusercontent.com/u/9840435?v=4" width="100px;" alt="Franck Abgrall"/><br /><sub><b>Franck Abgrall</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=kefranabg" title="Code">💻</a> <a href="#question-kefranabg" title="Answering Questions">💬</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

### Core Team Emeriti

Here we honor some no-longer-active core team members who have made valuable contributions in the past.

<table>
  <tr>
    <td align="center"><a href="http://www.bencodezen.io"><img src="https://avatars0.githubusercontent.com/u/4836334?v=4" width="100px;" alt="Ben Hong"/><br /><sub><b>Ben Hong</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=bencodezen" title="Code">💻</a> <a href="https://github.com/vuejs/vuepress/commits?author=bencodezen" title="Documentation">📖</a> <a href="#question-bencodezen" title="Answering Questions">💬</a></td>
    <td align="center"><a href="https://github.com/f3ltron"><img src="https://avatars1.githubusercontent.com/u/11556276?v=4" width="100px;" alt="Giraud Florent"/><br /><sub><b>Giraud Florent</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=f3ltron" title="Code">💻</a></td>
    <td align="center"><a href="https://frontstuff.io/"><img src="https://avatars0.githubusercontent.com/u/5370675?v=4" width="100px;" alt="Sarah Dayan"/><br /><sub><b>Sarah Dayan</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=sarahdayan" title="Code">💻</a> <a href="https://github.com/vuejs/vuepress/commits?author=sarahdayan" title="Documentation">📖</a></td>
    <td align="center"><a href="https://twitter.com/_vinayak_k"><img src="https://avatars2.githubusercontent.com/u/19776877?v=4" width="100px;" alt="Vinayak Kulkarni"/><br /><sub><b>Vinayak Kulkarni</b></sub></a><br /><a href="#plugin-vinayakkulkarni" title="Plugin/utility libraries">🔌</a> <a href="https://github.com/vuejs/vuepress/commits?author=vinayakkulkarni" title="Code">💻</a> <a href="#blog-vinayakkulkarni" title="Blogposts">📝</a></td>
    <td align="center"><a href="https://twitter.com/vicbergquist"><img src="https://avatars0.githubusercontent.com/u/25737281?v=4" width="100px;" alt="Victoria Bergquist"/><br /><sub><b>Victoria Bergquist</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=vicbergquist" title="Code">💻</a> <a href="#design-vicbergquist" title="Design">🎨</a></td>
    <td align="center"><a href="https://sobolevn.me"><img src="https://avatars1.githubusercontent.com/u/4660275?v=4" width="100px;" alt="Nikita Sobolev"/><br /><sub><b>Nikita Sobolev</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=sobolevn" title="Code">💻</a> <a href="https://github.com/vuejs/vuepress/commits?author=sobolevn" title="Documentation">📖</a></td>
    <td align="center"><a href="https://fatihacet.com"><img src="https://avatars3.githubusercontent.com/u/712419?v=4" width="100px;" alt="Fatih Acet"/><br /><sub><b>Fatih Acet</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=fatihacet" title="Code">💻</a></td>
    <td align="center"><a href="http://farcaller.net/"><img src="https://avatars2.githubusercontent.com/u/693?v=4" width="100px;" alt="Vladimir Pouzanov"/><br /><sub><b>Vladimir Pouzanov</b></sub></a><br /><a href="https://github.com/vuejs/vuepress/commits?author=farcaller" title="Code">💻</a></td>
  </tr>

</table>

### Code Contributors

This project exists thanks to all the people who contribute. [[Contribute](.github/CONTRIBUTING.md)].
<a href="https://github.com/vuejs/vuepress/graphs/contributors"><img src="https://opencollective.com/vuepress/contributors.svg?width=890&button=false" /></a>

## License

[MIT](https://github.com/vuejs/vuepress/blob/master/LICENSE)

<p align="center">
  <a href="https://ant.design">
    <img width="200" src="https://gw.alipayobjects.com/zos/rmsportal/KDpgvguMpGfqaHPjicRK.svg">
  </a>
</p>

<h1 align="center">Ant Design</h1>

<div align="center">

An enterprise-class UI design language and React UI library.

[![CI status][github-action-image]][github-action-url] [![codecov][codecov-image]][codecov-url] [![NPM version][npm-image]][npm-url] [![NPM downloads][download-image]][download-url]

[![Renovate status][renovate-image]][renovate-dashboard-url] [![Total alerts][lgtm-image]][lgtm-url] [![][bundlesize-js-image]][unpkg-js-url] [![][bundlesize-css-image]][unpkg-css-url]

[![Follow Twitter][twitter-image]][twitter-url] [![FOSSA Status][fossa-image]][fossa-url] [![Discussions][discussions-image]][discussions-url] [![][issues-helper-image]][issues-helper-url] [![Issues need help][help-wanted-image]][help-wanted-url]

[npm-image]: http://img.shields.io/npm/v/antd.svg?style=flat-square
[npm-url]: http://npmjs.org/package/antd
[github-action-image]: https://github.com/ant-design/ant-design/workflows/%E2%9C%85%20test/badge.svg
[github-action-url]: https://github.com/ant-design/ant-design/actions?query=workflow%3A%22%E2%9C%85+test%22
[codecov-image]: https://img.shields.io/codecov/c/github/ant-design/ant-design/master.svg?style=flat-square
[codecov-url]: https://codecov.io/gh/ant-design/ant-design/branch/master
[download-image]: https://img.shields.io/npm/dm/antd.svg?style=flat-square
[download-url]: https://npmjs.org/package/antd
[lgtm-image]: https://flat.badgen.net/lgtm/alerts/g/ant-design/ant-design
[lgtm-url]: https://lgtm.com/projects/g/ant-design/ant-design/alerts/
[fossa-image]: https://app.fossa.io/api/projects/git%2Bgithub.com%2Fant-design%2Fant-design.svg?type=shield
[fossa-url]: https://app.fossa.io/projects/git%2Bgithub.com%2Fant-design%2Fant-design?ref=badge_shield
[help-wanted-image]: https://flat.badgen.net/github/label-issues/ant-design/ant-design/help%20wanted/open
[help-wanted-url]: https://github.com/ant-design/ant-design/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22
[twitter-image]: https://img.shields.io/twitter/follow/AntDesignUI.svg?label=Ant%20Design&style=social
[twitter-url]: https://twitter.com/AntDesignUI
[discussions-image]: https://img.shields.io/badge/discussions-on%20github-blue?style=flat-square
[discussions-url]: https://github.com/ant-design/ant-design/discussions
[bundlesize-js-image]: https://img.badgesize.io/https:/unpkg.com/antd/dist/antd.min.js?label=antd.min.js&compression=gzip&style=flat-square
[bundlesize-css-image]: https://img.badgesize.io/https:/unpkg.com/antd/dist/antd.min.css?label=antd.min.css&compression=gzip&style=flat-square
[unpkg-js-url]: https://unpkg.com/browse/antd/dist/antd.min.js
[unpkg-css-url]: https://unpkg.com/browse/antd/dist/antd.min.css
[issues-helper-image]: https://img.shields.io/badge/using-issues--helper-orange?style=flat-square
[issues-helper-url]: https://github.com/actions-cool/issues-helper
[renovate-image]: https://img.shields.io/badge/renovate-enabled-brightgreen.svg?style=flat-square
[renovate-dashboard-url]: https://github.com/ant-design/ant-design/issues/32498

</div>

[![](https://gw.alipayobjects.com/mdn/rms_08e378/afts/img/A*Yl83RJhUE7kAAAAAAAAAAABkARQnAQ)](https://ant.design)

English | [Português](./README-pt_BR.md) | [简体中文](./README-zh_CN.md) | [Українською](./README-uk_UA.md) | [Spanish](./README-sp_MX.md) | [日本語](./README-ja_JP.md)

## ✨ Features

- 🌈 Enterprise-class UI designed for web applications.
- 📦 A set of high-quality React components out of the box.
- 🛡 Written in TypeScript with predictable static types.
- ⚙️ Whole package of design resources and development tools.
- 🌍 Internationalization support for dozens of languages.
- 🎨 Powerful theme customization in every detail.

## 🖥 Environment Support

- Modern browsers and Internet Explorer 11 (with [polyfills](https://stackoverflow.com/questions/57020976/polyfills-in-2019-for-ie11))
- Server-side Rendering
- [Electron](https://www.electronjs.org/)

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/electron/electron_48x48.png" alt="Electron" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Electron |
| --- | --- | --- | --- | --- |
| IE11, Edge | last 2 versions | last 2 versions | last 2 versions | last 2 versions |

## 📦 Install

```bash
npm install antd
```

```bash
yarn add antd
```

## 🔨 Usage

```jsx
import { Button, DatePicker } from 'antd';

const App = () => (
  <>
    <Button type="primary">PRESS ME</Button>
    <DatePicker placeholder="select date" />
  </>
);
```

And import style manually:

```jsx
import 'antd/dist/antd.css'; // or 'antd/dist/antd.less'
```

### TypeScript

`antd` is written in TypeScript with complete definitions, check [Use in TypeScript](https://ant.design/docs/react/use-in-typescript) to get started.

## 🌍 Internationalization

Dozens of languages supported in `antd`, see [i18n](https://ant.design/docs/react/i18n).

## 🔗 Links

- [Home page](https://ant.design/)
- [Components Overview](https://ant.design/components/overview)
- [Ant Design Pro](http://pro.ant.design/)
- [Change Log](CHANGELOG.en-US.md)
- [rc-components](http://react-component.github.io/)
- [Mobile UI](http://mobile.ant.design)
- [Ant Design Pro Components](https://procomponents.ant.design)
- [Ant Design Charts](https://charts.ant.design)
- [Ant Design Icons](https://github.com/ant-design/ant-design-icons)
- [Ant Design Colors](https://github.com/ant-design/ant-design-colors)
- [Landing Pages](https://landing.ant.design)
- [Motion](https://motion.ant.design)
- [Scaffold Market](http://scaffold.ant.design)
- [Developer Instruction](https://github.com/ant-design/ant-design/wiki/Development)
- [Versioning Release Note](https://github.com/ant-design/ant-design/wiki/%E8%BD%AE%E5%80%BC%E8%A7%84%E5%88%99%E5%92%8C%E7%89%88%E6%9C%AC%E5%8F%91%E5%B8%83%E6%B5%81%E7%A8%8B)
- [FAQ](https://ant.design/docs/react/faq)
- [CodeSandbox Template](https://u.ant.design/codesandbox-repro) for bug reports
- [Customize Theme](https://ant.design/docs/react/customize-theme)
- [How to Apply for Being A Collaborator](https://github.com/ant-design/ant-design/wiki/Collaborators#how-to-apply-for-being-a-collaborator)

## ⌨️ Development

Use Gitpod, a free online dev environment for GitHub.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ant-design/ant-design)

Or clone locally:

```bash
$ git clone git@github.com:ant-design/ant-design.git
$ cd ant-design
$ npm install
$ npm start
```

Open your browser and visit http://127.0.0.1:8001 , see more at [Development](https://github.com/ant-design/ant-design/wiki/Development).

## 🤝 Contributing [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

Read our [contributing guide](https://ant.design/docs/react/contributing) and let's build a better antd together.

We welcome all contributions. Please read our [CONTRIBUTING.md](https://github.com/ant-design/ant-design/blob/master/.github/CONTRIBUTING.md) first. You can submit any ideas as [pull requests](https://github.com/ant-design/ant-design/pulls) or as [GitHub issues](https://github.com/ant-design/ant-design/issues). If you'd like to improve code, check out the [Development Instructions](https://github.com/ant-design/ant-design/wiki/Development) and have a good time! :)

If you are a collaborator, please follow our [Pull Request principle](https://github.com/ant-design/ant-design/wiki/PR-principle) to create a Pull Request with [collaborator template](https://github.com/ant-design/ant-design/compare?expand=1&template=collaborator.md).

[![Let's fund issues in this repository](https://issuehunt.io/static/embed/issuehunt-button-v1.svg)](https://issuehunt.io/repos/34526884)

## ❤️ Sponsors and Backers [![](https://opencollective.com/ant-design/tiers/sponsors/badge.svg?label=Sponsors&color=brightgreen)](https://opencollective.com/ant-design#support) [![](https://opencollective.com/ant-design/tiers/backers/badge.svg?label=Backers&color=brightgreen)](https://opencollective.com/ant-design#support)

[![](https://opencollective.com/ant-design/tiers/sponsors.svg?avatarHeight=36)](https://opencollective.com/ant-design#support)

[![](https://opencollective.com/ant-design/tiers/backers.svg?avatarHeight=36)](https://opencollective.com/ant-design#support)
