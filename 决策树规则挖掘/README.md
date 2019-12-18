# 问题：
给定一组出租司机用户，现在要根据他们的请款决定给其中一部分人放贷，给出一个方案，使放贷的人尽量多，坏账率尽量低。

# 特征含义
变量类型	最终基础变量名（还需要做上述变换）	释义
数值统计型		
	oil_amount	加油升数
	discount_amount	折扣金额
	sale_amount	促销金额
	amount	总金额
	pay_amount	实际支付金额
	coupon_amount	优惠券金额
	payment_coupon_amount	支付优惠券金额
		
		
分类型		
	channel_code	渠道
	oil_code	油品品类（规格）
	scene	场景
	source_app	来源端口（1货车帮、2微信）
	call_source	订单来源(1:中化扫描枪 2:pos 3:找油网 4:油掌柜5：司机自助加油 6 油站线)
		