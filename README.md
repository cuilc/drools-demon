#DroolDemo

我们定义一下发放规则：

积分的发放参考因素有：交易笔数、交易金额数目、信用卡还款次数、生日特别优惠等。

定义规则：  
- 过生日，则加10分，并且将当月交易比数翻倍后再计算积分  
- 2011-01-08 - 2011-08-08每月信用卡还款3次以上，每满3笔赠送30分  
- 当月购物总金额100以上，每100元赠送10分  
- 当月购物次数5次以上，每五次赠送50分  
- 特别的，如果全部满足了要求，则额外奖励100分  
- 发生退货，扣减10分  
- 退货金额大于100，扣减100分  

	mvn install
	