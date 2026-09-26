# Stardust Bottle

个人外观配置备份。这里只存放可公开同步的主题、配色和字体设置；不要提交 API key、访问令牌、账号信息或本机绝对路径。

## 目录

- `vscode/themes/`：VS Code 主题配色
- 未来可并列增加 `kitty/themes/` 等应用目录

## VS Code

`vscode/themes/night-rose.jsonc` 是基于 **Dark Modern** 的「夜蔷薇」主题片段，包含工作台、语法高亮和语义高亮配色。

使用时，将文件中的三个颜色自定义对象合并到个人 `settings.json` 的同名设置项，并选用 `"workbench.colorTheme": "Dark Modern"`。不要直接用此片段覆盖整个 `settings.json`，以免丢失其他个人设置。

壁纸文件及 `background.fullscreen` 的本机图片路径不在仓库中。扩展自绘界面可能不会采用全部 VS Code 主题颜色。
