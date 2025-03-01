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
## 2024.6.4
高数＋线代，抽空去竞选了无协的技术总监（doge）
## 2024.6.5
今晚搓电子工艺，完成了51和32的通信，可以玩点新花样了
## 2024.6.6
做了几个简单的功能：密码锁，温度报警，定时器时钟，旋转编码器调参，基于lcd1602的多级菜单，菜单显示仍有bug
## 2024.6.7
写电路分析报告。下周要交5篇电路分析报告+谐振电路仿真，数电课设＋实验报告，电子工艺验收+实验报告，还要考4级。干就完了。
## 2024.7.15-7.21
承接期末考前进度，开始学习机器人建模。跟着文档在RVIZ中创建了两轮差速模型。URDF里面的代码看不懂。在Gazebo里面给之前的两轮差速车建模，加了仿真插件。想下载一些Gazebo的物体模型，没想到硬盘空间不够了，只能重装Ubuntu。下载了jazzy版本的ros，Ubuntu是24.04的.学习了什么是栅格地图，salm的图优化算法，了解了动态规划的A*算法。添加了cartographer配置文件进行建图，遇到了bug，得找找问题
## 2024.7.22-7.28
用c8t6把平衡车给弄了，调参花的时间比较久，还烧坏了一个TB6612。本来想着用蓝牙遥控的，后面改用ps2手柄了，软件spi，延迟的话还行。
## 2024.7.29
navigation 2导航实战
## 2024.9.8
希望队友也能每天写好日报，一起进步

***violate关键字:***

和const相对应，告诉编译器该变量是易变的，可能会以其它形式改变
violate修饰的结构体，其成员也是violate修饰

***register关键字:*** 

建议变量放入寄存器，不放在内存中，提高效率（可能会继续放在内存中）
适用：局部变量，不会被写入的，需要被高频读出的
注意：该变量不能取地址&，不要大量使用register

***大津法:***  

得到灰度直方图，有两个峰值，代表白色与蓝色，提取尖峰之间的值作为阈值，找到可cv的代码，需要啃下来

***边线提取:***  

看了基础的提取中线。有空研究一下八邻域，迷宫法，逆透视

***PID:***       

电机PID，舵机PD 前期调电机PID主要是小P大D，借助tft，IPS进行二值化图像显示，用按键进行调参，上位机显示PID曲线（在赛道上调，空转调没什么用）

***入库出库：***       

提取行列的黑白跳变信息，电机开环处理，考虑要不要用imu，对角度积分进行处理（画板子的时候可以留一个位置）

***舵机机械中值设定：***  

小车左轮贴着直线，给一个初速度，能直线行走，记录此时pwm的值
## 2024.9.11
这两天跑例程。根据error提示发现之前用的江科大的MDK版本过低，重新下了一个。然后去安装pack，发现没有芯片对应的。一编译有50条报错，都是启动文件的问题。后来在ASM改了设置就行了，解决完第一个困难。
## 2024.9.15
继续学习逐飞开源库
复习extern：`extern void pit_handler();` 这一行代码的作用是声明一个外部函数 `pit_handler`，该函数没有参数并返回 `void` 类型。具体来说，它的作用包括：

1. **外部链接**：`extern` 关键字表示该函数是在其他文件中定义的。这意味着 `pit_handler` 函数的实现可能在另一个源文件中，而不是在当前文件中。

2. **函数声明**：通过声明 `pit_handler`，编译器知道在当前文件中可以调用这个函数。这样可以在当前文件中使用 `pit_handler()`，而不需要在当前文件中提供其具体实现。

3. **模块化编程**：使用 `extern` 声明可以帮助实现模块化编程，使得不同的源文件可以相互调用函数。这种方式有助于代码的组织和重用。

4. **避免重复定义**：通过在一个文件中定义函数并在其他文件中声明，可以避免函数的重复定义，从而减少编译错误。

总之，`extern void pit_handler();` 是为了在当前文件中使用 `pit_handler` 函数，而该函数的具体实现可能在其他地方。
https://blog.csdn.net/qq_41709234/article/details/122984203?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522B87FE643-9318-4A84-92A6-D4253FBAA274%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=B87FE643-9318-4A84-92A6-D4253FBAA274&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-122984203-null-null.142^v100^pc_search_result_base5&utm_term=extern%E7%94%A8%E6%B3%95&spm=1018.2226.3001.4187
## 2024.9.16
解决机械问题，编码器难换，螺丝根本拆不下来马勒戈壁
## 2025.2.22
大二下学期马上开始了，有一段时间没有写学习日志。这学期竞赛很多，不同竞赛需要的技术栈不同，横跨数字、模拟、嵌入式、c++，专业课也很多，希望能抗住。还需要思考，学习的深度和广度如何去兼顾。回顾自己学了什么东西，有什么感悟，有什么收获。一定要加油！！！，这是个重要的节点！！！

