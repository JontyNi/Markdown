# Markdown 语法教程



### 标题语法



 ```

 # 一级标题

 ## 二级标题

 ### 三级标题

 ...

 ###### 六级标题

 

 可选用 "=" 或 "-" 来代替

 ```



**效果如下**



> # 一级标题

> ## 二级标题

> ### 三级标题

> ...

> ###### 六级标题











### 换行语法



``` 

一般使用html语言中的 <br>

例如<br>效果

```



**效果如下**



> 例如<br>效果







### 强调语法



```

**粗体**

*斜体*

***粗体加斜体***

```



**效果如下**



>**粗体**

>*斜体*

>***粗体加斜体***







### 引用语法



```

> 引用的文字

```



**效果如下**



> 引用的文字











### 有序列表、无序列表



```

**有序列表**

1. 第一名

2. 第二名



**无序列表**

- 苹果

- 香蕉

```



**效果如下**



> **有序列表**

>

> 1. 第一名

>

> 2. 第二名

>

> **无序列表**

>

> - 苹果

> - 香蕉











### 代码语法



```

1. 入引用代码种没有反引号

这段里面这句是`code`

2. 引入代码里含有单反引号的用双反引号

``this is `code` ``

```



**效果如下**



>1. 入引用代码种没有反引号

>这段里面这句是`code`

>2. 引入代码里含有单反引号的用双反引号

>``this is `code` ``







### 分隔线语法



```

要创建分隔线，请在单独一行上使用三个或多个星号 (***)、破折号 (---) 或下划线 (___) ，并且不能包含其他内容。

***

---

___



为了兼容性，请在分隔线的前后均添加空白行。

```



**效果如下**



> 要创建分隔线，请在单独一行上使用三个或多个星号 (***)、破折号 (---) 或下划线 (___) ，并且不能包含其他内容。

> ***

> ---

> ___

>

> 为了兼容性，请在分隔线的前后均添加空白行。











### 链接语法



```

1. 创建带有title的链接

语法： [超链接显示名](超链接地址 "超链接title")

[这是一个链接](https://www.google.com "这是title")



2. 网址和email变成可点击链接

<www.google.com>

<hello@gmail.com>



3. 带有格式化的链接

this is a **[page](www.google.com)**.

next page is *[bing](www.bing.com)*

跳转置[`code`](#code)



4. 最后补充，若遇到带有空格的连接，为了兼容性，用%20代替空格

[google搜索引擎](www.google.com/kw=hello%20world "搜索helloworld")

```



**效果如下**



> 1. 创建带有title的链接

> 语法： [超链接显示名](超链接地址 "超链接title")

