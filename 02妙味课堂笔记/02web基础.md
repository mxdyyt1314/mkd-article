#### html是什么

超文本标记语言，是和和浏览器打交道的语言，定义网页的文档结构

语法格式`<开始标签></结束标签>`、标签

#### css  层叠样式表

描述网页样式的语言

1. 行间样式表
2. 内部样式表
3. 外部样式表

#### javascript能做什么

描述网页动态行为、功能交互的语言

---

#### css：`background`背景

1. `background-image` 背景图片
2. `background-repeat` 背景平铺方式 `no-repeat`,`x-repeat`,`y-repeat`
3. `background-position` 背景图片位置 x轴、y轴
4. `background-attachment` 背景图片定位方式 `fixed`,`absolute`

`background`复合样式：

```css
/*颜色、图片、重复方式、定位方式、定位位置*/
.bg{
    background: red url("img/img.png") no-repeat fixed 14px 20px;
}
 ```

#### css：`border`边框

1. bottom-top：上边框
2. bottom-bottom：下边框
3. bottom-left：左边框
4. bottom-right：右边框

```css
.border{
  border:1px solid #0083ff;
}
```

#### css常见单位

1. `px` 像素
2. `em` 相对于父元素的大小单位
3. `rem` 相对于根元素的大小单位
4. `%` 相对于父元素占百分比大小

#### 常见的几种颜色表示方式

1. 英文名称：`blue、red`
2. 十六进制代码：``#0094ff`
3. RGB代码：`rgb(122,23,98);`

tansition： 过渡
