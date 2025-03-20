# moyu-mini-app

# 摸鱼时长统计 Mini App

一个基于 Telegram Mini App 的摸鱼时长统计工具，让摸鱼更有趣！

## 功能特点

- 🕒 实时统计摸鱼时长
- 📊 个人摸鱼排行榜
- 🔔 群组摸鱼通知
- 🎮 有趣的交互体验
- 📱 完美适配移动端

## 技术栈

- 后端：Flask + SQLite
- 前端：HTML + CSS + JavaScript
- 机器人：Telegram Bot API
- 部署：Python + Gunicorn

- 搭建用宝塔就可以搭建了
- .env里面填写配置文件，也就是机器人token和群组id
  然后宝塔点击python项目 安装python3.12选中目录
  启动命令 python3 app.py
  然后绑定域名开启外网映射，申请一个ssl就行了。
