# -
一个基于卷积特征的增量式图像识别程序

挺久之前写的程序了，代码写得比较菜，只是能跑起来而已。。。

requirements：python2.7，keras2.+， tensorflow1.2+， opencv 

利用inception v4 提取图像特征，构建了一个简易增量式图片识别程序

inception v4参考自 https://github.com/kentsommer/keras-inceptionV4

将inception v4 最后一个AveragePooling2D的输出并Flatten后作为图像特征，再用简单的相似性度量与模板更新策略进行增量式学习。

程序可以从零开始学习，随着学习的图片数量的增加，程序识别能力越强。

简单的演示视频： https://pan.baidu.com/s/1skS3f1z
