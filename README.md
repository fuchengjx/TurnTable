# Turntable
一个抽奖转盘

一个原生js写的抽奖转盘，旋转动画采用element.animate()添加。具备移动端兼容。在不同的屏幕宽度会缩放转盘大小。 点击抽奖后，指针转动。转动结束后，将会显示你获得的奖品。指针在转动时无法点击，停止转动后才可以再次点击转动。

![1571313830010](http://cetquery.flura.cn/1571313830010.png)

```
// 自己设置奖品，改变数组的内容就可以改变奖品
let reward = ['谢谢参与', '50积分', '谢谢参与', '100元话费', '50积分', '谢谢参与', '100元话费', '谢谢参与', '50积分', '10元话费']
```

因为没有设置概率函数，所以每个奖品被抽中的概率理论上都是相等的。

代码参考：[用CSS实现一个抽奖转盘](https://www.cnblogs.com/wenruo/p/9732704.html)