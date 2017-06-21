---
layout: default
title: Awesome Rank for ashishb/android-security-awesome
---

<p align="center">
	This list is a copy of <a href="https://github.com/ashishb/android-security-awesome">ashishb/android-security-awesome</a> with ranks
</p>
---
android-security-awesome [![Backers on Open Collective](https://opencollective.com/android-security-awesome/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/android-security-awesome/sponsors/badge.svg)](#sponsors) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)
========================

A collection of android security related resources.

1. [TOOLS](#tools)
2. [ACADEMIC / RESEARCH / PUBLICATIONS / BOOKS](#academic)
3. [EXPLOITS / VULNERABILITIES / BUGS](#exploits)

----
# <a name="tools"></a>TOOLS

Online Analyzers
----

1. [AndroTotal](http://andrototal.org/)
* [Dexter](https://dexter.dexlabs.org/)
* [Tracedroid](http://tracedroid.few.vu.nl/)
* [Visual Threat](http://www.visualthreat.com/)
* [Mobile Malware Sandbox](http://www.mobilemalware.com.br/analysis/index_en.php)
* [MobiSec Eacus](http://www.mobiseclab.org/eacus.jsp)
* [Appknox](https://appknox.com) - not free
* [IBM Security AppScan Mobile Analyzer](https://appscan.bluemix.net/mobileAnalyzer) - not free
* [NVISO ApkScan](https://apkscan.nviso.be/)
* [AVC UnDroid](http://www.av-comparatives.org/avc-analyzer/)
* [Fireeye](https://fireeye.ijinshan.com/)- max 60MB 15/day
* [habo](https://habo.qq.com/) 10/day
* [Virustotal](https://www.virustotal.com/)-max 128MB
* [Fraunhofer App-ray](http://www.app-ray.co) - not free
* [AppCritique](http://appcritique.io/) - Upload your Android APKs and receive comprehensive free security assessments.
* ~~[CopperDroid](http://copperdroid.isg.rhul.ac.uk/copperdroid/)~~
* ~~[SandDroid](http://sanddroid.xjtu.edu.cn/)~~
* ~~[Stowaway](http://www.android-permissions.org/)~~
* ~~[Anubis](http://anubis.iseclab.org/)~~
* ~~[Mobile app insight](http://www.mobile-app-insight.org)~~
* ~~[Mobile-Sandbox](http://mobile-sandbox.com)~~
* ~~[Ijiami](http://safe.ijiami.cn/)~~
* ~~[Comdroid](http://www.comdroid.org/)~~
* ~~[Android Sandbox](http://www.androidsandbox.net/)~~
* ~~[Foresafe](http://www.foresafe.com/scan)~~

Static Analysis Tools
----

1. [Androwarn ★153 ⏳4Y](https://github.com/maaaaz/androwarn) - detect and warn the user about potential malicious behaviours developped by an Android application.
* [ApkAnalyser ★796 ⏳4Y](https://github.com/sonyxperiadev/ApkAnalyser)
* [APKInspector ★486 ⏳4Y](https://github.com/honeynet/apkinspector)
* [Droid Intent Data Flow Analysis for Information Leakage](https://www.cert.org/secure-coding/tools/didfail.cfm)
* [DroidLegacy](https://bitbucket.org/srl/droidlegacy)
* [Several tools from PSU](http://siis.cse.psu.edu/tools.html)
* [Smali CFG generator ★56 ⏳3Y](https://github.com/EugenioDelfa/Smali-CFGs)
* [FlowDroid](https://blogs.uni-paderborn.de/sse/tools/flowdroid/)
* [Android Decompiler](https://www.pnfsoftware.com/) – not free
* [PSCout](http://pscout.csl.toronto.edu/) - A tool that extracts the permission specification from the Android OS source code using static analysis
* [Amandroid](http://amandroid.sireum.org/)
* [SmaliSCA ★174](https://github.com/dorneanu/smalisca) - Smali Static Code Analysis
* [CFGScanDroid ★21 ⏳2Y](https://github.com/douggard/CFGScanDroid) - Scans and compares CFG against CFG of malicious applications
* [Madrolyzer ★51 ⏳2Y](https://github.com/maldroid/maldrolyzer) - extracts actionable data like C&C, phone number etc.
* [SPARTA](http://www.cs.washington.edu/sparta) - verifies (proves) that an app satisfies an information-flow security policy; built on the [Checker Framework](http://types.cs.washington.edu/checker-framework/)
* [ConDroid ★16 ⏳1Y](https://github.com/JulianSchuette/ConDroid) - Performs a combination of symoblic + concrete execution of the app
* [DroidRA ★10](https://github.com/serval-snt-uni-lu/DroidRA)

App Vulnerability Scanners
----

1. [QARK ★1313](https://github.com/linkedin/qark) - QARK by LinkedIn is for app developers to scan app for security issues
* [AndroBugs ★398](https://github.com/AndroBugs/AndroBugs_Framework)
* [Nogotofail ★2101](https://github.com/google/nogotofail)
* [Devknox](https://devknox.io/) - Autocorrect security issues as if it was spell check from your IDE
* [JAADAS ★147](https://github.com/flankerhqd/JAADAS) - Joint intraprocedure and interprocedure program analysis tool to find vulnerabilities in Android apps, built on Soot and Scala

Dynamic Analysis Tools
----

1. [Android DBI frameowork](http://www.mulliner.org/blog/blosxom.cgi/security/androiddbiv02.html)
2. [Androl4b ★378](https://github.com/sh4hin/Androl4b)- A Virtual Machine For Assessing Android applications, Reverse Engineering and Malware Analysis
* [Android Malware Analysis Toolkit](http://www.mobilemalware.com.br/amat/download.html) - (linux distro) Earlier it use to be an [online analyzer](http://dunkelheit.com.br/amat/analysis/index_en.php)
* [Mobile-Security-Framework MobSF](https://github.com/ajinabraham/Mobile-Security-Framework-MobSF) - Mobile Security Framework is an intelligent, all-in-one open source mobile application (Android/iOS) automated pen-testing framework capable of performing static, dynamic analysis and web API testing.
* [AppUse](https://appsec-labs.com/AppUse/) – custom build for pentesting
* [Cobradroid](https://thecobraden.com/projects/cobradroid/) – custom image for malware analysis
* [ViaLab Community Edition](https://www.nowsecure.com/blog/2014/09/09/introducing-vialab-community-edition/)
* [Droidbox ★271 ⏳1Y](https://github.com/pjlantz/droidbox)
* ~~[Mercury](https://labs.mwrinfosecurity.com/tools/2012/03/16/mercury/)~~
* [Drozer ★1011](https://github.com/mwrlabs/drozer)
* [Xposed](https://forum.xda-developers.com/xposed/xposed-installer-versions-changelog-t2714053) - equivalent of doing Stub based code injection but without any modifications to the binary
* [Inspeckage ★579](https://github.com/ac-pm/Inspeckage) - Android Package Inspector - dynamic analysis with api hooks, start unexported activities and more. (Xposed Module)
* [Android Hooker ★271](https://github.com/AndroidHooker/hooker) - Dynamic Java code instrumentation (requires the Substrate Framework)
* [ProbeDroid ★115](https://github.com/ZSShen/ProbeDroid) - Dynamic Java code instrumentation
* [Android Tamer](https://androidtamer.com/) - Virtual / Live Platform for Android Security Professionals
* [DECAF ★168](https://github.com/sycurelab/DECAF) - Dynamic Executable Code Analysis Framework based on QEMU (DroidScope is now an extension to DECAF)
* [CuckooDroid ★244](https://github.com/idanr1986/cuckoo-droid) - Android extension for Cuckoo sandbox
* [Mem ★23 ⏳2Y](https://github.com/MobileForensicsResearch/mem) - Memory analysis of Android (root required)
* [Crowdroid](http://www.ida.liu.se/labs/rtslab/publications/2011/spsm11-burguera.pdf) – unable to find the actual tool
* [AuditdAndroid ★23 ⏳4Y](https://github.com/nwhusted/AuditdAndroid) – android port of auditd, not under active development anymore
* [Android Security Evaluation Framework](https://code.google.com/p/asef/) - not under active development anymore
* [Android Reverse Engineering](https://redmine.honeynet.org/projects/are/wiki) – ARE (android reverse engineering) not under active development anymore
* [Aurasium ★16 ⏳2Y](https://github.com/xurubin/aurasium) – Practical security policy enforcement for Android apps via bytecode rewriting and in-place reference monitor.
* [Android Linux Kernel modules ★86 ⏳2Y](https://github.com/strazzere/android-lkms)
* [Appie](https://manifestsecurity.com/appie/) - Appie is a software package that has been pre-configured to function as an Android Pentesting Environment.It is completely portable and can be carried on USB stick or smartphone.This is a one stop answer for all the tools needed in Android Application Security Assessment and an awesome alternative to existing virtual machines.
* [StaDynA ★3](https://github.com/zyrikby/StaDynA) - a system supporting security app analysis in the presence of dynamic code update features (dynamic class loading and reflection). This tool combines static and dynamic analysis of Android applications in order to reveal the hidden/updated behavior and extend static analysis results with this information.
* [DroidAnalytics ★19 ⏳2Y](https://github.com/zhengmin1989/DroidAnalytics) - incomplete
* [Vezir Project ★48 ⏳1Y](https://github.com/oguzhantopgul/Vezir-Project) - Virtual Machine for Mobile Application Pentesting and Mobile Malware Analysis
* [MARA ★160](https://github.com/xtiankisutsa/MARA_Framework) - Mobile Application Reverse engineering and Analysis Framework
* [NowSecure Lab Automated](https://www.nowsecure.com/blog/2016/09/19/announcing-nowsecure-lab-automated/) - Enterprise tool for mobile app security testing both Android and iOS mobile apps. Lab Automated features dynamic and static analysis on real devices in the cloud to return results in minutes.
* ~~[Taintdroid](https://appanalysis.org/download.html)~~ - requires AOSP compilation

Reverse Engineering
----

1. [Smali/Baksmali ★1823](https://github.com/JesusFreke/smali) – apk decompilation
* [emacs syntax coloring for smali files ★19 ⏳1Y](https://github.com/strazzere/Emacs-Smali)
* [vim syntax coloring for smali files](http://codetastrophe.com/smali.vim)
* [AndBug ★393](https://github.com/swdunlop/AndBug)
* [Androguard ★1498](https://github.com/androguard/androguard) – powerful, integrates well with other tools
* [Apktool](https://ibotpeaches.github.io/Apktool/) – really useful for compilation/decompilation (uses smali)
* [Android Framework for Exploitation ★119 ⏳1Y](https://github.com/appknox/AFE)
* [Bypass signature and permission checks for IPCs ★43 ⏳3Y](https://github.com/iSECPartners/Android-KillPermAndSigChecks)
* [Android OpenDebug ★54 ⏳3Y](https://github.com/iSECPartners/Android-OpenDebug) – make any application on device debuggable (using cydia substrate).
* [Dare](http://siis.cse.psu.edu/dare/index.html) – .dex to .class converter
* [Dex2Jar ★3166](https://github.com/pxb1988/dex2jar) - dex to jar converter
* [Enjarify ★1901](https://github.com/google/enjarify) - dex to jar converter from Google
* [Dedexer](http://dedexer.sourceforge.net)
* [Fino ★73 ⏳2Y](https://github.com/sysdream/fino)
* [Frida](http://www.frida.re/) - inject javascript to explore applications and a [GUI tool ★65](https://github.com/antojoseph/diff-gui) for it
* [Indroid](https://bitbucket.org/aseemjakhar/indroid) – thread injection kit
* [IntentSniffer](https://www.nccgroup.trust/us/about-us/resources/intent-sniffer/)
* [Introspy ★289 ⏳3Y](https://github.com/iSECPartners/Introspy-Android)
* [Jad]( http://varaneckas.com/jad/) - Java decompiler
* [JD-GUI ★3383](https://github.com/java-decompiler/jd-gui) - Java decompiler
* [CFR](http://www.benf.org/other/cfr/) - Java decompiler
* [Krakatau ★702](https://github.com/Storyyeller/Krakatau) - Java decompiler
* [Procyon](https://bitbucket.org/mstrobel/procyon/wiki/Java%20Decompiler) - Java decompiler
* [FernFlower ★708](https://github.com/fesh0r/fernflower) - Java decompiler
* [Redexer ★98](https://github.com/plum-umd/redexer) – apk manipulation
* [Smali viewer](http://blog.avlyun.com/wp-content/uploads/2014/04/SmaliViewer.zip)
* ~~[ZjDroid](https://github.com/BaiduSecurityLabs/ZjDroid)~~, ~~[fork/mirror](https://github.com/yangbean9/ZjDroid)~~
* [Simplify Android deobfuscator ★652](https://github.com/CalebFenton/simplify)
* [Bytecode viewer ★1704](https://github.com/Konloch/bytecode-viewer)
* [Radare2 ★4714](https://github.com/radare/radare2)

Fuzz Testing
----

1. [IntentFuzzer](https://www.nccgroup.trust/us/about-us/resources/intent-fuzzer/)
* [Radamsa Fuzzer ★29 ⏳1Y](https://github.com/anestisb/radamsa-android)
* [Honggfuzz ★682](https://github.com/google/honggfuzz)
* [An Android port of the melkor ELF fuzzer ★43 ⏳2Y](https://github.com/anestisb/melkor-android)
* [Media Fuzzing Framework for Android ★204 ⏳1Y](https://github.com/fuzzing/MFFA)
* [AndroFuzz ★23 ⏳2Y](https://github.com/jonmetz/AndroFuzz)

App Repackaging Detectors
----

1. [FSquaDRA ★33 ⏳1Y](https://github.com/zyrikby/FSquaDRA) - a tool for detection of repackaged Android applications based on app resources hash comparison.

Market Crawlers
----

1. [Google play crawler (Java) ★325](https://github.com/Akdeniz/google-play-crawler)
* [Google play crawler (Python) ★614](https://github.com/egirault/googleplay-api)
* [Google play crawler (Node)  ★91](https://github.com/dweinstein/node-google-play) - get app details and download apps from official Google Play Store.
* [Aptoide downloader (Node) ★12 ⏳1Y](https://github.com/dweinstein/node-aptoide) - download apps from Aptoide third-party Android market
* [Appland downloader (Node) ★5 ⏳1Y](https://github.com/dweinstein/node-appland) - download apps from Appland third-party Android market

Misc Tools
----

1. [smalihook](http://androidcracking.blogspot.com/2011/03/original-smalihook-java-source.html)
* [APK-Downloader](http://codekiem.com/2012/02/24/apk-downloader/)
* [AXMLPrinter2](http://code.google.com/p/android4me/downloads/detail?name=AXMLPrinter2.jar) - to convert binary XML files to human-readable XML files
* [adb autocomplete ★158](https://github.com/mbrubeck/android-completion)
* [Dalvik opcodes](http://pallergabor.uw.hu/androidblog/dalvik_opcodes.html)
* [Opcodes table for quick reference](http://www.xchg.info/corkami/opcodes_tables.pdf)
* [ExploitMe Android Labs](http://securitycompass.github.io/AndroidLabs/setup.html) - for practice
* [GoatDroid ★148 ⏳2Y](https://github.com/jackMannino/OWASP-GoatDroid-Project) - for practice
* [mitmproxy ★7819](https://github.com/mitmproxy/mitmproxy)
* [dockerfile/androguard ★26](https://github.com/dweinstein/dockerfile-androguard)
* [Android Vulnerability Test Suite ★829](https://github.com/AndroidVTS/android-vts) - android-vts scans a device for set of vulnerabilities

----

# <a name="academic"></a>ACADEMIC / RESEARCH / PUBLICATIONS / BOOKS

Research Papers
----
1. [Exploit Database](https://www.exploit-db.com/papers/) 
* [Android security related presentations ★70 ⏳2Y](https://github.com/jacobsoo/AndroidSlides)
* [A good collection of static analysis papers](https://tthtlc.wordpress.com/2011/09/01/static-analysis-of-android-applications/)

Books
----
1. [SEI CERT Android Secure Coding Standard](https://www.securecoding.cert.org/confluence/display/android/Android+Secure+Coding+Standard)

Others
----
1. [OWASP Mobile Security Testing Guide Manual ★1024](https://github.com/OWASP/owasp-mstg) 
* [Android Reverse Engineering 101 by Daniele Altomare](http://www.fasteque.com/android-reverse-engineering-101-part-1/)
* [doridori/Android-Security-Reference ★363](https://github.com/doridori/Android-Security-Reference)

----

# <a name="exploits"></a>EXPLOITS / VULNERABILITIES / BUGS

List
----

1. [Android Security Bulletins](https://source.android.com/security/bulletin/)
* [Android's reported security vulnerabilities](https://www.cvedetails.com/vulnerability-list/vendor_id-1224/product_id-19997/Google-Android.html)
* [Android Devices Security Patch Status](https://kb.androidtamer.com/Device_Security_Patch_tracker/)
* [AOSP - Issue tracker](https://code.google.com/p/android/issues/list?can=2&q=priority=Critical&sort=-opened)
* [OWASP Mobile Top 10 2016](https://www.owasp.org/index.php/Mobile_Top_10_2016-Top_10)
* [Exploit Database](https://www.exploit-db.com/search/?action=search&q=android) - click search
* [Vulnerability Google Doc](https://docs.google.com/spreadsheet/pub?key=0Am5hHW4ATym7dGhFU1A4X2lqbUJtRm1QSWNRc3E0UlE&single=true&gid=0&output=html)
* [Google Android Security Team’s Classifications for Potentially Harmful Applications (Malware)](https://static.googleusercontent.com/media/source.android.com/en//security/reports/Google_Android_Security_PHA_classifications.pdf)


Malware
----
1. [androguard - Database Android Malwares wiki](https://code.google.com/p/androguard/wiki/DatabaseAndroidMalwares)
* [Android Malware Github repo ★76](https://github.com/ashishb/android-malware)
* [Android Malware Genome Project](http://www.malgenomeproject.org/policy.html) - contains 1260 malware samples categorized into 49 different malware families, free for research purpose.
* [Contagio Mobile Malware Mini Dump](http://contagiominidump.blogspot.com)
* [VirusTotal Malware Intelligence Service](https://www.virustotal.com/en/about/contact/) - powered by VirusTotal, not free
* [Admire](http://admire.necst.it/)
* ~~[Drebin](http://user.informatik.uni-goettingen.de/~darp/drebin/)~~



Bounty Programs
----
1. [Android Security Reward Program](https://www.google.com/about/appsecurity/android-rewards/)

How to report
----
1. [Android - reporting security issues](https://source.android.com/security/overview/updates-resources.html#report-issues)

----

# Other Awesome Lists
Other amazingly awesome lists can be found in the
[awesome-awesomeness ★18868](https://github.com/bayandin/awesome-awesomeness) list.

# Contributing
Your contributions are always welcome!


## Backers

Support us with a monthly donation and help us continue our activities. [[Become a backer](https://opencollective.com/android-security-awesome#backer)]

<a href="https://opencollective.com/android-security-awesome/backer/0/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/1/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/2/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/3/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/4/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/5/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/6/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/7/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/8/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/9/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/10/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/11/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/11/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/12/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/12/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/13/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/13/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/14/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/14/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/15/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/15/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/16/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/16/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/17/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/17/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/18/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/18/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/19/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/19/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/20/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/20/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/21/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/21/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/22/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/22/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/23/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/23/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/24/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/24/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/25/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/25/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/26/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/26/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/27/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/27/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/28/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/28/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/29/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/29/avatar.svg"></a>


## Sponsors

Become a sponsor and get your logo on our README on Github with a link to your site. [[Become a sponsor](https://opencollective.com/android-security-awesome#sponsor)]

<a href="https://opencollective.com/android-security-awesome/sponsor/0/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/1/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/2/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/3/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/4/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/5/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/6/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/7/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/8/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/9/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/9/avatar.svg"></a>


---
<p align="center">
	This list is a copy of <a href="https://github.com/ashishb/android-security-awesome">ashishb/android-security-awesome</a> with ranks
</p>
