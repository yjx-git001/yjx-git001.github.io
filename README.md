# Claude Code / Codex CLI 安装使用页

这个仓库现在是一个纯静态说明页，内容聚焦在：

- Claude Code 的多平台安装与使用
- Codex CLI 的多平台安装与使用
- OpenAI 兼容接入示意
- CCSwitch 的 macOS / Linux / Windows 配置切换

## 当前页面内容

- Codex CLI
  macOS / Linux、Windows PowerShell 的 npm 全局安装与启动方式
- Claude Code
  macOS / Linux、Windows 的原生安装与 npm 全局安装方式
- Claude Code API 配置
  `ANTHROPIC_BASE_URL=https://yjxapi-gpt.xyz`
  `ANTHROPIC_AUTH_TOKEN=xxx`
- 接入示意
  `API Key / Base URL / Model` 示例卡片
- CCSwitch
  保留平台 switch，并继续使用 `https://yjxapi-gpt.xyz/v1`

## 本地查看

直接打开 `index.html`，或者启动最简单的静态服务：

```bash
python -m http.server 8080
```

## 页面约定

- 页面里展示的密钥均为占位符，不放真实 key
- Claude Code 配置地址使用 `https://yjxapi-gpt.xyz`
- OpenAI 兼容接入与 CCSwitch 使用 `https://yjxapi-gpt.xyz/v1`

## 参考文档

- https://developers.openai.com/codex/cli
- https://developers.openai.com/codex/cli/features
- https://nodejs.org/en/download
- https://git-scm.com/downloads/win
- https://code.claude.com/docs/en/quickstart
- https://code.claude.com/docs/en/getting-started
