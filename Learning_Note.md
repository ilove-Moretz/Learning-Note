### 20191121  
主题：attention机制讲解</br>
内容：</br>
1、博客地址：https://blog.csdn.net/weixin_38547809/article/details/82382986</br>
2、理解内容：
![](https://ss.csdn.net/p?http://mmbiz.qpic.cn/mmbiz_png/ptp8P184xjxeRHqppry03SX1TTiblocHfIofqwrQntksrDjdCaafxv0E1ibK9CMHGzl9GlAMGJdXBiaeqTCANgCyg/0?wx_fmt=png)
>可以将Attention机制看作一种软寻址（Soft Addressing）:Source可以看作存储器内存储的内容，元素由地址Key和值Value组成，当前有个Key=Query的查询，目的是取出存储器中对应的Value值，即Attention数值。通过Query和存储器内元素Key的地址进行相似性比较来寻址，之所以说是软寻址，指的不像一般寻址只从存储内容里面找出一条内容，而是可能从每个Key地址都会取出内容，取出内容的重要性根据Query和Key的相似性来决定，之后对Value进行加权求和，这样就可以取出最终的Value值，也即Attention值。所以不少研究人员将Attention机制看作软寻址的一种特例，这也是非常有道理的。</br>

### 20191121
主题： github本地仓库连接远程仓库</br>
内容：https://www.cnblogs.com/irenehanb/p/10962854.html

### 20200221

主题：欧式空间和非欧式空间

内容：

>
>
>一句话总结：**欧几里得空间**就是在对**现实空间的规则抽象和推广（从n<=3推广到有限n维空间）
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