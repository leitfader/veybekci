# veybekci

`veybekci` is a simple command-line tool that retrieves historical URLs for a list of domains using the Internet Archive’s CDX API. It processes domains sequentially, saves results per domain, and provides a clean, real-time terminal display while running. Creating a directory with the list of domains saved as domains.txt and just simply execute it.

# Create a file with domains
`domains.txt` should look like this : 
```bash
example.com
example.org
```

## Installation
Download the script and make it executable:
```bash
curl -fsSL https://raw.githubusercontent.com/leitfader/veybekci/refs/heads/main/veybekci -o veybekci && chmod +x veybekci
```

## Disclaimer
This tool relies on the public `Internet Archive CDX API`. Availability, rate limits, and returned data are subject to change. Use responsibly.
