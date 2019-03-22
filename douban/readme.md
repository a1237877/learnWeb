-css 命名词汇
 feeds *-item   content  container 类名
-html 结构及布局
从上到下 从左到右 语义化和功能性
 1.结构套路
 content>h3+p
 2.舍得做盒子 ，搭结构
 3.a  作为盒子 ，在移动端是很正常的
 display:block;  转为块级元素
 3.盒子模型
 文字line-height padding margin
 5文字截断
 天猫  商铺信息是由商家填的，他的高度不受限制。
 display :-webkit-box; 新的盒子模型，像flex来划分父元素的空间，
 overflow:hidden;
 -webkit-line-clamp ：行数
 -webkit-box-orient:vertical
 6.浮动
 离开文档流
 在一个盒子里，将要浮动的元素写在最前面，
 左右布局
 在flex布局之前，我们一般借助于float 来布局
 图片的宽高？宽度用百分比，自适应的需求，
 高度怎么做？div padding-top: 自身的宽度来做比例。100%则为正方形
 自适应设备里盒子的等比例设置。50%则为高度为宽度的50%；

 7.弹性布局 flex 页面布局之王
 首先在父容器里声明弹性布局display：flex
 再在子容器写弹性布局的比例  flex:3; flex:1  表示比例为按父容器的3：1