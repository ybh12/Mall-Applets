#1.接口文档
[接口]: https://www.showdoc.com.cn/128719739414963/2526176842444912 "接口文档"
>[接口] 文档参考
----

#2.帮助文档
---
[小程序开发文档]: https://developers.weixin.qq.com/miniprogram/dev/component/share-element.html
"小程序开发"
&emsp;1.[小程序开发文档]



#3.搭建目录结构
---
##3.1.新建小程序项目
>填写自己的ID

##3.2.搭建目录结构
|目录名|作用|
|:-|:-:|-:|
|styles|存放公共样式|
|components|存放组件|
|lib|存放第三方库|
|utils|存放自己的帮助库|
|request|自己的接口帮助库|
##3.3.搭建项目的页面
|页面名称|名称|
|:-|:-:|-:|
|首页|index|
|页面分类|index|
|商品列表页面|goods_list|
|商品详情页面|goods_detail|
|购物车页面|cart|
|收藏页面|collect|
|订单页面|order|
|搜索页面|search|
|个人中心页面|user|
|意见反馈页面|feedback|
|登录页面|login|
|授权页面|auth|
|结算页面|pay|
--
#4.主页的设计
---
##4.1.搜索框
>1.在组件文件下创建SearchInput 文件
>>包含四个项目(app\josn\wxss\js)


>2.在子文件夹下的josn文件夹中声明应用如下：（切记路径为相对路径）

```
  "usingComponents": {
    "SearchInput":"../../components/SearchInput/SearchInput"  //"组件件名称":"相对路径"
},
```



