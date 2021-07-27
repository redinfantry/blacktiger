
Welcome to the blacktiger tool's official github page.

Running various tools during recon can be tedious , blacktiger minimizes this work by gathering intel for you through various tools like assetfinder, amass,certspotter, sublist3r, httprobe, waybackurls, whatweb , nmap and eyewitness 

What Black Tiger can do ?

Currently Black Tiger is capable of :

* Finding assets using asset finder
* DNS Enumeration and mapping of target 
* Finding SSL certificates for a domain, using Certificate Transparency logs. Include sub-domains.
* Enumerating subdomains of websites using OSINT
* Probing for active http and https servers
* Fetching known URLs from the Wayback Machine for *.domain 
* Recognises web technologies including content management systems,etc of a website
* Providing quick, detailed scans of network traffic
* Scan and capture screenshots of subdomains on http/https, using web ports and ocr


**Dependencies **
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Note: Kindly make sure your pentesting OS has these tools installed int it.

assetfinder - https://github.com/tomnomnom/assetfinder

amass - https://github.com/OWASP/Amass

certspotter - #curl -s https://certspotter.com/api/v0/certs\?domain\=$url | jq '.[].dns_names[]' | sed 's/"//g' | sed 's/*.//g' | sort -u (set as alias)

sublist3r - https://github.com/aboul3la/Sublist3r

httprobe - https://github.com/tomnomnom/httprobe

waybackurls - https://github.com/tomnomnom/waybackurls

whatweb - https://github.com/urbanadventurer/WhatWeb

nmap - https://nmap.org/download.html

eyewitness - https://github.com/FortyNorthSecurity/EyeWitness
