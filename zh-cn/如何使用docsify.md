# docsify部署笔记到GitHub
## 新建文件
建文件夹
npm i docsify-cli -g 安装
docsify init ./XXX 初始化
git init git初始化
git add "a.md"
git add "--all"
git status
docsify serve 部署本地
git commit -m "demo" 本地仓库
git remote add origin https://github.com/JackLee1417/JackLee1417.github.io.git github连接
git push -u origin master 提交

## 省略<!-- {docsify-ignore} -->