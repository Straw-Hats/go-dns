# go-dns
The 'net' package in go provides many functions for DNS lookup. It is similar using the Unix 'dig' command. 
This information can be extremely useful to implement any kind of network programming that requires dynamically determining IP addresses. 
Hence here we've implemented a simplified 'dig' command. This will seek to map a URL to all of its IPv4 and IPv6 addresses. 
By default the pure Go DNS resolver is used.
