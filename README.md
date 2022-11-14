# AndroidProjectRenovation
Android Open Project Renovation/Android开源项目翻新/Android开源项目传承

# 简介：本项目创建的主要目的是收集一些使用者众多，但是官方已经停止维护/长期不维护，由本人或其他开发者进行翻新的Android开源项目，主要解决项目在新环境下不可用的问题，有翻新需求的Android项目，可以提相关issue，翻新主要涉及以下几个方面  
1. 编译工具翻新
2. 依赖翻新
3. Bug修复

# Android开源项目
1. Arouter  
 💪 A framework for assisting in the renovation of Android componentization (帮助 Android App 进行组件化改造的路由框架)  
原工程：  
https://github.com/alibaba/ARouter  
翻新工程：  
https://github.com/jadepeakpoet/ARouter  
翻新项：  
1.迁移到androidx，对于本库可关闭jetifier(android.enableJetifier=false)或不做配置  
2.适配到AGP7.3.0，解决其中的兼容性bug  
3.升级依赖的第三方库  
4.在jitpack发布本库  

2. vlayout  
VirtualLayout是一个针对RecyclerView的LayoutManager扩展, 主要提供一整套布局方案和布局间的组件复用的问题。  
原工程：  
https://github.com/alibaba/vlayout  
翻新工程：  
https://github.com/jadepeakpoet/vlayout  
翻新项：  
1.迁移到androidx  
2.升级插件和依赖库  
3.把库发布到jitpack  
4.修复LinearLayoutHelper设置margin和padding后，页面从下到上滚动导致的margin和padding显示出错的问题  

3. walle  
Android Signature V2 Scheme签名下的新一代渠道包打包神器  
原工程：  
https://github.com/Meituan-Dianping/walle  
翻新工程：  
https://github.com/Petterpx/walle  
翻新项：
1.已适配到了 Agp7.0.4 ,理论上 7.x 都可以。
2.迁移到androidx
3.升级依赖的第三方库
4.在jitpack发布本库 

