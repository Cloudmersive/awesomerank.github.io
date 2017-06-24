---
layout: default
title: Awesome Rank for stoeffel/awesome-fp-js
---

<p align="center">
	This list is a copy of <a href="https://github.com/stoeffel/awesome-fp-js">stoeffel/awesome-fp-js</a> with ranks
</p>
---
# Awesome FP JS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)

This is a curated list of awesome [functional programming](https://en.wikipedia.org/wiki/Functional_programming) code and learning resources for JavaScript. As a multi-paradigm programming language, JavaScript can be written in many styles. With these resources we want to help you to make better use of JavaScript’s support for writing programs in a _functional_ way.

Functional programming is a [style of programming](https://wiki.haskell.org/Functional_programming) which models computations as the evaluation of expressions. Contrast this  with imperative programming where programs are composed of statements which change global state when executed. Functional programming typically avoids using mutable state and favors _side-effect free_ functions and _immutable_ data instead. This encourages writing composable and declarative programs that are easy to reason about.

##### Table of Contents

* [Libraries](#libraries)
  * [Data Structures](#data-structures)
  * [Algebraic Data Types](#algebraic-data-types)
  * [Lenses](#lenses)
* [Functional Languages that Compile to JavaScript](#functional-languages-that-compile-to-javascript)
* [Programming Tools](#programming-tools)
* [Resources](#resources)
  * [Books](#books)
  * [Articles](#articles)
  * [Videos](#videos)
  * [Examples and Exercises](#examples-and-exercises)
* [Community](#community)
* [Contribution](#contribution)

## Libraries

* [Ramda ★8190](https://github.com/ramda/ramda) – A practical functional library for JavaScript that is designed specifically for a functional programming style. A style that makes it easy to create functional pipelines and never mutates user data.
* [Folktale](http://folktalejs.org/) – Folktale is a suite of libraries for generic functional programming that allows you to write elegant modular applications with fewer bugs and more reuse.
* [lodash/fp](https://github.com/lodash/lodash/wiki/FP-Guide) – An instance of [Lodash ★23692](https://github.com/lodash/lodash) with its methods wrapped to produce immutable, auto-curried, iteratee-first, data-last methods.
* [functional.js](http://functionaljs.com) – A lightweight functional JavaScript library that facilitates currying and point-free / tacit programming.
* [101 ★1497](https://github.com/tjmehta/101) – A modern and modular JavaScript utility library made to work well with vanilla JavaScript methods.
* [fnuc ★15 ⏳1Y](https://github.com/algesten/fnuc) – A functional library for CoffeeScript (and JavaScript) to facilitate functional composition and higher order functions.
* [barely-functional ★40](https://github.com/cullophid/barely-functional) – A tiny (2.7kb) functional programming library using native ES5/6 operations.
* [bluebird-promisell ★38](https://github.com/zhangchiqing/bluebird-promisell) - A practical functional programming library for promises.
* [prelude.ls](http://gkz.github.io/prelude-ls/) – A functionally oriented utility library somewhat based off of Haskell's Prelude module.
* [preludejs ★51](https://github.com/alanrsoares/prelude-js) - Hardcore Functional Programming for JavaScript.
* [1-liners ★440](https://github.com/1-liners/1-liners) – Functional tools that couldn’t be simpler. A dead simple functional utility belt, hand-crafted with love and attention.
* [fn-curry ★5 ⏳3Y](https://github.com/thunklife/fn-curry) – A simple function to curry a function.
* [curry ★71](https://github.com/thisables/curry) – Curry your functions using function bind syntax.
* [compose-function ★25](https://github.com/stoeffel/compose-function) – Compose a new function from smaller functions.
* [functionize ★42 ⏳2Y](https://github.com/paldepind/functionize) – A collection of functions which aid in making non-functional libraries functional.
* [lambdajs ★122 ⏳3Y](https://github.com/loop-recur/lambdajs) – The full ECMAScript API done a functional way.
* [fp-dom](https://github.com/fp-dom/) – Making the DOM functional.
* [trifl ★33](https://github.com/algesten/trifl) – A functional user interface library with unidirectional dataflow and a virtual dom.
* [funcy ★198](https://github.com/bramstein/funcy) – An experiment in adding functional pattern matching to JavaScript. _Experimental_  :triangular_flag_on_post:
* [date-fp ★86](https://github.com/cullophid/date-fp) – A functional utility library for working with JavaScript dates. All functions in date-fp are pure, autocurried and will not mutate the date objects they are applied to.
* [js-joda ★448](https://github.com/js-joda/js-joda) – An immutable date and time library that provides a simple, domain-driven and clean API based on the ISO8601 calendar.
* [\_part\_ ★46 ⏳3Y](https://github.com/AutoSponge/_part_) – A micro library that encourages functional programming by making native methods available as partially applied functions.
* [claire](https://github.com/robotlolita/claire) – A property-based testing library for clearly specifying code invariants and behaviour.
* [FPO.js ★229](https://github.com/getify/fpo) – FP library for JavaScript by Kyle Simpson (aka getify). Supports named-argument style methods.
* [Javascript Parser Combinator ★21](https://github.com/d-plaindoux/parsec) – Javascript parser combinator implementation inspired by the Haskell's Parsec
* [fun-task ★197](https://github.com/rpominov/fun-task) – An abstraction for managing asynchronous code in JS. Tasks are similar to Promises with the key difference that Tasks can represent a computation while Promises can represent only the results of a computation. Ships with Flow type definitions.
* [most ★1962](https://github.com/cujojs/most) – Ultra-high performance reactive programming to help you compose asynchronous operations on streams of values and events without many of the hazards of side effects and mutable shared state.


### Data Structures

Write performant functional code by using the right data structures for the task.

* [Icepick ★264](https://github.com/aearly/icepick) Utilities for treating frozen JavaScript objects as persistent immutable collections
* [Immutable.js ★18899](https://github.com/facebook/immutable-js) – Immutable persistent data collections.
* [Mori ★2607](https://github.com/swannodette/mori) – ClojureScript’s persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [Baobab ★2578](https://github.com/Yomguithereal/baobab) – persistent and optionally immutable data tree with cursors.
* [immutable-sequence.js](https://github.com/qiao/immutable-sequence.js) –  High performance implementation of Immutable Sequence in JavaScript, based on [Finger Trees ★17](https://github.com/qiao/fingertree.js).
* [Timm](http://guigrpa.github.io/timm/) – Immutability helpers with fast reads and acceptable writes.
* [Lazy.js ★4154](https://github.com/dtao/lazy.js) – A utility library with a lazy engine under the hood that strives to do as little work as possible while being as flexible as possible.
* [DerivableJS ★384](https://github.com/ds300/derivablejs) – Functional Reactive State for JavaScript and TypeScript. DerivableJS enables you to make elegant declarative statements about how your bits of state are related.
* [imlazy ★38](https://github.com/benji6/imlazy) – Library for creating and manipulating lazy iterables using the ES2015 iteration protocols.


### Algebraic Data Types

Use the laws of math instead of always reinventing your own thing. Algebraic!

* [Fantasy Land ★3698](https://github.com/fantasyland/fantasy-land) – Not a library, but a specification of the Monad laws for libraries to follow.
* [Static Land ★265](https://github.com/rpominov/static-land) – Specification similar to Fantasy Land but based on static methods rather than instance methods.
* [immutable-ext](https://github.com/DrBoolean/immutable-ext) – FantasyLand extensions for [Immutable.js ★18899](https://github.com/facebook/immutable-js).
* [daggy](https://github.com/puffnfresh/daggy) – Library for creating tagged constructors.
* [Sanctuary](https://github.com/plaid/sanctuary) – Sanctuary makes it possible to write safe code without null checks.
* [monet.js](http://cwmyers.github.io/monet.js/) – A library that assists functional programming by providing a rich set of Monads and other useful functions.
* [union-type ★314](https://github.com/paldepind/union-type) – A small JavaScript library for defining and using union types.
* [freeky ★87](https://github.com/DrBoolean/freeky) – A collection of Free monads.
* [Fluture](https://github.com/Avaq/Fluture) – A Future library with included control utilities, high performance and great error messages.
* [fantasy-combinators ★40 ⏳1Y](https://github.com/fantasyland/fantasy-combinators) – Common combinators.
* [fantasy-birds ★41](https://github.com/fantasyland/fantasy-birds) – Port of the Haskell package Data.Aviary.Birds. Everything for your combinatory needs.
* [crocks ★62](https://github.com/evilsoft/crocks) – A collection of popular Algebraic Data Types with the main goal to curate and provide not only a common interface between each type, but also all of the helper functions needed to hit the ground running.

### Lenses

* [lenses](https://github.com/DrBoolean/lenses) – Composable [kmett ★1059](https://github.com/ekmett/lens) style lenses.
* [optics ★39 ⏳1Y](https://github.com/flunc/optics) – Profunctor optics (Lens, Prism, iso).
* [ramda-lens ★130](https://github.com/ramda/ramda-lens) – :ram: :mag_right: Lens library built on Ramda.
* [fantasy-lenses ★97 ⏳1Y](https://github.com/fantasyland/fantasy-lenses) – Composable, immutable getters and setters. (Profunctor lenses WIP)
* [nanoscope ★149](https://github.com/5outh/nanoscope) – Lenses with dotty support.
* [partial.lenses ★226](https://github.com/calmm-js/partial.lenses) – Partial lenses is a comprehensive, high-performance optics library for JavaScript.

## Functional Languages that Compile to JavaScript

* [ClojureScript ★7020](https://github.com/clojure/clojurescript) – Compiles [Clojure](http://clojure.org/), a hosted Lisp with immutable persistent data structures, to JavaScript.
* [Elm](http://elm-lang.org/) – A type-safe functional programming language for declaratively creating web browser-based graphical user interfaces. Implemented in Haskell.
* [Fable](http://fable.io/) - Compiles [F#](http://fsharp.org) to readable JavaScript.
* [PureScript](http://www.purescript.org/) – A small strongly typed programming language that compiles to JavaScript.
* [Idris](http://www.idris-lang.org/) – A general purpose pure functional programming language with dependent types.
* [GHCJS ★1647](https://github.com/ghcjs/ghcjs) – [Haskell](https://www.haskell.org/) to JavaScript compiler, based on GHC.
* [ElixirScript](https://github.com/bryanjos/elixirscript) – Compiles a subset of [Elixir](http://elixir-lang.org/), a dynamic, functional language designed for building scalable and maintainable applications, to JavaScript.
* [Js\_of\_ocaml](http://ocsigen.org/js_of_ocaml/) – Compiles [OCaml](http://ocaml.org/) bytecode to JavaScript, making it possible to run OCaml programs in the browser.
* [BuckleScript](https://bloomberg.github.io/bucklescript/) – JavaScript backend for [the OCaml compiler](https://ocaml.org/).
* [Reason](http://facebook.github.io/reason/) – Reason is a new interface to OCaml, a highly expressive dialect of the ML language featuring type inference and static type checking.
* [Scala.js](http://www.scala-js.org/) – Compiles [Scala](http://www.scala-lang.org/) to JavaScript.
* [LiveScript](http://gkz.github.io/LiveScript/) – LiveScript has a straightforward mapping to JavaScript and allows you to write expressive code devoid of repetitive boilerplate.
* [Quack ★138](https://github.com/quack/quack) - A multi-paradigm programming language with gradual and duck typing that targets PHP and JS.

## Programming Tools

* [eslint-plugin-fp ★224](https://github.com/jfmengels/eslint-plugin-fp) - ESLint rules for functional programming
* [eslint-config-cleanjs ★896](https://github.com/bodil/eslint-config-cleanjs) - An eslint config which reduces JS to a pure functional language
* [4.5 ★12](https://github.com/TylorS/4.5) – A functional assertions library. If you prefer functional style APIs and practices in JavaScript, this library aims to solve this with functionally-oriented assertions that are lazy and monadic.
* [hm-def ★10](https://github.com/xodio/hm-def) – Runtime type checking for JS with Hindley Milner signatures.

## Resources

### Books

* [Professor Frisby’s Mostly Adequate Guide to Functional Programming](https://github.com/MostlyAdequate/mostly-adequate-guide) – This is a book on the functional paradigm in general using the world’s most popular functional programming language: JavaScript. It’s a practical introduction that builds up intuition through real-world examples. Strongly recommended. By [Brian Lonsdorf](https://twitter.com/drboolean) (2016)
* [Functional-Light JavaScript ★3429](https://github.com/getify/functional-light-js) – This book explores the core principles of functional programming (FP) that can be applied to JavaScript. But what makes this book different is that it approaches these principles without all the heavy terminology.
* [JavaScript Allongé](https://leanpub.com/javascriptallongesix), the “Six” edition. Starts with as little as possible about functions – but no less! – and builds up towards powerful combinators and decorators. A foundational book. By [Reginald  Braithwaite](https://github.com/raganwald) (2016)
* [Functional Programming in JavaScript](https://www.manning.com/books/functional-programming-in-javascript) teaches JavaScript developers functional techniques that will improve extensibility, modularity, reusability, testability, and performance. Through concrete examples and jargon-free explanations, this book teaches you how to apply functional programming to real-life development tasks. By Luis Atencio (2016)
* [Eloquent JavaScript](http://eloquentjavascript.net/). A modern introduction to programming using JavaScript. By Marijn Haverbeke (2014)
* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) teaches how to create code that’s beautiful, safe, and simple to understand and test by using JavaScript’s functional programming support. By [Michael Fogus](https://github.com/fogus) (2013)

### Articles

* [FP Concepts in JavaScript](https://medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-b0650773139c) – An introduction to Functional Programming Concepts in JavaScript. Uses the Ramda library to teach the concepts of composition, pointfree style, and functors through the simplest of examples.
* [Functional programming with JavaScript](http://stephen-young.me.uk/2013/01/20/functional-programming-with-javascript.html) – Another introduction to Functional Programming in JavaScript with a focus on three key themes: computation as the application of functions, statelessness, avoiding side effects.
* [A gentle introduction to functional JavaScript](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/) – A four-part series introduction functional programming in JavaScript that gets you up to speed what all the hype about functional programming is all about.
* [Why Curry Helps](https://hughfdjackson.com/javascript/why-curry-helps/) – A short overview of how to write reusable and declarative code using currying.
* [Favoring Curry](http://fr.umio.us/favoring-curry/) - Practical applications of currying using Ramda.
* [Functional Mumbo Jumbo – ADTs](http://blog.jenkster.com/2016/06/functional-mumbo-jumbo-adts.html) – A beginner-friendly introduction to Algebraic Data Types.
* [JavaScript and Type Thinking](https://medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d) – Learn to reason about your JavaScript code with _type thinking_. Algebraic Data Types are introduced as a conceptual basis to reason about program entities.
* [Lazy, composable, and modular JavaScript](https://codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript) – Use four new features of ES6 – iterables, generators, fat arrows, and for-of – in conjunction with higher-order functions, function composition, and lazy evaluation, to write cleaner and more modular JavaScript.
* [Why Ramda](http://fr.umio.us/why-ramda/) – To those not used to functional programming, Ramda seems to serve no purpose whatsoever. However, it does offer a different style of coding, a style that’s taken for granted in purely functional programming languages: Ramda makes it simple for you to build complex logic through functional composition.
* [Monads in JavaScript](https://curiosity-driven.org/monads-in-javascript) – An introduction to the Monad design pattern in JavaScript.
* [A Monad in Practicality: First-Class Failures](http://robotlolita.me/2013/12/08/a-monad-in-practicality-first-class-failures.html) – A walk through some practical use cases for specific monadic structures in JavaScript: use the `Maybe` monad to handle simple failure cases and model more complex scenarios with the `Either` monad or the `Validation` applicative functor.
* [Functional programming](https://glebbahmutov.com/blog/tags/functional/) – Many articles on various aspects of functional programming in JavaScript by Gleb Bahmutov.
* [Functional Programming Jargon ★9011](https://github.com/hemanth/functional-programming-jargon) – Jargon from the functional programming world explained in JavaScript.
* [Data Structures in JavaScript](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/) – A series of blog posts that reimplements various data structures in JavaScript to better understand their benefits and downsides.
* [So You Want to be a Functional Programmer](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536) - Easy to understand, with some examples, introduction to Functional Programming in Javascript and Elm.
* [Functional Programming for JavaScript People](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504) - A complete introduction to functional programming patterns by Chet Corcos with a lot of javascript examples.
* [Introduction to Immutable.js and Functional Programming Concepts](https://auth0.com/blog/intro-to-immutable-js/) - Learn about functional data structures and their uses in this overview of Facebook's popular library for JavaScript: Immutable.js.
* [Master the JavaScript Interview: What is Functional Programming?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0) - A simple introduction by @ericelliott to functional principles and vocabulary. 
* [Composing Software](https://medium.com/javascript-scene/the-rise-and-fall-and-rise-of-functional-programming-composable-software-c2d91b424c8c) - A series of articles on learning functional programming and compositional software techniques in JavaScript ES6+ from the ground up by @ericelliott.

### Videos

* [Classroom Coding with Prof. Frisby](https://www.youtube.com/watch?v=h_tkIpwbsxY&list=PLK_hdtAJ4KqX0JOs_KMAmUNTNMRYhWEaC) – A series that builds a “practical” web application with React and functional programming in JavaScript.
* [Hey Underscore, You're Doing It Wrong!](https://www.youtube.com/watch?v=m3svKOdZijA) – Underscore.js claims to be a functional programming library, but is it really?
* [Functional programming patterns for the non-mathematician](https://www.youtube.com/watch?v=AvgwKjTPMmM) – Learn about practical use cases for functors, applicatives, and monads.
* [Pure JavaScript](https://vimeo.com/49384334) – Christian Johansen will show you how you can significantly up your game by leaving loops behind and embracing functions as the primary unit of abstraction.
* [Functional programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) - A series by Mattias Petter Johansson, from the youtube channel FunFunFunction, that is specifically about popularization of functional programming in JavaScript.
* [Anjana Vakil: Learning Functional Programming with JavaScript - JSUnconf 2016](https://www.youtube.com/watch?v=e-5obm1G_FY) - A simple and understandable introduction of functional proramming in javascript.

### Examples and Exercises

* [FPJS-Class ★67 ⏳1Y](https://github.com/loop-recur/FPJS-Class) – Functional Programming learned through JavaScript.
* [functional-javascript-workshop ★1436](https://github.com/timoxley/functional-javascript-workshop) – The goal of this workshop is to create realistic problems that can be solved using terse, vanilla, idiomatic JavaScript to teach fundamental functional programming features of JavaScript.
* [functional-frontend-architecture ★872 ⏳1Y](https://github.com/paldepind/functional-frontend-architecture) – A functional frontend framework. Based on Ramda + union-type-js + Flyd + Snabbdom
* [cube-composer ★1132](https://github.com/sharkdp/cube-composer) – A puzzle game inspired by functional programming.
* [FP Youtube Search ★35](https://github.com/jaysoo/example-fp-youtube-search) – YouTube search app with ReactJS, Redux, and FP concepts
* [Hardcore Functional Programming in JavaScript](https://frontendmasters.com/courses/functional-javascript/) – Learn to apply techniques from the forefront of computer science research to solve practical problems in Javascript. Discover functional programming and see it demonstrated step-by-step with how to build an example web app using abstract interfaces like Monads, Functors, Monoids and Applicatives. (_commercial_)
* [Escape from Callback Mountain ★6](https://github.com/justsml/escape-from-callback-mountain) - Design & refactoring tips for Promise-based Functional JavaScript. Key benefits include better readability, testability, and reusability. MIT.

## Community

### Related Lists

* [Awesome FRP JS ★106](https://github.com/stoeffel/awesome-frp-js) – A curated list of awesome (functional) reactive programming stuff in JavaScript.
* [lucasviola/Awesome Functional Programming ★240](https://github.com/lucasviola/awesome-functional-programming) – Awesome resources on functional programming theory and learning materials.
* [xgrommx/Awesome Functional Programming ★1289](https://github.com/xgrommx/awesome-functional-programming) – A ton of articles on functional programming, as well as a huge list of functional libraries for many programming languages.
* [Functional Programming Resources In JavaScript ★196](https://github.com/busypeoples/functional-programming-javascript)

### Talk

* [Functional Programming Slack channel](https://functionalprogramming.slack.com/) – Community with a friendly channel for JavaScript as well as many other channels about functional programming in general.


## Contribution

:star: Suggestions and PRs are welcome! :star:

Please read the [contribution guidelines](./contributing.md) to get started.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christoph Hermann](http://stoeffel.github.io/) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/stoeffel/awesome-fp-js">stoeffel/awesome-fp-js</a> with ranks
</p>
