# MyProject
1. 缓存  
DiskLruCache  Java实现基于LRU的磁盘缓存: https://github.com/JakeWharton/DiskLruCache

2.图片加载
Android Universal Image Loader  一个强大的加载，缓存，展示图片的库 https://github.com/nostra13/Android-Universal-Image-Loader
Picasso 一个强大的图片下载与缓存的库 https://github.com/square/picasso
Fresco  一个用于管理图像和他们使用的内存的库   https://github.com/facebook/fresco
Glide   一个图片加载和缓存的库  https://github.com/bumptech/glide

3. 图片处理

Picasso-transformations 一个为Picasso提供多种图片变换的库  https://github.com/wasabeef/picasso-transformations

Glide-transformations   一个为Glide提供多种图片变换的库 https://github.com/wasabeef/glide-transformations

Android-gpuimage    基于OpenGL的Android过滤器 https://github.com/CyberAgent/android-gpuimage

4. 网络请求

Android Async HTTP  Android异步HTTP库 https://github.com/loopj/android-async-http

AndroidAsync    异步Socket，HTTP(客户端+服务器)，WebSocket，和socket.io库。基于NIO而不是线程。https://github.com/koush/AndroidAsync

OkHttp  一个Http与Http/2的客户端 https://github.com/square/okhttp

Retrofit    类型安全的Http客户端 https://github.com/square/retrofit

Volley  Google推出的Android异步网络请求框架和图片加载框架  https://android.googlesource.com/platform/frameworks/volley    //目前打不开
5. 网络解析

Gson    一个Java序列化/反序列化库，可以将JSON和java对象互相转换  https://github.com/google/gson

Jackson Jackson可以轻松地将Java对象转换成json对象和xml文档，同样也可以将json、xml转换成Java对象  https://github.com/codehaus/jackson

Fastjson    Java上一个快速的JSON解析器/生成器  https://github.com/alibaba/fastjson

HtmlPaser   一种用来解析单个独立html或嵌套html的方式 https://sourceforge.net/projects/htmlparser/

Jsoup   一个以最好的DOM，CSS和jQuery解析html的库  https://github.com/jhy/jsoup

6. 数据库

OrmLite JDBC和Android的轻量级ORM java包  https://sourceforge.net/projects/ormlite/files/releases/com/j256/ormlite/

Sugar   用超级简单的方法处理Android数据库  https://github.com/satyan/sugar

GreenDAO    一种轻快地将对象映射到SQLite数据库的ORM解决方案  https://github.com/greenrobot/greenDAO

ActiveAndroid   以活动记录方式为Android SQLite提供持久化  https://github.com/pardom/ActiveAndroid

SQLBrite    SQLiteOpenHelper 和ContentResolver的轻量级包装   https://github.com/square/sqlbrite

Realm   移动数据库：一个SQLite和ORM的替换品   https://github.com/jhy/jsoup
 
7. 依赖注入

ButterKnife 将Android视图和回调方法绑定到字段和方法上 https://github.com/JakeWharton/butterknife

Dagger2 一个Android和java快速依赖注射器。https://github.com/google/dagger

AndroidAnotations   快速安卓开发。易于维护  https://github.com/androidannotations/androidannotations

RoboGuice   Android平台的Google Guice  https://github.com/roboguice/roboguice

8. 图表

WilliamChart    创建图表的Android库 https://github.com/diogobernardino/WilliamChart

HelloCharts 兼容到API8的Android图表库 https://github.com/lecho/hellocharts-android

MPAndroidChart  一个强大的Android图表视图/图形库 https://github.com/PhilJay/MPAndroidChart

9. 后台处理

Tape    一个轻快的，事务性的，基于文件的FIFO的库  https://github.com/square/tape

Android Priority Job Queue  一个专门为Android轻松调度任务的工作队列 https://github.com/yigit/android-priority-jobqueue

10. 事件总线
 
EventBus    安卓优化的事件总线，简化了活动、片段、线程、服务等的通信  https://github.com/greenrobot/EventBus

Otto    一个基于Guava的增强的事件总线  https://github.com/square/otto

11. 响应式编程

RxJava  JVM上的响应式扩展 https://github.com/ReactiveX/RxJava

RxJavaJoins 为RxJava提供Joins操作 https://github.com/ReactiveX/RxJavaJoins

RxAndroid   Android上的响应式扩展，在RxJava基础上添加了Android线程调度 https://github.com/ReactiveX/RxAndroid

RxBinding   提供用RxJava绑定Android UI的API  https://github.com/JakeWharton/RxBinding

Agera   Android上的响应式编程  https://github.com/google/agera

12. Log框架

Logger  简单，漂亮，强大的Android日志工具  https://github.com/orhanobut/logger

Hugo    在调试版本上注解的触发方法进行日志记录  https://github.com/JakeWharton/hugo

Timber  一个小的，可扩展的日志工具 https://github.com/JakeWharton/timber

13. 测试框架

Mockito Java编写的Mocking单元测试框架  https://github.com/mockito/mockito

Robotium    Android UI 测试  https://github.com/RobotiumTech/robotium

Robolectric Android单元测试框架  https://github.com/xtremelabs/robolectric //已删除

Android自带很多测试工具：JUnit，Monkeyrunner，UiAutomator，Espresso等   

14. 调试框架

Stetho  调试Android应用的桥梁，使得可以利用Chrome开发者工具进行调试  https://github.com/facebook/stetho

15. 性能优化

LeakCanary  内存泄漏检测工具   https://github.com/square/leakcanary

ACRA  Android应用程序崩溃报告  https://github.com/ACRA/acra

/**
*一个基于MVP+retrofit+rxJava+lambda的日记为主项目
*      https://github.com/MissMyDearBear/Diary
*/

/**
*数据库查看工具
*/
添加依赖：
    在你的build.gradle添加如下代码：
         1 debugCompile 'com.amitshekhar.android:debug-db:1.0.0' 
    ok，至此你不需要任何其他的代码。

使用方式：    
    1 >> 不填加任何代码，直接在 Debug‘app’ 下运行程序，要注意查看logcat，会有这么一行：
         1 D/DebugDB: Open http://xxx.xxx.xxx.xxx:8080 
        点击后在网页上打开地址链接。

    2 >> 在项目的文件中添加如下代码：
         1 DebugDB.getAddressLog(); 
    然后在 Run‘app’ 下运行程序，要注意查看logcat，会有这么一行：
        1 D/DebugDB: Open http://xxx.xxx.xxx.xxx:8080

　　点击后在网页上打开地址链接。
注意：
    1 >> 要使用除8080之外的其他端口。在buildTypes中的build.gradle文件中，进行以下更改：

      1 debug {
      2      resValue（ “ string ” ， “ PORT_NUMBER ” ， “ 8081 ” ）
      3       }
      
    2 >> 使用Android设备测试App时：
        Android手机和电脑应连接到同一网络（Wifi或LAN）。

    3 >> 使用模拟器测试App时:
        Android默认模拟器：运行adb forward tcp:8080 tcp:8080并打开http：// localhost：8080。
        Genymotion Emulator：从配置虚拟设备启用网桥（在genymotion中可用的选项）。
