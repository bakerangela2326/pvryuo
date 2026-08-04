蓝图平台开户【Q-——333307——】蓝图平台开户【 辋芷《888yx●vip》 】
蓝图平台开户【Q-——333307——】蓝图平台开户【 辋芷《888yx●vip》 】

 从0到1搭建个人博客网站：GitHub Pages + Hexo 完整教程（2025版）

你是否想过拥有一个完全属于自己的技术博客？不需要买服务器，不需要备案，甚至零成本就能搭建一个加载速度快、支持HTTPS的静态博客网站。今天，我将手把手教你用 GitHub Pages + Hexo 完成从环境配置到一键部署的全流程。

 为什么选择Hexo + GitHub Pages？

- 免费且稳定：托管在GitHub上，全球CDN加速，无需维护服务器。
- Markdown写作：专注内容，支持代码高亮，对程序员极其友好。
- SEO友好：纯静态页面，百度收录速度快，可自定义URL和站点地图。
- 主题丰富：数百款开源主题，几分钟即可完成个性化定制。

 第一步：环境准备（Node.js + Git）

1. 下载并安装 [Node.js](https://nodejs.org)（选择LTS版本）。
2. 安装Git，并配置好你的用户名和邮箱。
3. 检查环境：打开终端，输入 `node -v` 和 `git --version`，看到版本号即成功。

 第二步：安装Hexo并初始化博客

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo server
```

此时访问 `http://localhost:4000`，默认博客已启动。你可以在 `source/_posts` 文件夹中新建 `.md` 文件开始写文章。

 第三步：部署到GitHub Pages

1. 在GitHub上新建仓库，命名为 `用户名.github.io`。
2. 修改根目录下的 `_config.yml` 文件：
   ```yaml
   deploy:
     type: git
     repo: https://github.com/你的用户名/你的仓库.git
     branch: main
   ```
3. 安装自动部署工具：
   ```bash
   npm install hexo-deployer-git --save
   ```
4. 执行三连命令：
   ```bash
   hexo clean && hexo generate && hexo deploy
   ```

浏览器访问 `https://用户名.github.io`，你的个人博客就正式上线了！

 第四步：让百度收录你的博客

为了让博客更快被百度索引，建议完成以下操作：

1. 在 `_config.yml` 中开启 `url` 和 `root` 配置。
2. 安装SEO插件：
   ```bash
   npm install hexo-generator-seo --save
   ```
3. 在`source`目录下新建 `robots.txt`，并添加站点地图。

 常见问题与解决思路

- 部署后样式丢失：检查 `_config.yml` 中的 `root` 是否为 `/仓库名/`。
- 百度不收录：确保站点开启HTTPS，并在百度站长平台提交链接。
- 文章图片不显示：建议使用图床或相对路径。

 互动引导

搭建过程中你遇到了哪个问题？是部署失败、主题配置，还是关键词优化？欢迎在评论区留言，我会一一解答！如果你已经成功上线，也欢迎分享你的博客链接，一起交流进步。

---

如果你觉得这篇教程有用，请点赞、收藏并转发给你身边需要的朋友，让更多人实现创作自由的乐趣！

相关推荐：

https://github.com/gloverjoseph140/fniwrs/blob/main/2026%E5%AE%98%E6%96%B9%E7%83%AD%E7%82%B9%EF%BC%9A%E8%93%9D%E5%9B%BE%E7%BD%91%E5%9D%80%E7%BD%91%E5%9D%80_%E5%92%95%E8%BF%94%E6%B2%BC%E6%B8%A1%E6%80%9DYRLZG.md

<img src="https://i.postimg.cc/kGjWYk5W/lantu-00006.png" />

相关推荐：

https://github.com/gloverjoseph140/fniwrs/commit/2e4a6f644780ac98f34f9e704eea293336a00f9e

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />
相关推荐：

https://github.com/benderjessica393/clipwq/blob/main/2026%E5%AE%98%E6%96%B9%E7%83%AD%E6%A2%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E7%BD%91%E5%9D%80%E5%BC%80%E6%88%B7_%E7%89%8C%E6%81%8B%E5%90%AD%E6%88%8E%E4%BE%A0CWXEL.md

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />
相关推荐：

https://github.com/benderjessica393/clipwq/commit/146ff275b652036a68675881cf09510d43169c66

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
