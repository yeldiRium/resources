# collection of (un-)ordered internet resources

These are things that are or were of interest to me. No guarantee for existence or still sensible content. If something is in this list that does not mean that I recommend it or even have tested it. Some thing here are just for future reference.

# Table of Contents

1. [JavaScript](#JavaScript)
2. [Haskell](#Haskell)
3. [PureScript](#PureScript)
4. [APIs](#APIs)
5. [Infrastructure](#Infrastructure)
6. [Computer Science](#Computer-Science)
7. [Markdown](#Markdown)
8. [Databases](#Databases)
9. [Operating Systems / Computer Setup](#Operating-Systems--Computer-Setup)
10. [Web (Frontend)](#Web-Frontend)
11. [Editors](#Editors)
12. [Security](#Security)
13. [Selfhosted Web Services](#Selfhosted-Web-Services)
14. [Miscellaneous](#Miscellaneous)

# JavaScript

## Documentation

- [MDN Developer Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference) - Mozilla JavaScript reference.
- [Node.js Documentation Overview](https://nodejs.org/en/docs/) - List of all Node.js versions and their documentations.
- [Node.js Ecmascript Compatibility](https://node.green/)

## Functional Programming

- [Immutable](https://www.npmjs.com/package/immutable) - Collection of immutable data structures.
- [Ramda](https://www.npmjs.com/package/ramda) - Data-last, immutable utility function library.
  - [Ramda Documentation](https://ramdajs.com/docs/)
- [Fluture](https://www.npmjs.com/package/fluture) - Monadic alternative to Promises.

## State Management

- [Redux](https://www.npmjs.com/package/redux) - Immutable state management.
  - [Redux Watch](https://www.npmjs.com/package/redux-watch) - Watching of deep states in redux.
  - [Redux Thunk](https://www.npmjs.com/package/redux-thunk) - Thunks as actions.
  - [Redux Migrations](https://www.npmjs.com/package/@yeldirium/redux-migrations) - Migrations enhancer for persisted redux states.
  - [Redux Combine Getters](https://www.npmjs.com/package/@yeldirium/redux-combine-getters) - Combine getters similar to redux' `combineReducers`.

## Parsing / ASTs

- [UnifiedJS](https://github.com/unifiedjs/unified) - Interface backend for parser, transformer, stringifier ecosystem.
  - [remark](https://github.com/remarkjs/remark) - Markdown plugin.
- [vfile](https://github.com/vfile/vfile#vfileoptions) - Virtual file handling.
- [AST explorer](https://astexplorer.net)
- [jscodeshift](https://github.com/facebook/jscodeshift) - Runner for code refactoring scripts.
  - [js-codemod](https://github.com/cpojer/js-codemod/) - Collection of scripts for jscodeshift.

## Tools

- [Webpack](https://www.npmjs.com/package/webpack) - _The_ build tool for javascript. Plugin based source transformation.
  - [Webpack Concepts](https://webpack.js.org/concepts/)
- [ESLint](https://eslint.org) - Plugin based linter.
- [Prettier](https://prettier.io/) - Opinionated code formatter.
  - [Prettier Documentation](https://prettier.io/docs/en/index.html)
  - [Prettier on GitHub](https://github.com/prettier/prettier)
  - [ESLint Config Prettier](https://github.com/prettier/eslint-config-prettier) - Disables eslint formatting rules in favor of prettier.
  - [ESLint Plugin Prettier](https://github.com/prettier/eslint-plugin-prettier) - Integrates Prettier as formatter in ESLint.
- [Babel](https://babeljs.io) - Pligun based transpiler from JavaScript to JavaScript. For compatibility with older Interpreters.
- [Jake](https://www.npmjs.com/package/jake) - Make for JavaScript (comparable to rake for ruby).
- [Gulp](https://www.npmjs.com/package/gulp) - Streaming-based automation system.
- [Nexe](https://github.com/nexe/nexe) - Bundle js project and node into standalone executable binaries. JS API oriented.
- [Zeit Pkg](https://github.com/zeit/pkg) - Bundle js project and node into standalone executable binaries. CLI oriented.
- [semantic release](https://github.com/semantic-release/semantic-release) - A tool for automatic releases based on commit message conventions. Plugin based and flexible.
  - [semantic-release-changelog](https://github.com/semantic-release/changelog) - Update a changelog based on the released commits.
  - [semantic-release-docker](https://github.com/felixfbecker/semantic-release-docker) - Create a docker image with the release tag as docker tag.
  - [semantic-release-exec](https://github.com/semantic-release/exec) - Run custom scripts during the release.
  - [semantic-release-git](https://github.com/semantic-release/git) - Create a release commit with e.g. an updated package.json or a changelog.

## Server and Clients

- [Express](https://www.npmjs.com/package/express) - Http server and router.
  - [Morgan](https://www.npmjs.com/package/morgan) - Logger middleware.
  - [Body Parser](https://www.npmjs.com/package/body-parser) - Body parsing middleware for e.g. JSON.
- [WS](https://www.npmjs.com/package/ws) - Websocket client and server.
- [Node Fetch](https://www.npmjs.com/package/node-fetch) - Node implementation of [fetch api](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API).
- [Telegraf](https://www.npmjs.com/package/telegraf) - Telegram API client.

## Miscellaneous

- [is-url](https://www.npmjs.com/package/is-url) - Check whether a string is a url.
- [winston](https://github.com/winstonjs/winston) - Logging framework.
- [Commander](https://github.com/tj/commander.js) - CLI framework.
- [Enquirer](https://www.npmjs.com/package/enquirer) - Interactive CLI framework.

## Testing

- [Jest](https://jestjs.io) - Unit testing framework all in one. Good mocking.
  - [Jest Documentation](https://jestjs.io/docs/en/getting-started)
  - [Jest API Reference](https://jestjs.io)
  - [Jest Extended](https://github.com/jest-community/jest-extended) - Additional matchers for assertions.
  - [ESLint Plugin Jest](https://github.com/jest-community/eslint-plugin-jest) - Adds ESLint rules for Jest.
- [Supertest](https://github.com/visionmedia/supertest) - Http server testing tool.
- [Cucumber](https://github.com/cucumber/cucumber-js) - Integration testing framework based on Gherkin syntax.
  - [Gherkin](https://cucumber.io/docs/gherkin/reference/)
  - [Cucumber documentation](https://cucumber.io/docs/cucumber/)
  - npm packages
    - [cucumber](https://www.npmjs.com/package/cucumber)
    - [cucumber-pretty](https://www.npmjs.com/package/cucumber-pretty) - A pretty formatter.
    - [eslint-plugin-cucumber](https://www.npmjs.com/package/eslint-plugin-cucumber)

## Databases

### MinIO

- [Official Client Library](https://github.com/minio/minio-js)

### RabbitMQ

- [amqplib](https://www.npmjs.com/package/amqplib) - Most fully implemented client library.

### MongoDB

- [driver api overview](https://mongodb.github.io/node-mongodb-native/)

## third-party collections

- [Awesome Javascript](https://github.com/sorrycc/awesome-javascript)

# Haskell

- [Haskell Homepage](https://www.haskell.org)

## Libraries

- [Pandoc](https://pandoc.org/index.html) - Swiss army knife for markup format conversion and transformation.
- [SemVer](http://hackage.haskell.org/package/semver) - SemVer specification implementation.
- [time](http://hackage.haskell.org/package/time) - Time parsing and formatting.

## Documentation

- [Hackage](http://hackage.haskell.org/) - Haskell Package registry and documentation hub.
- [Haskell Wiki](https://wiki.haskell.org/Haskell)
- [Hoogle](https://hoogle.haskell.org) - Search engine for haskell functions.
- [Typeclass Hierarchy Wiki Page](https://wiki.haskell.org/Typeclassopedia)

## State Management

- [Lense](http://hackage.haskell.org/package/lens-4.17.1/docs/Control-Exception-Lens.html) - Complex data structure access.

## Content

- [Talk on Monad Transformers - Ben Kolera](https://www.youtube.com/watch?v=pzouxmWiemg&t=2221s)
- [Blogpost - Refactoring to a Monad Transformer Stack](https://thoughtbot.com/blog/refactoring-to-a-monad-transformer-stack)

# PureScript

- [PureScript Homepage](http://www.purescript.org)

## Documentation

- [Pursuit](https://pursuit.purescript.org) - PureScript package documentation database.
- [PureScript Language Reference](https://github.com/purescript/documentation/tree/master/language)

## Resources

- [PureScript by Example book](https://leanpub.com/purescript)

# APIs

## OpenAPI

- [Specification](https://github.com/OAI/OpenAPI-Specification)
- [Speccy](https://github.com/wework/speccy) - OpenAPI formatter and compiler.

## GraphQL

- [GraphQL Spec](http://spec.graphql.org/)
- [GraphQL Introduction](https://graphql.org/learn/)
- [The real power behind graphql and an architecture to leverage it](https://medium.com/@jdylanstewart/the-real-power-behind-graphql-and-an-architecture-to-leverage-it-7d1dd1004ada) - Blogpost about GraphQLs abilities.

# Infrastructure

## Provisioning

- [SaltStack Documentation](https://docs.saltstack.com/en/latest/)

- [SaltStack states for kubernetes setup](https://github.com/strangedev/saltstack-states)
  - [Pillar example](https://github.com/strangedev/saltstack-pillar-examples)
  - [Data example](https://github.com/strangedev/saltstack-data-examples)
  - These were made by a friend of mine and myself for our private server setup.

## Docker

- [Lazy Docker](https://github.com/jesseduffield/lazydocker) - CLI tool for docker management.

## Cloud

### Kubernetes

- [Kubernetes API Reference v1.14](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.14/)

## Tools

### Nextcloud

- [app store](https://apps.nextcloud.com/)
  - [calendar](https://apps.nextcloud.com/apps/calendar)
  - [contacts](https://apps.nextcloud.com/apps/contacts)
  - [polls](https://apps.nextcloud.com/apps/polls)
  - [mail client](https://apps.nextcloud.com/apps/mail)
  - [tasks](https://apps.nextcloud.com/apps/tasks)
  - [notes](https://apps.nextcloud.com/apps/notes)
  - [pride 🏳️‍🌈](https://apps.nextcloud.com/apps/pride)
  - For larger user groups or companies (untested, just for future reference):
    - [announcements](https://apps.nextcloud.com/apps/announcementcenter) - Lets admins send announcement to users.
    - [only office](https://apps.nextcloud.com/apps/onlyoffice)
    - [deck](https://apps.nextcloud.com/apps/deck) - Kanban-style organization tool.
    - [spreed.me](https://apps.nextcloud.com/apps/spreedme) - Video/audio/text chat.
    - [external sites](https://apps.nextcloud.com/apps/external) - Integrate external links into navigation.
    - [nextant](https://apps.nextcloud.com/apps/nextant) - Solr search for cloud content.
    - [phone tracker](https://apps.nextcloud.com/apps/phonetrack)
    - [gluu openid connect](https://apps.nextcloud.com/apps/gluusso)
    - [sso & saml](https://apps.nextcloud.com/apps/user_saml)
    - [news](https://apps.nextcloud.com/apps/news) - RSS reader.
- v17
  - [developer documentation](https://docs.nextcloud.com/server/17/developer_manual/)

# Computer Science

## Algorithms

- [Complexity Cheat Sheet](https://www.bigocheatsheet.com) - Overview of algorithms and data structures and the complexities of their operations.
- [Algolist](http://www.algolist.net) - Algorithms and Data Structures with Java and C++ implementations.

## Mathematics

- [Wolfram|Alpha](https://www.wolframalpha.com) - Computational Intelligence. Impressive "Calculator".
- [TKS.AL](http://www.tks.informatik.uni-frankfurt.de/formelchecker/AL.php?inputhelp=off&formel=%28x+%2F%5C+y%29) - Boolean expression analyser.

# Markdown

- [GitHub-flavored Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [CommonMark](https://commonmark.org) - Strong specification for markdown with unambiguous syntax.

# Databases

## MinIO

- [MinIO Docker Image](https://hub.docker.com/r/minio/minio)
- [MinIO Docker Readme](https://github.com/minio/minio/blob/master/docs/docker/README.md)

## RabbitMQ

- [RabbitMQ Docker Image](https://hub.docker.com/_/rabbitmq)
- [RabbitMQ Docker Documentation](https://docs.docker.com/samples/library/rabbitmq/)

## SQL

- [SQLite Syntax Diagrams](https://www.sqlite.org/syntaxdiagrams.html)

# Operating Systems / Computer Setup

## Manjaro

- [My setup guide](https://github.com/yeldiRium/configs/blob/manjaro/manjaro.md) - Tailored to my own needs.

## Arch Linux

- [Arch Linux Wiki](https://wiki.archlinux.org)
- [Arch User Repository](https://aur.archlinux.org) - User maintained package repository.

## Window Manager

- [i3](https://i3wm.org) - Tiling window manager. The best (I've used so far).
  - [i3 user guide](https://i3wm.org/docs/userguide.html)

# Web (Frontend)

## Frameworks

- [Hexo](https://hexo.io/) - A cli and markdown based blog engine.

## CSS

### Guides

- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### Frameworks

- [Tailwind CSS](https://tailwindcss.com) - Utility framework for postCSS. Cool concepts for building blocks.
- [FontAwesome](https://fontawesome.com/icons?from=io) - Collection of free symbols.
- [Hamburgers](https://jonsuh.com/hamburgers/) - Hamburger icons and animations.

# Editors

## VSCode

### Plugins

- [Advanced New File](https://marketplace.visualstudio.com/items?itemName=dkundel.vscode-new-file) - Create new file at path instead of unnamed and then saving it.
- [Center Editor Window](https://marketplace.visualstudio.com/items?itemName=kaiwood.center-editor-window) - Provides command to center editor on cursor.
- [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools) - GUI for kubernetes cluster interaction.
- [Swagger Viewer](https://marketplace.visualstudio.com/items?itemName=Arjun.swagger-viewer) - Preview OpenAPI specs with swagger in VSCode.
- [VSCode PDF](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf) - Inline PDF viewer.

#### PureScript

- [PureScript Language Support](https://marketplace.visualstudio.com/items?itemName=nwolverson.language-purescript) - Syntax Highlighting.
- [PureScript IDE](https://marketplace.visualstudio.com/items?itemName=nwolverson.ide-purescript) - Language Server integration. Needs installed [language server](https://github.com/nwolverson/purescript-language-server).
- [VSCode Purty](https://marketplace.visualstudio.com/items?itemName=mvakula.vscode-purty) - Purty integration.

#### Haskell

- [Simple GHC Integration](https://marketplace.visualstudio.com/items?itemName=dramforever.vscode-ghc-simple) - Basic code analysis.
- [Haskell Linter](https://marketplace.visualstudio.com/items?itemName=hoovercj.haskell-linter)
- [Haskell Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=justusadam.language-haskell)
- [Haskell Language Server](https://marketplace.visualstudio.com/items?itemName=alanz.vscode-hie-server) - Needs the [Haskell language server] to be installed.
- [Haskell Code Formatter](https://marketplace.visualstudio.com/items?itemName=sergey-kintsel.haskell-formatter-vscode-extension)

## Emacs

- [My config](https://github.com/yeldiRium/configs/blob/manjaro/emacs.org)

## Vim

- [Vim Documentation](http://vimdoc.sourceforge.net/htmldoc/visual.html)

# Security

- [OWASP](https://www.owasp.org/index.php/Main_Page) - Open Web Application Security Project.

## GPG and OpenPGP

- [Anatomy of a GPG key](https://davesteele.github.io/gpg/2014/09/20/anatomy-of-a-gpg-key/) - Blogpost GPG key backgrounds.
- [Yubikey Guide](https://github.com/drduh/YubiKey-Guide) - Complete GPG and SSH guide using a YubiKey. Just as relevant without one.

# Selfhosted Web Services

- [Talk](https://github.com/coralproject/talk) - An open source commenting platform by the [coral project](https://docs.coralproject.net/talk/).

# Miscellaneous

## Browser Plugins (Chrome)

- [OctoLinker](https://github.com/OctoLinker/OctoLinker) - Enhances GitHub code viewer by linking requires etc.

## Resources

- [Free Programming Books](https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books.md)
- [SED Tutorial](http://www.grymoire.com/Unix/Sed.html)
- [Awesome](https://github.com/sindresorhus/awesome) - List of various awesome stuff.
- [TIL](https://github.com/jbranchaud/til) - List of collected learnings.
- [Terminal Color Scheme Generator](https://terminal.sexy)

## Tools

- [Ultimate Plumber](https://github.com/akavel/up) - Linux pipeline tool with live preview.
- [JSON Placeholder](https://jsonplaceholder.typicode.com) - JSON Api for testing and prototyping.
- [JSON Formatter](https://jsonformatter.curiousconcept.com)
- [Lorem Ipsum Generator](https://lipsum.com/feed/html)
- [Lorem Pixel](http://lorempixel.com/) - Image placeholder generator.
- [RegEx101](https://regex101.com) - RegEx tester and debugger.
