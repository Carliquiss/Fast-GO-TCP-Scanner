# Fast-GO-TCP-Scanner
Script to scan quite fast all TCP ports from an IP

Usage: 
```
./fastTCPscan -host=IP -range=80,100,1000-2000  -threads=1000 -timeout=1 
```
or if you have Go installed: 
```
go run fastTCPscan.go -host=IP -range=80,100,1000-2000  -threads=1000 -timeout=1 
```
Default port scan: all 65535 ports  
Default threads: 1000 threads  (For Linux machines seems to be OK, but for Windows ones its recommended to set about 200)
Default timeout for each port: 1 second  
