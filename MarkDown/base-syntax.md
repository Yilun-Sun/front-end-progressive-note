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

