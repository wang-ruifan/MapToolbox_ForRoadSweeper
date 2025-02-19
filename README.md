# MapToolbox_ForRoadSweeper

Fork 自 [AutowareMapToolBox](https://github.com/autocore-ai/MapToolbox)，并对车道（lane）定义进行了修改，新增了 `IsSweep` 参数以支持 RoadSweeper 功能。

## 描述

这是一个 Unity 插件，用于为 [RoadSweeper](https://github.com/wang-ruifan/Road-sweeper) 项目绘制高精地图。  

## 需求

* Windows 10
* [Unity 2019.3.0](https://store.unity.com/download?ref=personal) 或更高版本
* [com.unity.entities](https://docs.unity3d.com/Packages/com.unity.entities@1.0/manual/index.html)
* [Git](https://www.git-scm.com/download/)

## 使用方法

* 在 Unity 中创建一个新项目
* 在 Unity 编辑器菜单栏中点击 Window -> Package Manager -> ➕ -> 通过 Git URL 添加包...
* 在文本框中粘贴以下 Git URL：

```
com.unity.entities
```

* 继续添加以下 Git URL：
  
```
https://github.com/wang-ruifan/MapToolbox_ForRoadSweeper
```

* 通过在项目面板中右键单击并选择导入新资产来导入 PCD
* 通过在层次结构中右键单击 Autoware -> AutowareADASMap 来创建新地图