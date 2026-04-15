# Codex 使用文档页

这个仓库已经从原来的个人主页，改成了一个纯静态的 **Codex 说明页**。

目前首页包含这些内容：

- Codex CLI 的安装与首次启动
- `~/.codex/config.toml` 的基础配置
- `gpt-5.4` 等模型的推荐与切换方式
- VS Code / 兼容客户端的接入说明
- CCSwitch 的 macOS、Linux、Windows 配置示例

## 本地查看

直接打开 `index.html`，或者启动一个最简单的静态服务：

```bash
python -m http.server 8080
```

## 当前改动重点

- 整站内容已换成 Codex 文档展示
- 原个人主页逻辑已经移除
- 页面底部增加了 CCSwitch 配置区
- CCSwitch 里的请求地址已替换为 `https://yjxapi-gpt.xyz/v1`
- 页面里的 API key 只保留占位符，避免泄露真实密钥

## 参考文档

- https://developers.openai.com/codex/quickstart
- https://developers.openai.com/codex/auth
- https://developers.openai.com/codex/config-basic
- https://developers.openai.com/codex/models
- https://developers.openai.com/codex/ide
- https://developers.openai.com/codex/cli/reference
