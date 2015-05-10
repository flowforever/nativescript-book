# 模块-modules

[原文地址](http://docs.nativescript.org/modules)

关于模块,NativeScript的官方文档写了很多，简单来说，其实NativeScript也是使用node.js的包管理机制，如果你熟悉node.js这个章节你可以不用花费太多时间只需要了解一下NativeScript提供了那些跨平台的Module给我们使用，以后的章节我也会详细介绍每一个Module。

1. 核心模块(Core Modules)
2. 设备功能模块(Device Functionality Modules)
3. 数据模块(Data Modules)
4. 用户界面相关模块(User Interface Modules)
    * 布局(Layouts)
    * 组件(Widgets)

##核心模块

* application 
* console
* locale-settings
* http
* image-source
* timer
* trace
* ui/image-cache


##设备功能模块
* camera 
* location
* platform
* fps-meter
* file-system
* ui/gestures

##数据模块
* data/observable
* data/observable-array
* data/virtual-array

##用户界面相关模块

* ###布局
  * ui/layouts/stack-layout
  * ui/layouts/grid-layout
  * ui/layouts/absolute-layout
  * ui/layouts/wrap-layout 
  

* ###组件
    * ui/activity-indicator: Provides the ActivityIndicator class which represents a widget for showing that a service is currently busy.
    * ui/button: Provides the Button class which is a standard button widget.
ui/label: Provides the Label class which is a standard label widget.
    * ui/text-field: Provides the TextField class which represents an editable single-line box.
    * ui/text-view: Provides the TextView class which represents an editable multi-line line box.
    * ui/list-view: Provides the ListView class which represents a standard list view widget.
    * ui/image: Provides the Image class, which represents an image widget.
    * ui/progress: Provides the Progress class which represents a progress or loading indicator.
    * ui/scroll-view: Provides the ScrollView class which represents a scrollable area that can show content which is larger than the visible area.
    * ui/search-bar: Provides the SearchBar class which represents a standard search bar component.
    * ui/slider: Provides the Slider class which represents a standard slider component.
    * ui/switch: Provides the Switch class which represents a standard switch component.
    * ui/tab-view: Provides the TabView class which represents a standard content component with tabs.
    * ui/web-view: Provides the WebView class which represents a standard browser widget.
    * ui/dialogs: Lets you show various dialogs such as alerts, prompts, confirmations and others.
    * ui/list-picker: Provides the ListPicker class which represents a standard list picker component.
    * ui/date-picker: Provides the DatePicker class which represents a standard date picker component.
    * ui/time-picker: Provides the TimePicker class which represents a standard time picker component.
    * ui/placeholder: Provides the Placeholder class which lets you add a native widget to the visual tree.
