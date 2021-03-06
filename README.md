# **ThinkPHP集成支付宝demo_采用自定义类形式**

![](http://www.itinfor.cn/wp-content/uploads/2017/08/pay_ui.png)

## 目录介绍
* AlipayClass：为ThinkPHP3.2.3版本集成支付宝及时到账官方demo的demo
* AlipayDemo：为支付宝及时到账官方demo

## 修改说明
* AlipayDemo：<br />
	该文件在AopClient.php的第426行追加了一个写文件的操作，如此我们就可以很清楚的看到到底给支付宝提交了哪些参数以及这些参数所对应的值,其他未做任何处理
* AlipayClass：<br />
	1. 将支付宝官方demo整体搁到ThinkPHP的三方库下面
	
	2. 然后在官方demo的配置文件中填写上需要的参数：app_id、公私钥等
	
	3. 创建前台文件夹并编写支付、充值记录页面
	
	4. 编写自定义类将官方demo中对数据处理的方法进行二次封装，方便调用（此处有修改文件包含的情况）
	
	5. 追加自定义数据库，并附赠对应sql文件
	
	6. 实现支付时写入数据库，回调时修改数据库对于字段的功能
	
	7. 以上为简要说明，具体修改请参见该网址：http://www.itinfor.cn/archives/1319
	
## 演示说明
* 暂无，敬请期待─=≡Σ(((つ•̀ω•́)つ

## 联系方式
* QQ：980569038 （添加请注明技术咨询）
* QQ群：594955172 （TP支付宝集成，添加请注明技术咨询）

## 打赏说明
* 该源码是本人业余时间编写的，若对您有一定的帮助，欢迎打赏，打赏金额将用于域名、服务器升级续费。后期会出一个打赏记录页面，具体什么时候出，我也不是很清楚，不过放心你们的打赏我记着的
*  可通过以下方式进行打赏：

![](https://raw.githubusercontent.com/paopao7/source/master/alipay_new.jpg)

![](https://raw.githubusercontent.com/paopao7/source/master/weixin_pay_new.jpg)


## 总结说明
* 大家都是一群热爱技术的程序猿\程序媛,你我本着开源的精神将自己编写的demo公开出来供大家使用，希望大家珍惜并尊重其他人的劳动成果
* 若您对我的项目有任何修改，欢迎提交到本GitHub地址
* 若您对我的源码有任何意见，也欢迎添加本人QQ

	
	
	



