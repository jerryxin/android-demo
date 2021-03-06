![Trinea](http://farm8.staticflickr.com/7426/9456847893_053161c7a4_o.png)android-demo
-------------
**主要包括**：[图片缓存Demo](http://www.trinea.cn/?p=704)，[图片SD卡缓存Demo](http://www.trinea.cn/?p=757)，[下拉刷新及滚动到底部加载更多listview Demo](http://www.trinea.cn/android/滚动到底部加载更多及下拉刷新listview的使用)，[Android系统下载管理DownloadManager功能介绍及使用示例](http://www.trinea.cn/android/android%E7%B3%BB%E7%BB%9F%E4%B8%8B%E8%BD%BD%E7%AE%A1%E7%90%86downloadmanager%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D%E5%8F%8A%E4%BD%BF%E7%94%A8%E7%A4%BA%E4%BE%8B/)，[ViewPager Multi Page](http://www.trinea.cn/android/viewpager%E5%AE%9E%E7%8E%B0%E7%94%BB%E5%BB%8A%E4%B8%80%E5%B1%8F%E5%A4%9A%E4%B8%AAfragment%E6%95%88%E6%9E%9C/)，[滚动到底部或顶部响应的ScrollView使用](http://www.trinea.cn/android/%E6%BB%9A%E5%8A%A8%E5%88%B0%E5%BA%95%E9%83%A8%E6%88%96%E9%A1%B6%E9%83%A8%E5%93%8D%E5%BA%94%E7%9A%84scrollview%E4%BD%BF%E7%94%A8/)，[Gallery滑动一页效果 Demo](http://www.trinea.cn/android/gallery%e6%bb%91%e5%8a%a8%e4%b8%80%e9%a1%b5%e4%b8%80%e4%b8%aaitem%e6%95%88%e6%9e%9c/)，[SearchView Demo](http://www.trinea.cn/android/android-searchview介绍及搜索提示实现/)，[ViewPager、Fragment使用](http://www.cnblogs.com/trinea/archive/2012/11/23/2771273.html)，[Service Demo](http://www.cnblogs.com/trinea/archive/2012/11/08/2699856.html)，[BroadcastReceiver Demo](http://www.cnblogs.com/trinea/archive/2012/11/09/2763182.html)。  
<strong>注&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;意</strong>：编译需要将[trinea-android-common](https://github.com/Trinea/android-common)做为公共库引入。公共库添加方法：android-common代码导入IDE,右击你的工程->properties->Android，在library中选择android-common即可。  
**个人博客**：[www.trinea.cn](http://www.trinea.cn/) 关注于[Android](http://www.trinea.cn/category/android/)、[Java](http://www.trinea.cn/category/java/)、[性能优化](http://www.trinea.cn/category/perf/)、[开源代码](http://www.trinea.cn/category/open-code/)。  
####示例APK下载(Demo Download):  
<a href="https://play.google.com/store/apps/details?id=cn.trinea.android.demo" target="_blank" title="从Google Play下载"><img src="http://www.android.com/images/brand/get_it_on_play_logo_small.png" title="从Google Play下载"/></a>
    <a href="http://as.baidu.com/a/item?docid=5499464" target="_blank" title="从Baidu手机助手下载"><img src="http://farm3.staticflickr.com/2826/11928623406_b9e8d39bd7_o.png" title="从Baidu手机助手下载"/></a>
    <a href="http://zhushou.360.cn/detail/index/soft_id/994107" target="_blank" title="从360手机助手下载"><img src="http://farm4.staticflickr.com/3775/11983355756_f8548f4c17_o.png" title="从360手机助手下载"/></a>
    <a href="http://app.xiaomi.com/detail/54761" target="_blank" title="从小米应用商店下载"><img src="http://farm8.staticflickr.com/7380/11982503045_b0538df5f5_o.png" title="从小米应用商店下载"/></a>  
    
#####1. 图片缓存Demo
使用见：[图片缓存Demo](http://www.trinea.cn/?p=704)  
适用：获取图片较多的应用，包含二级缓存，如新浪微博、twitter、微信头像、美丽说、蘑菇街、花瓣、淘宝等等。效果图如下：  
![ImageCahe](http://farm4.staticflickr.com/3710/9312163125_81f1c1997b_o.jpg)
  

#####2. 图片SD卡缓存Demo
使用见：[图片SD卡缓存Demo](http://www.trinea.cn/?p=757)  
适用：应用中获取图片较多且图片较大的情况，在微博、花瓣、美丽说、path这类应用中可以起到很好的效果。效果图如下：  
![ImageSDCardCache](http://farm3.staticflickr.com/2834/9314949798_ea69bdb5e8_o.jpg)
  

#####3. 下拉刷新及滚动到底部加载更多的Listview Demo
使用: [下拉刷新及滚动到底部加载更多listview Demo](http://www.trinea.cn/android/滚动到底部加载更多及下拉刷新listview的使用)  
实现原理: [http://trinea.iteye.com/blog/1562281](http://trinea.iteye.com/blog/1562281)。效果图如下：  
![DropDownListView](http://farm8.staticflickr.com/7376/9312162951_74b597ebaa_o.jpg)
  

 
#####4. Android系统下载管理DownloadManager Demo
使用示例：[Android系统下载管理DownloadManager功能介绍及使用示例](http://www.trinea.cn/android/android%E7%B3%BB%E7%BB%9F%E4%B8%8B%E8%BD%BD%E7%AE%A1%E7%90%86downloadmanager%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D%E5%8F%8A%E4%BD%BF%E7%94%A8%E7%A4%BA%E4%BE%8B/)  
功能扩展：[Android下载管理DownloadManager功能扩展和bug修改](http://www.trinea.cn/android/android%E4%B8%8B%E8%BD%BD%E7%AE%A1%E7%90%86downloadmanager%E5%8A%9F%E8%83%BD%E5%A2%9E%E5%BC%BA%E5%92%8Cbug%E4%BF%AE%E6%94%B9/)。效果图如下：  
![downloadManagerDemo](http://www.trinea.cn/wp-content/uploads/2013/05/downloadDemo2.gif)  
  

#####5. viewpager实现画廊效果Demo
使用示例：[ViewPager Multi Page](http://www.trinea.cn/android/viewpager%E5%AE%9E%E7%8E%B0%E7%94%BB%E5%BB%8A%E4%B8%80%E5%B1%8F%E5%A4%9A%E4%B8%AAfragment%E6%95%88%E6%9E%9C/)。效果图如下：  
![viewpager multi page demo](http://farm8.staticflickr.com/7330/9321381014_4e5408a445_b.jpg)  
  

#####6. 滑动到底部或顶部响应的ScrollView Demo
使用及实现原理: [滚动到底部或顶部响应的ScrollView使用](http://www.trinea.cn/android/%E6%BB%9A%E5%8A%A8%E5%88%B0%E5%BA%95%E9%83%A8%E6%88%96%E9%A1%B6%E9%83%A8%E5%93%8D%E5%BA%94%E7%9A%84scrollview%E4%BD%BF%E7%94%A8/)。效果图如下：  
![ScrollView](http://farm4.staticflickr.com/3669/9459686814_1a523ceeb6_o.jpg)
  

#####7. Gallery滑动一页效果 Demo
[Gallery One Page](http://www.trinea.cn/android/gallery%e6%bb%91%e5%8a%a8%e4%b8%80%e9%a1%b5%e4%b8%80%e4%b8%aaitem%e6%95%88%e6%9e%9c/)。效果图如下：  
![gallery one page demo](http://farm8.staticflickr.com/7330/9321381014_fb404e2430_o.jpg)   
  

#####8. SearchView Demo
使用示例：[SearchView Demo](http://www.trinea.cn/android/android-searchview介绍及搜索提示实现/)。效果图如下：  
![SearchView Demo](http://www.trinea.cn/wp-content/uploads/2013/04/SearchView.jpg)   
  

#####9. ViewPager、Fragment Demo
[ViewPager、Fragment使用](http://www.cnblogs.com/trinea/archive/2012/11/23/2771273.html)。效果图如下：  
![viewpager demo](http://pic002.cnblogs.com/images/2012/392321/2012112319384979.jpg)  
  
#####10. Service Demo
使用示例：[Service Demo](http://www.cnblogs.com/trinea/archive/2012/11/08/2699856.html)   
  

#####11. BroadcastReceiver Demo
使用示例：[BroadcastReceiver Demo](http://www.cnblogs.com/trinea/archive/2012/11/09/2763182.html)   

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/Trinea/androiddemo/trend.png)](https://bitdeli.com/free "Bitdeli Badge")  
[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/9aacf0f4a496e0647f415dbfa2df098a "githalytics.com")](http://githalytics.com/Trinea/android-demo)

