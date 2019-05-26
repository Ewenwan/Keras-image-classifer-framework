# Keras-image-classifer-framework
a general image classifer framework written by Keras

使用了Keras搭建了一个基于LeNet的图片分类器的通用框架，并用它成功完成两个实际的分类任务。最后再说说我们现有的模型的一些改进的地方吧。第一，图片归一化的尺寸是否合适？比如票据分类任务中，图片归一化为64，可能这个尺寸有点小，如果把尺寸改为128或256，效果可能会更好；第二，可以考虑更深的网络，比如VGG,GoogLeNet等；第三，数据增强部分还可以再做一做。


This is a general image classifer framework base on LeNet written by Keras. We can use it to deal with some classification tasks. 
In addition, we can use some deeper network base on this calssifier framework to handle more complex tasks. 

This repo includes two examples on image classification using deep learing method. 
One is traffic-sign task, the other is invoice task. We use the same framework to handle these task successfully.

Here is the plot(acc and loss) for the these two classification tasks.

![](traffic-sign-code/plot.png) 


![](invoice-code/plot.png) 



Please visit my blog for more details.

http://www.cnblogs.com/skyfsm/p/8051705.html
