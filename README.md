# SystemVerilog_Demo
# <b><font size = 4> <center> 目录 <center> </font><b>

[toc]

***

## <b><font size = 4><font face = "楷体"> <center> 第一章 验证导论 <center> </font><b>

<font size = 2><font face = "宋体">
1、硬件验证语言(Hardware Verification Language, HVL)

2、HVL同HDL相比的典型特点：

    (1)受约束的随机激励生成
    (2)功能覆盖率
    (3)更高层次的结构，尤其是面向对象编程
    (4)多线程以及线程间的通信
    (5)支持HDL数据类型，例如Verilog的四状态数值
    (6)集成事件仿真器，便于对设计施加控制

3、验证的目的：确保设备能够成功地完成预定的任务

4、测试平台用途在于确定待测设计的正确性。包含下列步骤：
    
    (1)产生激励
    (2)把激励施加到DUT待测模块(Design Under Test)上
    (3)捕捉响应
    (4)检验正确性
    (5)对照整个验证目标测算进展情况

5、定向测试能够找出设计中预期漏洞，而随机测试能偶找出预料之外的漏洞

6、使用随机激励时，需要用功能覆盖率来评估验证的进展情况

7、
</font>





## <font size = 4> <center> 第二章 数据类型 <center> </font>

<font size =3><font face = "黑体">
 硬件验证语言(Hardware Verification Language, HVL)
</font>

