# sesese-se

一个优雅的 Pixiv 图片展示网站，使用 Astro 构建。

## 特点

- 🎨 优雅的图片展示界面
- 🔄 自动获取 Pixiv 图片
- 📱 响应式设计
- 🚀 基于 Astro 构建
- 🤖 使用 GitHub Actions 自动部署

## 样式参考

本站样式参考于 [Artab](https://github.com/get-artab/artab)，一个展示世界名画的新标签页扩展。

## 开发工具

大部分的代码编写工作由 [Cursor](https://cursor.sh) 完成，这是一个强大的 AI 驱动的代码编辑器。

## 开始使用

1. 克隆仓库
```bash
git clone https://github.com/yourusername/sesese-se.git
cd sesese-se
```

2. 安装依赖
```bash
npm install
```

3. 启动开发服务器
```bash
npm run dev
```

4. 构建生产版本
```bash
npm run build
```

## 配置

1. 在 `src/content/images/pixiv` 目录下创建作品目录，目录名为作品ID
2. 将图片文件命名为 `作品ID_页码.jpg` 格式
3. 在 `src/content/config.ts` 中配置作品信息

## 部署

本站使用 GitHub Actions 自动部署到 Vercel。每次推送代码到 main 分支时，都会自动触发部署。

## 许可证

MIT 