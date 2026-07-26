<img width="425" height="120" alt="Screenshot_2026-07-26_100448-removebg-preview" src="https://github.com/user-attachments/assets/797d215c-b7be-4fc8-aa15-ffdd9e586bdd" />




**This is a simple websocket relay that forward websocket message from one client to another**

>run main.go

    go run main.go -p [port]
    eg: - go run main.go -p 8080

>run fsocket [linux executable]

    fsock -p [port]
    eg:- fsock -p 8080

>enable/disable website mode

    fsock -w=[true/false]
    eg:- fsock -w=false //disables website mode

>build (main.go)

    go build -ldflags="-s -w" main.go  //build
    upx --brute main  //lower size executable
