# VideoBeautify

1.Support video recording as well as import from photo album.  
2.Support multi themes process(Filter, Text effects, Animation effects...).  
3.Support saving the video to photo album.  

功能酷似美拍,秒拍等应用的源码：对视频进行各种美化处理，采用主题形式进行分类，内含各种滤镜，动画特效和音效等。  
Tested on iPhone 4 and iPhone 5S.  

Johnny Xu(徐景周)  
Future Studio

Demo 1    
<img src="https://github.com/xujingzhou/VideoBeautify/blob/master/Resource/Demo/Demo2.gif" width = "300" height = "500" alt="Demo" align=center />

Demo 2   
<img src="https://github.com/xujingzhou/VideoBeautify/blob/master/Resource/Demo/Demo.gif" width = "300" height = "500" alt="Demo" align=center />

‘’‘
关于该工程报错,我遇到的主要是GPUImage,YoukuUploader这两个静态库文件问题,首先是GPUImage报错说是,找不到相关的文件路径,解决办法可以参考一下博客链家地址(http://www.cnblogs.com/S2-huai/p/3881349.html),按照第一种方式解决的,需要将工程里面的GPUImage.xcodeproj重新编译成功.如果你遇到了YoukuUploader.xcodeproj文件报错:   "YoukuUploader.h" 这个文件找不到,就需要修改一下VideoBeautify这个工程的Header Search Paths(Build Seting选项中),我修改的是路径:$(SRCROOT)/Dependencies.再者真机调试者需要自己的开发者帐号了. 
’‘’
