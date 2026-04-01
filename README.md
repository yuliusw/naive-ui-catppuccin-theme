# naive-ui-catppuccin-theme

基于 Catppuccin 暗色系的 Naive UI 主题配色  
A Catppuccin dark-based theme palette for Naive UI

- Naive UI GitHub: https://github.com/tusen-ai/naive-ui
- Catppuccin GitHub: https://github.com/catppuccin/catppuccin

## 简介 | Overview

- 这是一个为 Naive UI 的 Catppuccin 暗色主题 json 包。
- 你可以将主题 JSON 文件导入 Naive UI 官方主题编辑器进行实时预览；也可以在项目中通过 themeOverrides 直接应用。
  
- These are Catppuccin dark themes for Naive UI.
- You can import the theme JSON into Naive UI’s official theme editor for live preview, or use it directly in your project via themeOverrides.

## 在线预览 | Live Preview

- 打开 Naive UI 主题编辑器: https://www.naiveui.com/zh-CN/os-theme
- 点击右下角“调色板”按钮，选择“导入”，上传本仓库的 JSON 主题文件，即可预览效果。

- Open Naive UI Theme Editor: https://www.naiveui.com/en-US/os-theme
- Click the palette icon at the bottom-right, choose “Import”, then upload the JSON theme file from this repo to preview.


## 使用方法 | How to Use

参考 Naive UI 主题配置文档：  
- 中文: https://www.naiveui.com/zh-CN/os-theme/docs/customize-theme  
- English: https://www.naiveui.com/en-US/os-theme/docs/customize-theme

1) 在根组件使用 NConfigProvider 引入暗色主题与主题覆盖  
- Wrap your app with NConfigProvider, apply darkTheme and theme overrides
