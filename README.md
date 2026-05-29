# 觅星小臣 — AI 智能求职助手

一站式求职效率工具，让求职更高效、更智能。

## 功能

- **AI 简历分析** — 六维度评分，智能诊断简历亮点与短板
- **AI 简历优化** — 专业表达改写，STAR 法则重构
- **岗位收集** — 浏览器扩展一键采集招聘信息
- **投递追踪** — 可视化看板管理求职进度

## 下载安装

前往 [Releases](https://github.com/xiao-chen-ai/seeking-stars/releases) 页面下载最新版 `觅星小臣.dmg`，双击挂载后拖入 Applications 即可。

## 浏览器扩展

| 扩展 | 说明 |
|------|------|
| [job-collector-extension](./job-collector-extension) | Chrome 岗位收集扩展 |
| [boss-extension](./boss-extension) | BOSS 直聘专用扩展 |
| [job-collector-v2.js](./job-collector-v2.js) | 油猴脚本（Tampermonkey） |

加载方式：Chrome 地址栏输入 `chrome://extensions` → 打开"开发者模式" → 加载已解压的扩展程序。

## 技术栈

- 前端：Vue 3 + TypeScript + Element Plus + Vite
- 后端：Flask + SQLAlchemy + SQLite
- AI：接入硅基流动（SiliconFlow），支持 DeepSeek / Qwen / GLM / Kimi 等模型
- 桌面版：PyInstaller 打包为 macOS .app / .dmg

## 注意事项

- 桌面版目前仅支持 macOS
- AI 功能需要配置自己的 API Key（硅基流动免费注册获取）
- 数据存储在本地 `~/.seeking-stars/career_ai.db`

---

觅星小臣 © 2026 | 让求职更高效
