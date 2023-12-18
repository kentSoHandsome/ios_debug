# ios_debug
ios 常用断点记录
<img width="399" alt="image" src="https://github.com/kentSoHandsome/ios_debug/assets/152961018/075b4ef0-303e-4410-9bef-4fcbf8aba8c8">

# 符号断点
> 查看显示的controller是哪一个
```
-[UIViewController viewWillAppear:]
```

> 监听点击方法，执行的是哪一个函数。
```
-[UIControl addTarget:action:forControlEvents:]
```

> reveal UI调试神器的LLDB配置。

<img width="476" alt="image" src="https://github.com/kentSoHandsome/ios_debug/assets/152961018/22aca9c4-90b8-4ea4-8513-b5786c7cbe4f">

> 符号是`UIApplicationMain`,然后配置debugger 命令`reveal load --autostart`



