# 觅星小臣 — AI 智能求职助手

一站式求职效率工具，让求职更高效、更智能。

## 下载安装（macOS 桌面版）

前往 [Releases](https://github.com/xiao-chen-ai/seeking-stars/releases) 下载最新版 `觅星小臣.dmg`，双击挂载后拖入 **Applications** 即可。

首次打开若提示"无法验证开发者"，右键点击 App → 打开。

---

## 主要功能

- **AI 简历分析** — 六维度评分，智能诊断简历亮点与短板
- **AI 简历优化** — 专业表达改写，STAR 法则重构
- **岗位投递追踪** — 可视化看板管理求职进度
- **BOSS 直聘一键采集** — 浏览器脚本自动收集职位信息

---

## BOSS 直聘职位采集 — 使用教程

### 1. 安装脚本猫

首先在浏览器安装 **脚本猫** 插件：

- [Chrome / Edge](https://docs.scriptcat.org/docs/use/install/)
- 安装后在地址栏旁会出现 🐱 图标

### 2. 安装采集脚本

点击安装以下两个脚本：

| 脚本 | 安装链接 | 说明 |
|------|----------|------|
| 觅星小臣 - BOSS 沟通模板 | [安装](https://scriptcat.org/zh-CN/script-show-page/5970) | 自动填充打招呼模板，提高回复率 |
| 觅星小臣 - BOSS 职位收集器 | [安装](https://scriptcat.org/zh-CN/script-show-page/6435) | 一键采集职位信息，同步到桌面版 |

### 3. 开始使用

1. 确保 **觅星小臣桌面版已启动**（Dock 中运行）
2. 打开 [Boss 直聘](https://www.zhipin.com/) 沟通页面
3. 脚本会自动在页面添加操作按钮，点击即可一键采集

> 采集的职位数据会自动同步到桌面版的「投递追踪」页面，无需手动输入。

---

## AI 模型配置

桌面版内置硅基流动（SiliconFlow）接口，支持以下模型：

- **DeepSeek** — V4-Pro、V4-Flash、V3.2、R1 等
- **Qwen** — Qwen3.6、Qwen3.5 等
- **GLM** — GLM-5.1、GLM-4.7 等
- **Kimi** — Kimi-K2.6 等

### 获取 API Key

- **免费拿** — 打开应用点「找小臣」，免费获取
- **自己注册** — [硅基流动](https://cloud.siliconflow.cn/i/8Wt6MyMe) 注册即送免费额度

配置路径：打开桌面版 → 右上角 AI 设置 → 填入 API Key → 测试连接 → 保存。

---

## 注意事项

- 桌面版目前仅支持 macOS
- 数据存储在本地 `~/.seeking-stars/career_ai.db`，不上传服务器
- 采集脚本需要在 Boss 直聘的沟通页面（`zhipin.com/web/geek/chat`）使用
- 脚本采集时桌面版必须处于运行状态

---

觅星小臣 © 2026
