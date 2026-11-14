# Thesis Draft · 假装在写论文

单文件网页（`index.html`）：伪装成在线 LaTeX 编辑器或 Word 文档。随便敲键盘，光标就会按节奏自动打出预先存好的论文，包括公式、表格和图，右侧 PDF 预览会自动重新编译。

- 任意键：写论文（每次按键吐出的字数可调）
- `F2`：设置（切换伪装界面、换论文内容或粘贴自己的 .tex、调节速度/错字/停顿、键盘音效）
- `F4`：自动打字（不用按键）　`F8`：静音　`F9`：全屏伪装　`Ctrl+S`：重新编译/保存　`Esc`：关闭设置
- 左侧文件树可以点开 refs.bib、配图等文件；编译日志会带几个警告；设置里有“今日摸鱼战报”

## 不用 Claude 怎么打开

1. **下载直接用**：把 `index.html` 存到电脑上，双击用浏览器打开（公式和字体需要联网）。
2. **公开网址（GitHub Pages）**：在仓库 Settings → Pages 里，Source 选 “Deploy from a branch”，分支选 `claude/vigilant-edison-q05d30`、目录 `/ (root)`，保存。一两分钟后可以访问 https://felix-dev-x.github.io/app/ 。
