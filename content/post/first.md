+++
date = 2014-07-24T06:25:47Z
draft = false
title = "Hello World!"
+++
Hello there! This is supposedly the first post of this site, so I guess it’s
customary to start off this post with a `Hello World!` shout out.

Currently I like [go](http://golang.org) a lot, so why not start with a simple
hello world program in go :)

See this running @ http://play.golang.org/p/PN7GapMy3q

{{% highlight go %}}
package main

import "fmt"

func main() {
        你好 := "Hello"
        world := "世界"

        问好(你好, world)
}

func 问好(排列 ...string) {
        for _, 串 := range 排列 {
                fmt.Printf("%s ", 串)
        }
        fmt.Printf("\n")
}
{{% /highlight %}}
