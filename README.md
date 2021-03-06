# Bilibili Mac Client

An unofficial bilibili client for mac

![Build Status](https://app.ship.io/jobs/LajSkdYLuE7THK7n/build_status.png)

# Why

众所周知的原因，Flash 不支持硬解，Macbook 热的烤鸡蛋！

# Features
- 硬解播放
- libass 显示弹幕，超低 CPU 占用
- 自动拼接分段视频
- 视频缓冲过慢自动切换备用源

# Screenshot

![](http://ww2.sinaimg.cn/large/a74f330bjw1eqq21b23c7j21740npqbp.jpg)

# Download

[GitHub](https://github.com/typcn/bilibili-mac-client/releases)

[百度盘](http://pan.baidu.com/s/1eQvSx6i)

[Mega](https://mega.co.nz/#F!48gXiAxa!BFrmfzq9c97cfSbR4A1v8g)

# FAQ

Q: 提示应用程序已损坏

A: 请到设置 - 安全与隐私 - 通用 - 点击左下角的锁 - 允许任何应用

Q: 是否支持弹幕发送

A: 当前暂时不支持，下一个版本加入

Q: 程序为何会连接 app.eqoe.cn

A: 如果你选择了自动更新，系统会定时检查更新，建议您开启该选项。

Q: 如何关闭弹幕

A: 点击播放器右下角的字幕按钮关闭，再次点击开启

# Known problems

- 在视频开始播放之前，关闭窗口会导致程序在一段时间后崩溃
- 首次播放可能创建字体缓存，播放器唤醒时间过长，程序可能误判播放已完成，多等一会即可开始播放

# TODO

- [ ] 发送弹幕 (未完成)
- [ ] 防挡字幕 (未完成)
- [ ] 弹幕屏蔽 (未完成)
- [ ] 官方 API 无法解析时，切换到 flvcd 等第三方解析

# Thanks

- Bilidan
- mpv
- ISSoundAdditions
- Sparkle
- Danmaku2ass
- FFmpeg

# License

GPLv2