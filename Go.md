# Go

Go（又称Golang）是Google开发的一种静态强类型、编译型、并发型，并具有垃圾回收功能的编程语言喵~

## 安装

杂鱼~杂鱼~大哥哥不会连安装也不会吧（笑）  
快去求助万能的因它奈特吧~

## 设置代理

因它奈特🌐我们的 euphoria😆  
机油，乐子，SOX🥵  
"嗨，让我访问，哈哈哈🤪"  
但机油......也有界限👮‍♂️  
“不！为什么不能访问？不！！！😭”  
INVASION  
哈哈，觉得眼熟？🤔  
这样的场景，此时此刻正在各地上演！🤓  
下一个可能就是你👈  
除非你能做出生命中最重要的决定🤗  
......（广告位招租）

```shell
go env -w GO111MODULE=on
go env -w GOPROXY=https://goproxy.cn,direct
```

总之敲入这两行命令就可以解决你的网络问题了喵~

## Hello World

这里是经典的 Hello World 喵~

首先，跟着我做：

```shell
mkdir helloworld
cd helloworld
go mod init helloworld
touch main.go
```

然后复制以下代码🤓

```go
package main

import "fmt"

func main {
    fmt.Println("Hello World")
}
```

哦没得多🎉🎉🎉  
你又学会了一门编程语言（的 Hello World）  
~~现在就去编写一个多线程服务器吧~~

## 常量与变量

```go
const name = "田所"
const (
    age = 24
    job = "学生"
) 
var a, b = 114514, 1919810
// 好臭的数字🤮
```

这时候就有人要问了：  
诶，不是说 go 是静态强类型吗？为什么你不声明类型🤓👆  

作为一门现代编程语言，go 有自动类型推断，好舒服呢🥰

哦，对了，go 的类型声明是后置的😮

```go
var youzi string = "Ciallo～(∠・ω< )⌒☆"
```

## 运算符

懂得都懂，不懂的我也不多解释🤗

还是说一句吧，有 `i++` 但没有 `++i` 喵~

## 格式化 I/O

杂鱼不会自己查文档吗😡  
什么都让我教，小孩子吗？  
哈？给个链接？  
除非你跪下来舔我的🦶

prprprpr🥵

呜哇！真恶心🤮  
[https://pkg.go.dev/fmt](https://pkg.go.dev/fmt)  
快拿走吧，熟读 fmt 再来找我😤

To be continued...
