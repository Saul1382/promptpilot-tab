# PromptPilot Tab

<p align="center">
  <a href="https://www.youtube.com/watch?v=gl7XjzoNPHM">
    <img src="assets/readme/promptpilot-tab-demo.jpg" width="100%" alt="PromptPilot Tab 将模糊想法整理为五模块提示词，并通过 Tab 插入 AI 对话框">
  </a>
</p>

<p align="center">
  <strong>把模糊想法变成清晰、可编辑、可直接使用的提示词。</strong>
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/promptpilot-tab/onlkbnbjokbjbbhmaodfiejfbpldnjjo">Chrome 商店安装</a> ·
  <a href="https://promptpilot-tab.com">官方网站</a> ·
  <a href="https://www.youtube.com/watch?v=gl7XjzoNPHM">56 秒产品演示</a> ·
  <a href="https://github.com/Saul1382/promptpilot-tab/discussions">交流与问答</a> ·
  <a href="https://github.com/Saul1382/promptpilot-tab/issues/new/choose">反馈问题</a> ·
  <a href="README.en.md">English</a>
</p>

PromptPilot Tab 是一款面向主流人工智能（Artificial Intelligence，AI）对话网站的浏览器提示词增强扩展。写下想法后，它会先生成可编辑的“角色 / 目标 / 背景 / 要求 / 输出”五模块预览；确认无误，再按 `Tab` 插入当前对话。内容不会自动发送。

```text
写下想法 → 五模块预览 → 检查或修改 → 可选 AI 优化 → 按 Tab 插入
```

## 先看真实效果

点击上方主视觉可观看完整宣传片：[YouTube 产品演示](https://www.youtube.com/watch?v=gl7XjzoNPHM)。

### 本地生成，先改再插入

基础本地规则无需登录、无需配置模型。五个模块都可以直接编辑，确认后才插入对话框。

![PromptPilot Tab 本地生成五模块提示词并通过 Tab 插入](assets/screenshots/01-local-five-modules.png)

### 主动选择 AI 优化

快速、适中、复杂三档模式可按任务调整，并支持优化前后对比；用户自带密钥（Bring Your Own Key，BYOK）只保存在当前浏览器。

![PromptPilot Tab 三档 AI 优化、前后对比与自定义模型](assets/screenshots/02-ai-optimization.png)

### 推荐更匹配的模板

识别当前任务分类和标签后，优先展示更匹配的精选模板，而不是只按热度排序。

![PromptPilot Tab 根据当前任务推荐匹配模板](assets/screenshots/03-template-recommendation.png)

### 社区模板与本地模板

浏览、搜索和收藏社区模板，也可以把自己的常用提示词保存在本地，继续编辑和复用。

![PromptPilot Tab 社区模板与本地模板库](assets/screenshots/04-community-local-library.png)

### 支持 12 个主流 AI 对话网站

在 ChatGPT、Claude、Gemini、DeepSeek、Kimi、通义千问、腾讯元宝、豆包、Grok、Perplexity、NotebookLM 和 Google AI Studio 中保持一致的预览与插入流程。

![PromptPilot Tab 支持的 12 个 AI 对话网站](assets/screenshots/05-twelve-ai-sites.png)

## 当前获取方式

PromptPilot Tab 已在 Chrome Web Store 公开发布：[前往官方商店安装](https://chromewebstore.google.com/detail/promptpilot-tab/onlkbnbjokbjbbhmaodfiejfbpldnjjo)。请勿从非官方来源下载安装包。

如果你想关注后续更新，可以为本仓库点亮 **Star**，或在 [Discussions](https://github.com/Saul1382/promptpilot-tab/discussions) 中交流。

## 隐私与控制

- 基础本地功能无需登录，离线也能使用。
- AI 优化只在用户主动选择后运行。
- 插入前可以检查和修改，PromptPilot Tab 不会替你自动发送消息。
- BYOK 配置和应用程序编程接口密钥（Application Programming Interface Key，API Key）只保存在当前浏览器。

完整说明请查看[隐私政策](https://promptpilot-tab.com/privacy)。

## 交流、提问与反馈

- 使用问题、经验分享和开放讨论：[GitHub Discussions](https://github.com/Saul1382/promptpilot-tab/discussions)
- 可复现的问题和功能建议：[GitHub Issues](https://github.com/Saul1382/promptpilot-tab/issues/new/choose)
- 国际用户社区：[Discord](https://discord.gg/WEKBT36Q8U)
- QQ 交流群：`1106177594`
- 小红书账号：`517411810`
- 联系邮箱：[support@promptpilot-tab.com](mailto:support@promptpilot-tab.com)

<p>
  <img src="assets/community/qq-group.jpg" alt="PromptPilot Tab QQ 交流群二维码，群号 1106177594" width="160">
  <img src="assets/community/xiaohongshu-profile.jpg" alt="PromptPilot Tab 小红书账号二维码，账号 517411810" width="160">
</p>

提交公开内容前，请先删除提示词、账号、邮箱、API Key 和其他私人信息；安全问题请通过支持邮箱私下报告。

## 关于本仓库

这是 PromptPilot Tab 的公开产品展示与社区仓库，不包含产品源代码，也不接受源代码拉取请求（Pull Request，PR）。私密开发仓库与本仓库完全分离。

本仓库公开可见不等于开源授权。品牌、文案、截图、视频和其他媒体素材仍保留全部权利，详情见 [NOTICE](NOTICE.md)。
