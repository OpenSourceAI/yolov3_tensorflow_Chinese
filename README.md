# 简介
本项目是对[yolov3的tensorflow实现](https://github.com/YunYang1994/tensorflow-yolov3)项目的"整合"吧,做了一些细微的修改,添加大量的中文注释,帮助进行快速阅读理解. 基础好的可以直接阅读原代码.

[yolov3的tensorflow实现](https://github.com/YunYang1994/tensorflow-yolov3)这个项目,应该是作为菜鸟的我到目前为止在原理和代码实现上最复杂的深度学习项目了. 项目代码量大,shape变换,维度广播,看着看着一不小心就迷失了,反反复复的看了好几遍,感觉才把整个项目代码的逻辑给拉通,整个过程反复调试,计算维度变换,运算的处理过程,总之收获巨大.

欢迎交流,指出错误等.

# 开箱即用

下载[data](#)

```
$ python video_dome.py # 默认使用0摄像头, 也可以通过局域网调用手机摄像头
```
![截图](screenshot/frames_2019-03-29-21_45_02.jpg)

# 学习

通过快速训练[train_demo/quick_train.py](train_demo/quick_train.py)开始,阅读项目代码开始学习yolov3的细节. 在这之前

- 下载[data](#),使用浣熊数据集
- [train_demo/pic_visu.py](train_demo/pic_visu.py) 可视化数据
- 使用[core/convert_tfrecord.py](core/convert_tfrecord.py),转换为tfrecord文件
- [train_demo/show_image_from_tfrecord.py](train_demo/show_image_from_tfrecord.py),检查文件是否正常
- [train_demo/quick_train.py](train_demo/quick_train.py)开始训练调试
- [train_demo/show_trained_result.py](train_demo/show_trained_result.py) 检测所训练的模型效果.

# 使用其他数据集进行训练

待更新....

>https://github.com/YunYang1994/tensorflow-yolov3