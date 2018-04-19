md文档攻略
===
该文件用来测试和展示书写README的各种markdown语法。GitHub的markdown语法在标准的markdown语法基础上做了扩充，称之为`GitHub Flavored Markdown`。简称`GFM`，GFM在GitHub上有广泛应用，除了README文件外，issues和wiki均支持markdown语法。
## 标题
* 一级标题 `# 一级标题  ===`
* 二级标题 `## 二级标题 ---`
* 三级标题 `### 三级标题`
* 四级标题 `#### 四级标题`
* 五级标题 `##### 五级标题`
* 六级标题 `###### 六级标题`
## 引用的方式
>引用内容   `>引用内容`
>>引用内容  `>>引用内容`
>>>引用内容  `>>>引用内容`
## 分割符
连续输入`---,***`如下所示，但是如果是---并且它的前一行是文字，则文字变成了一级标题
***
---
## 列表
* 这是一个无序列表 `* 这是一个无序列表`
* 这是一个无序列表 `* 这是一个无序列表`

- 这是一个无序列表 `- 这是一个无序列表`
- 这是一个无序列表 `- 这是一个无序列表`

+ 这是一个无序列表 `+ 这是一个无序列表`
+ 这是一个无序列表 `+ 这是一个无序列表`

* 这是一个无序列表 `* 这是一个无序列表`
+ 这是一个无序列表 `+ 这是一个无序列表`

1. 这是一个有序列表 `1. 这是一个有序列表`
2. 这是一个有序列表 `2. 这是一个有序列表`
3. 这是一个有序列表 `3. 这是一个有序列表`
## 链接
[md文档攻略](https://github.com/Harrdy2018/Learning-README/blob/master/README.md)
***
也可以直接用尖括号包含网址的方式`<https://github.com/Harrdy2018/Learning-README/blob/master/README.md>`来构成链接
***
<https://github.com/Harrdy2018/Learning-README/blob/master/README.md>
## 图片
像构造链接一样，格式为`![图片信息](图片地址)`<br>
![金所炫](https://github.com/Harrdy2018/Learning-README/blob/master/jsx.jpg)<br>
也可以用html方式来指定图片大小`<img src="" width="240px" height="240px" alt="jsx">`<br>
<img src="https://github.com/Harrdy2018/Learning-README/blob/master/jsx.jpg" width="208px" height="242px" alt="金所炫">
## 代码
```python
print("Hello")
>>>Hello
```
## 字体样式
* *倾斜*  `*倾斜*`
* **加粗** `**加粗**`
* ***倾斜加粗***   `***倾斜加粗***`
## 表格
* 使用`-|`符号把内容分割为你认为合适的表格样式就好
* 使用`:`符号标识对齐
***
|表头1|表头2|表头3|
|:---|:---:|---:|
|左对齐|居中对齐|右对齐|
## 保存
最后将markdown编写的文档保存为.md格式即可！！
