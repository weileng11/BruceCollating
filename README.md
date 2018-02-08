# BruceCollating
===============================================================================<br>
前言:由于每次做一样的东西总是要重新去找很好的demo，所以花点时间整理一下，方便以后自己开发过程中使用，由于个人整理能力
有限，如果有更好的列子，欢迎大家提交issues或者QQ：275762645留言，一起吧这个整理的更完美。
===============================================================================<br>

## 主要内容介绍
----------------------------------------------------------------------------------------------------
###  一.[图片](#图片)
* 仿微信拍照<br>
----------------------------------------------------------------------------------------------------
###  二.[自定义组件](#自定义组件)
* CircleTextImage 圆形图片里面带文字
* PagerSlidingTabStrip
* RecyclerView
* 上啦下拉刷新
* progress
* 联系人排序
* dialog和pop
* EditText
* ...<br>
----------------------------------------------------------------------------------------------------
###  三.[安卓打印信息](#安卓打印信息)
* logger （推荐使用)
* ...<br>
----------------------------------------------------------------------------------------------------
###  四.[动画](#动画)
* 属性动画
* ...<br>
----------------------------------------------------------------------------------------------------
###  五.[加密解密](#加密解密)
* 加密解密 md5 AES
* ...<br>
----------------------------------------------------------------------------------------------------
###  六.[视频播放](#视频播放)
* 视频播放
* ...<br>
----------------------------------------------------------------------------------------------------
###  七.[自定义控件](#自定义控件)
* 自定义 View
* ...<br>
----------------------------------------------------------------------------------------------------
###  八.[断点续传](#断点续传)
* 断点续传
* ...<br>
----------------------------------------------------------------------------------------------------
###  九.[开源库](#开源库)
* Android开源库
* ...<br>
----------------------------------------------------------------------------------------------------
###  十.[屏幕适配](#屏幕适配)
* Android屏幕适配方案
* ...<br>
----------------------------------------------------------------------------------------------------
###  十一.[第三方分享](#第三方分享)
* QQ和微信，新浪
* ...<br>
----------------------------------------------------------------------------------------------------
###  十二.[其他工具](#其他工具)
* PxCook 最高效易用的自动标注工具
* ...<br>
----------------------------------------------------------------------------------------------------
###  十三.[网络请求框架](#网络请求框架)
* RxEasyHttp okgo okhttp3
* ...<br>
----------------------------------------------------------------------------------------------------
###  三.android工具类
* AndroidUtilCode安卓工具类库
* ...<br>
----------------------------------------------------------------------------------------------------
###  三.android 杂七杂八
* ...<br>
----------------------------------------------------------------------------------------------------
###  LAST.android 学习
* ...<br>
----------------------------------------------------------------------------------------------------

===============================================================================<br>
## 整理的具体地址

