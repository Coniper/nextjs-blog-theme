# Next.js 博客模板存档

这个仓库不是我从零写的项目，而是保存的一份开源博客模板，原项目为 [Netlify 的 nextjs-blog-theme](https://github.com/netlify-templates/nextjs-blog-theme)，由 Bejamas 设计。我把来源写清楚，免得以后自己或者别人误认。

它使用 Next.js、React、Tailwind CSS 和 MDX，带有示例文章、页面布局与 Netlify 相关配置。想研究静态博客的代码结构，可以从 `pages`、`components`、`posts` 这几个目录入手。

本地运行的基本步骤：

```bash
npm install
npm run dev
```

然后在浏览器访问 `http://localhost:3000`。这些命令取自项目脚本，我没有在当前环境重新验证构建。

原作者、贡献者和许可证信息以仓库中的 `package.json`、`LICENSE` 以及[上游项目](https://github.com/netlify-templates/nextjs-blog-theme)为准。这里只作为模板参考，不当作我的原创作品。
