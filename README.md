# PC HTML 原型评审助手

面向产品经理的 Codex Skill：读取业务规则和 PC HTML 原型，生成评审提纲，并注入可拖拽、可标注、可持续保存的原型评审助手。

当前公开版本：`v1.1.8`

## 下载

请从 [Releases](https://github.com/liyangxu219318-bot/pc-html-review-assistant-release/releases/latest) 下载：

- `pc-html-review-assistant-v1.1.8.zip`
- 对应的 `.sha256` 校验文件

## 安装

1. 解压 ZIP。
2. 将 `pc-html-review-assistant` 目录复制到：

```text
%USERPROFILE%\.codex\skills\pc-html-review-assistant
```

3. 在 Codex 中使用 `$pc-html-review-assistant` 调用。

## 包含内容

- 完整 `SKILL.md` 和 Codex 元数据
- 评审助手 Demo、冻结注入片段和机器人图标
- 确定性注入、冻结及测试脚本
- 评审数据 Schema 与示例
- 原创、授权与使用免责声明

## 完整性校验

PowerShell：

```powershell
Get-FileHash .\pc-html-review-assistant-v1.1.8.zip -Algorithm SHA256
```

将结果与同名 `.sha256` 文件比对。

## 授权说明

本公开仓库仅用于提供版本下载和完整性校验。公开可见或允许下载不代表本项目已经开源，也不构成商用、复制、修改、分发或再许可授权。下载、安装或使用前请阅读 [NOTICE.md](./NOTICE.md)；需要其他授权时，应取得权利人的明确书面许可。

开发源仓库和完整版本历史保持私有，公开仓库仅发布经过校验的发行包。
