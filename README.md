第一章 计算机基础面试题
一、网络面试题
1.HTTP/HTTPS

HTTP 与 HTTPS 有什么区别？

Http1.1 和 Http1.0 及 2.0 的区别？

解决 head of line blocking

Http 的 request 和 response 的协议组成

谈谈对 http 缓存的了解

Http 长连接

Https 加密原理

HTTPS 如何防范中间人攻击？

有哪些响应码，分别都代表什么意思？

2.TCP/UDP

为什么 tcp 要经过三次握手，四次挥手？

TCP 可靠传输原理实现（滑动窗口）

Tcp 和 Udp 的区别？

如何设计在 UDP 上层保证 UDP 的可靠性传输？

3.其它重要网络概念

socket 断线重连怎么实现，心跳机制又是怎样实现？

Cookie 与 Session 的作用和原理

IP 报文中的内容

4.常见网络流程机制

浏览器输入地址到返回结果发生了什么？

二、操作系统面试题
操作系统如何管理内存的？

进程调度

说下Linux进程和线程的区别

你能解释一下Linux 的软链接和硬链接吗？

安卓权限管理，为何在清单中注册权限，安卓 APP 就可以使用，反之不可以？

三、数据库面试题
数据库的四大特征，数据库的隔离级别？

数据库设计中常讲的三范式是指什么？

第二章 数据结构和算法面试题
对于算法面试准备，无疑就是刷《剑指 Offer》+ LeetCode 效果最佳。刷《剑指 Offer》是为了建立全面的算法面试思维，打下坚实的基础，刷 LeetCode 则是为了不断强化与开阔我们自己的算法思想。这两块 CS-Notes 中已经实现地很完美了，建议大家将《剑指 Offer》刷完，然后再至少刷 100 道 LeetCode 题目 以上。


第三章 Java面试题
一、Java基础面试题
1.面向对象

谈谈对java多态的理解？

你所知道的设计模式有哪些？

通过静态内部类实现单例模式有哪些优点？

静态代理和动态代理的区别，什么场景使用？

简单工厂、工厂方法、抽象工厂、Builder模式的区别？

装饰模式和代理模式有哪些区别？与桥接模式相比呢？

外观模式和中介模式的区别？

策略模式和状态模式的区别？

适配器模式，装饰者模式，外观模式的异同？

代码的坏味道

是否能从Android中举几个例子说说用到了什么设计模式？

2.集合框架

集合框架，list，map，set都有哪些具体的实现类，区别都是什么？

set集合从原理上如何保证不重复？

HashMap和HashTable的主要区别是什么？两者底层实现的数据结构是什么？

HashMap、ConcurrentHashMap、hash()相关原理解析？

ArrayMap跟SparseArray在HashMap上面的改进？

3.反射

说说你对Java反射的理解？
4.泛型

简单介绍一下java中的泛型，泛型擦除以及相关的概念，解析与分派？
5.注解

说说你对java注解的理解？
6.其他

Java的char是凉介字节，是怎么存Utf-8的字符的？

Java String可以有多长？

Java的匿名内部类有哪些限制？

Java中对异常是如何进行分类的？

String为什么要设计成不可变的？

Java里的幂等性了解吗？

为什么Java里的匿名内部类只能访问final修饰的外部变量？

讲一下Java的编码方式？

String，StringBuffer，StringBuilder有哪些不同？

什么是内部类？内部类的作用

抽象类和接口区别？

接口的意义？

父类的静态方法能否被子类重写？

抽象类的意义？

静态内部类、非静态内部类的理解？

为什么复写equals方法的同时需要复写hashcode方法，前者相同后者是否相同，反过来呢？为什么？

equals和hashcode的关系？

java为什么跨平台？

浮点数的精准计算

final，finally，finalize 的区别？

静态内部类的设计意图

Java中对象的生命周期

静态属性和静态方法是否可以被继承？是否可以被重写？以及原因？

object 类的 equal 和 hashcode 方法重写，为什么？

java 中==和 equals 和 hashCode 的区别？

Java 的四种引用及使用场景？

类的加载过程，Person person = new Person();为例进行说明。

JAVA 常量池

在重写 equals 方法时，需要遵循哪些约定，具体介绍一下？

深拷贝和浅拷贝的区别

Integer类对int的优化

二、Java并发面试题
1.线程池相关

什么是线程池，如何使用？为什么要使用线程池？

Java 中的线程池共有几种？

