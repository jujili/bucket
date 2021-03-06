<!-- markdownlint-disable MD041 -->
<h1 align="center">:hourglass_flowing_sand: bucket</h1>
<p align="center">
<!--  -->
<a href="https://github.com/jujili/bucket/releases"> <img src="https://img.shields.io/github/v/tag/jujili/bucket?include_prereleases&sort=semver" alt="Release" title="Release"></a>
<!--  -->
<a href="https://www.travis-ci.org/jujili/bucket"><img src="https://www.travis-ci.org/jujili/bucket.svg?branch=master"/></a>
<!--  -->
<a href="https://codecov.io/gh/jujili/bucket"><img src="https://codecov.io/gh/jujili/bucket/branch/master/graph/badge.svg"/></a>
<!--  -->
<a href="https://goreportcard.com/report/github.com/jujili/bucket"><img src="https://goreportcard.com/badge/github.com/jujili/bucket" alt="Go Report Card" title="Go Report Card"/></a>
<!--  -->
<a href="http://godoc.org/github.com/jujili/bucket"><img src="https://img.shields.io/badge/godoc-bucket-blue.svg" alt="Go Doc" title="Go Doc"/></a>
<!--  -->
<br/>
<!--  -->
<a href="https://github.com/jujili/bucket/blob/master/CHANGELOG.md"><img src="https://img.shields.io/badge/Change-Log-blueviolet.svg" alt="Change Log" title="Change Log"/></a>
<!--  -->
<a href="https://golang.google.cn"><img src="https://img.shields.io/github/go-mod/go-version/jujili/bucket" alt="Go Version" title="Go Version"/></a>
<!--  -->
<a href="https://github.com/jujili/bucket/blob/master/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License" title="MIT License"/></a>
<!--  -->
<br/>
<!--  -->
<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=7f61280435c41608fb8cb96cf8af7d31ef0007c44b223c9e3596ce84dec329bc"><img border="0" src="https://img.shields.io/badge/QQ%20群-23%2053%2000%2093-blue.svg" alt="jili交流QQ群:23530093" title="jili交流QQ群:23530093"></a>
<!--  -->
<a href="https://mp.weixin.qq.com/s?__biz=MzA4MDU4NDI5Mw==&mid=2455230332&idx=1&sn=8086c43e259b0012596ed63d6ecd7d10&chksm=88017c76bf76f5604f2f3280ffd96029b5ccaf99db48d18066d3e3bc9bc8a2e1a05de1a3225f&mpshare=1&scene=1&srcid=&sharer_sharetime=1578553397373&sharer_shareid=5ce52651949258759d82d1bf31b455b5#rd"><img src="https://img.shields.io/badge/微信公众号-jujili-success.svg" alt="微信公众号：jujili" title="微信公众号：jujili"/></a>
<!--  -->
<a href="https://zhuanlan.zhihu.com/jujili"><img src="https://img.shields.io/badge/知乎专栏-jili-blue.svg" alt="知乎专栏：jili" title="知乎专栏：jili"/></a>
<!--  -->
</p>

除了 `Token Bucket` 模块都会有的 `Wait` 方法。本模块，还提供了 `Hurry` 方法，能使用单独保留的 token，较高优先级的请求可以更快地得到执行。

- [安装与更新](#%e5%ae%89%e8%a3%85%e4%b8%8e%e6%9b%b4%e6%96%b0)
- [例子](#%e4%be%8b%e5%ad%90)

## 安装与更新

在命令行中输入以下内容，可以获取到最新版

```shell
go get -u github.com/jujili/bucket
```

## 例子
