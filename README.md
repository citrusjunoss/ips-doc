# 快速开始

推荐安装 `docsify-cli` 工具，可以方便创建及本地预览文档网站。

```bash
npm i docsify-cli -g
```

## 初始化项目

如果想在项目的 `./docs` 目录里写文档，直接通过 `init` 初始化项目。

```bash
docsify init ./docs
```

## 开始写文档

初始化成功后，可以看到 `./docs` 目录下创建的几个文件

- `index.html` 入口文件
- `README.md` 会做为主页内容渲染
- `.nojekyll` 用于阻止 GitHub Pages 会忽略掉下划线开头的文件

直接编辑 `docs/README.md` 就能更新网站内容，当然也可以[写多个页面](zh-cn/more-pages.md)。

## 本地预览网站

运行一个本地服务器通过 `docsify serve` 可以方便的预览效果，而且提供 LiveReload 功能，可以让实时的预览。默认访问 http://localhost:3000 。

```bash
`docsify serve docs`
```

## 在线预览
[在线预览](https://citrusjunoss.github.io/vue-rules-doc/)


?> 更多命令行工具用法，参考 [docsify-cli 文档](https://github.com/docsifyjs/docsify-cli)。
