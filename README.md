🍣 Cloudflare Worker 部署 Sushi 注册脚本指南 🍣
一键部署 · 自动注册 · 订阅链接生成

📌 简介：

本指南将引导您在 Cloudflare Worker 上部署一个自动注册 Sushi 账号并生成订阅链接的脚本。此方法高效便捷，可用于获取新的订阅内容。

⚡️ 部署步骤：

1. 登录 Cloudflare：
• 访问 Cloudflare 官网 并登录您的账号 。

2. 创建 Worker：
• 在左侧导航栏点击 Workers & Pages。
• 点击 Create application 按钮。
• 点击 Create Worker 按钮。
• 为您的 Worker 起一个名字（例如 sushi-reg），然后点击 Deploy。

3. 编辑代码：
• 部署成功后，点击 Edit Code 按钮进入在线编辑器。
• 将编辑器中原有的代码全部删除。
• 将您提供的 cf_worker_sushi.js 文件中的内容全部复制并粘贴进去。

4. 保存并部署：
• 点击右上角的 Save and deploy 按钮。
• 确认部署。

🚀 如何使用：

部署完成后，您会获得一个以 .workers.dev 结尾的 URL。

使用场景示例：
• 直接注册并获取订阅：
https://sushi-reg.yourname.workers.dev/

提示：您可以直接在浏览器访问该 URL ，或者将其作为订阅链接填入 Clash、V2Ray 等客户端中，每次请求都会自动触发一次新账号的注册并返回订阅内容。

#CloudflareWorker #Sushi注册 #订阅链接 #自动化脚本 #V2Ray #Clash
