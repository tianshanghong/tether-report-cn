# 量化Tether的影响

*The Tether Report* 中文翻译版

## 译文说明

原文地址：[Quantifying the Effect of Tether](https://www.tetherreport.com)

网页存档：[GitHub](https://github.com/tianshanghong/tether-report-cn/tree/master/archive)（2019年8月29日）

译文地址：[量化Tether的影响 http://www.tetherreport.cn](http://www.tetherreport.cn)

## 译文内容

2018年1月24日

作者 - `32E3690D50B3B477DF7841212D4BB938DC9CDB50307618328E7F8B53F37CC1E2`

**免责声明**

本报告中所提供的信息仅供参考。它不应被视为法律或财务建议。您应咨询律师、财务顾问或其他专业人士，以获取最适合您个人需求的内容。

1000x Group对使用我们的内容可能获得的任何结果不作任何保证或其他承诺。没有事先咨询自己的财务顾问并进行自己的研究和尽职调查，任何人都不应做出任何投资决定。

本网站和报告中包含或提供的内容无意也不构成法律或投资建议，也不构成顾问-客户关系。您自行承担您在使用本报告中的信息时的风险。

本报告中表达的观点均为作者的观点，不应被视为代表1000x集团的观点。

**作者**

该报告的作者将被标记为 `32E3690D50B3B477DF7841212D4BB938DC9CDB50307618328E7F8B53F37CC1E2`。

作者担心会遭受抵制，因此要求通过使用他们名字的公共哈希来签署此报告来保持匿名。

有时人们会表达不受欢迎的观点和意见。匿名哈希签名使作者能够在不用受到针对个人的反对的情况下分享这些观点和意见。

如果你有一个想要分享的宝贵观点，请通过共同的朋友来联系我们。我们很乐意谈谈。

**摘要**

 - 作者的观点 - Tether不太可能通过任何自然业务发展。它很有可能是根据市场情况进行印钞进行盈利。
 - Tether增发会显著地推动市场发展。在91次不同的Tether到Bitfinex钱包的发放中，**48.8%** 的情况比特币的价格会在两小时内上涨。
 - Bitfinex的存取款数据不同寻常，并且会在典型的会计环境中引发进一步的审查。
 - 如果有可疑活动发生，作者认为可以预测比特币的价格会降低**30-80%**。

**报告**

Tether[1]是一个“稳定币”，是在Omni网络上的一种代币（覆盖在比特币网络上），旨在维持每个Tether或“USDT”可以兑换一美元的稳定价值。通过从客户那里获取美元存款并将其兑换成等量的USDT，Tether在2014年对真实货币[2]进行表面上功能性的重塑，进而获得了今天的形象。Tether的一个优点是可以在不拥有美元控制的银行账户的情况下，对数字资产进行定价。鉴于许多交易所在维护世界各地的银行业务关系方面面临极大困难，这种安排非常具有吸引力。截至撰写本文时，Omni网络上存在2,150,000,000 USDT [3]，而在以太坊网络上有以欧元计价的另外约0.14亿Tether的ERC20代币。该分析将重点关注Omni网络上以美元计价的Tether。

2017年，许多令人担忧的事件引起了对Tether的关注。4月份，他们发现他们在台湾的银行业务关系已被切断;这导致零售客户的存款和取款被暂停。尽管他们自称无法接受来自非台湾银行账户的存款，但从4月开始大量扩张市场上的Tether。9月初，Tether否认他们资金不足，并承诺提供历史审计（在撰写本文时审计仍不完整）[5]。他们在9月底制作了一份内部文件[6]，显示美元余额足以支持当时不多的约4.4亿美元的数额。但这个数字仅在5个月内增加了10倍。这些基金附带的服务协议和机构名称没有在这份内部备忘录中透露给公众。自4月份报告确定其早期银行合作伙伴名称以来，Tether的透明度降低。在11月，他们遇到了一个黑客攻击[7]，并通过修改Tether网络代码缓解了这一问题，这允许他们“冻结”价值超过3000万美元的资金。12月，他们宣布将逐步取消现有平台，不再尝试在现有钱包上存款[8]。

Tether发行与比特币价格之间高度相关的增长带来了几个有趣的问题。比特币的增长是否会推动Tether？ Tether发行是否会推动比特币？ 如果人们假设最糟糕的情况，比特币的价格已经被Tether发行人为地提高了，那么人们就会预计，根据2017年4月之前的趋势线以及Tether发行的显着增长，比特币的市场价格将接近2,000美元。

![](https://raw.githubusercontent.com/tianshanghong/tether-report-cn/master/archive/images/image4.jpg)

如果我们不作任何假设并相信Tether的话；在新的USDT被授予之前，新Tether的创建会由存入银行的美元支持，这些购买在出于方便的考量将会直接分发给Bitfinex，以及Tether授予的时间是由市场参与者增加其加密货币持有量的自然行为。