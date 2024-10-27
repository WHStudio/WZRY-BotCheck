# WZRY-BotCheck

## 教程

**首先** 下载合适的代理工具，比如[ClashMetaForAndroid](https://github.com/MetaCubeX/ClashMetaForAndroid/releases/download/v2.11.1/cmfa-2.11.1-meta-arm64-v8a-release.apk)

**然后** 打开代理工具（ClashMetaForAndroid）并进行以下操作：

**导入文件** 配置-右上角+-从文件导入，导入[botcheck.yaml](https://github.com/WHStudio/WZRY-BotCheck/blob/main/botcheck.yaml)文件，保存。

**开始使用** 回到代理工具首页开启代理，必须使用规则模式，节点选择DIRECT。

**测试效果** 默认拦截了部分网址供测试（比如[360.cn](https://360.cn)，具体看配置文件），请在浏览器中测试它们，打不开就是已生效。

**最后一步** 打开游戏，开一局排位（理论上人机最多），检查是否生效，效果如图（我方两个人机，敌方全是人机）：

![](https://290f154.webp.li/202410271435087.jpg)

## 原理

利用ClashMeta的分流功能，拦截人机头像域名(sgameicon.ecology.smoba.qq.com)。

所有流量均在本地处理，比使用他人提供的DNS更安全，不会泄露隐私信息。

如果你有自己的路由器或者DNS，则直接拦截指定域名更方便。
