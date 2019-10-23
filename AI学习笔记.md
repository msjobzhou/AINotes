## 机器学习中的数学知识

导数和微分

**方向导数和梯度**

关于方向导数的证明，有两种形式：

1)利用*泰勒展开*

http://netedu.xauat.edu.cn/jpkc/netedu/jpkc/gdsx/homepage/5jxsd/51/513/5308/530807.htm

![1571756841075](pic/1571756841075.png)

更多维的方向导数可以按照上面三维情形的泰勒展开依次推导得到

2）另外一种证明方式参考如下网址中的图片

https://www.jianshu.com/p/76197f128366

![](pic/pic_fangxiangdaoshu1.png)

![](pic/pic_fangxiangdaoshu2.png)

梯度下降

导数的链式法则

**泰勒展开**

https://zhuanlan.zhihu.com/p/27348707

上面这个链接对于泰勒展开做了一个粗略的证明，讲解了其和牛顿差值的关系，很有启发意义，但这里有一个二阶多项式的系数的求解不是很理解，作为遗留问题吧

![1571839766566](pic/1571839766566.png)

另外一篇帖子讲到了如何求解这个多项式系数

https://www.zhihu.com/question/25627482/answer/313088784?utm_medium=social&utm_source=weibo

![1571840269325](pic/1571840269325.png)

同时这篇帖子也讲解了，泰勒展开的误差问题，比较经典，可以细读一下

![1571841653223](pic/1571841653223.png)

**梯度下降和泰勒展开的关系**

参考：https://zhuanlan.zhihu.com/p/82757193

BP神经网络