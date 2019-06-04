# android.Broadcast-notes
android入门-第一行代码的第五章内容 (所有的android之小a为入门阶段~)
# 将以定位章节 和 自己的理解为主加以整理   

## 5.1 广播机制简介  
* 就好比以前上课的广播铃声也只有班级里会响但是  老师的办公室明显不会响啊 这就相当于每个app只对自己感兴趣的广播进行注册 这样也只会收到自己关心的广播内容   
* 广播可以分为标准广播和有序广播 具体如图   
![图片](https://github.com/pawNku/image.inGithub/blob/master/5.1.png?raw=true)   

## 5.2 接受系统广播   
* 动态注册广播 也就是代码中 其实很easy就是新建一个类 然后继承BroacastReceiver 并且重写onReceive方法就ok了-->编写监听网络变化的   
![图片](https://github.com/pawNku/image.inGithub/blob/master/5.2.1.png?raw=true)   
