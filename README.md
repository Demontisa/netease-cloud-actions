# 网易云音乐升级全家桶 - 企业微信机器人推送版

<p align="center">
    <a href="https://github.com/Demontisa"><img alt="Author" src="https://img.shields.io/badge/author-Demontisa-blueviolet"/></a>
    <img alt="PHP" src="https://img.shields.io/badge/code-Python-success"/>
</p>
通过调用官方接口，每天自动刷完300首歌，借此可以达到快速升级的目的。

一个账号平均耗时为3-5分钟左右。程序在GitHub Actions里自动运行不需要人工干预，每天自动听歌做任务，向你的企业微信发送任务通知。

------

#### 本项目由[netease-cloud](https://github.com/ZainCheung/netease-cloud) 修改而来，感谢作者提供代码！


目前已实现功能：

- [x]  运行在GitHub Actions里
- [x]  每天自动升级
- [x] 任务进度推送到企业微信
- [x] 自定义网易云日推风格

本项目实则由三个项目组成，分别是：

- 使用PHP搭建的API接口：[netease-cloud-api](https://github.com/ZainCheung/netease-cloud-api)
