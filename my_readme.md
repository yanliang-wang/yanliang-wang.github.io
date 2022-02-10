## Pipeline to update

### 1. Modify locally

对master的源代码进行更新，通过下面的指令编译修改

```bash
p jekyll serve --config _config_dev.yml
```

在浏览器访问http://localhost:4000来查看修改后的效果，如果是想要的效果，就部署到github上

### 2. Deployment

本地部署

```
./bin/deploy
```

Github Action自动部署

应该是代码更新到master后，会进行部署

