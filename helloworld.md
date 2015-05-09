# HelloWorld

#通过NativeScript CLI创建一个Hello World

http://docs.nativescript.org/hello-world/hello-world-ns-cli

如果你已经搭建完NativeScript开发环境那么就可以开始动手写一个NativeScript的Hello World程序了.

本文你将学习到:
* 如何新建Project
* 如何添加用户界面(View)
* 如何创建一个ViewModel
* 如何为你的App添加修改样式

## 新建Project

第一步,创建NativeScript Project
```
tns create hello-world
```
第二步,添加相应的App平台(Android或者iOs)
```
cd hello-world
tns platform add ios
tns platform add android
```
这步操作使用native SDK初始化以及生成一些平台相关的内容在 platforms 目录.然后NativeScript CLI会使用native sdk的一些工具编译这些平台相关项目文件到真正的native应用包里面.与此同时NativeScript CLI会自动从 app 目录拷贝跨平台的代码到平台相关项目目录.

第三步，在设备或者模拟器上面运行NativeScript程序

```

tns run ios // 在ios设备上面运行hello-world
tns run android

tns emulate ios // 在ios设备上面运行hello-world
tns emulate android // 该命令等同于 tns run android --emulate
```

![android preview](http://docs.nativescript.org/img/getting-started/step3-android.png)
![ios preview](http://docs.nativescript.org/img/getting-started/step3-ios.png)