**蓝桥杯FPGA**：
实现了可调pwm，仿真验证通过。目前是占空比可调，频率可调还没有实现，fpga本身不支持浮点数运算，要想一下别的方法。仿真时出现了***高阻态Z、不定态X***的问题。***高阻态***是因为位宽没有定义。input cnt时默认cnt位宽是1，用电脑自带的计算机计算1000的二进制位数，给cnt加上位宽高阻态解决。***说明在初始化每一个变量时都应该想好它的位宽，这不仅可以减少bug，还可以减少资源占用，优化时序。***   ***不定态X***通常是因为信号没有初始的值导致的。pwm_generate里input [6:0] duty（这里的duty我在一开始也没给位宽，有Z的问题）在always直接赋给了pwm_num，那我就在top文件中初始化一个reg [6:0] r_duty，复位是0，其它情况是top中input的值。在仿真中，对这个input值多次改变，观察pwm占空比，是正确的，不定态解决。

**后续的任务是**：1、完善pwm代码，支持可调频率2、在pwm代码基础上支持上位机通过uart修改FPGA中的pwm参数（今天看的模拟题三就涉及了uart）3、修改模拟题二中eeprom的读写时序 4、设计一个系统能调度板子上的所有外设

**智能车**：
今天开始cpp多线程的学习，今日主要是理论学习：

1、线程和进程的概念：线程是进程的子集。进程与进程不同地址，多个线程一个地址。进程抢占时间片去完成任务，这个叫分时复用，每次切换都要保存进度，下一次抢到时间片就可以接着上一次的进度继续弄。处理多任务用线程更好。可以用rtos的任务调度和FPGA的并行去辅助理解。子线程瓜分栈空间，子线程没了，栈释放了，那么里面数据也没了。 

2、线程id类型unsigned long；线程库名；如何创建线程:pthread_create(传出参数（线程id），线程属性（默认，用null），线程调用的函数，这个函数需要传入的参数)；主线程和子线程的关系，执行顺序是怎样（回顾自己敲的代码），主线程main先抢到时间片，如果主线程执行完了，释放了地址空间，那么子线程也没了，如果主线程执行太快可以加sleep（）函数；linux编译gcc -l pthread 

3、线程退出函数pthread_exit（想要传出的参数，是一个地址），如果主线程退出（在main里调用这个函数），这个地址还在，那么子线程可以继续执行 

4、子线程结束，主线程回收子线程占用的资源（内核资源），pthread_join(回收子线程的id，指向传出函数参数一级指针的二级指针（也就是一级指针的地址）)，每次回收一个子线程，谁回收子线程，谁就能得到子线程传出的参数。这是个阻塞函数，子线程在运行这个函数就阻塞在这。想得到子线程里的东西，这个东西可以声明全局或者放到主线程的栈（在main里声明）上，如果东西在栈里声明，子线程没了，栈释放了，那么里面数据也没了，就得不到了。

5、线程分离 pthread_detach（子线程id），在主线程main里调用，主线程与子线程分离了，主线程虽然退出，但是不释放子线程的内核资源，当子线程结束，其内核资源被系统其它线程接管回收。使用场景比如：想要回收子线程资源，用pthread_join，但是它会阻塞在那里，你想让主线程去做其它事情，这时候效率很低了。线程分离后，子线程资源不由主线程回收了，在主线程使用pthread_join也回收不了子线程资源。注意：主线程进行线程分离，要跟上pthread_exit，让这个地址还在，子线程可以继续执行，否则主线程没了地址没了子线程没地址活不了

6、线程取消pthread_cancel（子线程id），在一个线程调用pthread_cancel杀死另一个线程时，线程不会立刻死，当该线程进行系统调用，踩到地雷，才会死

***遇到的问题：1、指针，指针的类型，指针指向哪里 2、堆，栈，内存等数据结构的问题***
## 2025.2.23
**智能车**：
今日是理论学习：

