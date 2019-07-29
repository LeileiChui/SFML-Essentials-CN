## 目录

### 第一章:开始使用 SFML

* 创建窗口
  * 视频模式
  * 风格
  * 环境设置
  * 禁用鼠标光标
* 游戏循环
* 事件处理
  * 窗口相关事件
  * 键盘相关事件
  * 鼠标相关事件
  * 操纵杆相关事件
  * 使用事件
* 形状渲染与转换
  * 渲染帧
  * 形状绘图
  * 形状转换
  * 控制形状
* 总结

### 第二章:加载和使用纹理

* 加载纹理
  * 图像与纹理
  * 创建图像
  * 创建纹理
* 用纹理渲染形状
* 什么是精灵图（sprite）
  * 形状和精灵图
  * 变形与绘图
  * 精灵图的最终实例
* 管理资源
* 总结

### 第三章：精灵图动画

* 捕捉时间
  * sf::Time和 sf::Clock
* 精灵图操作
  * 设置
* 创建动画
  * 使用动画
  * 多重动画 
* 总结

### 第四章：操控一个2d camera

* 什么是camera
  
  * 什么时候使用camera
  * SFML如何实现camera

* 使用sd::View操控camera
  
  * 旋转和缩放视图 
  * 视角viewpoints
  * 映射坐标

* 什么是 OpenGL
  
  * 应该使用 OpenGL 的情况

* 在SFML中使用 OpenGL
  
  * 在多重窗口中的 OpenGL

* 总结
  
  ### 第五章：探索声音和文本的世界

* 音频模块-概述、

* 声音与音乐

* 音频操作
  
  * sf::Sound 类
  * 介绍AssetManager 2.0
  * sf::Music 和 sd::SoundStream

* Sf::SoundSStream和 3D 音频
  
  * 常见音频特征
  * 3D音频
    * 创建listener（监听器）
    * 音频资源
    * 总结音频特征

* 开始使用sf::Text
  
  * AssetManager 3.0

* 总结

### 第六章：使用着色器渲染特殊效果

* sf::RenderTarget 和sf::RenderWindow
* 对纹理直接渲染
* 着色器编程
  * 什么是着色器
  * 加载着色器
  * AssetManager 4.0
  * 使用着色器
  * 设置着色器样式 
  * sf::Shader 和 OpenGL
* 把它们结合在一起
  * 设置渲染纹理
* 总结

### 第七章：构建多人游戏

* 了解 网络
  * 游戏中的网络
* 传输层-TPC与UDP
  * SFML中的TCP
  * SFML中的UDP
* 非阻塞socket
* 交换packets
  * 创建一个包
* 实现
* 摘要
