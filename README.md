# Stardust Bottle

个人外观配置备份。这里只存放可公开同步的主题、配色和字体设置；不要提交 API key、访问令牌、账号信息或本机绝对路径。

## 目录

- `vscode/themes/`：VS Code 主题配色
- 未来可并列增加 `kitty/themes/` 等应用目录

## VS Code

- [`vscode/themes/dark-modern-current.jsonc`](vscode/themes/dark-modern-current.jsonc)：从当前本机 `settings.json` 提取的 Dark Modern 配色与字体快照（60 个界面配色键、8 条语法规则）。
- [`vscode/themes/night-rose.jsonc`](vscode/themes/night-rose.jsonc)：为壁纸设计的「夜蔷薇」主题方案，包含工作台、语法和语义高亮配色。

两个文件是并列方案。使用时选择一套，将其中的主题与外观设置合并到个人 `settings.json`；不要直接覆盖整个文件，以免丢失其他个人设置。

壁纸文件及 `background.fullscreen` 的本机图片路径不在仓库中。扩展自绘界面可能不会采用全部 VS Code 主题颜色。
