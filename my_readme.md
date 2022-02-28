## Prerequisites
参考：

- [github.io的介绍说明](https://pages.github.com/)，[github.io的官方教程](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
- [jekyll tutorial](https://www.taniarascia.com/make-a-static-website-with-jekyll/)，[使用jekyll搭建github.io中文简单教程](https://blog.csdn.net/tyyytcj/article/details/80880018)，[github官方教程](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)，[jekyll官网](https://jekyllrb.com/)
- [jekyll主题网站](http://jekyllthemes.org/)，[jekyll github topic](https://github.com/topics/jekyll-theme)
- [demo1](https://engcang.github.io/), [demo2](https://epsavlc.github.io/)

教程可以主要参考[jekyll tutorial](https://www.taniarascia.com/make-a-static-website-with-jekyll/)

## Pipeline to update

[使用的模板demo](https://maruan.alshedivat.com/)

### 1. Modify locally

对master的源代码进行更新，通过下面的指令编译修改

```bash
p jekyll serve --config _config_dev.yml --trace
```

在浏览器访问http://localhost:4000来查看修改后的效果，如果是想要的效果，就部署到github上

### 2. Deployment

本地部署

将代码更新到master分支之后，执行下面的语句进行部署
```
./bin/deploy
```

## 3. Other options

- 修改字体

  https://github.com/alshedivat/al-folio/discussions/265