### 图片
#### 1.图片处理模块
* 仿微信拍照       [仿微信拍照，带裁剪,无压缩，后面需要将里面的拍照部分获取不到size修改调整一下(推荐使用)](https://github.com/jeasonlzy/ImagePicker)
* 图片选择器        [支持直接拍照、拍照并裁剪、单选裁剪、图片多选、图片放大预览、裁剪比例设置](https://github.com/weileng11/PhotoPicker-master)
* 图片的开源工具库     [Android设备上获取照片（拍照或从相册、文件中选择）、裁剪图片、压缩图片的开源工具库](https://github.com/crazycodeboy/TakePhoto#%E5%AE%89%E8%A3%85%E8%AF%B4%E6%98%8E)
* 图片/视频文件选择器     [支持多选、单选、拍摄和裁剪，主题可自定义，无强制绑定第三方图片](https://github.com/FinalTeam/RxGalleryFinal)
* 图片贴图打标签     [相机,图片裁剪,给图片贴贴图打标签的APP](https://github.com/Skykai521/StickerCamera)
* 图片等40余种实时滤镜相机   [可拍照、录像、图片修改](https://github.com/wuhaoyu1990/MagicCamera)

### 自定义组件
#### 2.常用的自定义组件
* CircleTextImage [圆形图片里面带文字](https://github.com/viviant1224/CircleTextImage)
* PagerSlidingTabStrip [android指示器TabLayout、PagerSlidingTabStrip，仿Boss直聘，带有红点未读提示](https://github.com/q805699513/PagerSlidingTabStrip)
* RecyclerView [RecyclerView之通用适配](http://blog.csdn.net/u012551350/article/details/52026740)
* BaseRecyclerViewAdapterHelper [BRVAH是一个强大的RecyclerAdapter框架](https://www.jianshu.com/p/b343fcff51b0)
* [RecyclerView仿ios左滑删除的轻量级实现](http://blog.csdn.net/fornana/article/details/60966521)
* [打造最强RecyclerView，Item侧滑菜单，长按拖拽Item，滑动删除Item](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2016/0805/4573.html)
* [Android实现RecyclerView左侧滑删除与右侧滑选择](http://download.csdn.net/download/qq_22770457/9736919#comment)
----------------------------------------------------------------------------------------------------
* [Android智能下拉刷新框架，支持越界回弹、越界拖动，具有极强的扩展性，集成了几十种炫酷的Header和 Footer](https://github.com/scwang90/SmartRefreshLayout#1)（推荐使用）
* [PtrClassicFrameLayout下拉刷新控件](https://github.com/chrisbanes/Android-PullToRefresh)
* [那些年用过的下拉刷新、上拉加载更多的库](https://www.jianshu.com/p/699e2662fc27)
----------------------------------------------------------------------------------------------------
* [Android NumberProgressBar](https://github.com/daimajia/NumberProgressBar)
* [Android 三种方式实现自定义圆形页面加载中效果的进度条](http://blog.csdn.net/jdsjlzx/article/details/42497253)
* [Android 自定义圆形进度条](https://github.com/MyLifeMyTravel/CircleProgress)
* [Android：自定义View实现绚丽的圆形进度条](http://blog.csdn.net/books1958/article/details/48267903)
* [Android自定义之圆形进度条2](http://blog.csdn.net/u012551350/article/details/51179957)
* [圆弧刻度进度条](https://github.com/woodnaonly/ArcProgressBar)
* [Android 圆形的进度条，类似于一些计步的进度显示](https://github.com/gyw520gyw/ArcProgress)
* [Android 竖立的进度](https://github.com/hadiidbouk/ChartProgressBar-Android)
* [Android 圆进度](https://github.com/flyou/NiceProgressBar)更多搜ProgressBar
----------------------------------------------------------------------------------------------------
* [Android 悬浮菜单按钮](https://github.com/cpacm/FloatingMusicMenu)
----------------------------------------------------------------------------------------------------
* [Android 仿联系人列表实现ListView的A-Z字母排序和过滤搜索功能](http://892848153.iteye.com/blog/2042122)
* [Android通讯录字母排序城市列表展示效果](http://blog.csdn.net/jaynm/article/details/51861137)
* [Android仿微信通讯录功能，好友排序+字母索引](http://blog.csdn.net/afei__/article/details/51532132)
* [Android】使用RecyclerView优雅实现悬浮标题通讯录](https://www.jianshu.com/p/52bce7f59c00)
* [Android 实现ListView的A-Z字母排序和过滤搜索功能，实现汉字转成拼音](http://blog.csdn.net/xiaanming/article/details/12684155)
----------------------------------------------------------------------------------------------------
* [通用PopupWindow，几行代码搞定PopupWindow弹窗](https://github.com/pinguo-zhouwei/CustomPopwindow)
----------------------------------------------------------------------------------------------------
* [自定义的仿IOS格式的EditText](https://github.com/thinkerzhangyan/EditTextApplication)
* [可以伸缩的搜索栏](https://github.com/yuqirong/FlexibleSearchBar)
* [Android雷达扫描显示效果，模仿QQ附近的人搜索展示 ](https://github.com/ImmortalZ/RadarScan)
* [一款封装了 历史搜索记录功能 & 样式 的Android自定义搜索框](https://github.com/Carson-Ho/Search_Layout)
----------------------------------------------------------------------------------------------------
###  安卓打印信息
#### 3.logCat使用
* [logger](https://github.com/orhanobut/logger)
* [Klog](https://github.com/ZhaoKaiQiang/KLog)
* [Alog](https://github.com/Blankj/ALog)

###  动画
#### 4.各种动画（需扩展）
* [Android动画-属性动画-ValueAnimator](https://www.jianshu.com/p/2966227ea0b4)

###   加密解密
####  5.加密解密 md5 AES
* [Android 加密解密工具,推荐使用](https://github.com/GcsSloop/encrypt)
* [Android AES加密和解密](http://blog.csdn.net/hongyan_love/article/details/44220873)

###  视频播放
####  6.视频播放IJKplayer，MediaPlayer，JPlayer
* [视频播放器（IJKplayer）](https://github.com/CarGuo/GSYVideoPlayer)
* [用IjkPlayer/MediaPlayer + TextureView封装](https://github.com/xiaoyanger0825/NiceVieoPlayer)
* [基于exoPlayer 自定义播放器 JPlayer](https://github.com/yangchaojiang/yjPlay)
* [安卓视频播放器 一行代码快速实现在线视频播放](https://github.com/qiushi123/VideoDemoQcl)

### 自定义控件
#### 7.自定义View
* [自定义 View 之炫酷的成绩展示界面](https://mp.weixin.qq.com/s/WamWBViJMNksefxs8xIB_Q)
* [Android PinnedHeaderListView 详解](http://blog.csdn.net/aaawqqq/article/details/43866339)
* [可下拉的PinnedHeaderExpandableListView的实现](http://blog.csdn.net/singwhatiwanna/article/details/25546871)
* [Android之联系人PinnedHeaderListView使用](http://download.csdn.net/download/fx_sky/5995355#comment)
* [使用PinnedHeaderListView实现固定头部的列表](http://blog.csdn.net/ruancoder/article/details/52076039)
* [Android仿联系人列表分组悬浮列表,PinnedHeaderListView源码解析](http://blog.csdn.net/u010335298/article/details/51178179)
* [Android仿联系人列表分组悬浮列表实现，自定义PinnedHeaderListView实现](http://blog.csdn.net/u010335298/article/details/51150346)
* [Android实用view系列------炫酷的进度条](https://www.jianshu.com/p/7ecdb565e8f0?open_source=weibo_search)

* [Android5.0之NavigationView的使用](http://blog.csdn.net/u012702547/article/details/51253222)
----------------------------------------------------------------------------------------------------
* [三步实现Android悬浮效果](https://www.jianshu.com/p/167507486ff2)
* [Android滑动到顶部悬停](https://github.com/peipei1024/scroll)

### 断点续传
#### 8.Android 断点续传
* [Android 使用多线程来做多文件上传Or下载](http://blog.csdn.net/qq402164452/article/details/53896099)
* [Android-Service之多线程断点续传下载](https://github.com/lishide/DownloadDemo)
* [Android-Service之多线程断点续传下载 加入了七牛](https://github.com/weileng11/DownloadDemo-master)
* [Android多线程，断点传输](https://segmentfault.com/a/1190000009937326)


### 开源库
#### 9.Android开源库更新
* [Android开源库：这里有一个简单好用、含历史搜索记录的搜索框](https://www.jianshu.com/p/3682f6536e49)

### 屏幕适配
#### 10.所有的屏幕适配
* [Android屏幕适配方案](https://github.com/hongyangAndroid/AndroidAutoLayout)
* [一种粗暴快速的Android全屏幕适配方案](https://github.com/Firedamp/Rudeness)
* [Android屏幕适配方案，直接填写设计图上的像素尺寸即可](https://github.com/l123456789jy/AutoAndroidLayout)
* [Android屏幕适配全攻略（最权威的官方适配指导](http://www.cocoachina.com/android/20151030/13971.html)
* [Android 屏幕适配：最全面的解决方案](https://www.jianshu.com/p/ec5a1a30694b)

### 第三方分享
#### 11.QQ,WX,XL分享
* [Android 微信分享图片!!!](http://blog.csdn.net/u013241923/article/details/53635236)
* [Android 微信分享与QQ分享功能](https://www.jianshu.com/p/7100645fe1a8)
* [Android QQ分享本地url,demo仅用来获取mipmap目录下的图片](https://github.com/weileng11/BitmapUtilDemo-master)
* [Android 分享到新浪微博](http://blog.csdn.net/u010241861/article/details/51924904)

### 其它工具
#### 12.学习其它工具
* [PxCook 最高效易用的自动标注工具](http://www.fancynode.com.cn/pxcook)
* [七牛 最高效上传图片](https://developer.qiniu.com/kodo/sdk/1236/android)
* [Android如何制作自己的依赖库上传至github供别人下载使用](http://blog.csdn.net/xuchao_blog/article/details/62893851)
* [第一次使用Android Studio时你应该知道的一切配置](http://www.cnblogs.com/smyhvae/p/4390905.html)
* [Android SDk Manager里面到底哪些东西是必须下载的](https://www.zhihu.com/question/31935836)
* [Android Studio添加忽略文件](http://blog.csdn.net/lyankj/article/details/52218742)

### 网络请求框架
#### 13.网络请求框架.....
* [RxEasyHttp](https://github.com/zhou-you/RxEasyHttp)
* [okhttp-OkGo](https://github.com/jeasonlzy/okhttp-OkGo)

### android工具类库
#### android工具类库大全
* [AndroidUtilCode是一个强大易用的安卓工具类库](https://github.com/Blankj/AndroidUtilCode)
* [Android快速开发框架，采用AndroidStudio进行开发](https://github.com/jiangqqlmj/FastDev4Android)


### android杂七杂八
#### android杂七杂八
* [Android定时每十分钟执行一次任务](http://blog.csdn.net/upset7117/article/details/70783514)
* [Android 全面的UI](https://github.com/wasabeef/awesome-android-ui)
* [java根据时间排序list,使用collections.sort](http://blog.csdn.net/u010002184/article/details/51519838)
* [Android对数据按照时间排序](http://blog.csdn.net/qq_16131393/article/details/75289079)
* [Android studio中的一次编译报错Error:Execution failed for task ':app:transformClassesWithDexForDebug](http://blog.csdn.net/hejjunlin/article/details/51737003)
* [android的Dialog全屏、activity大小的设置详解](http://www.lxway.com/4069404966.htm)
* [Android中通过xml改变背景及文字颜色](https://www.cnblogs.com/ivan-xu/p/4555534.html)
* [多个activity页面跳转，跳过中间页面返回前边页面传值](http://blog.csdn.net/github_36719758/article/details/68946471)
* [Activity从屏幕底部滑出、滑入、处理黑色背景和状态栏](http://blog.csdn.net/hello_1s/article/details/62892331)

###  LAST.android 学习
####  LAST.android 学习（wl）
* [Android ConstraintLayout详解](https://www.jianshu.com/p/a8b49ff64cd3)
* [Android上使用retrofit+okhttp时token失效的处理方案](https://www.jianshu.com/p/62ab11ddacc8)

### 混淆
#### 混淆代码
* [Android混淆配置总结](https://www.jianshu.com/p/155430a27f00)
* [APK混淆通用框架（Studio）](https://www.jianshu.com/p/c02049ed035d)


===============================================================================<br>
#### 说明：github上面如何编辑README http://blog.csdn.net/kaitiren/article/details/38513715
#### 说明：关于github上 README.md 的编写排版问题 点击链接实现页面内的跳转 https://github.com/LuckSiege/PictureSelector#%E9%9B%86%E6%88%90%E6%96%B9%E5%BC%8F

