# wechat_for_linux



## 更新

好好好，再也不骂腾讯和微信了，终于出了好用的官方版本微信了。

![image-20240314113430708](README/image-20240314113430708.png)



安装包丢在Releases中了，一共三个版本：

wechat-beta_1.0.0.145_amd64.deb

wechat-beta_1.0.0.150_arm64.deb

wechat-beta_1.0.1.212_loongarch64.deb



## 我可没骂过腾讯和微信

=================我是分割线============================

通过bwrap模拟来绕过系统限制的版本可通过应用商店一键下载，支持x86,arm,龙芯新世界的各种发行版

https://spark-store-project.gitee.io/spk-resolv/?spk=spk://store/chat/store.spark-app.wechat-linux-spark



http://archive.ubuntukylin.com/ubuntukylin/pool/partner/weixin_2.1.1_amd64.deb

root用户使用前需要修改`vim /usr/share/applications/weixin.desktop`增加--no-sandbox：

![image-20220104142528064](README/image-20220104142528064.png)

**其他内核版本的，arm版本的可参考**：https://github.com/lovechoudoufu/wechat_for_linux/issues/1
