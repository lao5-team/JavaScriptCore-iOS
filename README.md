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