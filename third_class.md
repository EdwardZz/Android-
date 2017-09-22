#   关于floatingActionButton控件的使用



## 1.更改下MainActivity的页面布局文件并设置属性设置：  
id alignParentButton alignParentRight mariginButton   
margnRight(如果有图片可以加载下图片)

## 2.在MainActivity的逻辑文件下：
申请一个private FloatingActionButtton变量，在initView函数下  
进行初始化（加载id）。并调用setonclickLisener函数设置监听函数。  
完成后在外面进行onClick函数的编写：
```
public void onClick(View v){
switch(v.getId()){

case R.id.fab_setting:
          startActivity(new Intent(this, setting_Activity.class))
	  break;

}
}
```

##  tips: 
某个活动如果编写好了类与布局，是需要在主xml文件中进行注册的  
alt+enter可以将文字资源直接添加进value文件夹中  


