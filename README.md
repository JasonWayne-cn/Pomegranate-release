# Pomegranate 发布仓库

石榴（Pomegranate）— 智能桌面文档应用。本仓库存放自动更新清单（`update.json`），安装包托管在 GitHub Releases。

## 最新版本: v2.2.0

| 平台 | 下载链接 |
|------|---------|
| Windows x64 | [Pomegranate_2.2.0_x64-setup.exe](https://github.com/JasonWayne-cn/Pomegranate/releases/download/v2.2.0/Pomegranate_2.2.0_x64-setup.exe) |

> 全部版本：https://github.com/JasonWayne-cn/Pomegranate/releases

## 版本历史

### v2.2.0 (2026-11-22)

- 左侧页面归并：查询与标签归入「文档」，推送、记忆卡片分别收进首页与 AI 问答
- 主功能合并为文档、日记、待办、AI 问答四大项
- 增强 AI 智能体能力
- 扩展 PPT 制作，新增助研插件
- 设置按功能模块划分，补充使用说明与页面导航

## 项目结构

```
update.json      # Tauri 自动更新清单（签名取自 CI 产物）
README.md
```

安装包由 GitHub Actions 构建并上传至源码仓库的 Releases。本仓库的 `update.json` 为
应用内自动更新的发现端点（Gitee 主 + GitHub 备）。
