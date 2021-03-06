---
layout: default
title: Awesome Rank for avelino/awesome-go
---

<p align="center">
	This list is a copy of <a href="https://github.com/avelino/awesome-go">avelino/awesome-go</a> with ranks
</p>
---
# Awesome Go

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★87749](https://github.com/sindresorhus/awesome) [![Slack Widget](https://camo.githubusercontent.com/984828c0b020357921853f59eaaa65aaee755542/68747470733a2f2f73332e65752d63656e7472616c2d312e616d617a6f6e6177732e636f6d2f6e6774756e612f6a6f696e2d75732d6f6e2d736c61636b2e706e67)](http://gophers.slack.com/messages/awesome)

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python ★51865](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)

## Audio and Music

*Libraries for manipulating audio.*

* [EasyMIDI ★9](https://github.com/algoGuy/EasyMIDI) - EasyMidi is a simple and reliable library for working with standard midi file (SMF).
* [flac ★75](https://github.com/eaburns/flac) - Native Go FLAC decoder.
* [flac ★62](https://github.com/mewkiz/flac) - Native Go FLAC decoder.
* [gaad ★41](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
* [go-sox ★71](https://github.com/krig/go-sox) - libsox bindings for go.
* [go_mediainfo ★17 ⏳2Y](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go.
* [gosamplerate ★5](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
* [id3v2 ★64](https://github.com/bogem/id3v2) - Fast and stable ID3 parsing and writing library for Go.
* [malgo ★26](https://github.com/gen2brain/malgo) - Mini audio library.
* [minimp3 ★8](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
* [mix ★81 ⏳1Y](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps.
* [mp3 ★71 ⏳1Y](https://github.com/tcolgate/mp3) - Native Go MP3 decoder.
* [music-theory ★197](https://github.com/go-music-theory/music-theory) - Music theory models in Go.
* [PortAudio ★194](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.
* [portmidi ★168](https://github.com/rakyll/portmidi) - Go bindings for PortMidi.
* [taglib ★55](https://github.com/wtolson/go-taglib) - Go bindings for taglib.
* [vorbis ★20](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies).
* [waveform ★211 ⏳2Y](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams.

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [authboss ★1451](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.
* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
* [cookiestxt ★1](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format.
* [Go-AWS-Auth ★206](https://github.com/smartystreets/go-aws-auth) - AWS (Amazon Web Services) request signing library.
* [go-jose ★888](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
* [go-oauth2-server ★870](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang.
* [gologin ★847](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
* [gorbac ★735](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
* [goth ★1747](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
* [httpauth ★147 ⏳2Y](https://github.com/goji/httpauth) - HTTP Authentication middleware.
* [jwt ★44](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT).
* [jwt ★4](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.
* [jwt-auth ★118](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
* [jwt-go ★3709](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT).
* [loginsrv ★594](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.
* [oauth2 ★1658](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.
* [osin ★1428](https://github.com/RangelReale/osin) - Golang OAuth2 server library.
* [paseto ★123](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO)
* [permissions2 ★265](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.
* [securecookie ★17](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
* [session ★62](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
* [sessiongate-go ★5](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module.
* [sessions ★30](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
* [signedvalue](https://github.com/sashka/signedvalue) - Signed and timestamped strings compatible with [Tornado's ★16057](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`.
* [yubigo ★89 ⏳1Y](https://github.com/GeertJohan/yubigo) - Yubikey client package that provides a simple API to integrate the Yubico Yubikey into a go application.

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [argparse ★31](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.
* [argv ★9](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
* [cli ★383](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
* [cli ★30](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
* [cli-init ★826](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line applications.
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [cobra ★7948](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
* [commandeer ★62](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
* [complete ★462](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
* [docopt.go ★951](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile.
* [drive ★4155](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
* [env ★24](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
* [flag ★76](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand.
* [flagvar ★20](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
* [go-arg ★500](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
* [go-flags ★1064](https://github.com/jessevdk/go-flags) - go command line option parser.
* [gocmd ★14](https://github.com/devfacet/gocmd) - Go library for building command line applications.
* [kingpin ★1911](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands.
* [liner ★452](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
* [mitchellh/cli ★828](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.
* [mow.cli ★525](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
* [pflag ★418](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
* [readline ★1164](https://github.com/chzyer/readline) - Pure golang implementation that provides most features in GNU-Readline under MIT license.
* [sflags ★58](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.
* [strumt ★18](https://github.com/antham/strumt) - Library to create prompt chain.
* [ukautz/clif ★86 ⏳1Y](https://github.com/ukautz/clif) - Small command line interface framework.
* [urfave/cli ★8388](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
* [wlog ★25](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
* [wmenu ★50](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices.

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [aurora ★305](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf.
* [cfmt ★40](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.
* [chalk ★253 ⏳2Y](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
* [color ★2479](https://github.com/fatih/color) - Versatile package for colored terminal output.
* [colourize ★13 ⏳2Y](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.
* [go-ataman ★6](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
* [go-colorable ★280](https://github.com/mattn/go-colorable) - Colorable writer for windows.
* [go-colortext ★174](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
* [go-isatty ★245](https://github.com/mattn/go-isatty) - isatty for golang.
* [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit ★4504](https://github.com/jonathanslenders/python-prompt-toolkit).
* [gocui ★2501](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* [mpb ★235](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
* [progressbar ★290](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
* [tabular ★8](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.
* [termbox-go ★2854](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
* [termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [terminal-tables ★1023](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output.
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib ★11527](https://github.com/yaronn/blessed-contrib).
* [tui-go ★1358](https://github.com/marcusolsson/tui-go) - Go UI library for building rich terminal applications.
* [uilive ★656](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime.
* [uiprogress ★1128](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
* [uitable ★435](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.

## Configuration

*Libraries for configuration parsing.*

* [config ★164](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing.
* [configure ★38](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
* [confita ★47](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct.
* [env ★503](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
* [envcfg ★88 ⏳1Y](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs.
* [envconf ★6 ⏳3Y](https://github.com/ian-kent/envconf) - Configuration from environment.
* [envconfig ★118](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
* [envh ★85](https://github.com/antham/envh) - Helpers to manage environment variables.
* [gcfg ★86](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.
* [go-up ★13](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic.
* [goConfig ★73](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.
* [godotenv ★1261](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
* [gofigure ★52 ⏳1Y](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [hjson ★129](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
* [ingo ★17 ⏳1Y](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
* [ini ★982](https://github.com/go-ini/ini) - Go package to read and write INI files.
* [joshbetz/config ★191](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
* [kelseyhightower/envconfig ★1712](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.
* [mini ★17 ⏳1Y](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
* [store ★222](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
* [viper ★5543](https://github.com/spf13/viper) - Go configuration with fangs.
* [xdg ★5](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

## Continuous Integration

*Tools for help with continuous integration.*

* [drone ★14753](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
* [gomason ★6](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace.
* [goveralls ★486](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.
* [overalls ★91](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.
* [roveralls ★9](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [c6 ★406](https://github.com/c9s/c6) - High performance SASS compatible-implementation compiler written in Go.
* [gcss ★404 ⏳3Y](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.
* [go-libsass ★88](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

## Data Structures

*Generic datastructures and algorithms in Go.*
* [algorithms ★26](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.
* [binpacker ★85](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
* [bit ★20](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
* [bitset ★372](https://github.com/willf/bitset) - Go package implementing bitsets.
* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
* [bloom ★5 ⏳1Y](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
* [boomfilters ★947](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
* [concurrent-writer ★5](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
* [conjungo ★33](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library.
* [count-min-log ★37 ⏳1Y](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
* [cuckoofilter ★322](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
* [deque ★2](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue).
* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go.
* [go-adaptive-radix-tree ★34 ⏳1Y](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
* [go-datastructures ★4210](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
* [go-ef ★5](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.
* [go-geoindex ★278](https://github.com/hailocab/go-geoindex) - In-memory geo index.
* [go-mcache ★9](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches.
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
* [gods ★4267](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* [golang-set ★773](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
* [goset ★6](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
* [goskiplist ★160 ⏳1Y](https://github.com/ryszard/goskiplist) - Skip list implementation in Go.
* [gota ★556](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
* [hilbert ★130](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.
* [hyperloglog ★587](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* [levenshtein ★12 ⏳1Y](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* [levenshtein ★17](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
* [mafsa ★265 ⏳1Y](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing.
* [merkletree ★67](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.
* [mspm ★1](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.
* [roaring ★421](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.
* [skiplist ★54 ⏳3Y](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
* [trie ★273](https://github.com/derekparker/trie) - Trie implementation in Go.
* [ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang.
* [willf/bloom ★482](https://github.com/willf/bloom) - Go package implementing Bloom filters.

## Database

*Databases implemented in Go.*

* [badger ★3895](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
* [BigCache ★1533](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
* [bolt ★8680](https://github.com/boltdb/bolt) - Low-level key/value database for Go.
* [buntdb ★1930](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* [cache2go ★548](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
* [clusteredBigCache ★23](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.
* [cockroach ★13717](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* [couchcache ★33](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
* [dgraph ★5824](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [diskv ★597](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
* [eliasdb ★486](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* [forestdb ★29 ⏳1Y](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
* [GCache ★445](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB ★14117](https://github.com/google/leveldb) key/value database in Go.
* [gorocksdb ★4](https://github.com/kapitan-k/gorocksdb) - Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go.
* [groupcache ★6529](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* [jaeger ★4978](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
* [ledisdb ★2584](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [levigo ★333 ⏳1Y](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
* [moss ★515](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
* [piladb ★160](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
* [prometheus ★17189](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* [rqlite ★3842](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
* [Scribble ★0](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store.
* [slowpoke ★35](https://github.com/recoilme/slowpoke) - Key-value store with persistence.
* [tempdb ★11](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
* [tidb ★13846](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* [tiedot ★2081](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
* [Vasto ★77](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.

*Database schema migration.*

* [darwin ★58](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.
* [go-fixtures ★14](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.
* [gondolier ★17](https://github.com/emvicom/gondolier) - Gondolier is a library to auto migrate database schemas using structs.
* [goose ★76 ⏳1Y](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* [gormigrate ★158](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
* [migrate ★318](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
* [pravasan ★21 ⏳3Y](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc.
* [soda](https://github.com/markbates/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [sql-migrate ★967](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.

*Database tools.*

* [chproxy ★131](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.
* [clickhouse-bulk ★66](https://github.com/nikepan/clickhouse-bulk) - Collects small insterts and sends big requests to ClickHouse servers.
* [go-mysql ★1093](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
* [go-mysql-elasticsearch ★1487](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* [kingshard ★3576](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* [myreplication ★104 ⏳3Y](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication.
* [orchestrator ★1394](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
* [pgweb ★5111](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
* [prep ★19](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code.
* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database.
* [rwdb ★8](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.
* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

*SQL query builder, libraries for building and using SQL.*

* [dat ★520](https://github.com/mgutz/dat) - Go Postgres Data Access Toolkit.
* [Dotsql ★359 ⏳2Y](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.
* [gendry ★331](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.
* [godbal ★44](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
* [goqu ★422](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
* [igor ★65 ⏳1Y](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
* [ozzo-dbx ★241](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* [scaneo ★131](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs.
* [sqrl ★115](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
* [Squirrel ★1561](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [avatica ★13](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql.
    * [bgc ★7](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
    * [firebirdsql ★81](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
    * [go-adodb ★74](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
    * [go-mssqldb ★753](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
    * [go-oci8 ★301](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.
    * [go-sql-driver/mysql ★5629](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
    * [go-sqlite3 ★2546](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
    * [gofreetds ★66](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).
    * [goracle ★96](https://github.com/go-goracle/goracle) - Oracle driver for Go, using the ODPI-C driver
    * [pgx ★1414](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
    * [pq ★3969](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.

* NoSQL Databases
    * [aerospike-client-go ★264](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
    * [arangolite ★60](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
    * [asc ★3](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.
    * [dsc ★5](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
    * [dynago ★56](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB.
    * [go-couchbase ★276](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
    * [go-couchdb ★46](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go.
    * [gocb ★254](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [godscache ★2](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
    * [gomemcache ★918](https://github.com/bradfitz/gomemcache) - memcache client library for the Go programming language.
    * [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
    * [goriak ★22](https://github.com/zegl/goriak) - Go language driver for Riak KV.
    * [mgo ★801](https://github.com/globalsign/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms
    * [mongo-go-driver ★557](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
    * [neo4j ★22 ⏳3Y](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
    * [Neo4j-GO ★66](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.
    * [neoism ★337](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
    * [redigo ★4569](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
    * [redis ★3583](https://github.com/go-redis/redis) - Redis client for Golang.
    * [redis ★562 ⏳1Y](https://github.com/hoisie/redis) - Simple, powerful Redis client for Go.
    * [redis ★207](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
    * [xredis ★7](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.

* Search and Analytic Databases.
    * [bleve ★4446](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
    * [elastic ★2670](https://github.com/olivere/elastic) - Elasticsearch client for Go.
    * [elasticsql ★183](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
    * [elastigo ★910](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
    * [goes ★23 ⏳1Y](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch.
    * [riot ★3614](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine
    * [skizze ★51 ⏳2Y](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.

## Date and Time

*Libraries for working with dates and times.*

* [carbon ★206](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
* [date ★13](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
* [dateparse ★634](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
* [durafmt ★183](https://github.com/hako/durafmt) - Time duration formatting library for Go.
* [feiertage ★12](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
* [go-persian-calendar ★33 ⏳1Y](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
* [go-sunrise ★4](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location.
* [goweek ★14 ⏳1Y](https://github.com/grsmv/goweek) - Library for working with week entity in golang.
* [now ★1721](https://github.com/jinzhu/now) - Now is a time toolkit for golang.
* [NullTime ★6 ⏳1Y](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`.
* [strftime ★1](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter.
* [timespan ★49](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration.
* [timeutil ★143 ⏳2Y](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
* [tuesday ★5](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [celeriac ★37](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
* [consistent ★107](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads.
* [digota ★215](https://github.com/digota/digota) - grpc ecommerce microservice.
* [drmaa ★19](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
* [emitter-io ★1237](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
* [flowgraph ★35](https://github.com/vectaport/flowgraph) - MPI-style ready-send coordination layer.
* [gleam ★1409](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
* [glow ★2090](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
* [go-health ★190](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service.
* [go-jump ★191](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
* [go-kit ★10390](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* [gorpc ★467 ⏳1Y](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
* [grpc-go ★5820](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
* [heimdall ★519](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities.
* [hprose ★776](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
* [jsonrpc ★68](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
* [jsonrpc ★46](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
* [KrakenD ★534](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares.
* [micro ★4573](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform.
* [NATS ★4275](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
* [raft ★1933](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* [redis-lock ★52](https://github.com/bsm/redis-lock) - Simplified distributed locking implementation using Redis.
* [ringpop-go ★469](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
* [rpcx ★2472](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ ★4356](https://github.com/zeromq/libzmq)).
* [tendermint ★1956](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.
* [torrent ★2275](https://github.com/anacrolix/torrent) - BitTorrent client package.
    * [dht](https://godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
    * [go-peerflix ★319 ⏳1Y](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.

## Email

*Libraries and tools that implement email creation and sending.*

* [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
* [douceur ★121](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.
* [email ★898](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
* [go-dkim ★38](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
* [go-imap ★444](https://github.com/emersion/go-imap) - IMAP library for clients and servers.
* [go-message ★52](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.
* [Gomail ★1713](https://github.com/go-gomail/gomail) - Gomail is a very simple and powerful package to send emails.
* [Hectane ★143](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.
* [hermes ★1270](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
* [MailHog ★3560](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.
* [SendGrid ★358](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.
* [smtp ★43](https://github.com/mailhog/smtp) - SMTP server protocol state machine.

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go.
* [anko ★688](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
* [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua ★2184](https://github.com/yuin/gopher-lua).
* [gisp ★393](https://github.com/jcla1/gisp) - Simple LISP in Go.
* [go-duktape ★581](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.
* [go-lua ★1275](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
* [go-php ★489](https://github.com/deuill/go-php) - PHP bindings for Go.
* [go-python ★687](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
* [golua ★395](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
* [gopher-lua ★2184](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
* [ngaro ★13](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
* [otto ★3850](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go.
* [purl ★22 ⏳3Y](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.

## Files

*Libraries for  handling files and file systems.*

* [afero ★1528](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
* [go-csv-tag ★23](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
* [go-gtfs ★5](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
* [notify ★354](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
* [skywalker ★30](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
* [tarfs ★19 ⏳1Y](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.

## Financial

*Packages for accounting and finance.*

* [accounting ★386](https://github.com/leekchan/accounting) - money and currency formatting for golang.
* [decimal ★981](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.
* [go-finance ★548](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go.
* [go-finance ★13](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
* [go-money ★435](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.
* [ofxgo ★39](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).
* [techan ★46](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies.
* [transaction ★21](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode.
* [vat ★42](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.

## Forms

*Libraries for working with forms.*

* [bind ★19 ⏳3Y](https://github.com/robfig/bind) - Bind form data to any Go values.
* [binding ★674](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct.
* [conform ★127](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
* [form ★269](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
* [formam ★100](https://github.com/monoculum/formam) - decode form's values into a struct.
* [forms ★87 ⏳1Y](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
* [gorilla/csrf ★288](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
* [nosurf ★868](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.

## Game Development

*Awesome game development libraries.*

* [Azul3D ★368](https://github.com/azul3d/engine) - 3D game engine written in Go.
* [Ebiten ★909](https://github.com/hajimehoshi/ebiten) - dead simple 2D game library in Go.
* [engo ★798](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
* [GarageEngine ★296 ⏳4Y](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL.
* [glop ★77 ⏳2Y](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library.
* [go-astar ★257](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.
* [go-collada ★12 ⏳4Y](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format.
* [go-sdl2 ★895](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
* [go3d ★138](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.
* [gonet ★935 ⏳1Y](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
* [goworld ★672](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping
* [Leaf ★2184](https://github.com/name5566/leaf) - Lightweight game server framework.
* [nano ★603](https://github.com/lonnng/nano) - Lightweight, facility, high performance golang based game server framework
* [Oak ★488](https://github.com/oakmound/oak) - Pure Go game engine.
* [Pixel ★1434](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go.
* [raylib-go ★235](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
* [termloop ★870](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [efaceconv ★32](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations.
* [gen ★892](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality.
* [go-enum ★48](https://github.com/abice/go-enum) - Code generation for enums from code comments.
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
* [goderive ★578](https://github.com/awalterschulze/goderive) - Derives functions from input types.
* [interfaces ★138 ⏳1Y](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
* [jennifer ★724](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
* [pkgreflect ★65](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection.

## Geographic

*Geographic tools and servers*

* [geocache ★85 ⏳2Y](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications.
* [geoserver ★6](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.
* [osm ★9](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs.
* [pbf ★6](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder.
* [S2 geometry ★642](https://github.com/golang/geo) - S2 geometry library in Go.
* [Tile38 ★4726](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.

## Go Compilers

*Tools for compiling Go to other languages.*

* [c4go ★13](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code.
* [gopherjs ★6990](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.
* [llgo ★896 ⏳3Y](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go.
* [tardisgo ★365 ⏳1Y](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.

## Goroutines

*Tools for managing and working with Goroutines.*

* [cyclicbarrier ★13](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang.
* [go-floc ★140](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
* [go-flow ★77](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
* [go-trylock ★1](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang.
* [GoSlaves ★28](https://github.com/themester/GoSlaves) - Simple and Asynchronous Goroutine pool library.
* [goworker ★1982](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
* [grpool ★364](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
* [parallel-fn ★15](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel.
* [pool ★373 ⏳1Y](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
* [semaphore ★30](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
* [semaphore ★35](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
* [tunny ★805](https://github.com/Jeffail/tunny) - Goroutine pool for golang.
* [worker-pool ★11](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.
* [workerpool ★25](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app ★2239](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
* [go-astilectron ★1676](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-sciter ★1038](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
* [gotk3 ★445](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
* [gowd ★122](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.
* [qt ★4089](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
* [ui ★5501](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
* [walk ★2684](https://github.com/lxn/walk) - Windows application library kit for Go.
* [webview ★2110](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

*Interaction*

* [gosx-notifier ★432](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
* [robotgo ★2940](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
* [systray ★455](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
* [trayhost ★127](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware ★708](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [bild ★1749](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
* [bimg ★535](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
* [cameron ★5](https://github.com/sheng/cameron) - An avatar generator for Go.
* [geopattern ★953 ⏳1Y](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
* [gg ★1364](https://github.com/fogleman/gg) - 2D rendering in pure Go.
* [gift ★1071](https://github.com/disintegration/gift) - Package of image processing filters.
* [go-cairo ★72](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
* [go-gd ★43](https://github.com/bolknote/go-gd) - Go binding for GD library.
* [go-nude ★252 ⏳3Y](https://github.com/koyachi/go-nude) - Nudity detection with Go.
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.
* [go-webcolors ★24 ⏳2Y](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
* [gocv ★1084](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
* [goimagehash ★100](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package.
* [govatar ★242](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
* [imagick ★746](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
* [imaginary ★1805](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
* [imaging ★1684](https://github.com/disintegration/imaging) - Simple Go image processing package.
* [img ★120 ⏳3Y](https://github.com/hawx/img) - Selection of image manipulation tools.
* [ln ★2218](https://github.com/fogleman/ln) - 3D line art rendering in Go.
* [mpo ★4](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.
* [picfit ★854](https://github.com/thoas/picfit) - An image resizing server written in Go.
* [pt ★1568](https://github.com/fogleman/pt) - Path tracing engine written in Go.
* [resize ★1835](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.
* [rez ★151](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
* [smartcrop ★1115](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
* [svgo ★1067](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
* [tga ★17 ⏳3Y](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb ★107](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
* [devices ★204 ⏳2Y](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
* [eywa ★17 ⏳1Y](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
* [flogo ★645](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* [gatt ★670](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
* [gobot ★4389](https://github.com/hybridgroup/gobot) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
* [iot ★17](https://github.com/vaelen/iot) - IoT is a simple framework for implementing a Google IoT Core device.
* [mainflux ★45](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
* [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
* [sensorbee ★143](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.

## Logging

*Libraries for generating and working with log files.*

* [distillog ★11](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels).
* [glg ★16](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
* [glog ★1842](https://github.com/golang/glog) - Leveled execution logs for Go.
* [go-cronowriter ★11](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
* [go-log ★5](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers.
* [go-log ★16 ⏳3Y](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* [go-log ★28](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
* [go-logger ★184](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
* [gologger ★37](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
* [gomol ★12](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* [journald ★7](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging.
* [log ★551](https://github.com/apex/log) - Structured logging package for Go.
* [log ★251](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
* [log ★18](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
* [log-voyage ★80 ⏳1Y](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
* [log15 ★748](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
* [logdump ★6](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
* [logex ★33 ⏳1Y](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
* [logger ★116](https://github.com/azer/logger) - Minimalistic logging library for Go.
* [logo ★3](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
* [logrus ★7748](https://github.com/Sirupsen/logrus) - Structured logger for Go.
* [logrusly](https://github.com/sebest/logrusly) - [logrus ★7748](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
* [logutils ★218 ⏳3Y](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* [logxi ★327](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
* [lumberjack ★878](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
* [mlog ★15 ⏳2Y](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* [onelog ★261](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenario. Also, it is one of the logger with the lowest allocation.
* [ozzo-log ★89](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* [seelog ★1145](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
* [spew ★2420](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* [stdlog ★44 ⏳2Y](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* [tail ★1111](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
* [xlog ★3 ⏳1Y](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
* [xlog ★123](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
* [zap ★4087](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
* [zerolog ★1167](https://github.com/rs/zerolog) - Zero-allocation JSON logger.

## Machine Learning

*Libraries for Machine Learning.*

* [bayesian ★555](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
* [CloudForest ★594](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
* [fonet ★14](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.
* [gago ★494](https://github.com/MaxHalford/gago) - Multi-population, flexible, parallel genetic algorithm.
* [go-cluster ★10](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
* [go-deep ★171](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go.
* [go-fann ★95 ⏳3Y](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
* [go-galib ★157 ⏳2Y](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
* [go-pr ★51 ⏳5Y](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
* [gobrain ★250](https://github.com/goml/gobrain) - Neural Networks written in go.
* [godist ★18 ⏳3Y](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
* [goga ★64 ⏳1Y](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
* [GoLearn ★5696](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
* [golinear ★34 ⏳1Y](https://github.com/danieldk/golinear) - liblinear bindings for Go.
* [goml ★878 ⏳1Y](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
* [goRecommend ★115 ⏳3Y](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
* [gorgonia](https://github.com/chewxy/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
* [goscore ★15](https://github.com/asafschers/goscore) - Go Scoring API for PMML.
* [gosseract ★535](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
* [libsvm ★55 ⏳2Y](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
* [mlgo ★3 ⏳2Y](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go.
* [neat ★40](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).
* [neural-go ★57 ⏳4Y](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
* [probab ★8 ⏳2Y](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
* [regommend ★213](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
* [shield ★114 ⏳2Y](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.
* [tfgo ★872](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.
* [Varis ★10](https://github.com/Xamber/Varis) - Golang Neural Network.

## Messaging

*Libraries that implement messaging systems.*

* [Benthos ★273](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols.
* [Centrifugo ★2704](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
* [dbus ★224](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
* [drone-line ★48](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.
* [emitter ★213](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
* [event ★13](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
* [EventBus ★379](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
* [gaurun-client ★6 ⏳1Y](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
* [Glue ★283](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
* [go-notify ★34 ⏳2Y](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
* [go-nsq ★1104](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
* [go-socket.io ★2224](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
* [go-vitotrol ★7](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
* [Gollum ★605](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
* [golongpoll ★372](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
* [goose ★32 ⏳3Y](https://github.com/ian-kent/goose) - Server Sent Events in Go.
* [gopush-cluster ★1702 ⏳1Y](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm).
* [guble ★124](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
* [hub ★5](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.
* [machinery ★2258](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
* [mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability.
* [melody ★1014](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
* [messagebus ★18](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
* [nsq-event-bus ★31](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
* [oplog ★87 ⏳2Y](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
* [rabbus ★40](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues.
* [rabtap ★20](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app.
* [RapidMQ ★39](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
* [sarama ★3021](https://github.com/Shopify/sarama) - Go library for Apache Kafka.
* [Uniqush-Push ★976](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2 ★16](https://github.com/pebbe/zmq2).

## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit.*

* [alice ★17 ⏳1Y](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
* [anagent ★5](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
* [antch ★86](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework.
* [archiver ★906](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
* [autoflags ★21](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
* [avgRating ★5](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
* [banner ★166 ⏳1Y](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
* [base64Captcha ★351](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
* [battery ★91 ⏳1Y](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
* [bitio ★55](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
* [browscap_go ★26](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/).
* [captcha ★19](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
* [conv ★319 ⏳1Y](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
* [datacounter ★22](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
* [errors ★3109](https://github.com/pkg/errors) - Package that provides simple error handling primitives.
* [ghorg ★9](https://github.com/gabrie30/ghorg) - Clone all repos from a GitHub org into a single directory.
* [go-chat-bot ★330](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.
* [go-commons-pool ★503](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
* [go-multierror ★461](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency ★636](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
* [go-sarah ★95](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.
* [go-unarr ★31](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
* [go.uuid ★2128](https://github.com/satori/go.uuid) - Implementation of Universally Unique Identifier (UUID). Supported both creation and parsing of UUIDs.
* [gofakeit ★143](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
* [goid ★12 ⏳1Y](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
* [gopsutil ★2706](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* [gosh ★7](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method.
* [gosms ★1132 ⏳1Y](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
* [gountries ★166](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
* [hanu ★58 ⏳1Y](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
* [health ★292](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
* [healthcheck ★43](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
* [hostutils ★3](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
* [indigo ★37](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
* [jobs ★427](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.
* [lk ★56](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
* [margelet ★47 ⏳1Y](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
* [pdfgen ★12](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests.
* [persian ★12](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
* [sandid ★1](https://github.com/sheng/sandid) - Every grain of sand on earth has its own ID.
* [secdl](https://github.com/xor-gate/secdl) - Lighttpd ModSecDownload algorithm ported to go to secure download urls.
* [shellwords ★1](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
* [shortid ★268](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
* [slacker ★183](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.
* [stats ★100 ⏳1Y](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
* [turtle ★46](https://github.com/hackebrot/turtle) - Emojis for Go.
* [url-shortener ★3](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support.
* [uuid ★5 ⏳1Y](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and ouput handling.
* [werr ★5 ⏳2Y](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.
* [wuid ★170](https://github.com/edwingeng/wuid) - An extremely fast unique number generator, 10-135 times faster than UUID.
* [xkg ★33 ⏳3Y](https://github.com/go-xkg/xkg) - X Keyboard Grabber.
* [xstrings ★473](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.

## Natural Language Processing

*Libraries for working with human languages.*

* [getlang ★13](https://github.com/rylans/getlang) - Fast natural language detection package.
* [go-eco ★3 ⏳2Y](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.
* [go-i18n ★642](https://github.com/nicksnyder/go-i18n) - Package and an accompanying tool to work with localized text.
* [go-mystem ★15 ⏳1Y](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
* [go-nlp ★74 ⏳6Y](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
* [go-stem ★44](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
* [go-unidecode ★24 ⏳1Y](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
* [go2vec ★28 ⏳1Y](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba ★14013](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
* [golibstemmer ★14 ⏳4Y](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
* [gounidecode ★57 ⏳2Y](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
* [gse ★407](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other.
* [icu ★16 ⏳1Y](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
* [libtextcat ★9 ⏳5Y](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* [MMSEGO ★54 ⏳6Y](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
* [nlp ★339](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
* [nlp ★140](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
* [paicehusk ★22 ⏳4Y](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
* [petrovich ★11](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.
* [porter ★7 ⏳4Y](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
* [prose ★592](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more.
* [RAKE.go ★30](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* [segment ★38 ⏳1Y](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* [sentences ★234](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences.
* [shamoji ★8](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.
* [snowball ★19 ⏳1Y](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
* [stemmer ★40 ⏳1Y](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
* [textcat ★56 ⏳1Y](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.
* [whatlanggo ★283](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).
* [when ★864](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.

## Networking

*Libraries for working with various layers of the network.*

* [arp ★133](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
* [buffstreams ★197 ⏳1Y](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
* [canopus ★109](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
* [cidranger ★276](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
* [dhcp6 ★48](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
* [dns ★2893](https://github.com/miekg/dns) - Go library for working with DNS.
* [ether ★52 ⏳2Y](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
* [ethernet ★144](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
* [fasthttp ★6452](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* [fortio ★357](https://github.com/istio/fortio) - Load testing library and command line tool and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them.
* [ftp ★364](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959).
* [go-getter ★510](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
* [go-stun ★243](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
* [gobgp ★1324](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* [golibwireshark ★12](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
* [gopacket ★1989](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
* [gopcap ★313 ⏳1Y](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
* [goshark ★6](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
* [gosnmp ★319](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
* [gotcp ★332 ⏳1Y](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
* [grab ★339](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
* [graval ★19](https://github.com/koofr/graval) - Experimental FTP server framework.
* [HTTPLab ★3048](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses.
* [jazigo ★83](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
* [kcp-go ★1283](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
* [kcptun ★8258](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* [lhttp ★416](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
* [linkio ★34](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
* [llb ★6 ⏳2Y](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
* [mdns ★424](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [NFF-Go ★462](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
* [peerdiscovery ★270](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast
* [portproxy ★35 ⏳3Y](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
* [publicip ★15 ⏳1Y](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
* [quic-go ★1469](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.
* [raw ★205](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
* [sftp ★519](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
* [ssh ★767](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
* [sslb ★103](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
* [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
* [tcp_server ★191](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.
* [utp ★137](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
* [water ★435](https://github.com/songgao/water) - Simple TUN/TAP library.
* [winrm ★159](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
* [xtcp ★41](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol.

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl ★486](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* [glfw ★478](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* [goxjs/gl ★122](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* [goxjs/glfw ★52](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* [mathgl ★227](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [go-pg ★1796](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* [go-queryset ★321](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.
* [go-sqlbuilder ★52](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM.
* [go-store ★88 ⏳1Y](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
* [gomodel ★59](https://github.com/cosiner/gomodel) - Lightweight, fast, orm-like library helps interactive with database.
* [GORM ★9380](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
* [gorp ★2797](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
* [grimoire ★10](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
* [lore ★3](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
* [Marlow ★28](https://github.com/dadleyy/marlow) - Generated ORM from project structs for compile time safety assurances.
* [pop/soda ★568](https://github.com/markbates/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [QBS ★503 ⏳1Y](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM.
* [reform ★659](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
* [SQLBoiler ★1253](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
* [upper.io/db ★1254](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
* [Xorm ★3446](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go.
* [Zoom ★210](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.

## Package Management

*Libraries for package and dependency management.*

* [dep ★9486](https://github.com/golang/dep) - Go dependency tool.
* [gigo ★194 ⏳2Y](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes.
* [glide ★6807](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
* [godep ★5383](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
* [gom ★1316](https://github.com/mattn/gom) - Go Manager - bundle for go.
* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
* [gop ★41](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH
* [gopm ★1806](https://github.com/gpmgo/gopm) - Go Package Manager.
* [govendor ★3543](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
* [gpm ★1200](https://github.com/pote/gpm) - Barebones dependency manager for Go.
* [gvt ★742](https://github.com/FiloSottile/gvt) - `gvt` is a simple vendoring tool made for Go native vendoring (aka GO15VENDOREXPERIMENT), based on gb-vendor.
* [johnny-deps ★212 ⏳3Y](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
* [nut ★247 ⏳3Y](https://github.com/jingweno/nut) - Vendor Go dependencies.
* [VenGO ★109 ⏳2Y](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.

## Query Language

* [gojsonq ★174](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data.
* [graphql ★45 ⏳1Y](https://github.com/tmc/graphql) - graphql parser + utilities.
* [graphql ★34 ⏳2Y](https://github.com/sevki/graphql) - GraphQL implementation in go.
* [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
* [graphql-go ★3205](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
* [jsonql ★159](https://github.com/elgs/jsonql) - JSON query expression library in Golang.
* [rql ★48](https://github.com/a8m/rql) - Resource Query Language for REST API.

## Resource Embedding

* [esc ★315](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.
* [fileb0x ★243](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.
* [go-embed ★13 ⏳2Y](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable.
* [go-resources ★145](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.
* [go.rice ★1322](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy.
* [packr ★1018](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries.
* [statics ★47 ⏳1Y](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
* [statik ★1339](https://github.com/rakyll/statik) - Embeds static files into a Go executable.
* [templify ★12](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.
* [vfsgen ★317](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [blas ★118 ⏳4Y](https://github.com/ziutek/blas) - Implementation of BLAS (Basic Linear Algebra Subprograms).
* [chart ★488 ⏳2Y](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
* [evaler ★31](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
* [ewma ★225](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
* [geom ★35](https://github.com/skelterjohn/geom) - 2D geometry for golang.
* [go-dsp ★531](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
* [go-fn ★7 ⏳3Y](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg.
* [go-gt ★3 ⏳2Y](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
* [go.matrix ★301](https://github.com/skelterjohn/go.matrix) - linear algebra for go (has been stalled).
* [gocomplex ★3 ⏳3Y](https://github.com/varver/gocomplex) - Complex number library for the Go programming language.
* [goent ★5](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures
* [gofrac ★6 ⏳2Y](https://github.com/anschelsc/gofrac) - (goinstallable) fractions library for go with support for basic arithmetic.
* [gohistogram ★106](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.
* [gonum/mat64 ★461](https://github.com/gonum/matrix) - The general purpose package for matrix computation. Package mat64 provides basic linear algebra operations for float64 matrices.
* [gonum/plot ★876](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
* [goraph ★503](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization).
* [gosl ★1089](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* [gostat ★24](https://github.com/ematvey/gostat) - Statistics library for the go language.
* [graph ★141](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
* [ode ★5 ⏳1Y](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
* [orb ★23](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
* [pagerank ★38 ⏳2Y](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
* [PiHex ★3](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
* [sparse ★32](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
* [stats ★895](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
* [streamtools ★1307 ⏳3Y](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
* [TextRank ★11](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
* [vectormath ★59 ⏳5Y](https://github.com/spate/vectormath) - Vectormath for Go, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code (currently inactive).

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool ★1540](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
* [argon2pw ★60](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison.
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
* [BadActor ★222 ⏳1Y](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
* [Cameradar ★1330](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras.
* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA ★69 ⏳1Y](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
* [goArgonPass ★1](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.
* [goSecretBoxPassword ★17](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.
* [lego ★2648](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
* [memguard ★784](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
* [nacl ★360](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's.
* [passlib ★190](https://github.com/hlandau/passlib) - Futureproof password hashing library.
* [secure ★968](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
* [simple-scrypt ★135](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
* [ssh-vault ★151](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.

## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
* [bambam ★58 ⏳1Y](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
* [colfer ★374](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
* [csvutil ★217](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
* [fwencoder ★3](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go.
* [go-capnproto ★262 ⏳1Y](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
* [go-codec ★961](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
* [gogoprotobuf ★1756](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* [goprotobuf ★3081](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* [jsoniter ★3047](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
* [mapstructure ★1496](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
* [php_session_decoder ★87 ⏳1Y](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
* [structomap ★73 ⏳3Y](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.
* [structs ★2238](https://github.com/fatih/structs) - Library with support for converting structs to maps, struct keys/values to slices, and more.

## Server Applications

* [algernon ★450](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
* [Caddy ★17591](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd ★2553](https://github.com/cortesi/devd) - Local webserver for developers.
* [etcd ★18952](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.
* [Fider ★322](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.
* [Flagr ★378](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service.
* [jackal ★438](https://github.com/ortuman/jackal) - An XMPP server written in Go.
* [minio ★11833](https://github.com/minio/minio) - Minio is a distributed object storage server.
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [yakvs](https://github.com/sci4me/yakvs) - Small, networked, in-memory key-value store.

## Template Engines

*Libraries and tools for templating and lexing.*

* [ace ★718](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.
* [amber ★787](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
* [damsel ★19 ⏳2Y](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.
* [ego ★369](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
* [fasttemplate ★195 ⏳1Y](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/).
* [gofpdf ★2405](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images.
* [grender ★75](https://github.com/dannyvankooten/grender) - small wrapper around html/template for file-based templates that support extending other template files.
* [hero ★984](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.
* [jet ★469](https://github.com/CloudyKit/jet) - Jet template engine.
* [kasia.go ★69 ⏳2Y](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation.
* [liquid ★60](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
* [mustache ★929](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language.
* [pongo2 ★1235](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
* [quicktemplate ★1021](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
* [raymond ★267](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
* [Razor ★630](https://github.com/sipin/gorazor) - Razor view engine for Golang.
* [Soy ★125](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
* [velvet ★58 ⏳1Y](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [assert ★9 ⏳2Y](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
    * [badio ★6 ⏳2Y](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.
    * [baloo ★501](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
    * [biff ★2](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible.
    * [bro ★20 ⏳1Y](https://github.com/marioidival/bro) - Watch files in directory and run tests for them.
    * [cupaloy ★49](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
    * [dbcleaner ★37](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
    * [dsunit ★17](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
    * [endly ★35](https://github.com/viant/endly) - Declarative end to end functional testing.
    * [frisby ★227](https://github.com/verdverm/frisby) - REST API testing framework.
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [go-carpet ★179](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
    * [go-mutesting ★146](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
    * [go-vcr ★206](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
    * [goblin ★507](https://github.com/franela/goblin) - Mocha like testing framework fo Go.
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey ★3670](https://github.com/smartystreets/goconvey) - BDD-style framework with web UI and live reload.
    * [gocrest ★6](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions.
    * [godog ★402](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go.
    * [gofight ★168](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
    * [gogiven ★6](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go.
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [GoSpec ★109 ⏳3Y](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
    * [gospecify ★49 ⏳6Y](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
    * [gosuite ★5 ⏳1Y](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
    * [Hamcrest ★24 ⏳7Y](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
    * [httpexpect ★883](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
    * [testfixtures ★179](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
    * [Testify ★5221](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
    * [Tt ★1](https://github.com/vcaesar/tt) - Simple and colorful test tools.
    * [wstest ★37](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.

* Mock
    * [counterfeiter ★241](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
    * [go-sqlmock ★891](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
    * [go-txdb ★62](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
    * [gock ★495](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
    * [gomock ★1440](https://github.com/golang/mock) - Mocking framework for the Go programming language.
    * [govcr ★32](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
    * [minimock ★128](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
    * [mockhttp ★20 ⏳3Y](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz ★2257](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
    * [gofuzz ★430](https://github.com/google/gofuzz) - Library for populating go objects with random values.
    * [Tavor ★186](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

* Selenium and browser control tools.
    * [cdp ★133](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
    * [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
    * [ggr ★143](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium Wedriver requests to multiple Selenium hubs.
    * [selenoid ★5](https://github.com/aandryashin/selenoid) - alternative Selenium hub server that launches browsers within containers.

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align ★38](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
    * [allot ★29 ⏳1Y](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
    * [bbConvert ★3 ⏳1Y](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
    * [blackfriday ★3069](https://github.com/russross/blackfriday) - Markdown processor in Go.
    * [bluemonday ★929](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
    * [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers
    * [commonregex ★491](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go
    * [doi ★0](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
    * [editorconfig-core-go ★20](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
    * [enca ★4 ⏳2Y](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/).
    * [encdec ★2](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decodersa.
    * [genex ★45 ⏳2Y](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-fixedwidth ★11](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
    * [go-humanize ★1499](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
    * [go-nmea ★54](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
    * [go-runewidth ★132](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
    * [go-slugify ★16 ⏳1Y](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
    * [go-vcard ★7](https://github.com/emersion/go-vcard) - Parse and format vCard.
    * [gofeed ★857](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
    * [gographviz ★191](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
    * [gonameparts ★25 ⏳1Y](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
    * [goq ★91](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
    * [GoQuery ★5862](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
    * [goregen ★29 ⏳2Y](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
    * [gotext ★165](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
    * [guesslanguage ★38](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
    * [inject ★927](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.
    * [mxj ★263](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
    * [sh ★1210](https://github.com/mvdan/sh) - Shell parser and formatter.
    * [slug ★203](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
    * [Slugify ★22](https://github.com/avelino/slugify) - Go slugify application that handles string.
    * [syndfeed ★2](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0.
    * [toml ★2080](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
* Utility
    * [gotabulate ★173 ⏳1Y](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
    * [kace ★6](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
    * [parth ★18](https://github.com/codemodus/parth) - URL path segmentation parsing.
    * [radix ★52](https://github.com/yourbasic/radix) - fast string sorting algorithm.
    * [xj2go ★9](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.
    * [xurls ★347](https://github.com/mvdan/xurls) - Extract urls from text.

## Third-party APIs

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api ★30](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [anaconda ★896](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
* [aws-sdk-go ★4025](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
* [brewerydb ★13 ⏳3Y](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
* [cachet ★50](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* [circleci ★26](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* [codeship-go ★13](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2.
* [discordgo ★605](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
* [ethrpc ★93](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
* [facebook ★641](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
* [fcm ★25](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
* [gads ★33 ⏳1Y](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
* [gami ★22](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
* [gcm ★29 ⏳2Y](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
* [geo-golang ★235](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* [github ★3667](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
* [go-chronos ★1](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
* [go-hacknews ★5](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
* [go-imgur ★6 ⏳2Y](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* [go-jira ★281](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-marathon ★177](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
* [go-myanimelist ★13 ⏳1Y](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [go-sptrans ★4](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
* [go-telegraph](https://github.com/toby3d/go-telegraph) - Telegraph publishing platform API client.
* [go-tgbot ★71](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
* [go-twitch ★12](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
* [go-twitter ★473](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* [go-unsplash ★9](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* [go-xkcd ★32 ⏳2Y](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
* [goamz ★677 ⏳1Y](https://github.com/mitchellh/goamz) - Popular fork of [goamz](https://launchpad.net/goamz) which adds some missing API calls to certain packages.
* [golyrics ★21](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* [GoMusicBrainz ★25](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
* [google ★1444](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* [google-analytics ★8 ⏳3Y](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
* [google-email-audit-api ★4 ⏳1Y](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [gostorm ★107](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* [govkbot ★16](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
* [hipchat ★106 ⏳2Y](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
* [hipchat (xmpp) ★111 ⏳1Y](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
* [igdb ★15](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/).
* [Medium ★99](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
* [megos ★50](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.
* [micha ★6](https://github.com/onrik/micha) - Go Library for Telegram bot api.
* [minio-go ★490](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
* [mixpanel ★24](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* [patreon-go ★11](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
* [paypal](https://github.com/logpacker/paypalsdk) - Wrapper for PayPal payment API.
* [playlyfe ★0 ⏳2Y](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
* [pushover ★39](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
* [rrdaclient ★6 ⏳3Y](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
* [shopify ★18](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* [slack ★1666](https://github.com/nlopes/slack) - Slack API in Go.
* [smite ★8 ⏳4Y](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
* [spotify ★13](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* [steam ★8](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
* [stripe ★721](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
* [tbot ★154](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
* [telebot ★652](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
* [TheMovieDb ★10 ⏳2Y](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org).
* [translate](https://github.com/poorny/translate) - Go online translation package.
* [Trello ★51](https://github.com/adlio/trello) - Go wrapper for the Trello API.
* [tumblr ★5 ⏳1Y](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
* [webhooks ★188](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
* [zooz ★2](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

## Utilities

*General utilities and tools to make your life easier.*

* [abutil ★46 ⏳2Y](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers.
* [apm ★111 ⏳1Y](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
* [backscanner ★5](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
* [boilr ★727](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* [chyle ★88](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
* [circuit ★35](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
* [circuitbreaker ★637](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* [clockwork ★20](https://github.com/whiteShtef/clockwork) - Simple and intuitive job scheduling library in Go.
* [command ★8 ⏳2Y](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
* [coop ★1202 ⏳2Y](https://github.com/rakyll/coop) - Cheat sheet for some of the common concurrent flows in Go.
* [copy-pasta ★26](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* [ctop ★7091](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* [Death ★96](https://github.com/vrecan/death) - Managing go application shutdown with signals.
* [Deepcopier ★157](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
* [delve ★8548](https://github.com/derekparker/delve) - Go debugger.
* [dlog ★14](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
* [ergo ★196](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
* [evaluator ★9](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.
* [excelize ★2170](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
* [fastlz ★9 ⏳3Y](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang.
* [filetype ★309](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* [filler ★11 ⏳1Y](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
* [fzf ★15041](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* [generate ★10 ⏳1Y](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
* [gentleman ★534](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
* [git-time-metric ★575](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
* [GJSON ★3049](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* [go-astitodo ★35](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
* [go-bind-plugin ★157](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* [go-cron ★160 ⏳3Y](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* [go-dry ★405](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
* [go-excel ★24](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table.
* [go-funk ★425](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* [go-health ★53](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services.
* [go-httpheader ★14 ⏳1Y](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
* [go-rate ★262](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
* [go-respond ★10](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
* [go-sitemap-generator ★78](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* [go-torch ★3007](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs.
* [go-trigger ★138 ⏳1Y](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* [go-underscore ★960 ⏳3Y](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
* [goback ★38](https://github.com/carlescere/goback) - Go simple exponential backoff package.
* [godaemon ★363 ⏳2Y](https://github.com/VividCortex/godaemon) - Utility to write daemons.
* [godropbox ★3562](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* [gohper ★241](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* [gojq ★117](https://github.com/elgs/gojq) - JSON query in Golang.
* [gojson ★1708](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
* [golarm ★31 ⏳2Y](https://github.com/msempere/golarm) - Fire alarms with system events.
* [golog ★39 ⏳1Y](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
* [gopencils ★410](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
* [goplaceholder ★19 ⏳2Y](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
* [goreleaser ★2958](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [goreq ★681](https://github.com/franela/goreq) - Minimal and simple request library for Go language.
* [goreq ★72](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest.
* [gorequest ★1752](https://github.com/parnurzeal/gorequest) - Simplified HTTP client with rich features for Go.
* [goseaweedfs ★12](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
* [gotenv ★95](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
* [goxlsxwriter ★10](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
* [gpath ★22 ⏳1Y](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
* [grequests ★1092](https://github.com/levigross/grequests) - Elegant and simple `net/http` wrapper that follows Python's requests library.
* [gron ★514 ⏳1Y](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* [gubrak](https://gubrak.github.io/) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
* [htcat ★451 ⏳3Y](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
* [httpcontrol](https://github.com/facebookgo/httpcontrol) - Package httpcontrol allows for HTTP transport level control around timeouts and retries.
* [hub ★13109](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* [hystrix-go ★1144](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* [immortal ★499](https://github.com/immortal/immortal) - *nix cross-platform (OS agnostic) supervisor.
* [intrinsic ★26 ⏳1Y](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* [JobRunner ★456 ⏳1Y](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* [jsonapi-errors ★3 ⏳1Y](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
* [jsonf ★49 ⏳2Y](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
* [jsongo ★78 ⏳1Y](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
* [jsonhal ★7](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* [kazaam ★84](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* [lrserver ★94](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
* [mc ★760](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* [mergo ★506](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* [minify ★1465](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* [minquery ★37](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
* [mmake ★1396](https://github.com/tj/mmake) - Modern Make.
* [moldova ★145](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
* [mp ★26 ⏳2Y](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
* [mssqlx ★44](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
* [multitick ★56 ⏳1Y](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
* [myhttp ★27](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.
* [netbug ★62 ⏳2Y](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* [okrun ★12 ⏳3Y](https://github.com/xta/okrun) - go run error steamroller.
* [onecache ★76](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* [panicparse ★1737](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* [peco ★4643](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* [pester ★260](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
* [pm ★59](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
* [profile ★756 ⏳1Y](https://github.com/pkg/profile) - Simple profiling support package for Go.
* [rclient ★20 ⏳1Y](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* [repeat ★46](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
* [request ★302](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
* [rerate ★11 ⏳1Y](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.
* [rerun ★146](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
* [resty ★921](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [retry ★48](https://github.com/kamilsk/retry) - Functional mechanism based on context to perform actions repetitively until successful.
* [retry ★17](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go.
* [retry-go ★22](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang.
* [robustly ★129](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
* [rq ★20](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client.
* [scheduler ★219](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
* [sling ★707](https://github.com/dghubble/sling) - Go HTTP requests builder for API clients.
* [spinner ★527](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* [sqlx ★4526](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* [Storm ★1011](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* [structs ★6](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
* [Task ★915](https://github.com/go-task/task) - simple "Make" alternative.
* [toolbox ★25](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* [ugo ★18 ⏳2Y](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
* [UNIS ★66 ⏳1Y](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* [util ★70](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* [wuzz ★7434](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
* [xferspdy ★56 ⏳1Y](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.
* [xlsx ★2474](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.

## Validation

*Libraries for validation.*

* [govalidator ★2679](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
* [govalidator ★420](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
* [ozzo-validation ★689](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* [validate ★37](https://github.com/markbates/validate) - This package provides a framework for writing validations for Go applications.
* [validator ★1891](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.

## Version Control

*Libraries for version control.*

* [gh ★57](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.
* [git2go ★1165](https://github.com/libgit2/git2go) - Go bindings for libgit2.
* [go-vcs ★63](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
* [hgo ★11 ⏳2Y](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

## Video

*Libraries for manipulating video.*

* [gmf ★371](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
* [go-astisub ★106](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* [go-astits ★206](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.
* [goav ★477](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg.
* [gst ★143](https://github.com/ziutek/gst) - Go bindings for GStreamer.
* [libgosubs ★6](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
* [v4l ★12](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Aero ★39](https://github.com/aerogo/aero) - High-performance web framework for Go, reaches top scores in Lighthouse.
* [Air ★74](https://github.com/sheng/air) - Ideal RESTful web framework for Go.
* [Banjo ★2](https://github.com/nsheremet/banjo) - Very simple and fast web framework for Go.
* [Beego ★15853](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo ★10805](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
* [Fireball ★35](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.
* [Florest ★42 ⏳1Y](https://github.com/jabong/florest-core) - High-performance workflow based REST API framework.
* [Gem ★154 ⏳1Y](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API.
* [Gin ★18312](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* [Gizmo ★2254](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
* [go-json-rest ★3123](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* [go-relax ★146](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's.
* [go-rest ★107 ⏳1Y](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
* [goa](https://github.com/raphael/goa) - Framework for developing microservices based on the design of Ruby's Praxis.
* [Golax ★60](https://github.com/fulldump/golax) - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more.
* [Golf ★219 ⏳1Y](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
* [Gondola ★312 ⏳1Y](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.
* [gongular ★391](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
* [Macaron ★2421](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
* [mango ★326](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
* [Microservice ★41](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
* [neo ★365](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.
* [Resoursea ★29 ⏳3Y](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel ★9966](https://github.com/revel/revel) - High-productivity web framework for the Go language.
* [rex ★20](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
* [sawsij ★1 ⏳2Y](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications.
* [tango ★728](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.
* [tigertonic ★981 ⏳1Y](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.
* [traffic ★515 ⏳2Y](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go.
* [utron ★2044](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).
* [violetear ★85](https://github.com/nbari/violetear) - Go HTTP router.
* [WebGo ★40](https://github.com/bnkamalesh/webgo) - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc).
* [YARF ★43](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.
* [Zerver ★141 ⏳2Y](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework.

### Middlewares

#### Actual middlewares

* [client-timing ★9](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header.
* [CORS ★815](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
* [formjson ★28 ⏳2Y](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
* [go-server-timing ★692](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header.
* [Limiter ★340](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* [Tollbooth ★899](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
* [XFF ★66 ⏳1Y](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

* [alice ★1584](https://github.com/justinas/alice) - Painless middleware chaining for Go.
* [catena ★6 ⏳1Y](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").
* [chain ★63 ⏳1Y](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* [go-wrap ★52 ⏳3Y](https://github.com/go-on/wrap) - Small middlewares package for net/http.
* [gores ★69 ⏳1Y](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
* [interpose ★283 ⏳1Y](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
* [muxchain ★204 ⏳3Y](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
* [negroni ★5611](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
* [render ★1105](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
* [renderer ★91](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
* [rye ★77](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
* [stats ★478](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.
* [Volatile ★81 ⏳2Y](https://github.com/volatile/core) - Minimalist middleware stack promoting flexibility, good practices and clean code.

### Routers

* [alien ★91](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
* [Bone ★1134](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
* [Bxog ★86](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
* [chi ★3660](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
* [fasthttprouter ★508](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* [FastRouter ★15](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
* [gocraft/web ★1321](https://github.com/gocraft/web) - Mux and middleware package in Go.
* [Goji ★649 ⏳1Y](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
* [GoRouter ★33](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
* [gowww/router ★147](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
* [httprouter ★7224](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* [httptreemux ★334](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
* [lars ★358](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
* [medeina ★17 ⏳3Y](https://github.com/imdario/medeina) - Medeina is a HTTP routing tree based on HttpRouter, inspired by Roda and Cuba.
* [mux ★6442](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
* [ozzo-routing ★286](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* [pat ★1128](https://github.com/bmizerany/pat) - Sinatra style pattern muxer for Go’s net/http library, by the author of Sinatra.
* [pure ★58](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
* [Siesta ★347](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
* [vestigo ★223](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
* [xmux ★79 ⏳1Y](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
* [xujiajun/gorouter ★86](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go.
* [zeus ★110 ⏳1Y](https://github.com/daryl/zeus) - Very simple and fast HTTP router for Go.

## Windows

* [d3d9 ★68](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
* [go-ole ★404](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.

## XML

*Libraries and tools for manipulating XML.*

* [XML-Comp ★13](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
* [xmlwriter ★3 ⏳1Y](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
* [xpath ★66](https://github.com/antchfx/xpath) - XPath package for Go.
* [xquery ★122](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.

# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat ★144 ⏳1Y](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
* [dupl ★108](https://github.com/mibk/dupl) - Tool for code clone detection.
* [errcheck ★1057](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* [gcvis ★822](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* [Go Metalinter ★2762](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form.
* [go-checkstyle ★79](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments.
* [go-cleanarch ★213](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
* [go-outdated ★38 ⏳2Y](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.
* [goast-viewer ★272](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GolangCI](https://golangci.com/) - GolangCI is an automated Golang code review service for GitHub pull requests. Service is open source and it's free for open source projects.
* [GoLint ★2561](https://github.com/golang/lint) - Golint is a linter for Go source code.
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* [gostatus ★222](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
* [interfacer ★707](https://github.com/mvdan/interfacer) - Linter that suggests interface types.
* [lint ★59](https://github.com/surullabs/lint) - Run linters as part of go test.
* [php-parser ★457](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go.
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code.
* [unconvert ★214](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* [validate ★62 ⏳2Y](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-language-server ★10](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
* [go-mode ★779](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* [go-plus ★1394](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* [Goclipse ★762](https://github.com/GoClipse/goclipse) - Eclipse plugin for Go.
* [gocode ★4328](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
* [GoSublime ★2931](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
* [theia-go-extension ★5](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE.
* [velour ★14 ⏳1Y](https://github.com/velour/velour) - IRC client for the acme editor.
* [vim-compiler-go ★75 ⏳2Y](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* [vim-go ★8674](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* [vscode-go ★3638](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* [Watch ★145](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

## Go Generate Tools

* [generic ★15](https://github.com/usk81/generic) - flexible data type for Go.
* [genny ★651](https://github.com/cheekybits/genny) - Elegant generics for Go.
* [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go.
* [gotests ★1222](https://github.com/cweill/gotests) - Generate Go tests from your source code.
* [re2dfa ★146](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.

## Go Tools

* [colorgo ★91 ⏳1Y](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
* [depth ★232](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [generator-go-lang ★4](https://github.com/axelspringer/generator-go-lang) - A [Yeoman](http://yeoman.io) generator to get new Go projects started.
* [go-callvis ★1145](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
* [go-pkg-complete ★36](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
* [go-swagger ★2398](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* [richgo ★274](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
* [rts ★173 ⏳1Y](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.

## Software Packages

*Software written in Go.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
* [aurora ★291](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
* [awsenv ★14 ⏳1Y](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
* [Banshee ★923](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics.
* [Blast ★133](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs.
* [bombardier ★1026](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
* [bosun ★2558](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* [dogo ★180 ⏳1Y](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
* [drone-jenkins ★14](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
* [drone-scp ★32](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
* [Dropship ★40 ⏳2Y](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
* [easyssh-proxy ★47](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* [fac ★1428](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts
* [Gitea ★8785](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
* [Go Metrics ★1958](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics.
* [go-selfupdate ★589 ⏳1Y](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
* [gobrew ★174 ⏳1Y](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* [godbg ★217 ⏳2Y](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative ★293 ⏳1Y](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
* [gox ★2736](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
* [goxc ★1514](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* [grapes ★105](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
* [GVM ★3617](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* [Hey ★3471](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
* [kala ★1220](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
* [kcli ★21](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages.
* [kubernetes ★38089](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* [lstags ★177](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries.
* [lwc ★4](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command.
* [manssh ★175](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.
* [Moby ★49330](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* [Mora ★247 ⏳1Y](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
* [ostent ★155](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [Pewpew ★156](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
* [Rodent ★32 ⏳1Y](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* [s3gof3r ★929](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* [Scaleway-cli ★436](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
* [sg ★3 ⏳1Y](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the reponse code and data between each call for specific server stress based on its previous response.
* [skm ★407](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
* [StatusOK ★935](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* [traefik ★16029](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
* [Vegeta ★8162](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [webhook ★2981](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli ★38](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.

### Other Software
* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
* [boxed ★67 ⏳2Y](https://github.com/tejo/boxed) - Dropbox based blog engine.
* [Cherry ★161 ⏳1Y](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
* [Circuit ★1652 ⏳1Y](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [Comcast ★5545](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* [confd ★5153](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* [DDNS ★46](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize ★446](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
* [fleet ★2416](https://github.com/coreos/fleet) - Distributed init System.
* [Go Package Store ★852](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
* [gocc ★179](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
* [GoDNS ★226](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.
* [GoDocTooltip ★11 ⏳2Y](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at funciton list.
* [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ide ★177](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
* [ipe ★225](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
* [JayDiff ★12](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps ★578](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE ★4524](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [mockingjay ★356 ⏳1Y](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
* [myLG ★2038](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* [naclpipe ★11](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
* [nes ★3605](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
* [orange-cat](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go.
* [Orbit ★102](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
* [peg ★495](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
* [Pipe ★1028](https://github.com/b3log/pipe) - A small and beautiful blogging platform.
* [Postman ★716 ⏳1Y](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email.
* [restic ★4622](https://github.com/restic/restic) - De-duplicating backup program.
* [rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM.
* [Seaweed File System ★5483](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* [shell2http ★233](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
* [snap ★1738](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
* [Snitch ★14](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
* [Stack Up ★1744](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [Tenyks ★164 ⏳1Y](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.
* [term-quiz ★11](https://github.com/crazcalm/term-quiz) - Quizzes for your terminal.
* [toto ★21 ⏳1Y](https://github.com/blogcin/ToTo) - Simple proxy server written in Go language, can be used together with browser.
* [toxiproxy ★2826](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow ★399](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* [websysd](https://github.com/ian-kent/websysd) - Web based process manager (like Marathon or Upstart).
* [wellington ★273](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench ★88 ⏳3Y](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* [go-benchmark-app ★15 ⏳1Y](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* [go-benchmarks ★98 ⏳2Y](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* [go-http-routing-benchmark ★1094](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
* [go-type-assertion-benchmark ★5](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go.
* [go-web-framework-benchmark ★738](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
* [go_serialization_benchmarks ★659](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
* [golang-micro-benchmarks ★15 ⏳2Y](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others.
* [golang-sql-benchmark ★44](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* [gospeed ★82 ⏳2Y](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* [kvbench ★13 ⏳4Y](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
* [skynet ★854](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* [speedtest-resize ★137 ⏳1Y](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA
* [dotGo](http://www.dotgo.eu) - Paris, France
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan
* [GoLab](http://golab.io/) - Florence, Italy
* [GolangUK](http://golanguk.com/) - London, UK
* [GopherChina](http://gopherchina.org) - Shanghai, China
* [GopherCon](http://www.gophercon.com/) - Denver, USA
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR
* [GopherCon Europe](https://gophercon.is/) - Reykjavik, Iceland
* [GopherCon India](https://www.gophercon.in/) - Pune, India
* [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore
* [GothamGo](http://gothamgo.com/) - New York City, USA

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details
* [Go Bootcamp](http://golangbootcamp.com)
* [GoBooks ★5031](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [Web Application with Go the Anti-Textbook ★2023](https://github.com/thewhitetulip/web-dev-golang-anti-textbook)

## Gophers

* [Go-gopher-Vector ★20](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg]
* [gopher-logos ★34](https://github.com/GolangUA/gopher-logos) - adorable gopher logos
* [gopher-stickers ★370 ⏳1Y](https://github.com/tenntenn/gopher-stickers)
* [gopher-vector ★301 ⏳1Y](https://github.com/golang-samples/gopher-vector)
* [gophericons ★542](https://github.com/shalakhin/gophericons)
* [gopherize.me ★204](https://github.com/matryer/gopherize.me) - Gopherize yourself
* [gophers ★1282](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara
* [gophers ★1093](https://github.com/egonelbre/gophers) - Free gophers
* [gophers ★44 ⏳1Y](https://github.com/rogeralsing/gophers) - random gopher graphics
* [gophers ★17](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern

## Meetups

* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Syney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job ★11963](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
* [awesome-awesomeness ★21639](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [gocryforhelp ★27](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics ★132 ⏳2Y](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by  Francesc Campoy [@francesc](https://twitter.com/francesc).
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.

### Tutorials

* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang ★23589](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Games With Go](http://gameswithgo.org/) - A video series teaching programming and game development.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet ★3167](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Learn Go with TDD ★1973](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.
* [Working with Go ★983](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.
* [Your basic Go](http://yourbasic.org/golang) - Huge collection of tutorials and how to's
---
<p align="center">
	This list is a copy of <a href="https://github.com/avelino/awesome-go">avelino/awesome-go</a> with ranks
</p>
