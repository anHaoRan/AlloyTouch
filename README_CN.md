﻿[English](https://github.com/AlloyTeam/AlloyTouch) | 简体中文

# AlloyTouch

腾讯AlloyTeam移动Web触摸解决方案

# Install
```js
npm install alloytouch
```

# API
```js
new AlloyTouch({
            touch:"#wrapper",//反馈触摸的dom
            vertical: true,//不必需，默认是true代表监听竖直方向touch
            target: target, //运动的对象
            property: "translateY",  //被运动的属性
            min: 100, //不必需,运动属性的最小值
            max: 2000, //不必需,滚动属性的最大值
            sensitivity: 1,//不必需,触摸区域的灵敏度，默认值为1，可以为负数
            factor: 1,//不必需,表示触摸位移与被运动属性映射关系，默认值是1
            spring: true, //不必需,是否有回弹效果。默认是true
            step: 45,//用于校正到step的整数倍
            change:function(value){  }, //不必需，属性改变的回调。alloytouch.css版本不支持该事件
            touchStart:function(evt, value){  },
            touchMove:function(evt, value){  },
            touchEnd:function(evt,value){  },
            tap:function(evt, value){  },
            pressMove:function(evt, value){  },
            animationEnd:function(value){  } //运动结束
 })
```
# 演示(Mobile)

- Simple : [http://alloyteam.github.io/AlloyTouch/](http://alloyteam.github.io/AlloyTouch/)
- 3D : [http://alloyteam.github.io/AlloyTouch/example/3d.html](http://alloyteam.github.io/AlloyTouch/example/3d.html)
- Rotate : [http://alloyteam.github.io/AlloyTouch/example/rotate.html](http://alloyteam.github.io/AlloyTouch/example/rotate.html)
- Carousel : [http://alloyteam.github.io/AlloyTouch/example/carousel.html](http://alloyteam.github.io/AlloyTouch/example/carousel.html)
- Carousel2 : [http://alloyteam.github.io/AlloyTouch/example/carousel2.html](http://alloyteam.github.io/AlloyTouch/example/carousel2.html)
- Three.js : [http://alloyteam.github.io/AlloyTouch/example/threejs/](http://alloyteam.github.io/AlloyTouch/example/threejs/)

# 感谢
- [transformjs](http://alloyteam.github.io/AlloyTouch/transformjs/)

# 谁用AlloyTouch?

![preview](http://sqimg.qq.com/qq_product_operations/im/qqlogo/imlogo.png)

# License
This content is released under the [MIT](http://opensource.org/licenses/MIT) License.
[掘金地址](https://gold.xitu.io/post/584e4f2fb123db0066211c18)
