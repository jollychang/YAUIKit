YAUIKit
=======

YAUIKit 是一个复杂UI的实现库。其提供了多种复杂UI的实现和自定义。

## ChangeLog

#### v0.2.0
##### 合并YAToolKit，提供YAToolKit中的所有功能以下。
- Set Each Frame Property
- Set Each Bounds Property
- Remove the View all Subviews
- 提供使用16进制颜色值来获取颜色的方法
- 提供生成纯色UIImage的方法
- 提供可自定义动画的Pop & Push方法。

#### v0.1.0

- 第一次发布YAUIKit
- 提供带Place Holder的UITextView
- 提供可下拉刷新，上拉加载等功能的Controller
- 提供可自定义的Toggle
- 提供Block版本的AlertView
- 提供Block版本的ActionSheet
- 提供Block版本的PickerView
- 提供页面滑动后退Controller
- 提供可以全部自定义的SearchBar

## 添加到你的工程
#### 1.YAUIKit

将 `YAUIKit.xcodeproj` 图标拖拽到你的项目文件目录中。

#### 2.设置项目 Building Settings

点击 `项目` -> `(TARGETS)` 图标，在 `Build Settings` 里找到 `Other Linker Flags`, 设置为 `-ObjC`和`-all_load`。

#### 3.设置目标 Building Settings

同上，找到 Header Search Paths，添加

* ../YAUIKit/YAUIKit/Library
* ../YAUIKit/YAUIKit/Source

#### 4.添加依赖

点击目标(TARGETS)图标，选择 `Building Phases`。

在 `Target Dependencies`，添加 `YAUIKit`。

在 `Link Binary with Libaries` 中，加入下列库 `libYAUIKit.a`

#### 5.使用方法

`#import “YAUIKit.h”` 即可使用UIKit中的全部功能和View。

