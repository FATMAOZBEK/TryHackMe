# YourFirstHack Room

Gobuster is a tool used for directory and file enumeration on web servers. 
It helps security professionals discover hidden files and directories by brute-forcing common names based on a wordlist. 
By sending HTTP requests, it identifies accessible resources that may not be linked directly on the website, aiding in vulnerability assessments and penetration testing.

In the terminal  -u is used to state the website we're scanning, -w takes a list of words to iterate through to find hidden pages.

gobuster -u http://1111.com -w wordlist.txt dir

You will see that GoBuster scans the website with each word in the list, finding pages that exist on the site.
GoBuster will have told you the pages it found in the list of page/directory names.(1111.com used as an example)
