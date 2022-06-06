# Meta元宇宙 NFT藏品 前端H5+APP+小程序源码 Meta-APP
# META-NFT-Market
# 项目介绍 -- 幻核 鲸探 唯一艺术 
目前最新最火的元宇宙NFT藏品项目，支持二次开发

不用再找了，这就是最新的台子

支持平台邀新注册活动、直购、优先购、盲盒、空投、兑换、抽（中）签、转赠、合成玩法、二级（衍生品）流通交易等功能

## 支持系统
[Meta元宇宙 NFT藏品 后台管理系统源码 Meta-Admin](https://github.com/Meta-NFT-boy/meta-nft-admin)

[Meta元宇宙 NFT藏品 服务端系统源码 Meta-Server](https://github.com/Meta-NFT-boy/meta-nft-server)


**效果演示**

- [效果演示地址](http://server.aimdream.com)

**说明：**

**master**：支持各大主流小程序，和iOS、安卓客户端

## 提示 如果您喜欢并看好这个行业，我们一起聊聊行业，如果您想在行业有所建树和发展，那我们可以一起聊聊更多合作机会

```bash
  如果对您对此项目有兴趣，觉得该项目对你有帮忙，可以联系我们! 谢谢！ ^_^
  
  如有问题请直接联系我们，或者您发现问题并有非常好的解决方案，欢迎提出
```

## 合作交流，项目答疑

欢迎联系我们：

QQ：287145101、1423374876

微信：huniuoo

加的时候备注：github

<img width="300" src="https://github.com/Meta-NFT-boy/meta-nft-admin/blob/main/static/weichat.png">

# 优先购特别说明

目前支持有三种优选购配置

创世优先于中签用户，中签用户优先普通用户

一、创世用户优先购，（名单是动态的，根据平台设定的条件快照白名单）

未购完的份额，自动分配到中签用户份额，如果没有中签用户份额，继续分配到普通购买份额中

二、中签用户优先购

中签又分两种

1. > 一种是优先于普通用户的购买。未购完的份额，自动分配到普通购买份额中

2. >另外一种是一期藏品只有中签用户才能购买

普通用户0购买额度，即不能购买

优先购期间，只有优先购用户可以看到购买按钮，其他用户是倒计时。

三、最后是普通用户抢购

如果没有设置前面两个优先购，则全部都是普通用户可购买

## 中签演示

### 盲盒支持两种模式，一种是购买资格盲盒，一种是N个藏品抽取其一的盲盒。

流程是预约->抽签->购买->流通，每一个环节都可以控制时间

可以单独或结合盲盒配置成新用户注册的活动奖励

<img width="300" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/1653823109297.gif">

## 合成玩法演示

多种活动形式，后台可以灵活配置，每期活动可配置一种或N种玩法，每种玩法可以消耗不同的藏品，销毁的藏品任何人都不再持有，将在链上销毁。

<img width="300" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/0220607005035.gif">

## 二级演示

<img width="300" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/20220531164931.gif">

## 邀请好友拉新活动演示

<img width="300" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/1653988575719.gif">


# 前端支持功能：

> 深、浅两种皮肤可供配置

- [x] 更多的风格可以自行定制 SCSS

> 用户中心相关

- [x] 用户互关、藏品关注收藏
- [x] 用户分享->邀请->奖励完整逻辑
- [x] 用户藏品（藏馆）分享
- [x] 用户签到->奖励
- [x] 消息推送（全站推送，活动推送，充提买赠动态推送）
- [x] ……

> 支付和安全

- [x] KYC实名
- [x] 绑定银行卡
- [x] 提现申请
- [x] 充值
- [x] 流水记录
- [x] 订单、支付管理
- [x] ……

> 藏品相关

- [x] 赠与管理
- [x] 藏品秒杀购买
1. 最大程度防科学/科技抢购
2. 保证高并发下的用户抢购体验
3. 15分钟内未支付，将重新释放库存，XX分钟后可再捡漏购买
4. 转增、炫耀、分享
5. ……
- [x] 藏品盲盒 
1. 盲盒抽奖 可有1-N个藏品
2. 概率控制 稀有级别UR SSR SR R N
3. 未打开之前也可以转增

- [x] 藏品转赠
1. 用户平台可以自行转增
2. 不同的藏品可以设置转增类型：不可转增、可以转增（有xx天限制）、无限制（购买后即可转增）
3. 用户可以不通过平台，直接去公链上自行操作转增

- [x] 藏品空投（抽签）
概率控制
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/assets/20220519103210_1.gif" width="400" />

- [x] 更多……

完整整站功能，不一一罗列




# 海报生成服务器：运营利器

- [x] 可灵活配置
可以根据不同的需求随意配置
动态实现分享不同的内容，可单独设置每一个藏品的分享内容
背景图，二维码，文案

# 区块链相关：
- [x] 在线创建藏品合约,铸造NFT藏品
- [x] 按项目对购买用户批量发放NFT（铸造）
- [x] 按购买订单批量发放NFT
- [x] 自动发放NFT

另外的服务程序介绍

# 后台支持功能：

> 权限控制

> 用户管理

- [x] 用户信息管理
- [x] 用户钱包管理
- [x] 银行卡管理（记录、审核）
- [x] KYC实名认证（记录、审核）
- [x] 用户关注

> 交易充提
- [x] 充值管理（记录、审核、自动对账）
- [x] 提现管理（记录、审核、自动对账）
- [x] 交易流水（自动对账）
- [x] 安全支付密码设置

> NFT藏品
- [x] NFT藏品管理（藏品上下架）
- [x] 缓存管理
- [x] 盲盒配置管理
- [x] 购买黑白名单（过滤设置、优先购买）
- [x] 藏品创造者
- [x] 用户喜欢的藏品

> 藏品流转
- [x] 藏品订单管理
- [x] 藏品流转记录
- [x] 赠与管理
- [x] 用户拥有藏品

> 用户邀请管理
- [x] 邀请记录
- [x] 邀请奖励

> 签到管理（签到奖励）
> 公告管理（平台公告发布管理）
> 区块链管理
- [x] *链上交易记录
- [x] *添加发布藏品，铸造
> 横幅banner管理
动态配置灵活各banner横幅信息
> 活动弹窗
首页弹窗设置，动态灵活配置弹窗内容和形式

> 其他
- [x] 验证记录
- [x] 用户意见反馈
- [x] 用户操作记录

完整后台功能，不一一罗列

# 关于上链铸造NFT
比较多人问和纠结，现在一个共识，是会选择公链。原因有几个。可以参考。

## 演示

测试账号:
1. username: 13800138000 
2. password: 654321

# 部分展示

## 前端展示 APP，H5，小程序

### APP，H5 浅色
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/assets/20220519103210_1.gif" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/assets/20220519100532.gif" width="400" />

<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(2).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(5).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(9).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(10).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(1).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(3).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(4).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(6).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(7).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/view-demo(8).png" width="400" />

### 深色 演示
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/dark-view-demo(1).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/dark-view-demo(2).png" width="400" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/dark-view-demo(3).png" width="400" />

### 更多的风格可以自行定制

#后台展示
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/assets/220519104940.png" width="900" />
<img style="border:1px solid #ddd;" src="https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/static/023b5bb5c9ea15ce72b87b2218.png" width="900" />
![](https://github.com/Meta-NFT-boy/meta-nft-app/blob/main/assets/220519104940.png)