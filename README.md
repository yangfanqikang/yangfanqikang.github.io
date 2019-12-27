# Hello zzr 
## 一.share project 到github
## 二.根据vuepress手册配置环境:
### 1.README.md
### 2.文件夹.vuepress/config.js:
`base:/项目名/` 两条斜杠不可少
## 三.deploy.sh配置
---如果发布到 https://<USERNAME>.github.io/<REPO> 这里尤其重要,需要配置github的权限---
### GitHub如何配置SSH Key---https://blog.csdn.net/u013778905/article/details/83501204   
git push -f git@github.com:yangfanqikang/zzr-vue-components-1.git master:gh-pages
