# 苹果 iOS 使用 Shadowsocks 设置教程

## 第一步 下载手机客户端

1、登陆苹果非大陆区账号单独购买下载，以下是苹果商店链接（需非大陆苹果账号，选择任意一个下载即可）。

苹果美区商店 App Store下载：【[推荐 Shadowrocket小火箭 - App Store](https://itunes.apple.com/us/app/shadowrocket/id932747118?mt=8) 】 | 【 [Potatso Lite代理工具 - App Store](https://itunes.apple.com/us/app/potatso-lite/id1239860606?mt=8)】

2、代理软件在iOS国区里已经下架了，需要登录非国区ID才能下载，非常的麻烦而且有些小白也会登录iCloud的，挺危险的，所以推荐在线安装一步到位（选择任意一个在线安装即可）。

苹果手机游览器打开 在线安装：【 [Shadowrocket小火箭在线安装]( https://shadowsocks-help.github.io/ios/) 】| 【 [Potatso Lite代理工具 在线安装]( https://shadowsocks-help.github.io/Potatso-Lite/) 】

3、苹果美区账号分享 详见： [APPLE ID 免费账号共享](appleid.md)

## 第二步 获取 Shadowsocks 账号信息

一个可用的 Shadowsocks 账户（需要包括以下信息：服务器地址、端口号、加密方式、密码）

详见：[SS/ShadowsocksR 服务器节点 点击获取](ss.md)

## 第三步 iOS配置 Shadowsocks 客户端

### 一、Shadowrocket 小火箭 设置教程

***添加 Shadowsocks 账户***

Shadowrocket 是一款专门为 Shadowsocks 设计的 APP，所以添加起来也是极其方便。点击左上角的方框即可扫描 Shadowsocks 账户服务器节点的二维码，免去输入的麻烦。

![](/img/Shadowrocket1.png)

第一次连接时会弹出一个添加代理的提示框，点“Allow”允许，否则不能用。如果你有多个节点，连接后是使用前面有圆点的节点，点击节点即选中作为默认，选中的节点使用中无法删除。

![](/img/Shadowrocket2.png)

或者你也可以点击右上角的加号进行手动输入

![](/img/Shadowrocket3.png)

![](/img/Shadowrocket7.png)

***规则的设置***

一般全局路由选择默认配置即可，如果要实现部分网站国内走直连，国外走代理的话，就需要用到规则。

点击 Settings，然后在点击 Config 你就可以看到以下界面

![](/img/Shadowrocket4.png)

点击 + 通过添加链接，在点击 Use Config 来下载规则文件。你可以对其进行编辑，以满足自己的使用习惯。点击感叹号，然后在点击 Add Rule，点击 Type，就可以看到多种过滤方式进行设置了。

***节点订阅设置***

打开Shadowrocket，点击右上角加号 + ，在添加节点页面，将类型改为第三个 Subscribe，复制订阅地址粘贴到URL中，然后点击右上角完成即可。

![](/img/Shadowrocket5.jpg)

在Shadowrocket设置--服务器订阅中打开【打开时更新】选项。

![](/img/Shadowrocket6.png)

回到首页，打开连接开关，享受科学上网吧！

<hr>

### 二、Potatso Lite 代理工具 设置教程

从 App Store 安装后打开 Potatso Lite。点击 "立即使用" > "现在添加"。

![](/img/PotatsoLite1.PNG)

***扫码配置***

点击 "二维码" > "Potatso Lite 想访问您的相机"的窗口，选择 "好" > 扫描你节点的二维码，节点将自动添加成功。

***手动配置***

1、点击 "添加" > 填写代理。

2、选择 "Shadowsocks“ > 填写 "服务器" > 填写 "端口" > 选择 "加密" > 填写 "密码" 。

3、填写 "备注" 为可选项 > 点击右上角的 "✔"， 设置完成。

![](/img/PotatsoLite2.PNG)

***开始代理***

1、点击 "开始" > 选择 "Allow" > 开启 "智能路由"。

2、当看到左上角出现 VPN 字样时，代表连接成功。

3、智能路由 表示可以实现自动代理， 及本来可以访问的网站不会经过代理，推荐日常使用。

![](/img/PotatsoLite3.PNG)

## 最后 若无法打开网页，可以进行如下测试

1、可以尝试小火箭软件最下面一排按钮，选择-配置 页面，点击 恢复默认配置。

2、更换手机4G网络进行尝试、重启路由器更改IP。

3、下载其他代理软件尝试， 推荐 如 Potatso Lite ,请使用 美区账号登陆App Store 搜索下载安装。

## 需要再次说明的是

1、由于 shadowrocket 等软件 不在部分国家如中国等商店上架，因此需要使用美国/香港等appstore账号才可下载。

2、苹果美区账号分享 详见： [APPLE ID 免费账号共享](appleid.md)。

3、使用共享账号登录，切记请勿登录iCloud。

### [<< 返回首页](https://shadowsocks-help.github.io/Shadowsocks/)
