# anyconnect->openconnect->ocserv
cisco anyconnect vpn,  server, client
---

AnyConnect为思科推出的VPN客户端，目前已有Windows、Android、iOS、OS X、Ubuntu、WebOS等操作系统的客户端。AnyConnect主要作用是方便员工在任何设备上安全地办公，也有部分中国大陆用户利用AnyConnect bypass GFW。

OpenConnect is an open-source software application for connecting to virtual private networks (VPN), which implement secure point-to-point connections.

It was originally written as an open-source replacement for Cisco's proprietary AnyConnect SSL VPN client, which is supported by several Cisco routers. As of 2013, the OpenConnect project also offers an AnyConnect-compatible server, ocserv, and thus offers a full client-server VPN solution.

OpenConnect是一个开源软件应用程序，用于连接虚拟专用网络（VPN），实现安全的点对点连接。

它最初是作为思科专有的AnyConnect SSL VPN客户端的开源替代品，由几个思科路由器支持。 截至2013年，OpenConnect项目还提供与AnyConnect兼容的服务器ocserv ，从而提供完整的"客户端--服务器"VPN解决方案。


## Anyconnect的代替: openconnect(client), ocserv(server) 

**服务器端的代替： ocserv (openconnect server on linux)

[OCSERV: Openconnect VPN Server](http://ocserv.gitlab.io/www/index.html)

[Mirror of official ocserv repository](https://github.com/openconnect/ocserv)

**客户端的代替：  openconnect  (on linux, windows, and Mac )

[openconnect/openconnect-gui](https://github.com/openconnect/openconnect-gui)

[openconnect/openconnect](https://github.com/openconnect/openconnect)

## ocserv linux(Debian)安装

### 安装:

> wget -N --no-check-certificate https://raw.githubusercontent.com/st286/ocserv-openconnect-anyconnect/master/ocserv.sh
>
> chmod +x ./ocserv.sh
>
> ./ocserv.sh

ocserv version: 0.12.3

**also see:**

[lllvcs/ocserv](https://github.com/lllvcs/ocserv)

## openconnect客户端

**for macOS:**

>  brew cask install openconnect-gui

**also see for other OS:**

[使用openconnect代替cisco anyconnect](https://segmentfault.com/a/1190000011530974)

[openconnect/openconnect-gui](https://openconnect.github.io/openconnect-gui/)

---
