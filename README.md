# 删减版的backbone

结合项目的实际使用，对backbone源码做了删减和部分增加；

## 删除部分

* backbone.model
* backbone.collection

## 增加部分

* 支持路由不区分大小写，使得路由可以实现驼峰命名
* 支持路由事先检测，解决在跳路由前，先处理通用的功能


# 删减版的underscore

只提供backbone依赖的underscore函数

## 保留的其他函数

* _.each
* _.template

