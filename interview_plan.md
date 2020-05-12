# 复试准备

## 不熟悉的知识点

- [x] 手写快排
- [x] 堆排序原理：建堆、输出节点（排序）、新增节点
- [x] 树的基本性质
- [x] 平衡二叉树的调整
- [x] 图的基本概念
- [x] 图的存储方式
- [x] 哈弗曼树相关概念：带权路径长度最短的树
- [x] Dijkstra算法流程
- [x] B-树、B+树
- [x] 贪心算法：整体最优解可以在求局部最优解的过程中得到（最小生成树的两个算法，Dijkstra算法）
- [x] Hash相关概念
- [x] 静态分区分配算法
- [x] 动态分区分配算法：首次适应、最佳适应、最坏适应、邻近适应
- [x] TLB定义与查询流程
- [x] 虚拟存储：对内存的逻辑扩充，__基本分页 + 请求调页 + 页面置换__
- [x] Cache相关概念
- [x] 进程调度算法
- [x] 页面置换算法：最佳、FIFO（Belady异常）、LRU、时钟（访问位、修改位）
- [x] 磁盘调度算法
- [x] 死锁产生的必要条件：互斥、请求和保持、不剥夺、循环等待
- [x] 数据库三范式、BC范式
- [x] CSMA/CD的争用期
- [x] 数据链路层协议：PPP（无编号和确认，不可靠）、HDLC（有编号和确认，可靠），只支持全双工
- [x] 网络层协议：IP、RIP、OSPF、BGP
- [x] 传输层协议：TCP、UDP
- [x] 应用层协议：HTTP、SMTP、FTP、DNS
- [x] CDMA原理
- [x] ICMP协议——`ping`命令
- [x] 中断、DMA、通道：DMA在一个存取周期结束后开始，期间CPU不访存
- [x] 中断隐指令：关中断->保存断点（PC）->引出中断服务程序
- [x] C语言声明和定义：如果一个变量或函数的声明（Declaration）要求编译器为它分配存储空间，那么这个声明也称为定义（Definition）
- [x] C语言运算符优先级
- [x] C语言printf细节
- [x] C语言scanf细节
- [x] 物理层设备：中继器、集线器
- [x] 数据链路层设备：网桥、交换机
- [x] 网络层设备
- [x] 数据库设计的几个阶段：需求分析->概念结构设计（E-R图）->逻辑结构设计（数据库表）->数据库物理设计->数据库的实施（编码、测试、运维）
- [x] 计算机存储介质：纸带、半导体、磁带、磁盘、光盘
- [x] 可屏蔽中断与不可屏蔽中断：打印机中断与电源掉电
- [x] SRAM与DRAM：是否需要刷新、用途、行列地址传送、容量、成本、速度
- [x] 广播风暴
- [x] 关系模型与二维表
- [x] 字符串和字符数组的区别：1.字符串是末尾元素为`'\0'`的字符数 2.字符数组每个字符可以修改，而字符串指针指向一个常量字符串（静态区）
- [x] 拥塞控制在哪一层：传输层TCP
- [x] malloc分配的内存在哪里：C语言共有：程序代码区、静态区（全局、静态、常量）、堆区（malloc等）、栈区、命令行参数区
- [x] 外部中断、内部中断：内中断来自于CPU内部且与当前指令有关，外中断反之
- [x] 生成树、最小生成树
- [x] 一趟快速排序需要比较多少次
- [x] 优先级队列：就是大（小）顶堆
- [x] 二叉排序树
- [x] TCP、UDP区别：是否面向连接、数据切片、用途、时延、开销
- [x] 自然连接：必须是同名列
- [x] 软件工程生命周期：可行性分析、需求收集和分析、概要设计（原型）、详细设计（用例）、编码实现、测试、运维
- [x] 冯诺依曼体系结构：运算器（核心）、控制器、存储器、输入、输出
- [x] 软件开发模式：瀑布（文档驱动）、迭代（子产品与小型瀑布）、螺旋（强调风险）、敏捷
- [x] UML图
- [x] 什么是文件系统：操作系统中负责存储和管理文件的软件机构
- [x] FAT
- [x] OS的三个指标：并发、共享、虚拟、异步
- [x] 怎么从外存取一个数：程序查询、中断、DMA
- [x] OSI英文中文全称：Open System Interconnection
- [x] OSI每层的作用：比特传输、冲突与设备识别、地址管理与路由选择、点对点传输、具体应用
- [x] 静态变量是什么：`static`变量位于静态存储区，全局静态变量文件内私有，局部静态变量只在函数第一次调用进行定义和初始化
- [x] 需求分析如何细分：功能性需求（领域相关）、非功能性需求（可靠性、性能指标、可维护性、可扩展性）
- [x] 编译型语言、解释型语言
- [x] 程序运行的过程
- [x] C++面向对象
- [x] 函数式编程：以映射为核心

