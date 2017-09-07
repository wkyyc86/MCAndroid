# MCAndroid


#### ScreenShot

![Screenshot_2017-07-05-18-45-33-449_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-f1c1dd8b132f4349.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![
![Screenshot_2017-07-05-18-45-40-526_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-c42f395034b1d451.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
](http://upload-images.jianshu.io/upload_images/5701672-a84e8fe1abfedfbe.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![Screenshot_2017-07-05-18-49-27-385_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-e54d614c51520a42.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



![Screenshot_2017-07-05-18-49-35-458_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-f5e2750cdac76579.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![Screenshot_2017-07-05-18-45-47-283_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-10d10f44b99a789f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



![Screenshot_2017-07-05-18-45-57-765_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-fcad66172c008f77.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![Screenshot_2017-07-05-18-46-10-887_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-765aa222045b53ca.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



![
](http://upload-images.jianshu.io/upload_images/5701672-9767737b51340eb3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



![Screenshot_2017-07-05-18-47-57-376_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-760537f09aa739f8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



![Screenshot_2017-07-05-18-48-30-534_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-cbff6d85d42382df.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



![Screenshot_2017-07-05-18-48-35-859_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-4ecf5bcf2f8d1e0b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![Screenshot_2017-07-05-18-48-41-606_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-15ceeddf8020f05e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![Screenshot_2017-07-05-18-48-47-196_com.example.wk.png](http://upload-images.jianshu.io/upload_images/5701672-87b15574829e3fad.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 项目简介

项目中用到的知识点主要参照郭霖大神最新出版的《第一行代码》第2版。

1.主页面使用TabLayout+ViewPager+Fragment实现顶部导航栏功能，可左右滑动。仿照Bilibili实现沉浸式ToolBar，搜索使用第三方的materialsearchview，SwipeRefreshLayout实现下拉刷新效果。

2.右侧采用DrawerLayout+NavigationView实现抽屉式菜单栏，顶部背景图片采用沉浸式效果，头像图片使用CircleImageView实现圆形化。

3.右侧演示菜单中通过EditText控件输入数据，采用SQL数据库对输入的数据进行添加，删除等操作。通过查询数据库中添加的数据并将数据展现在ACTIVITY活动页面上。

4.轮播图因优化等问题，使用了第三方轮子banner。以后会对此块重新学习一下。

5.使用RecyclerView实现多布局格式，采用网格模式对每部分进行划分，添加header用来添加轮播图。

6.分类部分中的基础内容简单的采用跳转到另外一个带沉浸式Toolbar的页面中。
   全部分类采用RecyclerView的网格布局进行实现。
   经典博客页面中使用shape.xml对Button控件进行颜色 ，Padding，corners（圆弧半径），stroke（边框）的设置，使用android:drawableLeft=“”属性添加左侧图片（图片来源于“我是胖虎，我要统治拳皇”），Button点击事件是跳转到网页，使用了WebView进行页面解析（主要是查看一些Android技术知识，并不想通过网站提供的api接口对数据解析，就简化的用了封装好的WebView实现查看页面）。

7.干货以及推荐内容采用CardView实现卡片式布局。跳转页面采用CollapsingToolbarLayout实现可折叠沉浸式标题栏。

8.课程页面使用RecyclerView+CardView实现，暂未添加点击跳转页面功能。

9.技术页面使用RecyclerView 实现，调用ddItemDecoration(new DividerItemDecoration(this,DividerItemDecoration.VERTICAL))；方法实现分割线效果，暂未添加点击跳转页面功能。

10.我的页面使用LinearLayout实现图片文字的横向排列，添加View控件实现每个LinearLayout布局之间的分割线。

11.首页 课程 技术页面实现滚动同时标题栏隐藏的效果。

12.图片加载主要采用Glide库。


#### 第三方库

Glide 图片加载

CircleImageView 图片圆形化

materialsearchview 搜索

Banner 无限轮播图




