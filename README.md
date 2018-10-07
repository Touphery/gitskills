# MarkDown学习

---

## 1. 菜单

> '# 这是一级标题'
> '## 这是二级标题'
> '### 这是三级标题'
> '#### 这是四级标题'
> '##### 这是五级标题'
> '###### 这是六级标题'

## 2. 分割线

> '---'
> '***'
> '___'

## 3. 文字效果

> **加粗文字**
> *斜体字*
> ***加粗斜体字***
> ~~删除线~~~~
> ***加粗斜体删除线***~~

## 4. 引用

> 引用内容
> > 二级引用内容
> > > 三级引用
> > > > 四级引用
> 二级引用结束

## 5. 图片

### 5.1 在线图片

![blockchain](https://upload-images.jianshu.io/upload_images/6860761-fd2f51090a890873.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/550/format/webp "网络图片")

### 5.2 本地图片

![blockchain](source/skin.jpg "本地图片")

## 6. 超链接

[百度](http://baidu.com)
[Markdown语法](https://www.jianshu.com/p/191d1e21f7ed)

## 7. 列表

### 7.1 无序列表

> '-, *, +' 都行
- 列表内容-
* 列表内容+
+ 列表内容*

### 7.2 有序列表

1. 有序
2. 有序
3. ...

### 7.3 列表嵌套

- 无序列表1级
   - 无序列表2级
   - 无序列表
   - 无序列表
1. 列表嵌套
   * 嵌套
   * 嵌套2
      - 嵌套3
      - 嵌套4
    * 嵌套2.1
    * 嵌套2.2

### 8. 表格

> '表头|表头|表头'
> '---|:--:|---:'
> '内容|内容|内容'
> '内容|内容|内容'
> 第二行分割表头和内容。
> - 有一个就行，为了对齐，多加了几个
> 文字默认居左
> -两边加：表示文字居中
> -右边加：表示文字居右
> 注：原生的语法两边都要用 | 包起来。此处省

表头|表头2|表头3
---|:--:|:--:
内容1|内容2|内容3
行2|行2|行2

### 9. 代码段

`var a = b;`

```
<hr>
<h3 class="mume-header" id="%E4%B8%89%E7%BA%A7%E8%8F%9C%E5%8D%95">&#x4E09;&#x7EA7;&#x83DC;&#x5355;</h3>

<hr>
<h4 class="mume-header" id="%E5%9B%9B%E7%BA%A7%E8%8F%9C%E5%8D%95">&#x56DB;&#x7EA7;&#x83DC;&#x5355;</h4>

<h5 class="mume-header" id="%E4%BA%94%E7%BA%A7%E8%8F%9C%E5%8D%95">&#x4E94;&#x7EA7;&#x83DC;&#x5355;</h5>

<h6 class="mume-header" id="%E5%85%AD%E7%BA%A7%E8%8F%9C%E5%8D%95">&#x516D;&#x7EA7;&#x83DC;&#x5355;</h6>

```

### 10. 流程图

```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
