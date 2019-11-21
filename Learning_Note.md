### 20191121  
主题：attention机制讲解</br>
内容：</br>
1、博客地址：https://blog.csdn.net/weixin_38547809/article/details/82382986</br>
2、理解内容：
![](https://ss.csdn.net/p?http://mmbiz.qpic.cn/mmbiz_png/ptp8P184xjxeRHqppry03SX1TTiblocHfIofqwrQntksrDjdCaafxv0E1ibK9CMHGzl9GlAMGJdXBiaeqTCANgCyg/0?wx_fmt=png)
>可以将Attention机制看作一种软寻址（Soft Addressing）:Source可以看作存储器内存储的内容，元素由地址Key和值Value组成，当前有个Key=Query的查询，目的是取出存储器中对应的Value值，即Attention数值。通过Query和存储器内元素Key的地址进行相似性比较来寻址，之所以说是软寻址，指的不像一般寻址只从存储内容里面找出一条内容，而是可能从每个Key地址都会取出内容，取出内容的重要性根据Query和Key的相似性来决定，之后对Value进行加权求和，这样就可以取出最终的Value值，也即Attention值。所以不少研究人员将Attention机制看作软寻址的一种特例，这也是非常有道理的。