1、线程同步（互斥锁、读写锁、条件变量、信号量）：干某件事的时候让多个线程按照先后顺序依次执行，虽然费时了，但是数据会更安全。例子：从硬盘取数据，经过cache，到cpu。线程A抢到时间片开始工作，并把该工作的结果发回硬盘。时间片结束后，线程B进行工作，我们想让他接着A上次的工作继续弄，但是A有数据没来得及发回硬盘，还在cache中，导致出错了。

***2、互斥锁：*** 被锁住的代码块，所有线程只能顺序执行它，不能并行处理。互斥锁类型： pthread_mutex_t 可得到：锁是开还是关，锁的主人是哪个线程（只有锁主人才能够解锁）
创建：pthread_mutex_init(互斥锁变量地址，互斥锁属性（默认为null）)  销毁：pthread_mutex_destroy(互斥锁变量地址) 加锁：pthread_mutex_lock（互斥锁变量地址），如果被锁定了，加锁失败，线程都会阻塞在这把锁上  pthread_mutex_trylock（互斥锁变量地址）,与前面不同的是，如果尝试加锁失败，线程先去干别的事，然后再回来尝试加锁，如果尝试加锁失败，线程又去干别的事 解锁：pthread_mutex_unlock（互斥锁变量地址）

加锁和解锁函数中间是临界区，在线程同步期间，要保证锁对应的资源是有效的（比如临界区处理全局变量，全局变量不会消失）

流程：main外声明互斥锁变量，main内声明线程变量，初始化互斥锁，创建子线程，pthread_join，销毁互斥锁

3、死锁：所有线程被阻塞，无法解开，因为锁主人也被阻塞了

***原因：*** 1、主人加锁忘记解锁  2、重复加锁  3、有多个共享资源，很多把锁，随意加锁（资源个数=锁数）比如A有B室的钥匙，B有A室的钥匙，当A锁在A室 B锁在B室，就死锁了

***解决方法：*** 1、检查代码逻辑  2、加锁时使用trylock  3、对其它互斥锁进行加锁前，把自己的互斥锁释放掉，让别人可以加锁  4、引入检测死锁的模块

***关于互斥锁如何工作可以回去看视频理解***

4、***读写锁：*** 类型： pthread_rwlock_t 记录信息：锁是开还是关，锁的主人是哪个线程（只有锁主人才能够解锁），锁是read还是write

读写锁特点：1、读锁锁定临界区，线程并行访问，读是共享的2、写锁锁定临界区，线程串行访问3、***写锁优先级大于读锁，读线程和写线程来了，读线程被阻塞***   因此大量读操作用读写锁，大量写操作用互斥锁

