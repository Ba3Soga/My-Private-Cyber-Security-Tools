I was using Jok3r framework to scan website. I created this tool so that a Pentester only need to feed it with the main domain.

The tool will:

* grab all the subdomains it can (can reach up to 2k subdomains)
* checks the working domain (200 c0de)
* return a list of domains that is compatible with jok3r framework.

┌──(root㉿azo)-[/My-Private-Cyber-Security-Tools/subdomain-enum-to-jok3r]
└─# bash shebangeDweb.sh                                   
Usage: bash -d <domain> | -f <file> [-c http_code,...]


- you can also specify -c to tell the tool what http codes you are interested in to put in the list
- specify the main domain using -d 0r multiple main domains using -f
