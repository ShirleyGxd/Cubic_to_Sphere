# Cubic_to_Ball

0、背景：
    
    这是我大四时《计算机图形学》这门课的课程项目，现在上传也主要是想对自己本科阶段做过的一些有趣、有意义的项目进行整理、保存和分享。
    
1、简介：
    
    这是一个利用openGL实现立方体渐变为球体的工程。
    
    code：所有的代码
    
    build：相应的VS工程（已搭建好openGL）

2、算法思想：
    
    1）将立方体三角网格化
    
    2）计算出三角网格化后的立方体上的每个点在对应球体上的相应点的位置
    
    3）设定变化的所需的帧数，将立方体上的点和对应球体上的相应点的位置之间均匀采样出每一帧对应的点的位置
    
    4）按顺序显示每一帧
    
    细节考虑：
    
    1）为了从各个角度看形变的过程，设置立方体保持旋转
    
    2）设定开始形变的命令为：鼠标点击一下
    
3、使用说明：
    
    1）打开build文件夹中的工程：cubic_to_ball.sln
    
    2）编译生成.exe文件
    
    3）运行.exe文件（不需要额外的命令），会弹出旋转立方体的显示窗口
    
    4）单击窗口内任意处，立方体开始渐变为球体
