# Pikpak
Docker 部署 Pikpak 网页客户端。

端口：8080



- 本仓库 Fork 自 [ykxVK8yL5L / pikpak ](https://github.com/ykxVK8yL5L/pikpak)。由于我不用 Koid，所以移除了相关插件。

- 网页版源码替换至：https://github.com/tjsky/pikpak。
- 服务器方面用 go 的 gin 框架。

- 没有 push 到 docker hub，有需要自行 build。



跟原版相比，在推送到 aria2 的提示消息后增加计数器。个人认为，这对于下载拥有数十个甚至上百个文件的蓝光原盘非常有必要。

只修改了 list.vue 文件 ，所以就只上传它了。

![预览](https://github.com/J0ins08/pikpak/blob/main/preview/截屏2022-12-27%2014.02.16.png)


# 如不能登录 就是配置里代理失效 需要走流量登录后设置里修改为可用代理
