# soft-and-hard
《软硬结合——从零打造物联网》，软硬件结合可以说是所有硬件开发人员心中的一大追求，当一个人技能树上点亮了软硬件，所有创意想法基本都能靠自己去实现。 __如果你想支持这个免费的网络教程，请在github上给我一个关注的星星以示支持__ 


[软硬结合 在线浏览网址:`https://www.scaugreen.cn/posts/44755/`](https://www.scaugreen.cn/posts/44755/)

---

![](http://ww1.sinaimg.cn/large/005BIQVbgy1fz6du0ubg4j31hc0q27a9.jpg)

## 教程简介
### 教程目标
制作并演示一个物联网系统是怎么跑起来的，介绍如何学习相关知识。
### 教程内容
- 硬件上选择价格便宜(淘宝价十几块钱)的NodeMCU开发板，使用Arduino进行开发。
- 物联网你还得先懂网，在教程中简单介绍了计算机网络基础知识、TCP/IP协议、HTTP协议、MQTT协议等等。
- Web上选择了无所不能的JavaScript，在教程中将会演示其在网页开发、小程序开发、桌面应用开发、服务器后端服务开发。
- 整个教程里，推荐先用后学，先把项目跑起来看看效果，再按需学习相关知识，直到自己能把项目写出来。
- demo1演示了最简的系统，实现软件显示硬件的数据，可控制硬件执行动作。
![demo1示例](http://ww1.sinaimg.cn/large/005BIQVbgy1fzboqhds5sj30lu0co75a.jpg)
- 在demo1的基础上，demo2添加了MongoDB数据库、实时显示数据（websocket协议）、数据可视化(Echart图表)功能。
![demo2主要流程图](http://ww1.sinaimg.cn/large/005BIQVbgy1fzbotaayifj30lu0coab7.jpg)
## 其它说明
本教程是基于hexo博客系统搭建的，所以也可以理解为IOT博客，上面写了物联网教程《软硬结合》以及一系列相关文章。
<!-- - 这个教程之前是要本地浏览的形式做的，需要读者先clone此项目到本地，才能进行阅读，但发现好多新手会卡在github上。[旧版教程备份（已弃用）-百度云](https://pan.baidu.com/s/1TcUtfI5hFedj_RL6j8QacQ)
- 为了降低阅读门槛，我重新制作并发布在线教程。[软硬结合-在线访问](https://www.scaugreen.cn/posts/44755/) -->

### 文件目录说明
- 基础教程 : 各基础教程代码。详情查看该目录下的README.md。
- demo1 ：demo1的源代码，详情查看该目录下的README.md。
- demo2 : demo2的源代码，包含微信小程序、electron源代码，详情查看该目录下的README.md。
- pm2.json : 使用pm2启动时的配置文件`pm2 start pm2.json`，启动前需要先安装项目依赖。

### 端口使用情况
- base-tcp1: 9001 （方便TCP基础学习时抓包所用。）

- demo1-tcp: 9002
- demo1-http: 8001

- demo2-tcp: 9003
- demo2-http: 8002
<!-- 因为微信小程序正式发布后通信是需要SSL证书，所以申请了证书并在nginx进行了配置，可访问[https://sh.scaugreen.cn](https://sh.scaugreen.cn) -->

