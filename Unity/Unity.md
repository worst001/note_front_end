# Unity

[文档](https://docs.unity.cn/cn/current/Manual/index.html)

## 界面

### 面板

+ Project
    > 项目资源面板
    + 控制场景中物体所在的坐标系
    + 程序运行面板类似Linux 的 Htop
    + 资源菜单

+ Hierarchy
> 层次面板
    + Camara 组件
        + 摄像机表示玩家看到的画面
    + 粒子组件
        + 微粒子散发渲染画面
    + Text 组件
    + 灯光组件
        + 全局光照
            > ( 太阳光、平行光 )
        + 点光
            > ( 某个点向四周发光 )
        + 光束
            > ( 放射形光照 可控制散射角度 )
    + 物体组件
        + 几种常用的形状
        + 材质设置
        + 碰撞检测轮廓
    + 精灵组件
        + 多个微图片组成的小动画
    + 地形组件
        + 地形贴图
        + 控制地形高地(造山)
        + 添加树木、草地
        + 添加风向

+ Scene
> 场景面板

+ Game
> 游戏面板

+ Inspector
> 检视面板

### 工具条

+ 变换工具
+ 变换切换
+ 播放控件
+ 视图

## 脚本
![组件结构图](file:///Users/hanwenhao/Cloud/笔记/Unity/组件结构图.png)

### 响应组件
[交互函数](https://www.bilibili.com/video/BV19x41127BP?p=43)

## 生命周期

### Update
> 监测每一帧变化
> 用于非物理运动的变化

### FixedUpdate

> 每隔固定时间调用一次
> 用于物理运动的变化

