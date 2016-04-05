VisionPicker
=====
* A simple oc value picker based on DownPicker(MIT License) which supports key-value selection
* 简单实用的基於DownPicker(MIT License)的二次封裝Picker（Selector/DropdownList/ComboBox）,实现选择结果键值分离

### Screenshots
![image](http://blog.viiio.com/wp-content/uploads/2016/04/visionpickerdemo_02.gif)

### Contents
## Installation 安装

* Just drag `VisionControl` folder into your project
* 将`VisionControl`文件夹拖入你的項目

### 在你需要使用Picker的文件中导入头文件:
```objective-c
#import "VisionPicker.h"
```
## Usage 使用方法
```objective-c
VisionPicker *picker = [[VisionPicker alloc] 
                        initWithFrame:CGRectMake(50, 100, 270, 40)
                        data:[@[[CboDataMODEL modelWithValue:@"ValueA" name:@"First Object"],
                                [CboDataMODEL modelWithValue:@"ValueB" name:@"2nd Object"],
                                [CboDataMODEL modelWithValue:@"ValueC" name:@"3nd Object"],
                                [CboDataMODEL modelWithValue:@"ValueD" name:@"4th Object"],
                                [CboDataMODEL modelWithValue:@"ValueE" name:@"5th Object"],
                                ] mutableCopy]];
picker.delegate = self;
[self.view addSubview:picker];
```

## Features 特性
* Support key-value selection by `CboDataMODEL`</br>
* Support autolayout.You could set frame to `CGRectZero`
* 利用`CboDataMODEL`实现键值分离</br>
* 支持Autolayout，可以在初始化时将Frame设定为`CGRectZero`</br>

## Requirements 要求
iOS 7 or later. Requires ARC  ,support iPhone/iPad

iOS 7及以上系统可使用. 本控件纯ARC，支持iPhone/iPad横竖屏
## More 更多 

Please create a issue if you have any questions.
Welcome to visit my [Blog](http://blog.viiio.com/ "Vision的博客")

## Licenses
All source code is licensed under the [MIT License](https://github.com/VIIIO/VisionPicker/blob/master/LICENSE "License").

