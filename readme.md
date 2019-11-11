### 微信，支付宝，云闪付个人免签支付系统

`免签支付``个人网站支付``支付宝免签支付``云闪付免签支付`

-------------------

### [免签支付测试页面(点我跳转)](http://pay.changu.net/pay) 
http://pay.changu.net/pay 

如遇到测试失败等问题可联系：QQ497596754

#### 目前支持如下免签支付：
 - 微信支付
 - 支付宝二维码　
 - 支付宝红包　
 - 支付宝主动收款　
 - 支付宝银行卡　
 - 云闪付　 

#### 系统介绍：
    
> 个人网站如何实现支付功能？想必很多程序员都有过想开发一个自己的网站来获得一些额外的收入，但做这件事会遇到支付这个问题。目前个人网站是无法实现支付功能的。目前主流的技术实现方案都是基于xposed逆向微信、支付宝、云闪付来实现个人免签支付
    
> 关键点在于如何逆向微信支付宝云闪付这些App，找到核心函数钩子，然后写一个hook程序来模拟调用这些方法，来实现根据服务端传过来的金额，订单号自动调用微信支付宝生成支付二维码的函数得到相对应的支付二维码再传给服务端，然后监听微信支付宝的支付成功消息最终回调给服务端实现支付成功通知。这里面用到的核心技术点有：xposed逆向框架、apk反编译，网络抓包，apk动态调试等技术。
    
> 像微信支付宝这些apk反编译后的代码基本上都是天书一样的，严重混淆过的代码。想从中找到核心代码并非易事。

#### 系统效果图
![enter image description here](https://raw.githubusercontent.com/cinser/weixin-alipay-yunshanfu-paytest/master/demo1.png)
![enter image description here](https://raw.githubusercontent.com/cinser/weixin-alipay-yunshanfu-paytest/master/demo2.png)
