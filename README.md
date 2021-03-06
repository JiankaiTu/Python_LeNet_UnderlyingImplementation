# Python_LeNet_UnderlyingImplementation
使用Python从底层实现简单的卷积神经网络CNN——LeNet，完成MNIST手写数字识别任务。
#  使用方法：

## 全连接神经网络实现
另外，我还写了一个全连接神经网络完成MNIST手写数字识别，放在"全连接神经网络"文件夹中，和LeNet实现的文件夹一样，里面也提供了三个文件，运行说明,ipynb格式的代码，py格式的代码。
在知乎上，我写了两篇文章讲了对全连接神经网络实现的数学理论以及实现方法，里面有具体代码的分析，欢迎阅览：  
https://zhuanlan.zhihu.com/p/61863634 全连接神经网络中反向传播算法数学推导  
https://zhuanlan.zhihu.com/p/61875022 用Python从底层实现一个多层感知机

## LeNet实现
实现LeNet的代码放在了"卷积神经网络LeNet实现"文件夹中，里面提供了了.ipynb格式和.py格式两种形式的代码，里面提供了比较详细（自以为的）的注释，运行方法写成了一个.md格式的说明也放在文件夹中。
在知乎上，我写了文章对卷积神经网络涉及的理论进行推导，欢迎阅览：  
https://zhuanlan.zhihu.com/p/61898234 卷积神经网络(CNN)反向传播算法推导  
https://zhuanlan.zhihu.com/p/62303214 卷积神经网络(CNN)Python的底层实现——以LeNet为例

## LeNet高效实现
LeNet代码上传之后一个月里又研究了下效率如何进一步提升，把LeNet的代码放在了LeNet高效实现中，相比较之前的实现，训练效率提高了10倍。主要使用了numpy自带的几个函数改进卷积以及池化的实现，这几个函数有些复杂，不是很直观，如果只是想研究计算原理，看第一版即可。
在这一版本中还添加了loss曲线以及accuracy曲线的绘制。
这个文件的使用和之前一样，提供.ipynb格式和.py格式两种形式的代码，各自都只有一个文件，在MNIST官网下载好数据后，将程序中读取的路径更改一下，即可直接运行。
