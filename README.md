# wechat
同一个package中函数互相调用的时候，需要将整个目录作为编译的单元，而不能单独执行 go run main.go
正确的做法，在 wechat 目录下面执行以下命令生成执行文件
```
go build .
```
My WeChat Backend Example
