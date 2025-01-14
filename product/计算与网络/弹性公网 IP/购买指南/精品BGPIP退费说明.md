为了方便您使用腾讯云弹性公网 IP（EIP），如果您在购买 EIP 后有任何不满意，我们支持包月带宽计费模式的 EIP 享有 [五天内自助退还](#nonreason) 和 [普通自助退还](#ordinary)。
- 包月带宽预付费：您可申请退货退款，每个账号默认享有1次五天内无理由全额退款，其余退款申请按照非全额退款处理。具体操作详情请参见 [退还包月带宽 EIP](https://cloud.tencent.com/document/product/1199/43137#.E9.80.80.E8.BF.98.E5.8C.85.E6.9C.88.E5.B8.A6.E5.AE.BD-eip.3Ca-id.3D.2233.22.3E.3C.2Fa.3E)。
- 按流量后付费：您可申请直接清退资源，无法申请退款。具体操作详情请参见 [释放 EIP](https://cloud.tencent.com/document/product/1199/41704)。


## 自助退还说明
- 包月带宽实例自助退还后，实例的状态一旦变为已释放或已销毁时，就不再产生与该实例相关的费用。
- 包月带宽实例自助退还后，实例将进入隔离期保留7天。若期间未进行续费，则隔离期满后，再经过7天将自动释放该实例。
- 若退还的包月带宽实例非首次退还，则此次退还距离之前续费的时间不得小于6小时，否则无法退还。
- 如出现疑似异常/恶意退货，腾讯云有权拒绝您的退货申请。
- 部分活动资源不支持自助退还，具体以官网展示为准。

## 五天内自助退还[](id:nonreason)
弹性公网 IP 产品遵守腾讯云 [云服务退货说明](https://cloud.tencent.com/document/product/555/7440)，如果您在购买 EIP 后有任何不满意，我们支持五天内无理由自助退还，具体规则如下：
>! 
> - **抵扣的代金券不予以退还。**
> - **退还金额**将全部退还到**腾讯云账号余额**。
> 
1. 对于每个主体而言，EIP 新购之日起五天之内（含五天），可支持**1**个  EIP 实例五天无理由退还。
2. 符合五天无理由退还场景的订单，退款金额为**购买时花费的全部消耗金额** ，包括现金账户金额、收益转入账户金额以及赠送账户金额。
3. 如出现疑似异常/恶意退货，腾讯云有权拒绝您的退货申请。



## 普通自助退还[](id:ordinary)
- 如果您已经享用5天无理由退还，我们还支持您的**199**个包月带宽 EIP 实例可在任意时间内，在控制台自助退还。
- 普通自助退还将扣除您已使用的费用，退款金额将按购买支付使用的现金和赠送金支付比例退还至您的腾讯云账号。

### 普通自助退还规则
>! 
> - **抵扣的代金券不予以退还。**
> - **退还金额**将按**购买支付使用的现金和赠送金支付比例**退还至您的腾讯云账户。
> 
**退款金额 = 当前有效订单金额 + 未开始订单有效金额 - 资源已使用价值。**
- **当前有效订单金额：**指生效中订单的付款金额，不包含折扣和代金券。
- **未开始订单金额：**将来生效的订单的付款金额，不包含代金券。
- **资源已使用价值**按照如下策略计算：
  - 发起退费的当天，已使用满整月的，按已使用整月的包月带宽计费价格进行扣除；不满整月的，按已使用时长的比例进行扣除。
  - 已使用时间精确到秒。
- **退款金额** <= 0时，按0计算并清退资源。

## 自助退还计费规则示例
>! 以下价格均做示例用，非官网实际价格。具体单价可能因地域、活动或策略等调整变化，请以实际单价为准。计费详情请参见 [计费说明](https://cloud.tencent.com/document/product/1199/41692)。

### 示例背景
您在香港地域购买了一个包月带宽的精品 BGP IP 实例，公网带宽为5Mbps，1900元/月，使用200元代金券，购买3个月。
- 总金额为：1900元/月 × 3月 = 5700元
- 支付金额为：5700元 - 200元 = 5500元

### 五天无理由退还场景
购买五天内发现不满意，想要退还，且该账户首次退还。
**退款金额** = 真实支付金额5500元

### 普通自助退还场景
**示例1**：使用1个月零8天后退款，假设购买期内每月均30天。
**退还现金金额** = 5500元 - (38天 ÷ 90天) × 5700元 = 3093.33元
>?退费金额 = 支付金额 - (已使用时长 ÷ 总时长)× 订单原价。

**示例2**：使用1个月零8天后退款，其中使用期间内又续费3个月，续费实际支付金额5700元，假设购买期内每月均30天。
**退还现金金额** = 5500元 + 5700元 - (38天 ÷ 180天) × (5700元 + 5700元) = 8793.33元
>?(38天 ÷ 180天) × (5700元 + 5700元)为资源已使用费用。

