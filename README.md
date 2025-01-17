# WOW-OS

这是一个纯列表的多级菜单，从 WouoUI - Lite_General 改进而来，优化了动画效果，简化了配置步骤。

虽然起名 OS ，但其实只是一个简单的任务生命周期管理器。
  
因为定义了硬件和编写框架，也因为对一些简单的设备来说这些足够用了，所以臭不要脸起名为 OS。
  
演示视频：https://www.bilibili.com/video/BV1Kp4y1J7WG/

注意，使用此项目需接受GPL协议的传染性。

# 功能特性

与 WouoUI - Lite_General 相比，减少的功能和特性：

* 主题切换：去除了白色主题滤镜
* 列表循环：去除了选择框在头尾继续操作时，跳转至另一头的功能
* 任意行高：去除了支持屏幕高度与行高度不能整除的特性，这个版本需要能够整除
* 背景虚化：去除了弹窗背景虚化的可选项

与 WouoUI - Lite_General 相比，增加和有区别的功能和特性：

* 展开列表动画从Y轴展开改为X轴排队进入
* 进入更深层级时，选择框从头展开改为跳转
* 层级跳转时，不需要等动画完成就能移动选择框
* 增加选择时拖影，滚动越快拖影越长，XY轴都有拖影
* 增加跳转时拖影，跳转越远拖影越长，XY轴都有拖影

# 开源协议

此项目使用的开源协议为GPL，以下简单解释权利和义务，详情请参考文档

权利：

* 不限制数量的复制
* 不限制方式的传播
* 允许增加，删除和修改代码
* 允许收费，但以服务的形式

义务：

* 新项目也要开源，不能通过代码本身盈利
* 新项目也要使用该许可证
* 出售时要让买家知道可以免费获得

# 赛博乞讨（划掉
开发不易，如果有帮到你，请我喝杯咖啡可好
![1697424547928](https://github.com/RQNG/WOW-OS/assets/115459678/835b1445-0fd1-44cb-b22a-aa9df6803039)

# 版本更新

## v 1.1

* 升级了版本号

## v 1.0

* 精简 WouoUI - Lite_General
* 增加选择框拖影特性
* 优化框架
