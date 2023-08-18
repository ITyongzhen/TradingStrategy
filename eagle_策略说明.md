
## 前言

- 这是长期趋势策略。不建议重仓。把仓位控制在可控制范围内。如果追求把把梭哈的，每个月翻几倍的，不建议订阅
- 行情不可预测，做好风险控制
- 承诺如果一个月不盈利的(自己不手动干预情况下)，下个月免费延期
- 回测不代表未来。过去实盘也不代表未来。币圈有风险，投资需谨慎
- 所有策略都可免费试用1周
- 使用我的节点注册欧意，自动返佣20%，并充值超过500U, 额外再给2周试用时间，也就是总共3周试用时间
## 联系方式：
- telegram: @eagle_012
- wechat: eagle_01yz
	- 无论是否订阅，都可加入微信群一起交流
- 币coin实盘 点击用户搜索 eagle
- 返佣链接  https://www.cnouyi.expert/join/41686764
- 邀请码： 41686764
-  1：路人，欧意返佣(自动返佣20%) ，
-  2：群友40% （自动20%+手动20%）
-  3，试用：欧意返佣(自动返佣20%) ，需要充值500U，总共给3周试用时间
-  有很多手动返佣的都不返够。用我节点的返佣保证按照比例返，如果有疑问可以联系我，看后台数据
## 策略说明
-  [自主调节版本](https://www.tradingview.com/script/RvwT64Nd-eth-30min-%E8%B6%8B%E5%8A%BF-%E8%87%AA%E4%B8%BB%E8%B0%83%E8%8A%82%E8%83%9C%E7%8E%87%E7%89%88%E6%9C%AC/)
自主调节胜率版本的核心思想是通过调节胜率因子来平衡盈亏比和胜率。这个策略的目的是适应不同人的心态差异。有些人更注重高胜率，而有些人则更看重盈亏比。单笔止盈百分比是指提前平仓的比例。这样做的好处是如果无法达到止盈点位，损失会较小。相反，如果达到止盈点位却提前平仓，盈利也会减少。
回测如下 

- ![image](https://github.com/ITyongzhen/image_eagle/blob/main/WechatIMG565.jpeg?raw=true)


- [ETH 30-V1版本]( https://www.tradingview.com/script/32fxHjtO-eth-30min-%E9%95%BF%E6%9C%9F%E7%A8%B3%E5%AE%9A%E7%AD%96%E7%95%A5/) 该版本的主要特点是追求长期稳定性。与自主调节胜率版本不同的是，该版本最多只能进行一次提前平仓。将该参数设置为0，则不进行提前平仓，仅进行一次平仓操作。

- ![image](https://github.com/ITyongzhen/image_eagle/blob/main/WechatIMG564.jpeg?raw=true)

- [V2+V3]( https://www.tradingview.com/script/sJu0UBwc-eth-30min-V2-and-v3/) V2版本和V3版本具有完全相同的参数，因此将这两个策略合并为一个，通过开关控制。
	- 参数说明：
		- V3模式：表示是否开启V3版本，关闭则使用默认的V2版本。
仓位管理系数：这是影响每次交易仓位的关键因素之一。建议将其设为0.6以下。简单来说，值越大，当市场震荡较久时，磨损也越多，但行情好时赚取的利润也会更多。
		- 策略开始日期：最好将其设置为实际交易开始的日期。由于开仓点位参考了历史盈亏，因此将该参数设置为开始实际交易的那天，相当于从那天起进行第一笔交易。

- ![image](https://github.com/ITyongzhen/image_eagle/blob/main/WechatIMG563.jpeg?raw=true)


- 所有策略的仓位管理都是基于参考止损金额来确定的。该参数是理论上的单次止损金额，实际上可能会大于或小于该值，因此更像是一个参考值。
- 
- ![image](https://github.com/ITyongzhen/image_eagle/blob/main/%E8%AE%BE%E7%BD%AE%E8%AF%B4%E6%98%8E.jpg?raw=true)
- 使用说明：这些策略与您的本金无关。我的理念是每个人的本金和风险承受能力不同。举个例子，某人的本金为1WU，但亏损1000U就无法承受；而另一个人的本金为3000U，可以承受亏损2000U。因此，仓位和本金应该无关。我通过止损来控制仓位。

- 具体而言，通过调整参数参考止损金额、仓位管理系数和止盈百分比进行回测。一般建议回测时间为一到两年。然后观察最大回撤值。我推荐采取保守的做法。比如，如果您能够承受最多1000U的亏损，您可以通过调整参数，使得最近两年的最大回撤不超过500U，这样相对来说比较适合。需要注意的是，这仅仅是一种相对保守的建议，并且行情是无法预测的，过去的数据并不能代表未来。

## 如何使用
- 自己对接需要[tv会员](https://www.tradingview.com/gopro/?share_your_love=ea704) 和 [tvc会员](https://www.tvcbot.com/aff.php?aff=550)，或其他的自己搭建平台都可以，把下面的对接文档看完就懂了

- ![image](https://github.com/ITyongzhen/image_eagle/blob/main/WechatIMG569.jpeg?raw=true)



- ![image](https://github.com/ITyongzhen/image_eagle/blob/main/WechatIMG568.jpeg?raw=true)

## 如何定价

- 随着人数的变化，价格可能后期会调整。目前价格如下

-  [自主调节版本](https://www.tradingview.com/script/RvwT64Nd-eth-30min-%E8%B6%8B%E5%8A%BF-%E8%87%AA%E4%B8%BB%E8%B0%83%E8%8A%82%E8%83%9C%E7%8E%87%E7%89%88%E6%9C%AC/)   200U/月
- [ETH 30-V1版本]( https://www.tradingview.com/script/32fxHjtO-eth-30min-%E9%95%BF%E6%9C%9F%E7%A8%B3%E5%AE%9A%E7%AD%96%E7%95%A5/)   200U/月
- [ETH 30-V2+V3]( https://www.tradingview.com/script/sJu0UBwc-eth-30min-V2-and-v3/)  200U/月

- [分批止盈](https://www.tradingview.com/script/VBfCaesi-eth-30min-%E5%88%86%E6%89%B9%E6%AD%A2%E7%9B%88/) 200U/月




## 其他
- 如果自己本金太小。也想使用，可通过跟单模式
- 欧意跟单，去[欧意跟单](https://www.okx.com/cn/copy-trading/square) 搜索 eagle_01 就可以看到了

- 币安的[traderwagon](https://www.traderwagon.com/zh-CN/register?ref=zogys9x )  ,在里面搜索eagle就可以看到了

<!--- ![image](https://github.com/ITyongzhen/image_eagle/blob/main/WechatIMG566.jpeg?raw=true)-->


- [bitGet跟单广场](https://www.bitgetapp.com/zh-CN/copytrading/futures/all) 搜索 eagle_01 就可以看到了
这个平台主要测试小币种，如果一段时候之后没问题，就去欧意币安带单

<!--- ![image](https://github.com/ITyongzhen/image_eagle/blob/main/WechatIMG567.jpeg?raw=true)-->




 -  历史回测不代表未来，上个月的实盘也不代表下个月行情
 -  历史回测不代表未来，上个月的实盘也不代表下个月行情
 -  历史回测不代表未来，上个月的实盘也不代表下个月行情
 -  历史回测不代表未来，上个月的实盘也不代表下个月行情
 -  历史回测不代表未来，上个月的实盘也不代表下个月行情
 - 币圈有风险，投资需谨慎。
 - 币圈有风险，投资需谨慎。
 - 币圈有风险，投资需谨慎。
 - 币圈有风险，投资需谨慎。