线程池原理？

线程池都有哪几种工作队列？

怎么理解无界队列和有界队列？

多线程中的安全队列一般通过什么实现？

2.Synchronized、volatile、Lock(ReentrantLock)相关

synchronized 的原理？

Synchronized 优化后的锁机制简单介绍一下，包括自旋锁、偏向锁、轻量级锁、重量级锁？

谈谈对 Synchronized 关键字涉及到的类锁，方法锁，重入锁的理解？

wait、sleep 的区别和 notify 运行过程

synchronized 关键字和 Lock 的区别你知道吗？为什么 Lock 的性能好一些？

volatile 原理

synchronized 和 volatile 关键字的作用和区别

ReentrantLock 的内部实现

ReentrantLock 、synchronized 和 volatile 比较？

3.其他

多线程的使用场景？

CopyOnWriteArrayList 的了解

ConcurrentHashMap 加锁机制是什么，详细说一下？

线程死锁的 4 个条件？

CAS 介绍？

进程和线程的区别？

什么导致线程阻塞？

线程的生命周期

乐观锁与悲观锁

run()和 start()方法区别？

多线程断点续传原理

怎么安全停止一个线程任务？原理是什么？线程池里有类似机制吗？

堆内存，栈内存理解，栈如何转换成堆？

三、Java虚拟机面试题
JVM内存区域

JVM的内存模型的理解？

描述一下GC的原理和回收策略？

类的加载器，双亲机制，Android 的类加载器

GC收集器简介？以及它的内存划分怎么样的？

Java的虚拟机 JVM 的两个内存：栈内存和堆内存的区别是什么？

JVM 调优的常见命令行工具有哪些？JVM 常见的调优参数有哪些？

第四章 Android面试题
一、Android基础面试题
什么是ANR，如何避免它？

Activity 和 Fragment 生命周期有哪些？

横竖屏切换时候 Activity 的生命周期

AsyncTask 的缺陷和问题，说说他的原理

onSaveInstanceState() 与 onRestoreIntanceState()

android 中进程的优先级？

Bunder 传递对象为什么需要序列化？Serialzable 和 Parcelable 的区别？

动画

Context 相关

Android 各版本新特性

Json

android 中有哪几种解析 xml 的类,官方推荐哪种？以及它们的原理和区别？

Jar 和 Aar 的区别

Android 为每个应用程序分配的内存大小是多少

更新 UI 方式

ContentProvider 使用方法

Thread、AsyncTask、IntentService 的使用场景与特点

Merge、ViewStub的作用

activity 的 startActivity 和 context 的 startActivity 区别？

怎么在Service中创建 Dialog 对话框？

Asset 目录与 res 目录的区别？

Android 怎么加速启动 Activity？

Handler 机制

程序 A 能否接收到程序 B 的广播？

数据加载更多涉及到分页，你是怎么实现的？

通过 google 提供的 Gson 解析 json 时，定义 JavaBean 的规则是什么？

json 解析方式的两种区别？

线程池的相关知识

内存泄露，怎样查找，怎么产生的内存泄露？

类的初始化顺序依次是？

JSON 的结构？

ViewPager 使用细节，如何设置成每次只初始化当前的 Fragment，其他的不初始化（提示： Fragment 懒加载）？

Android 为什么引入 Parcelable？

有没有尝试简化 Parcelable 的使用？

Bitmap 使用时候注意什么？

Oom 是否可以 try catch ？

多进程场景遇见过么？

Canvas.save()跟 Canvas.restore()的调用时机

数据库升级增加表和删除表都不涉及数据迁移，但是修改表涉及到对原有数据进行迁移。

编译期注解跟运行时注解

bitmap recycler 相关

强引用置为 null，会不会被回收？

Bundle 传递数据为什么需要序列化？

广播传输的数据是否有限制，是多少，为什么要限制？

是否了解硬件加速？

ContentProvider 的权限管理(读写分离，权限控制-精确到表级，URL 控制)

Fragment 状态保存

直接在 Activity 中创建一个 thread 跟在 service 中创建一个 thread 之间的区别？

如何计算一个 Bitmap 占用内存的大小，怎么保证加载 Bitmap 不产生内存溢出？

对于应用更新这块是如何做的？(灰度，强制更新，分区域更新)

请解释安卓为啥要加签名机制

为什么 bindService 可以跟 Activity 生命周期联动？

如何通过 Gradle 配置多渠道包？

