# my_diary
记录一下日常学习进度
## 2024.4.29
学习了用hal库写串口中断，pwm输出。安装了opencv库（Python）
## 2024.4.30
学习了opencv（c++）：mat，imread，imshow，waitkey，nameWindow，cvtcolor，imwrite，尝试配置vscode opencv （cpp）没成功，先用studio学着
## 2024.5.1
复习期中考内容
## 2024.5.2
放假，晚上回家继续复习
## 2024.5.3
实现hal库的k210与32通讯。调舵机，知道了180度和360度舵机的区别，360度舵机控制角度的话要控制时间
## 2024.5.4
调了一下舵机，整合一下机械臂姿态解算代码
## 2024.5.5
确定了舵机角度的位置，为控制机械臂做准备
## 2024.5.6
再次阅读机械臂开源的代码，理清设计思路。观看华南虎战队的视频，初步学习了pid原理
## 2024.5.7
结合案例分析pid的具体应用，尝试对舵机进行p调节
## 2024.5.8
复习期中考
## 2024.5.9
复习期中考
## 2024.5.10
复习期中考
## 2024.5.11
写机械臂代码框架，一直写到12点半
## 2024.5.12
学习opencv的API：
mat：：zeros（）   mat：：ones（）   Scalar（）
打算5.6月份在学习32的同时学一下ros
## 2024.5.13
因为学ros2的时候感觉有很多命令行的意思不太清楚，打算先补一下linux基础
学习了linux：ls命令
晚上在源代码写入了apriltag二维码识别功能，等拿到k210再跑一下代码，进行修改
## 2024.5.14
学习了linux：cd、pwd、mkdir创建文件夹
touch创建文件、cat查看文件内容、more翻页查看文件内容（空格翻页）
ctrl+l清屏
晚上学了直立环和速度环的pid，为电子工艺搓平衡小车作准备（可能吧）
电机方面一直想学，等校内赛结束找个时间看看
## 2024.5.15
学习了linux：cp复制文件 mv移动文件 rm删除文件 *通配符进行模糊匹配
su - root切换root用户 exit退回普通用户
在root情况下不要用 rm -rf /和 rm -rf /*
## 2024.5.16
备战校内赛
## 2024.5.17
备战校内赛,还有很多参数没调
## 2024.5.18
今晚因为装车，有时间学一下电机驱动模块
了解了H桥驱动电路，怎么使电机电机正反转
编码器测速原理
## 2024.5.19
跟着鱼香ros学习用oop编写ros2节点
痛苦的机械臂调参，运动路径还要规划，预估在实际比赛场地可能还会有新问题
## 2024.5.20
这周整合代码，让队友用freertos给我堆了个任务，等参数调好后将函数写到任务内
熟悉了一下stm32f4
## 2024.5.21
了解了话题与服务通信机制，用rqtgraph查看话题，CLI工具，如何编写话题发布者
；备战校内赛
；买了做平衡车的相关外设，校赛结束就搞电子工艺课设
；和队友讨论机械臂代码
## 2024.5.22
校内赛很寄，昨晚给队友展示了机械臂的demo，发现核心舵机的力不够，转不到对应角度，导致机械臂不能很好的执行代码的命令。机械臂没搞好，k210可能也发挥不出作用了。
可能要使用保底方案了（doge）
## 2024.5.23
昨晚调夹子，发现舵机有时转有时不转，但是舵机用其他程序试过是好的，以为是代码问题。最后发现5个舵机同时供电，给夹子舵机的电压根本不够，但是其他舵机供电又可以。最后测试单独给几个舵机供电效果很好。现在主要是两个问题，舵机的扭矩不够和电压不足，佛了，亏我调半天代码。
今天攻克16路舵机驱动模块PCA9685，pwm分辨率应该够用了
## 2024.5.24
调车
## 2024.5.25
看校内赛大佬表演。通宵调车，原本采用f1和f4双机串口通讯，但是没搞定。最后采用了两个ps2手柄操作。本来都调好了，早上7点的时候关键舵机齿轮损坏，ps2遥控接收器被烧坏，导致晚上写的机械臂功能完全不能实现。后来也只能根据场地情况让机械爪一直摆动，小组第二晋级8进4,三等奖。搞完校内赛回归导航学习，不想被硬件折磨了
## 2024.5.26
补作业,晚上用cpp编写话题发布者和订阅者，相关API还不熟悉，要多看ros2官方文档
## 2024.5.27
今天补作业＋校内赛颁奖，速通了一下光学的测验，看ros2官方文档回顾一下之前学习的内容，顺便增强英语阅读能力
## 2024.5.28
高数＋线代＋修板子＋4级备考，一直到晚上11点50才有时间看ros。浅浅看了一下什么是接口和自定义接口，接口相关的CLI。上b站了解了CMakeLists里相关代码的含义，之前对cmake有什么用还没有一个很清晰的概念，只知道它是一个构建工具
## 2024.5.29
用TB6612和L298N成功驱动减速电机，晚上被高数电分数电一起折磨，准备渡劫
## 2024.5.30
学习课内知识，备考。编码器电机测速还没搞定
## 2024.5.31
学习课内知识，备考。植物大战僵尸杂交版是真好玩
## 2024.6.1
ddl大战
## 2024.6.2
继续ddl大战
## 2024.6.3
大物，大雾
