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

* [elmish](https://github.com/elmish) - Find web app samples in elmish repository list.
* [SAFE Bookstore](https://github.com/SAFE-Stack/SAFE-BookStore) - Full stack SAFE example with support for deploying in a Docker container.
* [SAFE-Chat](https://github.com/SAFE-Stack/SAFE-Chat) - IRC-style chat demo featuring full-stack F#, Akka.Streams, Akkling, Fable, Elmish, Websockets and .NET Core.
* [SAFE Nightwatch](https://github.com/SAFE-Stack/SAFE-Nightwatch) - A Demo application for React Native development in F# using Fable and the SAFE stack.
* [SAFE Confplanner](https://github.com/SAFE-Stack/SAFE-ConfPlanner) - A Demo application showcasing shared behaviour of CQRS/Event-Sourcing on the backend and the Elm architecture on the frontend. Both systems communication with push-notifications via websockets.
* [tabula-rasa](https://github.com/Zaid-Ajaj/tabula-rasa) - Minimalistic real-worldish blogging platform, written entirely in F#, made as a learning reference for building large Elmish apps
* [SAFE TodoList](https://github.com/Zaid-Ajaj/SAFE-TodoList) - The simplest Todo app: a client-server application written entirely in F# using Elmish on the client, Suave on the server and Fable.Remoting for type-safe communication between the two.
* [Fable-Elmish-Electron-Material-UI demo](https://github.com/cmeeren/fable-elmish-electron-material-ui-demo) - Complete boilerplate for Electron apps using Fable 2 and Elmish with hot module reloading, time-travel debugging, etc. Also demoes how to implement some non-trivial UX patterns in Elmish, as well as how to use Material-UI with JSS (styles as code).
* [device-scanner](https://github.com/intel-hpdd/device-scanner) - A Production Fable -> Node.js daemon for monitoring Linux storage devices. Has full testing + code coverage.
* [Volca FM editor](https://magicmonty.github.io/volca-fm-editor) - A Patch editor for the Korg Volca FM made with Fable-Elmish-React which uses Web MIDI
* [fable-webmidi-sample](https://github.com/magicmonty/fable-webmidi-sample) - A simple sample for making a Web MIDI application with fable
* [fable-uploadcare](https://whitetigle.github.io/fable-uploadcare/) - A simple React sample to use [UploadCare](https://uploadcare.com) widget
* [bulma-timepicker](https://github.com/rfrerebe/fable2-samples/tree/master/minimal) - A simple timepicker using Bulma in an F# React component + how to use this React component in Elmish.

**[:arrow_up: back to top](#table-of-contents)**


## Learn

*Learn what this awesome thing is.*

* [Official Docs](http://fable.io/docs) — General information and in-depth guide with examples.
* [Official SAFE-Stack Docs](https://safe-stack.github.io/docs/) - Official SAFE-Stack docs with nice samples and getting started tutorials.
* [Official Elmish Docs](https://elmish.github.io/elmish/) - Official Elmish docs with nice samples and explanation of concepts
<!--* [Fable blog]() — Official Fable blog with new version announcements.-->
* [Minimalistic Live Testing Fable Apps With QUnit](https://medium.com/@zaid.naom/minimalistic-live-testing-fable-apps-with-qunit-b9d9f2f64725)
* [F# Interop with Javascript in Fable: The Complete Guide](https://medium.com/@zaid.naom/f-interop-with-javascript-in-fable-the-complete-guide-ccc5b896a59f) - A comprehensive guide to Fable's interop capabilities
* [Introducing Fable.Remoting: Automated Type-Safe Client-Server Communication for Fable Apps](https://medium.com/@zaid.naom/introducing-fable-remoting-automated-type-safe-client-server-communication-for-fable-apps-e567454d594c)
* [Statically Typed Client-Server Communication with F#: Proof of Concept](https://medium.com/@zaid.naom/statically-typed-client-server-communication-with-f-proof-of-concept-7e52cff4a625#.upg5r1mah) - Joining F# Server and Client (outdated).
* [Fable and Fable-Elmish Step-by-Step](https://medium.com/@zaid.naom/fable-and-fable-elmish-step-by-step-creating-a-calculator-fa2abe9594be) - Creating a Calculator using Fable-Elmish (**Fable 0.7**).
* [Getting Started with Fable Elmish](http://inchingforward.com/2017/03/getting-started-with-fable-elmish/) - Learn Elmish by working up to the Counter sample app from scratch (**Fable 0.7**).
* [Fablelous Enterprise Tic-Tac-Toe](https://martinand.net/2017/05/10/fablelous-enterprise-tic-tac-toe/) - Web-based tic-tac-toe game written in F# and transpiled to JavaScript using Fable.
* [Fable from Scratch Series](https://medium.com/fable-compiler/fable-io-from-scratch-part-1-7ec7938c5026) - Bootstrap a Fable application from an empty directory to learn more about the stack.
* [Creating Visual Planetary Systems using Fable and F#](https://medium.com/@mukund.sharma92/creating-visual-planetary-systems-using-fable-and-f-de23415ca6f7)
* [FableConf 2017, Elmish & Canvas based presentation](https://github.com/whitetigle/fableconf2017) - Learn how to create gorgeous Perlin based canvas animations and texts with Elmish and JS Events through a very simple example.
* [Learning about the F# SAFE stack - Suave.io, Azure, Fable, Elmish](https://www.hanselman.com/blog/LearningAboutTheFSAFEStackSuaveioAzureFableElmish.aspx) - High level introduction to the SAFE stack by Scott Hanselman.
* [A fable of Web MIDI](http://blog.pagansoft.de/articles/a-fable-of-webmidi) - An article about how to create Fable bindings for Web MIDI
* [Opinionated Fable - Architecture & Performance](http://kunjan.in/2018/03/opinionated-fable-architecture-and-performance/) - Architecture & Performance tips and tricks for Fable 1.x
* [Fable in React land](https://blog.vbfox.net/2018/02/06/fable-react-1-react-in-fable-land.html) - Fable for React: creating components and optimizing them
* [Create WebComponents with Fable + Elmish + React](http://hardt.software/building-a-webcomponent-with-fable-elmish-react/) - How to create WebComponents with Fable + Elmish + React
* [Even more interop with Fable](https://medium.com/@whitetigle/even-more-interop-with-fable-7afb0e8db5b4) - How to use Bcrypt Js library with Fable - Dec 2018
* [Fable interop 101 : generate-password](https://medium.com/@whitetigle/fable-interop-101-generate-password-8ee21f56978e) - How to use generate-password Js library with Fable - Jan 2019

**[:arrow_up: back to top](#table-of-contents)**


## Videos and podcasts

*Watch great talks about Fable*

* [Official Fable youtube channel](https://www.youtube.com/channel/UC6m70Jyr65ogDySbK7aMmzg)
    * [FableConf 2018 videos playlist](https://www.youtube.com/watch?v=Ry4qQxU0380&list=PL4vOF1DmOhsmzsCd1ghrey7sASjOngnOt) - All FableConf 2018 videos
    * [FableConf 2017 videos playlist](https://www.youtube.com/watch?v=ssKX7T3lNvw&list=PL4vOF1DmOhsl8mXF8NkR_rgkVJP2nR4Mh) - All FableConf 2017 videos
    * [Fable conference talks videos playlist](https://www.youtube.com/watch?v=iP-50fj06Eo&list=PL4vOF1DmOhsnIq6db_j3jv29HoatR4G-Q) - Other Fable talks on Youtube
* [Conquer the JavaScript Ecosystem with F# and Fable](https://skillsmatter.com/skillscasts/9732-conquer-the-javascript-ecosystem-with-f-sharp-and-fable-audience-level-beginner) - A gentle introduction of Fable from creator _Alfonso Garcia-Caro_
* [WTF# is Fable?](https://wtfsharp.net/wtf-is-fable) - An overview of the Fable ecosystem on the [WTF#](https://wtfsharp.net) podcast.
* [From F# to JavaScript and beyond with Fable](https://hanselminutes.com/616/from-f-to-javascript-and-beyond-with-fable-and-alfonso-garcia-caro) - with Alfonso Garcia-Caro on Scott Hanselman's "[Hanselminutes][Hanselminutes]" podcast
* [F# and the SAFE stack](https://hanselminutes.com/624/f-and-the-functional-safe-stack-with-krzysztof-cielak) - with Krzysztof Cieślak on Scott Hanselman's "[Hanselminutes][Hanselminutes]" podcast

**[:arrow_up: back to top](#table-of-contents)**


## Libraries

*Useful helpers to build apps.*

* [Elmish](https://elmish.github.io/elmish/) - Elm-like abstractions for F# apps
* [Elmish.Bridge](https://github.com/Nhowka/Elmish.Bridge) - Create client-server Fable-Elmish apps keeping a single mindset
* [Fable.Fetch](https://github.com/fable-compiler/fable-fetch) - Fable bindings for Browsers' Fetch API.
* [Fable.Promise](https://github.com/fable-compiler/fable-promise) - Fable bindings for JS promise.
* [Fable.Date](https://github.com/fable-compiler/fable-date) - Fable bindings for working with Dates.
* [Fable.Remoting](https://github.com/Zaid-Ajaj/Fable.Remoting) - Typed RPC client-server communication for Fable and .NET
* [Fable.Aether](https://github.com/Prolucid/fable-aether) - Optics library build for Fable
* [Fable.Mqtt](https://github.com/Prolucid/fable-mqtt) - Fable bindings for MqttJS
* [Fable.Mocha](https://github.com/Zaid-Ajaj/Fable.Mocha) - Fable testing library with mocha. Works in browser without any dependency.
* [Fable.Jest](https://github.com/jgrund/fable-jest) - Testing Fable apps with [Jest](https://facebook.github.io/jest/)
* [Fable.Ava](https://github.com/YoloDev/Fable.Ava) - Testing Fable apps with [Ava](https://github.com/avajs/ava)
* [Elmish.SweetAlert](https://github.com/Zaid-Ajaj/Elmish.SweetAlert) - [sweetalert2](https://sweetalert2.github.io/) integration in Fable, implmeneted as Elmish commands, see [live docs](https://zaid-ajaj.github.io/Elmish.SweetAlert/).
* [Elmish.Toastr](https://github.com/Zaid-Ajaj/Elmish.Toastr) - [Toastr](https://github.com/CodeSeven/toastr) (notification library) integration with Fable, implemented as Elmish commands
* [Elmish.AnimatedTree](https://github.com/Zaid-Ajaj/Elmish.AnimatedTree) - A tree component built on top of react-animated-tree ready to use from Elmish applications.
* [Fable.SqlClient](https://github.com/Zaid-Ajaj/Fable.SqlClient) - Fable Node client for Microsoft SQL Server, built around a node-mssql binding
* [Fable.React.Flatpickr](https://zaid-ajaj.github.io/Fable.React.Flatpickr/) - Fable binding for [react-flatpickr](https://github.com/coderhaoxin/react-flatpickr) (datetime picker component) that is ready to use within Elmish applications
* [Fable.Parsimmon](https://github.com/Zaid-Ajaj/Fable.Parsimmon) - Fable bindings for the [Parsimmon](https://github.com/jneen/parsimmon) parser combinator library.
* [Fable.SimpleJson](https://github.com/Zaid-Ajaj/Fable.SimpleJson) A library for easily working with JSON in Fable projects.
* [Fable.SimpleXml](https://github.com/Zaid-Ajaj/Fable.SimpleXml) A library for easily working with XML in Fable projects.
* [Fable.DateFunctions](https://github.com/Zaid-Ajaj/Fable.DateFunctions) - binding for the [date-fns](https://date-fns.org/) library, implemented as 120+ extension methods for DateTime.
* [fable-signalr](https://github.com/Prolucid/fable-import-signalr) - Fable bindings for SignalR
* [fable-websockets](https://github.com/Prolucid/fable-import-ws) - Fable bindings for WS
* [fable-react-toolbox](https://github.com/Prolucid/fable-react-toolbox) - UI components for fable-react
* [fable-momentjs](https://github.com/Prolucid/fable-import-momentjs) - Fable bindings for momentjs
* [fable-moment-range](https://github.com/DmitryBatalov/fable-import-moment-range) - Fable bindings for momentjs range
* [fable-react-grid-system](https://github.com/Prolucid/fable-react-grid-system) - Fable bindings for React Grid System
* [Fulma](https://mangelmaxime.github.io/Fulma/#fulma) - Fable-React like DSL for Bulma
* [Fulma.Extensions](https://mangelmaxime.github.io/Fulma/#fulma-extensions) - Fable-React like DSL for Bulma extensions
* [Fulma.Elmish](https://github.com/MangelMaxime/Fulma/#fulma-elmish) - Ready to use *elmish components*
* [fable-validation](https://github.com/zaaack/fable-validation) - A isomorphic validation library for F#/Fable
* [Fable.Import.WebMIDI](https://github.com/magicmonty/fable-import-webmidi) - Web MIDI bindings for Fable
* [Thoth.Json](https://mangelmaxime.github.io/Thoth/) - Json encoder/decoder library inspire by Elm
* [fable-material-ui](https://github.com/mvsmal/fable-material-ui) - Fable bindings for [MaterialUI](https://material-ui.com)
* [Fable Linq](https://github.com/bigteech/fable-linq) - QueryBuilder for Fable
* [FSharp.Control.AsyncRx](https://elmish-streams.readthedocs.io/en/latest/asyncrx/index.html) - Async Reactive (Rx) for F# and Fable
* [Elmish.Streams](http://elmish-streams.rtfd.io/) - Extends Elmish with reactive ([AsyncRx](https://elmish-streams.readthedocs.io/en/latest/asyncrx/index.html)) query capabilities

**[:arrow_up: back to top](#table-of-contents)**


## Tools

*Tools around Fable platform.*

* [fable-loader](https://www.npmjs.com/package/fable-loader) - Fable loader for Webpack
* [rollup-plugin-fable](https://www.npmjs.com/package/rollup-plugin-fable) - Fable plugin for Rollup
* [ts2fable](https://github.com/fable-compiler/ts2fable) - Fable parser for Typescript declaration files
* [Online REPL](http://fable.io/repl) - The Fable Online REPL
* [HTML to Elmish](https://mangelmaxime.github.io/html-to-elmish/) - Convert HTML snippets into code ready to be used in Elmish apps
* [JSON to Thoth](https://nojaf.com/redhood/) - Convert JSON to F# code with Thoth decoders.


**[:arrow_up: back to top](#table-of-contents)**


## Editors

*Editors to code with F#.*

* [Ionide][ionide] - A wonderful Visual Studio Code extension for F# language.
* [Visual Studio](https://visualstudio.microsoft.com/)
* [JetBrains Rider](https://www.jetbrains.com/rider/)

**[:arrow_up: back to top](#table-of-contents)**


## Templates

*Fable templates to get up and running*

* [Elmish templates](https://github.com/fable-elmish/templates) - Templates to kick start a new Elmish application.
  Install them like `dotnet new -i "Fable.Template.Elmish.React::*"` and create a project with `dotnet new fable-elmish-react -n myproject`
* [SAFE template](https://github.com/SAFE-Stack/SAFE-template) - Dotnet CLI template to bootstrap [SAFE](https://safe-stack.github.io/) projects, including [Suave.IO](https://suave.io/) on server side
* [Fulma minimal template](https://mangelmaxime.github.io/Fulma/#template) - The quickest way to get started an Elmish + Fulma application from scratch
* [Fable.Library.Template](https://github.com/TheAngryByrd/Fable.Library.Template) - F# Template for create and publishing Fable Libraries

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
* [Casque Noir](http://www.casquenoir.com) - Web documentary about Haïti environmental issues
* [Fable-of-the-Day](https://github.com/rommsen/fable-of-the-day) - Catch of the day by @wesbos ported to Fable
* [Czech Republic 2018 Election Analytics](http://showme.median.cz/volby-2018/)

# Who to follow

* [Official Twitter Handle of Fable](https://twitter.com/FableCompiler)
* [F# Weekly](https://sergeytihon.com/)

**[:arrow_up: back to top](#table-of-contents)**


# More awesome

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
