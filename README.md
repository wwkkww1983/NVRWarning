读取海康等NVR摄像头信息然后并每隔一段时间进行截图并送入Tegu进行检测。
将返回的结果分为不同结果警告。

需要Tegu作为后端：http://www.giai.tech/#/index

9月3日新增：用Pygame播放警告音效。

9月25日新增：添加HOG监测物体是否被移动和火灾监测（高斯滤波）

10月17日新增：改进火焰检测/物体移动监测算法