<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="http://github.com/qazbnm456/awesome-web-security">qazbnm456/awesome-web-security</a> with ranks
</p>
---
# Awesome Web Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)

[<img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" align="right" width="70">](https://www.w3.org/TR/html5/)

> 🐶 Curated list of Web Security materials and resources.

Needless to say, most of websites on-line are suffered from various type of bugs, which might eventually lead to vulnerabilities. Why would this happen so often? Many factors can be involved, including misconfiguration, shortage of engineers' security skills, and etc. Therefore, here is the curated list of Web Security materials and resources for learning the cutting edge penetrating techniques.

*Please read the [contribution guidelines](https://github.com/qazbnm456/awesome-web-security/blob/master/CONTRIBUTING.md) before contributing.*

---

<p align="center"><b>🌈 Want to strengthen your penetration skills?</b><br>I would recommend to play some <a href="https://github.com/apsdehal/awesome-ctf" target="_blank">awesome-ctf</a>s.</p>

---

Check out my [repos](https://github.com/qazbnm456) 🐾 or say *hi* on my [Twitter](https://twitter.com/qazbnm456).

## Contents

- [Forums](#forums)
- [Resources](#resources)
    - [Introductions](#introductions)
        - [XSS](#introductions-xss)
        - [SQL Injection](#introductions-sql-injection)
        - [XML](#introductions-xml)
        - [XXE](introductions-xxe)
        - [CSRF](#introductions-csrf)
        - [SSRF](#introductions-ssrf)
        - [Rails](#introductions-rails)
        - [AngularJS](#introductions-angularjs)
        - [SSL/TLS](#introductions-ssl-tls)
        - [Webmail](#introductions-webmail)
        - [AWS](#introductions-aws)
        - [Fingerprint](#introductions-fingerprint)
    - [Books](#books)
- [Evasions](#evasions)
	- [CSP](#evasions-csp)
    - [WAF](#evasions-waf)
    - [JSMVC](#evasions-jsmvc)
    - [Authentication](#evasions-authentication)
- [Tricks](#tricks)
    - [Remote Code Execution](#tricks-rce)
    - [XSS](#tricks-xss)
    - [SQL Injection](#tricks-sql-injection)
    - [SSRF](#tricks-ssrf)
    - [Header Injection](#tricks-header-injection)
    - [URL](#tricks-url)
    - [Others](#tricks-others)
- [Browser Exploitation](#browser-exploitation)
- [PoCs](#pocs)
    - [JavaScript](#pocs-javascript)
- [Tools](#tools)
    - [Reconnaissance](#tools-reconnaissance)
    - [Code Generating](#tools-code-generating)
    - [Fuzzing](#tools-fuzzing)
    - [Penetrating](#tools-penetrating)
    - [Leaking](#tools-leaking)
    - [Detecting](#tools-detecting)
    - [Preventing](#tools-preventing)
    - [Webshell](#tools-webshell)
    - [Disassembler](#tools-disassembler)
    - [Others](#tools-others)
- [Social Engineering Database](#social-engineering-database)
- [Blogs](#blogs)
- [Twitter Users](#twitter-users)
- [Practices](#practices)
    - [AWS](#practices-aws)
    - [XSS](#practices-xss)
- [Community](#community)
- [Miscellaneous](#miscellaneous)

## Forums

* [Drops (backup)](https://drops.secquan.org/) - Drops was known as a famous knowledge base for hacking technology.
* [Paper from Seebug](http://paper.seebug.org/) - Knowledge base for hacking technology built by [Seebug](http://seebug.org/).
* [Freebuf](http://www.freebuf.com/) - Freebuf is the most popular forum in China for exchanging and sharing hacking technology.
* [安全脉搏](https://www.secpulse.com/) - Blog for Security things.

## Resources

### Introductions

<a name="introductions-xss"></a>
### XSS

* [H5SC ★1566](https://github.com/cure53/H5SC) - HTML5 Security Cheatsheet - Collection of HTML5 related XSS attack vectors by [@cure53](https://github.com/cure53).
* [XSS.png ★181 ⏳1Y](https://github.com/jackmasa/XSS.png) - XSS mind map by [@jackmasa](https://github.com/jackmasa).
* [C.XSS Guide](https://excess-xss.com/) - Comprehensive tutorial on cross-site scripting by [@JakobKallin](https://github.com/JakobKallin) and [Irene Lobo Valbuena](https://www.linkedin.com/in/irenelobovalbuena/).

<a name="introductions-sql-injection"></a>
### SQL Injection

* [HQL for pentesters](http://blog.h3xstream.com/2014/02/hql-for-pentesters.html) - Written by [@h3xstream](https://twitter.com/h3xstream/).

<a name="introductions-xml"></a>
### XML

* [XML实体攻击 - 从内网探测到命令执行步步惊心](http://www.freebuf.com/video/49961.html) - Written by 张天琪.

<a name="introductions-xxe"></a>
### XXE

* [XXE](https://phonexicum.github.io/infosec/xxe.html) - Written by [@phonexicum](https://twitter.com/phonexicum).

<a name="introductions-csrf"></a>
### CSRF

* [讓我們來談談 CSRF](http://blog.techbridge.cc/2017/02/25/csrf-introduction/) - Written by [TechBridge](http://blog.techbridge.cc/).

<a name="introductions-ssrf"></a>
### SSRF

* [SSRF bible. Cheatsheet](https://docs.google.com/document/d/1v1TkWZtrhzRLy0bYXBcdLUedXGb9njTNIJXa3u9akHM/edit) - Written by [@Wallarm](https://twitter.com/wallarm).

<a name="introductions-rails"></a>
### Rails

* [Rails 動態樣板路徑的風險](http://devco.re/blog/2015/07/24/the-vulnerability-of-dynamic-render-paths-in-rails/) - Written by [Shaolin](http://devco.re/blog/author/shaolin/).
* [Rails Security](http://php.ph/wydrops/drops/Rails%20Security%20(%E4%B8%8A).pdf) - Written by [@qazbnm456](https://github.com/qazbnm456).

<a name="introductions-angularjs"></a>
### AngularJS

* [XSS without HTML: Client-Side Template Injection with AngularJS](http://blog.portswigger.net/2016/01/xss-without-html-client-side-template.html) - Written by [Gareth Heyes](https://www.blogger.com/profile/10856178524811553475).
* [DOM based Angular sandbox escapes](http://blog.portswigger.net/2017/05/dom-based-angularjs-sandbox-escapes.html) - Written by [@garethheyes](https://twitter.com/garethheyes)

<a name="introductions-ssl-tls"></a>
### SSL/TLS

* [SSL & TLS Penetration Testing](https://www.aptive.co.uk/blog/tls-ssl-security-testing/) - Written by [APTIVE](https://www.aptive.co.uk/).

<a name="introductions-webmail"></a>
### Webmail

* [Webmail-Hacking](https://github.com/mottoin/SecPaper/blob/master/Webmail-Hacking.pdf) - Written by [千域千寻](http://blog.csdn.net/f1n4lly/).

<a name="introductions-aws"></a>
### AWS

* [PENETRATION TESTING AWS STORAGE: KICKING THE S3 BUCKET](https://rhinosecuritylabs.com/penetration-testing/penetration-testing-aws-storage/) - Written by Dwight Hohnstein from [Rhino Security Labs](https://rhinosecuritylabs.com/).

<a name="introductions-fingerprint"></a>
### Fingerprint

* [浅谈Web客户端追踪](http://www.freebuf.com/articles/web/127266.html) - Written by [arkteam](http://www.freebuf.com/author/arkteam).

### Books

* [Security Geek 2016 - Part. A](http://bobao.360.cn/download/book/security-geek-2016-A.pdf) - Written by [360网络攻防实验室](http://bobao.360.cn/).
* [Security Geek 2016 - Part. B](http://bobao.360.cn/download/book/security-geek-2016-B.pdf) - Written by [360网络攻防实验室](http://bobao.360.cn/).

## Evasions

<a name="evasions-csp"></a>
### CSP

* [CSP: bypassing form-action with reflected XSS](https://labs.detectify.com/2016/04/04/csp-bypassing-form-action-with-reflected-xss/) - Written by [Detectify Labs](https://labs.detectify.com/).
* [TWITTER XSS + CSP BYPASS](http://www.paulosyibelo.com/2017/05/twitter-xss-csp-bypass.html) - Written by [Paulos Yibelo](http://www.paulosyibelo.com/).

<a name="evasions-waf"></a>
### WAF

* [浅谈json参数解析对waf绕过的影响](https://xianzhi.aliyun.com/forum/read/553.html) - Written by [doggy](https://xianzhi.aliyun.com/forum/u.php?uid=1723895737531437).
* [Airbnb – When Bypassing JSON Encoding, XSS Filter, WAF, CSP, and Auditor turns into Eight Vulnerabilities](https://buer.haus/2017/03/08/airbnb-when-bypassing-json-encoding-xss-filter-waf-csp-and-auditor-turns-into-eight-vulnerabilities/) - Written by [@Brett Buerhaus](https://twitter.com/bbuerhaus).
* [How to bypass libinjection in many WAF/NGWAF](https://medium.com/@d0znpp/how-to-bypass-libinjection-in-many-waf-ngwaf-1e2513453c0f)

<a name="evasions-jsmvc"></a>
### JSMVC

* [JavaScript MVC and Templating Frameworks](http://www.slideshare.net/x00mario/jsmvcomfg-to-sternly-look-at-javascript-mvc-and-templating-frameworks) - Written by [Mario Heiderich](http://www.slideshare.net/x00mario).

<a name="evasions-authentication"></a>
### Authentication

* [Trend Micro Threat Discovery Appliance - Session Generation Authentication Bypass (CVE-2016-8584)](http://blog.malerisch.net/2017/04/trend-micro-threat-discovery-appliance-session-generation-authentication-bypass-cve-2016-8584.html) - Written by [@malerisch](https://twitter.com/malerisch) and [@steventseeley](https://twitter.com/steventseeley).
* [Yahoo Bug Bounty: Chaining 3 Minor Issues To Takeover Flickr Accounts](http://blog.mish.re/index.php/2017/04/29/yahoo-bug-bounty-chaining-3-minor-issues-to-takeover-flickr-accounts/) - Written by [Mishre](http://blog.mish.re/).

## Tricks

<a name="tricks-rce"></a>
### Remote Code Execution

* [Exploiting Node.js deserialization bug for Remote Code Execution](https://opsecx.com/index.php/2017/02/08/exploiting-node-js-deserialization-bug-for-remote-code-execution/) - Written by [OpSecX](https://opsecx.com/index.php/author/ajinabraham/).
* [eval长度限制绕过 && PHP5.6新特性](https://www.leavesongs.com/PHP/bypass-eval-length-restrict.html) - Written by [PHITHON](https://www.leavesongs.com/).
* [PHP垃圾回收机制UAF漏洞分析](http://www.freebuf.com/vuls/122938.html) - Written by [ph1re](http://www.freebuf.com/author/ph1re).
* [DRUPAL 7.X SERVICES MODULE UNSERIALIZE() TO RCE](https://www.ambionics.io/blog/drupal-services-module-rce) - Written by [Ambionics Security](https://www.ambionics.io/).
* [How we exploited a remote code execution vulnerability in math.js](https://capacitorset.github.io/mathjs/) - Written by [@capacitorset](https://github.com/capacitorset).
* [GitHub Enterprise Remote Code Execution](http://exablue.de/blog/2017-03-15-github-enterprise-remote-code-execution.html) - Written by [@iblue](https://github.com/iblue).

<a name="tricks-xss"></a>
### XSS

* [ECMAScript 6 from an Attacker's Perspective - Breaking Frameworks, Sandboxes, and everything else](http://www.slideshare.net/x00mario/es6-en) - Written by [Mario Heiderich](http://www.slideshare.net/x00mario).
* [How I found a $5,000 Google Maps XSS (by fiddling with Protobuf)
](https://medium.com/@marin_m/how-i-found-a-5-000-google-maps-xss-by-fiddling-with-protobuf-963ee0d9caff#.u50nrzhas) - Written by [Marin Moulinier](https://medium.com/@marin_m).

<a name="tricks-sql-injection"></a>
### SQL Injection

* [屌智硬之mysql不用逗号注入](http://www.jinglingshu.org/?p=2220) - Written by [jinglingshu](http://www.jinglingshu.org/?p=2220).
* [见招拆招：绕过WAF继续SQL注入常用方法](http://www.freebuf.com/articles/web/36683.html) - Written by [mikey](http://www.freebuf.com/author/mikey).
* [MySQL Error Based SQL  Injection Using  EXP](https://www.exploit-db.com/docs/37953.pdf) - Written by [@osandamalith](https://twitter.com/osandamalith).
* [SQL injection in an UPDATE query - a bug bounty story!](http://zombiehelp54.blogspot.jp/2017/02/sql-injection-in-update-query-bug.html) - Written by [Zombiehelp54](http://zombiehelp54.blogspot.jp/).
* [GitHub Enterprise SQL Injection](http://blog.orange.tw/2017/01/bug-bounty-github-enterprise-sql-injection.html) - Written by [Orange](http://blog.orange.tw/).

<a name="tricks-ssrf"></a>
### SSRF

* [SSRF in https://imgur.com/vidgif/url](https://hackerone.com/reports/115748) - Written by [aesteral](https://hackerone.com/aesteral).
* [SSRF漏洞中绕过IP限制的几种方法总结](http://www.freebuf.com/articles/web/135342.html) - Written by [arkteam](http://www.freebuf.com/author/arkteam).

<a name="tricks-header-injection"></a>
### Header Injection

* [Java/Python FTP Injections Allow for Firewall Bypass](http://blog.blindspotsecurity.com/2017/02/advisory-javapython-ftp-injections.html) - Written by [Timothy Morgan](https://plus.google.com/105917618099766831589).

<a name="tricks-url"></a>
### URL

* [URL Hacking - 前端猥琐流](http://php.ph/wydrops/drops/URL%20Hacking%20-%20前端猥琐流.pdf) - Written by [0x_Jin](http://xssec.lofter.com/).
* [Phishing with Unicode Domains](https://www.xudongz.com/blog/2017/idn-phishing/) - Written by [Xudong Zheng](https://www.xudongz.com/).
* [Unicode Domains are bad and you should feel bad for supporting them](https://www.vgrsec.com/post20170219.html) - Written by [VRGSEC](https://www.vgrsec.com/).

<a name="tricks-others"></a>
### Others

* [Some Tricks From My Secret Group](https://www.leavesongs.com/SHARE/some-tricks-from-my-secret-group.html) - Written by [PHITHON](https://www.leavesongs.com/).
* [CTF比赛总是输？你还差点Tricks!](https://docs.google.com/presentation/d/1Cx0vI2Mzy0zwdTrgic3S3TwGMCpH-QhMUdHU1r3AYfI/edit#slide=id.g35f391192_065) - Written by [PHITHON](https://www.leavesongs.com/).
* [隱匿的攻擊之-Domain Fronting](https://evi1cg.me/archives/Domain_Fronting.html) - Written by [Evi1cg](https://evi1cg.me/).

## Browser Exploitation

* [First Step to Browser Exploitation](http://mashirogod.dothome.co.kr/index.php/2017/01/07/first-step-to-browser-exploitation/) - Written by [Brian Pak](http://mashirogod.dothome.co.kr/).
* [JSON hijacking for the modern web](http://blog.portswigger.net/2016/11/json-hijacking-for-modern-web.html) - Written by [portswigger](https://portswigger.net/).
* [IE11 Information disclosure - local file detection](https://www.facebook.com/ExploitWareLabs/photos/a.361854183878462.84544.338832389513975/1378579648872572/?type=3&theater) - Written by James Lee.
* [Attacking JavaScript Engines - A case study of JavaScriptCore and CVE-2016-4622](http://www.phrack.org/papers/attacking_javascript_engines.html) - Written by [phrack@saelo.net](phrack@saelo.net).
* [SOP bypass / UXSS – Stealing Credentials Pretty Fast (Edge)](https://www.brokenbrowser.com/sop-bypass-uxss-stealing-credentials-pretty-fast/) - Written by [Manuel](https://twitter.com/magicmac2000).
* [Three roads lead to Rome](http://blogs.360.cn/360safe/2016/11/29/three-roads-lead-to-rome-2/) - Written by [Luke Viruswalker](http://blogs.360.cn/360safe/author/xsecure/).
* [Exploiting a V8 OOB write.](https://halbecaf.com/2017/05/24/exploiting-a-v8-oob-write/) - Written by [@halbecaf](https://twitter.com/halbecaf).
* [FROM CRASH TO EXPLOIT: CVE-2015-6086 – OUT OF BOUND READ/ASLR BYPASS](http://payatu.com/from-crash-to-exploit/) - Written by [payatu](http://payatu.com/).

## PoCs

<a name="pocs-javascript"></a>
### JavaScript

* [js-vuln-db ★844](https://github.com/tunz/js-vuln-db) - Collection of JavaScript engine CVEs with PoCs by [@tunz](https://github.com/tunz).
* [awesome-cve-poc ★339](https://github.com/qazbnm456/awesome-cve-poc) - Curated list of CVE PoCs by [@qazbnm456](https://github.com/qazbnm456).
* [Some-PoC-oR-ExP ★359](https://github.com/coffeehb/Some-PoC-oR-ExP) - 各种漏洞poc、Exp的收集或编写 by [@coffeehb](https://github.com/coffeehb).

## Tools

<a name="tools-reconnaissance"></a>
### Reconnaissance

* [Censys](https://censys.io/) - Censys is a search engine that allows computer scientists to ask questions about the devices and networks that compose the Internet by [University of Michigan](https://umich.edu/).
* [urlscan.io](https://urlscan.io/) - Service which analyses websites and the resources they request by [@heipei](https://twitter.com/heipei).
* [Certificate Transparency ★416](https://github.com/google/certificate-transparency) - Google's Certificate Transparency project fixes several structural flaws in the SSL certificate system by [@google](https://github.com/google).

<a name="tools-code-generating"></a>
### Code Generating

* [VWGen ★35](https://github.com/qazbnm456/lulumi-browser) - Vulnerable Web applications Generator by [@qazbnm456](https://github.com/qazbnm456).

<a name="tools-fuzzing"></a>
### Fuzzing

* [wfuzz ★689](https://github.com/xmendez/wfuzz) - Web application bruteforcer by [@xmendez](https://github.com/xmendez).
* [charsetinspect ★15](https://github.com/hack-all-the-things/charsetinspect) - Script that inspects multi-byte character sets looking for characters with specific user-defined properties by [@hack-all-the-things](https://github.com/hack-all-the-things).
* [IPObfuscator ★50](https://github.com/OsandaMalith/IPObfuscator) - Simple too to convert the IP to a DWORD IP by [@OsandaMalith](https://github.com/OsandaMalith).
* [wpscan ★2473](https://github.com/wpscanteam/wpscan) - WPScan is a black box WordPress vulnerability scanner by [@wpscanteam](https://github.com/wpscanteam).
* [JoomlaScan ★57](https://github.com/drego85/JoomlaScan) - Free software to find the components installed in Joomla CMS, built out of the ashes of Joomscan by [@drego85](https://github.com/drego85).

<a name="tools-penetrating"></a>
### Penetrating

* [Burp Suite](https://portswigger.net/burp/) - Burp Suite is an integrated platform for performing security testing of web applications by [portswigger](https://portswigger.net/).
* [mitmproxy ★7819](https://github.com/mitmproxy/mitmproxy) - Interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers by [@mitmproxy](https://github.com/mitmproxy).

<a name="tools-leaking"></a>
### Leaking

* [HTTPLeaks ★597](https://github.com/cure53/HTTPLeaks) - All possible ways, a website can leak HTTP requests by [@cure53](https://github.com/cure53).
* [dvcs-ripper ★485](https://github.com/kost/dvcs-ripper) - Rip web accessible (distributed) version control systems: SVN/GIT/HG... by [@kost](https://github.com/kost).
* [DVCS-Pillage ★169](https://github.com/evilpacket/DVCS-Pillage) - Pillage web accessible GIT, HG and BZR repositories by [@evilpacket](https://github.com/evilpacket).

<a name="tools-detecting"></a>
### Detecting

* [sqlchop ★196](https://github.com/chaitin/sqlchop) - [DEPRECATED] Novel SQL injection detection engine built on top of SQL tokenizing and syntax analysis by [chaitin](http://chaitin.com).
* [retire.js ★1200](https://github.com/RetireJS/retire.js) - Scanner detecting the use of JavaScript libraries with known vulnerabilities by [@RetireJS](https://github.com/RetireJS).
* [malware-jail ★174](https://github.com/HynekPetrak/malware-jail) - Sandbox for semi-automatic Javascript malware analysis, deobfuscation and payload extraction by [@HynekPetrak](https://github.com/HynekPetrak).

<a name="tools-preventing"></a>
### Preventing

* [js-xss ★1409](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist by [@leizongmin](https://github.com/leizongmin).

<a name="tools-webshell"></a>
### Webshell

* [webshell ★1983](https://github.com/tennc/webshell) - This is a webshell open source project by [@tennc](https://github.com/tennc).

<a name="tools-disassembler"></a>
### Disassembler

* [plasma ★2292](https://github.com/plasma-disassembler/plasma) - Plasma is an interactive disassembler for x86/ARM/MIPS by [@plasma-disassembler](https://github.com/plasma-disassembler).
* [radare2 ★4714](https://github.com/radare/radare2) - Unix-like reverse engineering framework and commandline tools by [@radare](https://github.com/radare).
* [Iaitō ★1399](https://github.com/hteso/iaito) - Qt and C++ GUI for radare2 reverse engineering framework by [@hteso](https://github.com/hteso).

<a name="tools-others"></a>
### Others

* [Dnslogger](https://wiki.skullsecurity.org/index.php?title=Dnslogger) - DNS Logger by [@iagox86](https://github.com/iagox86).
* [CyberChef ★2677](https://github.com/gchq/CyberChef) - The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis - by [@GCHQ](https://github.com/gchq).

## Social Engineering Database

**use at your own risk**

* [haveibeenpwned](https://haveibeenpwned.com/) - Check if you have an account that has been compromised in a data breach by [Troy Hunt](https://www.troyhunt.com/).
* [70 SECURITY TEAM Social Engineering Data](http://s.70sec.com/) - 70 SECURITY TEAM 社工库 by [70 Security Team](http://70sec.com/).
* [mysql-password](http://www.mysql-password.com/database/1) - Database of MySQL hashes.

## Blogs

* [Orange](http://blog.orange.tw/) - Taiwan's talented web penetrator.
* [leavesongs](https://www.leavesongs.com/) - China's talented web penetrator.
* [Broken Browser](https://www.brokenbrowser.com/) - Fun with Browser Vulnerabilities.
* [Blog of Osanda](https://osandamalith.com/) - Security Researching and Reverse Engineering.
* [BRETT BUERHAUS](https://buer.haus/) - Vulnerability disclosures and rambles on application security.
* [n0tr00t](https://www.n0tr00t.com/) - ~# n0tr00t Security Team.

## Twitter Users

* [@filedescriptor](https://twitter.com/filedescriptor) - Active penetrator often tweets and writes useful articles
* [@cure53berlin](https://twitter.com/cure53berlin) - [Cure53](https://cure53.de/) is a German cybersecurity firm.
* [@XssPayloads](https://twitter.com/XssPayloads) - The wonderland of JavaScript unexpected usages, and more.
* [@kinugawamasato](https://twitter.com/kinugawamasato) - Japanese web penetrator.
* [@h3xstream](https://twitter.com/h3xstream/) - Security Researcher, interested in web security, crypto, pentest, static analysis but most of all, samy is my hero.
* [@garethheyes](https://twitter.com/garethheyes) - English web penetrator.

## Practices

<a name="practices-aws"></a>
### AWS

* [FLAWS](http://flaws.cloud/) - Amazon AWS CTF challenge - Written by [@0xdabbad00](https://twitter.com/0xdabbad00).

<a name="practices-xss"></a>
### XSS

* [alert(1) to win](https://alf.nu/alert1) - Series of XSS challenges - Written by [@steike](https://twitter.com/steike).
* [prompt(1) to win](http://prompt.ml/) - Complex 16-Level XSS Challenge held in summer 2014 (+4 Hidden Levels) - Written by [@cure53](https://github.com/cure53).

## Community

* [Reddit](https://www.reddit.com/r/websecurity/)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/security)

## Miscellaneous

* [awesome-bug-bounty ★299](https://github.com/djadmin/awesome-bug-bounty) - Comprehensive curated list of available Bug Bounty & Disclosure Programs and write-ups by [@djadmin](https://github.com/djadmin).
* [bug-bounty-reference ★281](https://github.com/ngalongc/bug-bounty-reference) - List of bug bounty write-up that is categorized by the bug nature by [@ngalongc](https://github.com/ngalongc).
* [如何正確的取得使用者 IP ？](http://devco.re/blog/2014/06/19/client-ip-detection/) - Written by [Allen Own](http://devco.re/blog/author/allenown).
* [1000php ★244](https://github.com/Xyntax/1000php) - 1000个PHP代码审计案例(2016.7以前乌云公开漏洞) by [@Xyntax](https://github.com/Xyntax).
* [Brute Forcing Your Facebook Email and Phone Number](http://pwndizzle.blogspot.jp/2014/02/brute-forcing-your-facebook-email-and.html) - Written by [PwnDizzle](http://pwndizzle.blogspot.jp/).
* [GITLEAKS](https://gitleaks.com/) - Search engine for exposed secrets on lots of places.
* [Pentest + Exploit dev Cheatsheet wallpaper](http://i.imgur.com/Mr9pvq9.jpg) - Penetration Testing and Exploit Dev CheatSheet.
* [Hunting for Web Shells](https://www.tenable.com/blog/hunting-for-web-shells) - Written by [Jacob Baines](https://www.tenable.com/profile/jacob-baines).
* [The Definitive Security Data Science and Machine Learning Guide](http://www.covert.io/the-definitive-security-datascience-and-machinelearning-guide/) - Written by JASON TROS.
* [EQGRP ★3136](https://github.com/x0rz/EQGRP) - Decrypted content of eqgrp-auction-file.tar.xz by [@x0rz](https://github.com/x0rz).
* [Browser Extension and Login-Leak Experiment](https://extensions.inrialpes.fr/) - Browser Extension and Login-Leak Experiment.
* [notes ★666](https://github.com/ChALkeR/notes) - Some public notes by [@ChALkeR](https://github.com/ChALkeR).
* [The Art of Subdomain Enumeration](https://blog.sweepatic.com/art-of-subdomain-enumeration/) - Written by [Patrik Hudak](https://blog.sweepatic.com/author/patrik/).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@qazbnm456](https://qazbnm456.github.io/) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="http://github.com/qazbnm456/awesome-web-security">qazbnm456/awesome-web-security</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
