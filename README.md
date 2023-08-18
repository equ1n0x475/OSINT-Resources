# OSINT-Resources
This is a repository of FREE OSINT resources I have used throughout my time in investigations. Happy Hunting!

**Dark Web Investigations**

ahmia.fi -my favorite tor search engine: usable from the surface web [requires tor to click on any of the results & blocks CSAM]

dark.fail - a surface web index of popular onion links. Small collection but has real time detection if a link is down or not

OnionSearch [More in Command Line Must Haves]

**Usernames/People**

https://whatsmyname.app/ -username scan (runs a username through a bunch of different social media platforms. Useful, but make sure results are your target and not someone else with the same username)

https://www.mugshots.org - find a mugshot 

https://www.whitepages.com/ -free information is super beneficial, addresses, phone numbers, family members, but criminal records are a paid service

https://thatsthem.com/ -  free people search engine [compatible with emails]


**Email Addresses**

https://thatsthem.com/ - People search engine, gives good information about emails, IPs, names, addresses, VIN numbers, and phone numbers

https://hunter.io - Finds emails associated with domains

https://haveibeenpwned.com/ -email breach finder, make sure you scroll down and see if any of the breaches are clickable. 

https://emailrep.io/ -email information gatherer (very surface level but good info)

https://tools.epieos.com/ -great tool for emails (especially GMAIL)



**Domains**

https://tools.iplocation.net/unshorten-url  - unshortens possibly malicious urls (shortening a url is a very common tactic for IP logging, ex: shorturl.at/fprP0 )

http://dns-lookup.com/ -DNS lookup- get IPs, web service, and name servers

https://www.virustotal.com/gui/home/upload - Analyze suspicious files, domains, IPs and URLs to detect malware and other breaches, automatically share them with the security community [VERY USEFUL, upload any file and VirusTotal will tell you if there’s malware in it]

https://urlscan.io/ - scans websites for malicious content and lets the user view a screenshot

https://www.iana.org/whois - find public information about a given domain.

https://tools.iplocation.net/ - suite of tools applicable to this domain


**IP Addresses**

https://earth.google.com/web/ -use coordinates from IP Geolocation, go into street view, and find the street address of an IP address

https://www.iplocation.net - Amazing collection of Networking tools. The ‘IP Lookup’ bar at the top of the page will do geolocation on any IP. Click on ‘tools’ for a vast array of free tools

https://www.abuseipdb.com - database of malicious IPs

**Images**

https://tineye.com/ - reverse image search (find if the image was posted anywhere else, if not its an authentic photograph)

http://pimeyes.com/ - reverse image search with AI facial recognition component built in. Scans faces and finds the picture you gave it, and other pictures of the same person. Limited to 10 searches a day

https://exifdata.com/ -EXIF data is the metadata behind photos. This tool extracts said data.


**Tool Collections/Education**

https://github.com/jivoi/awesome-osint  - Gigantic OSINT tool list. Includes websites, python tools, and more! 

https://osintframework.com/ - Great list of starting points for any investigation

https://tools.iplocation.net/ -very useful DNS/IP tools

https://www.hackers-arise.com/osint -great resource for learning advanced OSINT (Also has case studies!!!)

https://www.hackers-arise.com/post/osint-google-hacking-and-dorks-to-find-key-information - Google Dork Tutorial and intro to GHDB (highly recommend)

**Cryptocurrency**

BEFORE ANYTHING FANCY: google the address in quotes “” 
One time I spent hours trying to reverse a chain of BTC transactions. One google search like this cracked the case. Save yourself some time :)

https://www.bitcoinabuse.com/ - database of malicious BTC addresses

Blockchain.info - blockchain address lookup

walletexplorer.com - BTC wallet and address tool. Tie an address to a wallet

https://www.bitcoinwhoswho.com/ - BTC reputation report + public listings


**Command Line Must Haves**

https://github.com/sherlock-project/sherlock - Automated username scanner

https://github.com/soxoj/maigret - comprehensive username scanner  

https://github.com/pixelbubble/ProtOSINT - Protonmail OSINT (great for protonmail validation) 

https://github.com/D3Ext/AORT - Domain Recon in one script

https://github.com/kpcyrd/sn0int - OSINT framework for easy pivots

https://github.com/sundowndev/phoneinfoga - phone number info gatherer

https://github.com/megadose/OnionSearch - fantastic for dark web investigations **Make sure to set the proxy as 127.0.0.1:9150 and have TOR running.**

**VM Recommendation**

https://www.tracelabs.org/initiatives/osint-vm - TraceLabs VM 


**Tips**

OSINT job board (private sector): https://www.osint-jobs.com/

Use DuckDuckGo instead of Google. Google will get suspicious of you if you dork too many times and make you solve captchas, duckduckgo will not.

