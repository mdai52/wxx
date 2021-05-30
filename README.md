![](https://files.mdnice.com/user/164/42f70c6b-f984-4787-ae4c-cc86041900b6.png)

## 目录

[TOC]

## 一键添加源地址

[添加到 Sileo](sileo://source/https://twjacy.github.io/wx/)

[添加到 Cydia](cydia://url/https://cydia.saurik.com/api/share#?source=https://twjacy.github.io/wx/)

[添加到 Zebra](zbra://sources/add/https://twjacy.github.io/wx/)

[添加到 Installer](installer://add/repo=https://twjacy.github.io/wx/)

## 前言

Jan 微信插件 1.5.9-6 版本功能之多，深受广大用户喜欢，但是由于开发者丢失源码，不得不重头再来，1.5.9-6 版本已无法再更新，所以有了新的 WeChat 1.0 版本，具体功能如下图以及下文所述。

注：由于插件名称为 WeChat 容易混淆，个人为了区别且功能属于微信增强，个人命名为 WeChat Plus，与开发者无关。

## 更新记录

1.0.4 更新日志

1. 消息功能增加未接视频自动回复，未接语音自动回复；
2. 新增菜单功能，微信主界面右上角 `+` 号可选增加清理未读消息、一键删除所有会话、解析短视频（无水印下载短视频）；
3. 自动功能增加抢红包功能；
4. 朋友圈功能增加朋友圈评论通知、朋友圈评论回复、朋友圈自动点赞、常驻后台；
5. 新增 `#选择` 命令，恢复人物语音；
6. 新增聊天界面语音增加到语音包；
7. 恢复短视频链接转语音，部分短视频链接无法转语音，暂时无解；
8. 新增文字 +1、语音 +1、表情 +1 菜单图标，文字转语音菜单图标，视频转语音、转发朋友圈菜单图标，语音试听、添加至语音包菜单图标；
9. 授权版语音包图标自定义路径及文件名称：`微信文档目录/Library/Caches/VoiceBao/Voice.png` ，深色模式图标名称为 `Voice_Dark.png`，自定义语音包图标需放两个文件。

1.0.3 更新日志

- 兼容 libhooker 基板；
- 修复朋友圈转发闪退问题；
- 修复聊天界面长按文件、图片、语音闪退问题；
- 修复点歌功能，乱触发问题；
- 修复点击猜拳骰子会出现微信卡死或闪退问题；
- 修复发送语音包内语言，未回到聊天界面问题；
- 修复进群欢迎，无法选择加入的群问题；
- 删除 1-15 号人物，文字转语音之前请再次设置；
- 恢复语音试听功能；
- 语调、语速设置功能取消；
- 新增自动功能，具体功能详见思维导图或下文叙述。

> 如果你发现什么问题，也可以添加我的微信进行反馈，我将整理后反馈给开发者，毕竟我能遇到的问题有限，感谢。

## 杂项功能

- 自定义步数
  - 运动步数设置
  - 最低随机步数设置
  - 最高随机步数设置
- 自定义零钱
  - 娱乐功能
- 支付加锁
- 收藏加锁
- 朋友圈加锁
  - 开启加锁功能的前提是开启锁屏功能。
- CallKit
  - 像接电话那样接听微信语音
- 显示微信号
  - 显示群友微信号，即使没有添加好友。
- 自动确认登录
  - PC 端或者 iPad 登录微信，手机端自动确认。
- 好友快速备注
  - 在对话框中发送：#备注+空格+备注名，即可完成备注。
- 猜拳骰子作弊
  - 娱乐功能
- iPad 登录
  - 模拟 iPad 登录，开启后将导致朋友圈无法选择视频，订阅号文章排版改变
- 禁止下拉小程序
- 禁止下拉视频动态
- 屏蔽自己输入状态
  - 对方无法看到你的输入状态，保留对方的输入状态

## 消息功能

- 消息防撤回
- 保留聊天记录
- 自定义小尾巴
  - 小尾巴来源设置
  - 小尾巴内容设置
- 关键字回复
  - 模糊匹配/完全匹配
  - 关键字设置
  - 回复内容设置
- 自动回复
  - 回复内容设置
- 未接视频自动回复
  - 回复内容设置
- 未接语音自动回复
  - 回复内容设置

## 群功能

- 伪装群主
- 伪装群管理
- 群公告
  - 批量发布创建的群聊公告
- 群解散
  - 批量解散创建的群
- 群退出
  - 批量退出加入的群
- 群踢人
  - 仅适用群主及群管理：@群友+空格+踢
- 关键字踢人
  - 设置群
- 进群欢迎
  - 欢迎内容设置
- @所有人
  - 非公告形式，非群主、管理员@所有人形式，是真的@所有人
- 屏蔽@我

## 菜单功能

- 清理未读消息
- 一键删除所有会话
- 解析短视频
  - 无水印短视频下载

## 自动功能

- 红包详情
  - 点开红包后在左侧显示详情
- 自动抢红包
- 抢自己红包
- 抢个人红包
- 防止同时抢多个红包
- 抢到红包自动回复
- 延迟抢红包
- 不抢指定群红包
- 不抢关键字红包
- 后台推送已抢金额通知
- 抢到红包语音播报
- 红包统计
- 自动接收转账
- 接受转账语音播报
- 收款后自动回复
  - 回复内容设置
- 自动通过好友
- 通过好友自动回复
  - 回复内容设置

## 朋友圈功能

- 朋友圈转发
  - **可发长视频，收费功能**。
  - 安卓设备可以查看完整视频，苹果未越狱设备只能查看 30 秒
- 屏蔽原作者
- 隐藏朋友圈可见图标
- 朋友圈原图
  - 朋友圈发图默认选择原图
- 查看已删除评论
- 小视频进度条
  - 播放小视频显示进度条
- 小视频30秒
- 观看完整视频
- 朋友圈广告
  - 屏蔽朋友圈广告
- 朋友圈评论通知
- 朋友圈评论回复
- 朋友圈自动点赞
- 常驻后台

## 语音功能

- 点歌
  - 目前仅支持网易云音乐
- MP3转语音
- MP4转语音
- 转发音乐
- 短视频链接转语音
  - 支持抖音、快手、皮皮虾中复制链接在聊天中粘贴发送即可
- 文字转语音
  - 支持命令，查看命令：#语音命令 或 #命令
  - 文字转语音字数限制最多 300 字
- 长按文字转语音
- 左滑文字转语音
  - **点歌、MP3 转语音、MP4 转语音、转发音乐、短视频链接转语音、文字转语音、长按或左滑文字转语音为收费功能。**
- 右滑文字引用
- 语音转发
- 转发收藏
- 语音+1
- 文字+1
- 表情+1
- 语音秒数
  - 可设置发送语音秒数：1-60
- 语音包
  - 授权版本地语言包文件放至微信文档目录：/Libray/Caches/VoiceBao/新建文件夹/，支持语音包分类
  - 免费版本地语言包文件放至微信文档目录：/Libray/Caches/Voice/
- 语音包试听
  - 首先发送一条语音给自己，长按改语音，点击试听，让第一条语音作为试听载体，发送语音前请先清空记录

## 动态视频

- 播放声音
- 选择视频
  - 从相册选择视频，或者视频文件放至微信文档目录：/Libray/Caches/，命名为 backgoup.mp4

## 点击复制

- 复制注册码
- 绑定微信号，不支持换绑

![](https://files.mdnice.com/user/164/20ae1e39-21db-427a-812f-51c3f30679fd.png)

## 兼容性

- Chimera/Odyssey/Taurine 越狱设备，需安装 libhooker Configurator 插件，设置 Jan WeChat 为 Substrate 兼容模式。

![](https://files.mdnice.com/user/164/8be352d2-5f78-438c-910d-ef477d2a59b8.JPEG)

> 如果在默认 libhooker 默认模式下出现使用某项功能导致微信闪退，请务必切换至 Substrate 兼容模式。设置完成后，请注销设备，以确保设置生效。

## 语言包下载

- 下载地址：https://wwr.lanzoui.com/b0dqw3rda
- **密码:4ckk**

##  购买授权

- 关于授权，目前是新版发布特惠，35RMB 绑定微信号，不支持更换微信号。

TG：[https://t.me/twjacy](https://t.me/twjacy)

![](https://files.mdnice.com/user/164/044478ed-f4f1-47ff-8c9c-40eeeae9f487.png)

主要微信：

![](https://files.mdnice.com/user/164/da1725b6-e875-4855-b1b8-de8c3c105391.png)

备用微信：

![](https://files.mdnice.com/user/164/c6d2efc9-50fd-434b-9495-67242cce67e4.jpg)


## 授权之后

- 上滑微信退出后台，再次进入；
- 插件开关都有相关功能说明，在开启之前请查看；
- 文字转语音开启后，请先设置人物以及语音秒数；

## 广而告之

**憨憨&亦欢 UDID 定制**

- 身边没有电脑，无法续签？
- 手机忘记续签，超过 7 天？
- 不仅仅是 UDID 定制，更是提供交流的平台；
- 包含掉签修复、后期更新维护、售后服务；
- 50/年（不排除随着市场价格波动）

![](https://files.mdnice.com/user/164/61cac610-2f94-47a1-a4fc-1f62adcad5f8.png)

![](https://files.mdnice.com/user/164/4813b140-6793-4c05-8530-0386f77756b3.png)

