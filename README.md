# 🍣 Cloudflare Worker Sushi 自动注册脚本

**一键部署 · 自动注册 · 订阅链接生成**

一个高效便捷的 Cloudflare Worker 脚本，可自动注册 Sushi 账号并生成订阅链接，适合搭配 Clash、V2Ray、Sing-box 等客户端使用。

---

## 📌 简介

本项目通过 Cloudflare Worker 实现 Sushi 账号的自动化注册，每次访问 Worker URL 时会自动创建一个新账号，并返回可用的订阅内容。

无需服务器、无需数据库，部署简单，免费使用。

---

## ⚡️ 部署步骤

### 1. 登录 Cloudflare
访问 [Cloudflare Dashboard](https://dash.cloudflare.com/) 并登录你的账号。

### 2. 创建 Worker
- 在左侧导航栏点击 **Workers & Pages**
- 点击 **Create application**
- 选择 **Create Worker**
- 输入 Worker 名称（推荐：`sushi-reg`、`sushi-auto` 等），然后点击 **Deploy**

### 3. 编辑代码
- 部署完成后，点击 **Edit Code** 进入代码编辑器
- 删除编辑器中所有默认代码
- 将 `cf_worker_sushi.js` 文件中的全部代码复制并粘贴到编辑器中

### 4. 保存并部署
- 点击右上角的 **Save and deploy** 按钮
- 等待部署成功

---

## 🚀 使用方法

部署完成后，你会获得一个 `.workers.dev` 结尾的 URL，例如：