# 🌿 绿源智能 · 全屋智能产品图鉴

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Type: Static Site](https://img.shields.io/badge/Type-Static%20Site-blue.svg)](index.html)
[![3D](https://img.shields.io/badge/3D-Viewer-000000.svg)](index.html)
[![Theme](https://img.shields.io/badge/Theme-Light%2FDark-success.svg)](index.html)
[![Deploy](https://img.shields.io/badge/Deploy-ywswyz.xyz-blue.svg)](https://ywswyz.xyz/lvyuan-smart-clean-v3/)
[![English](https://img.shields.io/badge/Docs-English-blue.svg)](README.en.md)

> 绿源智能（智能家居硬件）的**产品图鉴**交付物：以产品展示为核心，顶部三产品标签切换 + 实时 3D + 明暗双主题，离线双击即可运行。

## ✨ 项目简介

绿源智能面向 25–45 岁、注重生活品质的城市家庭用户，主营智能门锁、智能照明、智能安防。本仓库是其品牌官网的**产品图鉴版**交付物，专注于让访客快速浏览三条产品线的外观与核心卖点，并引导留资咨询。

🌐 线上演示：<https://ywswyz.xyz/lvyuan-smart-clean-v3/>

## 🧩 核心特性

- 🔖 **三产品标签切换**：顶部智能门锁 / 智能照明 / 智能安防一键切换。
- 🧊 **实时 3D 展示**：拖拽旋转、滚轮缩放，查看产品细节。
- 🌗 **明暗双主题**：右上角太阳/月亮按钮切换浅色 / 深色模式。
- 📩 **留资入口**：左侧「免费获取全屋方案」咨询卡片。
- 🔤 **自托管字体**：`assets/` 内置多语言 Web 字体（Fraunces / Instrument Sans / Inter 的 woff/woff2），离线可用。

## 🚀 快速开始

```bash
# 方式一：双击 index.html（Windows 用户也可双击 open-offline.bat 一键打开），用较新的 Chrome / Edge / Safari 打开
# 方式二：放到任意 Web 服务器目录下访问 index.html
```

无需安装依赖、无需启动服务器、无需联网。建议浏览器支持 WebGL。

## 📂 目录结构

```text
lvyuan-smart-clean-v3/
├─ index.html       # 站点本体
├─ assets/          # 自托管 Web 字体与脚本（多语言 woff/woff2）
├─ images/          # 产品与界面图片
├─ 使用说明.txt      # 使用说明
├─ LICENSE
├─ README.md        # 本文件（中文）
└─ README.en.md     # English
```

## 🛠️ 技术栈

- 纯静态前端（HTML / CSS / 原生 JavaScript）
- 实时 3D 产品查看器
- 自托管 Web 字体，离线可用

## 📡 部署

将整个目录部署到任意静态服务器根路径下的 `lvyuan-smart-clean-v3/` 子目录即可。线上示例托管于 `ywswyz.xyz`。

> ⚠️ **演示声明**：产品价格、咨询热线与表单均为**演示占位**；表单不会发送真实数据。正式上线前需替换为真实信息并接入真实留资系统。

## 📄 许可

[MIT](LICENSE) © 2026 skywalkerqqq
