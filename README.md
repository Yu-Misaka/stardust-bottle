# Stardust Bottle

个人外观配置备份。这里只存放可公开同步的主题、配色和字体设置；不要提交 API key、访问令牌、账号信息或本机绝对路径。

## 目录

- `vscode/themes/`：VS Code 主题配色与字体
- `vscode/background/`：壁纸插件的可公开同步参数，不含图片路径
- 未来可并列增加 `kitty/themes/` 等应用目录

## VS Code

- [`vscode/themes/dark-modern-current.jsonc`](vscode/themes/dark-modern-current.jsonc)：创建仓库时从本机 `settings.json` 提取的 Dark Modern 配色与字体基线（60 个界面配色键、8 条语法规则）。
- [`vscode/themes/night-rose.jsonc`](vscode/themes/night-rose.jsonc)：为壁纸设计的「夜蔷薇」主题方案，包含工作台、语法、语义高亮配色，并继承旧版字体和关键词斜体。
- [`vscode/background/night-rose-fullscreen.jsonc`](vscode/background/night-rose-fullscreen.jsonc)：建议的壁纸不透明度 `0.24`；只合并该字段，保留个人设置中的 `images` 路径。

两套主题是并列方案。使用时选择一套，将其中的主题与外观设置合并到个人 `settings.json`；不要直接覆盖整个文件，以免丢失其他个人设置。壁纸片段只更新已有 `background.fullscreen` 对象里的 `opacity`。

夜蔷薇当前将编辑器、侧栏、活动栏、面板、标题栏、标签栏和状态栏等大面积底层统一设为纯黑；选中、悬停和弹窗仍保留紫色层次。壁纸不透明度建议值为 `0.24`，可按实际观感微调。Background 插件的全屏壁纸叠在整个界面上方，所以即使底层纯黑，图片仍可能影响文字观感。壁纸文件及 `background.fullscreen` 的本机图片路径不在仓库中。扩展自绘界面可能不会采用全部 VS Code 主题颜色。
