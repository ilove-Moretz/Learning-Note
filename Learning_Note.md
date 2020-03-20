[TOC]

------



### 20191121  attention机制讲解

主题：attention机制讲解</br>
内容：</br>
1、博客地址：https://blog.csdn.net/weixin_38547809/article/details/82382986</br>
2、理解内容：
![](https://ss.csdn.net/p?http://mmbiz.qpic.cn/mmbiz_png/ptp8P184xjxeRHqppry03SX1TTiblocHfIofqwrQntksrDjdCaafxv0E1ibK9CMHGzl9GlAMGJdXBiaeqTCANgCyg/0?wx_fmt=png)

>可以将Attention机制看作一种软寻址（Soft Addressing）:Source可以看作存储器内存储的内容，元素由地址Key和值Value组成，当前有个Key=Query的查询，目的是取出存储器中对应的Value值，即Attention数值。通过Query和存储器内元素Key的地址进行相似性比较来寻址，之所以说是软寻址，指的不像一般寻址只从存储内容里面找出一条内容，而是可能从每个Key地址都会取出内容，取出内容的重要性根据Query和Key的相似性来决定，之后对Value进行加权求和，这样就可以取出最终的Value值，也即Attention值。所以不少研究人员将Attention机制看作软寻址的一种特例，这也是非常有道理的。</br>

### 20191121  github本地仓库连接远程仓库
主题： github本地仓库连接远程仓库</br>
内容：https://www.cnblogs.com/irenehanb/p/10962854.html

### 20200221 欧式空间和非欧式空间

主题：欧式空间和非欧式空间

内容：

**欧式空间**

>一句话总结：**欧几里得空间**就是在对现实空间的规则抽象和推广（从n<=3推广到有限n维空间）
>
>欧几里得几何就是中学学的平面几何、立体几何，**在欧几里得几何中，平行线任何位置的间距相等**。
>
>而中学学的几何空间一般是2维，3维（所以，我们讨论余弦值、点间的距离、内积都是在低纬空间总结的），如果将这些低维空间所总结的规律推广到有限的n维空间，那这些符合定义的空间则被统称为**欧几里得空间（欧式空间，Euclidean Space）**。
>
>而欧几里得空间主要是定义了**内积、距离、角**（没错，就是初中的那些定义），理解了这些再去理解数学定义就很明确了。
>
>
>
>作者：匿名用户
>链接：https://www.zhihu.com/question/27903807/answer/699570097
>来源：知乎
>著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

**关于非欧式空间**

>非欧几何，爱因斯坦曾经形象地说明过：假定存在一种二维扁平智能生物，但它们不是生活在绝对的平面上，而是生活在一个球面上，那么，当它们在小范围研究圆周率的时候，会跟我们一样发现圆周率是3.14159……可是，如果它们画一个很大的圆，去测量圆的周长和半径，就会发现周长小于2πr，圆越大，周长比2πr小得越多，为了能够适用于大范围的研究，它们就必须修正它们的几何方法。如果空间有四维，而我们生活在三维空间中，而这个三维空间在空间的第四个维度中发生了弯曲，我们的几何就会象那个球面上的扁平智能生物一样，感受不到第四维的存在，但我们的几何必须进行修正，这就是非欧几何。在非欧几何中，平行的直线只在局部平行，就象地球的经线只在赤道上平行。
>闵可夫斯基空间属于欧几里得几何的扩展，它是把时间也作为一个维度进行量化，再添加光速系数，跟洛伦兹变换一样，使得不同惯性系中的运动问题计算得以简化。

### 20200221 图神经网络

主题：图神经网络

内容：https://www.cnblogs.com/SivilTaram/p/graph_neural_network_1.html

> 1、

### 20200307 卷积

1. 一句话概括卷积：一个函数在另一个函数上的加权求叠加
2. 卷积的解释：如何通俗易懂地解释卷积？ - 马同学的回答 - 知乎 https://www.zhihu.com/question/22298352/answer/228543288
3. 卷积神经网络的卷积是一种空间域的卷积。信号处理中，因为空（时）域上卷积运算很麻烦，因此通过傅里叶变化转化的频域上计算，然后再转回到空（时）域。

### 20200310 表示学习

主题：表示学习

内容：https://blog.csdn.net/weixin_40449300/article/details/89941348

表示学习的综述，写的挺好，mark一下，有时间看看学习一下

### 20200310 network embeddin

主题：network embeddin

内容：

> 1、**定义**：
>
> 网络嵌入就是将网络节点表示为低纬度的向量
>
> 2、**DeepWalk**
>
> https://zhuanlan.zhihu.com/p/45167021

### 20200317 sigmoid 和softmax 

主题：sigmoid 和softmax

内容：

> - sigmoid函数的作用是将数字映射到[0,1]范围内，当分类问题是多标签问题时，神经网络最后一层使用sigmoid函数，最后一层每一个神经元都是独立的分布，都用sigmoid计算出一个概率值。所有神经元的概率值加起来的和不为一
> - softmax函数的输出概率总和为1，可以理解为一个归一化的操作。当分类问题的类别是互斥的时候可以使用softmax函数作为最后一层输出，比如手写体数字识别，是一个多分类的问题，每个最后的输出肯定是确定，因此神经网络最后一层所有神经元共同满足一个分部，所有神经元概率和为1。

### 20200317 NLL求导过程

主题：NLL求导过程

内容：

> https://bigquant.com/community/t/topic/119348

### 20200317 对抗训练（adversarial training）

主题：对抗训练

内容：

>- 从泛化性角度看对抗训练：算法应该对标记数据点的$\epsilon$邻域内的新数据点保持结果的一致性

### 20200319 permutation invariant

主题：permutation invariant

内容：https://stats.stackexchange.com/questions/120089/what-does-permutation-invariant-mean-in-the-context-of-neural-networks-doing-i

https://www.quora.com/What-does-it-mean-that-a-neural-network-is-invariant-to-permutation-When-does-this-happen

需要翻墙访问

### 20200320 交叉熵和NLL

1、主题：交叉熵和NLL

2、内容： https://blog.csdn.net/qq_22210253/article/details/85229988 这个博客里讲了Pytorch下交叉熵函数和NLL函数的区别。交叉熵函数=log-softmax+NLL函数

> 关于交叉熵的一些理解：
>
> - 交叉熵的数学定义是$-p_{i}logq_{i}$其中$p_{i}$是目标分布，$q_{i}$是要待优化的分布，交叉熵计算了两个分布之间的距离。距离越小两个分布越近，因此我们就可以讲将交叉熵看做是损失，最小化交叉熵就可以将待优化粉笔逼近目标分布。
> - 在代码实现中，使用神经网络实现多分类的问题，最后一层通过softmax输出一组概率，比如我们实现的是3分类的问题，那么就会输出三维的一组概率，比如说[0.2,0.7,0.3]。此时标签是第三类，用one-hot编码来表示是[0,0,1]。对应与上面的交叉熵的数学公式，此时$p_{i}$的大小应该就是1，而$q_{i}$则是0.3。那么$-1*log0.3$就是这组数据的交叉熵。那么对于每组数据来说，他的目标分布都是1。因此我们使用NLL（Negative Log Likehood）就可以得到损失。

