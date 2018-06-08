---
layout: default
title: Awesome Rank for JStumpp/awesome-android
---

<p align="center">
	This list is a copy of <a href="https://github.com/JStumpp/awesome-android">JStumpp/awesome-android</a> with ranks
</p>
---
# Awesome Android
[<img src="https://raw.githubusercontent.com/jstumpp/awesome-android/master/awesome-android.png"> ★5489](https://github.com/jstumpp/awesome-android)

<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img alt="awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" /></a>
  <a href="https://travis-ci.org/JStumpp/awesome-android"><img alt="Build Status" src="https://api.travis-ci.org/JStumpp/awesome-android.svg?branch=master" /></a>
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" />
</p>

# About
A curated list of awesome Android [libraries](#libraries) and [resources](#resources). For general Java libraries have a look at [awesome-java ★16771](https://github.com/akullpp/awesome-java).

# Supported with ❤️ by [Instabug](https://goo.gl/ykpN6D)
[![android](https://user-images.githubusercontent.com/9888943/35685005-23aa115a-0771-11e8-9ca7-82f41daeeafd.gif)](https://goo.gl/9UVi6P)
> Instabug SDK allows Android developers to receive detailed bug reports from users and testers directly from inside the app. It attaches screenshots, screen recordings, network requests, and reproduce steps with each bug report. This  minimizes debugging time and helps developers in tracing weird bugs. [Learn more.](https://goo.gl/wGJngN)🚀
 [![](https://instabug-ga.appspot.com/UA-41982088-6/github/awesomeandroid?pixel)](https://instabug.com)

# How to Use
Awesome-Android is an amazing list for people who need a certain feature on their app, so the best ways to use are:
 - Simply press command + F to search for a keyword
 - Go through our Content Menu

# Content
- [Emulators](#emulators)
- [Libraries](#libraries)
    - [Charts](#charts)
    - [Cloud Services](#cloud-services)
    - [Dependency Injection](#dependency-injection)
    - [Android Services](#android-services)
    - [Game Development](#game-development)
	- [Security](#security)
    - [GUI](#gui)
        - [ActionBar](#actionbar)
        - [Navigation](#navigation)
        - [Animations](#animations)
        - [Images](#images)
        - [Inputs](#inputs)
        - [Loading images](#loading-images)
        - [Video](#video)
        - [Camera](#camera)
        - [Field Validation](#field-validation)
    - [JSON](#json)
    - [Crash monitoring](#crash-monitoring)
    - [Networking](#networking)
    - [Logger](#logger)
    - [Notifications](#notifications)
    - [Database](#database)
        - [ORM](#orm)
    - [REST](#rest)
    - [Testing](#testing)
    - [Tracking](#tracking)
    - [Maps](#maps)
    - [Utility](#utility)
    - [Debugging tools](#debugging-tools)
    - [Wireless](#wireless)
    - [Chat and Messaging](#chat--messaging)
    - [Custom Dialog](#custom-dialog)
    - [Version Checking](#version-checking)
    - [Date & Time](#date--time)
    - [Runtime Permissions](#runtime-permissions)
    - [Other](#other)
- [Resources](#resources)
    - [More lists of libraries](#more-lists-of-libraries)
- [Development Alternatives](#development-alternatives)
    - [C#](#c)
    - [HTML, CSS and Javascript](#html-css-and-javascript)
    - [Lua](#lua)
    - [Scala](#scala)
    - [Groovy](#groovy)
    - [Kotlin](#kotlin)
- [Performance](#performance)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Emulators
- [AMIDuOS](https://www.amiduos.com)
- [AndY](https://andyroid.net)
- [ARChon](https://archon-runtime.github.io)
- [BlueStacks](https://www.bluestacks.com)
- [Genymotion](https://www.genymotion.com)
- [nox](https://www.bignox.com)
- [Xamarin](https://www.xamarin.com)
- [Remix OS Player](http://www.jide.com/remixos-player)

## Libraries

### Charts

- [AChartEngine ★561](https://github.com/ddanny/achartengine) - Charting Engine.
- [EazeGraph ★1355 ⏳1Y](https://github.com/blackfizz/EazeGraph) - Chart and graph library.
- [WilliamChart ★3828](https://github.com/diogobernardino/WilliamChart) - Chart library with good motion capabilities.
- [HelloCharts ★5816](https://github.com/lecho/hellocharts-android) - Chart and graph library with support for scaling, scrolling and animations.
- [MPAndroidChart ★22362](https://github.com/PhilJay/MPAndroidChart) - An Android chart and graph library supporting scaling and dragging by gesture.
- [ArcChartView ★67](https://github.com/imaNNeoFighT/ArcChartView) - Draw Creative Statistic Arc Charts.

### Cloud Services

- [CloudRail](https://cloudrail.com) - Unified API Library for: Cloud Storage, Social Profiles, Payment, Email, SMS & POIs.

### Data binding

- [Anvil ★1235](https://github.com/zserge/anvil) - A small library to create reactive UI components, inspired by React. Provides data binding and event listener binding, fits well for MVVM.
- [Data Binding Library](https://developer.android.com/topic/libraries/data-binding/) - Official Android Data Binding Library to write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

### Dependency Injection

- [Dagger 2 ★10724](https://github.com/google/dagger) - A fast dependency injector for Android and Java.
- [Butter Knife](http://jakewharton.github.io/butterknife/) - View "injection" library for Android.
- [ActivityStarter ★298](https://github.com/MarcinMoskala/ActivityStarter) - Android Library that provide simpler way to start the Activities with multiple arguments.
- [AndroidAnnotations ★10286](https://github.com/androidannotations/androidannotations) - Java annotations with dependency injection at compile time.
- [Toothpick ★709](https://github.com/stephanenicolas/toothpick) - A scope tree based Dependency Injection (DI) library for Java.

### Android Services
- [Remoter ★15](https://github.com/josesamuel/remoter) - An alternative to Android AIDL for Android Remote IPC services using plain java interfaces.
- [Service Connector ★3](https://github.com/josesamuel/serviceconnector) - Bind Android services and callbacks to fields and methods.

### Game Development

- [Libgdx](https://libgdx.badlogicgames.com/) - Cross-platform game engine and SDK. [Open Source ★13891](https://github.com/libGDX/libGDX)
- [Vuforia](https://www.vuforia.com/) - Augmented Reality library.
- [Unity](https://unity3d.com/unity/features/multiplatform) - Cross-platform game creation system.
- [Rajawali ★1716](https://github.com/Rajawali/Rajawali) - Android OpenGL ES 2.0/3.0 Engine
- [Cocos2d-x](http://www.cocos2d-x.org) - Cross-platform 2d game framework.
- [JustWeEngine ★711](https://github.com/lfkdsk/JustWeEngine) - An easy open source Android Native Game FrameWork.

### Security

- [libsignal-protocol-java ★721](https://github.com/signalapp/libsignal-protocol-java) - A ratcheting forward secrecy protocol that works in synchronous and asynchronous messaging environments.

### GUI

- [Pull to refresh](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout) - A swipe refresh layout is available in the v4 support library.
- [Cardslib ★4770](https://github.com/gabrielemariotti/cardslib) - Android Library to build a UI Card.
- [AndroidStaggeredGrid ★4675](https://github.com/etsy/AndroidStaggeredGrid) - Grid view which supports multiple columns with rows of varying sizes.
- [Flow ★2645](https://github.com/square/flow) - Library that helps with describing an app as a collection of moderately independent screens.
- [SortableTableView ★892](https://github.com/ISchwarz23/SortableTableView) - An Android library containing a simple TableView and an advanced SortableTableView providing a lot of customisation possibilities to fit all needs.
- [MaterialProgressBar ★1572](https://github.com/DreaminginCodeZH/MaterialProgressBar) - Material design ProgressBar with consistent appearance.
- [AndroidFillableLoaders ★1752](https://github.com/JorgeCastilloPrz/AndroidFillableLoaders) - Fillable progress view working with SVG paths. Nice option too for creating interesting app logos.
- [NexusDialog ★174](https://github.com/dkharrat/NexusDialog) - Allows you to easily and quickly create forms in Android with little code.
- [Snap RecyclerView Utils ★76 ⏳1Y](https://github.com/prashantsolanki3/Snap-RecyclerView-Utils) - Populate Single or multiple Layout RecyclerView without creating an Adapter.
- [MultiSnapRecyclerView ★1507](https://github.com/TakuSemba/MultiSnapRecyclerView) - Android library for multiple snapping of RecyclerView
- [SwipeableCard ★713 ⏳1Y](https://github.com/michelelacorte/SwipeableCard) - Implementation of swipe card like StreetView!!
- [ElasticProgressBar ★290 ⏳1Y](https://github.com/michelelacorte/ElasticProgressBar) - Beautiful loading bar.
- [EntryScreenManager ★33 ⏳2Y](https://github.com/kunall17/EntryScreenManager) - Intro/Entry/Walkthrough/Starting Screens.
- [EasyIntro ★79 ⏳1Y](https://github.com/meNESS/EasyIntro) - The flexible, easy to use, all in one app intro library for your Android project.
- [Material-Calendar-View ★326](https://github.com/BlackBoxVision/material-calendar-view) - Material Design Calendar compatible with API 8+
- [SectionedRecyclerViewAdapter ★943](https://github.com/luizgrp/SectionedRecyclerViewAdapter) - An Adapter that allows a RecyclerView to be split into Sections with headers and/or footers.
- [DragListView ★395](https://github.com/woxblom/DragListView) - Drag and drop to reorder items in a list, grid or board.
- [Animated Expanding ListView ★124 ⏳1Y](https://github.com/LeonardoCardoso/Animated-Expanding-ListView) - Animated Expanding ListView provides a fancy animation on expanding or collapsing the content of a listview item.
- [TastyToast ★1768](https://github.com/yadav-rahul/TastyToast) - Toasts with icons and color.
- [DotLoader ★103 ⏳1Y](https://github.com/bhargavms/DotLoader) - A customizable loading animation with Dots.
- [PodSlider ★106 ⏳1Y](https://github.com/bhargavms/PodSLider) - A customizable slider widget adhering to material design specs.
- [TapTargetView ★3754](https://github.com/KeepSafe/TapTargetView) - An implementation of tap targets from the Material Design guidelines for feature discovery.
- [ShowCaseView ★62](https://github.com/mreram/ShowCaseView) - The ShowcaseView library is designed to highlight and showcase specific parts of apps to the user with a attractive and flat overlay.
- [MaterialIntroScreen ★2331](https://github.com/TangoAgency/material-intro-screen) - Material Intro Screen implementation with easily extensible API.
- [FloatingView ★1521](https://github.com/UFreedom/FloatingView) - FloatingView can make the target view floating above the anchor view with cool animation.
- [Timecon ★175](https://github.com/alxrm/animated-clock-icon) - Easy-to-use animated clock icon
- [Audiogram ★163](https://github.com/alxrm/audiowave-progressbar) - Lightweight audiowave progressbar
- [Bubbles for Android ★1298](https://github.com/txusballesteros/bubbles-for-android) - Facebook like chat bubble library
- [Litho (By Facebook) ★4940](https://github.com/facebook/litho) - A declarative framework for building efficient UIs on Android.
- [MultiViewAdapter ★399](https://github.com/DevAhamed/MultiViewAdapter) - Recyclerview Adapter library to create composable view holders.
- [LGSnackbar ★35](https://github.com/loregr/LGSnackbar) - An easy to use and customisable wrapper of the native Android Snackbar which stays visible across multiple activities.
- [ShimmerLayout ★1422](https://github.com/team-supercharge/ShimmerLayout) - Memory efficient shimmering effect for Android applications.
- [CircleProgressBar ★15](https://github.com/emre1512/CircleProgressBar) - A simple library for creating circular progressbars for Android.
- [Easy-Signature-Android ★8](https://github.com/smalam119/Easy-Signature-Android) - An simple ui library that provides a plugable signature view.
- [Flashbar ★1090](https://github.com/aritraroy/Flashbar) - A highly customizable, powerful and easy-to-use alerting library for Android.

#### Paginate
- [NoPaginate ★103](https://github.com/NoNews/NoPaginate) - Simple Android pagination library

#### ActionBar
- [ActionBarSherlock](http://actionbarsherlock.com) - ActionBar for older Android versions.
- [FadingActionBar ★2913](https://github.com/ManuelPeinado/FadingActionBar) - Fading action bar effect that can be seen in the new Play Music app.

#### Navigation
- [SlidingMenu ★10994 ⏳1Y](https://github.com/jfeinstein10/SlidingMenu) - Library to create applications with slide-in menus.
- [SlidingTutorial ★2293](https://github.com/Cleveroad/slidingtutorial-android) - Simple library that helps to create awesome sliding android app tutorials.
- [PagerSlidingTabStrip ★6518](https://github.com/astuetz/PagerSlidingTabStrip) - An interactive indicator to navigate between the different pages of a ViewPager.
- [Page View indicator ★9771](https://github.com/JakeWharton/ViewPagerIndicator) - Support for horizontally scrolling ViewPager.
- [RecyclerTabLayout ★1076](https://github.com/nshmura/RecyclerTabLayout) - An efficient TabLayout library implemented with RecyclerView.
- [MaterialDrawer ★9258](https://github.com/mikepenz/MaterialDrawer) - Simple take on a material design navigation drawer.
- [Debug-Artist ★43](https://github.com/baristaventures/debug-artist) - Debug menu to enable leakcanary, scalpel and others easy.
- [Floating-Navigation-View ★933](https://github.com/andremion/Floating-Navigation-View) - A simple Floating Action Button that shows an anchored Navigation View.

#### Animations
- [Rebound ★5058](https://github.com/facebook/rebound) - Rebound is a Java library that models spring dynamics.
- [Android View Animations ★9440](https://github.com/daimajia/AndroidViewAnimations) - Cute view animation collection.
- [Android-Transition ★577](https://github.com/kaichunlin/android-transition) - Allows the easy creation of view transitions that react to user inputs.
- [Android-View-Actions ★132 ⏳1Y](https://github.com/dtx12/AndroidAnimationsActions) - Makes creating complex animations for views easy.
- [Swipper ★73 ⏳1Y](https://github.com/sdsmdg/Swipper) - Android library for swipeable gestures to control volume , brightness and seek .
- [Spotlight ★1427](https://github.com/TakuSemba/Spotlight) - Android Library that lights items for tutorials or walk-throughs etc...

#### Images

- [Crescento ★1098](https://github.com/developer-shivam/crescento) - Explore new style in material design by adding curve below image view.
- [android-crop ★4090](https://github.com/jdamcd/android-crop) - Library project for cropping images.
- [CircularImageView ★1173](https://github.com/Pkmmte/CircularImageView) - Custom view for circular images while maintaining the best draw performance.
- [Android-Image-Filter ★568 ⏳2Y](https://github.com/ragnraok/android-image-filter) - Library project for applying image filters easily.
- [Compressor ★3422](https://github.com/zetbaitsu/Compressor) - Compressor is a lightweight and powerful android image compression library.
- [ShapeImageView ★2167 ⏳1Y](https://github.com/siyamed/android-shape-imageview) - Library to display images in different shapes.

#### Inputs

- [FloatingLabel ★258 ⏳1Y](https://github.com/hardik-trivedi/FloatingLabel) - FloatingLabel Allows you to create a blow kind of EditText. *Doesn't have Gradle or Maven Support.*
- [MaterialEditText ★5187](https://github.com/rengwuxian/MaterialEditText) - Supporting Floating Labels, Single Line Ellipsis, Max/Min Characters, Helper Text and Error Text with Custom Colors.
- [Emojicon ★3248](https://github.com/rockerhieu/emojicon) - Adds emoticons to your app
- [MaterialSearchBar ★1371](https://github.com/mancj/MaterialSearchBar) - Material Design Search Bar for Android
- [InputMask ★577](https://github.com/RedMadRobot/input-mask-android) - Pattern-based user input formatter, parser and validator.
- [SweetPassword ★2](https://github.com/jesusmartinoza/Sweet-Password) - Password EditText that allows to custom toggle button

#### View Pagers
- [Material Dots Indicators ★67](https://github.com/tommybuonomo/dotsindicator) - Three Material Dots Indicators styles for View Pagers.

#### Loading Images

- [Picasso ★15478](https://github.com/square/picasso) - A powerful image downloading and caching library for Android.
- [Universal Image Loader ★16115](https://github.com/nostra13/Android-Universal-Image-Loader) - Asynchronous, out of the box loading and caching of images.
- [Glide ★21769](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling, Recommended by Google.
- [Fresco ★14531](https://github.com/facebook/fresco) - An Android library for managing images and the memory they use.
- [Glide Bitmap Pool ★401](https://github.com/amitshekhariitbhu/GlideBitmapPool) - Glide Bitmap Pool is a memory management library for reusing the bitmap memory.
- [MediaPicker ★129](https://github.com/alhazmy13/MediaPicker) - Android Library that lets you to select multiple images, video or voice for Android

#### Video

- [ijkplayer ★19132](https://github.com/Bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.2, with MediaCodec, VideoToolbox support.
- [Exoplayer ★10066](https://github.com/google/ExoPlayer) - ExoPlayer is an application level media player for Android, allow  playing audio and video both locally and over the Internet.
   Supports features like Dynamic adaptive streaming over HTTP (DASH), SmoothStreaming and Common Encryption
- [Easy-Video-Player ★1152](https://github.com/afollestad/easy-video-player) - Easy Video Player is very simple and easy to use in our app. 
- [VideoPlayView ★63](https://github.com/MarcinMoskala/VideoPlayView) - Custom Android view with video player, play/stop, loader and placeholder image.

#### Camera

- [MagicalCamera ★265 ⏳1Y](https://github.com/fabian7593/MagicalCamera) - Simple way to take or select photos of your gallery, with other features for manage pictures.

#### Field Validation
- [Convalida ★152](https://github.com/WellingtonCosta/convalida) - A simple and annotation-based way to validate your input fields.

### JSON

- [Gson ★12617](https://github.com/google/gson) - Gson is a Java library used for serializing and deserializing Java objects from and into JSON.
- [Jackson JSON Processor ★3854](https://github.com/FasterXML/jackson) - High-performance JSON processor.
- [Moshi ★3871](https://github.com/square/moshi) - A modern JSON library for Android and Java.
### Crash monitoring

- [Fabric Crashlytics](https://get.fabric.io/) - Easy crash reporting solution.
- [HockeyApp](https://www.hockeyapp.net/) - Distribution, Crash Reports, Feedback and Analytics
- [Splunk MINT](https://mint.splunk.com/) - Monitoring, Crash Reports, Real time data, Statistic.
- [Bugsnag](https://www.bugsnag.com/) - Cross platform error monitoring. Free tier. Support for SDK & NDK. Error reports include data on device, release, user, and allows arbitrary data.
- [Catcho ★27 ⏳1Y](https://github.com/alhazmy13/Catcho) - No Force Close any more.
- [Apteligent](https://www.apteligent.com/) - Cross platform crash reporting/analytics solution. Supports NDK log.
- [Instabug](https://instabug.com/) - Bug reporting, Crash Reporting, In-app Feedback.

### Networking

- [Ion ★5723](https://github.com/koush/ion) - Good networking library for android.
- [OkHttp ★26780](https://github.com/square/okhttp) - An HTTP+SPDY client for Android and Java applications.
- [Asynchronous Http Client ★10244](https://github.com/loopj/android-async-http) - An Asynchronous HTTP Library.
- [RoboSpice ★3055](https://github.com/stephanenicolas/robospice) - Library that makes writing asynchronous network requests easy.
- [IceNet ★64 ⏳3Y](https://github.com/anton46/IceNet) - Fast, Simple and Easy Networking for Android
- [Android Volley](https://developer.android.com/training/volley/) - Official Android HTTP library that makes networking for easier and faster.
- [IceSoap ★76 ⏳2Y](https://github.com/AlexGilleran/IceSoap) - Easy, asynchronous, annotation-based SOAP for Android.
- [node-android ★478](https://github.com/InstantWebP2P/node-android) - Run Node.js on Android.
- [HappyDns ★160](https://github.com/qiniu/happy-dns-android) - A Dns library, user can use custom dns server, dnspod httpdns. Only support A record.
- [RESTMock ★622](https://github.com/andrzejchm/RESTMock) - HTTP Web server for mocking API responses in Android Instrumentation tests.
- [Packetzoom](https://www.packetzoom.com/blog/introducing-http-optimizer-and-analytics-service.html) - SDK for optimizing HTTP requests and free analytics service for networking.
- [Fast-Android-Networking ★3312](https://github.com/amitshekhariitbhu/Fast-Android-Networking) - A Complete Fast Android Networking Library that also support HTTP/2.

### Logger
- [logger ★9172](https://github.com/orhanobut/logger) - Simple, pretty and powerful logger for android
- [timber ★5682](https://github.com/JakeWharton/timber) - A logger with a small, extensible API which provides utility on top of Android's normal Log class.
- [LoggingInterceptor ★811](https://github.com/ihsanbal/LoggingInterceptor) - An OkHttp interceptor which pretty logs request and response data.
- [Bugfender ★17](https://github.com/bugfender/BugfenderSDK-android-sample) - Upload your logs and check them online, specially made for mobile
- [EzyLogger ★4 ⏳1Y](https://github.com/afiqiqmal/EzyLogger) - Simple Lightweight logger
- [Logback Android ★616](https://github.com/tony19/logback-android) - Logback port to Android which provides a highly configurable logging framework for Android apps.

### Notifications
- [android-remote-notifications ★76](https://github.com/kaiwinter/android-remote-notifications) - Pulls notifications from a remote JSON file and shows them in your app.
- [Android HeartBeat Fixer ★44 ⏳2Y](https://github.com/joaopedronardari/AndroidHeartBeatFixer) - Way to set heartbeat interval and users receive PushNotifications from GCM.

### Database
- [Cupboard](https://bitbucket.org/littlerobots/cupboard) - Access the sqlite easily via direct database access or through the ContentProvider framework.
- [DbInspector ★778 ⏳1Y](https://github.com/infinum/android_dbinspector) - Provides a simple way to view the contents of the in-app database for debugging purposes.
- [SQLite Asset Helper ★1952](https://github.com/jgilfelt/android-sqlite-asset-helper) - manage database creation and version management using an application's raw asset files.
- [Realm ★9556](https://github.com/realm/realm-java) - The alternative to SQLite and ORMs: Simple, modern and fast! Object oriented API and multi platform support.
- [Realm Asset Helper ★28 ⏳1Y](https://github.com/eggheadgames/android-realm-asset-helper) - Copies a realm database from the apk assets folder. Efficiently handles versioning of read-only realm databases.
- [RestorableSQLiteDatabase ★17 ⏳2Y](https://github.com/yaa110/RestorableSQLiteDatabase) - A wrapper to replicate android's SQLiteDatabase with restoring capability.
- [Nitrite Database ★189](https://github.com/dizitart/nitrite-database) - A NoSQL embedded document store for Android with MongoDb like API.

#### ORM

- [requery ★2490](https://github.com/requery/requery) - Compile time ORM and SQL query library for Java & Android.
- [GreenDAO](http://greenrobot.org/greendao/) - Light & fast ORM solution.
- [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml) - Lightweight ORM Java package for JDBC and Android.
- [ActiveAndroid](http://www.activeandroid.com) - Active record style ORM.
- [Sugar ORM](http://satyan.github.io/sugar/) - Insanely easy way to work with Android Databases.
- [DBFlow ★4204](https://github.com/Raizlabs/DBFlow) - Fast and powerful ORM with compile-time annotation processing.
- [NexusData ★70 ⏳3Y](https://github.com/dkharrat/NexusData) - Object graph and persistence framework for Android.
- [SimpleNoSQL ★399](https://github.com/Jearil/SimpleNoSQL) - A simple NoSQL client for Android. Meant as a document store using key/value pairs and some rudimentary querying. Useful for avoiding the hassle of SQL code.
- [RxSimpleNoSQL ★40](https://github.com/xmartlabs/RxSimpleNoSQL) - Reactive extensions for SimpleNoSQL. Manipulate entities using Observables.

### REST

- [Retrofit](http://square.github.io/retrofit/) - Retrofit turns your REST API into a Java interface.
- [Spring for Android - Rest Template ★667 ⏳2Y](https://github.com/spring-projects/spring-android) - A Rest Client for Android.

### Testing

- [Robotium ★2391 ⏳1Y](https://github.com/robotiumtech/robotium) - Test automation framework for black-box UI tests.
- [Roboletric](http://robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.
- [AssertJ Android ★1555](https://github.com/square/assertj-android) - AssertJ assertions geared towards Android.
- [Green Coffee ★177](https://github.com/mauriciotogneri/green-coffee) - Run your Cucumber tests in your Android instrumentation tests.

### Tracking

- [MobileAppTracking](https://www.tune.com/) - Tracking your marketing campaigns across multiple ad networks.
- [Mixpanel](https://mixpanel.com/) - Analytics platform to analyze the users.
- [Countly](https://count.ly) - Open source mobile & web analytics, push notifications and crash reporting platform, based on Node.js, MongoDB and Linux.
- [CleverTap](https://clevertap.com) - Analytics platform and user-engagement platform with 1 million free events

### Maps

- [Google-Directions-Android ★790](https://github.com/jd-alexander/Google-Directions-Android) - Allows you to calculate the direction between two locations and display the route on a Google Map using the Google Directions API.
- [Android Maps Extensions ★381](https://github.com/mg6maciej/android-maps-extensions) - Extending capabilities of Google Maps Android API v2, adding marker clustering among other things
- [MapScaleView ★66](https://github.com/pengrad/MapScaleView) - Scale bar for Google Maps Android API

### Utility

- [Conceal SharedPreferences ★69](https://github.com/afiqiqmal/SharedChamber) - Secured Preferences using Facebook Secure Encryption called Conceal.
- [EventBus](http://greenrobot.github.io/EventBus/) - EventBus is a library that simplifies communication between different parts of your application.
- [Otto ★5087](https://github.com/square/otto) - Event Bus for Android.
- [Weak handler ★1244](https://github.com/badoo/android-weak-handler) - Memory safer implementation of android.os.Handler.
- [Byte Buddy](http://bytebuddy.net) - Runtime code generation library with support for Android.
- [Secure Preference Manager ★68 ⏳1Y](https://github.com/prashantsolanki3/Secure-Pref-Manager) - Secure Preference Manager for android. It uses various Encryption to protect your application's Shared Preferences.
- [LeakCanary ★19461](https://github.com/square/leakcanary) - Catch memory leaks as they occur.
- [Drekkar ★20 ⏳2Y](https://github.com/coshx/drekkar) - An Android event bus for WebView and JS.
- [Androl4b ★605](https://github.com/sh4hin/Androl4b) - A vm for assessing android applications.
- [DroidMVP ★227](https://github.com/andrzejchm/DroidMVP) - Android library to help you incorporate MVP along with Passive View and Presentation Model patterns into your app.
- [Gota ★56](https://github.com/alhazmy13/Gota) - Simplifying Android Permissions.
- [EasyDeviceInfo ★1379](https://github.com/nisrulz/easydeviceinfo) - Get device information in a super easy way.
- [Ask-Permission ★48](https://github.com/Kishanjvaghela/Ask-Permission) - Simple RunTime permission manager.
- [Shutter-Android ★30](https://github.com/levibostian/Shutter-Android) - Capture photos/videos from device camera or get photos/video from gallery app with no runtime permissions needed.
- [Validator ★30](https://github.com/anderscheow/Validator) - An utilities class to validate text inside TextInputLayout.

### Debugging Tools

- [Linx ★614](https://github.com/pedrovgs/Lynx) - Show logcat inside the device for debug builds
- [Scalpel ★2500 ⏳1Y](https://github.com/JakeWharton/scalpel) - View the entire hierarchy in 3d in the phone.
- [Stetho ★9731](https://github.com/facebook/stetho) - Debug hierarchy and network from chrome.
- [Android Debug Database ★4196](https://github.com/amitshekhariitbhu/Android-Debug-Database) - Android Debug Database is a powerful library for debugging databases and shared preferences in Android applications.
- [Android Debug Bridge - ADB](https://github.com/mzlogin/awesome-adb/blob/master/README.en.md) - a command-line tool to assist in debugging Android-powered devices
- [ADB Enhanced ★65](https://github.com/ashishb/adb-enhanced) - a command-line wrapper around ADB for developers, so that, developers don't have to remember esoteric version-dependent commands
- [Pidcat ★3456](https://github.com/JakeWharton/pidcat) - a colored command-line ADB wrapper that only shows log entries for a specific application package

### Wireless

- [SmartGattLib ★234](https://github.com/movisens/SmartGattLib) - Simplifies the work with Bluetooth SMART devices (a.k.a. Bluetooth Low Energy in Bluetooth 4.0).

### Chat & Messaging

- [Applozic Android Chat SDK ★461](https://github.com/AppLozic/Applozic-Android-SDK) - Android Chat and Messaging SDK for adding real time chat and in-app messaging into your android application.
- [Qiscus SDK ★131](https://github.com/qiscus/qiscus-sdk-android) - Qiscus SDK is a lightweight and powerful android chat library. Qiscus SDK will allow you to easily integrating Qiscus engine with your apps to make cool chatting application.
- [Kommunicate Live Chat SDK ★16](https://github.com/Kommunicate-io/Kommunicate-Android-Chat-SDK) - Kommunicate provides open source live chat sdk in android. Kommunicate lets you add real time live chat and in-app messaging in your mobile (android, iOS) applications and website for customer support.

#### Custom Dialog

- [MediaRecorderDialog ★52 ⏳1Y](https://github.com/alhazmy13/MediaRecorderDialog) - Custom Dialog to record audio, store it and play it in your phone.
- [HijriDatePicker ★70](https://github.com/alhazmy13/HijriDatePicker) - offers a hijri (Islamic Calendar) Date Picker designed on Google's Material Design Principals For Pickers.
- [Noty ★46](https://github.com/emre1512/Noty) - A simple library for creating animated alerts/dialogs/warnings.

### Version Checking

 - [AppUpdater ★1134](https://github.com/javiersantos/AppUpdater) - comprehensive and feature rich library, including support for checks at Amazon and FDroid.
 - [Gandalf ★291 ⏳1Y](https://github.com/btkelly/gandalf) - comprehensive features and a "companion" iOS solution.
 - [Siren ★79](https://github.com/eggheadgames/Siren) - focused feature set that mimicks the popular iOS library of the same name. Supports Play and Amazon.
 - [Fit ★56 ⏳1Y](https://github.com/KeithYokoma/Fit) - version checking callback framework with no UI.

### Date & Time

- [ThreeTen Android Backport ★2144](https://github.com/JakeWharton/ThreeTenABP) - An adaptation of the JSR-310 backport for Android.
- [Joda-Time Android ★2173](https://github.com/dlew/joda-time-android) - Joda-Time library with Android specialization.
- [True Time ★655](https://github.com/instacart/truetime-android) - Android NTP time library. Get the true current time impervious to device clock time changes.

### Runtime Permissions

- [Permission Dispatcher ★7300](https://github.com/permissions-dispatcher/PermissionsDispatcher) - Simple annotation-based API to handle runtime permissions.
- [RxPermissions ★6273](https://github.com/tbruyelle/RxPermissions) - Android runtime permissions powered by RxJava.
- [NoPermission ★81](https://github.com/NoNews/NoPermission) - Simple Android library for permissions request. Consists of only one class.

### Other

- [Android Support library](https://developer.android.com/topic/libraries/support-library/) - The Android Support Library package is a set of code libraries that provide backward-compatible versions of Android framework API.
- [Google Play Services](https://developers.google.com/android/guides/overview) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
- [Tape ★2071](https://github.com/square/tape) - A lightning fast, transactional, file-based FIFO for Android and Java.
- [Guava: Google Core Libraries for Java ★24301](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
- [Android Scripting ★1646](https://github.com/damonkohler/sl4a) - Allows to run scripting languages on Android.
- [Android Priority Job Queue ★3096](https://github.com/yigit/android-priority-jobqueue) - Implementation of a Job Queue to easily schedule jobs (tasks) that run in the background, improving UX and application stability.
- [RateMeMaybe ★95 ⏳5Y](https://github.com/nspo/RateMeMaybe) - Asks the user if (s)he wants to open the Play Store to rate your application.
- [Easy Rating Dialog ★102](https://github.com/fernandodev/easy-rating-dialog) - Lib provides a simple way to display an alert dialog for rating app.
- [ZXing Android-Integration ★18636](https://github.com/zxing/zxing) - Integration with Barcode Scanner via Intent.
- [Gradle Retrolambda Plugin ★5274](https://github.com/evant/gradle-retrolambda) - Java 8 Lambdas on Android!
- [RxJava ★33172](https://github.com/ReactiveX/RxJava)- RxJava – Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
- [RxBinding ★7468](https://github.com/JakeWharton/RxBinding)- RxBinding – RxJava binding APIs for Android UI widgets from the platform and support libraries.
- [Caffeine ★420 ⏳1Y](https://github.com/percolate/caffeine) - A collection of utility classes that help make Android development faster.
- [AboutLibraries ★2082](https://github.com/mikepenz/AboutLibraries) - Automatically generates an About this app section, with a list of used libraries.
- [AudioPlayerView ★79](https://github.com/HugoMatilla/AudioPlayerView) - A view that loads audio from an url and have basic playback tools.
- [andle ★53](https://github.com/Jintin/andle) - command line tool help you sync dependencies, sdk or build tool version.
- [Typography ★38 ⏳2Y](https://github.com/workarounds/typography) - An Android library that makes it easy to use custom fonts in views.
- [Calligraphy ★7716](https://github.com/chrisjenx/Calligraphy) - Custom fonts in Android an OK way.
- [transai ★52](https://github.com/Jintin/transai) - command line tool help you manage localization string files.
- [Android-Link-Preview ★314](https://github.com/LeonardoCardoso/Android-Link-Preview) - It makes a preview from an url, grabbing all the information such as title, relevant texts and images.
- [Sensey ★2255](https://github.com/nisrulz/sensey) - Detecting gestures in a snap.
- [UserAwareVideoView ★46 ⏳1Y](https://github.com/kevalpatel2106/UserAwareVideoView) - A customized video view that will automatically pause video is user is not looking at device screen!
- [Flexbox Layout ★11472](https://github.com/google/flexbox-layout) - FlexboxLayout is a library which brings the similar capabilities of CSS Flexible Box Layout Module to Android. 
- [Agile Boiler Plate ★44 ⏳1Y](https://github.com/xresco/Android-Agile-Boiler-Plate) - The boiler plate is based on MVP architecture and it is fully based on Dependency Injection design pattern using Dagger2.

## Resources

- [Programming Community Curated Resources for Learning Android Development](https://hackr.io/tutorials/learn-android-development) - Android Tutorials & Courses submitted and voted by the programming community.
- [Vogella Tutorials](http://www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
- [Android Design in Action Video series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc8j2B95zGMb8muZvrIy-wcF) The video series by Android Design Team of Google.
- [Android DevBytes Video Series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_XOgcRukSoKKjewFJZrKV0) - It is the technical counterpart of Android Design in Action series.
- [Developing for Android](https://medium.com/google-developers/developing-for-android-introduction-5345b451567c) - A series of articles from Googler Chet Hasae and others, answering most commonly asked question: "What are some of the important rules to keep in mind when developing Android applications?".
- [Android Hive Tutorials](https://www.androidhive.info) - Very good tutorials for beginners.
- [Android Weekly](https://androidweekly.net) - Newsletter with weekly information about android.
- [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
- [Android Action Bar Style Generator](http://jgilfelt.github.io/android-actionbarstylegenerator/).
- [Device Art Generator](https://developer.android.com/distribute/marketing-tools/device-art-generator) - Wraps app screenshots in real device artwork.
- [Android UI design resources](https://androiduiux.com/free-design-resources/) - Gives you wide variety of design resources form a Google Developer Expert in UI/UX.
- [Pencil Project](https://pencil.evolus.vn/) - An open source prototyping software.
- [How to Make Android Apps](https://www.youtube.com/playlist?list=PLGLfVvz_LVvSPjWpLPFEfOCbezi6vATIh) - Video tutorials by Derek Banas.
- [android-blogs ★443](https://github.com/vbauer/android-blogs) - List with blogs about Android.
- [Future Studio](https://futurestud.io/tutorials/tag/android) - Extensive Android tutorials on Retrofit, Picasso, Glide & Gson.
- [Android Tips & Tricks ★3403](https://github.com/nisrulz/android-tips-tricks) - Cheatsheet about tips and tricks for Android Development.
- [Droid Talks](http://www.droidtalks.pro/) -  Awesome Android talks and learning resources, categorised by topic.
- [Associate Android Developer Certification Materials ★616](https://github.com/Amejia481/Associate-Android-Developer-Certification) - A collection of materials for getting ready for the test.
- [Google Developers Training](https://developers.google.com/training/android/) -  Google Developers Official Training page has list of various useful learning resources for beginner as well seasoned developer.

### Podcast
- [Fragmented](http://fragmentedpodcast.com/)  is the Android developer podcast where Donn Felker and Kaushik Gopal talk about building good software and becoming better Android developers.
- [Android Developers Backstage](http://androidbackstage.blogspot.com/) is a podcast by and for Android developers. Hosted by developers from the Android engineering team, this show covers topics of interest to Android programmers, with in-depth discussions and interviews with engineers on the Android team at Google.
- [Android Dialogs](https://www.youtube.com/channel/UCMEmNnHT69aZuaOrE-dF6ug/feed) is a video based podcast, where they have bite-sized conversations with people from the Android community.
- [Android Intelligence](https://plus.google.com/collection/ATg6b) features in-depth interviews with interesting people from the Android world.
- [The Context ★544](https://github.com/artem-zinnatullin/TheContext-Podcast) a podcast about Android Development with Hannes Dorfmann, Artem Zinnatullin and wonderful guests!


### More lists of libraries
- [The Android Arsenal](https://android-arsenal.com/) - Large list of android libraries
- [Square libraries](http://square.github.io/#android) - Multiple high quality libraries by square.
- [Awesome Android @LibHunt](https://android.libhunt.com) - Your go-to Android Toolbox.

## Development Alternatives

My personal recommendation is (for now) to use the android api to build a native app. Scala can help to build this native apps with cleaner code but it adds to many methods (Multidex required). Kotlin is a modern language with 100% interoperatibility with java projects **without multidex**. But there are also use cases where alternatives like cross-platform development can be useful.

### C&#35;

- [Xamarin](https://www.xamarin.com/) - Framework to create native iOS, Android, Mac and Windows apps in C#.

### HTML, CSS and Javascript

- [PhoneGap](https://phonegap.com) - Open source framework by Adobe to create cross platform mobile apps using HTML, CSS, and JavaScript.
- [Titanium](http://www.appcelerator.com/mobile-app-development-products/) - Open-source framework to create 'native' cross platform apps using JavaScript.
- [NativeScript](https://www.nativescript.org/) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
- [React Native ★64108](https://github.com/facebook/react-native) - A framework for building native apps with React by Facebook.
- [Ionic Framework](https://ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.
- [Apache Cordova ★2265](https://github.com/apache/cordova-android) - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript.
- [Capacitor ★1200](https://github.com/ionic-team/capacitor) - Build cross-platform Native Progressive Web Apps for iOS, Android, and the web. Very promising Cordova alternative. 

### Lua
- [Corona SDK](https://coronalabs.com/product/) - Framework to create native iOS and Android Apps (especially Games).

### Scala
- [Scaloid ★2098](https://github.com/pocorall/scaloid) - Library for less painful Android development with Scala.
- [Macroid ★536](https://github.com/47deg/macroid) - A modular functional UI language for Android.

### Groovy
- [Groovy on Android](http://melix.github.io/blog/2014/06/grooid.html) - Introduction to Groovy on Android.
- [Groovy Language Support for Android ★778](https://github.com/groovy/groovy-android-gradle-plugin) - Gradle Plugin for Compiling Groovy for Android.
- [SwissKnife ★260 ⏳2Y](https://github.com/Arasthel/SwissKnife) - A multi-purpose Groovy library containing view injection and threading for Android using annotations.

### Kotlin
- [Anko ★11106](https://github.com/Kotlin/anko) - DSL for Android written in Kotlin by JetBrains.
- [Kotterknife ★1973](https://github.com/JakeWharton/kotterknife) - Android view injection written in Kotlin based on ButterKnife
- [Android Kotlin Samples ★236](https://github.com/irontec/android-kotlin-samples) - Some basic Android code samples written in Kotlin.
- [KAndroid ★738](https://github.com/pawegio/KAndroid) - Lightweight library providing useful extensions to eliminate boilerplate code in Android SDK.
- [RxKotlin/Pocket ★19 ⏳1Y](https://github.com/RxKotlin/Pocket) - This app help user to save links easily, and can export to Evernote as weekly.
- [Android Clean Architecture - Kotlin ★224](https://github.com/patrickyin/clean-architecture-android-kotlin) - A base project using the Uncle Bob's clean architecture with Kotlin language and the latest Android technologies.
- [Koin](https://insert-koin.io/) - Lightweight dependency injection framework for Kotlin

### Flutter
- [Flutter](https://flutter.io/) - Google's mobile app SDK for high-quality native interfaces for Android and iOS in very quick time.

# Performance
- [awesome-android-performance ★2368](https://github.com/Juude/awesome-android-performance) - A list of awesome Android tutorials, videos and tools for performance optimization.

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness ★21454](https://github.com/bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](https://github.com/JStumpp/awesome-android/blob/master/contributing.md) first.
---
<p align="center">
	This list is a copy of <a href="https://github.com/JStumpp/awesome-android">JStumpp/awesome-android</a> with ranks
</p>
