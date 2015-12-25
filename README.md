# JavaScriptCore iOS

## Binaries

A compiled version of the `JavaScriptCore.framwork` for armv7, armv7s, arm64 and the Simulator can be found in the root directory.

## How to Compile

1. Run `python make.py`.
2. Get coffee! Building this takes a while ;P

You can do `python make.py --help` for more options.


支持 JSContext JSValue  等  OBJC API

修改了编译选项 ， 有些地方是用 OS X 的代码，改为了 iOS代码，使用 xcode6.4 编译成功。   xcode 7.2 还没有试。   我直接把编译好的framework 传上来了， 可直接使用。 最低支持版本 5.1.1

bitcode 还未开启

使用时候需要导入 libc++, libicucore

自己还参试在iOS6 下面运行了  React-Native 的Demo  2048

![](http://img.blog.csdn.net/20151225134912312)
![](http://img.blog.csdn.net/20151225134919291)