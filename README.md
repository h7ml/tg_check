# TG-Signer Action

[![check](https://github.com/h7ml/tg_check/actions/workflows/check.yml/badge.svg?branch=main)](https://github.com/h7ml/tg_check/actions/workflows/check.yml)

一个基于 GitHub Actions 的 Telegram 签到自动化工具。

## 功能特点

- 自动运行 Telegram 签到
- 支持定时执行（每天 14:00 UTC+8）
- 自动记录签到日志
- 支持手动触发运行
- 支持自定义 Python 版本

## 目录结构

```bash
.
├── .github
│   └── workflows
│       └── check.yml      # GitHub Actions 工作流配置
├── .signer
│   ├── me.json           # Telegram 账号配置
│   ├── latest_chats.json # 最近聊天记录缓存
│   └── signs
│       └── my_sign
│           ├── config.json     # 签到配置
│           └── sign_record.json # 签到记录
├── my_account.session_string # Telegram 会话字符串
├── main.py                   # 主程序
└── README.md                 # 项目说明
```

## 配置说明

### 配置文件示例

`.signer/me.json`:

```json
{
  "session_string": "YOUR_SESSION_STRING",
  "api_id": "YOUR_API_ID",
  "api_hash": "YOUR_API_HASH"
}
```

`.signer/signs/my_sign/config.json`:

```json
{
  "sign_name": "my_sign",
  "chat_ids": [],
  "schedule": ""
}
```

## 使用方法

1. Fork 本仓库
2. 配置必要的 Secrets
3. 启用 GitHub Actions
4. 等待自动运行或手动触发

## 日志记录

- 签到日志将以 Markdown 格式保存
- 日志路径格式：`YYYY/MM/DD.md`
- 自动提交并推送日志文件
