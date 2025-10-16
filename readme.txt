中文：
数据集用于LoRa链路损耗估计
实验区域：中国广东省深圳市深圳大学
网关地点：深圳大学科技楼天台（G1）、科技楼2楼（G2）、致理楼天台(G3)、致理楼地面（G4）、紫薇斋天台（G5）
csv文件信息：RSSI、SNR、经度、纬度、高度
RSSI、SNR可以计算LoRa定义的一个“预期信号功率（ESP）”指标
经纬度信息可以通过坐标变换、空间投影等处理对应到图像的像素点上
高度可以作为辅助信息输入到深度学习模型，以便更好学习链路特征



英文
Dataset used for LoRa link loss estimation.

Experimental site: Shenzhen University, Shenzhen, Guangdong, China

Gateway locations: 
Shenzhen University Science and Technology Building rooftop (G1),
2nd Floor, Science and Technology Building (G2),
Zhili Building rooftop (G3),
Zhili Building ground floor (G4),
Ziweizhai rooftop (G5)

CSV file information: Packet ID, RSSI, SNR, acquisition time, longitude, latitude, and altitude
RSSI and SNR can be used to calculate the "Expected Signal Power (ESP)" metric defined by LoRa.
(Longitude, Latitude) can be mapped to pixels on the image of the study area.
Height can be used as auxiliary information to input into the deep learning model to better learn link characteristics