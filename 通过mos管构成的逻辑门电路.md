# 通过mos管构成的逻辑门电路

## 一、总结

`mos管` 是构成 `逻辑门电路` 的最基本单元。

各个逻辑门电路的真值表如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/b7af1829045a47cfbe84b52fa30503f5.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5L2g5p2_5a2Q5YaS54Of5LqG,size_16,color_FFFFFF,t_70,g_se,x_16)

## 二、各种门

### 1、非门

NOT
![在这里插入图片描述](https://img-blog.csdnimg.cn/fd5066d8e2f94c698dc41119dd810a6e.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5L2g5p2_5a2Q5YaS54Of5LqG,size_16,color_FFFFFF,t_70,g_se,x_16)

### 2、与门

AND
![在这里插入图片描述](https://img-blog.csdnimg.cn/66a4909f773f4beda0bf69f52d2f2046.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5L2g5p2_5a2Q5YaS54Of5LqG,size_16,color_FFFFFF,t_70,g_se,x_16)

### 3、[与非门](https://so.csdn.net/so/search?q=与非门&spm=1001.2101.3001.7020)

把上面`与门电路` 右边的 `非门电路` 去掉
NAND
![在这里插入图片描述](https://img-blog.csdnimg.cn/a99d5007214142d19393b3ac69b4990b.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5L2g5p2_5a2Q5YaS54Of5LqG,size_16,color_FFFFFF,t_70,g_se,x_16)

### 4、或门

OR
![在这里插入图片描述](https://img-blog.csdnimg.cn/468e67a8249b480992c0a8b8bf5cc977.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5L2g5p2_5a2Q5YaS54Of5LqG,size_16,color_FFFFFF,t_70,g_se,x_16)

### 5、或非门

NOR
把或门右边的非门电路去掉
![在这里插入图片描述](https://img-blog.csdnimg.cn/65f4773660ab4ccfbf15c25b9d8c3994.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5L2g5p2_5a2Q5YaS54Of5LqG,size_16,color_FFFFFF,t_70,g_se,x_16)

### 6、[异或门](https://so.csdn.net/so/search?q=异或门&spm=1001.2101.3001.7020)

XOR
两个输入相异为1，相同为0。
![在这里插入图片描述](https://img-blog.csdnimg.cn/a62d72e0957645008b386f37d2f89b81.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5L2g5p2_5a2Q5YaS54Of5LqG,size_16,color_FFFFFF,t_70,g_se,x_16)

### 7、同或门

XNOR
两个输入相同为1，相异为0。
![在这里插入图片描述](https://img-blog.csdnimg.cn/341ca1eb9b14411f82e3d8749b9b1a93.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5L2g5p2_5a2Q5YaS54Of5LqG,size_16,color_FFFFFF,t_70,g_se,x_16)