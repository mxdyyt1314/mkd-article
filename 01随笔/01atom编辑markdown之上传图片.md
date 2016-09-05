## atom编辑markdown-图片上传

因为对markdown比较感兴趣，所以一直想找一款能够实现本地化的markdown编辑器，先后用过vscode、cmdmarkdown，也因为各种问题而弃坑。我对markdown编辑器的要求有两点：

1. 支持基本的markdown语法
2. 能够自动化上传图片
3. 预览效果比较美观，这个比较主观。

先说下vscode，首先预览效果不是太满意，感觉不太好看，这个当然是很主观的看法。第二个，就是没找到上传图片的相关插件。

而cmdmarkdown用了一段时间，感觉bug还是挺多的，而且因为是完全基于html的，所以用的时候感觉反应比较迟钝。

于是，我把目光转向了atom，据说是个利用插件基本能实现基本上所有效果的编辑器。这篇文章就是利用atom来写的，文章目的主要是想告诉大家用atom来一键上传图片的方法。

首先，先上一张效果图：

![atom markdown效果图](http://occldmzoz.bkt.clouddn.com/ebec9ccf715e76ab9ac37000eed48533.png)

怎么样，看起来是不是很漂亮。

#### 1. 注册七牛账号

这里就不写怎么注册了，网址放出来

[七牛官方网址](https://portal.qiniu.com/signin)

#### 2. 下载qiniu-uploader插件

![qiniu-uploader](http://occldmzoz.bkt.clouddn.com/9f605c5ac7a985bf5f5de064294f1d27.png)

安装好`qiniu-uploader`后，先要对其进行设置，主要设置四个参数：

![设置参数](http://occldmzoz.bkt.clouddn.com/8ecc7f47f62a6c17e0a1250bea7e7638.png)

#### 3.下载markdown-assistant插件

接下来下载`markdown-assistant`插件并安装，设置的时候发现，会让你填一个上传插件，而且默认已经帮你填好了`qiniu-uploader`，其实你也就什么都不用设置了。

![uploader](http://occldmzoz.bkt.clouddn.com/ce974616d49dd7e610493ea7c348b938.png)

---

这些做完以后，让我们来试一下吧，用qq截图，然后直接在`atom`中`ctrl+v`粘贴，弹出上传图片提示，会让你填写一个title，点击enter会自动构建一条markdown图片语句。这样上传图片就完成了，是不是很简单！

![上传图片效果](http://occldmzoz.bkt.clouddn.com/438d297e438de9c41f14ee308d5612f9.png)

