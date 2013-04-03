ChecksumTheWeb
==============

Does your ISP inject data into your traffic? Checksum the web is designed to find out.

Consisting of a small piece of javascript and a seperate JSONP file, it performs an MD5 checksum on the page when it loads, and lets you know if the page is not being recieved exactly as transmitted. No fancy server side magic is required, all that is needed is for the admin to know the MD5 of the page (which you can get by notifying when you have a mismatch) to configure the JSONP side. 

At present, this is little more than a proof of concept hacked together quickly. Fuller examples coming soon...
