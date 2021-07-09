# gitbook安装

## 安装node.js

1. 访问官方网站[node.js](https://nodejs.org/en/)

   ![LOGO](https://nodejs.org/static/images/logo.svg)

2. 选择node.js 6.17.1

   - [Other Downloads](https://nodejs.org/en/download/current/)
   - [Previous Releases](https://nodejs.org/en/download/releases/)
   - [Downloads](https://nodejs.org/download/release/v6.17.1/)

3. 安装

   点击next。

4. 检查

   命令行模式下，执行`node -v`，出现版本号v6.17.1。

   <iframe src="//player.bilibili.com/player.html?aid=248661453&bvid=BV1Uv411p7Sg&cid=354986296&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

   

## 安装git

## 安装gitbook

# gitbook常用命令

# gitbook插件

## 目录折叠

* gitbook init主目录下新建book.json

* 打开文件book.json，增加代码：

  ```
  {
  	"plugins": [
  	"expandable-chapters"
  	]
  }
  ```

* 主目录下用命令行执行gitbook install，会生成node_modules文件夹，配置的插件也会自动下载到该目录下。

* 配置目录

  在SUMMARY.md文件中配置目录时直接配置目录名称即可，不用配置连接地址，如下:

  ​		[目录名称] ()

  启动后查看即可达到预期。





