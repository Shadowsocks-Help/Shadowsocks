# 苹果 macOS 使用 Shadowsocks 设置教程

## 第一步 安装 ShadowsocksX-NG

**在安装之前，请始终确保您的系统满足最低系统要求。**

您需要具备 MacOS 10.11 或更高版本才能运行 ShadowsocksX-NG。如果您的操作系统版本较旧， 则请先升级到 MacOS 10.11 或更高版本。按照下面的说明在 MacOS 上下载并安装 ShadowsocksX-NG。

#### 1. 下载客户端

【 [ShadowsocksX-NG 下载](https://github.com/shadowsocks/ShadowsocksX-NG/releases/download/v1.8.2/ShadowsocksX-NG.app.1.8.2.zip)】|【 [Sourceforge 备用下载](https://sourceforge.net/projects/shadowsocksgui/files/dist/ShadowsocksX-2.6.3.dmg/download) 】|【[历史版本](https://github.com/shadowsocks/ShadowsocksX-NG/releases/)】

#### 2. 安装客户端

双击解压 `ShadowsocksX-NG.x.x.x.zip` , 获取 `ShadowsocksX-NG`。

![安装客户端](/img/mac1.png)

将 "ShadowsocksX-NG" 拖移到 “访达”里面的 “应用程序”。

!["ShadowsocksX-NG" 移动到 "访达" 里面的 "应用程序"](/img/mac2.gif)

在 "应用程序" 中双击 "ShadowsocksX-NG" > 选择 "打开"。

![选择打开](/img/mac3.png)

## 第二步 获取 Shadowsocks 账号信息

详见：[SS/ShadowsocksR 服务器节点 点击获取](ss.md)

## 第三步 配置 Shadowsocks 账号

#### 在您的电脑上， 执行下列操作：

* 点击屏幕顶部菜单栏的 ![menu_icon_disabled](/img/mac5.png) > "服务器" > "服务器设置"。

![点击屏幕最上方菜单栏](/img/mac6.png)

* 点击窗口上的 "+" > 填写 "地址" > 填写 “服务端口" > 选择 ”加密方法"。
* 填写 "密码“ > 填写"备注" 为可选项。
* 点击 "打开Shadowsocks" 。
* 当显示 `Shadowsocks: On`时，表示系统代理已经打开。

![服务器设置，打开ss](/img/mac7.png)

#### 可以通过二维码方式单独增加节点， 在您的电脑上， 执行下列操作：

此二维码同样适用于其他客户端。

* 点击屏幕顶部菜单栏的 ![menu_icon_disabled](/img/mac5.png) > "扫描屏幕上的二维码" > 当看到 "已添加新的Shadowsocks服务器"，代表添加成功。
* 点击 "打开Shadowsocks" 。
* 当显示 `Shadowsocks: On`时，表示系统代理已经打开。

![打开ss](/img/mac8.png)

## 配置系统代理模式
*  点击屏幕右上方菜单栏的 ![menu_icon_disabled](/img/mac5.png)  > "PAC自动模式"。

![pac设置](/img/mac9.png)

## 其他
* **PAC 模式** 表示可以实现自动代理， 及本来可以访问的网站不会经过代理，推荐日常使用。
* **全局模式** 表示计算机内大多数流量都会经过代理， 不推荐日常使用。

### [<< 返回首页](https://shadowsocks-help.github.io/Shadowsocks/)
