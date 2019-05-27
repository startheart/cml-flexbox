# cml-flexbox
基于[chameleon](https://github.com/didi/chameleon)跨端框架，测试 FlexBox 布局实现效果

web 端预览效果：
[访问地址](https://startheart.github.io/cml-flexbox/dist/web/cml-flexbox.html)

## 使用

- 克隆项目 `git clone https://github.com/startheart/cml-flexbox.git`
- 安装项目依赖 `npm install`
- 全局安装cml脚手架 `npm i chameleon-tool -g`
- 启动项目 `cml dev`

## FlexBox布局模型 
从被作用对象来分类这些属性：
#### 父容器
- flex-direction  定义主轴的方向（即项目的排列方向）
- flex-wrap       定义主轴排列的项目如何换行
- flex-flow        flex-direction属性和flex-wrap属性的简写
- justify-content  定义项目在主轴上的对齐方式
- align-items      定义项目在侧轴上的对齐方式
- align-content   定义多根轴线的对齐方式

#### 子项目
- order         定义项目的排列顺序
- flex-grow   定义项目的放大比例
- flex-shrink 定义项目的缩小比例
- flex-basis   定义在分配多余空间之前，项目占据的主轴空间（main size）
- flex            flex-grow, flex-shrink 和 flex-basis的简写
- align-self    可覆盖align-items属性

## [跨端样式一致性](https://cml.js.org/doc/view/cmss/base_style.html)
- 盒模型(box-sizing)：
height、width、padding、border、margin …..

- 布局模型(display)：
flex、block、inline-bock

- 定位(position)：
static、relative、absolute、fixed...

- 文本(font)：
font-size、font-weight、font-family、line-height...

## 预览效果

| web   |      微信小程序      |  native-weex |  百度小程序 |  支付宝小程序 |
|:----------:|:-------------:|:------:|:------:|:------:|
| <img src="./preview/web-1.png" width="200px"/> |  <img src="./preview/wx-1.png" width="200px"/>| <img src="./preview/weex-1.png" width="200px"/> |<img src="./preview/baidu-1.png" width="200px"/> |<img src="./preview/alipay-1.png" width="200px"/> |