activty 和 Fragmengt 之间怎么通信，Fragmengt 和 Fragmengt 怎么通信？

自定义 view 效率高于 xml 定义吗？说明理由

广播注册一般有几种，各有什么优缺点？

服务启动一般有几种，服务和 activty 之间怎么通信，服务和服务之间怎么通信

ddms 和 traceView 的区别？

ListView 卡顿原因

AndroidManifest 的作用与理解

LaunchMode 应用场景

说说 Activity、Intent、Service 是什么关系

ApplicationContext 和 ActivityContext 的区别

Handler、Thread 和 HandlerThread 的差别

ThreadLocal 的原理

计算一个 view 的嵌套层级

MVP，MVVM，MVC 解释和实践

SharedPrefrences 的 apply 和 commit 有什么区别

Base64、MD5 是加密方法么？

HttpClient 和 HttpConnection 的区别？

ActivityA 跳转 ActivityB 然后 B 按 back 返回 A，各自的生命周期顺序，A 与 B 均不透明

如何通过广播拦截和 abort 一条短信？

BroadcastReceiver，LocalBroadcastReceiver 区别？

如何选择第三方，从那些方面考虑？

简单说下接入支付的流程，是否自己接入过支付功能？

单例实现线程的同步的要求

如何保证 Service 不被杀死？

说说 ContentProvider、ContentResolver、ContentObserver 之间的关系？

如何导入外部数据库?

LinearLayout、FrameLayout、RelativeLayout 性能对比，为什么？

scheme 跳转协议

HandlerThread

IntentService

如何将一个 Activity 设置成窗口的样式

Android 中跨进程通讯的几种方式

Android 中跨进程通讯的几种方式

Android Holo 主题与 MD 主题的理念，以及你的看法

如何让程序自动启动？

屏幕适配的处理技巧都有哪些?

断点续传实现？

二、Android高级面试题
1.性能优化

App 稳定性优化

你们做了哪些稳定性方面的优化？

性能稳定性是怎么做的？

业务稳定性如何保障？

如果发生了异常情况，怎么快速止损？

App 启动速度优化

启动优化是怎么做的？

是怎么异步的，异步遇到问题没有？

启动优化有哪些容易忽略的注意点？

版本迭代导致的启动变慢有好的解决方式吗？

开放问题：如果提高启动速度，设计一个延迟加载框架或者 sdk 的方法和注意的问题

App 内存优化

你们内存优化项目的过程是怎么做的？

你做了内存优化最大的感受是什么？

如何检测所有不合理的地方？

App 绘制优化

你在做布局优化的过程中用到了哪些工具？

布局为什么会导致卡顿，你又是如何优化的？

做完布局优化有哪些成果产出？

你是怎么做卡顿优化的？

你是怎么样自动化的获取卡顿信息？

卡顿的一整套解决方案是怎么做的？

开放问题：优化一个列表页面的打开速度和流畅性

网络优化

移动端获取网络数据优化的几个点

客户端网络安全实现

设计一个网络优化方案，针对移动端弱网环境

App 电量优化

安卓的安全优化

提高 app 安全性的方法？

安卓的 app 加固如何做？

安卓的混淆原理是什么？

谈谈你对安卓签名的理解

为什么 WebView 加载会慢呢？

如何优化自定义 View

FC(Force Close)什么时候会出现？

mmap + native 日志优化？

2.Android Framework 相关

Android 系统架构

View 的事件分发机制？滑动冲突怎么解决？

View 的绘制流程？

跨进程通信

Android 系统启动流程是什么？（提示：init 进程 -> Zygote 进程 –> SystemServer 进程 –> 各种系统服务 –> 应用进程）

启动一个程序，可以主界面点击图标进入，也可以从一个程序中跳转过去，二者有什么区别？

AMS 家族重要术语解释

App 启动流程（Activity 的冷启动流程）

说下四大组件的启动过程，四大组件的启动与销毁的方式

理解 Window 和 WindowManager

大体说清一个应用程序安装到手机上时发生了什么？

Android 的打包流程？（即描述清点击 Android Studio 的 build 按钮后发生了什么？） apk 里有哪些东西？签名算法的原理？

说下安卓虚拟机和java 虚拟机的原理和不同点?（JVM、Davilk、ART 三者的原理和区别）

安卓采用自动垃圾回收机制，请说下安卓内存管理的原理？

JNI

