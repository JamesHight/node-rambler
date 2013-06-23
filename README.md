Rambler
=======

Walk a website checking for bad links

Installation
------------

````bash
npm install -g rambler
````

Usage:
------

````bash
# Show help
ramber -h

# Walk a website
rambler -u http://example.com

# Override the IP address for a domain by doing evil things to 
# the core dns library.
rambler -u http://example.com -d example.com:1.2.3.4
````