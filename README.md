# <img src="http://fsharp.org/img/logo/fsharp256.png" width="26"> Awesome Fable


> A community driven list of useful Fable tutorials, libraries and software.

Inspired by the [awesome](#more-awesome) list thing. Feel free to <a href="https://github.com/kunjee17/awesome-fable/blob/master/CONTRIBUTION.md" target="_blank">improve</a> this list.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://travis-ci.org/kunjee17/awesome-fable.svg?branch=master)](https://travis-ci.org/kunjee17/awesome-fable)


## Table of Contents
- [Awesome Fable](#awesome-fable)
    - [Core Fable Ecosystem](#core-fable-ecosystem)
    - [Tooling](#tooling)
    - [Learn Fable](#learn-fable)
    - [Libraries](#libraries)
    - [Components, Libraries, Utilities, and Toolkits](#components-libraries-utilities-and-toolkits)
    - [Showcase Applications](#showcase-applications)
    - [Elmish](#elmish)
    - [Bindings, Templates, and Samples](#bindings-templates-and-samples)
    - [Testing](#testing)
    - [Full-Stack F# with Fable](#full-stack)
    - [Support](#support)
    - [Built with Fable](#built-with-fable)
    - [Who to follow](#who-to-follow)
- [More awesome](#more-awesome)
- <a href="https://github.com/kunjee17/awesome-fable/blob/master/CONTRIBUTION.md" target="_blank">Contribution Guidelines</a>

## Core Fable Ecosystem

* [fable](https://github.com/fable-compiler/Fable) - the F#-to-JS transpiler itself!
* [ts2fable](https://github.com/fable-compiler/ts2fable) - Parses .t.ds Typescript Definition files and turns them into Fable bindings
* [fable-import](https://github.com/fable-compiler/fable-import) - Core fable bindings


## Tooling

* [Ionide][http://ionide.io/] - A [VS Code](https://code.visualstudio.com/) plugin for F#, built with Fable
* [fable-loader](https://www.npmjs.com/package/fable-loader) - Fable loader for Webpack
* [rollup-plugin-fable](https://www.npmjs.com/package/rollup-plugin-fable) - Fable plugin for Rollup
* [Online REPL](http://fable.io/repl) - The Fable Online REPL; execute F# in the browser
* [HTML to Elmish](https://mangelmaxime.github.io/html-to-elmish/) - Convert HTML snippets into code ready to be used in Elmish applications
* [F# Station](https://github.com/amieres/FSharpStation)

**[:arrow_up: back to top](#table-of-contents)**


## Learn Fable

[Official Documentation](http://fable.io/docs) — General information and in-depth guide with examples.

### FableConf - The Fable-Specific Conference

* [FableConf 2018](http://fable.io/fableconf/#home) - Source code [here](https://github.com/fable-compiler/fableconf)
* [Talks from FableConf 2017](https://www.youtube.com/watch?v=ssKX7T3lNvw&list=PL4vOF1DmOhsl8mXF8NkR_rgkVJP2nR4Mh)

### Talks

* [Official Fable youtube channel](https://www.youtube.com/channel/UC6m70Jyr65ogDySbK7aMmzg)
* [Fable Quick Start](https://www.youtube.com/watch?v=iP-50fj06Eo) on FSharp.tv
* [Conquer the JavaScript Ecosystem with F# and Fable](https://skillsmatter.com/skillscasts/9732-conquer-the-javascript-ecosystem-with-f-sharp-and-fable-audience-level-beginner) - A gentle introduction of Fable from creator _Alfonso Garcia-Caro_
* [Visualizing Olympic Medals with F# and Fable](https://www.youtube.com/watch?v=M9xk7KkSY1A) by Tomas Petricek
* [Full-Stack F# with Fable](https://www.youtube.com/watch?v=hf0gepgb0Dc) at DotNetConf
* [Modern App Development with Fable and React Native](https://www.youtube.com/watch?v=fmaPeUBWZuM) by Steffen Forkmann
* [Grappling the JS Ecosystem with F# and Fable](https://stachu.net/f-fable-talk-notes/) by Stachu Korick

### Blog Posts

* [Fable and Fable-Elmish Step-by-Step](https://medium.com/@zaid.naom/fable-and-fable-elmish-step-by-step-creating-a-calculator-fa2abe9594be) - Creating a Calculator using Fable-Elmish (**Fable 0.7**).
* [Getting Started with Fable Elmish](http://inchingforward.com/2017/03/getting-started-with-fable-elmish/) - Learn Elmish by working up to the Counter sample app from scratch (**Fable 0.7**).
* [Minimalistic Live Testing Fable Apps With QUnit](https://medium.com/@zaid.naom/minimalistic-live-testing-fable-apps-with-qunit-b9d9f2f64725)
* [F# Interop with Javascript in Fable: The Complete Guide](https://medium.com/@zaid.naom/f-interop-with-javascript-in-fable-the-complete-guide-ccc5b896a59f) - A comprehensive guide to Fable's interop capabilities
* [Introducing Fable.Remoting: Automated Type-Safe Client-Server Communication for Fable Apps](https://medium.com/@zaid.naom/introducing-fable-remoting-automated-type-safe-client-server-communication-for-fable-apps-e567454d594c)
* [Statically Typed Client-Server Communication with F#: Proof of Concept](https://medium.com/@zaid.naom/statically-typed-client-server-communication-with-f-proof-of-concept-7e52cff4a625#.upg5r1mah) - Joining F# Server and Client (outdated).
* [Early Fable Adventures – Building A Memory Tiles Game](http://www.prigrammer.com/?p=439) - Game of memory in F# using Fable DOM interactions and .Net events.
* [Fablelous Enterprise Tic-Tac-Toe](https://martinand.net/2017/05/10/fablelous-enterprise-tic-tac-toe/) - Web-based tic-tac-toe game written in F# and transpiled to JavaScript using Fable.
* [Fable from Scratch Series](https://medium.com/fable-compiler/fable-io-from-scratch-part-1-7ec7938c5026) - Bootstrap a Fable application from an empty directory to learn more about the stack.
* [Creating Visual Planetary Systems using Fable and F#](https://medium.com/@mukund.sharma92/creating-visual-planetary-systems-using-fable-and-f-de23415ca6f7)
* [Two Tetromino Tetris with Fable and F#](http://www.prigrammer.com/?p=489) - Implementation of a version of Tetris using Fable with the JS Canvas API and JS interval and .Net events for the game clock.
* [FableConf 2017, Elmish & Canvas based presentation](https://github.com/whitetigle/fableconf2017) - Learn how to create gorgeous Perlin based canvas animations and texts with Elmish and JS Events through a very simple example.
* [Learning about the F# SAFE stack - Suave.io, Azure, Fable, Elmish](https://www.hanselman.com/blog/LearningAboutTheFSAFEStackSuaveioAzureFableElmish.aspx) - High level introduction to the SAFE stack by Scott Hanselman.
* [A fable of Web MIDI](http://blog.pagansoft.de/articles/a-fable-of-webmidi) - An article about how to create Fable bindings for Web MIDI
* [Opinionated Fable - Architecture & Performance](http://kunjan.in/2018/03/opinionated-fable-architecture-and-performance/) - Architecture & Performance tips and tricks for Fable 1.x
* [Fable in React land](https://blog.vbfox.net/2018/02/06/fable-react-1-react-in-fable-land.html) - Fable for React: creating components and optimizing them

### Podcast Episodes

* [From F# to JavaScript and beyond with Fable](https://hanselminutes.com/616/from-f-to-javascript-and-beyond-with-fable-and-alfonso-garcia-caro) - with Alfonso Garcia-Caro on Scott Hanselman's "[Hanselminutes][Hanselminutes]" podcast
* [F# and the SAFE stack](https://hanselminutes.com/624/f-and-the-functional-safe-stack-with-krzysztof-cielak) - with Krzysztof Cieślak on Scott Hanselman's "[Hanselminutes][Hanselminutes]" podcast
* [WTF# is Fable?](https://wtfsharp.net/wtf-is-fable) - An overview of the Fable ecosystem on the [WTF#](https://wtfsharp.net) podcast.

**[:arrow_up: back to top](#table-of-contents)**


## Components, Libraries, Utilities, and Toolkits

*Frequently-used tools to be used with Fable itself*

* [Fulma](https://mangelmaxime.github.io/Fulma) - Fable-Elmish Bindings for the CSS framework [Bulma](https://bulma.io)
* [Fulma.Extensions](https://mangelmaxime.github.io/Fulma/#fulma-extensions) - Fable-React like DSL for Bulma extensions
* [Fulma.Elmish](https://github.com/MangelMaxime/Fulma/#fulma-elsmish) - Ready to use *elmish components*
* [Fable.PowerPack](https://github.com/fable-compiler/fable-powerpack) - Utilities for Fable apps
* [Fable.Remoting](https://github.com/Zaid-Ajaj/Fable.Remoting) - Typed Client-Server communication for Fable and Suave
* [Fable.Aether](https://github.com/Prolucid/fable-aether) - Optics library build for Fable
* [Fable.Mqtt](https://github.com/Prolucid/fable-mqtt) - Fable bindings for MqttJS
* [Elmish.Toastr](https://github.com/Zaid-Ajaj/Elmish.Toastr) - [Toastr](https://github.com/CodeSeven/toastr) (notification library) integration with Fable, implemented as Elmish commands
* [Fable.SqlClient](https://github.com/Zaid-Ajaj/Fable.SqlClient) - Fable Node client for Microsoft SQL Server, built around a node-mssql binding
* [Fable.SimpleJson](https://github.com/Zaid-Ajaj/Fable.SimpleJson) A library for easily working with JSON in Fable projects.
* [Fable.SimpleXml](https://github.com/Zaid-Ajaj/Fable.SimpleXml) A library for easily working with XML in Fable projects.
* [Fable.DateFunctions](https://github.com/Zaid-Ajaj/Fable.DateFunctions) - binding for the [date-fns](https://date-fns.org/) library, implemented as 120+ extension methods for DateTime. 
* [fable-signalr](https://github.com/Prolucid/fable-import-signalr) - Fable bindings for SignalR
* [fable-momentjs](https://github.com/Prolucid/fable-import-momentjs) - Fable bindings for momentjs
* [fable-moment-range](https://github.com/DmitryBatalov/fable-import-moment-range) - Fable bindings for momentjs range
* [fable-validation](https://github.com/zaaack/fable-validation) - A isomorphic validation library for F#/Fable
* [Thoth.Json](https://mangelmaxime.github.io/Thoth/) - Json encoder/decoder library inspired by Elm

**[:arrow_up: back to top](#table-of-contents)**


## Showcase Applications

*Production application that built with Fable*

* [The Gamma](https://thegamma.net/) - Tools for open data-driven storytelling
* [Payoff charts](http://www.payoffcharts.com/) - Shows you the profit of strategy in the dependency on the underlying movements
* [Casque Noir](https://www.casquenoir.com) - Web documentary about Haïti environmental issues 
* [Fable-of-the-Day](https://github.com/rommsen/fable-of-the-day) - Catch of the day by @wesbos ported to Fable
* [Czech Republic 2018 Election Analytics](http://showme.median.cz/volby-2018/)

**[:arrow_up: back to top](#table-of-contents)**


## Bindings, Templates, and Samples

*You can do **anything** with F#!*

### Basic Samples

* [Fable website](http://fable.io/samples.html) - Basic examples in official website.
* [Fable repo samples](https://github.com/fable-compiler/samples) - Fable's samples repository.
* [Browser Samples](https://github.com/fable-compiler/samples-browser)

### Electron

* [](https://github.com/fable-compiler/samples-electron)
* [](https://github.com/aolney/fable-template-electron)

### HTML5 Bindings

* [Fable.Import.WebMIDI](https://github.com/magicmonty/fable-import-webmidi) - Web MIDI bindings for Fable
* [fable-import-webmidi](https://github.com/magicmonty/fable-import-webmidi) - Bindings for WebMIDI
* [fable-webmidi-sample](https://github.com/magicmonty/fable-webmidi-sample) - Sample of WebMIDI usage in F#
* [fable-webaudio](https://github.com/JohnStov/fable-webaudio) - Bindings for WebAudio
* [fable-webmidi-sample](https://github.com/magicmonty/fable-webmidi-sample) - A simple sample for making a Web MIDI application with fable

### VS Code

* [fable-vscode](https://github.com/vasyl-purchel/fable-vscode)
* [fable-vscode-rollup-sample](https://github.com/inosik/fable-vscode-rollup-sample)
* [fable-vscode-demo](https://github.com/LambdaFactory/fable-vscode-demo)
* [vscode-extension-fable-simple](https://github.com/acormier/vscode-extension-fable-simple)

### React

* [](https://github.com/fable-compiler/fable-react)
* [](https://github.com/gstamac/fable-import-react-router-dom)
* [](https://github.com/gstamac/fable-import-react-md)
* [fable-react-grid-system](https://github.com/Prolucid/fable-react-grid-system) - Fable bindings for React Grid System
* [Fable.React.Flatpickr](https://zaid-ajaj.github.io/Fable.React.Flatpickr/) - Fable binding for [react-flatpickr](https://github.com/coderhaoxin/react-flatpickr) (datetime picker component) that is ready to use within Elmish applications
* [fable-react-toolbox](https://github.com/Prolucid/fable-react-toolbox) - UI components for fable-react

### Vue

* [](https://github.com/janno-p/fable-vue)
* [](https://github.com/lemonheadhs/FableVueSeed)
* [](https://github.com/janno-p/fable-vue-samples)
* [](http://fable.io/samples-browser/vue-todomvc/#/all)

### Authorization and Authentication

* [Auth0 Bindings](https://github.com/TinyBlueRobots/Fable.Auth0)


### Misc. Samples

* [device-scanner](https://github.com/intel-hpdd/device-scanner) - A Production Fable -> Node.js daemon for monitoring Linux storage devices. Has full testing + code coverage.
* [Volca FM editor](https://magicmonty.github.io/volca-fm-editor) - A Patch editor for the Korg Volca FM made with Fable-Elmish-React which uses Web MIDI

### Game Development

* [GameDevelopment Scaffold](https://github.com/realvictorprm/fable-game-scaffold) - Template to kick start a new dummy game. Based on the Fable Suave scaffold for Client <> Server support 
* [minesweeper](https://github.com/MecuSorin/minesweeper)
* [ConnectFour](https://github.com/jmmk/ConnectFour)
* [screeps_fable](https://github.com/ilmaestro/screeps_fable)
* [fsteroids](https://github.com/MiloszKrajewski/fsteroids)
* [memory-tiles](https://github.com/priort/memory-tiles)
* [Tetris](https://github.com/priort/Tetris)
* [fable-space-invaders](https://github.com/paytonrules/fable-space-invaders)
* [fable-pong](https://github.com/enerqi/fable-pong)

### Misc. Bindings and Templates

* [Fable.Parsimmon](https://github.com/Zaid-Ajaj/Fable.Parsimmon) - Fable bindings for the [Parsimmon](https://github.com/jneen/parsimmon) parser combinator library. 
* [](https://github.com/fable-compiler/fable-templates)
* [fable-import-sharepoint](https://github.com/hsharpsoftware/fable-import-sharepoint) - Bindings for SharePoint
* [fable-inferno](https://github.com/fable-compiler/fable-inferno) - Bindings and helpers for [inferno](https://infernojs.org/)
* [fable-dnn-scaffold](https://github.com/SCullman/fable-dnn-scaffold) - Full-stack DotNetNuke development sample
* [fable-import-chokidar](https://github.com/p69/fable-import-chokidar) - Bindings around [chokidar](https://github.com/paulmillr/chokidar)
* [](https://github.com/Prolucid/fable-mqtt)
* [](https://github.com/realvictorprm/fable-game-scaffold)
* [](https://github.com/TheAngryByrd/Fable.Template.Library)
* [](https://github.com/Zaid-Ajaj/fable-library-template)
* [](https://github.com/zaaack/fable-office-ui-fabric-react)
* [raspberry-fsharp](https://github.com/pkese/raspberry-fsharp) - full-stack IoT starter project for Raspberry Pi
* [alexa-fs](https://github.com/danielrbradley/alexa-fs) - Build Alexa apps with F#
* [fable-google-chrome-extension](https://github.com/DougBeney/fable-google-chrome-extension)





* [Fable.Library.Template](https://github.com/TheAngryByrd/Fable.Library.Template) - F# Template for create and publishing Fable Libraries

* [Fable + React Native](https://github.com/fable-compiler/fable-react_native-demo) - Full React Native app using Fable.
* [Fable + Fuse](https://github.com/alfonsogarciacaro/MyFuseApp) - Simple F# cross-platform mobile app based on [Fuse Tools](https://www.fusetools.com/) quickstart tutorial.
* [fable-electron](https://github.com/fable-compiler/fable-electron) - Learn how to write a cross-platorm desktop app in F# with Fable and Github Electron.
* [fable vscode](https://github.com/acormier/vscode-extension-fable-simple) - Basic Visual Studio Code 'Hello Word!' extension.
* [fable-uploadcare](https://whitetigle.github.io/fable-uploadcare/) - A simple React sample to use [UploadCare](https://uploadcare.com) widget

**[:arrow_up: back to top](#table-of-contents)**





## Elmish

*Power your Fable applications with a Model-View-Update architecture*

* [Elmish](https://elmish.github.io/elmish/) - Elm-like abstractions for F# apps 
* [fable-elmish](https://github.com/fable-elmish) - Find web app samples in fable-elmish repository list.
* [Official Elmish Docs](https://elmish.github.io/elmish/) - Official Elmish docs with nice samples and explanation of concepts
* [Elmish templates](https://github.com/fable-elmish/templates) - Templates to kick start a new Emish application.
  Install them like `dotnet new -i "Fable.Template.Elmish.React::*"` and create a project with `dotnet new fable-elmish-react -n myproject`
* [Fulma minimal template](https://mangelmaxime.github.io/Fulma/#template) - The quickest way to get started an Elmish + Fulma application from scratch
  
**[:arrow_up: back to top](#table-of-contents)**




## Testing

*Powering Client-Side testing with F#!*

* [Ava bindings](https://github.com/YoloDev/Fable.Ava) - Bindings for [Ava](https://github.com/avajs/ava)
* [](https://github.com/jgrund/jest-fable-preprocessor) - Bindings for [Jest](https://github.com/facebook/jest)
* [](https://github.com/jgrund/fable-template-jest) - Template for [Jest](https://github.com/facebook/jest)

**[:arrow_up: back to top](#table-of-contents)**


## Full-Stack F# with Fable

*Bindings, templates, and more repositories related to Full-Stack F# Web Development*

### The SAFE Stack (Saturn, Giraffe server-side)

* [Official SAFE-Stack Docs](https://safe-stack.github.io/docs/) - Official SAFE-Stack docs with nice samples and getting started tutorials. 
* [SAFE template](https://github.com/SAFE-Stack/SAFE-template) - Dotnet CLI template to bootstrap [SAFE](https://safe-stack.github.io/) projects, including [Suave.IO](https://suave.io/) on server side
* [SAFE Nightwatch](https://github.com/SAFE-Stack/SAFE-Nightwatch) - A Demo application for React Native development in F# using Fable and the SAFE stack.
* [SAFE Bookstore](https://github.com/SAFE-Stack/SAFE-BookStore) - Full stack SAFE example with support for deploying in a Docker container.
* [SAFE-Chat](https://github.com/SAFE-Stack/SAFE-Chat) - IRC-style chat demo featuring full-stack F#, Akka.Streams, Akkling, Fable, Elmish, Websockets and .NET Core.
* [SAFE Confplanner](https://github.com/SAFE-Stack/SAFE-ConfPlanner) - A Demo application showcasing shared behaviour of CQRS/Event-Sourcing on the backend and the Elm architecture on the frontend. Both systems communication with push-notifications via websockets.
* [SAFE TodoList](https://github.com/Zaid-Ajaj/SAFE-TodoList) - The simplest Todo app: a client-server application written entirely in F# using Elmish on the client, Suave on the server and Fable.Remoting for type-safe communication between the two.

### Suave

* [Fable Suave](https://github.com/fable-compiler/fable-suave-scaffold) - Scaffold to start an _isomorphic_ F# web app using Suave in the backend and Fable in the frontend, with canopy tests, best practices, etc.

### Node
* [Node 6 Bindings](https://github.com/jgrund/fable-node6) - Bindings for Node 6.x
* [Fable Express Sample](https://github.com/aolney/fable-express-sample)
* [Fable Express Elmish Scaffold](https://github.com/ntwilson/fable-express-elmish-scaffold)

### Fable.Remoting

* [Fable.Remoting](https://github.com/Zaid-Ajaj/Fable.Remoting)

### Websockets

* [Fable.Websockets](https://github.com/ncthbrt/Fable.Websockets) - Library to provide strongly-typed client/server communication between Fable and F# websocket servers
* [Fable.Websockets.Elmish](https://github.com/ncthbrt/Fable.Websockets.Elmish) - Library wrapping Fable.Websockets.Client to fit into the Elmish architecture
* [fable-import-ws](https://github.com/Prolucid/fable-import-ws) - Bindings for [ws](https://github.com/websockets/ws)

**[:arrow_up: back to top](#table-of-contents)**

## Support

*Where to find help.*

* [Gitter](https://gitter.im/fable-compiler/Fable) - Ask questions on fable gitter.
* [Slack](http://foundation.fsharp.org/join) - The fsharp.org slack channel has many fable users. Check out the #web channel!

**[:arrow_up: back to top](#table-of-contents)**


# Who to follow

* [Official Twitter Handle of Fable](https://twitter.com/FableCompiler)
* [Alfonso](http://twitter.com/alfonsogcnunez) - the creator of Fable!
* [F# Weekly](https://sergeytihon.com/) - for weekly F# news; frequently contains Fable content!

**[:arrow_up: back to top](#table-of-contents)**


# More Awesome

*Discover other amazingly awesome lists.*

Awesome Fable is just a part of awesome thing, get more here:

- <a href="https://github.com/sindresorhus/awesome" target="_blank">awesome</a> by [**@sindresorhus**](https://github.com/sindresorhus)
- <a href="https://github.com/bayandin/awesome-awesomeness" target="_blank">awesome-awesomeness</a> by [**@bayandin**](https://github.com/bayandin)
- <a href="https://github.com/fsprojects/awesome-fsharp" target="_blank">awesome-fsharp</a> by [**@fsprojects**](https://github.com/fsprojects)

**[:arrow_up: back to top](#table-of-contents)**


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@kunjee17](https://github.com/kunjee17) has waived all copyright and related or neighboring rights to this work.


[ionide]: http://ionide.io/
[Hanselminutes]: https://hanselminutes.com