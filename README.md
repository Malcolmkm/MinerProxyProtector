# MinerProxyProtector
本程序可用于minerProxy303版本，用于修复303版本崩溃漏洞，防止其遭受攻击崩溃导致用户掉线，修复303版本后门，使用简单,目前仅支持windows版本。

## 如何使用？
1. 首先打开303程序本体 设置好抽水端口
2. 关闭303程序
3. 将保护器放入303程序目录
4. 打开保护器(以管理员身份运行)
5. 保护器启动完成后打开303本体即可

注意: 运行时强制关闭保护器会导致303所有连接闪断

## 注意事项
1. 保护器开启后添加的抽水端口不会被保护
2. 保护器开启和关闭都会导致303所有连接闪断
3. 请先打开保护器再打开303程序, 否则可能出现未知错误

## 软件原理
运行后将扫描303程序收发的所有流量, 识别到恶意流量后在数据包到达程序以前将其拦截

## 授权方式
支持12小时试用, 一机一授权, 绑定机器永久有效

## 购买方式
Telegram私聊购买: @Minerofeth

诚招代理, 分成详谈, 量大优惠

## 效果
在一台被持续攻击的机器上的测试:
![image](https://user-images.githubusercontent.com/98759471/152011573-9435ec00-f5a2-4f3e-b8e5-a25a3d15a1ac.png)
