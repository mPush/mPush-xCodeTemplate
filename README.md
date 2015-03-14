# mPush-xCodeTemplate
xcode template for mPush 


安装步骤：

1、下载zip包解压，或者 git clone

2、打开命令行工具，cd到文件夹所在目录

3、执行install.sh


如果不想使用sh来安装，可以将文件夹里三个xctemplate文件拷贝到：

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Xcode/Templates/Project Templates/iOS 目录下，重启xcode即可。


本模板内置了Podfile文件，如果不希望使用Cocoapods，可以删除PodFile文件，下载mPush SDK后加入项目工程。

无误完成后，可参考mPush集成文档中[配置MPushAppID](http://doc.mpush.cn/ios_guide.html#g5-3)步骤继续。