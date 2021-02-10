### 1.掌握盒子水平垂直居中的五大方案

1. 定位：三种
2. display: flex
3. JavaScript
4. display: table-cell

> github图床Token：ac7e3c0d4634cd7915b47d1917105d84c53aef70

### 2.标准盒子模型：

1.标准盒子模型：box-sizing: content-box

![标准盒子模型](https://raw.githubusercontent.com/chnjames/cloudImg/main/20210210201831.png)

2.IE盒模型(怪异盒模型)：

![IE盒模型](https://raw.githubusercontent.com/chnjames/cloudImg/main/20210210203429.png)

2.Flex盒模型

### 3.掌握几大经典布局方案：

1. 圣杯布局(左右固定，中间自适应)
2. 双飞翼布局(左右固定，中间自适应)

### 4.移动端响应式布局开发的三大方案：

1. media

2. rem

3. flex

4. vh / vw （百分比布局）

   

> 作业：
>
> 1.让一个div在视野中消失
>
> 2.z-index的工作原理（文档流和定位）
>
> 3.对HTML5的理解
>
> 4.div里面的文字垂直居中，且该文字的大小根据屏幕大小自适应
>
> 5.不考虑其他因素，下面哪种的渲染性能比较好
>
> ```css
> .box a {
> 	...
> }
> a {
> 	...
> }
> 
> css的渲染是从右向左，就是先查找渲染a，再去查找box
> ```
>
> 