创建：pthread_rwlock_init(读写锁变量地址，读写锁属性（默认为null）)  销毁：pthread_rwlock_destroy(读写锁变量地址)  加锁：pthread_rwlock_rdlock(读写锁变量地址）本身是读锁，加锁成功；本身是写锁，阻塞  pthread_rwlock_tryrdlock(读写锁变量地址）本身是读锁，加锁成功；本身是写锁，加锁失败，线程先去干别的事，然后再回来尝试加锁，如果尝试加锁失败，线程又去干别的事
pthread_rwlock_wrlock(读写锁变量地址）本身是读或写锁，阻塞  pthread_rwlock_trywrlock(读写锁变量地址）本身是读或写锁，加锁失败，线程先去干别的事，然后再回来尝试加锁，如果尝试加锁失败，线程又去干别的事  解锁：pthread_rwlock_unlock(读写锁变量地址）

***读写同步需要动手练习***

5、***条件变量：*** 用于处理生产者消费者模型类型，配合互斥锁使用，进行多个线程的阻塞  类型：pthread_cond_t

创建：pthread_cond_init(条件变量地址，读写锁属性（默认为null）) 销毁：pthread_cond_destroy(条件变量地址)  阻塞后不唤醒，就一直阻塞：pthread_cond_wait(条件变量地址，互斥锁地址)
阻塞一定时间后就解除阻塞：pthread_cond_timewait(条件变量地址，互斥锁地址，超时的时长（结构体，秒＋纳秒）)，如何定义阻塞时长回顾视频代码  唤醒至少一个阻塞的线程：pthread_cond_signal(条件变量地址)  唤醒所有阻塞的线程：pthread_cond_signal(条件变量地址)

***遇到的问题：1、数据结构，链表知识不熟 2、生产者消费者模型理解不透彻***

## 2025.2.25
**智能车**：
生产者决定容器上限，消费者决定容器下限；生产者填满容器阻塞，消费者消费完容器堵塞，二者通过条件变量通信

**蓝桥杯FPGA**：
eeprom读写出问题，top的读写控制用ila测试感觉没问题，那么应该是i2c控制部分出了问题，需要仿真解决

## 2025.2.26
**集创赛**：
结束噪声章节，开始学反馈

**智能车**：
1、***信号量：*** 用于解决生产者消费者模型 头文件<semaohore> 类型：sem_t 

创建：sem_init(信号量变量地址，0线程同步/非0进程同步，信号量拥有的资源数)，生产者和消费者各创建一个变量  
销毁：sem_destroy(信号量变量地址)
sem_wait（信号量变量地址）判断信号量的资源数，>0不阻塞，资源-1，=0阻塞
sem_trywait（信号量变量地址）判断信号量的资源数，>0不阻塞，资源-1，=0不阻塞，返回错误号，去做别的事然后再回来看资源是否为0
sem_post（信号量变量地址） 信号量的资源数+1
sem_getvalue（信号量变量地址） 查看信号量的资源数

## 2025.2.27
**智能车**：
学习如何在生产者消费者模型中使用信号量，资源是怎么互动的。当资源大于1，需要启用线程同步。锁应该加在sem_wait的下边，加在上面会造成死锁。

已经大致学习完理论内容，后续开始敲代码实践，可以上力扣刷刷题什么的

**集创赛**：
1、继续学习反馈章节

2、了解linux computer里文件夹内容：
bin：存放系统命令的可执行文件，比如ls、cp等。
boot：存放系统启动时需要的文件，比如启动加载器的配置文件和内核文件。
dev：存放设备文件，比如硬盘、终端等。
etc：存放系统配置文件，比如passwd、group、fstab等。
home：存放用户的主目录，每个用户都有一个自己的子目录，比如/home/user1。
lib 和 lib64：存放库文件，lib是32位库，lib64是64位库。
media：用于挂载外部存储设备，比如U盘、光盘。
mnt：手动挂载文件系统的挂载点，比如手动挂载一个分区。
opt：可选软件包的安装目录，一些大型软件或第三方软件会安装在这里。
proc：虚拟文件系统，存放进程和内核的相关信息，比如/proc/cpuinfo。
root：超级用户的主目录，存放root用户的个人文件和设置。
run：系统运行时的文件，比如进程ID文件。
sbin：存放系统管理命令的可执行文件，比如shutdown、reboot等，通常需要管理员权限。
srv：服务数据的存放目录，比如Web服务器的数据。
sys：虚拟文件系统，用于访问和控制系统硬件设备，比如/sys/class/gpio。
tmp：临时文件的存放目录，系统和应用程序可以在这里存放临时数据，系统重启后这些文件会被清空。
usr：用户程序和数据的存放目录，包含子目录如/bin、/lib、/include等。
var：可变数据的存放目录，比如日志文件、缓存文件等，/var/log存放系统日志文件。

3、启动文件：
calibre：存放验证文件
models：电路仿真需要的文件
tsmc18rf：工艺库
display.drf：图层颜色显示文件
skill：
在这个文件夹打开virtuoso

4、复习命令：pwd 、cd 、ls（-a）、ctrl-l 、mkdir 、mv 、cp(-r) 、ln -s、rm（-r）

5、vi编辑:vi 文件名创建文件；i插入文字，回车换行，方向键移动光标；esc退出当前模式；：wq保存退出，：w保存不退出，：q退出，：q！不保存退出；a在光标右边写文本，A在行最右边写文本,I在行最左边写文本，o在下一行编辑，O在上一行编辑;：set nu显示行数，：set nonu显示行数，：想跳转的行数；x删除光标处文本，X删除光标前一处文本，D删除光标处与该行后面的文本，u撤销操作，ctrl+r恢复撤销；光标在行首，dd删除该行，2dd删除该行与下一行，以此类推；r替换一次文本，R连续替换文本；yy+p复制黏贴；/c在文本中查找c这个文字，以此类推，按n向下查找下一个c；？c在文本中查找c这个文字，以此类推，按n向上查找下一个c；：%s/d/D/g将d全部替换为D   ：1，4 s/d/D/g将一至四行d全部替换为D     ：4 s/d/D/g将第四行d全部替换为D

## 2025.2.28
**集创赛**：
继续学习反馈章节

修改简历，也是对之前学习内容的回顾。向学姐讨教了很多简历修改的问题，大有启发

## 2025.3.1
**集创赛**：
跟着B站课程学习原理图绘制，瞬态、dc仿真；快捷键使用

**社团**：
学会如何从小程序中导出报名名单

找学姐修改简历



