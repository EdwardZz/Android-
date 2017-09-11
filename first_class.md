#     项目架构部署


## 我们从哪些方面入手：
* Package  
* Application  
* Activity  
* Drawable  
* Values  
* UtilTools  
* StaticClass  

##具体步骤：
### 一
- 路径：app--src--main--java--com...  
- 新建package 分别命名为adapter application entity  
fragment service ui utils view.
- 在application包里重写Application类BaseApplication，使其继承自Application,  
重写onCreate方法,dakai Mainifest.xml文件，在Application注册信息里加入  
android:name=".application.BaseApplication"
- 在ui包里新建BaseActivity类继承自AppCompatActivity,重写oncreate方法
设置显示返回键并设置监听函数，实现点击就返回的效果
### 二
- 路径变为res
- 新建文件夹drawable-hdpi drawable-mdpi drawable-xhdpi  
drawable-xxhdpi drawable-xxxhdpi
- 新建values-zh文件夹，新建values-en文件夹
### 三
-路径回到一中建立的utils包下，新建一个utilTool工具类，StaticClass类

##tips:
settings--搜索code--file and code Temlates--class Header
