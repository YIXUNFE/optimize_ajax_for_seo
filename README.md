# optimize_ajax_for_seo
SEO，旁路服务优化 ajax 接口数据

本项目使用 NodeJs 运行 PhantomJs 获取客户端网页内容。其目标在于构建一套旁路服务，等待网页 ajax 获取数据并渲染至 HTML 后将网页内容返回给蜘蛛，以提高 SEO 效果。

方案参看：[SEO 优化，旁路服务处理 AJAX 数据](https://github.com/YIXUNFE/blog/issues/70)

## 安装

首先安装依赖，进入目录执行。

```javascript
npm install 
```

然后下载 [PhantomJs](http://phantomjs.org/download.html) 应用程序，放置在项目目录下。

<br />

## 运行

执行命令 

```javascript
node app.js
```

即可启动一个 web 服务。


在浏览器中打开网址，带上需要测试的网页地址即可。

```
http://localhost:3000/get?q=http%3A%2F%2Fwww.baidu.com
```

稍等一会页面就会返回对应的源码啦。

<br />

## Thanks

<br />



