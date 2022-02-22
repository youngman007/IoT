SDK version:2.0.0实验简介
	实验内容: 温湿度监控接入OneNet（ESP8266 WIFI模块接入）
	MDK版本 : 5.15
	开发板：STM32F103
	固件库  : STM32Cube_FW_F1_V1.8.3

  实验功能
	利用ESP8266模块，无线连接路由器，通过MQTT协议接入中国移动的OneNet平台，远程监控温湿度，
	以及温湿度报警阈值的下发控制，实现开发板和平台的双向数据通信。

SDK version:3.0.0实验简介
	实验内容: 安防报警MQTT接入腾讯云IOT（W5500以太网接入）
	MDK版本 : 5.15
	开发板：STM32F103
	固件库  : STM32Cube_FW_F1_V1.8.3

  实验功能
	利用板载W5500网络，用网线连接开发板和路由器，通过MQTT协议接入腾讯云IOT平台，
	采集上传温湿度、热释电信息，以及布防报警模式（触发蜂鸣报警）的设置，实现开发板和平台的双向数据通信
	手机端支持腾讯连连小程序、腾讯连连APP

SDK version:4.0.0实验简介
	实验内容: 智慧路灯MQTT接入TLink（4G无线接入）
	MDK版本 : 5.15
	开发板：STM32F103
	固件库  : STM32Cube_FW_F1_V1.8.3

  实验功能
	利用4G模块，通过MQTT协议接入TLink物联网平台，远程监控实地光照度传感，自动/手动控制光照阈值及开关的下发控制，
	实现开发板和平台的双向数据通信
	支持的4G模块为SIM7600CE/A7600C1，A7600C1为CAT1网络模块
	手机端支持TLINK小程序、TLINK APP

SDK version:5.0.0实验简介
	实验内容: 智慧物流接入阿里云（4G无线接入）
	MDK版本 : 5.15
	开发板：STM32F103
	固件库  : STM32Cube_FW_F1_V1.8.3

  实验功能
	利用4G模块，通过MQTT协议接入阿里云IOT平台，上传GPS定位或基站定位信息，GPS定位精度3米左右，
	支持仿真模式，此模式下模拟GPS的数据变化，在地图上生成轨迹，用于调试，4G模块为SIM7600CE/A7600C1，其中A7600C1为CAT1网络模块
	支持IOT Studio制作的WEB网页及手机App端网页
	
	注：常用的定位有GPS定位和基站定位，GPS定位使用的是国际坐标系，基站定位使用的是国内定位
	
SDK version:6.0.0实验简介
	实验内容: 智慧农业接入阿里云（NBIOT无线接入）
	MDK版本 : 5.15
	开发板：STM32F103
	固件库  : STM32Cube_FW_F1_V1.8.3

  实验功能
	利用NBIOT模块，通过MQTT协议接入阿里云IOT平台，采集上传温湿度、光照信息，
	以及相应的开关控制，阈值设置等等，实现开发板和平台的双向数据通信，NBIOT模块为BC28
	支持IOT Studio制作的WEB网页及手机App端网页
