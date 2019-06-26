# rollVideo
仿抖音微视触屏滚动播放小程序版

##### 效果图：

![显示和隐藏.gif](https://blog-1259100054.cos.ap-guangzhou.myqcloud.com/images/githubVideoDemo.gif)


> 一直想写个类似抖音那样的上下滑动切换，奈何web端开发还是跟原生有区别，虽然没有完全达到抖音效果，也基本满足了需求


###### 实现思路：
- tuoch 实现滑动的切换，css3过渡完成切换动画，不能连续切换，避免出现其他问题
- 优化渲染节点数量，不宜过多，需要判断列表靠前后的item
- video视频在一些机型会出现层级变高，需要将浮层原生改成cover-view  cover-image 等

###### 觉得有帮助抬起你的幸运小手为我点击star

