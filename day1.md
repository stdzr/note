嵌入式就是将计算机嵌入到产品中，形成一体机的过程，是生活中绝大部分智能设备都是嵌入式  
嵌入式的就业方向很广，新能源，工业机器人，医疗仪器都能做，掌握MCU是干这些行业的基石  
其核心包含软硬件和通信协议(**UART,I2C,SPI,TCP/IP**)，硬件包括电子技术基础，MCU架构(**ARM Cortex-M,RISC-V,8051**)，外设与接口(**GPIO,UART,I2C,SPI,ADC/DAC,PWM,定时器，看门狗**)，电路设计基础；软件包括C，汇编，实时操作系统（**RTOS**），驱动开发（**ISR,DMA配置**），低功耗设计。

# 学习目标
掌握MCU设计，一体系统搭建，AI拓展  

**拼搏一百天，我要进QG**  

![photo](https://github.com/stdzr/note/blob/main/photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-02-02%20223810.png)  
## keil常用操作  
[视频](https://www.bilibili.com/video/BV1Mb411e7re?t=154.2&p=4)  
![](https://github.com/stdzr/note/blob/main/photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-02-06%20192827.png)  
![](https://github.com/stdzr/note/blob/main/photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-02-06%20192852.png)
![]()
![]()
![]()
![]()
## proteus常用元件图示和名称
### 1 SWITCH(一位开关)
### SWITCH 一位开关
### SW-SPST 一位开关
### SW-SPDT 两位开关  
![](https://i-blog.csdnimg.cn/blog_migrate/be157ff34c1842877e8328736b086792.png#pic_center)

### 2 CAP(无极性电容)  
![](https://i-blog.csdnimg.cn/blog_migrate/4d42df00cff60767481eca305420f466.png#pic_center)

### 3 CAP-ELEC(极性电容)  
![](https://i-blog.csdnimg.cn/blog_migrate/385fc16d499f625346183a64e1f627ef.png#pic_center)

### 4 CRYSTAL(晶振)  
![](https://i-blog.csdnimg.cn/blog_migrate/7187c6851b4fb8c7cf0f21646193e27e.png#pic_center)

### 5 LED-BIBY(发光二极管)  
![](https://i-blog.csdnimg.cn/blog_migrate/4692d48fd06bba0a3b7f5de809df0319.png#pic_center)

### 6 RES(电阻)  
![](https://i-blog.csdnimg.cn/blog_migrate/9407888de9dc2f31b54ecff56cf1d0a3.png#pic_center)

### 7 BUTTON(按钮)  
![](https://i-blog.csdnimg.cn/blog_migrate/c05bf9be5b85faee020451a5d78aa0ac.png#pic_center)

### 8 AT89C51(经典单片机)  
![](https://i-blog.csdnimg.cn/blog_migrate/cbd66fcdbe50de9e73b9b982b2904372.png#pic_center)

### 9 BUS(总线)
### 右侧:

### 总线模式->蓝色粗线:总线    
![](https://i-blog.csdnimg.cn/blog_migrate/f2cedc034064dd03586a08b22271566b.png#pic_center)


### 10 VCC(电源)
### 右侧:
### 终端模式->POWER:电源(默认+5v)
### 终端模式->GROUND:接地电源  
![](https://i-blog.csdnimg.cn/blog_migrate/bb5b2d4ebd04b81fbc81091a66e6ee35.png#pic_center)


### 11 GROUND(接地)  
![](https://i-blog.csdnimg.cn/blog_migrate/c906985cf48ec48999af45acbd3e26f9.png#pic_center)

### 12 BUZZER(蜂鸣器)
### device:通用蜂鸣器
### active:有源蜂鸣器，通过直流操作由声卡发声  
![](https://i-blog.csdnimg.cn/blog_migrate/9fa94a90b4d96543d199b3b8ba061ad0.png#pic_center)

### 13 74HC273(常用锁存器)  
![](https://i-blog.csdnimg.cn/blog_migrate/211dab925d515a9ec010857d758f8485.png#pic_center)

### 14 7SEG-MPX4-CA(共阳极数码管)
### cc表示共阴极,ca表示共阳极;  
![](https://i-blog.csdnimg.cn/blog_migrate/0b27b3ce44934de0856711239bf4668e.png#pic_center)

### 15 LM016L(常用液晶)  
![](https://i-blog.csdnimg.cn/blog_migrate/d14bd07aa44c6311af4e04e0b3d1e596.png#pic_center)

### 16 POT(滑动变阻器)
### POT-HG 滑动电阻（调整精度为1%）
### POT-LIN 滑动电阻（调整精度为10%）
### POT-LOG 滑动电阻（调整精度为10%）  
![](https://i-blog.csdnimg.cn/blog_migrate/22bc6654008b9fd8883e048e203e365d.png#pic_center)


### 17 RP2(排电阻)  
![](https://i-blog.csdnimg.cn/blog_migrate/b521e79c1c0b965c858de9f38063dc65.png#pic_center)

### 18 DAC0832(D/A转换器)  
![](https://i-blog.csdnimg.cn/blog_migrate/7d9e50b0e1a7008f979f3648c1145717.png#pic_center)

### 19 PNP(三极管)  
![](https://i-blog.csdnimg.cn/blog_migrate/b5c9d35e7950cc4163651b1c93aa0153.png#pic_center)

### 20 NPN(三极管)  
![](https://i-blog.csdnimg.cn/blog_migrate/7921eb7c65c3811cf1a7ccdb7aed7431.png#pic_center)

### 21 LAMP(灯泡)  
![](https://i-blog.csdnimg.cn/blog_migrate/4b00e4ea24ac822657243ce4058e5c7f.png#pic_center)

### 22 默认终端(一条线加一个空心圆)
### 右侧:

### 终端模式->DEFAULT  
![](https://i-blog.csdnimg.cn/blog_migrate/5d0cbc4c5249e7cf21608b38f9c60b68.png#pic_center)

### 23 双击导线形成的实心圆点
### 搭配网络标号使用(鼠标移动到导线上->右键属性->添加网络标号)  
![](https://i-blog.csdnimg.cn/blog_migrate/7a060bb91e9af56bc7031e2d67dea564.png#pic_center)


### 24 RX8(双列x8电阻网络)  
![](https://i-blog.csdnimg.cn/blog_migrate/6632b2d86b8c3313a8750ff5cecff597.png#pic_center)

### 25 SPEAKER(扬声器)
### device:不能发出声音  
![](https://i-blog.csdnimg.cn/blog_migrate/8b293b4bdb599fd41f431a7a1531c68b.png#pic_center)

### active:活动的,可以发出声音  
![](https://i-blog.csdnimg.cn/blog_migrate/6c9958ccfb3e62c8759606098a8d767b.png#pic_center)

### 26 OSCILLOSCOPE(示波器)
### 右边仪器->选择  
![](https://i-blog.csdnimg.cn/blog_migrate/74da09059e6f44137437370d046ef8c0.png#pic_center)

### 27 74HC154译码器  
![](https://i-blog.csdnimg.cn/blog_migrate/d47881823b46d1b5780f1ebf6ee3443f.png#pic_center)

### 28 NOT-非门(一个三角形前面有个圆圈)  
![](https://i-blog.csdnimg.cn/blog_migrate/6290ea2408836de7fbb488c96f499550.png#pic_center)

### 29 DIPSWC(拨码开关)  
![](https://i-blog.csdnimg.cn/blog_migrate/8c41607cc6062a9fa13213673a61c834.png#pic_center)

### 30 SW-SPDT(单刀双掷开关)  
![](https://i-blog.csdnimg.cn/blog_migrate/f55d87ea3901a0b0ee2e12f00764c06c.png#pic_center)

### 31 DIODE(二极管)  
![](https://i-blog.csdnimg.cn/blog_migrate/152529bcd06bb93547476576164ac441.png#pic_center)

### 32 VSINE(交流电源)  
![](https://i-blog.csdnimg.cn/blog_migrate/4a7b2655f6f85489745b4f54b8484b51.png#pic_center)

### 33 MOC3052(双向光耦)  
![](https://i-blog.csdnimg.cn/blog_migrate/90da81150b2dea94d4ee0ed75f9185b9.png#pic_center)

### 34 TRIAC(三端双向可控硅开关)  
![](https://i-blog.csdnimg.cn/blog_migrate/54b663a805673cb351621fb3534ffbcd.png#pic_center)

### 35 G2R继电器系列  
![](https://i-blog.csdnimg.cn/blog_migrate/b2a98cd22e90e332c9a685e73442b545.png#pic_center)

### 36 RELAY(继电器)  
![](https://i-blog.csdnimg.cn/blog_migrate/c50c9b82fe8621b6844ef1f773dfe3a1.png#pic_center)

### 37 7406(双极型晶体管)  
![](https://i-blog.csdnimg.cn/blog_migrate/fa8b6725222e310c49079b6e232be928.png#pic_center)

### 38 MATRIX-8乘8点阵  
![](https://i-blog.csdnimg.cn/blog_migrate/ce0df1abcb3caa2d693f4a799a894a45.png#pic_center)

### 39 TRAFFICLIGHTS(交通指示灯)  
![](https://i-blog.csdnimg.cn/blog_migrate/1b5373cacfd4a67fd4dd4ebb78966842.png#pic_center)

### 40 SW-ROT-3(单刀三掷开关)  
![](https://i-blog.csdnimg.cn/blog_migrate/db9cbfa051a8713a96143f77fa8411a7.png#pic_center)

### 41 PULSE(脉冲发生器)
右边->选择激励源模式  
![](https://i-blog.csdnimg.cn/blog_migrate/b3364d4947b361072fc965b29a44b270.png#pic_center)

### 42 SINE(正弦波发生器)  
![](https://i-blog.csdnimg.cn/blog_migrate/b96d5d0d80e3aaaf9bbeba5a350c5950.png#pic_center)

### 43 DIODE-LED(发光二极管)  
![](https://i-blog.csdnimg.cn/blog_migrate/2dc39376fc419637df98bf014483b496.png#pic_center)

### 44 PHOTODIODE(光敏二极管)  
![](https://i-blog.csdnimg.cn/blog_migrate/d5c7421c8ab8952ecd2900f4183739fb.png#pic_center)
### 本文为CSDN博主「kdnnnd」的原创文章
原文链接：**[https://blog.csdn.net/kdnnnd/article/details/122754372](https://blog.csdn.net/kdnnnd/article/details/122754372)**  
## 简单的LED串联电路  
![](https://github.com/stdzr/note/blob/main/photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-02-04%20181157.png)  
### 点亮
![](https://github.com/stdzr/note/blob/main/photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-02-04%20181204.png)  
## Proteus中调用keil生成的hex文件  
### 选中并双击MCU
![](https://github.com/stdzr/note/blob/main/photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-02-05%20125438.png)  
![](https://github.com/stdzr/note/blob/main/photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-02-05%20125456.png)    
![](https://github.com/stdzr/note/blob/main/photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-02-05%20125505.png)  
### 调试project
![](https://github.com/stdzr/note/blob/main/photos/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202026-02-05%20125521.png)  


