# Blender笔记

课程网址链接🔗

https://www.bilibili.com/video/BV14u41147YH/?spm_id_from=333.337.search-card.all.click&vd_source=dec0df5946c5a4e7864de4bc96371c49



## 模型三要素

模型、灯光、摄像机



## 视角操作

- 以物体为中心移动视角 = 鼠标中键
- 移动视角 = shift + 鼠标中键
- 放大缩小视角 = 鼠标滚轮
- 点击右侧小工具<img src="Blender笔记.assets/Screenshot 2025-08-05 152851.png" style="zoom:50%;" />



## 模型操作

- 点击左侧小工具<img src="Blender笔记.assets/image-20250805153241711.png" alt="image-20250805153241711" style="zoom:50%;" />
- 删除模型 = x/DEL
- 新建模型 = shift + a
- 移动模型 = g
- 只沿x/y/z轴移动模型 = g + x/y/z
- 缩放模型 = s
- 只沿x/y/z轴缩放模型 = s + x/y/z
- 旋转模型 = r
- 只沿x/y/z轴旋转模型 = r + x/y/z
- 撤销移动/缩放/旋转 = alt + g
- 隐藏模型 = h
- 撤销隐藏模型 = alt + h
- 隐藏没有被选中的模型 = shift + h
- 移动复制 = shift + d
- 多种选择模型的方式<img src="Blender笔记.assets/Screenshot 2025-08-05 162603.png" style="zoom:50%;" />
- 吸附网格移动 = g + ctrl + 鼠标拖动



## 切换视图

- ～
- alt + 按住中键并拖动鼠标
- 点击右边的xyz顶点<img src="Blender笔记.assets/Screenshot 2025-08-05 162900.png" style="zoom:50%;" />
- 数字键盘



## 方便地调整摄像头

选中摄像头后，按N，进入视图并选择锁定摄像头![](Blender笔记.assets/截屏2024-05-19 21.24.40.png)



## 基本工作流

建模->布光->材质->渲染



## 管理工作区页面

- 鼠标移到工作区角落上，出现十字后，往自己的方向拉 = 分裂出自己的新工作区，往别人的方向拉 = 把别人合并为自己的新工作区。

  选择顶栏加号以新建工作区，右键删除以删除工作区。<img src="Blender笔记.assets/Screenshot 2025-08-05 164226.png" style="zoom:50%;" />

- 最大化当前选中的工作区 = 鼠标左键选择工作区 + ctrl + space



## 游标操作

游标的作用：用于模型定位/用作模型的原点。

- 控制游标 = 在选择模式下 shift + 右键
- 切换到游标模式  = shift + 空格 + 空格
- 控制所选物体到游标 = shift + s
- 游标定位至世界原点 = shift + c
- 在模型上方选择变换轴心点 = <img src="Blender笔记.assets/image-20250805171135497.png" alt="image-20250805171135497" style="zoom:50%;" />



## 改变模型的原点

blender只通过原点来识别模型。

1. 选中模型并勾选原点 = <img src="Blender笔记.assets/image-20250805171715977.png" alt="image-20250805171715977" style="zoom:50%;" />
2. 选择模型，按g



## 以鼠标为视角放大缩小中心

<img src="Blender笔记.assets/image-20250805175416277.png" alt="image-20250805175416277" style="zoom:50%;" />



## 选择物体为旋转中心

<img src="Blender笔记.assets/image-20250805175530975.png" alt="image-20250805175530975" style="zoom:50%;" />



## 变换轴心点

- 边界框中心
- 3D游标
- 各自的原点
- 质心点：重心点
- 活动元素：最后选中的那个模型



## 坐标轴切换

1. g + x/y/z是全局坐标
2. g +  x/y/z +  x/y/z是局部坐标
3. 单独查看选中物体 = /



## 禁用内容被选中

1. 用<img src="Blender笔记.assets/Screenshot 2025-08-06 091458.png" style="zoom:50%;" />