# Simple-DNS-over-HTTPS-client
Simple DNS over HTTPS client written in python

```bash
usage: doh.py [-h] [-i INPUTFILENAME] [-o OUTPUTFILENAME] [-d {A,AAAA,MX,TXT}]
              [-t {GET,POST}] [-w {wire,json}] [-u URL]
              [domain]

Application do requests DOH requests

positional arguments:
  domain

optional arguments:
  -h, --help            show this help message and exit
  -i INPUTFILENAME, --input-file INPUTFILENAME
  -o OUTPUTFILENAME, --output-file OUTPUTFILENAME
  -d {A,AAAA,MX,TXT}, --dns-request-type {A,AAAA,MX,TXT}
  -t {GET,POST}, --http-request-type {GET,POST}
  -w {wire,json}, --wire-or-json {wire,json}
  -u URL, --url URL
```
