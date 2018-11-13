# 基于LSTM的MNIST手写体识别:

### **1.数据预处理：**

原始数据为`[batchsize,high,width]`的格式，现在需要将数据转换成如下形状：
    ![p24](./data/p24.png)<br>
也就是原始数据集要经过两步才能得到我们所需要的喂给RNN网络的数据格式

### **2.搭建网络**  

网络就采取最原始的 `BasicLSTMCell`进行处理.

### **3.模型表现
在验证集上的表现为0.9724<br>

在测试集上的表现为0.9706<br>

[源代码](./V_1.py)

[循环神经网络系列（四）基于LSTM的MNIST手写体识别](https://blog.csdn.net/The_lastest/article/details/83745098)