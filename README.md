# <img src="http://fsharp.org/img/logo/fsharp256.png" width="26"> Awesome Fable


> A community driven list of useful Fable tutorials, libraries and software.

Inspired by the [awesome](#more-awesome) list thing. Feel free to <a href="https://github.com/kunjee17/awesome-fable/blob/master/CONTRIBUTION.md" target="_blank">improve</a> this list.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://travis-ci.org/kunjee17/awesome-fable.svg?branch=master)](https://travis-ci.org/kunjee17/awesome-fable)


## Table of Contents
- [Awesome Fable](#awesome-fable)
    - [Examples](#examples)
    - [Learn](#learn)
    - [Videos and podcasts](#videos-and-podcasts)
    - [Libraries](#libraries)
    - [Tools](#tools)
    - [Editor plugins](#editor-plugins)
    - [Templates](#templates)
    - [Support](#support)
    - [Built with Fable](#built-with-fable)
    - [Who to follow](#who-to-follow)
- [More awesome](#more-awesome)
- <a href="https://github.com/kunjee17/awesome-fable/blob/master/CONTRIBUTION.md" target="_blank">Contribution Guidelines</a>


## Examples

*Some good apps written in Fable.*

* [Fable website](http://fable.io/samples.html) - Basic examples in official website.
* [Fable repo samples](https://github.com/fable-compiler/Fable/tree/master/samples) - More examples in Fable's repository.
* [fable-elmish](https://github.com/fable-elmish) - Find web app samples in fable-elmish repository list.
* [Fable + React Native](https://github.com/fable-compiler/fable-react_native-demo) - Full React Native app using Fable.
* [Fable + Fuse](https://github.com/alfonsogarciacaro/MyFuseApp) - Simple F# cross-platform mobile app based on [Fuse Tools](https://www.fusetools.com/) quickstart tutorial.
* [fable-electron](https://github.com/fable-compiler/fable-electron) - Learn how to write a cross-platorm desktop app in F# with Fable and Github Electron.
* [fable vscode](https://github.com/acormier/vscode-extension-fable-simple) - Basic Visual Studio Code 'Hello Word!' extension.

**[:arrow_up: back to top](#table-of-contents)**


## Learn

*Learn what this awesome thing is.*

* [Official Docs](http://fable.io/docs.html) — General information and in-depth guide with examples.
* [Fable blog](http://fable.io/blog.html) — Official Fable blog with new version announcements.
* [F# Interop with Javascript in Fable: The Complete Guide](https://medium.com/@zaid.naom/f-interop-with-javascript-in-fable-the-complete-guide-ccc5b896a59f) - A comprehensive guide to Fable's interop capabilities
* [Statically Typed Client-Server Communication with F#: Proof of Concept](https://medium.com/@zaid.naom/statically-typed-client-server-communication-with-f-proof-of-concept-7e52cff4a625#.upg5r1mah) - Joining Server and Client using Reflection.
* [Fable and Fable-Elmish Step-by-Step](https://medium.com/@zaid.naom/fable-and-fable-elmish-step-by-step-creating-a-calculator-fa2abe9594be) - Creating a Calculator using Fable-Elmish (**Fable 0.7**).
* [Getting Started with Fable Elmish](http://inchingforward.com/2017/03/getting-started-with-fable-elmish/) - Learn Elmish by working up to the Counter sample app from scratch (**Fable 0.7**).
* [Early Fable Adventures – Building A Memory Tiles Game](http://www.prigrammer.com/?p=439) - Game of memory in F# using Fable DOM interactions and .Net events.
* [Fablelous Enterprise Tic-Tac-Toe](https://martinand.net/2017/05/10/fablelous-enterprise-tic-tac-toe/) - Web-based tic-tac-toe game written in F# and transpiled to JavaScript using Fable.

**[:arrow_up: back to top](#table-of-contents)**


## Videos and podcasts

*Watch great talks about Fable*

* [Conquer the JavaScript Ecosystem with F# and Fable](https://skillsmatter.com/skillscasts/9732-conquer-the-javascript-ecosystem-with-f-sharp-and-fable-audience-level-beginner) - A gentle introduction of Fable from creator _Alfonso Garcia-Caro_

**[:arrow_up: back to top](#table-of-contents)**


## Libraries

*Useful helpers to build apps.*

* [fable-core](https://www.npmjs.com/package/fable-core) - Fable Core Library
* [fable-powerpack](https://www.npmjs.com/package/fable-powerpack) - Utilities for Fable apps
* [fable-aether](https://github.com/Prolucid/fable-aether) - Optics library build for Fable
* [fable-mqtt](https://github.com/Prolucid/fable-mqtt) - Fable bindings for MqttJS
* [fable-signalr](https://github.com/Prolucid/fable-import-signalr) - Fable bindings for SignalR
* [fable-websockets](https://github.com/Prolucid/fable-import-ws) - Fable bindings for WS
* [fable-react-toolbox](https://github.com/Prolucid/fable-react-toolbox) - UI components for fable-react
* [fable-momentjs](https://github.com/Prolucid/fable-import-momentjs) - Fable bindings for momentjs
* [fable-react-grid-system](https://github.com/Prolucid/fable-react-grid-system) - Fable bindings for React Grid System

**[:arrow_up: back to top](#table-of-contents)**


## Tools

*Tools around Fable platform.*

* [fable-loader](https://www.npmjs.com/package/fable-loader) - Fable loader for Webpack
* [rollup-plugin-fable](https://www.npmjs.com/package/rollup-plugin-fable) - Fable plugin for Rollup
* [ts2fable](https://github.com/fable-compiler/ts2fable) - Fable parser for Typescript declaration files
* [Online REPL](http://fable.io/repl.html) - The Fable Online REPL


**[:arrow_up: back to top](#table-of-contents)**


## Editor plugins

*Tools to support Fable in code editors.*

* [ionide][ionide] - A wonderful Plugin for F# language.

**[:arrow_up: back to top](#table-of-contents)**


## Templates

*Fable templates to get up and running*

* [Elmish templates](https://github.com/fable-elmish/templates) - Templates to kick start a new Emish application.
  Install them like `dotnet new -i "Fable.Template.Elmish.React::*"` and create a project with `dotnet new fable-elmish-react -n myproject`
* [Fable Suave](https://github.com/fable-compiler/fable-suave-scaffold) - Scaffold to start an _isomorphic_ F# web app using Suave in the backend and Fable in the frontend, with canopy tests, best practices, etc.


**[:arrow_up: back to top](#table-of-contents)**


## Support

*Where to find help.*

* [Gitter](https://gitter.im/fable-compiler/Fable) - Ask questions on fable gitter.
* [Slack](http://foundation.fsharp.org/join) - Join Official FSharp.org and Slack channel.

**[:arrow_up: back to top](#table-of-contents)**


## Built with Fable

*Production application that built with Fable*

* [ionide][ionide] - VS Code and Atom extension for F# development
* [The Gamma](https://thegamma.net/) - Tools for open data-driven storytelling
* [Payoff charts](http://www.payoffcharts.com/) - Shows you the profit of strategy in the dependency on the underlying movements


# Who to follow

* [Official Twitter Handle of Fable](https://twitter.com/FableCompiler)
* [F# Weekly](https://sergeytihon.com/)

**[:arrow_up: back to top](#table-of-contents)**


# More awesome

*Discover other amazingly awesome lists.*

Awesome Fable is just a part of awesome thing, get more here:

- <a href="https://github.com/sindresorhus/awesome" target="_blank">awesome</a> by [**@sindresorhus**](https://github.com/sindresorhus)
- <a href="https://github.com/bayandin/awesome-awesomeness" target="_blank">awesome-awesomeness</a> by [**@bayandin**](https://github.com/bayandin)


**[:arrow_up: back to top](#table-of-contents)**


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@kunjee17](https://github.com/kunjee17) has waived all copyright and related or neighboring rights to this work.


[ionide]: http://ionide.io/
