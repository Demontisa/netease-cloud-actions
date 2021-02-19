# 网易云音乐自动打卡签到 - Actions

<p align="center">
    <a href="https://github.com/Demontisa"><img alt="Author" src="https://img.shields.io/badge/author-Demontisa-blueviolet"/></a>
    <img alt="PHP" src="https://img.shields.io/badge/code-Python-success"/>
</p>
通过调用官方接口，每天自动刷完300首歌，借此可以达到快速升级的目的。

一个账号平均耗时为3-5分钟左右。程序在GitHub Actions里自动运行不需要人工干预，每天自动听歌做任务，向你的企业微信发送任务通知。

------

#### 本项目由[netease-cloud](https://github.com/ZainCheung/netease-cloud) 修改而来，感谢作者提供代码！


目前已实现功能：

- [x] 运行在GitHub Actions里
- [x] 每天自动升级
- [x] 任务进度推送到企业微信
- [x] 自定义网易云日推风格

本项目使用方法：

- Fork 本项目，不要忘记给我点个start哦(;´༎ຶٹ༎ຶ`)
- 在Fork来的项目里点击`Setting --> Secrets --> Actions`
- 点击 `New repository secret` 新建以下Secret
    - `Name` 值为 `ACCOUNT` `Value` 值为 `网易云音乐账号(手机号/网易邮箱)`
    - `Name` 值为 `PASSWORD` `Value` 值为 `网易云音乐密码(md5)` 如需使用明文请修改init.config
    - `Name` 值为 `API` `Value` 值为 `API接口URL` 需自行搭建API接口：[netease-cloud-api](https://github.com/ZainCheung/netease-cloud-api)
    - `Name` 值为 `KEY` `Value` 值为 `企业微信机器人https://qyapi.weixin.qq.com/cgi-bin/webhook/send?key=48af13**************`中的`48af13**************`企业微信机器人创建方法需自行百度
- 点击 `Actions` 再点击 `I understand my workflows, go ahead and enable them`
- 首次使用需手动点击一次 `Start`
