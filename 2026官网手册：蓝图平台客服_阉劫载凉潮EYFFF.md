蓝图平台客服【Q-——333307——】蓝图平台客服【 辋芷《888yx●vip》 】
蓝图平台客服【Q-——333307——】蓝图平台客服【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hugo 保姆级教程

> 想拥有一个免费、高速、完全属于自己的博客？本文带你用 GitHub Pages 和 Hugo，30 分钟上线个人网站，告别繁琐的服务器和域名配置。

 为什么选择 GitHub Pages + Hugo？

GitHub Pages 提供免费静态托管，稳定且支持自定义域名；Hugo 是号称“全球最快”的静态站点生成器，秒级构建。两者搭配，零成本、高可定制，非常适合开发者、写作爱好者和技术博主。

本教程面向 GitHub 新手，即使你刚注册账号，按步骤操作也能成功。

 第一步：环境准备与仓库创建

1. 安装 Git：官网下载，命令行输入 `git --version` 验证。
2. 注册 GitHub 并创建仓库，仓库名必须为 `你的用户名.github.io`，勾选 Public。
3. 安装 Hugo：macOS 用 `brew install hugo`，Windows 下载 exe，安装后运行 `hugo version` 确认。

 第二步：本地生成站点并关联远程仓库

打开终端，执行以下命令：

```bash
hugo new site myblog
cd myblog
git init
git remote add origin https://github.com/你的用户名/你的用户名.github.io.git
```

 第三步：选择主题并配置

在 [Hugo Themes](https://themes.gohugo.io/) 选择一个简洁主题，比如 `LoveIt` 或 `PaperMod`。将主题下载到 `themes` 目录，然后在 `config.toml` 中启用。小技巧：修改 `baseURL` 为 `https://你的用户名.github.io/`，并设置 `title` 为你的博客名称。

 第四步：发布文章与自动部署

创建`hugo new posts/first-post.md`，用 Markdown 写内容，头部 `draft: false` 后即可发布。

推荐操作：用 GitHub Actions 实现自动部署。在仓库 `.github/workflows` 下新增 `deploy.yml`，推送 `main` 分支后，GitHub 会自动构建并部署博客，无需手动执行命令。

 第五步：绑定自定义域名（可选）

在仓库设置 `Pages` 面板中填写你的域名，并在 DNS 服务商添加 `CNAME` 记录指向 `你的用户名.github.io`，即可实现免费 HTTPS + 专属域名访问。

 常见问题排查

- 页面 404：检查仓库名是否完全匹配用户名，等待 1-2 分钟再访问。
- 样式丢失：确认 `config.toml` 中的主题路径正确，且 `baseURL` 结尾带 `/`。

---

互动引导：你的博客建成后，欢迎在评论区分享域名，或提问搭建中遇到的任何问题，我会逐一解答。

延伸阅读：想了解 Hugo 的 SEO 优化？关注我，下期分享如何让博客被搜索引擎快速收录。如果本文对你有帮助，请点赞、转发支持一下，你的鼓励是持续输出的动力！

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E5%AE%98%E7%BD%91%E4%B8%A5%E9%80%89%EF%BC%9A%E4%B9%90%E5%AF%8C%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E6%9D%86%E8%8B%B9%E6%8E%B3%E4%BA%BF%E5%9C%86KQETA.md

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/bda649a25ded32d64c201e4b5fe1ec90a6a9bdca

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/blob/main/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97%EF%BC%9A%E4%B9%90%E5%AF%8C%E6%B3%A8%E5%86%8C%E5%9C%B0%E5%9D%80_%E6%9E%B7%E6%AF%8F%E9%97%B2%E9%A5%B6%E4%BB%BFIPJKS.md

<img src="https://i.postimg.cc/c4bQRyjk/lantu-00008.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/commit/fee87d8afac3206e17831e85c9dc4dd0a21e3b7f

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
