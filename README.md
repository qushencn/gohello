# gohello
参考博客：https://blog.csdn.net/weixin_38959210/article/details/122528007

### 初始化项目：

新建文件夹，初始化项目

```go
go mod init
```

### 新建main.go文件：

```go
package main // 声明 main 包，表明当前是一个可执行程序
 
import (
 
	"github.com/qushencn/gohello"
)
 
func main() { // main函数，是程序执行的入口
 
	gohello.Hi("zhangsan")
 
	
}
```



### go mod tidy：

执行go mod tidy，检查并拉取仓库文件

```go
go mod tidy
```

### go run：

```
go run main.go
```

![img](https://img-blog.csdnimg.cn/95a66bc345264fdc9d35cc9e72cf782f.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA5oCq5Y-q5oCq5ruh55y85bC95piv5Lq66Ze054Of54Gr,size_20,color_FFFFFF,t_70,g_se,x_16)

