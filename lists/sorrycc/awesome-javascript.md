---
layout: default
title: Awesome Rank for sorrycc/awesome-javascript
---

<p align="center">
	This list is a copy of <a href="https://github.com/sorrycc/awesome-javascript">sorrycc/awesome-javascript</a> with ranks
</p>
---
# Awesome JavaScript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★62884](https://github.com/sindresorhus/awesome)

A collection of awesome browser-side [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) libraries, resources and shiny things.

* [Awesome JavaScript](#awesome-javascript)
  * [Package Managers](#package-managers)
  * [Loaders](#loaders)
  * [Bundlers](#bundlers)
  * [Testing Frameworks](#testing-frameworks)
  * [QA Tools](#qa-tools)
  * [MVC Frameworks and Libraries](#mvc-frameworks-and-libraries)
  * [Node-Powered CMS Frameworks](#node-powered-cms-frameworks)
  * [Templating Engines](#templating-engines)
  * [Articles/Posts](#articles-and-posts)
  * [Data Visualization](#data-visualization)
    * [Timeline](#timeline)
    * [Spreadsheet](#spreadsheet)
  * [Editors](#editors)
  * [Documentation](#documentation)
  * Utilities
    * [Files](#files)
    * [Functional Programming](#functional-programming)
    * [Reactive Programming](#reactive-programming)
    * [Data Structure](#data-structure)
    * [Date](#date)
    * [String](#string)
    * [Number](#number)
    * [Storage](#storage)
    * [Color](#color)
    * [I18n And L10n](#i18n-and-l10n)
    * [Class](#class)
    * [Control Flow](#control-flow)
    * [Routing](#routing)
    * [Security](#security)
    * [Log](#log)
    * [RegExp](#regexp)
    * [Media](#media)
    * [Voice Command](#voice-command)
    * [API](#api)
    * [Streaming](#streaming)
    * [Vision Detection](#vision-detection)
    * [Browser Detection](#browser-detection)
    * [Benchmark](#benchmark)
    * [Machine Learning](#machine-learning)
  * UI
    * [Code Highlighting](#code-highlighting)
    * [Loading Status](#loading-status)
    * [Validation](#validation)
    * [Keyboard Wrappers](#keyboard-wrappers)
    * [Tours And Guides](#tours-and-guides)
    * [Notifications](#notifications)
    * [Sliders](#sliders)
    * [Range Sliders](#range-sliders)
    * [Form Widgets](#form-widgets)
    * [Tips](#tips)
    * [Modals and Popups](#modals-and-popups)
    * [Scroll](#scroll)
    * [Menu](#menu)
    * [Table/Grid](#tablegrid)
    * [Frameworks](#frameworks-1)
    * [Boilerplates](#boilerplates)
  * [Gesture](#gesture)
  * [Maps](#maps)
  * [Typography](#typography)
  * [Animations](#animations)
  * [Image processing](#image-processing)
  * [ES6](#es6)
  * [SDK](#sdk)
  * [Misc](#misc)
  * [Podcasts](#podcasts)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

----


## Package Managers
*Host the javascript libraries and provide tools for fetching and packaging them.*

* [npm](https://www.npmjs.com/) - npm is the package manager for javascript.
* [Bower ★15185](https://github.com/bower/bower) - A package manager for the web.
* [component ★4613 ⏳1Y](https://github.com/componentjs/component) - Client package management for building better web applications.
* [spm ★913 ⏳1Y](https://github.com/spmjs/spm) - Brand new static package manager.
* [jam ★1535](https://github.com/caolan/jam) - A package manager using a browser-focused and RequireJS compatible repository.
* [jspm ★3593](https://github.com/jspm/jspm-cli) - Frictionless browser package management.
* [Ender ★1821 ⏳2Y](https://github.com/ender-js/Ender) - The no-library library.
* [volo ★1380 ⏳1Y](https://github.com/volojs/volo) - Create front end projects from templates, add dependencies, and automate the resulting projects.
* [Duo ★3567](https://github.com/duojs/duo) - Next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless.
* [yarn](https://yarnpkg.com/) - Fast, reliable, and secure dependency management.


## Loaders
*Module or loading system for JavaScript.*

* [RequireJS ★10807](https://github.com/requirejs/requirejs) - A file and module loader for JavaScript.
* [browserify ★11219](https://github.com/substack/node-browserify) - Browser-side require() the node.js way.
* [SeaJS ★6889](https://github.com/seajs/seajs) - A Module Loader for the Web.
* [HeadJS ★4121](https://github.com/headjs/headjs) - The only script in your HEAD.
* [curl ★1762](https://github.com/cujojs/curl) - A small, fast, extensible module loader that handles AMD, CommonJS Modules/1.1, CSS, HTML/text, and legacy scripts.
* [lazyload ★1233 ⏳1Y](https://github.com/rgrove/lazyload) - Tiny, dependency-free async JavaScript and CSS loader.
* [script.js ★2357](https://github.com/ded/script.js) - Asyncronous JavaScript loader and dependency manager.
* [systemjs ★8425](https://github.com/systemjs/systemjs) - AMD, CJS & ES6 spec-compliant module loader.
* [LodJS ★270](https://github.com/yanhaijing/lodjs) - Module loader based on AMD
* [ESL ★680](https://github.com/ecomfe/esl) - Module loader browser first, support lazy define and AMD.
* [modulejs ★103](https://github.com/lrsjng/modulejs) - Lightweight JavaScript module system.


## Bundlers

* [browserify ★11219](https://github.com/substack/node-browserify) - Browserify lets you require('modules') in the browser by bundling up all of your dependencies.
* [webpack ★30679](https://github.com/webpack/webpack) - Packs CommonJs/AMD modules for the browser.
* [Rollup ★10042](https://github.com/rollup/rollup) - Next-generation ES6 module bundler.
* [Brunch ★6020](https://github.com/brunch/brunch) - Fast front-end web app build tool with simple declarative config.


## Testing Frameworks

### Frameworks

* [mocha ★12916](https://github.com/mochajs/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser.
* [jasmine ★12686](https://github.com/jasmine/jasmine) - DOM-less simple JavaScript testing framework.
* [qunit](https://github.com/jquery/qunit) - An easy-to-use JavaScript Unit Testing framework.
* [jest ★11486](https://github.com/facebook/jest) - Painless Javascript Unit Testing.
* [prova ★322](https://github.com/azer/prova) - Node & Browser test runner based on Tape and Browserify
* [DalekJS ★727](https://github.com/dalekjs/dalek) - Automated cross browser functional testing with JavaScript
* [Protractor ★6801](https://github.com/angular/protractor) - Protractor is an end-to-end test framework for AngularJS applications.
* [tape ★4020](https://github.com/substack/tape) - Tap-producing test harness for node and browsers.
* [TestCafe ★3028](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack.
* [ava ★10931](https://github.com/avajs/ava) - 🚀 Futuristic JavaScript test runner

### Assertion

* [chai ★4370](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [Enzyme](http://airbnb.io/enzyme/index.html) - Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.
* [Sinon.JS ★4506](https://github.com/sinonjs/sinon) - Test spies, stubs, and mocks for JavaScript.
* [expect.js ★1736 ⏳1Y](https://github.com/Automattic/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser.

### Coverage

* [istanbul ★6446](https://github.com/gotwarlost/istanbul) - Yet another JS code coverage tool.
* [blanket ★1354 ⏳1Y](https://github.com/alex-seville/blanket) - A simple code coverage library for javascript. Designed to be easy to install and use, for both browser and nodejs.
* [JSCover ★330](https://github.com/tntim96/JSCover) - JSCover is a tool that measures code coverage for JavaScript programs.

### Runner

* [phantomjs ★22830](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit.
* [slimerjs ★2290](https://github.com/laurentj/slimerjs) - A PhantomJS-like tool running Gecko.
* [casperjs ★6765](https://github.com/casperjs/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS.
* [zombie ★4607](https://github.com/assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js.
* [totoro ★545 ⏳2Y](https://github.com/totorojs/totoro) - A simple and stable cross-browser testing tool.
* [karma ★8829](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript.
* [nightwatch ★6840](https://github.com/nightwatchjs/nightwatch) - UI automated testing framework based on node.js and selenium webdriver.
* [intern ★3784](https://github.com/theintern/intern) - A next-generation code testing stack for JavaScript.
* [yolpo](http://www.yolpo.com) - A statement-by-statement javascript interpreter in the browser.


## QA Tools

* [JSHint ★7333](https://github.com/jshint/jshint) - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code.
* [jscs ★5148](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker.
* [jsfmt ★1702](https://github.com/rdio/jsfmt) - For formatting, searching, and rewriting JavaScript.
* [jsinspect ★1510](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code.
* [buddy.js ★564](https://github.com/danielstjules/buddy.js) - Magic number detection for JavaScript.
* [ESLint ★8218](https://github.com/eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript.
* [JSLint ★2991](https://github.com/douglascrockford/JSLint) - High-standards, strict & opinionated code quality tool, aiming to keep only good parts of the language.


## MVC Frameworks and Libraries

* [angular.js ★56616](https://github.com/angular/angular.js) - HTML enhanced for web apps.
* [aurelia](http://aurelia.io) - A Javascript client framework for mobile, desktop and web.
* [backbone ★26527](https://github.com/jashkenas/backbone) - Give your JS App some Backbone with Models, Views, Collections, and Events.
* [batman.js](http://batmanjs.org/) - The best JavaScript framework for Rails developers.
* [ember.js ★18110](https://github.com/emberjs/ember.js) - A JavaScript framework for creating ambitious web applications.
* [meteor ★37956](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework.
* [ractive ★5322](https://github.com/ractivejs/ractive) - Next-generation DOM manipulation.
* [vue ★61957](https://github.com/vuejs/vue) - Intuitive, fast & composable MVVM for building interactive interfaces.
* [knockout ★8362](https://github.com/knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript.
* [spine ★3313](https://github.com/spine/spine) - Lightweight MVC library for building JavaScript applications.
* [espresso.js ★525 ⏳2Y](https://github.com/techlayer/espresso.js) - A minimal javascript library for crafting user interfaces.
* [canjs ★1513](https://github.com/canjs/canjs) - Can do JS, better, faster, easier.
* [react](https://facebook.github.io/react/) - A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM.
* [hyperapp ★5266](https://github.com/hyperapp/hyperapp) - 1kb JavaScript library for building frontend applications. 
* [preact ★11507](https://github.com/developit/preact) - Fast 3kb React alternative with the same ES6 API. Components & Virtual DOM.
* [nativescript ★10757](https://github.com/NativeScript/NativeScript) - Build truly native cross-platform iOS and Android apps with JavaScript
* [react-native ★51594](https://github.com/facebook/react-native) - A framework for building native apps with React.
* [riot ★12179](https://github.com/riot/riot) - React-like library, but with very small size.
* [thorax ★1367 ⏳2Y](https://github.com/walmartlabs/thorax) - Strengthening your Backbone.
* [chaplin ★2972](https://github.com/chaplinjs/chaplin) - An architecture for JavaScript applications using the Backbone.js library.
* [marionette ★7142](https://github.com/marionettejs/backbone.marionette) - A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications.
* [ripple ★1282 ⏳3Y](https://github.com/ripplejs/ripple) - A tiny foundation for building reactive views.
* [rivets ★2997](https://github.com/mikeric/rivets) - Lightweight and powerful data binding + templating solution.
* [derby ★4276](https://github.com/derbyjs/derby) - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
    * [derby-awesome ★10 ⏳2Y](https://github.com/russll/awesome-derby) - A collection of awesome derby components
* [way.js ★2779](https://github.com/gwendall/way.js) - Simple, lightweight, persistent two-way databinding.
* [mithril.js](https://github.com/lhorie/mithril.js) - Mithril is a client-side MVC framework (Light-weight, Robust, Fast).
* [jsblocks ★2819](https://github.com/astoilkov/jsblocks) - jsblocks is better MV-ish framework.
* [LiquidLava](http://www.lava-framework.com/) - Transparent MVC framework for building user interfaces.
* [feathers ★7060](https://github.com/feathersjs/feathers) - A minimalist real-time JavaScript framework for tomorrow's apps.
* [Keo ★208](https://github.com/Wildhoney/Keo) - Functional stateless React components with Shadow DOM support.

## Node-Powered CMS Frameworks

* [KeystoneJS ★10572](https://github.com/keystonejs/keystone) - powerful CMS and web app framework
* [Reaction Commerce ★5172](https://github.com/reactioncommerce/reaction) - reactive CMS, real-time architecture and design
* [Ghost ★23375](https://github.com/tryghost/Ghost) - simple, powerful publishing platform
* [Apostrophe ★1581](https://github.com/punkave/apostrophe) - CMS with content editing and essential services
* [We.js ★178](https://github.com/wejs/we) - framework for real time apps, sites or blogs
* [Hatch.js ★70](https://github.com/inventures/hatchjs) - CMS platform with social features.
* [TaracotJS ★16 ⏳2Y](https://github.com/xtremespb/taracotjs-generator) - fast and minimalist CMS based on Node.js.
* [Nodizecms ★185 ⏳4Y](https://github.com/nodize/nodizecms) - CMS for CoffeeScript lovers
* [Cody ★618](https://github.com/jcoppieters/cody) - CMS with WSYWYG editor
* [PencilBlue ★1582](https://github.com/pencilblue/pencilblue) - CMS and blogging platform

## Templating Engines
*Templating engines allow you to perform string interpolation.*

* [mustache.js ★11004](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript.
* [handlebars.js ★12245](https://github.com/wycats/handlebars.js) - An extension to the Mustache templating language.
* [hogan.js ★4782](https://github.com/twitter/hogan.js) - A compiler for the Mustache templating language.
* [doT ★3515](https://github.com/olado/doT) - The fastest + concise javascript template engine for nodejs and browsers.
* [dustjs ★2611](https://github.com/linkedin/dustjs) - Asynchronous templates for the browser and node.js.
* [eco ★1772 ⏳2Y](https://github.com/sstephenson/eco) - Embedded CoffeeScript templates.
* [JavaScript-Templates ★1208](https://github.com/blueimp/JavaScript-Templates) - < 1KB lightweight, fast & powerful JavaScript templating engine with zero dependencies.
* [t.js ★766](https://github.com/jasonmoo/t.js) - A tiny javascript templating framework in ~400 bytes gzipped.
* [Jade ★14908](https://github.com/pugjs/pug) - Robust, elegant, feature rich template engine for nodejs.
* [EJS ★1628](https://github.com/mde/ejs) - Effective JavaScript templating.
* [xtemplate ★352](https://github.com/xtemplate/xtemplate) - eXtensible Template Engine lib for node and the browser
* [marko ★3119](https://github.com/marko-js/marko) - A fast, lightweight, HTML-based templating engine for Node.js and the browser with async, streaming, custom tags and CommonJS modules as compiled output.
* [swig](http://paularmstrong.github.io/swig/) - A simple, powerful, and extendable Node.js and browser-based JavaScript template engine.

## Articles and Posts

* [The JavaScript that you should know](https://medium.com/@pedropolisenso/o-javasscript-que-você-deveria-conhecer-b70e94d1d706) - Article about concepts of JavaScript Functional.

## Data Visualization
*Data visualization tools for the web.*

* [d3 ★66697](https://github.com/d3/d3) - A JavaScript visualization library for HTML and SVG.
  * [metrics-graphics ★6692](https://github.com/mozilla/metrics-graphics) - A library optimized for concise, principled data graphics and layouts.
* [pykcharts.js ★274 ⏳1Y](https://github.com/pykih/PykCharts.js) - Well designed d3.js charting without the complexity of d3.js.
* [three.js ★34333](https://github.com/mrdoob/three.js) - JavaScript 3D library.
* [Chart.js ★31453](https://github.com/chartjs/Chart.js) - Simple HTML5 Charts using the <canvas> tag.
* [paper.js ★8076](https://github.com/paperjs/paper.js) - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas.
* [fabric.js ★8392](https://github.com/kangax/fabric.js) - Javascript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser.
* [peity ★3846](https://github.com/benpickles/peity) - Progressive <svg> bar, line and pie charts.
* [raphael ★9210](https://github.com/DmitryBaranovskiy/raphael) - JavaScript Vector Library.
* [echarts ★19591](https://github.com/ecomfe/echarts) - Enterprise Charts.
* [vis ★5446](https://github.com/almende/vis) - Dynamic, browser-based visualization library.
* [two.js ★5118](https://github.com/jonobr1/two.js) - A renderer agnostic two-dimensional drawing api for the web.
* [g.raphael ★1512 ⏳1Y](https://github.com/DmitryBaranovskiy/g.raphael) - Charts for Raphaël.
* [sigma.js ★7379](https://github.com/jacomyal/sigma.js) - A JavaScript library dedicated to graph drawing.
* [arbor ★2414 ⏳1Y](https://github.com/samizdatco/arbor) - A graph visualization library using web workers and jQuery.
* [cubism ★4554](https://github.com/square/cubism) - A D3 plugin for visualizing time series.
* [dc.js ★5764](https://github.com/dc-js/dc.js) - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js
* [vega ★17 ⏳1Y](https://github.com/trifacta/vega) - A visualization grammar.
* [processing.js](http://processingjs.org/) - Processing.js makes your data visualizations work using web standards and without any plug-ins
* [envisionjs ★1565 ⏳4Y](https://github.com/HumbleSoftware/envisionjs) - Dynamic HTML5 visualization.
* [rickshaw ★6074](https://github.com/shutterstock/rickshaw) - JavaScript toolkit for creating interactive real-time graphs.
* [flot ★5403](https://github.com/flot/flot) - Attractive JavaScript charts for jQuery.
* [morris.js ★6578](https://github.com/morrisjs/morris.js) - Pretty time-series line graphs.
* [nvd3 ★6092](https://github.com/novus/nvd3) - Build re-usable charts and chart components for d3.js
* [svg.js](https://github.com/wout/svg.js) - A lightweight library for manipulating and animating SVG.
* [heatmap.js ★3886](https://github.com/pa7/heatmap.js) - JavaScript Library for HTML5 canvas based heatmaps.
* [jquery.sparkline ★1069](https://github.com/gwatts/jquery.sparkline) - A plugin for the jQuery javascript library to generate small sparkline charts directly in the browser.
* [xCharts ★1792 ⏳4Y](https://github.com/tenxer/xCharts) - A D3-based library for building custom charts and graphs.
* [trianglify ★7665](https://github.com/qrohlf/trianglify) - Low poly style background generator with d3.js
* [d3-cloud ★2159](https://github.com/jasondavies/d3-cloud) - Create word clouds in JavaScript.
* [d4 ★399](https://github.com/heavysixer/d4) - A friendly reusable charts DSL for D3.
* [dimple.js](http://dimplejs.org) -  Easy charts for business analytics powered by d3
* [chartist-js ★9727](https://github.com/gionkunz/chartist-js) - Simple responsive charts.
* [epoch ★4859](https://github.com/epochjs/epoch) - A general purpose real-time charting library.
* [c3 ★7005](https://github.com/c3js/c3) - D3-based reusable chart library.
* [BabylonJS ★5278](https://github.com/BabylonJS/Babylon.js) - A framework for building 3D games with HTML 5 and WebGL.
* [recharts ★6232](https://github.com/recharts/recharts) - Redefined chart library built with React and D3
* [GraphicsJS](https://www.graphicsjs.org) - A lightweight JavaScript graphics library with the intuitive API, based on SVG/VML technology.

There're also some great commercial libraries, like [amchart](https://www.amcharts.com/), [anychart](http://www.anychart.com), [plotly](https://plot.ly/), and [highchart](http://www.highcharts.com/).


## Timeline

* [TimelineJS ★8407](https://github.com/NUKnightLab/TimelineJS) - A Storytelling Timeline built in JavaScript.
* [timesheet.js ★38 ⏳2Y](https://github.com/semu/timesheet.js) - JavaScript library for simple HTML5 & CSS3 time sheets.

## Spreadsheet

* [HANDSONTABLE ★8378](https://github.com/handsontable/handsontable) - Handsontable is a JavaScript/HTML5 Spreadsheet Library for Developers

## Editors

* [ace ★15424](https://github.com/ajaxorg/ace) - Ace (Ajax.org Cloud9 Editor).
* [CodeMirror ★12331](https://github.com/codemirror/CodeMirror) - In-browser code editor.
* [esprima ★260](https://github.com/ariya/esprima) - ECMAScript parsing infrastructure for multipurpose analysis.
* [quill ★14272](https://github.com/quilljs/quill) - A cross browser rich text editor with an API.
* [medium-editor ★10860](https://github.com/yabwe/medium-editor) - Medium.com WYSIWYG editor clone.
* [pen ★4190](https://github.com/sofish/pen) - enjoy live editing (+markdown).
* [jquery-notebook ★1694](https://github.com/raphaelcruzeiro/jquery-notebook) - A simple, clean and elegant text editor. Inspired by the awesomeness of Medium.
* [bootstrap-wysiwyg ★5373](https://github.com/mindmup/bootstrap-wysiwyg) - Tiny bootstrap-compatible WYSIWYG rich text editor.
* [ckeditor-releases ★366](https://github.com/ckeditor/ckeditor-releases) - The best web text editor for everyone.
* [editor ★2397 ⏳1Y](https://github.com/lepture/editor) - A markdown editor. still on development.
* [EpicEditor ★4382](https://github.com/OscarGodson/EpicEditor) - An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more.
* [jsoneditor ★3533](https://github.com/josdejong/jsoneditor) - A web-based tool to view, edit and format JSON.
* [vim.js ★4138 ⏳1Y](https://github.com/coolwanglu/vim.js) - JavaScript port of Vim with a persistent ~/.vimrc
* [Squire ★3661](https://github.com/neilj/Squire) - HTML5 rich text editor.
* [TinyMCE ★4575](https://github.com/tinymce/tinymce) - The JavaScript Rich Text editor.
* [trix ★7855](https://github.com/basecamp/trix) - A rich text editor for everyday writing. By Basecamp.
* [Trumbowyg ★1733](https://github.com/Alex-D/Trumbowyg) - A lightweight and amazing WYSIWYG JavaScript editor.
* [Draft.js ★10598](https://github.com/facebook/draft-js) - A React framework for building text editors.
* [bootstrap-wysihtml5 ★4214](https://github.com/jhollingworth/bootstrap-wysihtml5) - Simple, beautiful wysiwyg editor
* [wysihtml5 ★6606 ⏳1Y](https://github.com/xing/wysihtml5) - Open source rich text editor based on HTML5 and the progressive-enhancement approach. Uses a sophisticated security concept and aims to generate fully valid HTML5 markup by preventing unmaintainable tag soups and inline styles.
* [raptor-editor ★523 ⏳2Y](https://github.com/PANmedia/raptor-editor) - Raptor, an HTML5 WYSIWYG content editor!
* [popline ★1036 ⏳1Y](https://github.com/kenshin54/popline) - Popline is an HTML5 Rich-Text-Editor Toolbar


## Documentation

* [DevDocs](http://devdocs.io/) is an all-in-one API documentation reader with a fast, organized, and consistent interface.
* [dexy](http://www.dexy.it/) is a free-form literate documentation tool for writing any kind of technical document incorporating code.
* [docco](http://jashkenas.github.io/docco/) is a quick-and-dirty, hundred-line-long, literate-programming-style documentation generator.
* [styledocco](http://jacobrask.github.io/styledocco/) generates documentation and style guide documents from your stylesheets.
* [Ronn ★960 ⏳1Y](https://github.com/rtomayko/ronn) builds manuals. It converts simple, human readable textfiles to roff for terminal display, and also to HTML for the web.
* [dox ★1997](https://github.com/tj/dox) is a JavaScript documentation generator written with node. Dox no longer generates an opinionated structure or style for your docs, it simply gives you a JSON representation, allowing you to use markdown and JSDoc-style tags.
* [jsdox ★195 ⏳1Y](https://github.com/sutoiku/jsdox) is a JSDoc3 to Markdown documentation generator.
* [YUIDoc](http://yui.github.io/yuidoc/) is a Node.js application that generates API documentation from comments in source, using a syntax similar to tools like Javadoc and Doxygen.
* [coddoc](http://doug-martin.github.io/coddoc/) is a jsdoc parsing library. Coddoc is different in that it is easily extensible by allowing users to add tag and code parsers through the use of coddoc.addTagHandler and coddoc.addCodeHandler. coddoc also parses source code to be used in APIs.
* [sphinx](http://www.sphinx-doc.org/) a tool that makes it easy to create intelligent and beautiful documentation
* [Using JSDoc](http://usejsdoc.org/)
* [Beautiful docs](http://beautifuldocs.com/) is a documentation viewer based on markdown files.
* [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.
* [jsduck ★1418](https://github.com/senchalabs/jsduck) - API documentation generator made for Sencha JavaScript frameworks, but can be used for other frameworks too.



## Files
*Libraries for working with files.*

* [Papa Parse ★4455](https://github.com/mholt/PapaParse) - A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV.
* [jBinary ★400 ⏳1Y](https://github.com/jDataView/jBinary) - High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures.
* [diff2html ★378](https://github.com/rtfpessoa/diff2html) - Git diff output parser and pretty HTML generator.
* [jsPDF ★8573](https://github.com/MrRio/jsPDF) - JavaScript PDF generation.


## Functional Programming
*Functional programming libraries to extend JavaScript’s capabilities.*

* [underscore ★21121](https://github.com/jashkenas/underscore) - JavaScript's utility _ belt.
* [lodash ★25171](https://github.com/lodash/lodash) - A utility library delivering consistency, customization, performance, & extras.
* [Sugar ★3355](https://github.com/andrewplummer/Sugar) - A Javascript library for working with native objects.
* [lazy.js ★4257](https://github.com/dtao/lazy.js) - Like Underscore, but lazier.
* [ramda ★31](https://github.com/CrossEye/ramda) - A practical functional library for Javascript programmers.
* [mout ★749](https://github.com/mout/mout) - Modular JavaScript Utilities.
* [mesh ★1027](https://github.com/crcn/mesh.js) - Streamable data synchronization utility.
* [preludejs ★55 ⏳1Y](https://github.com/alanrsoares/prelude-js) - Hardcore Functional Programming for JavaScript.


## Reactive Programming
*Reactive programming libraries to extend JavaScript’s capabilities.*

* [RxJs ★16878](https://github.com/Reactive-Extensions/RxJS) - The Reactive Extensions for JavaScript.
* [Bacon ★5711](https://github.com/baconjs/bacon.js) - FRP (functional reactive programming) library for Javascript.
* [Kefir ★5 ⏳1Y](https://github.com/pozadi/kefir) - FRP library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory consumption.
* [Highland] (http://highlandjs.org/) - Re-thinking the JavaScript utility belt, Highland manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
* [Most.js ★2176](https://github.com/cujojs/most) - high performance FRP library.
* [MobX ★10299](https://github.com/mobxjs/mobx) - TFRP library for simple, scalable state management.
* [Cycle.js](https://cycle.js.org) - A functional and reactive JavaScript library for cleaner code.

## Data Structure
*Data structure libraries to build a more sophisticated application.*

* [immutable-js ★19865](https://github.com/facebook/immutable-js) - Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector.
* [mori ★2692](https://github.com/swannodette/mori) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [buckets ★743](https://github.com/mauriciosantos/Buckets-JS) - A complete, fully tested and documented data structure library written in JavaScript.
* [hashmap ★270](https://github.com/flesler/hashmap) - Simple hashmap implementation that supports any kind of keys.


## Date
*Date Libraries.*

* [moment ★32540](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript.
* [moment-timezone ★2205](https://github.com/moment/moment-timezone) - Timezone support for moment.js.
* [jquery-timeago ★3643](https://github.com/rmm5t/jquery-timeago) - A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago").
* [timezone-js ★786](https://github.com/mde/timezone-js) - Timezone-enabled JavaScript Date object. Uses Olson zoneinfo files for timezone data.
* [date ★1249](https://github.com/MatthewMueller/date) - Date() for humans.
* [ms.js](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility.
* [countdown.js ★377 ⏳3Y](https://github.com/gumroad/countdown.js) - Super simple countdowns.
* [timeago.js ★2721](https://github.com/hustcc/timeago.js) - Simple library (less then 2kb) used to format date with `*** time ago` statement.
* [fecha ★1080](https://github.com/taylorhakes/fecha) - Lightweight date formatting and parsing (~2KB). Meant to replace parsing and formatting functionality of moment.js.

## String
*String Libraries.*

* [selecting ★56 ⏳1Y](https://github.com/EvandroLG/selecting) - A library that allows you to access the text selected by the user
* [underscore.string ★3198](https://github.com/epeli/underscore.string) - String manipulation extensions for Underscore.js javascript library.
* [string.js ★1490](https://github.com/jprichardson/string.js) - Extra JavaScript string methods.
* [he ★1127](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript.
* [multiline ★1423 ⏳1Y](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript.
* [query-string ★1192](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings.
* [URI.js ★4815](https://github.com/medialize/URI.js) - Javascript URL mutation library.
* [jsurl ★375](https://github.com/Mikhus/domurl) - Lightweight URL manipulation with JavaScript.
* [sprintf.js ★1456](https://github.com/alexei/sprintf.js) - A sprintf implementation.
* [url-pattern ★253](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for urls and other strings. Turn strings into data or data into strings

## Number

* [Numeral-js ★5307](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers.
* [chance.js ★2571](https://github.com/chancejs/chancejs) - Random generator helper in Javascript. Can generate numbers, strings etc.
* [odometer ★5658](https://github.com/HubSpot/odometer) - Smoothly transitions numbers with ease.
* [accounting.js](https://github.com/josscrowcroft/accounting.js) - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies.
* [money.js](https://github.com/josscrowcroft/money.js) - A tiny (1kb) javascript currency conversion library, for web & nodeJS.
* [Fraction.js ★101](https://github.com/infusion/Fraction.js) - A rational number library for JavaScript
* [Complex.js ★93](https://github.com/infusion/Complex.js) - A complex number library for JavaScript
* [Polynomial.js ★39](https://github.com/infusion/Polynomial.js) - A polynomials library for JavaScript


## Storage

* [store.js ★9920](https://github.com/marcuswestin/store.js) - LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood.
* [localForage](https://github.com/mozilla/localForage) - Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.
* [jStorage ★1487](https://github.com/andris9/jStorage) - jStorage is a simple key/value database to store data on browser side.
* [cross-storage ★1006](https://github.com/zendesk/cross-storage) - Cross domain local storage, with permissions.
* [basket.js ★2962 ⏳1Y](https://github.com/addyosmani/basket.js) - A script and resource loader for caching & loading scripts with localStorage.
* [bag.js ★64](https://github.com/nodeca/bag.js) - A caching script and resource loader, similar to basket.js, but with additional k/v interface and localStorage / websql / indexedDB support.
* [basil.js ★1884](https://github.com/Wisembly/basil.js) - The missing Javascript smart persistent layer.
* [jquery-cookie ★8289](https://github.com/carhartl/jquery-cookie) - A simple, lightweight jQuery plugin for reading, writing and deleting cookies.
* [js-cookie ★6697](https://github.com/js-cookie/js-cookie) - A simple, lightweight JavaScript API for handling browser cookies
* [Cookies ★1655](https://github.com/ScottHamper/Cookies) - JavaScript Client-Side Cookie Manipulation Library.
* [DB.js] (https://github.com/aaronpowell/db.js/) - Promise based IndexDB Wrapper library
* [lawnchair.js] (https://github.com/brianleroux/lawnchair/) - Simple client-side JSON storage.
* [sql.js] (https://github.com/kripken/sql.js) - SQLite compiled to JavaScript through Emscripten.


## Color

* [randomColor ★4139](https://github.com/davidmerfield/randomColor) - A color generator for JavaScript.
* [chroma.js ★4390](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations.
* [color ★1590](https://github.com/Qix-/color) - JavaScript color conversion and manipulation library.
* [colors ★7493](https://github.com/mrmrs/colors) - Smarter defaults for colors on the web.
* [PleaseJS ★2087](https://github.com/Fooidge/PleaseJS) - JavaScript Library for creating random pleasing colors and color schemes.
* [TinyColor ★1743](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript.
* [Vibrant.js] (https://github.com/jariz/vibrant.js/) - Extract prominent colors from an image.

## I18n And L10n
*Localization (l10n) and internationalization (i18n) JavaScript libraries.*

* [i18next ★2353](https://github.com/i18next/i18next) - internationalisation (i18n) with javascript the easy way.
* [polyglot ★2359](https://github.com/airbnb/polyglot.js) - tiny i18n helper library.
* [babelfish ★167 ⏳1Y](https://github.com/nodeca/babelfish) - i18n with human friendly API and built in plurals support.

## Class

* [ClassManager ★35](https://github.com/kogarashisan/ClassManager) - One of the fastest and most convenient class systems in the world
* [klass ★726 ⏳2Y](https://github.com/ded/klass) - A utility for creating expressive classes in JavaScript.
* [augment ★894 ⏳2Y](https://github.com/javascript/augment) - The world's smallest and fastest classical JavaScript inheritance pattern.


## Control Flow

* [async ★21916](https://github.com/caolan/async) - Async utilities for node and the browser.
* [q ★13485](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript.
* [step ★2132](https://github.com/creationix/step) - An async control-flow library that makes stepping through logic easy.
* [contra ★720 ⏳1Y](https://github.com/bevacqua/contra) - Asynchronous flow control with a functional taste to it.
* [Bluebird ★15134](https://github.com/petkaantonov/bluebird) - fully featured promise library with focus on innovative features and performance.
* [when ★3229](https://github.com/cujojs/when) - A solid, fast Promises/A+ and when() implementation, plus other async goodies.
* [ObjectEventTarget ★7 ⏳1Y](https://github.com/gartz/ObjectEventTarget) - Provide a prototype that add support to event listeners (with same behavior of EventTarget from DOMElements available on browsers).


## Routing

* [director ★4833](https://github.com/flatiron/director) - A tiny and isomorphic URL router for JavaScript.
* [page.js ★4977](https://github.com/visionmedia/page.js) - Micro client-side router inspired by the Express router (~1200 bytes).
* [pathjs ★1052](https://github.com/mtrpcic/pathjs) - Simple, lightweight routing for web browsers.
* [crossroads ★1373](https://github.com/millermedeiros/crossroads.js) - JavaScript Routes.
* [davis.js ★538](https://github.com/olivernn/davis.js) - RESTful degradable JavaScript routing using pushState.


## Security

* [DOMPurify ★1561](https://github.com/cure53/DOMPurify) - A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG.
* [js-xss ★1536](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist.
* [xss-filters ★637](https://github.com/yahoo/xss-filters) - Secure XSS Filters by Yahoo


## Log

* [log ★2487](https://github.com/adamschwartz/log) - Console.log with style.
* [Conzole ★186 ⏳1Y](https://github.com/Oaxoa/Conzole) - A debug panel built in javascript that wraps javascript native console object methods and functionality in a panel displayed inside the page.
* [console.log-wrapper ★395](https://github.com/patik/console.log-wrapper) - Log to the console in any browser with clarity.
* [loglevel ★849](https://github.com/pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods.
* [minilog](http://mixu.net/minilog/) – Lightweight client & server-side logging with Stream-API backends
* [storyboard](http://guigrpa.github.io/storyboard/) - Universal logging library + Chrome extension; it lets you see all client and server tasks triggered by a user action in a single place.

## RegExp
* [RegEx101](https://regex101.com/#javascript) - Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE.
* [RegExr](http://regexr.com) - HTML/JS based tool for creating, testing, and learning about Regular Expressions.
* [RegExpBuilder ★1068 ⏳2Y](https://github.com/thebinarysearchtree/regexpbuilderjs) - Create regular expressions using chained methods.


## Voice Command

* [annyang ★4201](https://github.com/TalAter/annyang) - A JavaScript library for adding voice commands to your site, using speech recognition.
* [voix.js ★504](https://github.com/pazguille/voix) - A JavaScript library to add voice commands to your sites, apps or games.


## API

* [bottleneck ★279](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.
* [oauth-signature-js ★189](https://github.com/bettiolo/oauth-signature-js) - JavaScript OAuth 1.0a signature generator for node and the browser.
* [amygdala ★400](https://github.com/lincolnloop/amygdala) - RESTful HTTP client for JavaScript powered web applications.
* [jquery.rest ★574](https://github.com/jpillora/jquery.rest) - A jQuery plugin for easy consumption of RESTful APIs.

## Streaming

* [Tailor ★392](https://github.com/zalando/tailor) - Streaming layout service for front-end microservices, inspired by Facebook's BigPipe.


## Vision Detection

* [tracking.js ★5224](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web.
* [ocrad.js ★2648](https://github.com/antimatter15/ocrad.js) - OCR in Javascript via Emscripten.


## Machine Learning

* [ConvNetJS ★7627](https://github.com/karpathy/convnetjs) - Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
* [DN2A ★448](https://github.com/dn2a/dn2a-javascript) - Digital Neural Networks Architecture.
* [Brain.js ★7773](https://github.com/harthur/brain) - Neural networks in JavaScript.
* [Mind.js ★1026](https://github.com/stevenmiller888/mind) - A flexible neural network library.
* [Synaptic.js ★4448](https://github.com/cazala/synaptic) - Architecture-free neural network library for node.js and the browser.


## Browser Detection

* [bowser](https://github.com/ded/bowser) - a browser detector

## Benchmark

* [benchmark.js ★2880](https://github.com/bestiejs/benchmark.js) - A benchmarking library. As used on jsPerf.com.
* [matcha ★448](https://github.com/logicalparadox/matcha) - A caffeine driven, simplistic approach to benchmarking.

## Code highlighting

* [Highlight.js ★10375](https://github.com/isagalaev/highlight.js) - Javascript syntax highlighter.
* [PrismJS ★4326](https://github.com/PrismJS/prism) - Lightweight, robust, elegant syntax highlighting.


## Loading Status
*Libraries for indicate load status.*

* [Mprogress.js ★1493](https://github.com/lightningtgc/MProgress.js) - Create Google Material Design progress linear bars.
* [NProgress](http://ricostacruz.com/nprogress/) - Slim progress bars for Ajax'y applications.
* [Spin.js ★8785](https://github.com/fgnass/spin.js) - A spinning activity indicator.
* [progress.js ★2252 ⏳1Y](https://github.com/usablica/progress.js) - Create and manage progress bar for every objects on the page.
* [progressbar.js ★5780](https://github.com/kimmobrunfeldt/progressbar.js) - Beautiful and responsive progress bars with animated SVG paths.
* [pace ★12345](https://github.com/HubSpot/pace) - Automatically add a progress bar to your site.
* [topbar ★136 ⏳2Y](https://github.com/buunguyen/topbar) - Tiny & beautiful site-wide progress indicator.
* [nanobar ★2449](https://github.com/jacoborus/nanobar) - Very lightweight progress bars. No jQuery.
* [PageLoadingEffects ★550 ⏳3Y](https://github.com/codrops/PageLoadingEffects) - Modern ways of revealing new content using SVG animations.
* [SpinKit ★13555](https://github.com/tobiasahlin/SpinKit) - A collection of loading indicators animated with CSS.
* [Ladda ★6957](https://github.com/hakimel/Ladda) - Buttons with built-in loading indicators.
* [css-loaders ★4999](https://github.com/lukehaas/css-loaders) - A collection of loading spinners animated with CSS

Besides libraries, there're [Collection on Codepen](http://codepen.io/collection/HtAne/), and generators like [Ajaxload](http://www.ajaxload.info/), [Preloaders](http://preloaders.net/) and [CSSLoad](http://cssload.net/).


## Validation

* [Parsley.js ★8000](https://github.com/guillaumepotier/Parsley.js) - Validate your forms, frontend, without writing a single line of javascript.
* [jquery-validation](https://github.com/jzaefferer/jquery-validation) - jQuery Validation Plugin.
* [validator.js ★8247](https://github.com/chriso/validator.js) - String validation and sanitization.
* [validate.js ★2183](https://github.com/rickharrison/validate.js) - Lightweight JavaScript form validation library inspired by CodeIgniter.
* [validatr ★279](https://github.com/jaymorrow/validatr) - Cross Browser HTML5 Form Validation.
* [FormValidation](http://formvalidation.io/) - The best jQuery plugin to validate form fields. Formerly BootstrapValidator.
* [is.js ★7933](https://github.com/arasatasaygin/is.js) -  Check types, regexps, presence, time and more.
* [FieldVal ★135](https://github.com/FieldVal/fieldval-js) - multipurpose validation library. Supports both sync and async validation.


## Keyboard Wrappers

* [mousetrap ★7923](https://github.com/ccampbell/mousetrap) - Simple library for handling keyboard shortcuts in Javascript.
* [keymaster ★5765 ⏳1Y](https://github.com/madrobby/keymaster) - A simple micro-library for defining and dispatching keyboard shortcuts.
* [Keypress ★3049](https://github.com/dmauro/Keypress) - A keyboard input capturing utility in which any key can be a modifier key.
* [KeyboardJS ★1316](https://github.com/RobertWHurst/KeyboardJS) - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts.
* [jquery.hotkeys ★2427](https://github.com/jeresig/jquery.hotkeys) - jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination.
* [jwerty ★1188 ⏳1Y](https://github.com/keithamus/jwerty) - Awesome handling of keyboard events.


## Tours And Guides

* [intro.js ★15544](https://github.com/usablica/intro.js) - A better way for new feature introduction and step-by-step users guide for your website and project.
* [shepherd ★5056](https://github.com/HubSpot/shepherd) - Guide your users through a tour of your app.
* [bootstrap-tour ★3892](https://github.com/sorich87/bootstrap-tour) - Quick and easy product tours with Twitter Bootstrap Popovers.
* [tourist ★1193 ⏳1Y](https://github.com/easelinc/tourist) - Simple, flexible tours for your app.
* [chardin.js ★4585](https://github.com/heelhook/chardin.js) - Simple overlay instructions for your apps.
* [pageguide ★864](https://github.com/tracelytics/pageguide) - An interactive guide for web page elements using jQuery and CSS3.
* [hopscotch ★3751](https://github.com/linkedin/hopscotch) - A framework to make it easy for developers to add product tours to their pages.
* [joyride ★1344](https://github.com/zurb/joyride) - jQuery feature tour plugin.
* [focusable ★1072 ⏳1Y](https://github.com/zzarcon/focusable) - Set a spotlight focus on DOM element adding a overlay layer to the rest of the page.

## Notifications

* [messenger ★3946](https://github.com/HubSpot/messenger) - Growl-style alerts and messages for your app.
* [noty ★5379](https://github.com/needim/noty) - jQuery notification plugin.
* [pnotify ★2995](https://github.com/sciactive/pnotify) - JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft.
* [toastr ★7013](https://github.com/CodeSeven/toastr) - Simple javascript toast notifications.
* [humane-js ★2069](https://github.com/wavded/humane-js) - A simple, modern, browser notification system.
* [smoke.js ★944](https://github.com/hxgf/smoke.js) - Framework-agnostic styled alert system for javascript.
* [notie ★5619](https://github.com/jaredreich/notie) - Simple notifications and inputs with no dependencies.


## Sliders

* [Swiper ★13074](https://github.com/nolimits4web/Swiper) - Mobile touch slider and framework with hardware accelerated transitions.
* [slick ★18990](https://github.com/kenwheeler/slick) - The last carousel you'll ever need.
* [slidesJs](http://www.slidesjs.com) - Is a ressponsive slideshow plug-in for JQuery(1.7.1+) with features like touch and CSS3 transitions
* [FlexSlider](https://github.com/woothemes/FlexSlider) - An awesome, fully responsive jQuery slider plugin.
* [unslider ★4059](https://github.com/idiot/unslider) - The simplest jQuery slider there is.
* [sly ★2748](https://github.com/darsain/sly) - JavaScript library for one-directional scrolling with item based navigation support.
* [vegas ★1578](https://github.com/jaysalvat/vegas) - A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows.
* [Sequence ★3296 ⏳1Y](https://github.com/IanLunn/Sequence) - CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications.
* [reveal.js ★35768](https://github.com/hakimel/reveal.js) - A framework for easily creating beautiful presentations using HTML.
* [impress.js ★31992](https://github.com/impress/impress.js) - It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com.
* [bespoke.js ★4194](https://github.com/bespokejs/bespoke) - DIY Presentation Micro-Framework
* [Strut ★1418](https://github.com/tantaman/Strut) - Strut - An Impress.js and Bespoke.js Presentation Editor
* [PhotoSwipe ★14495](https://github.com/dimsemenov/PhotoSwipe) - JavaScript image gallery for mobile and desktop, modular, framework independent.
* [jcSlider ★36 ⏳1Y](https://github.com/JoanClaret/jcSlider) - A responsive slider jQuery plugin with CSS animations.
* [basic-jquery-slider ★572 ⏳1Y](https://github.com/jcobb/basic-jquery-slider) - Simple to use, simple to theme, simple to customise.
* [jQuery.adaptive-slider ★49 ⏳3Y](https://github.com/creative-punch/jQuery.adaptive-slider) - A jQuery plugin for a slider with adaptive colored figcaption and navigation.
* [slidr ★1496 ⏳1Y](https://github.com/bchanx/slidr) - add some slide effects.
* [Flickity ★3901](https://github.com/metafizzy/flickity) - Touch, responsive, flickable galleries.
* [Glide.js ★1644](https://github.com/jedrzejchalubek/glidejs) - Responsive and touch-friendly jQuery slider. It's simple, lightweight and fast.
* [jQuery.adaptive-slider ★49 ⏳3Y](https://github.com/creative-punch/jQuery.adaptive-slider) - A jQuery plugin for a slider with adaptive colored figcaption and navigation.

## Range Sliders

* [Ion.RangeSlider ★1664](https://github.com/IonDen/ion.rangeSlider) - Powerful and easily customizable range slider with many options and skin support.
* [jQRangeSlider ★673 ⏳1Y](https://github.com/ghusse/jQRangeSlider) - A javascript slider selector that supports dates.
* [noUiSlider ★2902](https://github.com/leongersen/noUiSlider) - A lightweight, highly customizable range slider without bloat.
* [rangeslider.js ★1533](https://github.com/andreruffert/rangeslider.js) - HTML5 input range slider element polyfill.


## Form Widgets

### Input

* [typeahead.js ★14428](https://github.com/twitter/typeahead.js) - A fast and fully-featured autocomplete library.
* [tag-it ★2311](https://github.com/aehlke/tag-it) - A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete.
* [At.js ★4551](https://github.com/ichord/At.js) - Add Github like mentions autocomplete to your application.
* [Placeholders.js ★933](https://github.com/jamesallardice/Placeholders.js) - A JavaScript polyfill for the HTML5 placeholder attribute.
* [fancyInput ★1912](https://github.com/yairEO/fancyInput) - Makes typing in input fields fun with CSS3 effects.
* [jQuery-Tags-Input ★2034](https://github.com/xoxco/jQuery-Tags-Input) - Magically convert a simple text input into a cool tag list with this jQuery plugin.
* [vanilla-masker](https://github.com/BankFacil/vanilla-masker) - A pure javascript mask input.
* [Ion.CheckRadio ★65 ⏳1Y](https://github.com/IonDen/ion.checkRadio) - jQuery plugin for styling checkboxes and radio-buttons. With skin support.
* [awesomplete ★5579](https://github.com/LeaVerou/awesomplete) - Ultra lightweight, usable, beautiful autocomplete with zero dependencies. - http://leaverou.github.io/awesomplete/

### Calendar

* [pickadate.js ★6982](https://github.com/amsul/pickadate.js) - The mobile-friendly, responsive, and lightweight jQuery date & time input picker.
* [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode.
* [Pikaday ★5438](https://github.com/dbushell/Pikaday) - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS.
* [fullcalendar ★6933](https://github.com/fullcalendar/fullcalendar) - Full-sized drag & drop event calendar (jQuery plugin).
* [rome ★2689](https://github.com/bevacqua/rome) - A customizable date (and time) picker. Dependency free, opt-in UI.
* [datedropper ★1701](https://github.com/felicegattuso/datedropper) -  datedropper is a jQuery plugin that provides a quick and easy way to manage dates for input fields.


### Select

* [selectize.js](https://github.com/brianreavis/selectize.js) - Selectize is the hybrid of a textbox and select box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc.
* [select2 ★20782](https://github.com/select2/select2) - a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.
* [chosen ★20945](https://github.com/harvesthq/chosen) - A library for making long, unwieldy select boxes more friendly.

### File Uploader

* [jQuery-File-Upload ★27183](https://github.com/blueimp/jQuery-File-Upload) - File Upload widget with multiple file selection, drag&amp;drop support, progress bar, validation and preview images, audio and video for jQuery.
* [dropzone ★12684](https://github.com/enyo/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars.
* [flow.js ★2317](https://github.com/flowjs/flow.js) - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API.
* [fine-uploader ★7113](https://github.com/FineUploader/fine-uploader) - Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading.
* [FileAPI ★3081](https://github.com/mailru/FileAPI) - A set of javascript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF.
* [plupload ★4446](https://github.com/moxiecode/plupload) - A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash.

### Other

* [form](https://github.com/malsup/form) - jQuery Form Plugin.
* [Garlic.js ★2230](https://github.com/guillaumepotier/Garlic.js) - Automatically persist your forms' text and select field values locally, until the form is submitted.
* [Countable ★1469](https://github.com/RadLikeWhoa/Countable) - A JavaScript function to add live paragraph-, word- and character-counting to an HTML element.
* [card ★8908](https://github.com/jessepollak/card) - Make your credit card form better in one line of code.
* [stretchy ★1154](https://github.com/LeaVerou/stretchy) - Form element autosizing, the way it should be.


## Tips

* [tipsy ★2047](https://github.com/jaz303/tipsy) - Facebook-style tooltips plugin for jQuery.
* [opentip ★1248 ⏳1Y](https://github.com/enyo/opentip) - An open source javascript tooltip based on the prototype framework.
* [qTip2 ★1975](https://github.com/qTip2/qTip2) - Pretty powerful tooltips.
* [tooltipster ★2319](https://github.com/iamceege/tooltipster) - A jQuery tooltip plugin.
* [simptip ★626](https://github.com/arashmanteghi/simptip) - A simple CSS tooltip made with Sass.
* [jquery-popup-overlay ★413](https://github.com/vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips.
* [toolbar ★2333](https://github.com/paulkinzett/toolbar) - A tooltip style toolbar jQuery plugin
* [hint.css ★7404](https://github.com/chinchang/hint.css) - A tooltip library in CSS for your lovely websites.

## Modals and Popups

* [Magnific-Popup ★9539](https://github.com/dimsemenov/Magnific-Popup) - Light and responsive lightbox script with focus on performance.
* [jquery-popbox ★450 ⏳1Y](https://github.com/gristmill/jquery-popbox) - jQuery PopBox UI Element.
* [jquery.avgrund.js ★1825 ⏳1Y](https://github.com/voronianski/jquery.avgrund.js) - A jQuery plugin with new modal concept for popups.
* [vex ★6241](https://github.com/HubSpot/vex) - A modern dialog library which is highly configurable and easy to style.
* [bootstrap-modal ★5047 ⏳2Y](https://github.com/jschr/bootstrap-modal) - Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more.
* [css-modal ★1680](https://github.com/drublic/css-modal) - A modal built out of pure CSS.
* [jquery-popup-overlay ★413](https://github.com/vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips.
* [SweetAlert ★16313](https://github.com/t4t5/sweetalert) - An awesome replacement for JavaScript's alert.
* [baguetteBox.js ★1282](https://github.com/feimosi/baguetteBox.js) - Simple and easy to use lightbox script written in pure JavaScript.
* [colorbox ★4656](https://github.com/jackmoore/colorbox) - A light-weight, customizable lightbox plugin for jQuery.
* [fancyBox ★4742](https://github.com/fancyapps/fancyBox) - A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages.
* [swipebox ★1814](https://github.com/brutaldesign/swipebox) - A touchable jQuery lightbox
* [jBox ★854](https://github.com/StephanWagner/jBox) - jBox is a powerful and flexible jQuery plugin, taking care of all your popup windows, tooltips, notices and more.

## Scroll

* [scrollMonitor ★2373](https://github.com/stutrek/scrollMonitor) - A simple and fast API to monitor elements as you scroll.
* [headroom ★9313](https://github.com/WickyNilliams/headroom.js) - Give your pages some headroom. Hide your header until you need it.
* [onepage-scroll ★9101 ⏳1Y](https://github.com/peachananr/onepage-scroll) - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin.
* [iscroll ★9842](https://github.com/cubiq/iscroll) - iScroll is a high performance, small footprint, dependency free, multi-platform javascript scroller.
* [skrollr ★17274 ⏳1Y](https://github.com/Prinzhorn/skrollr) - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery.
* [parallax ★11768](https://github.com/wagerfield/parallax) - Parallax Engine that reacts to the orientation of a smart device.
* [stellar.js ★4249](https://github.com/markdalgleish/stellar.js) - Parallax scrolling made easy.
* [plax ★2322](https://github.com/cameronmcefee/plax) - jQuery powered parallaxing.
* [jparallax ★1130 ⏳1Y](https://github.com/stephband/jparallax) - jQuery plugin for creating interactive parallax effect.
* [fullPage ★20024](https://github.com/alvarotrigo/fullPage.js) - A simple and easy to use plugin to create fullscreen scrolling websites (also known as single page websites).
* [ScrollMenu ★171](https://github.com/s-yadav/ScrollMenu) - A new interface to replace old boring scrollbar.
* [Clusterize.js ★5252](https://github.com/NeXTs/Clusterize.js) - Tiny vanilla JS plugin to display large data sets easily.


## Menu

* [jQuery-menu-aim ★7495](https://github.com/kamens/jQuery-menu-aim) - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's.
* [jQuery contextMenu] (https://github.com/swisnl/jQuery-contextMenu) -  contextMenu manager.
* [Slideout ★6694](https://github.com/mango/slideout) - A responsive touch slideout navigation menu for mobile web apps.
* [Slide and swipe ★85](https://github.com/JoanClaret/slide-and-swipe-menu) - A sliding swipe menu that works with touchSwipe library.


## Table/Grid

* [jTable ★829](https://github.com/hikalkan/jtable) - A jQuery plugin to create AJAX based CRUD tables.
* [DataTables](https://www.datatables.net/) - (jQuery plug-in) It is a highly flexible tool, based upon the foundations of progressive enhancement, and will add advanced interaction controls to any HTML table.
* [floatThead ★873](https://github.com/mkoryak/floatThead) - (jQuery plug-in) lock any table's header while scrolling within the body. Works on any table and requires no custom html or css.
* [Masonry](http://masonry.desandro.com/) - A cascading grid layout library.
* [Packery](http://packery.metafizzy.co/) - A grid layout library that uses a bin-packing algorithm. Useable for draggable layouts.
* [Isotope](http://isotope.metafizzy.co/) - A filterable, sortable, grid layout library. Can implement Masonry, Packery, and other layouts.
* [flexboxgrid ★6313](https://github.com/kristoferjoseph/flexboxgrid) - Grid based on CSS3 flexbox

## Frameworks

* [Semantic UI](http://semantic-ui.com/) - UI Kit with lots of themes and elements
* [w2ui](http://w2ui.com/) - A set of jQuery plugins for front-end development of data-driven web applications.
* [fluidity ★1119 ⏳1Y](https://github.com/mrmrs/fluidity) - The worlds smallest fully-responsive css framework
* [Ink ★1903](https://github.com/sapo/Ink) - An HTML5/CSS3 framework used at SAPO for fast and efficient website design and prototyping

## Boilerplates

 * [html5-boilerplate ★37891](https://github.com/h5bp/html5-boilerplate) - A professional front-end template for building fast, robust, and adaptable web apps or sites.
 * [mobile-boilerplate ★4027 ⏳2Y](https://github.com/h5bp/mobile-boilerplate) - A front-end template that helps you build fast, modern mobile web apps.
 * [webplate ★583](https://github.com/chrishumboldt/webplate) - An awesome front-end framework that lets you stay focused on building your site or app while remaining really easy to use.
 * [Cerberus ★2369](https://github.com/TedGoas/Cerberus) - A few simple, but solid patterns for responsive HTML emails. Even in Outlook.
 * [full-page-intro-and-navigation ★30 ⏳2Y](https://github.com/CodyHouse/full-page-intro-and-navigation) - An intro page with a full width background image, a bold animated menu and an iOS-like blurred effect behind the navigation
 * [Fluid-Squares ★27 ⏳2Y](https://github.com/crozynski/Fluid-Squares) - A fluid grid of square units.
 * [Mobile-First-RWD ★55 ⏳5Y](https://github.com/bradfrost/Mobile-First-RWD) - An example of a mobile-first responsive web design
 * [this-is-responsive ★1485](https://github.com/bradfrost/this-is-responsive) - This Is Responsive
 * [npm run-scripts](https://gist.github.com/addyosmani/9f10c555e32a8d06ddb0) Task automation with NPM run-scripts.

## Gesture

* [hammer.js ★16675](https://github.com/hammerjs/hammer.js) - A javascript library for multi-touch gestures.
* [touchemulator ★167](https://github.com/hammerjs/touchemulator) - Emulate touch input on your desktop.
* [Dragula] (https://github.com/bevacqua/dragula/) - Drag and drop so simple it hurts


## Maps

* [Leaflet ★19040](https://github.com/Leaflet/Leaflet) - JavaScript library for mobile-friendly interactive maps.
* [Cesium ★2353](https://github.com/AnalyticalGraphicsInc/cesium) - Open Source WebGL virtual globe and map engine.
* [gmaps ★6729](https://github.com/HPNeo/gmaps) - The easiest way to use Google Maps.
* [polymaps ★1454 ⏳2Y](https://github.com/simplegeo/polymaps) - A free JavaScript library for making dynamic, interactive maps in modern web browsers.
* [kartograph.js ★1496](https://github.com/kartograph/kartograph.js) - Open source JavaScript renderer for Kartograph SVG maps.
* [mapbox.js ★1448](https://github.com/mapbox/mapbox.js) - Mapbox JavaScript API, a Leaflet Plugin.
* [jqvmap ★1480](https://github.com/manifestinteractive/jqvmap) - jQuery Vector Map Library.
* [OpenLayers3](http://openlayers.org/) - A high-performance, feature-packed library for all your mapping needs.

## Video/Audio

 * [prettyembed.js ★1059](https://github.com/mike-zarandona/prettyembed.js) - Prettier embeds for your YouTubes - with nice options like high-res preview images, advanced customization of embed options, and optional FitVids support.
 * [html5media ★970](https://github.com/etianen/html5media) -  Enables <video> and <audio> tags in all major browsers. <https://html5media.info/>
 * [Play-em JS ★43](https://github.com/adrienjoly/playemjs) -  Play'em is a javascript component that manages a music/video track queue and plays a sequence of songs by embedding several players in a HTML DIV including Youtube, Soundcloud and Vimeo.
 * [polyplayer ★33 ⏳2Y](https://github.com/Acconut/polyplayer) - Rule YouTube, Soundcloud and Vimeo player with one API
 * [flowplayer ★1471](https://github.com/flowplayer/flowplayer) -  The HTML5 video player for the web
 <https://flowplayer.org/>
 * [mediaelement](https://github.com/johndyer/mediaelement) -  HTML5 <audio> or <video> player with Flash and Silverlight shims that mimics the HTML5 MediaElement API, enabling a consistent UI in all browsers. <http://mediaelementjs.com/>
 * [SoundJS ★2418](https://github.com/CreateJS/SoundJS) - A library to make working with audio on the web easier. It provides a consistent API for playing audio in different browsers.
 * [video.js ★17052](https://github.com/videojs/video.js) - Video.js - open source HTML5 & Flash video player
 * [FitVids.js ★4518](https://github.com/davatron5000/FitVids.js) - A lightweight, easy-to-use jQuery plugin for fluid width video embeds.
 * [Ion.Sound ★597](https://github.com/IonDen/ion.sound) - Simple sounds on any web page
 * [photobooth-js ★580 ⏳1Y](https://github.com/WolframHempel/photobooth-js) - A widget that allows users to take their avatar pictures on your site
 * [clappr ★3666](https://github.com/clappr/clappr) - An extensible media player for the web http://clappr.io

## Typography

 * [FlowType.JS ★4413](https://github.com/simplefocus/FlowType.JS) - Web typography at its finest: font-size and line-height based on element width.
 * [BigText ★821](https://github.com/zachleat/BigText) - jQuery plugin, calculates the font-size and word-spacing needed to match a line of text to a specific width.
 * [circletype ★311](https://github.com/peterhry/circletype) - A jQuery plugin that lets you curve type on the web
 * [slabText ★1324](https://github.com/freqDec/slabText) - A jQuery plugin for producing big, bold & responsive headlines
 * [simple-text-rotator ★661](https://github.com/peachananr/simple-text-rotator) - Add a super simple rotating text to your website with little to no markup
 * [novacancy.js ★140](https://github.com/chuckyglitch/novacancy.js) - Text Neon Golden effect jQuery plug-in.
 * [jquery-responsive-text ★121 ⏳2Y](https://github.com/ghepting/jquery-responsive-text) - Make your text sizing responsive!
 * [FitText.js ★6364](https://github.com/davatron5000/FitText.js) - A jQuery plugin for inflating web type
 * [Lettering.js ★4856](https://github.com/davatron5000/Lettering.js) - A lightweight, easy to use Javascript `<span>` injector for radical Web Typography


## Animations

* [velocity ★13248](https://github.com/julianshapiro/velocity) - Accelerated JavaScript animation.
* [jquery.transit ★7347 ⏳1Y](https://github.com/rstacruz/jquery.transit) - Super-smooth CSS3 transformations and transitions for jQuery.
* [imrpess.js ★31992](https://github.com/impress/impress.js) - Make Prezi-like presentations with CSS3 transformations/transitions in an HTML document.
* [bounce.js ★5142 ⏳2Y](https://github.com/tictail/bounce.js) - Create tasty CSS3 powered animations in no time.
* [GreenSock-JS ★6382](https://github.com/greensock/GreenSock-JS) - High-performance HTML5 animations that work in all major browsers.
* [TransitionEnd ★86 ⏳1Y](https://github.com/EvandroLG/transitionEnd) - TransitionEnd is an agnostic and cross-browser library to work with transitionend event.
* [Dynamic.js ★6449](https://github.com/michaelvillar/dynamics.js) - Javascript library to create physics-based CSS animations.
* [the-cube ★6 ⏳4Y](https://github.com/pstadler/the-cube) - The Cube is an experiment with CSS3 transitions.
* [Effeckt.css ★11043 ⏳1Y](https://github.com/h5bp/Effeckt.css) - A Performant Transitions and Animations Library
* [animate.css ★43771](https://github.com/daneden/animate.css) - A cross-browser library of CSS animations. As easy to use as an easy thing.
* [textillate ★3021](https://github.com/jschr/textillate) - A simple plugin for CSS3 text animations
* [move.js ★4081](https://github.com/visionmedia/move.js) - CSS3 backed JavaScript animation framework
* [animatable ★2282 ⏳2Y](https://github.com/LeaVerou/animatable) - One property, two values, endless possiblities
* [shuffle-images ★175 ⏳1Y](https://github.com/peachananr/shuffle-images) -  The Simplest Way to shuffle through images in a Creative Way http://www.thepetedesign.com/demos/shuffle-images_demo.html
* [smoothState.js ★4041](https://github.com/miguel-perez/smoothState.js) - Unobtrusive page transitions with jQuery. http://smoothstate.com/

## Image Processing

* [lena.js ★121](https://github.com/davidsonfellipe/lena.js) - A Library for image processing with filters and util functions.
* [pica ★825](https://github.com/nodeca/pica) - High quality image resize (with fast Lanczos filter, implemented in pure JS).
* [cropper ★5654](https://github.com/fengyuanchen/cropper) - A simple jQuery image cropping plugin.


## ES6

* [es6features ★21139](https://github.com/lukehoban/es6features) - Overview of ECMAScript 6 features.
* [es6-features ★3761](https://github.com/rse/es6-features) - ECMAScript 6: Feature Overview & Comparison.
* [es6-cheatsheet ★9776](https://github.com/DrkSephy/es6-cheatsheet) - ES2015 [ES6] cheatsheet containing tips, tricks, best practices and code snippets.
* [ECMAScript 6 compatibility table](http://kangax.github.io/compat-table/es6/) - Compatibility tables for all ECMAScript 6 features on a variety of environments.
* [Babel (Formerly 6to5) ★21932](https://github.com/babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime.
* [Traceur compiler ★7377](https://github.com/google/traceur-compiler) - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.


## SDK

* [javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) - Javascript SDK design guide extracted from work and personal experience
* [Spotify SDK ★131](https://github.com/loverajoel/spotify-sdk) - Entity oriented SDK to work with the Spotify Web API.


## Misc

* [echo ★3381](https://github.com/toddmotto/echo) - Lazy-loading images with data-* attributes.
* [picturefill ★9224](https://github.com/scottjehl/picturefill) - A responsive image polyfill for &lt;picture&gt;, srcset, sizes.
* [platform.js ★1635](https://github.com/bestiejs/platform.js) - A platform detection library that works on nearly all JavaScript platforms.
* [json3 ★955](https://github.com/bestiejs/json3) - A modern JSON implementation compatible with nearly all JavaScript platforms.
* [Logical Or Not](http://gabinaureche.com/logicalornot/) - A game about JavaScript specificities.
* [BitSet.js ★120](https://github.com/infusion/BitSet.js) - A JavaScript Bit-Vector implementation
* [spoiler-alert ★477](https://github.com/joshbuddy/spoiler-alert) - SPOILER ALERT! A happy little jquery plugin to hide spoilers on your site.
* [jquery.vibrate.js ★130 ⏳1Y](https://github.com/illyism/jquery.vibrate.js) - Vibration API Wrappers
* [list.js ★8122](https://github.com/javve/list.js) -  Adds search, sort, filters and flexibility to tables, lists and various HTML elements. Built to be invisible and work on existing HTML.
http://www.listjs.com
* [mixitup ★3824](https://github.com/patrickkunka/mixitup) - MixItUp - A Filter & Sort Plugin
* [grid ★3237](https://github.com/hootsuite/grid) - Drag and drop library for two-dimensional, resizable and responsive lists.
* [jquery-match-height ★2611](https://github.com/liabru/jquery-match-height) - a responsive equal heights plugin for jQuery.
* [survey.js ★587](https://github.com/surveyjs/surveyjs) - JavaScript Survey Engine. It uses JSON for survey metadata and results. http://surveyjs.org/

## Podcasts
* [JavaScript Air](https://javascriptair.com/) - The live video broadcast podcast all about JavaScript and the Web platform.
* [Web of Tomorrow](http://www.weboftomorrowpodcast.com/) - Podcast about JavaScript for beginners.
* [Javascript Jabber](https://devchat.tv/js-jabber) - A weekly podcast about JavaScript, including Node.js, Front-End Technologies, Careers, Teams and more.

# Worth Reading
* [braziljs/js-the-right-way ★6511](https://github.com/braziljs/js-the-right-way)
* [JSbooks ★1957](https://github.com/revolunet/JSbooks)
* [Superhero.js](http://superherojs.com) - A collection of resources about creating, testing and maintaining a large JavaScript code base.
* [SJSJ ★2015](https://github.com/HugoGiraudel/SJSJ) - Simplified JavaScript Jargon is a community-driven attempt at explaining the loads of buzzwords making the current JavaScript ecosystem in a few simple words.
* [How to Write an Open Source JavaScript Library ★87](https://github.com/sarbbottam/write-an-open-source-js-lib) - A comprehensive guide through a set of steps to publish a JavaScript open source library.


# Other Awesome Lists
* [sotayamashita/awesome-css ★1073](https://github.com/sotayamashita/awesome-css)
* [emijrp/awesome-awesome ★857](https://github.com/emijrp/awesome-awesome)
* [bayandin/awesome-awesomeness ★19353](https://github.com/bayandin/awesome-awesomeness)
* [sindresorhus/awesome ★62884](https://github.com/sindresorhus/awesome)
* [jnv/list ★4413](https://github.com/jnv/lists)
* [gianarb/angularjs ★2189](https://github.com/gianarb/awesome-angularjs)
* [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo)
* [addyosmani/es6-tools ★3466](https://github.com/addyosmani/es6-tools)
* [ericdouglas/ES6-Learning ★3942](https://github.com/ericdouglas/ES6-Learning)
* [obetomuniz/awesome-webcomponents ★122](https://github.com/obetomuniz/awesome-webcomponents)
* [willianjusten/awesome-svg ★3269](https://github.com/willianjusten/awesome-svg)
* [davidsonfellipe/awesome-wpo ★5960](https://github.com/davidsonfellipe/awesome-wpo)
* [instanceofpro/awesome-backbone ★364](https://github.com/sadcitizen/awesome-backbone)
* [enaqx/awesome-react ★20614](https://github.com/enaqx/awesome-react)
* [bolshchikov/js-must-watch ★11278](https://github.com/bolshchikov/js-must-watch)
* [peterkokot/awesome-jquery](https://github.com/peterkokot/awesome-jquery)
* [dinbror/you-might-not-need-jquery-plugins ★9 ⏳1Y](https://github.com/dinbror/you-might-not-need-jquery-plugins)
* [MaximAbramchuck/awesome-interviews ★15575](https://github.com/MaximAbramchuck/awesome-interview-questions)


# Contributing

Contributions welcome! Read the [contribution guidelines](https://github.com/sorrycc/awesome-javascript/blob/master/CONTRIBUTING.md) first.


# License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [chencheng](https://github.com/sorrycc) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/sorrycc/awesome-javascript">sorrycc/awesome-javascript</a> with ranks
</p>
