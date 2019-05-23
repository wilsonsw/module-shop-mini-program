## ModuleShop

一个基于 .NET Core构建的简单、跨平台、模块化的商城系统。

系统由三部分组成：后台API、后台前端、微信小程序。

***

## 后台API

项目地址：[https://github.com/trueai-org/module-shop](https://github.com/trueai-org/module-shop)

在线预览（Swagger）：[https://shopapi.circle.ac.cn/swagger](https://shopapi.circle.ac.cn/swagger)

***

## 后台前端

项目地址：[https://github.com/trueai-org/module-shop](https://github.com/trueai-org/module-shop)

在线预览（admin/123456）：[https://shop.circle.ac.cn](https://shop.circle.ac.cn)

***

## 微信小程序

**注意：当前版本功能还未完善，请勿商用。**

本项目需要配合ModuleShop商城服务端使用，GitHub: [https://github.com/trueai-org/module-shop](https://github.com/trueai-org/module-shop)

### 在线预览
![小程序码](https://gogs.circle.ac.cn/gogs/data/raw/master/images/shop_mp_8_8.jpg)
<img src="https://gogs.circle.ac.cn/gogs/data/raw/master/images/shop_mp_8_8.jpg" width="200">

 <!-- ![小程序码](https://gogs.circle.ac.cn/gogs/data/raw/master/images/shop_mp_8_8.jpg) -->

#### 后台api
[https://shopapi.circle.ac.cn](https://shopapi.circle.ac.cn)

#### 后台前端
[https://shop.circle.ac.cn](https://shop.circle.ac.cn)
**用户名/密码：admin/123456**

### 项目截图
![首页](https://gogs.circle.ac.cn/gogs/data/raw/master/images/wechatdevtools_2019-04-26_17-44-30.png)

![分类](https://gogs.circle.ac.cn/gogs/data/raw/master/images/wechatdevtools_2019-04-26_17-45-37.png)

![购物车](https://gogs.circle.ac.cn/gogs/data/raw/master/images/wechatdevtools_2019-04-26_17-50-15.png)

![商品详情](https://gogs.circle.ac.cn/gogs/data/raw/master/images/wechatdevtools_2019-04-26_17-50-50.png)

![订单列表](https://gogs.circle.ac.cn/gogs/data/raw/master/images/wechatdevtools_2019-04-26_17-54-33.png)

![评价](https://gogs.circle.ac.cn/gogs/data/raw/master/images/wechatdevtools_2019-04-26_17-56-43.png)

![我的](https://gogs.circle.ac.cn/gogs/data/raw/master/images/wechatdevtools_2019-04-26_17-57-19.png)


### 功能列表
+ 首页
+ 分类首页、分类商品、新品首发、人气推荐、商品页面等、可通过后台配置
+ 商品详情页面，包含加入购物车、收藏商品、商品评论功能
+ 搜索功能
+ 完整的购物流程，商品的加入、编辑、删除、批量选择，收货地址的选择，下单支付
+ 会员中心（订单、收藏、足迹、收货地址、意见反馈）
....

### 项目结构
```
├─config                
├─lib
│  └─wxParse　　　
├─pages
│  ├─auth
│  │  ├─login
│  │  ├─register
│  │  └─reset
│  ├─brand
│  ├─brandDetail
│  ├─cart
│  ├─catalog
│  ├─category
│  ├─comment
│  ├─goods
│  ├─hotGoods
│  ├─index
│  ├─logs
│  ├─newGoods
│  ├─pay
│  ├─search
│  ├─shopping
│  │  ├─address
│  │  ├─addressAdd
│  │  └─checkout
│  ├─topic
│  ├─topicDetail
│  └─ucenter
│      ├─address
│      ├─addressAdd
│      ├─collect
│      ├─coupon
│      ├─feedback
│      ├─footprint
│      ├─index
│      ├─order
│      └─orderDetail
├─static
│  └─images
└─utils
```

### 服务端api
项目地址：https://github.com/trueai-org/module-shop

### 服务端后台
项目地址：https://github.com/trueai-org/module-shop-admin

### 交流
喜欢别忘了 Star，有问题可通过微信、公众号、QQ 群联系我，谢谢您的关注。
