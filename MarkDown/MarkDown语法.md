# MarkDown

## 1. 标题
- \# 后接标题
- 一级标题#
- 二级标题##
- 三级标题###
- 四级标题####
- 五级标题#####
- 六级标题######

## 2. **字体**
- *斜体*
  - \* 文字 *

- **加粗**
  - ** 文字 **

- ***斜体加粗***
  - \*** 文字 ***

- ~~删除线~~
  - \~~ 文字 ~~

## 3. **列表**

- 有序列表
  - 1\.
  - 2\.
  - 3\.

- 无序列表
  - 段落前端 -号

- 列表注意缩进!


## 4. **链接**
- 内嵌式链接  

  1\. 外部链接  

     [百度](http://www.baidu.com "打开百度")  

      [百度](http://www.baidu.com "打开百度")

  2\.内部链接

     [MarkDown](MarkDown语法.md#MarkDown "回到MarkDown")  

	  [MarkDown](MarkDown语法.md#MarkDown "回到MarkDown")

- 引用式链接  

  1\. 外部链接  
     [百度]

  2\. 内部链接  
  [MarkDown]

<!---    链接     -->
[百度]: http://www.baidu.com "打开百度"
[MarkDown]: MarkDown语法.md#MarkDown "回到MarkDown"

	<!---    引用式链接     -->
	[百度]: http://www.baidu.com "打开百度"
	[MarkDown]: MarkDown语法.md#MarkDown "回到MarkDown"

## 5. **图片**
- 内嵌式
  - 外部图片  
  ![img](https://www.baidu.com/img/bd_logo1.png?where=super "百度图标")
  ```
  ![img](https://www.baidu.com/img/bd_logo1.png?where=super "百度图标")
  ```
  - 内部图片  
  `![img](文件相对路径 "图片描述")`

- 引用式
  - 外部图片  
  ![img]
  ```
  ![img]
  ```
  - 内部图片  
  ``![内部]``

```
<!--- 引用式图片 --->
  [img]: https://www.baidu.com/img/bd_logo1.png?where=super "百度图标"
  [内部]: 内部图片文件相对路径 "图片描述"
```

<!--- 引用式图片 --->
  [img]: https://www.baidu.com/img/bd_logo1.png?where=super "百度图标"










# 某些注意点
- 某些符号后面要先加空格,再加文字
- 语句与语句之间最好隔开一行,避免某些奇怪的冲突
- 每行结束打两个空格避免与下一行产生产生问题
