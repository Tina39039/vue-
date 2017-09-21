# vue-
## 什么是vue.js<br>
vue.js是一套构建用户界面的渐进式前端框架。<br>
vue.js提供了MVVM数据绑定和一个可组合的组件系统，具有简单、灵活的API。<br>
vue.js的特点是：<br>
* 数据绑定<br>
  比如你改变一个input标签中的值，会自动同步更新到页面上其他绑定改输入框的组件的值<br>
* 组件化<br>
  页面上小到一个按钮都可以是一个单独的文件.vue,这些小组件直接可以想乐高积木一样通过相互引用而组装起来。<br>
## 环境安装<br>
* Mac OS 系统安装brew<br>
打开终端运行一下命令：<br>
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"<br>
* Mac OS 系统安装nodejs<br>
brew install nodejs<br>
用 npm install npm@3.10.3 更新 npm 版本报错:<br>
(node:42) fs: re-evaluating native module sources is not supported.<br>
解决方法：<br>
在官网上下载6.70的安装包在安装一次（升级到最新的npm)<br>
* Windows 系统<br>
直接下载安装包即可<br>
linux下可以使用apt-get（ubuntu） 或 yum（centos） 命令安装。<br>
具体可参考：http://www.runoob.com/nodejs/nodejs-install-setup.html<br>
* 获取nodejs模块安装目录访问权限<br>
sudo chmod -R 777 /usr/local/lib/node_modules/<br>
* 安装webpack<br>
cnpm install webpack -g<br>
* 安装vue脚手架<br>
npm install vue-cli -g<br>
* 在硬盘中找到一个文件夹放在工程用，在终端中进入该目录<br>
cd 目录路径<br>
* 根据模板创建项目<br>
vue init webpack-simple 工程名字(不能用中文）<br>
一些初始化设置可直接按回车默认<br>
* cd命令进入创建的工程项目<br>
工程目录如图所示：<br>