> [这是一个链接](https://www.google.com "这是title")

>

> 2. 网址和email变成可点击链接

> <www.google.com>

> <hello@gmail.com>

>

> 3. 带有格式化的链接

> this is a **[page](www.google.com)**.

> next page is *[bing](www.bing.com)*

> 跳转置[`code`](#code)

>

> 4. 最后补充，若遇到带有空格的连接，为了兼容性，用%20代替空格

> [google搜索引擎](www.google.com/kw=hello%20world "搜索helloworld")











### 图片语法



```

1. 插入图片Markdown语法代码：![图片alt](图片链接 "图片title")

![打不开所显示文字](https://static.zhihu.com/heifetz/assets/liukanshan-peek.a71ecf3e.png "知乎小可爱")



2. 带链接的图片

[![打不开文字](https://static.zhihu.com/heifetz/assets/liukanshan-peek.a71ecf3e.png "打开google搜索此图片")](https://lens.google.com/search?ep=gisbubu&hl=zh-CN&re=df&p=AbrfA8rBOCwes9al1pF8702pJli06e5hIWq8hX1AymQbdsxdWOQeXtyqFv8-pVp7wVdhfagQt6IEJWwQpjfyL8llxfp53LJC1NDYUobPWYzfHVSpBQM2URP7KKsd63v1-i9yBdrCfQro-yn_U_A0t8oIb3m0ZlqxZvLCdeIco11a212P7HVzR9l3MKeKGOH0YF_HDZOU2ML9Mm0sKA%3D%3D#lns=W251bGwsbnVsbCxudWxsLG51bGwsbnVsbCxudWxsLG51bGwsIkVrY0tKR1psTlRobE9XVmhMV1EzTjJJdE5EQTFZaTA1TkRrNUxURTFOVE5sTmpVd05UbGpZUklmZHpod1ZXbHlNMVZhVW5kUlZVTm1hVWxtYTFwaVJFTTVZa05STlRONFp3PT0iXQ==)

```



**效果如下**



> 1. 插入图片Markdown语法代码：![图片alt](图片链接 "图片title")

> ![打不开所显示文字](https://static.zhihu.com/heifetz/assets/liukanshan-peek.a71ecf3e.png "知乎小可爱")

>

> 2. 带链接的图片

> [![打不开文字](https://static.zhihu.com/heifetz/assets/liukanshan-peek.a71ecf3e.png "打开google搜索此图片")](https://lens.google.com/search?ep=gisbubu&hl=zh-CN&re=df&p=AbrfA8rBOCwes9al1pF8702pJli06e5hIWq8hX1AymQbdsxdWOQeXtyqFv8-pVp7wVdhfagQt6IEJWwQpjfyL8llxfp53LJC1NDYUobPWYzfHVSpBQM2URP7KKsd63v1-i9yBdrCfQro-yn_U_A0t8oIb3m0ZlqxZvLCdeIco11a212P7HVzR9l3MKeKGOH0YF_HDZOU2ML9Mm0sKA%3D%3D#lns=W251bGwsbnVsbCxudWxsLG51bGwsbnVsbCxudWxsLG51bGwsIkVrY0tKR1psTlRobE9XVmhMV1EzTjJJdE5EQTFZaTA1TkRrNUxURTFOVE5sTmpVd05UbGpZUklmZHpod1ZXbHlNMVZhVW5kUlZVTm1hVWxtYTFwaVJFTTVZa05STlRONFp3PT0iXQ==)




### 表格


```
1. 要添加表，请使用三个或多个连字符（---）创建每列的标题，并使用管道（|）分隔每列。您可以选择在表的任一端添加管道。

name | id | year 
--- | ---| ---- 
`zhang` | 1 | 23  
li | 2 | 22 

2. 对齐
 > 题行中的连字符的左侧，右侧或两侧添加冒号（:），将列中的文本对齐到左侧，右侧或中心

name | id | year 
:--- | :---: | ---: 
zhang | 1 | 23  
**li** | 2 | 22 


```



**效果如下**



> 1. 要添加表，请使用三个或多个连字符（---）创建每列的标题，并使用管道（|）分隔每列。您可以选择在表的任一端添加管道。

>  name | id  | year 
>  ----- | ---- | ---- 
>  `zhang` | 1  | 23  
>  li  | 2  | 22  

>

> 2. 对齐

>  > 题行中的连字符的左侧，右侧或两侧添加冒号（:），将列中的文本对齐到左侧，右侧或中心

>  name | id | year 
>  :---- | :--: | ---:
>   zhang | 1  |  23 
>   **li**  | 2  |  22 











### 围栏代码块



````

语法：在代码块之前和之后的行上使用三个反引号（(```）或三个波浪号（~~~））

> 可加上不同语言的，来适应语法高亮,默认不加（文本）

```python

 pint('hello world')

```

````



**效果如下**



> 语法：在代码块之前和之后的行上使用三个反引号（(```）或三个波浪号（~~~））

> > 可加上不同语言的，来适应语法高亮,默认不加（文本）

> ```python

>  pint('hello world')

> ```















### 脚注



```

语法：文中用 [^备注]

 释义用 [^备注]： 释义内容

[^1]: 疑似

[^hi]: 抬头

---

**静夜思**
作者：李白

床前明月光，疑[^1]是地上霜。
举头[^hi]望明月，低头思故乡。

```



**效果如下**

> [^1]: 疑似
> [^hi]: 抬头
> ---
> **静夜思**
> 作者：李白

> 床前明月光，疑[^1]是地上霜。
> 举头[^hi]望明月，低头思故乡。



### 删除线



```

语法：~~文字~~



```



**效果如下**



> 语法：~~文字~~









### 任务列表语法



```

语法： 

- [x] 选中

- [ ] 未选中

注意事项： 

- 在句首

- -空格[空格] -空格[x]

```



**效果如下**



> 语法： 

>

> - [x] 选中

> - [ ] 未选中

> 注意事项： 

> - 在句首

> - -空格[空格] -空格[x]








### 使用emoji表情



```
语法： :对照表单词:
鸡飞蛋打
:chicken: :airplane: :egg: :punch:
[git符号对照表](https://gist.github.com/rxaviers/7360908 "点击直达")
```



**效果如下**

> 语法： :对照表单词:
> 鸡飞蛋打
> :chicken: :airplane: :egg: :punch:

> <br>

> [git符号对照表](https://gist.github.com/rxaviers/7360908 "点击直达")