![screenshot](https://scontent.fpku3-1.fna.fbcdn.net/v/t1.0-9/21557750_2042741135953712_5078261438831460254_n.jpg?oh=2f97d6a6bd568345cca1076e5eead7c4&oe=5A5ED863)

# Yuki Chan The Auto Pentest

The Yuki Chan is an Automated Penetration Testing tool this tool will auditing all standard security test method for you.

# WARNING                              
I highly recommend using this tool by using Kali Linux OS By using this tool it means you agree with terms, conditions, and risks   

By using this tool you agree that   

1. use for legitimate security testing                    
2. not for crime                                         
3. the use of this tool solely for educational reasons only   

By using this tool you agree that    

1. You are willing to be charged with criminal or state law applicable by law enforcement officers and government when abused                             
2. the risk is borne by yourself    

Thank you and happy pentest                                                             

# Change Log
- Version 1.0
> Very First Release

# Feature
- Automated 
- Intel-Gathering
- Vulnerability Analysis
- Security Auditing
- OSINT
- Tracking
- System Enumeration
- Fuzzing
- CMS Auditing
- SSL Security Auditing
- And Off Course This Tool Designed For Targetted Pentesting Too

# Modules In Yuki Chan
- Whois domain analyzer
- Nslookup
- Nmap
- TheHarvester
- Metagoofil
- DNSRecon
- Sublist3r
- Wafw00f
- WAFNinja
- XSS Scanner
- WhatWeb
- Spaghetti
- WPscan
- WPscanner
- WPSeku
- Droopescan ( CMS Vulnerability Scanner Wordpress, Joomla, Silverstripe, Drupal, And Moodle)
- SSLScan
- SSLyze
- A2SV 
- Dirsearch

# How To Use It ?

this tool is only designed for Linux OS so if you are not using Linux OS im sorry dude but if you have Android Smarphone or Tablet you can run this tool via Termux or GNURoot Debian

so Are You Ready ??

Let's Start It

Ok in my recent OS (Kali Linux) has been already installed this module
- Nmap
- Wafw00f
- WPScan
- SSLScan
- SSLyze

So if your OS Doesn't Have it 

you can install it first here i give you resource

- Nmap 

Red Hat, Fedora, Mandrake, and Yellow Dog Linux with Yum
> yum install nmap

Debian Linux and Derivatives such as Ubuntu
> apt-get install nmap

more info : https://nmap.org

- Wafw00f 
> git clone https://github.com/EnableSecurity/wafw00f.git

> cd wafw00f

> python setup.py install

or simple way

> pip install wafw00f

- WPScan 

Installing dependencies on Ubuntu
> sudo apt-get install libcurl4-openssl-dev libxml2 libxml2-dev libxslt1-dev ruby-dev build-essential libgmp-dev zlib1g-dev

Installing dependencies on Fedora
> sudo dnf install gcc ruby-devel libxml2 libxml2-devel libxslt libxslt-devel libcurl-devel patch rpm-build

Installing dependencies on Arch Linux
> pacman -Syu ruby

> pacman -Syu libyaml

Installing manually (not recommended)
> git clone https://github.com/wpscanteam/wpscan.git

> cd wpscan

> sudo gem install bundler && bundle install --without test

more info https://github.com/wpscanteam/wpscan if you cannot install WPScan don't worry just Skip it i have alternative wpscan module for you

- SSLScan 
> more info about installing this module

> https://github.com/rbsec/sslscan

- SSLyze : 
> git clone https://github.com/nabla-c0d3/sslyze.git

> cd sslyze

> pip install -r requirements.txt --target ./lib

or simple way

> pip install --upgrade setuptools

> pip install sslyze

if Nmap, Wafw00f, WPScan, SSLScan, SSLyze not installed in your OS maybe this tool not really work completely so if Nmap, Wafw00f, WPScan, SSLScan, SSLyze already installed you can next.

Q : can i skip using this tool without Nmap, Wafw00f, WPScan, SSLScan, SSLyze installed in my OS ?

A : yes you can do it but not really work completely

Ok next this is step by step for preparation for first time use

First Things First Clone This Tool 
> git clone https://github.com/Yukinoshita47/Yuki-Chan-The-Auto-Pentest.git

Get inside of directory
> cd Yuki-Chan-The-Auto-Pentest

Give Chmod 777 Access Level 
> chmod 777 wafninja  joomscan  install-perl-module.sh yuki.sh

> chmod 777 Module/WhatWeb/whatweb

And Then Install Python Module
> pip install -r requirements.txt

After That Install Perl Module 
> ./install-perl-module.sh

preparation finished now run this tool and happy pentest

Run This Tool 
> ./yuki.sh


# ScreenShoot Preview

this is my live pentest off course legal pentesting

![screenshot](https://3.bp.blogspot.com/-bU1df89ZQMU/WbbonSFpPuI/AAAAAAAABlo/EaBaQcA9sS8MwgwlSkpYHXjb8q6KWPizwCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A06.png)
![screenshot](https://3.bp.blogspot.com/-pd0OeaoYtTc/WbbonvelkOI/AAAAAAAABlw/0Vy7uRrq-qI-nl9VamJWvQqaMb52E_PawCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A12.png)
![screenshot](https://2.bp.blogspot.com/-sFHPJgeKbAw/WbbonrLfeEI/AAAAAAAABls/9HFtRVptdGkWcyiNt1hCa9X6hs5AgL0vgCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A17.png)
![screenshot](https://4.bp.blogspot.com/-91LlJr35qEk/WbbooxDl37I/AAAAAAAABl0/FVU31LeRzRM7K1zrY3NxR76f0UsL7WfYACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A20.png)
![screenshot](https://3.bp.blogspot.com/-gulWLbyuFCY/WbbopJdBEuI/AAAAAAAABl4/Pifc62a8hNIBYrNcYHwPkAp8qdqCq2m9ACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A26.png)
![screenshot](https://2.bp.blogspot.com/-3DRA3QFL_Vo/WbbopJnbtZI/AAAAAAAABl8/RXVDOEUIvPYvhDTE-Uu7y_X7FhaoR5UOQCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A31.png)
![screenshot](https://4.bp.blogspot.com/-YJHGPAMvOQk/Wbbopwgss4I/AAAAAAAABmA/pF3eRtVWhc0GrpVyZYZikNDJiBi8qfnXQCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A38.png)
![screenshot](https://3.bp.blogspot.com/-BHvOYjej6bM/WbboqNbVPcI/AAAAAAAABmE/GcPAGUaHePsxzyOt0MyWh7QUu3NKEkkqwCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A40.png)
![screenshot](https://4.bp.blogspot.com/-BmTHDr0Gs7c/WbboqIyIsrI/AAAAAAAABmI/d9s2DQjXORokNZ_AeetAGhFAyw4_VeoRACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A46.png)
![screenshot](https://4.bp.blogspot.com/-BHvvP7sQQv4/Wbboq-FHjaI/AAAAAAAABmM/FbY9DeJWPnQuewSRZfvV9_Ci6WzQjeC8QCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A51.png)
![screenshot](https://4.bp.blogspot.com/-b3fpMnBJz2s/WbborPu8CsI/AAAAAAAABmQ/LgjCf12qz0wp7yHSA5ftoUdheI5nbbsKwCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A05%253A54.png)
![screenshot](https://1.bp.blogspot.com/-51ATos0e4x4/WbborK8IpQI/AAAAAAAABmU/oDhQXcj7HaYATCsWTVNYtwmDiAM79680ACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A01.png)
![screenshot](https://2.bp.blogspot.com/-5wgibDzizMA/WbborxF_N_I/AAAAAAAABmY/coFrJ6BU8O0djxlXisdWtCILQJ_0NO6OwCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A09.png)
![screenshot](https://4.bp.blogspot.com/-DSfxX03js_M/Wbbor9KhESI/AAAAAAAABmc/fejuhOAXzQstrxMyTG7SVp3XM0LjEUK6QCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A15.png)
![screenshot](https://1.bp.blogspot.com/-XduIt3xvt3k/WbbosEEYGJI/AAAAAAAABmg/rh9v-297lLYxrH87KgBSNU-zBQ8VJJSsQCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A19.png)
![screenshot](https://2.bp.blogspot.com/-3mrMt2-ePGg/Wbbos_1H_XI/AAAAAAAABmk/v87yXyjD6dMkST2zjolmf1is3deMN476gCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A23.png)
![screenshot](https://2.bp.blogspot.com/-iY9oVzDAufM/WbbotLgyVRI/AAAAAAAABmo/2w4C0wXLq6k0oh1PWCWde2S33G-sCXbSgCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A30.png)
![screenshot](https://1.bp.blogspot.com/-tsSfVKw1PK8/WbbotLNSKUI/AAAAAAAABms/JO6kvmT9RcUdMk4FYIE2f2AXVZexSzyhwCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A35.png)
![screenshot](https://1.bp.blogspot.com/-_lRpF5kA9W8/Wbbotxz2JXI/AAAAAAAABmw/op2EYRgvr6QVnNjh0V638ZR42sSWkfvHwCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A40.png)
![screenshot](https://1.bp.blogspot.com/-Ymtmj7DWXOE/WbbouJXwsCI/AAAAAAAABm0/AWyV6Fl9sY00FDPBBj2MY_UtRvpTCKU6QCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A45.png)
![screenshot](https://1.bp.blogspot.com/-NeSWgAK2C_4/WbbouKfYg6I/AAAAAAAABm4/TRD_fvoFsjI-Ou3NWzpiJbWU0beW3DK-wCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A48.png)
![screenshot](https://1.bp.blogspot.com/-H1F_dIPhLbI/Wbbou8VmGFI/AAAAAAAABm8/IWjbtiZ7wxAdhlXtc52PdbVJF_CXM6WjgCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A51.png)
![screenshot](https://2.bp.blogspot.com/-_uekKTjXigM/WbbovP4S2oI/AAAAAAAABnA/Hd0wj4MvBk41MXkmf5NqcHRTRiJePGmQACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A54.png)
![screenshot](https://1.bp.blogspot.com/-Mub8T9B0WZ4/Wbbovbkd3WI/AAAAAAAABnE/BuLaadrZKFE-WRJpbTPGC7QGLawYGpg6wCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A06%253A58.png)
![screenshot](https://4.bp.blogspot.com/-dm42ZRZTszs/WbbowHgZHSI/AAAAAAAABnI/UzNFM9vZfRcrHUG9JEkfy4LiNhtpxXuwgCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A07%253A08.png)
![screenshot](https://4.bp.blogspot.com/-4DjG6NcadSs/WbbowmlpAfI/AAAAAAAABnM/BEVreiYjJU828ZP7UisNXHDe6MTDK3ZaQCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A09%253A36.png)
![screenshot](https://2.bp.blogspot.com/-Xe9Ji6YdUrE/Wbbowlv8zxI/AAAAAAAABnQ/y3Zchbc8HHs72M0agGCx5xAxq8_gtmUvwCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A20%253A23.png)
![screenshot](https://4.bp.blogspot.com/-5JsOrwOGuXE/WbboxN8ojHI/AAAAAAAABnU/bgzD871xFbQLbDRO6G3GPOdNeciWCQMsACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A20%253A46.png)
![screenshot](https://4.bp.blogspot.com/-SNoiPlWKF80/WbboxmMGz4I/AAAAAAAABnY/wnJK20qSezguMbAsMluQ-wcMloWxBYb-wCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A30%253A19.png)
![screenshot](https://2.bp.blogspot.com/-dWAKJNEpPRI/WbboxsAdJ2I/AAAAAAAABnc/_G1BkDNHvgoMswzP3fInedWuZjB2uRxnACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A30%253A30.png)
![screenshot](https://3.bp.blogspot.com/-SKkvKYoHNj8/WbboyXXls5I/AAAAAAAABng/TXns0NPC4hYoGCXs7rqUisD1nyIQVp53gCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A30%253A38.png)
![screenshot](https://4.bp.blogspot.com/-s1swnSpgKxU/Wbboy7XbJEI/AAAAAAAABnk/7ZRE3tHKo38Lhktlb_AuUTg7zzqqDBufQCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A31%253A07.png)
![screenshot](https://2.bp.blogspot.com/-JIUXQaX-SHc/Wbboy1Vpl-I/AAAAAAAABno/OJVoQE092gcXsmahRI-pahNFQCst67tpgCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A31%253A10.png)
![screenshot](https://1.bp.blogspot.com/-qOuCk-zliZk/WbbozZHEl5I/AAAAAAAABns/Fz8Xz_bfTGoHYAqZcxHof73T2HOd1jR7QCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A31%253A15.png)
![screenshot](https://2.bp.blogspot.com/-BXErKeoKF7E/Wbbo0C7D3qI/AAAAAAAABnw/p80xo0Nm7egeKOPaRZK-KU8M9SLnzseyQCLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A31%253A19.png)
![screenshot](https://1.bp.blogspot.com/-5FSTRw8hFY4/Wbbo0CtpObI/AAAAAAAABn0/4ffA4fWg1WwtJsjGUc6c7k15yAvnKWeZACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A31%253A28.png)
![screenshot](https://4.bp.blogspot.com/-iDmljrPlFV8/Wbbo0QokRlI/AAAAAAAABn4/uxmkZk8IU6oNS87VhC-ZzuqlnTzBfCA6ACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B16%253A52%253A06.png)
![screenshot](https://4.bp.blogspot.com/-J_RYvAzgqXg/Wbbo03jAl1I/AAAAAAAABn8/TqHKP1CCnfMM8GX1Z6L5kR7-cy2ipMJrACLcBGAs/s640/Screenshot%2Bfrom%2B2017-09-11%2B17%253A01%253A03.png)

# Greetings
Hope You Guys Enjoy This Tool And As Always Have Nice Day

Regard

From : Yukinoshita 47 

Team : Garuda Security Hacker

Email : yukinoshita47@gmail.com

Web : http://www.garudasecurityhacker.org
