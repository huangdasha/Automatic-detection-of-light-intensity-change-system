这是一个通过环境变化自动化调节LED灯亮度系统，它意在节能，用最少的电能发挥出最大的用处。

以下是它具体的功能：
1、Esp8266 的 wifi 链接云平台，手机可登录云平台查看当前灯的开关状态、当前亮度、有无出现故障、led 的电压电流、温湿度
2、可实现远程开、关灯
3、如果led 处于开的状态但是检测不到电流，则蜂鸣器叫，同时发送报警信息到云平台提示，oled 也显示出现故障
4、按键可设置光强阈值，高于阈值且有人的情况下自动调节led 亮度，无人情况下直接最
低亮度维持
5、0led 显示当前的 电压电流、有无故障、开灯和关灯时间、温湿度

手机蓝牙界面：
![de3db491ba0b008cf6fd946eea7a072](https://github.com/user-attachments/assets/cb65996a-f9e2-40da-88ab-e0bbf10a3417)


oled界面：

![image](https://github.com/user-attachments/assets/26e63644-6d43-4a27-bec7-f77e69606bba)