3.Android 优秀三方库源码

你项目中用到哪些开源库？说说其实现原理？

网络底层框架：OkHttp实现原理

网络封装框架：Retrofit 实现原理

响应式编程框架：RxJava 实现原理

图片加载框架：Glide 实现原理

事件总线框架：EventBus 实现原理

内存泄漏检测框架：LeakCanary 实现原理

依赖注入框架：ButterKnife 实现原理

依赖全局管理框架：Dagger2 实现原理

数据库框架：GreenDao 实现原理

4.热修复、插件化、模块化、组件化、Gradle、编译插桩技术

热修复和插件化

模块化和组件化

gradle

编译插桩

5.架构设计

MVC MVP MVVM 原理和区别？

基于 AOP 的架构设计

MVC 的情况下怎么把 Activity 的 C 和 V 抽离？

MVP 架构中 Presenter 定义为接口有什么好处

MVP 如何管理 Presenter 的生命周期，何时取消网络请求？

aop 思想

Fragment 如果在 Adapter 中使用应该如何解耦？

项目框架里有没有 Base 类，BaseActivity 和 BaseFragment 这种封装导致的问题，以及解决方法？

设计一个音乐播放界面，你会如何实现，用到那些类，如何设计，如何定义接 口，如何与后台交互，如何缓存与下载，如何优化(15 分钟时间)

从 0 设计一款 App 整体架构，如何去做？

说一款你认为当前比较火的应用并设计(比如：直播 APP，P2P 金融，小视频等)

实现一个库，完成日志的实时上报和延迟上报两种功能，该从哪些方面考虑？

你最优秀的工程设计项目，是怎么设计和实现的；扩展，如何做成一个平台级 产品？

6.其他高频面试题

如何保证一个后台服务不被杀死？（相同问题：如何保证 service 在后台不被 kill？）比较省 电的方式是什么？

Android 动画框架实现原理

Activity-Window-View 三者的差别？

低版本 SDK 如何实现高版本 api？

说说你对 Context 的理解？

Android 的生命周期和启动模式

ListView 和 RecyclerView 系列

如何实现一个推送，消息推送原理？推送到达率的问题？

动态权限系列

自定义 View 系列

Scroller 原理

Hybrid 系列

如果在当前线程内使用 Handler postdelayed 两个消息，一个延迟 5s，一个延迟 10s，然 后使当前线程 sleep 5 秒，以上消息的执行时间会如何变化？

Android 长连接，怎么处理心跳机制

CrashHandler 实现原理？

SurfaceView 和 View 的最本质的区别？

Android 程序运行时权限与文件系统权限

非 UI 线程可以更新 UI 吗?

单元测试有没有做过，说说熟悉的单元测试框架？

如何绕过 9.0 限制？

第五章 其他扩展面试题
一、Kotlin
Kotlin 特性，和 Java 相比有什么不同的地方?

Kotlin 为什么能和 Java 混编?

什么是协程？

二、大前端
Hybrid 通信原理是什么，有做研究吗？

JS 的交互理解吗？平时工作用的多吗，项目中是怎么与 Web 交互的？

react native 有多少了解？讲一下原理

weex 了解吗？如何自己实现类似技术？

flutter 了解吗？内部是如何实现跨平台的？如何实现多 Native 页面接入？如何实现对现有工程的 flutter 迁移？

Dart 语言有研究过吗？

快应用了解吗？跟其她方式相比有什么优缺点？

说说你用过的混合开发技术有哪些？各有什么优缺点？

三、脚本语言
脚本语言会吗？

Python会吗？

Gradle了解多少？groovy语法会吗？

第六章 非技术面试题
你还有什么要了解和要问的吗？

你觉得安卓开发最关键的技术在哪里？

研究比较深入的领域有哪些？

自己最擅长的技术点，最感兴趣的技术领域和技术？

项目中用了哪些开源库，如何避免因为引入开源库而导致的安全性和稳定性问题？

说下你都看过哪些技术书籍，你是如何自学的。你觉得自己的优势与弱点是什么。

说下项目中遇到的棘手问题，包括技术，交际和沟通。

说下你近几年的规划？

对加班怎么看？

介绍你做过的哪些项目

你并非毕业于名牌院校？

为什么要离职？

当你的开发任务很紧张，你怎么去做代码优化的？


————————————————
版权声明：本文为CSDN博主「喜欢喝酸奶」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/weixin_48091641/article/details/122156014
