# Go Installation

Go seems to be popping up on my radar (faster rsync written in Go, main exe demo for containers written in Go) - so let's divert to install it on Thorin.

1. 135 MB download from go.dev of a tar.gz file 
	wget https://go.dev/dl/go1.18.3.linux-amd64.tar.gz
2. Check and eradicate any /usr/local/go directory if necessary and untar as  
	rm -rf /usr/local/go && tar -C /usr/local -xzf go1.18.3.linux-amd64.tar.gz
3. Update PATH
	export PATH=$PATH:/usr/local/go/bin 

