---
layout: default
title: Awesome Rank for apsdehal/awesome-ctf
---

<p align="center">
	This list is a copy of <a href="https://github.com/apsdehal/awesome-ctf">apsdehal/awesome-ctf</a> with ranks
</p>
---
# Awesome CTF [![Build Status](https://travis-ci.org/apsdehal/awesome-ctf.svg?branch=master)](https://travis-ci.org/apsdehal/awesome-ctf) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★73813](https://github.com/sindresorhus/awesome)

A curated list of [Capture The Flag](https://en.wikipedia.org/wiki/Capture_the_flag#Computer_security) (CTF) frameworks, libraries, resources, softwares and tutorials. This list aims to help starters as well as seasoned CTF players to find everything related to CTFs at one place.

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/apsdehal/ctf-tools/blob/master/CONTRIBUTING.md) first.

#### _If you know a tool that isn't present here, feel free to open a pull request._

### Why?

It takes time to build up collection of tools used in ctf and remember them all. This repo helps to keep all these scattered tools at one place.


### Contents

- [Awesome CTF](#awesome-ctf)
  - [Create](#create)
    - [Forensics](#forensics)
    - [Platforms](#platforms)
    - [Steganography](#steganography)
    - [Web](#web)
  - [Solve](#solve)
    - [Attacks](#attacks)
    - [Bruteforcers](#bruteforcers)
    - [Cryptography](#crypto)
    - [Exploits](#exploits)
    - [Forensics](#forensics-1)
    - [Networking](#networking)
    - [Reversing](#reversing)
    - [Services](#services)
    - [Steganography](#steganography-1)
    - [Web](#web-1)

- [Resources](#resources)
  - [Operating Systems](#operating-systems)
  - [Starter Packs](#starter-packs)
  - [Tutorials](#tutorials)
  - [Wargames](#wargames)
  - [Websites](#websites)
  - [Wikis](#wikis)
  - [Writeups Collections](#writeups-collections)

# Create

*Tools used for creating CTF challenges*

## Forensics

*Tools used for creating Forensics challenges*

- [Dnscat](https://wiki.skullsecurity.org/Dnscat) - Hosts communication through DNS
- [Registry Dumper](http://www.kahusecurity.com/downloads/RegistryDumper_v0.2.7z) - Dump your registry

## Platforms

*Projects that can be used to host a CTF*

- [CTFd](https://github.com/isislab/CTFd) - Platform to host jeopardy style CTFs from ISISLab, NYU Tandon
- [FBCTF ★5184](https://github.com/facebook/fbctf) - Platform to host Capture the Flag competitions from Facebook
- [HackTheArch ★19](https://github.com/mcpa-stlouis/hack-the-arch) - CTF scoring platform
- [Mellivora ★234](https://github.com/Nakiami/mellivora) - A CTF engine written in PHP
- [NightShade ★39](https://github.com/UnrealAkama/NightShade) - A simple security CTF framework
- [OpenCTF ★43](https://github.com/easyctf/openctf) - CTF in a box. Minimal setup required
- [PicoCTF Platform 2 ★87](https://github.com/picoCTF/picoCTF-Platform-2) - A genericized version of picoCTF 2014 that can be easily adapted to host CTF or programming competitions.
- [PyChallFactory ★6](https://github.com/pdautry/py_chall_factory) - Small framework to create/manage/package jeopardy CTF challenges
- [RootTheBox ★232](https://github.com/moloch--/RootTheBox) - A Game of Hackers (CTF Scoreboard & Game Manager)
- [Scorebot ★39](https://github.com/legitbs/scorebot) - Platform for CTFs by Legitbs (Defcon)
- [SecGen ★1263](https://github.com/cliffe/SecGen) - Security Scenario Generator. Creates randomly vulnerable virtual machines


## Steganography

*Tools used to create stego challenges*

Check solve section for steganography.


## Web

*Tools used for creating Web challenges*

*JavaScript Obfustcators*

- [Metasploit JavaScript Obfustcator](https://github.com/rapid7/metasploit-framework/wiki/How-to-obfuscate-JavaScript-in-Metasploit)
- [Uglify](http://marijnhaverbeke.nl//uglifyjs)


# Solve

*Tools used for solving CTF challenges*

## Attacks

*Tools used for performing various kinds of attacks*

- [Bettercap ★2583](https://github.com/evilsocket/bettercap) - Framework to perform MITM (Man in the Middle) attacks.
- [Layer 2 attacks ★172](https://github.com/tomac/yersinia) - Attack various protocols on layer 2

## Crypto

*Tools used for solving Crypto challenges*

- [FeatherDuster ★564](https://github.com/nccgroup/featherduster) - An automated, modular cryptanalysis tool
- [Hash Extender ★361](https://github.com/iagox86/hash_extender) - A utility tool for performing hash length extension attacks
- [PkCrack](https://www.unix-ag.uni-kl.de/~conrad/krypto/pkcrack.html) - A tool for Breaking PkZip-encryption
- [RSACTFTool ★262](https://github.com/Ganapati/RsaCtfTool) - A tool for recovering RSA private key with various attack
- [RSATool ★206](https://github.com/ius/rsatool) - Generate private key with knowledge of p and q
- [XORTool ★508](https://github.com/hellman/xortool) - A tool to analyze multi-byte xor cipher

## Bruteforcers

*Tools used for various kind of bruteforcing (passwords etc.)*

- [Hashcat](https://hashcat.net/hashcat/) - Password Cracker
- [John The Jumbo ★1491](https://github.com/magnumripper/JohnTheRipper) - Community enhanced version of John the Ripper
- [John The Ripper](http://www.openwall.com/john/) - Password Cracker
- [Nozzlr ★19](https://github.com/intrd/nozzlr) - Nozzlr is a bruteforce framework, trully modular and script-friendly.
- [Ophcrack](http://ophcrack.sourceforge.net/) - Windows password cracker based on rainbow tables.
- [Patator ★1068](https://github.com/lanjelot/patator) - Patator is a multi-purpose brute-forcer, with a modular design.

## Exploits

*Tools used for solving Exploits challenges*

- [DLLInjector ★262 ⏳5Y](https://github.com/OpenSecurityResearch/dllinjector) - Inject dlls in processes
- [libformatstr ★226](https://github.com/hellman/libformatstr) - Simplify format string exploitation.
- [Metasploit](http://www.metasploit.com/) - Penetration testing software
- [one_gadget ★311](https://github.com/david942j/one_gadget) -  A tool to find the one gadget `execve('/bin/sh', NULL, NULL)` call
  - `gem install one_gadget`
- [Pwntools ★3445](https://github.com/Gallopsled/pwntools) - CTF Framework for writing exploits
- [Qira ★1594](https://github.com/BinaryAnalysisPlatform/qira) - QEMU Interactive Runtime Analyser
- [ROP Gadget ★1287](https://github.com/JonathanSalwan/ROPgadget) - Framework for ROP exploitation
- [V0lt ★229](https://github.com/P1kachu/v0lt) - Security CTF Toolkit

## Forensics

*Tools used for solving Forensics challenges*

- [Aircrack-Ng](http://www.aircrack-ng.org/) - Crack 802.11 WEP and WPA-PSK keys
  - `apt-get install aircrack-ng`
- [Audacity](http://sourceforge.net/projects/audacity/) - Analyze sound files (mp3, m4a, whatever)
  - `apt-get install audacity`
- [Bkhive and Samdump2](http://sourceforge.net/projects/ophcrack/files/samdump2/) - Dump SYSTEM and SAM files
  - `apt-get install samdump2 bkhive`
- [CFF Explorer](http://www.ntcore.com/exsuite.php) - PE Editor
- [Creddump ★68](https://github.com/moyix/creddump) - Dump windows credentials
- [DVCS Ripper ★629](https://github.com/kost/dvcs-ripper) - Rips web accessible (distributed) version control systems
- [Exif Tool](http://www.sno.phy.queensu.ca/~phil/exiftool/) - Read, write and edit file metadata
- [Extundelete](http://extundelete.sourceforge.net/) - Used for recovering lost data from mountable images
- [Fibratus ★399](https://github.com/rabbitstack/fibratus) - Tool for exploration and tracing of the Windows kernel
- [Foremost](http://foremost.sourceforge.net/) - Extract particular kind of files using headers
  - `apt-get install foremost`
- [Fsck.ext4](http://linux.die.net/man/8/fsck.ext3) - Used to fix corrupt filesystems
- [Malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool
- [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - Network Forensic Analysis Tool
- [PDF Streams Inflater](http://malzilla.sourceforge.net/downloads.html) - Find and extract zlib files compressed in PDF files
- [ResourcesExtract](http://www.nirsoft.net/utils/resources_extract.html) - Extract various filetypes from exes
- [Shellbags ★65 ⏳1Y](https://github.com/williballenthin/shellbags) - Investigate NT\_USER.dat files
- [UsbForensics](http://www.forensicswiki.org/wiki/USB_History_Viewing) - Contains many tools for usb forensics
- [Volatility ★1930](https://github.com/volatilityfoundation/volatility) - To investigate memory dumps


*Registry Viewers*
- [RegistryViewer](http://www.gaijin.at/en/getitpage.php?id=regview) - Used to view windows registries
- [Windows Registry Viewers](http://www.forensicswiki.org/wiki/Windows_Registry) - More registry viewers


## Networking

*Tools used for solving Networking challenges*

- [Bro](https://www.bro.org/) - An open-source network security monitor.
- [Masscan ★7340](https://github.com/robertdavidgraham/masscan) - Mass IP port scanner, TCP port scanner.
- [Monit](https://linoxide.com/monitoring-2/monit-linux/) - A linux tool to check a host on the network (and other non-network activities). 
- [Nipe ★251](https://github.com/GouveaHeitor/nipe) - Nipe is a script to make Tor Network your default gateway.
- [Nmap](https://nmap.org/) - An open source utility for network discovery and security auditing.
- [Wireshark](https://www.wireshark.org/) - Analyze the network dumps.
  - `apt-get install wireshark`
- [Zmap](https://zmap.io/) - An open-source network scanner.


## Reversing

*Tools used for solving Reversing challenges*

- [Androguard ★1815](https://github.com/androguard/androguard) - Reverse engineer Android applications
- [Angr ★2130](https://github.com/angr/angr) - platform-agnostic binary analysis framework
- [Apk2Gold ★489 ⏳1Y](https://github.com/lxdvs/apk2gold) - Yet another Android decompiler
- [ApkTool](http://ibotpeaches.github.io/Apktool/) - Android Decompiler
- [Barf ★949](https://github.com/programa-stic/barf-project) - Binary Analysis and Reverse engineering Framework
- [Binary Ninja](https://binary.ninja/) - Binary analysis framework
- [BinUtils](http://www.gnu.org/software/binutils/binutils.html) - Collection of binary tools
- [BinWalk](https://github.com/devttys0/binwalk) - Analyze, reverse engineer, and extract firmware images.
- [Boomerang ★90 ⏳1Y](https://github.com/nemerle/boomerang) - Decompile x86 binaries to C
- [ctf_import](https://github.com/docileninja/ctf_import) – run basic functions from stripped binaries cross platform
- [GDB](https://www.gnu.org/software/gdb/) - The GNU project debugger
- [GEF ★1263](https://github.com/hugsy/gef) - GDB plugin
- [Hopper](http://www.hopperapp.com/) - Reverse engineering tool (disassembler) for OSX and Linux
- [IDA Pro](https://www.hex-rays.com/products/ida/) - Most used Reversing software
- [Jadx ★13556](https://github.com/skylot/jadx) - Decompile Android files
- [Java Decompilers](http://www.javadecompilers.com) - An online decompiler for Java and Android APKs
- [Krakatau ★795](https://github.com/Storyyeller/Krakatau) - Java decompiler and disassembler
- [PEDA ★2266](https://github.com/longld/peda) - GDB plugin (only python2.7)
- [Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool) A dynamic binary instrumentaion tool by Intel
- [Plasma](https://github.com/joelpx/plasma) - An interactive disassembler for x86/ARM/MIPS which can generate indented pseudo-code with colored syntax.
- [Pwndbg ★1024](https://github.com/pwndbg/pwndbg) - A GDB plugin that provides a suite of utilities to hack around GDB easily. 
- [radare2 ★6396](https://github.com/radare/radare2) - A portable reversing framework
- [Uncompyle ★339](https://github.com/gstarnberger/uncompyle) - Decompile Python 2.7 binaries (.pyc)
- [WinDbg](http://www.windbg.org/) - Windows debugger distributed by Microsoft
- [Xocopy](http://reverse.lostrealm.com/tools/xocopy.html) - Program that can copy executables with execute, but no read permission
- [Z3 ★2704](https://github.com/Z3Prover/z3) - a theorem prover from Microsoft Research

*JavaScript Deobfustcators*

- [Detox](http://relentless-coding.org/projects/jsdetox/install) - A Javascript malware analysis tool
- [Revelo](http://www.kahusecurity.com/tools/Revelo_v0.6.zip) - Analyze obfuscated Javascript code

*SWF Analyzers*
- [RABCDAsm ★296 ⏳1Y](https://github.com/CyberShadow/RABCDAsm) - Collection of utilities including an ActionScript 3 assembler/disassembler.
- [Swftools](http://www.swftools.org/) - Collection of utilities to work with SWF files
- [Xxxswf](https://bitbucket.org/Alexander_Hanel/xxxswf) -  A Python script for analyzing Flash files.

## Services

*Various kind of useful services available around the internet*

- [CSWSH](http://ironwasp.org/cswsh.html) - Cross-Site WebSocket Hijacking Tester
- [Request Bin](http://requestb.in/) - Lets you inspect http requests to a particular url

## Steganography

*Tools used for solving Steganography challenges*

- [Convert](http://www.imagemagick.org/script/convert.php) - Convert images b/w formats and apply filters
- [Exif](http://manpages.ubuntu.com/manpages/trusty/man1/exif.1.html) - Shows EXIF information in JPEG files
- [Exiftool](https://linux.die.net/man/1/exiftool) - Read and write meta information in files
- [Exiv2](http://www.exiv2.org/manpage.html) - Image metadata manipulation tool
- [ImageMagick](http://www.imagemagick.org/script/index.php) - Tool for manipulating images
- [Outguess](https://www.freebsd.org/cgi/man.cgi?query=outguess+&apropos=0&sektion=0&manpath=FreeBSD+Ports+5.1-RELEASE&format=html) - Universal steganographic tool
- [Pngtools](http://www.stillhq.com/pngtools/) - For various analysis related to PNGs
  - `apt-get install pngtools`
- [SmartDeblur ★1549](https://github.com/Y-Vladimir/SmartDeblur) - Used to deblur and fix defocused images
- [Steganabara](https://www.openhub.net/p/steganabara) -  Tool for stegano analysis written in Java
- [Stegbreak](https://linux.die.net/man/1/stegbreak) - Launches brute-force dictionary attacks on JPG image
- [Steghide](http://steghide.sourceforge.net/) - Hide data in various kind of images
- [Stegsolve](http://www.caesum.com/handbook/Stegsolve.jar) - Apply various steganography techniques to images

## Web

*Tools used for solving Web challenges*

- [BurpSuite]() - A graphical tool to testing website security. 
- [Commix ★1416](https://github.com/commixproject/commix) - Automated All-in-One OS Command Injection and Exploitation Tool.
- [Hackbar](https://addons.mozilla.org/en-US/firefox/addon/hackbar/) - Firefox addon for easy web exploitation
- [OWASP ZAP](https://www.owasp.org/index.php/Projects/OWASP_Zed_Attack_Proxy_Project) - Intercepting proxy to replay, debug, and fuzz HTTP requests and responses
- [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) - Add on for chrome for debugging network requests
- [SQLMap ★10327](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tooli
- [W3af ★1778](https://github.com/andresriancho/w3af) -  Web Application Attack and Audit Framework.
- [XSSer](http://xsser.sourceforge.net/) - Automated XSS testor


# Resources

*Where to discover about CTF*

## Operating Systems

*Penetration testing and security lab Operating Systems*

- [BackBox](https://backbox.org/) - Based on Ubuntu
- [BlackArch Linux](https://blackarch.org/) - Based on Arch Linux
- [Fedora Security Lab](https://labs.fedoraproject.org/security/) - Based on Fedora
- [Kali Linux](https://www.kali.org/) - Based on Debian
- [Parrot Security OS](https://www.parrotsec.org/) - Based on Debian
- [Pentoo](http://www.pentoo.ch/) - Based on Gentoo
- [URIX OS](http://urix.us/) - Based on openSUSE
- [Wifislax](http://www.wifislax.com/) - Based on Slackware

*Malware analysts and reverse-engineering*

- [REMnux](https://remnux.org/) - Based on Debian

## Starter Packs

*Collections of installer scripts, useful tools*

- [CTF Tools ★2339](https://github.com/zardus/ctf-tools) - Collection of setup scripts to install various security research tools.
- [LazyKali ★16 ⏳1Y](https://github.com/jlevitsk/lazykali) - A 2016 refresh of LazyKali which simplifies install of tools and configuration.

## Tutorials

*Tutorials to learn how to play CTFs*

- [CTF Field Guide](https://trailofbits.github.io/ctf/) - Field Guide by Trails of Bits
- [CTF Resources](http://ctfs.github.io/resources/) -  Start Guide maintained by community
- [Damn Vulnerable Web Application](http://www.dvwa.co.uk/) PHP/MySQL web application that is damn vulnerable
- [How to Get Started in CTF](https://www.endgame.com/blog/how-get-started-ctf) - Short guideline for CTF beginners by Endgame
- [MIPT CTF ★128](https://github.com/xairy/mipt-ctf) - A small course for beginners in CTFs (in Russian)

## Wargames

*Always online CTFs*

- [Backdoor](https://backdoor.sdslabs.co/) - Security Platform by SDSLabs.
- [Ctfs.me](http://ctfs.me) - CTF All the time
- [Exploit Exercises](https://exploit-exercises.com/) - Variety of VMs to learn variety of computer security issues.
- [Gracker](http://gracker.org) - Binary challenges having a slow learning curve, and write-ups for each level.
- [Hack The Box](https://www.hackthebox.eu) - Weekly CTFs for all types of security enthusiasts.
- [Hack This Site](https://www.hackthissite.org/) - Training ground for hackers.
- [IO](http://io.netgarage.org/) - Wargame for binary challenges.
- [Over The Wire](http://overthewire.org/wargames/) - Wargame maintained by OvertheWire Community
- [Pwnable.kr](http://pwnable.kr/) - Pwn Game
- [Ringzer0Team](https://ringzer0team.com/) - Ringzer0 Team Online CTF
- [ROP Wargames](https://game.rop.sh/) - ROP Wargames
- [SmashTheStack](http://smashthestack.org/) - A variety of wargames maintained by the SmashTheStack Community.
- [VulnHub](https://www.vulnhub.com/) - VM-based for practical in digital security, computer application & network administration.
- [W3Challs](https://w3challs.com) - A penetration testing training platform, which offers various computer challenges, in various categories.
- [WebHacking](http://webhacking.kr) - Hacking challenges for web.
- [WeChall](https://www.wechall.net/) - Always online challenge site.
- [WTHack OnlineCTF](https://onlinectf.com) - CTF Practice platform for every level of cyber security enthusiasts. 

*Self-hosted CTFs*

- [Juice Shop CTF ★45](https://github.com/bkimminich/juice-shop-ctf) - Scripts and tools for hosting a CTF on [OWASP Juice Shop](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project) easily.

## Websites

*Various general websites about and on ctf*

- [CTF Time](https://ctftime.org/) - General information on CTF occuring around the worlds
- [Reddit Security CTF](http://www.reddit.com/r/securityctf) - Reddit CTF category

## Wikis

*Various Wikis available for learning about CTFs*

- [Bamboofox](https://bamboofox.torchpad.com/) - Chinese resources to learn CTF
- [ISIS Lab](https://github.com/isislab/Project-Ideas/wiki) - CTF Wiki by Isis lab
- [OpenToAll](http://wiki.opentoallctf.com/) - Open To All Knowledge Base

## Writeups Collections

*Collections of CTF write-ups*

- [Captf](http://captf.com/) - Dumped CTF challenges and materials by psifertex
- [CTF write-ups (community)](https://github.com/ctfs/) - CTF challenges + write-ups archive maintained by the community
- [CTFTime Scrapper ★9](https://github.com/abdilahrf/CTFWriteupScrapper) - Scraps all writeup from ctf time and organize which to read first
- [pwntools writeups ★235 ⏳1Y](https://github.com/Gallopsled/pwntools-write-ups) - A collection of CTF write-ups all using pwntools
- [Shell Storm](shell-storm.org/repo/CTF/) - CTF challenge archive maintained by Jonathan Salwan
- [Smoke Leet Everyday ★125](https://github.com/smokeleeteveryday/CTF_WRITEUPS) - CTF write-ups repo maintained by SmokeLeetEveryday team.


### LICENSE

CC0 :)
---
<p align="center">
	This list is a copy of <a href="https://github.com/apsdehal/awesome-ctf">apsdehal/awesome-ctf</a> with ranks
</p>
