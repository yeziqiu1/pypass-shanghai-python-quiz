# PyPass 上海 Python 二三级刷题库

面向上海市高等学校信息技术水平考试 Python 程序设计及应用（二三级）的离线刷题工具。

## 在线访问

GitHub Pages 部署完成后访问：

https://yeziqiu1.github.io/pypass-shanghai-python-quiz/

## 功能

- 500 道练习题，覆盖 12 个考试知识模块
- 单选、程序填空、编程自评
- 知识点全文查询与易错点清单
- 错题本、收藏、掌握标记
- 按考试时间自动生成每日计划
- 知识点笔记、题目笔记和自由笔记本
- AI 学习助教，可配置 DeepSeek、通义千问、Kimi、Ollama 或自定义 OpenAI 兼容接口
- 支持安装到手机主屏幕，离线使用

## 手机安装

- iPhone：用 Safari 打开后，点“分享” -> “添加到主屏幕”
- Android：用 Chrome 打开后，点菜单 -> “安装应用”或“添加到主屏幕”

## 数据说明

刷题记录、收藏和笔记保存在当前浏览器本地。换设备前请使用“数据与设置”里的导出备份功能。

AI API Key 只保存在浏览器本地，不会写入本仓库。公开部署时不要把自己的 API Key 提交到 GitHub。

## 文件

- `index.html`：支持 PWA 安装的手机/电脑版本
- `desktop.html`：单文件电脑版
- `manifest.webmanifest`：PWA 配置
- `service-worker.js`：离线缓存
- `icons/`：应用图标
