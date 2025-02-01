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

## 关键字

```go
break        default      func         interface    select
case         defer        go           map          struct
chan         else         goto         package      switch
const        fallthrough  if           range        type
continue     for          import       return       var
```

## 运算符

```go
+    &     +=    &=     &&    ==    !=    (    )
-    |     -=    |=     ||    <     <=    [    ]
*    ^     *=    ^=     <-    >     >=    {    }
/    <<    /=    <<=    ++    =     :=    ,    ;
%    >>    %=    >>=    --    !     ...   .    :
     &^          &^=          ~
```

懂得都懂，不懂的我也不多解释🤗

## 常量与变量的声明

Go 有自动类型推断，一般情况下不需要声明类型喵~

```go
const name = "田所"
const (
    age = 24
    job = "学生"
) 
var a, b = 114514, 1919810
// 好臭的数字🤮
```

> [!NOTE]
> 整数默认是 `int` 类型，浮点数默认是 `float64` 类型🤓👆

哦，对了，Go 的类型声明是后置的😮

```go
var youzi float32 = 0.721 
```

变量还可以使用 `:=` 短声明喵~

```go
youzi := "Ciallo～(∠・ω< )⌒☆"
```

> [!WARNING]
> 短声明不能用于声明 package 作用域的变量哦！
>
## 分支与循环

```go
if number := rand.Intn(3); number == 0 {
    fmt.Println("OGC，经验+3")
} else if number == 1 {
    fmt.Println("OGC，经验+3")
} else {
    fmt.Println("OGC，经验+3")
}

switch number := rand.Intn(6); number {
case 0:
    fmt.Println("game over")
default:
    fmt.Println("safe")
}

for {
    fmt.Println("break 呢？救一下啊😭")
}

for i := 10; i < 10; i-- {
    fmt.Println(i)
}

goto label
label:
    fmt.Println("不要乱用 goto 啊喂！")
```

除了 `break` 和 `continue` 以外，Go 还提供了一个 `fallthrough`  喵~  
通常情况下，switch 语句在执行完一个 case 分支后会自动退出，但使用 fallthrough 可以让程序继续执行下一个 case 分支，而不管下一个 case 的条件是否满足🤗

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
