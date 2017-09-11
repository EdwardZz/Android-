#    首页框架--TabLayout布局搭建


## 1.关于MainActivity布局界面的一些操作：
加载远程库‘com.android.support:design:24.2.0’

点击‘同步’按钮;打开MainActivity的布局文件，将没用的清理掉。

布置线性布局，并修改命名空间，方便后续使用。  
加入TabLayout布局代码，设置id和属性。  
加入ViewPager的布局代码，设置id和属性。  
代码如下图：  
![](image/MainActivity_Layout.png)  

## 2.关于主界面逻辑代码的书写：
- 申请几个私有变量mTablayout mViewPager mTitle mFragment
- 分别写初始化数据函数和初始化View函数
- 初始化数据中需要包含mTitle的文字信息以及mFragment的几个布局的添加。
- 初始化View函数中需要包含mTabLayout和mViewpager的id加载，  
然后进行预加载，设置适配器，设置标题以及绑定。




## tips:
- ctrl+Alt+L可以规范化代码
- 通过settings设置文件头可以让你构造类的时候更清晰



