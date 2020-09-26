# 计算机图形学学习笔记

本人目前在[人工智能与三维可视化实验室](http://www.ustb-ai3d.cn/index)做计算机图形学相关工作。此repo记录个人学习过程中遇到的问题和知识点的总结，包括计算机图形学，图像处理，C++等领域。

如果写的内容对您有帮助，或者帮您解决了棘手的问题，还希望一个``Star⭐️``。

当然，您有什么问题和意见都可以联系我，我的联系方式-微信：``douysuu``。 [邮箱：yindou97@163.com](mailto:yindou97@163.com)。我的知乎：[知乎地址](https://zhuanlan.zhihu.com/graphics-douysu) 

## 公众号

<img src="./result/gong.png" width = "500"> 

## 技术交流群

<img src="./result/wechat.png" width = "450"> 

<img src="./result/qq.png" width = "450"> 

# 目录
- [3D，OpenGL，图形学](#3dopengl%E5%9B%BE%E5%BD%A2%E5%AD%A6)
- [Shader着色器](#shader%E7%9D%80%E8%89%B2%E5%99%A8)
- [图像处理](#%E5%9B%BE%E5%83%8F%E5%A4%84%E7%90%86)
- [C++](#c)
- [算法](#%E7%AE%97%E6%B3%95)

## 3D，OpenGL，图形学

内容 | 介绍 | 
:-:|:-|
<img src="./result/PBR-OpenGL.jpg" width=200> | Physically Based Rendering-IBL（PBR基于物理渲染）<br>[[Video](https://www.bilibili.com/video/BV1TV411z7qe)] [[WebPage](https://zhuanlan.zhihu.com/p/176474625)] [[Code](https://github.com/douysu/graphics-algorithm/tree/master/physically-rendering)]
<img src="./result/IISPH.png" width=200> | Fluid Simulation(物理动画流体模拟) <br> [[Video](https://www.bilibili.com/video/BV1454y127Vy?from=search&seid=5825690446384116530)] [[WebPage](https://zhuanlan.zhihu.com/p/161808444)] [[Code](https://github.com/douysu/graphics-algorithm/tree/master/melt-animation)]
<img src="./result/tinyraytracer.jpg" width=200> | Ray Tracing（光线追踪) <br> [[WebPage](https://zhuanlan.zhihu.com/p/144189898)]  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/tinyraytracerYD)]
<img src="./result/render3.jpg" width=200> | Software Rendering（软渲染） <br> [[WebPage](https://zhuanlan.zhihu.com/p/141210744)]  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/tinyrendererYD)]
<img src="./result/curvature.png" width=200> | 3D Curvature（3D曲率原理及计算） <br> [[WebPage](https://zhuanlan.zhihu.com/p/112294045)]  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/3D-PLY)]
<img src="./result/skeleton.jpg" width=200> | 3D Skeleton Analysis（3D模型骨架提取及分析） <br> [[WebPage](https://zhuanlan.zhihu.com/p/112299945)]  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/3D-skeleton)]
<img src="./result/r9.gif" width=150> | 3D Medical Body（医疗项目3D人体展示系统） <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79241519)]  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/moving-light-strip)]
<img src="./result/streak.gif" width=150> | OpenGL MotionStreak（OpenGL拖尾、刀光、剑光、尾焰效果） <br> [[WebPage](https://zhuanlan.zhihu.com/p/112252151)]  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/streak)]
<img src="./result/wallpaper.gif" width=150> | 3D Aquarium（基于物理粒子系统的鱼群水族馆） <br>  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/wallpaper)]
<img src="./result/blur-scene-gaussian--3d.jpg" width=200> | 3D Scene Blur（OpenGL场景Blur虚化景深效果） <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79512208)]  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/blur-scene-gaussian--3d)]
<img src="./result/x-ray-scene_3d.png" width=200> | Multi-buffer X-Ray（多缓冲X-Ray人物透视效果） <br> [[Code](https://github.com/douysu/graphics-algorithm/tree/master/x-ray-scene_3d)]
<img src="./result/CameraRoam.jfif" width=200> | OpenGL Camera（OpenGL 摄像机漫游） <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79130876)]  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/CameraRoam)]
<img src="./result/opengles-uniform-buffer.jfif" width=150> | OpenGL Uniform Buffer Object（Uniform缓冲对象） <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79130517)]  [[Code](https://github.com/douysu/graphics-algorithm/tree/master/opengles-uniform-buffer)]



## Shader着色器

内容 | 介绍 | 
:-:|:-|
<img src="./result/r1.gif" width=200> | 关键帧动画效果顶点着色器的实现 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79152173)] [[Code](https://github.com/douysu/shader)]
<img src="./result/r2.gif" width=200> | 树干弯曲顶点着色器实现 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79151382)] [[Code](https://github.com/douysu/shader)]
<img src="./result/r3.gif" width=200> | 旋转扭动效果顶点着色器实现 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79141241)] [[Code](https://github.com/douysu/shader)]
<img src="./result/r4.gif" width=200> | 波动效果顶点着色器的实现 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79139315)] [[Code](https://github.com/douysu/shader)]
<img src="./result/r5.gif" width=200> | 扭曲效果顶点着色器的实现 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79171289)] [[Code](https://github.com/douysu/shader)]
<img src="./result/r6.gif" width=200> | 膨胀效果顶点着色器的实现 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79171410)] [[Code](https://github.com/douysu/shader)]
<img src="./result/zhuan.png" width=200> | 砖头墙壁纹理片元着色器实现 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79187023)] [[Code](https://github.com/douysu/shader)]
<img src="./result/shu1.png" width=200> | 着色器滤镜、图像卷积与滤波、数字图像处理 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79192901)] [[Code](https://github.com/douysu/shader)]
<img src="./result/r10.gif" width=200> | 体积雾特效的使用 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/79251244)] [[Code](https://github.com/douysu/shader)]


## 图像处理

内容 | 介绍 | 
:-|:-|
<img src="./result/radon.png" width=200> | radon直线检测及绘制直线 <br> [[WebPage](https://blog.csdn.net/ModestBean/article/details/89632272)] [[Code](https://github.com/douysu/algorithm/tree/master/image-processing)]


## C++

内容 | 源代码位置 |  
:-:|:-:|
[C++ 高级数据类型枚举Enum](https://blog.csdn.net/ModestBean/article/details/79173704) | [源代码位置](https://github.com/douysu/c-code) |
[C++ 函数内联inline](https://blog.csdn.net/ModestBean/article/details/79178943) | [源代码位置](https://github.com/douysu/c-code) | 
[C++ 泛型编程—Template模板](https://blog.csdn.net/ModestBean/article/details/79562998) | [源代码位置](https://github.com/douysu/c-code) |
[C++ 复数类complex解析](https://blog.csdn.net/ModestBean/article/details/79592468) | [源代码位置](https://github.com/douysu/c-code) |
[C++ 常量总结-const](https://blog.csdn.net/ModestBean/article/details/84995798) | [源代码位置](https://github.com/douysu/c-code) |
[C++ const常用用法-提高程序的健壮性](https://blog.csdn.net/ModestBean/article/details/85007434) | [源代码位置](https://github.com/douysu/c-code) | 
[C++ 内存管理——堆（stack）栈（heap）](https://blog.csdn.net/ModestBean/article/details/85258980) | [源代码位置](https://github.com/douysu/c-code) |
[C++ 内存管理——常见的内存错误及对策](https://blog.csdn.net/ModestBean/article/details/85344851)| [源代码位置](https://github.com/douysu/c-code) |
[C++ 内存管理——指针参数传递内存](https://blog.csdn.net/ModestBean/article/details/85375163) | [源代码位置](https://github.com/douysu/c-code) |
[C++ 实践细节总结](https://blog.csdn.net/ModestBean/article/details/86481072) | [源代码位置](https://github.com/douysu/c-code) |
[C++ 线程的基本使用方式](https://blog.csdn.net/ModestBean/article/details/90272892) | [源代码位置](https://github.com/douysu/c-code) |
[C++ 拷贝函数C++标准库复数类string解析](https://blog.csdn.net/ModestBean/article/details/90273092) | [源代码位置](https://github.com/douysu/c-code) |


## 算法

内容 | 源代码位置 |  
:-:|:-:|
[ACO蚂蚁寻路最短路径TSP问题](https://blog.csdn.net/ModestBean/article/details/101852092)| [源代码位置](https://github.com/douysu/algorithm/tree/master/ACO_aunt_optimal_path) |
