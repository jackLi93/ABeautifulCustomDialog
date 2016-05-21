##这是一个自定义的dialog项目


**自定义的dialog,具有如下特点**

-  圆角的dialog View
-  圆形图片的title

**效果图如下**

![dialog](http://upload-images.jianshu.io/upload_images/1307647-7c2a276dfcbb8551.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**实现原理**

-  首先，在Style中创建style,具体实现看源代码
-  然后，在代码中创建带有style的builder
-  自定义view
-  builder.setView(myView);