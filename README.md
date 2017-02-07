## index1——倒计时

#### [demo示例](http://htmlpreview.github.io/?https://github.com/ljuyi/javascript/blob/junyi.li/index1.html)

#### 原理说明
1.获取当前时间信息，定义0-9显示数组<br/>
2.拆分时间，分别记下时、分、秒的高位和低位<br/>  
3.根据拆分的时间位分别获取各个位对应的数组下标  <br/>
4.在画布上进行绘制<br/>

## index2——无缝轮播图
#### [demo示例](http://htmlpreview.github.io/?https://github.com/ljuyi/javascript/blob/junyi.li/index2.html)

#### 原理说明
1.在页面中插入一个div，设置css样式为溢出隐藏，在该div中插入ul，li中分别是各个Img标签，ul长度为li的总长度，并将ul相对div定位，初始化位置为left=0；<br/>
2.因为需要无缝轮播，所以在最后一个li后面再插入一个li，在其中插入第一张图片，第一次播放时第一张图片是第一张图片，后面轮播时，最后一张图片播放完后播放的第一张图片实际上是最后一张图片，此时判断ul相对div的位置，再设置下一张图片显示时ul的位置（也就是第二张图片位置），从而造成无缝的错觉。<br/>

## index3——特效搜索框
#### [demo示例](http://htmlpreview.github.io/?https://github.com/ljuyi/javascript/blob/junyi.li/index3.html)

#### 原理说明
1.文本域获取焦点时加入动画效果<br/>
2.文本域失去焦点时加入动画效果<br/>
