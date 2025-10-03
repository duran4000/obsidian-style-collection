# Obsidian 样式集合

精心设计的 Obsidian 笔记应用样式主题集合，为你的笔记添加专业美观的视觉效果。

🌐 **[在线演示网站](https://duran4000.github.io/obsidian-style-collection)**

## 包含的样式

### 1. Monokai Dark 代码块主题
- **文件**: `monokai-dark-codeblock.css`
- **描述**: 基于经典的 Monokai 配色方案，为 Obsidian 代码块提供专业的语法高亮显示
- **特点**:
  - 准确的语法高亮颜色
  - 深色背景减少视觉疲劳
  - 支持多种编程语言

### 2. 彩虹辉光跑马灯分割线
- **文件**: `rainbow-glow-marquee-hr.css`
- **描述**: 炫酷的彩虹色分割线，带有流动的跑马灯效果和动态辉光
- **特点**:
  - 彩虹色渐变效果
  - 流动的跑马灯动画
  - 动态辉光效果

## 如何在 Obsidian 中应用这些样式

### 方法一：通过 CSS 代码片段（推荐）

1. **打开 Obsidian 设置**
   - 点击左下角的设置图标
   - 或使用快捷键 `Ctrl + ,` (Windows/Linux) 或 `Cmd + ,` (Mac)

2. **找到外观设置**
   - 在左侧菜单中点击"外观"
   - 滚动到"CSS 代码片段"部分

3. **添加 CSS 文件**
   - 点击文件夹图标打开 CSS 代码片段文件夹
   - 将你想要的 CSS 文件复制到这个文件夹中
   - 例如：复制 `monokai-dark-codeblock.css` 到该文件夹

4. **启用样式**
   - 返回 Obsidian 设置的外观页面
   - 在 CSS 代码片段列表中，找到你添加的文件并启用开关
   - 重启 Obsidian 或重新加载 CSS 代码片段

### 方法二：直接添加到主题 CSS

1. **启用开发者模式**
   - 在设置中开启"开发者模式"

2. **打开主题 CSS 文件**
   - 按 `Ctrl + Shift + I` 打开开发者工具
   - 在"元素"面板中找到 `<style id="theme-css">`
   - 或者直接在 Obsidian 的配置文件夹中找到主题 CSS 文件

3. **添加样式代码**
   - 将 CSS 文件的内容复制到主题 CSS 文件中
   - 保存文件并重启 Obsidian

### 方法三：通过社区主题

如果你使用的是社区主题，可以将这些样式作为补充添加到你的主题中。

## 文件说明

- `monokai-dark-codeblock.css` - 代码块样式
- `rainbow-glow-marquee-hr.css` - 分割线样式
- `_config.yml` - GitHub Pages 配置文件
- `index.html` - 演示页面

## 自定义和修改

你可以自由修改这些 CSS 文件来满足你的个人需求：

- 调整颜色值来匹配你的主题
- 修改动画速度和效果
- 添加新的样式规则

## 贡献

欢迎提交 Pull Request 来添加新的样式或改进现有样式！

## 许可证

MIT License - 你可以自由使用、修改和分发这些样式。

---

**提示**: 在应用新样式后，建议先在一个测试笔记中预览效果，确保样式符合你的需求。