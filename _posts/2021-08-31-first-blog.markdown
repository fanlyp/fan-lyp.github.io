---
layout: post
title: first blog
date: 2016-02-16 15:32:24.000000000 +09:00
---

## git 使用

### 连接到已有的远程仓库
重新在git设置一下身份的名字和邮箱
```java
git config --global user.name "xxxxxx"
git config --global user.email "xxx@qq.com"
```
生成ssh

```java
ssh-keygen -t rsa -C "xxx@qq.com"
会提示（我的已存在了）：
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/x、/.ssh/id_rsa):
/c/Users/x、/.ssh/id_rsa already exists.
```
这是生成了三个文件，打开id_rsa.pub，复制出来其中的内容。
| Site Name    | file name                                          |
| ------------ | ---------------------------------------------------|
|      file    |                      id_rsa                        |
|      file    |                      id_rsa.pub                    |
|      file    |                      known_hosts                   |

登录自己的github账户，在github添加密钥

#### Sites using Vno

[My blog](http://onevcat.com) is using `Vno Jekyll` as well, you could see how it works in real. There are some other sites using the same theme. You can find them below:

| Site Name    | URL                                                |
| ------------ | ---------------------------------------------------|
| OneV's Den   | [http://onevcat.com](http://onevcat.com)           |
| July Tang    | [http://blog.julytang.xyz](http://onevcat.com)     |
| Harry Lee    | [http://qiuqi.li](http://qiuqi.li)                 |

> If you happen to be using this theme, welcome to [send me a pull request](https://github.com/onevcat/vno-jekyll/pulls) to add your site link here. :)

#### License

Great thanks to [Dale Anthony](https://github.com/daleanthony) and his [Uno](https://github.com/daleanthony/uno). Vno Jekyll is based on Uno, and contains a lot of modification on page layout, animation, font and some more things I can not remember. Vno Jekyll is followed with Uno and be licensed as [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/). See the link for more information.
