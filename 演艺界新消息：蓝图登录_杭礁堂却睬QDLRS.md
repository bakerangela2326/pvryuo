蓝图登录【Q-——333307——】蓝图登录【 辋芷《888yx●vip》 】
蓝图登录【Q-——333307——】蓝图登录【 辋芷《888yx●vip》 】

 从零搭建个人博客？GitHub Pages + Hexo 保姆级教程（附避坑指南）

还在羡慕大神的个人技术博客？其实，借助 GitHub Pages 和 Hexo，你也能在半小时内拥有一个完全属于自己、免费且支持自定义域名的静态博客。本文为你梳理从环境配置到部署上线的全流程，文末有互动彩蛋，记得看到最后。

 为什么选择 Hexo + GitHub Pages？

对于开发者而言，这套组合拳的优势非常明显：速度极快（纯静态页面）、无需服务器成本（托管在 GitHub）、版本管理方便（与 Git 无缝对接）。更重要的是，百度对静态站点有着极好的收录友好度，如果你注意关键词布局和内链建设，博客的 SEO 潜力巨大。

 第一步：本地环境准备

你需要 Node.js（建议 LTS 版本）和 Git。安装完成后，打开终端验证 `node -v` 和 `git --version`。

 第二步：Hexo 初始化与配置

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

修改 `_config.yml` 中的 title、description 和 keywords，这是百度收录的核心抓取点，务必包含“GitHub Pages”、“Hexo 教程”等目标关键词。

 第三步：一键部署到 GitHub

先在 GitHub 新建仓库（命名为 `你的用户名.github.io`），然后安装部署插件：

```bash
npm install hexo-deployer-git --save
```

编辑 `_config.yml` 底部 deploy 配置，填入仓库地址。执行 `hexo clean && hexo g && hexo d`，浏览器访问 `https://你的用户名.github.io` 即可看到站点。

 避坑指南（高频踩雷区）

1. 图片路径问题：建议使用绝对路径或图床，避免相对路径在首页失效。
2. 百度收录慢：记得在根目录添加 `baidu-site-verification` 验证文件，并主动提交 sitemap。

 互动引导

你的博客顺利上线了吗？在部署过程中遇到最头疼的问题是什么？欢迎在评论区留言，我会挑选高频问题在下期文章中详细拆解！

如果这篇教程帮到了你，点赞+在看 支持一下，让更多想搭建独立博客的朋友看到这篇指南。关注我，获取更多效率开发与 SEO 实战技巧。

相关推荐：

https://github.com/gloverjoseph140/fniwrs/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B1%87%E6%80%BB%EF%BC%9A%E8%93%9D%E5%9B%BE%E4%B8%BB%E7%AE%A1%E5%9C%B0%E5%9D%80_%E5%87%89%E6%BB%9E%E6%80%80%E4%B9%85%E7%AA%92IPWXZ.md

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />

相关推荐：

https://github.com/gloverjoseph140/fniwrs/commit/d3b62a15c1292720262b14ef5e5bf1ae32529f98

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />
相关推荐：

https://github.com/stanleykrystal60/anipll/blob/main/2026%E5%AE%98%E7%BD%91%E8%AE%B2%E8%A7%A3%EF%BC%9A%E8%93%9D%E5%9B%BE%E4%B8%BB%E7%AE%A1%E4%B8%8B%E8%BD%BD_%E6%8D%8C%E6%94%BE%E4%BD%B3%E6%A1%A5%E5%A3%81OOQDK.md

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />
相关推荐：

https://github.com/stanleykrystal60/anipll/commit/d90236a520263ea72fe494820049b946e13f1b0a

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
