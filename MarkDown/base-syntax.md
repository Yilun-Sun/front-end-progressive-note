# 基础语法

## Header

```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
```

有的 MarkDown 解析器不支持太小的标题，比如 GitBook 就不支持 h4、h5、h6 大小的标题，使用前要阅读官方文档了解下。

## Emphasis 

```
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
*You **can** combine them*
```

_This text will be italic_ 

_This will also be italic_ 

**This text will be bold** **This will also be bold**

_You **can** combine them_

## Lists

### 无序的

```
* Item 1
* Item 2
 * Item 2a
 * Item 2b
```

* Item 1
* Item 2
* Item 2a
* Item 2b

### 有序的

```
1. Item 1
2. Item 2
3. Item 3
 1. Item 3a
 2. Item 3b
```

1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b

### TODO

```
- [ ] Item 1
- [ ] Item 2
- [x] Item 3
- [ ] Item 4
```

* [ ] Item 1
* [ ] Item 2
* [x] Item 3
* [ ] Item 4

## Blockquotes 引用

```
鲁迅说：

> 这真不是我说的
```

鲁迅说：

> 这真不是我说的

## Links

```
[GitHub](http://github.com)
```

[GitHub](http://github.com)

## Images

```
[哎呀！熟悉的感觉！](https://image.baidu.com/search/detail?ct=503316480&z=undefined&tn=baiduimagedetail&ipn=d&word=github%20404&step_word=&ie=utf-8&in=&cl=2&lm=-1&st=undefined&hd=undefined&latest=undefined&copyright=undefined&cs=1177764154,2029729275&os=1395125231,1437887474&simid=1177764154,2029729275&pn=0&rn=1&di=62920&ln=498&fr=&fmq=1634106376569_R&fm=&ic=undefined&s=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&is=0,0&istype=0&ist=&jit=&bdtype=0&spn=0&pi=0&gsm=0&objurl=https%3A%2F%2Fgimg2.baidu.com%2Fimage_search%2Fsrc%3Dhttp%253A%252F%252Fpic1.zhimg.com%252F03b3167334b95a6e58b4f492b82e396f_r.jpg%26refer%3Dhttp%253A%252F%252Fpic1.zhimg.com%26app%3D2002%26size%3Df9999%2C10000%26q%3Da80%26n%3D0%26g%3D0n%26fmt%3Djpeg%3Fsec%3D1636698376%26t%3D867ad9853b0eb937eddcf16638f71038&rpstart=0&rpnum=0&adpicid=0&nojc=undefined)
```

![哎呀！熟悉的感觉！](https://pic1.zhimg.com/80/03b3167334b95a6e58b4f492b82e396f\_1440w.jpg?source=1940ef5c)
