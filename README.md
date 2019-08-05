# Embedded-written-reference
+ 2019-参加过的嵌入式笔试题目和解析分享

+ Table of Contents
  =================

     * [Embedded-written-reference](#embedded-written-reference)
        * [Contents](#contents)
        * [7.30诺瓦科技](#730诺瓦科技)
        * [8.1大疆嵌入式参考](#81大疆嵌入式参考)
        * [8.3网易笔试](#83网易笔试)

## 7.30诺瓦科技

1. [总线之间的区别和联系?](https://luckywater.top/2019/07/29/SerialBus/)
2. [ARM 指令集可以分为哪六大类?](https://luckywater.top/2019/08/02/ARM体系结构/)
3. [ARM体系结构中的工作状态?](https://luckywater.top/2019/08/02/ARM体系结构/)
4. ARM 和EEPROM之间的通信方式是什么?当时有两个电阻没有焊接出错, 后面焊接完成就正确了?
   - 两个电阻属于上拉电阻; I2C的通信方式
5. [Linux的**用户态与内核态 **?](https://luckywater.top/2019/08/02/linux用户和内核/)
   1. Linux的用户态与内核态 定义?
   2. Linux的用户态与内核态 **如何切换**的? 
   3. Linux的用户态与内核态的**通信**方式?
6. [linux内核裁剪的方式?](/7.30诺瓦科技/linux内核裁剪的方式.md)
7. *未全部完成 --*    [进程间通信有哪几种方式?](https://luckywater.top/2019/08/02/进程间通信的几种方式/)
   1. 为什么进程间通信需要**内核**?
   2. 编程题: 进程间通信通过管道pipe实现?
8. [英文翻译: 关于时钟发生器的英文翻译?](/7.30诺瓦科技/关于时钟发生器的英文翻译.md)
9. 编程题: 通过互斥量实现线程间的通信?

## 8.1号大疆嵌入式参考

+ [参考](https://blog.csdn.net/qq_38410730/article/details/80951443)

1. [TCP与UDP的区别?](https://luckywater.top/2019/05/06/TcpIp/)

3. [OS**内存字节对齐** pragma pack()用法详解?](https://luckywater.top/2019/08/02/PragmaPack/)
1. 32位/64位的系统中, 各自的sizeof()是多少?
   
2. 数据类型间的混合运算, 最后的输出?
   
3. [OS大端和小端存储问题问题?](/8.1Dji大疆/大端小端存储问题.md)

4. [OS无锁可以提高整个程序的性能，但是CPU需要对此提供支持，请以x86/ARM为例简述](/8.1Dji大疆/cpu对锁的支持.md)

5. [OS多任务嵌入式系统中，将寄存器REGn的指定位反转](/8.1Dji大疆/OS嵌入式系统指定位反转.md)

6. [OS简述处理器中断处理的过程](/8.1Dji大疆/OS嵌入式系统指定位反转.md)

7. [OS简述 处理器读取内存的过程](/8.1Dji大疆/OS处理器读取内存的过程.md)

8. [OS系统设计](/8.1Dji大疆/)

9. [C语言的**各种变量的存取区域**，给你一段小程序，让你分析各个变量的存储区域?](/8.1Dji大疆/C变量存储区域.md)

10. [C中使用memcpy()系列函数时要足够小心?](/8.1Dji大疆/C函数使用注意.md)

11. [C语言**编译执行**的四个阶段?](/8.1Dji大疆/C语言编译执行的四个阶段.md)

12. [C简述实时操作系统和非实时操作系统特点和区别?](/8.1Dji大疆/C的static作用.md)

13. [简述**C函数中参数**传递问题](/8.1Dji大疆/简述C函数中参数传递问题.md)

14. [linux**目录结构**，选项是/usr、/tmp、/etc目录的作用?](/8.1Dji大疆/linux目录结构.md)

15. [linux系统打开设备文件，进程可能处于三种基本状态?如果多次打开设备文件，驱动程序应该实现什么?](/8.1Dji大疆/linux系统打开设备文件处于的状态.md)

16. *未全部完成 --*[Linux内核中常用的两个宏定义?](/8.1Dji大疆/linux内核中常用的两个宏定义.md)

17. [编程题:  实现一个循环缓冲区.](https://github.com/quronghui/DataStructAndAlogrithmCode/blob/master/CompanyWrite/1_Dji/circularReadWrite.c)

### 8.4 大疆笔试

1.  [C : 当char类型变量进行赋值时, 超过其范围时怎么处理?](https://github.com/quronghui/DataStructAndAlogrithmCode/blob/master/CompanyWrite/1_Dji/charConvertint.c)
2. [C: 有符号的变量(负数)和无符号的变量(正数)相加](/8.1Dji大疆/C 有符号的变量(负数)和无符号的变量(正数)相加.md)
3. [C: 如何实现一个数的四舍五入?]
4. [OS 结构体和联合体的**内存字节**对齐计算?](https://luckywater.top/2019/08/02/PragmaPack/)
5. *未全部完成 --* [OS并发: 可以通过哪些方法进行同步?](/8.1Dji大疆/OS并发的同步机制.md)
6. 

## 8.3网易笔试

1. [Linux 系统权限755 777 644 ?](/8.3网易/LInux系统权限.md)
2. 没做出来 -- [echo 重定义 和 grep 正则表达式匹配](/8.3网易/echo 重定义 和 grep 正则表达式匹配.md)
3. [Dijkstra最短路径算法的描述正确的是?](/8.3网易/Dijkstra最短路径算法的描述.md)
4. [TCP/ IP 数据传输中, 数据如何进行分包?](/8.3网易/TCP IP数据分包.md)
5. [二叉树8个度为2节点, 5个度为1节点 , 度为0有多少个节点?](/8.3网易/二叉树节点和度.md)