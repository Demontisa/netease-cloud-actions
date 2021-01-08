# 网易云音乐升级全家桶 - 企业微信机器人推送版

<p align="center">
    <a href="https://github.com/Demontisa"><img alt="Author" src="https://img.shields.io/badge/author-Demontisa-blueviolet"/></a>
    <img alt="PHP" src="https://img.shields.io/badge/code-Python-success"/>
</p>
通过调用官方接口，每天自动刷完300首歌，借此可以达到快速升级的目的。

一个账号平均耗时为1分钟左右。放在服务器运行即可不需要人工干预，支持无服务器的云函数部署，每天自动听歌做任务，向你的企业微信发送任务通知。

------

#### 本项目由[netease-cloud](https://github.com/ZainCheung/netease-cloud) 修改而来，感谢作者提供代码！

### 使用文档: https://zaincheung.gitee.io/netease-cloud



目前已实现功能：


- [x]  每天自动升级
- [x] 任务进度推送到企业微信
- [x] 自定义网易云日推风格

本项目实则由三个项目组成，分别是：

- 给账号升级的Python项目：[netease-cloud](https://github.com/ZainCheung/netease-cloud)

- 使用PHP搭建的API接口：[netease-cloud-api](https://github.com/ZainCheung/netease-cloud-api)

- 使用Python开发的修改日推（每日推荐歌曲）Windows软件：[netease-cloud-fast](https://github.com/ZainCheung/netease-cloud-fastplay)
