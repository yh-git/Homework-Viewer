# Homework-Viewer

 ***此项目已经随着校园网的更新而作废。不过校园网的登录流程和加密算法仍可以参考。如果您有继续使用的需求，请在issue中提出或直接联系我。feel free to fork this repo and make some changes.***
 
同一附（同济大学第一附属中学）校园网作业查看器，Win32编写。
通过模拟登陆平台获取作业。

## 截图
![](https://github.com/yh-git/Homework-viewer/blob/master/doc/1.png)
![](https://github.com/yh-git/Homework-viewer/blob/master/doc/2.png)
![](https://github.com/yh-git/Homework-viewer/blob/master/doc/3.png)
![](https://github.com/yh-git/Homework-viewer/blob/master/doc/4.png)
![](https://github.com/yh-git/Homework-viewer/blob/master/doc/5.png)

## 关于安全
Homework Viewer会使用您的用户名密码来登录学校校园网平台以获取作业，并将您的密码加密保存在您的计算机上
但绝不会收集您的密码，或用作别的用处
如不放心可以检查源代码

校园网本身并不支持 https，所以Homework Viewer只能使用http协议，由此带来的安全隐患，是使用网页版校园网同样存在的，并非是Homework Viewer才存在该安全隐患。
