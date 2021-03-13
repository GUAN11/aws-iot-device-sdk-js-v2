This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.         For more information, please check Tuya Developer Website.

一、方案标题
==

>鱼缸WIFI自动喂食器<br>

二、方案应用场景
==

* 2.1应用地点

>地点1：有中小型鱼缸的家庭或需要自动投喂的小型水族商店；<br>
>地点2：对弱宠物有强烈兴趣的家庭；<br>
>地点3：家中有需要定时喂养的需要的家庭，比如上班族，需要经常出去旅游的家庭<br>
>地点4：需要对水质有检测需求的群体，随时检测水质，提醒主人一键换水
* 2.2软硬件功能
  * 硬件功能<br>
   1.Tiny RTC硬件定时设计<br>
   2.涂鸦智能开发板IOT功能<br>
   3.直流电机旋转功能<br>
   4.红外/编码器测定直流电机旋转圈数<br>
   5.水质测定功能，一键监测水质TDS水质监测模块<br>
   * 软件功能<br>
   1.实现物联网定时/校准/喂食功能<br>
   2.实现操作直流电机旋转一圈的程序<br>
   3.能实现余粮提醒警告功能<br>
   4.检测水质，定时上传水质等信息<br>
  

三、开发计划
==

第1周：完成TDS水质采集模块和时钟模块，在IOT模块上实现水质的数值显示以及制定因人而异的最低水质容忍度提示，或通过定时器功能实现水质的定期检测
第2周：完成电机控制模块与语音播报模块，在IOT模组方面，可以实现手机连上WIFI后的电机控制，语音模组为扩展功能，方便调试或方便对语音播报有需要的人群
第3周：完成控制策略<br>，控制策略整体包括IOT与非IOT，IOT方面主要实现手机联网方面的控制，非IOT主要实现硬件底层整机的控制，完善底层逻辑结构
第4周：调试wifi收发功能<br>，整体调试软件与硬件，打印完整3D打印件，并进行整机装机
第五周：完成相应文档的编写，收集使用信息，最终为我家鱼缸服务。


四、工程文件位置
==

https://iot.tuya.com/pmg/step?id=itd6uiazo9adzkbq&tab=function
