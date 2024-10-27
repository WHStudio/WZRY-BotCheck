# WZRY-BotCheck

利用ClashMeta有效拦截某moba排位赛人机头像

效果如图
![](https://290f154.webp.li/202410271435087.jpg)

首先，下载合适的代理工具，比如[ClashMetaForAndroid](https://github.com/MetaCubeX/ClashMetaForAndroid/releases/download/v2.11.1/cmfa-2.11.1-meta-arm64-v8a-release.apk)

然后，打开代理工具（ClashMetaForAndroid）并进行以下操作：

导入文件：配置-右上角+-从文件导入，导入botcheck.yaml文件，保存

开始使用：回到代理工具首页开启代理，必须使用规则模式，节点选择DIRECT

测试效果：默认拦截了360的部分网址供测试（具体看botcheck.yaml），请在浏览器中测试它们，打不开就是已生效

最后一步：打开某moba，开一局排位（人机更多），检查是否生效。
