#  代码说明：
本实验使用python语言，在社区版pytorch2021.2中编写。

主要依赖tensorflow包进行搭建，tensorflow的版本是2.7.0,使用了tensorflow中dataset库中的数据集。

使用RNN作为情感倾向分类训练网络模型，利用tf.keras.Sequential()函数进行模型构建。

#  使用说明
不需要额外的数据包，直接将压缩包中的.py文件在有tensorflow的python编译器中打开并运行即可。

如果没有tensorflow包，可以通过在python环境下的terminal中使用pip install tensorflow来下载最新版本的tensorflow

运行结束后，可以看到训练后的网络准确度示意图，以及对于示例文本的情感倾向预测。

在运行结束后，同文件夹下可以得到checkpoint模型文件，是已经训练好的模型。

运行时间可能较长，请耐心等待。

# 依赖的库
tensorflow: 提供机器学习框架

tensorflow_datasets: 提供训练数据

numpy: 提供数学运算

matplotlib.pyplot: 提供图像展示

