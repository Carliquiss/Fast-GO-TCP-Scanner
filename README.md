# Fast-GO-TCP-Scanner
Script to scan quite fast all TCP ports from an IP

Usage: 
```
go run fastTCPscan.go -host=IP -range=80,100,1000-2000  -threads=1000 -timeout=1 
```
Default port scan: all 65535 ports
Default threads: 1000 threads
Default timeout for each port: 1 second
