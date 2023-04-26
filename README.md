# 项目文件介绍
目前上传的文件是人体识别的主体代码，其中：

python文件是用于识别人体并获取33个关键点的位置信息，作为服务端将信息上传；

c#文件中，UDPReceive.cs将Unity作为接收端，用于接收关键点的信息；

Body.cs用于处理关键点的信息，并改变场景中对应关键点物体的位置；

LineCode.cs用于在场景中链接各关键点。

# 版本控制介绍
Ver 1.0

制作了项目的主体框架，包括了有氧运动、训练课程、常规训练以及力量训练四个板块；

但具体功能还未完全实现。

Ver 2.0 

实现了人体的识别功能，使用python语言调用摄像头识别人体，并将人体信息传输到Unity中，以关键点的形式表现人体运动。
