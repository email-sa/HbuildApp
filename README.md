## 使用Hbuild 打包vue项目

打开hbuildx，新建一个5+App项目

然后修改项目中生成的index.html文件内容，填写需要访问的网址，填写测试连接就是打包测试包，也可以打包发布包

根据项目修改manifest.js 的文件配置

以上配置好之后，原生APP云打包，就可以生成Android或是iOS安装包

具体安装步骤可以看 [用HbuildX打包vue 项目为App](https://blog.csdn.net/weixin_44514665/article/details/103213980).

错误文件运行后的页面截图

![加载失败的页面截图](/error.png)
设置文件运行后的页面截图

![设置页面的截图](/set.png)


### 本项目使用说明

- 克隆项目到本地
- 然后用hbuildx 导入项目
- 修改index.html 和error.html 里面的项目链接
- 然后打包即可

