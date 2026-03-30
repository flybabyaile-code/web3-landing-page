# 全链服务 | Web3 暗黑风格落地页

一个现代化的 Web3 服务展示页面，采用赛博朋克风格设计，提供一站式区块链解决方案。

## 🎨 设计特色

- **赛博朋克美学**：霓虹色彩、发光效果、扫描线动画
- **玻璃态效果**：现代化的毛玻璃设计风格
- **流畅动画**：多层次的交互反馈和过渡效果
- **响应式设计**：完美适配桌面、平板和移动设备
- **无障碍访问**：支持动画减速和深色模式

## ✨ 主要功能

### 导航栏
- 固定定位导航，支持平滑滚动
- Logo 悬停发光效果
- 链接下划线展开动画

### Hero 部分
- 大标题打字机动画
- 径向渐变背景光晕
- 呼吸灯发光效果

### 服务模块
- 6 个服务卡片展示
- 悬停上升和边框发光效果
- 顶部边框渐变动画

### 官方报价
- 价格方案网格展示
- 顶部渐变边框动画
- 底部边框宽度过渡效果

### 实时日志
- 模拟链上日志显示
- 日志行滑入动画
- 自定义滚动条样式

### 联系方式
- Telegram 集成
- 浮动按钮快速访问
- 响应式布局

## 🚀 快速开始

### 本地预览
直接在浏览器中打开 `index.html` 文件即可预览。

### GitHub Pages 部署

1. **创建 GitHub 仓库**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Web3 landing page"
   git branch -M main
   git remote add origin https://github.com/lybabyaile-code/web3-landing-page.git
   git push -u origin main
   ```

2. **启用 GitHub Pages**
   - 进入仓库设置 (Settings)
   - 找到 "Pages" 部分
   - 选择 "Deploy from a branch"
   - 选择 "main" 分支和 "/ (root)" 目录
   - 点击 "Save"

3. **访问您的网站**
   - GitHub Pages 会自动生成 URL：`https://lybabyaile-code.github.io/web3-landing-page`
   - 等待几分钟后即可访问

## 🎯 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 高级样式和动画
- **Google Fonts** - 专业字体
  - Orbitron - 标题字体
  - Share Tech Mono - 正文字体
  - Courier Prime - 代码字体

## 📊 浏览器兼容性

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- 移动浏览器（iOS Safari、Chrome Mobile）

## 🎨 自定义

### 修改颜色
编辑 `index.html` 中的 CSS 变量：

```css
:root {
  --neon: #00f0ff;           /* 主要霓虹色 */
  --neon-dark: #00d4e8;      /* 深霓虹色 */
  --neon-light: #33ffff;     /* 浅霓虹色 */
  --accent: #ff00ff;         /* 强调色 */
  --success: #00ff9f;        /* 成功色 */
}
```

### 修改内容
- 更新导航链接
- 修改服务卡片内容
- 调整价格方案
- 更新联系方式

### 修改动画
- 调整 `--transition` 的时间
- 修改 `@keyframes` 动画定义
- 改变 `animation-duration` 值

## 📱 响应式断点

- **桌面**：1200px+
- **平板**：768px - 1199px
- **手机**：< 768px

## ♿ 无障碍特性

- 支持 `prefers-reduced-motion` 媒体查询
- 支持 `prefers-color-scheme: dark`
- 语义化 HTML 标记
- 打印样式优化

## 🔧 优化建议

1. **添加 SEO**
   - 补充 meta 标签
   - 添加 structured data
   - 优化页面标题和描述

2. **性能优化**
   - 压缩 CSS
   - 延迟加载字体
   - 使用 CDN

3. **功能扩展**
   - 添加表单验证
   - 集成分析工具
   - 添加多语言支持

4. **用户交互**
   - 添加平滑滚动
   - 动态日志更新
   - 表单提交功能

## 📄 许可证

MIT License - 自由使用和修改

## 📞 联系方式

- Telegram: [@avetplogo](https://t.me/avetplogo)
- GitHub: [lybabyaile-code](https://github.com/lybabyaile-code)

## 🙏 致谢

感谢所有贡献者和用户的支持！

---

**最后更新**: 2026-03-30  
**版本**: 2.0  
**状态**: 生产就绪 ✅
