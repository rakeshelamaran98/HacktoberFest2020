##  BugBounty Resources
A comprehensive curated list of Bug Bounty Resources.

## Table of Contents
- [Getting Started](#getting-started)
- [Tools](#tools)
- [Cheat Sheet](#cheat-sheet)
- [Crowdsouces Platforms](#platforms)

### Getting Started
  1 Web Security                                       
    - [Basics](https://www.hacker101.com/sessions/web_in_depth) 
    - [Concepts](https://github.com/vasanthk/web-security-basics)
  
  2 Networking 
    - [Basics](https://www.digitalocean.com/community/tutorials/an-introduction-to-networking-terminology-interfaces-and-protocols)
    - [Concepts](https://null-byte.wonderhowto.com/how-to/networking-basics/)
 
 3 Programming
    - [Bash](https://linuxconfig.org/bash-scripting-tutorial-for-beginners)
    - [Linux](https://www.guru99.com/linux-commands-cheat-sheet.html)
    - [JavaScript](https://www.lynda.com/JavaScript-tutorials/Ethical-Hacking-JavaScript/758646-2.html)
    - [Python](https://analyticsindiamag.com/8-free-resources-to-learn-ethical-hacking-with-python/)
    
### Tools
---
#### _Web Content Scanner_
- [Burp Suite](https://portswigger.net/burp/communitydownload)
- [OWASP ZAP](https://owasp.org/www-project-zap/)
- [DIRB](https://tools.kali.org/web-applications/dirb)
- [Arachni](https://github.com/Arachni/arachni)

#### _Subdomain Enumeration_
- [ASSETFINDER](https://github.com/tomnomnom/assetfinder)
- [DirBuster](https://tools.kali.org/web-applications/dirbuster)
- [GoBuster](https://tools.kali.org/web-applications/gobuster)
- [Sublist3r](https://tools.kali.org/information-gathering/sublist3r)

#### _Information Gathering_
- [inspy](https://tools.kali.org/information-gathering/inspy)
- [MassDNS](https://github.com/blechschmidt/massdns)
- [dnsenum](https://tools.kali.org/information-gathering/dnsenum)
- [Th3inspector](https://github.com/Moham3dRiahi/Th3inspector)
- [URLExtractor](https://github.com/The404Hacking/URLExtractor)
- [BillCipher](https://github.com/GitHackTools/BillCipher)

#### _XSS Attack_
- [XSStrike](https://github.com/s0md3v/XSStrike)
- [XSpear](https://github.com/hahwul/XSpear)
- [dalfox](https://github.com/hahwul/dalfox)
- [domdig](https://github.com/fcavallarin/domdig)
- [ezXSS](https://github.com/ssl/ezXSS)
- [findom-xss](https://github.com/dwisiswant0/findom-xss)
- [xsser](https://github.com/epsylon/xsser)

#### _Injection_
- [NoSQLMap](https://github.com/codingo/NoSQLMap)
- [sqlninja](https://gitlab.com/kalilinux/packages/sqlninja)
- [bbqsql](https://github.com/CiscoCXSecurity/bbqsql)

#### _Git OSINT_
- [GitMiner](https://github.com/UnkL4b/GitMiner)
- [gitGraber](https://github.com/hisxo/gitGraber)
- [github-search](https://github.com/gwen001/github-search)
- [gitleaks](https://github.com/zricethezav/gitleaks)
- [gitrob](https://github.com/michenriksen/gitrob)

#### _HTTP_
- [hetty](https://github.com/dstotijn/hetty)
- [Parameter Discovery](https://github.com/s0md3v/Arjun)
- [httpx](https://github.com/projectdiscovery/httpx)
- [httprobe](https://github.com/tomnomnom/httprobe)
- [wuzz](https://github.com/asciimoo/wuzz)
- [smuggler](https://github.com/defparam/smuggler)

#### _CORS_
- [CorsMe](https://github.com/Shivangx01b/CorsMe)
- [Corsy](https://github.com/s0md3v/Corsy)
- [CORScanner](https://github.com/chenjj/CORScanner)

#### _SSRF_
- [Gopherus](https://github.com/tarunkant/Gopherus)
- [SSRFmap](https://github.com/swisskyrepo/SSRFmap)
- [ssrf-sheriff](https://github.com/teknogeek/ssrf-sheriff)

#### _LFI_
- [kadimus](https://github.com/P0cL4bs/kadimus)
- [LFISuite](https://github.com/D35m0nd142/LFISuite)
- [liffy](https://github.com/mzfr/liffy)
- [LFiFreak](https://github.com/OsandaMalith/LFiFreak)

#### _URL_
- [burl](https://github.com/tomnomnom/burl)
- [gau](https://github.com/lc/gau)
- [urlprobe](https://github.com/1ndianl33t/urlprobe)

#### _Automated_
- [jaeles](https://github.com/jaeles-project/jaeles)
- [rengine](https://github.com/yogeshojha/rengine)
- [Osmedeus](https://github.com/j3ssie/Osmedeus)
- [Sn1per](https://github.com/1N3/Sn1per)

#### _S3 Bucket_
- [S3Scanner](https://github.com/sa7mon/S3Scanner)
- [s3recon](https://github.com/clarketm/s3recon)
- [s3finder](https://github.com/magisterquis/s3finder)
- [CloudStorageFinder](https://github.com/digininja/CloudStorageFinder)

#### Payloads
- [SQL Injection](https://github.com/payloadbox/sql-injection-payload-list)
- [AllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
- [xss-payload-list](https://github.com/payloadbox/xss-payload-list)
- [XSS](https://github.com/pgaijin66/XSS-Payloads/blob/master/payload/payload.txt)
- [XSS_2020](https://github.com/ihebski/XSS-Payloads)
- [Command Injection](https://github.com/payloadbox/command-injection-payload-list)

#### _Open Re-Direct_

- Using CRLF to bypass "javascript" blacklisted keyword
```
       java%0d%0ascript%0d%0a:alert(0)
```
- Using "//" to bypass "http" blacklisted keyword
```
          //example.com
```
- Using "https:" to bypass "//" blacklisted keyword
```
          https:example.com
```
- Using "//" to bypass "//" blacklisted keyword (Browsers see // as //)
```
            \/\/example.com/
            /\/example.com/ 
```
- Using "%E3%80%82" to bypass "." blacklisted character
```
             //example%E3%80%82com
```
- Using null byte "%00" to bypass blacklist filter
```
             //example%00.com
```
- Using "@" character, browser will redirect to anything after the "@"
```
           http://www.theirsite.com@yoursite.com/
```
***
### Cheat Sheet
| CheatSheet                                               | PoC                                               |   
|----------------------------------------------------------|---------------------------------------------------|
| [Mobile- Pentest](https://github.com/tanprathan/MobileApp-Pentest-Cheatsheet) | [XSS](http://www.xsses.com/) |
| [NMap](https://github.com/jasonniebauer/Nmap-Cheatsheet) | hackerone reports                                 |
| [CEH](https://scadahacker.com/library/Documents/Cheat_Sheets/Hacking%20-%20CEH%20Cheat%20Sheet%20Exercises.pdf)|

---
### Platforms
- [HackerOne](https://hackerone.com/)
- [Bugcrowd](https://bugcrowd.com/)
- [YesWeHack](https://yeswehack.com/)
- [intigriti](https://intigriti.com/)
- [Cobalt](https://cobalt.io/)
- [Bountysource](https://www.bountysource.com/)
- [Bounty Factory](https://bountyfactory.io/)
- [Coder Bounty](http://www.coderbounty.com/)
- [FreedomSponsors](https://freedomsponsors.org/)
- [FOSS Factory](http://www.fossfactory.org/)
- [Synack](https://www.synack.com/)
- [HackenProof](https://hackenproof.com/)
- [Detectify](https://cs.detectify.com/)
- [Bugbountyjp](https://bugbounty.jp/)
- [Safehats](https://safehats.com/)
- [BugbountyHQ](https://www.bugbountyhq.com/)
- [Hackerhive](https://hackerhive.io/)
- [Hacktrophy](https://hacktrophy.com/)
- [AntiHACK](https://www.antihack.me/)
