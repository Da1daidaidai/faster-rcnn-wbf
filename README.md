# faster-rcnn-wbf

对于fasterrcnn的训练

1. 如若需要训练自己的backbone，需要torch 1.10以上的版本
2. 训练自己的backbone需要在change_backbone.py中调整输出通道的值

对于数据集

https://gas.graviti.cn/dataset/data-decorators/UrbanObjectDetection

数据集格式：

![image](https://user-images.githubusercontent.com/88768188/159166560-3c752d6e-d861-4c41-bd80-7b1bf28ce4f7.png)



todo

测试不同的backbone的map值（result文件夹内有目前测试的4种backbone的结果）

将wbf添加进测试阶段的代码，对两个训练好的模型做fusion
