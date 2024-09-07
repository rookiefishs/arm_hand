# 机械臂仿真项目

### 技术栈

1. vite
2. vue3
3. Threejs

### 实现的功能

1. 手动调整机械臂各个关节的运动
2. 连接和断开机械臂设备
3. 回到初始视角位置
4. 动作模拟

### 机械臂结构

![机械臂结构](https://cdn.z.wiki/autoupload/20240907/mABl/1202X973/image.png)

### 使用 Threejs 动态渲染机械臂

首先创建场景、相机和渲染器，渲染器负责渲染场景和相机

##### 在场景创建之后，即可做以下事情：

1. 解析加载 3d 模型
2. 创建并添加光线
3. 创建并添加辅助线
4. 创建并添加网格地板

##### 在相机和渲染器创建之后，即可做以下事情：

1. 创建并使用控制器

##### 在场景、相机和渲染器创建之后，并且渲染器被添加到页面之后，即可做以下事情：

1. 渲染画面（renderer.render(scene, camera)）
