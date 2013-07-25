bleed-baidu-white
==================

###榨干百度网盘计划

如果你自己写的App内有离线数据需要下载，但又像我一样一穷二白买不起类似又拍云的云存储服务。

那就跟我一起来榨干百度网盘吧！

###计划步骤：

1	将目标文件上传到百度网盘，并且分享之

2	获取到链接中的ID和UK值

3	App内构造链接并且发送请求

4	接收JSON格式真实下载地址

5	开始下载吧！


###部署
系统已经部署到 [http://daimajia.duapp.com](http://daimajia.duapp.com)

###用法

1	提取分享链接中的 id 和 uk

2	构造请求链接： http://daimajia.duapp.com/$id/$uk

3	请求地址，获取json格式返回数据

4	获取json中的真实下载地址

###Demo

Step:1 提取链接中的id,uk 

如： http://pan.baidu.com/share/link?shareid=445495&uk=2150962024 

id = 445495 / uk = 2150962024 

Step:2 构造链接 
http://daimajia.duapp.com/baidu/id/uk 

上面例子的id/uk填入，即： [http://daimajia.duapp.com/baidu/445495/2150962024](http://daimajia.duapp.com/baidu/445495/2150962024)

Step3:程序中发送请

Step4:获取Json格式真实地址

###还在犹豫什么？投入使用吧！

###关于我：
我是个学生，酷爱开发，擅长Android、php、python、nodejs、web，如果您手头有适合我的实习机会，欢迎邮件联系我:  [daimajia#gmail.com](mailto:daimajia@gmail.com)

*	[西北大学](http://zh.wikipedia.org/wiki/%E8%A5%BF%E5%8C%97%E5%A4%A7%E5%AD%A6_\(%E4%B8%AD%E5%9B%BD\))
*	北京师范大学
*	我的站点: [Daimajia](http://www.zhan-dui.com)
*	我的微博:[代码家](http://weibo.com/daimajia)
*	Twitter:[LinHuiwen](http://twitter.com/LinHuiwen)
*	Instagram:[daimajia](http://instagram.com/daimajia)

你也可以留意[我的Android项目](https://github.com/xuanqinanhai/little-bear-dictionary)