## 组件库开发经验

## 英语复试常见问题

### Self-introduction

Good afternoon! My name is SheYufei. I' m from Zhengzhou, Henan province. I graduated from Yunnan University, major in software engineering. My GPA is 3.3 out of 4.0.
During my college days, I spent most of my time and effort on exploring the world of programming. In senior year, I had a six-month experience as an intern in a software company, focusing on web front-end developing. My work consists of universal component library developing and regular webpage implementation based on react.js.
The internship was not plain sailing. Both the content and the income of the job cannot meet my expectations. After serious consideration, I decided to join the postgraduate extrance exam to fight for a chance to dive deeper in the software engineering field. I believe after 2 or 3 years of solid learning and practice, I can become the best developer that I can ever be and make impressive contributions to the software industry. That's all, thanks for your attention.

### Hometown

Zhengzhou is the provincial capital of Henan. The famous Longhai Line and Jingguang Line crosses at this city. It grows rapidly from a small town governed by Kaifeng to a big modern city in less than a hundred years, thanks to the railway construction. It has four distinctive seasons. The people there are friendly and sometimes humorous. The whole Henan province mainly focused on agriculture in the past few decades, so there is not many tech componies in Zhengzhou. I believe in the future, my generation will have the strength to make our hometown a better city to live in. I love my hometown.

### Strength & Weakness

My strength is that when I fully set the goal I want, I will do my best to reach it. However, the weakness of mine is that I usually spend too much time to find the goal. Unnessessary thinking may let go of the precious chance.

### Family

My family has three members, my father, my mother and me. My father works for the State Grid and my mother worked for the National Textile Mills. They're both workers at the production line. In spare time, my father likes watching movies and my mother enjoys doing the square dance. They treated me not only as a son, but also as a friend, which I really appreciate. I respect my parents for their love and hard work, and I want to give them the best I can give with my own hands. I love my family.

### Hobby

Playing the guitar, mainly acoustic finger-style. I have been learning music theory to do coverings of the classic songs. Playing instrucments is a great way to express feelings and release the daily pressure. Apart from music, I like doing exercises like running and swimming. Doing sports keeps me energetic to consentrate on working and learning.

### Why this major / Why postgraduate

I really want to know how the computer works under the hood and how to develop a great software. Recently I've been using Visual Studio Code from Microsoft as my No.1 code editor. The beautiful user interface and excellent performance of this software gave me a fantastic coding experience. I want to develop softwares as good as it to both gain reputation and make profit, so I've still got many things to learn. Persuing a master's degree of software engineering is the best option for me.

### University

Yunnan University located in Kunming, the provincial capital of Yunnan province. It's a comprehensive university full of great majors. The teachers of software institute are decent and respectable. They have solid professional skills and taught me a lot about software industry. As for natural environment, the climate there is just at the sweet point and the air condition is one of the best in China. Green plants and cute animals can be found in the campus. The four years I spent there were absolutely precious. I love my alma mater.

### Why ustc

First, I believe in the power of science and technology, and these two concepts are just in the name of this great university. Further more, theory and practice are the two main themes in  the teaching plan of ustc, especially the software institute. That's exactly what I need. I want to lay a solid fondation of programming and then use this fondation to develop the best software product that I can ever think of.

### Plans of Postgraduate study

First, I will follow the teaching plan and try to keep up. Then, I will find a direction that I am fully interested in as soon as possibile and spent spare time and effort to explore on this direction. Game developing is a great option for now. After laying a solid fondation, I tend to find an intern oppotunity of my interested direction to gain actual experience at the software production line. Finally I will learn from the experience to optimize my workflow and produce a gradution paper of high quality representing my engineering skills. That's the plan for now.
