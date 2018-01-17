小程序开发前端项目下载部署：

1、使用小程序开发框架wepy，因此第一步安装wepy  
 npm install wepy-cli -g
  

2、克隆项目
git clone git@github.com:silinabai/wepyTest.git  

3、切换到克隆项目的目录  
cd wepyTest

4、安装开发依赖  
npm install

5、编译源代码  
wepy build

6、开启实时编译  
wepy build --watch

7、编译后生成dist文件，用小程序开发者工具打开dist的项目，输入APPID，输入项目名称，打开可以看项目基础小程序  

8、在微信开发者工具-->详情里需要做以下步骤：  
<1> 关闭ES6转ES5。 重要：漏掉此项会运行报错。  
<2> 关闭上传代码时样式自动补全。 重要：某些情况下漏掉此项也会运行报错。  
<3> 关闭代码压缩上传。 重要：开启后，会导致真机computed, props.sync 等等属性失效。

完成以上步骤，小程序初始化完成。
