# ocr

图片文字识别工具，基于 Tesseract OCR 引擎。支持从 URL 或 base64 图片中提取文字内容。

HologramAgent 插件，随 SDK `1.0.0` 的示例插件拆分而来。

## 构建

```bash
hmapdev build
```

产物 `dist/ocr_bundle.hmap` 经 `plugin_install` 安装。

## 自动更新

本仓库地址登记在 `plg.json` 的 `repo` 字段，安装后随产物写入
`plugin.json` 的 `repository` 字段 —— 内核的 `plugin_update` 靠它
从本仓库拉最新源码并重编安装。
