# 随行租车

#### 项目介绍

这是一个仿照一嗨租车开发的基于Spring Boot的租车项目，用户注册并登录该平台，登录注册采用了MD5前后端同时加密的技术，
登录完了之后，可以在主页面看到当前热门的车型，然后进行预定车辆。还可以根据定位推荐附近门店，之后便可根据时间段和门店
进行租借想要使用的车辆。用户可以根据时间、品牌，价格等多种条件查询合适时间段的车辆，还可以查看车辆详情等等。在车辆详情页面，
用户可以查看当前车型的评价，还能对评价的人进行回复，如果觉得评价实用的话还可以对评价进行点赞，在选择完喜欢的车辆之后进行预定，预定的时候可以根据用户领取的优惠券来减免费用，预定成功之后提交订单，
然后进行用户信息的填写，用户可以进行手动填写和利用OCR技术进行对上传的身份证和驾驶证进行识别并填入，然后进行支付订单。

支付采用支付宝沙箱的技术进行支付，支付完成之后，会返回给客户一个回执编号，用于门店取车。租期到期后，用户可以在订单详情中一间还车，如果用户对于服务有什么建议的话还可以对此次租车服务进行评价。

#### 项目