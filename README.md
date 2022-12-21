利用iOS端 safari浏览器的全屏规则，添加到手机主屏后模拟出app样式。

原理很简单，只是一个网页，加入了全屏规则，内容都是图片。

欢迎有能力的同志对代码进行加强。

全屏规则
```js
//*yes为允许全屏
<meta name="apple-mobile-web-app-capable” content=“yes” />
//*设置顶部的bar为黑色背景色
<meta name="apple-mobile-web-app-status-bar-style” content=“black”/>
//*顶部bar颜色
<meta name="theme-color" content="#010737">
//*桌面图标
<link rel="apple-touch-icon” sizes=“114x114” href=“./img/icon.png”/>
```

##文件为纯静态网页形式，

##可以自己部署在vercel上或者4everland上均可，当然也可以直接上传至自己的服务器或者虚拟主机上。
