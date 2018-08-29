# 移动端豆瓣电影轻页面
## 预览链接
- 预览地址：https://f0rl.github.io/douban-mobile/index.html
- 扫描二维码

![](http://ww1.sinaimg.cn/large/90864b23gy1fuqpyk1recj207s07st8n.jpg)

## 界面介绍
- 主要由 `top250榜单`、`北美最新电影`、`搜索` 三个`tab`页面构成

## 版本
### index-bad.html
最原始的实现方式，对页面交互逐个实现，仅完成了`top250榜单`页面，使用了函数节流优化

### index-repeat
考虑到代码的复用，对数据获取、数据渲染等功能进行包装

### index.html
进一步优化代码，对各个界面相同的功能进行模块化包装

## 项目知识点

### 样式与布局
- 相对单位 vw 的使用
- `iconFont` 的使用
- `@keyframes` 关键帧的使用
- Flex 布局

### 页面相关功能
- 实现切换功能，点击改变颜色并展示对应界面
- 从api接口获取数据
- OM拼接
- 判断是否滑动到达底部
- loading动画的实现


