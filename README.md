This tool goes in hand with my js link finder bookmarklet and gofuzz, my tool that evades WAF. Install them both first to use this tool

run these commands to install this tool

-> cd ruhttps
-> chmod +x runhttps
-> sudo mv runhttps /usr/local/bin/runhttps

to use this tool

-> runhttps -h

This tool has 2 modes 
-> HTTPX : works like the tool HTTPX, you give the tool some urls by either copypasting the links or through a textfile 
-> FUZZ  : works like the tool FUZZ, the first line you give should be the url (dont have to add FUZZ, it will automatically add in the end) 
           and the lines after must be paths that were fetched from javascript files

How to use this tool

-> for fuzzing mode enter the following commands

runhttps -FUZZ
-> then paste the content down below and press ctrl-D twice

-> for httpx mode enter the following command

runhttps -HTTPX
-> then paste the urls below and press ctrl-D twice
