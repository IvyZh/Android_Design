# Android_Design

### 1.什么是DPI？

> DPI（Dots Per Inch）：每英寸点数，表示指屏幕密度。是测量空间点密度的单位，最初应用于打印技术中，它表示每英寸能打印上的墨滴数量。较小的DPI会产生不清晰的图片。计算机屏幕一般采用PPI（Pixels Per Inch）来表示一英寸屏幕上显示的像素点的数量。


### 2.DPI(屏幕密度)计算公式

![](http://DPI计算公式)

### 3.PPI和DPI的关系

> PPI(Pixels Per Inch)：图像分辨率；是每英寸图像内有多少个像素点，分辨率的单位为ppi，通常叫做像素每英寸。

* dpi是dot per inch，每英寸多少点，ppi是 Pixel per inch，每英寸像素数，针对显示器的设计时，dpi=ppi；
* ppi计算方法是长宽各自平方之和开方，除以对角线长度（单位英寸）；
* ppi表示显示设备的点密度，dpi表示印刷品点密度。


### 4.安卓各屏幕密度

![](http://安卓各屏幕密度)



### 4.Android开发单位DP和SP

DP：安卓专用长度单位。以160 DPI屏幕为标注，则1DP=1PX

计算公式：dp x dpi/160=px

例：以720x1280px （320dpi）为例计算 1dp x 320 dpi/=2px

SP：安卓专用字体单位。以160 DPI屏幕为标注，则1SP=1PX

计算公式：sp x dpi/160=px

例：以720x1280px （320dpi）为例计算 1sp x 320 dpi/=2px


### 5. 单位定义总结

px：pixel———————————— 【 像素】  电子屏幕上组成一幅图画或照片的最基本单元

pt: point—————————————【 点】印刷行业常用单位，等于1/72英寸

ppi: pixel per inch————————【每英寸像素数】  该值越高，则屏幕越细腻

dpi: dot per inch—————————【每英寸多少点】，该值越高，则图片越细腻

dp: dip，Density-independent pixel, 【安卓开发用的长度单位】


### PX与DP、SP的换算


![](http://PX与DP、SP的换算)



### 6.ic_laugcher


	mdpi----48x48px---320x480
	
	hdpi----72x72px---480x800
	
	xhdpi----96x96px---720x1280
	
	xxhdpi--144x144px---1080x1920
	
	xxxhdpi--192x192px--3840x2160


备注：

> 安卓的图标相对iOS来说较少，我们只需提供以下几个尺寸就可以了，但是需要提高2套，圆角和直角各一套，因为有的地方都会用到。
512x512px、192x192px、144x144px、96x96px、72x72px、48x48px


### 7.安卓设计字体

> 英文字体为 Roboto字体，中文字体为 思源黑体。在Android 5.0之后，使用的是思源黑体，字体文件有2个名称，“source han sans”和“noto sans CJK”。



### 8. 常见主流手机尺寸和分辨率


> 分辨率方面1920x1080以及1280x720是应用适配占比最高。

参考链接：http://compass.umeng.com/?&utm_source=zzbanner#/equipment?_k=jmi4ox


### 9.标注

![](http://标注)


### 10.补充

- 安卓720*1280界面尺寸规范参考：
http://www.25xt.com/appdesign/9712.html


- 安卓1080P界面设计规范解读：
http://www.25xt.com/appdesign/9487.html


1080  *  1920px的设计规范：

![](http://1080P)

> 以上界面参数和尺寸仅作为参考


其他，
https://www.jianshu.com/p/961f08e2fc18

https://www.jianshu.com/p/c898edf90300


以上，

后续再补充。