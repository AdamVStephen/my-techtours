REF https://iximiuz.com/en/posts/you-dont-need-an-image-to-run-a-container/

First install go

Create Makefile to hold the go build invocation.

printme : main.go
		GOOS=linux GOARC=amd64 go build -ldflags="-w -s" -o $@

go mod init my_container/main ; make ; 
