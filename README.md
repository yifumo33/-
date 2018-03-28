- 对于判断滚动头部用scrollTop(),自身元素高度用height(),元素相对容器的高度用offset().top
- 将存放图片的链接提前存放在img的data-src的属性中，要用时，直接设置即可
- children()是在所有后代中去寻找，find是在后代的一层中去寻找。
### 懒加载最重要原理：$(window).scrollTop() + $(window).height() > $node.offset().top
		window可以是其他容器