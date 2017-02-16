# sosout(个人博客)

## 前言
>  本工程主要基于NodeJS的前后端分离的思考与实践。

>  如果觉得不错的话，请star一下吧 😊

#####使用技术： 前端架构express + node + xtemplate + mockjs + modelproxy-copy，服务端架构nodejs + express
#####项目说明： 此项目是本人空余时间搭建的。希望大家提供宝贵的意见和建议，谢谢。
#####邮&emsp;&emsp;&ensp;箱： sosout@yeah.net
#####个人网站： http://www.sosout.com/
#####个人博客： http://blog.sosout.com/
#####个人简书： http://www.jianshu.com/users/23b9a23b8849/latest_articles
#####项目结构： 

|-- demo                         	 // 特殊功能单独示例
|-- myblog                           // 博客源码(http://blog.sosout.com/)技术架构：express + node + xtemplate + mockjs + modelproxy-copy
|-- sosout-admin                     // 博客后台源码nodejs + express
|-- static                           // 网站静态资源(http://www.sosout.com/)后台源码nodejs + express
|-- .gitignore                       // 配置不需要加入版本管理的文件
|-- 404.htmk                         // 网站404html文件(http://www.sosout.com/)
|-- index.html                       // 网站入口html文件(http://www.sosout.com/)
|-- nginx.node.conf                  // nodejs nginx 反向代理配置文件
|-- README.md                        // 说明
```


### 快速开始

```
# git clone
git clone https://github.com/sosout/sosout.git
 
# install dependencies
npm install

# serve at localhost:3000
npm start

# 访问路径
http://localhost:3000/
```

####历史更新
  *2016.12.18*

  	1. 初始化项目搭建;

  	2. 引入express作为博客后台地址;

  	3. 创建doc作为博文的详情目录(即所有的博文都链接github下的该名录，后期会进行改版)
