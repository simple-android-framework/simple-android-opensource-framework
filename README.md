# Android著名开源库的简版实现

## 简述
该项目通过分析并实现Android平台知名开源框架的简单版本来提升自我，并达到深入理解各大开源库的核心原理的目的。稳定、强大的开源库一般都较为复杂，比如Universal-ImageLoader，因此简版开源库不需要完全按照原版来实现，只需要把核心架构、原理实现，并且做到可运用到实际项目中即可。在实现开源库简版的同时，作者需要写一系列文章来剖析它的实现原理以及为什么要这么设计，在提升自我的同时将框架的设计与实现、领悟分享给他人，希望大家在提升自我的同时对行业做出一些贡献。       

如果你对面向对象不是很了解，那么在开始之前先学习一下[面向对象的六大原则](https://github.com/simple-android-framework-exchange/android_design_patterns_analysis/oop-principles/oop-principles.md)是非常有必要的。   
    

Android平台的开源库请参考Trinea的[android-open-project](https://github.com/Trinea/android-open-project),一些知名开源库的分析请参考Trinea的[android-open-project-analysis](https://github.com/android-cn/android-open-project-analysis)。      
   
 
**<font color="red">QQ交流群: 413864859,希望大家踊跃参与进来。</font>**



## 库的所属种类
| 开源库类型        | 文件夹           |
| ------------- |:-------------:| 
|    网络请求    |  	[network](network)		|  
|    数据库  		|   [orm](orm) |
|    图片加载  		|   [imageloader](imageloader) |  
|    view  			|   [view](view) |  
|    注入框架  		|   [inject](inject) |  
|    兼容库  		|   [compatibility](compatibility) |  
|    事件总线  		|   [eventbus](eventbus) |  
|    其他  			|   [others](others) |  



## 开发规范简述
[code-style.md](code-style.md)


## 如何参与
1. 通过git将本库clone到本地；
2. 首先将自己要实现的库、完成时间(包括设计与实现的第一篇概括性文章的完成)等填写到任务表中；
3. 在对应分类下创建库的目录，例如SimpleVolley,写代码实现开源库的简版，这个简版库需要可用；
4. 创建一个demo到该库的目录下，例如你要完成的库是SimpleVolley,那么你的demo的路径则为SimpleVolley/demo；
5. 将文章的图片统一放到库名/images目录下，例如SimpleVolley/images；
6. 按照[template.md](template.md)完成库的基本介绍，并且在后续的文章中对库进行详细分析。如果没有后续文章那么建议在该介绍文件中对库的核心实现、设计进行详细分析。    
7. 完成之后提交，并且push到该仓库当中。

**<font color="red">注意，在开发过程中不要修改不属于自己的文件，避免在协作时产生冲突。</font>**

## 任务表
### 一期任务 ( 截止时间 2015.4.5 )
| 原开源库名称    | 简版开源库名称  |     作者       |    分类   | 预计完成时间 |     进行状态   |
| ------------- | ------------- |:-------------:| ------------- | ------------- | ------------- |
|    [Volley](https://github.com/mcxiaoke/android-volley)    | [SimpleNet](https://github.com/bboyfeiyu/simple_net_framework)      | [Mr.Simple](https://github.com/bboyfeiyu) |   网络请求 |   2015.3.5 |  未完成  |
|    [ImageLoader](https://github.com/nostra13/Android-Universal-Image-Loader) | [SimpleImageLoader](https://github.com/bboyfeiyu/simple_imageloader) | [Mr.Simple](https://github.com/bboyfeiyu) |   图片加载 |   2015.3.15 |  未完成  |
|    [AndroidEventBus](https://github.com/bboyfeiyu/AndroidEventBus) | [AndroidEventBus](https://github.com/bboyfeiyu/AndroidEventBus) | [Mr.Simple](https://github.com/bboyfeiyu) |   		其他 |   2015.3.25 |  未完成  |








