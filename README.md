# Awesome Nebulas

> 星云链 DApp 开发文档、资料、工具、教程大全
>
> A collection of Nebulas blockchain DApp development tools and docs

***

| 目录 |
|---
| [新手入门指南](#guide)
| [常见问题（FAQ）](#faq)
| [官方教程](#official-tutorial)
| [必备工具](#tool)
| [星云激励计划](#incentive)
| [库](#lib)
| [星云币（NAS）](#nas)
| [DApp](#dapp)
| [社区](#community)
| [其它](#misc)

***


## 新手入门指南 <a name="guide">&nbsp;</a>

#### 使用 DApp <a name="guide--user">&nbsp;</a>

1. [创建自己的星云钱包地址](https://blog.nebulas.io/2018/04/12/creating-a-nas-wallet/)
1. 在星云官网 [注册一个账号](https://incentive.nebulas.io/cn/signup.html?invite=76rVp)
	1. 在星云官网 [验证邮箱](https://incentive.nebulas.io/cn/setting_active.html)
	1. 在星云官网 [填入你的钱包地址](https://https://incentive.nebulas.io/cn/setting.html)
	1. 半小时内你的钱包就会收到官方赠送的 0.0001 NAS（星云币）
1. 有钱了，就可以开始体验 DApp 了
	* 在 [DApp 商店](#dapp--store) 浏览选用你感兴趣的 DApp
	* 体验 [推荐的 DApp](#dapp--commended)

#### 转账

* 使用 [星云 Web 钱包](https://github.com/nebulasio/web-wallet)
	* [发起转账](https://blog.nebulas.io/2018/04/17/sending-nas-from-your-wallet/) - 适用于初级用户
	* [离线签名交易](https://blog.nebulas.io/2018/04/18/signing-a-transaction-offline/) - 适用于高级用户
	* [查看钱包信息](https://blog.nebulas.io/2018/04/19/view-wallet-information/) - 查看自己（或别人）还有多少钱
	* [查看交易状态](https://blog.nebulas.io/2018/04/28/check-tx-status/) - 查看转账是否已成功
* 使用 [星云钱包 Chrome 扩展](https://github.com/nebulasio/WebExtensionWallet) 
* 使用 [星云手机钱包 APP](https://nano.nebulas.io/)

#### 开发 DApp <a name="guide--developer">&nbsp;</a>

* 在星云官网 [注册一个账号](https://incentive.nebulas.io/cn/signup.html?invite=76rVp)
* 阅读 [官方教程](#official-tutorial) 和 [网友经验分享](#community-tutorial)
* 学习 [库](#lib)
* 加入 [微信群](#wechat-group) 交流经验

## 常见问题（FAQ） <a name="faq">&nbsp;</a>

> 💡 **友情提示**：善用搜索。

#### 星云链 <a name="faq--nebulas">&nbsp;</a>

* [TPS 是什么意思？](https://github.com/cssmagic/Awesome-Nebulas/issues/3)
* [什么是 gas/油费/矿工费/手续费？](https://github.com/cssmagic/Awesome-Nebulas/issues/4)
* ……

#### 智能合约 <a name="faq--smart-contract">&nbsp;</a>

* [智能合约部署上线之后还可以修改吗？我的 DApp 升级怎么办？](https://github.com/cssmagic/Awesome-Nebulas/issues/5)
* [如何查看别人的合约代码？](https://github.com/cssmagic/Awesome-Nebulas/issues/6)
* ……

####  DApp 开发 <a name="faq--dapp-dev">&nbsp;</a>

* [用 nebPay.queryPayInfo() 查询交易结果，总是得到 "payId *** does not exist" 是怎么回事？](https://github.com/cssmagic/Awesome-Nebulas/issues/1)
* ……

#### 星云激励计划 <a name="faq--incentive">&nbsp;</a>

* [“合约哈希” 是什么意思？在哪里能找到？](https://github.com/cssmagic/Awesome-Nebulas/issues/7)
* ……

> 👉 没有找到你想问的问题？点这里 [提交新问题](https://github.com/cssmagic/Awesome-Nebulas/issues/new)。

***

## 官方教程 <a name="official-tutorial">&nbsp;</a>

* [[英文] Nebulearn](http://nebulearn.com/) - 官方开发教程总站，比较全，建议英文好的开发者仔细研读
* [[英文/中文] 官方教程](https://github.com/nebulasio/wiki/blob/master/tutorials.md) - 星云链官方教程汇总，建议入门后阅读
* [[英文] 官方 Wiki](https://github.com/nebulasio/wiki/blob/master/tutorials.md) - 星云链官方资料汇总，建议入门后阅读

#### 智能合约 <a name="official-tutorial--smart-contract">&nbsp;</a>

* [[中文] 智能合约概述](https://github.com/nebulasio/wiki/blob/master/smart_contract_ch.md) - 简介智能合约的执行模型、编写范式、内置对象等
* [[中文] 编写并运行智能合约](https://github.com/nebulasio/wiki/blob/master/tutorials/%5B%E4%B8%AD%E6%96%87%5D%20Nebulas%20101%20-%2003%20%E7%BC%96%E5%86%99%E6%99%BA%E8%83%BD%E5%90%88%E7%BA%A6.md)
* [[中文] 智能合约存储区](https://github.com/nebulasio/wiki/blob/master/tutorials/%5B%E4%B8%AD%E6%96%87%5D%20Nebulas%20101%20-%2004%20%E6%99%BA%E8%83%BD%E5%90%88%E7%BA%A6%E5%AD%98%E5%82%A8%E5%8C%BA.md)
* [[中文] 部署智能合约](https://blog.nebulas.io/2018/04/28/deploy-a-smart-contract/)

#### DApp 开发 <a name="official-tutorial--dapp-dev">&nbsp;</a>

* [[英文] FAQ](https://github.com/nebulasio/wiki/blob/master/FAQ_nebulas_development_en.md) | [中文](https://github.com/nebulasio/wiki/blob/master/FAQ_nebulas_development_ch.md)
* [手把手教你星云DApp开发（一）](https://blog.nebulas.io/2018/05/04/how-to-build-a-dapp-on-nebulas-part-1/)
* [手把手教你星云DApp开发（二）](https://blog.nebulas.io/2018/05/05/how-to-build-a-dapp-on-nebulas-part-2/)
* 官方 Demo（super-dictionary）：
 	* [GitHub repo](https://github.com/15010159959/super-dictionary)
	* [解读](https://blog.nebulas.io/2018/04/28/nebulas-incentive-program%e2%80%8a-%e2%80%8a-demo/)

## 必备工具 <a name="tool">&nbsp;</a>

* [星云浏览器](https://explorer.nebulas.io/) - 查询交易、地址、合约等详细信息
* [星云 Web 钱包](https://github.com/nebulasio/web-wallet) - 创建自己的钱包、向他人转账、部署合约等
* [星云钱包 Chrome 扩展](https://github.com/nebulasio/WebExtensionWallet) - 把钱包功能集成到 Chrome 浏览器，便于使用 DApp
* [星云手机钱包 APP](https://nano.nebulas.io/) - 在手机上使用星云钱包，便于使用 DApp

## 星云激励计划 <a name="incentive">&nbsp;</a>

#### 常用链接 <a name="incentive--link">&nbsp;</a>

* [注册星云开发者账号](https://incentive.nebulas.io/cn/signup.html?invite=76rVp) - 这是本项目作者的邀请链接，可获额外奖金
* [提交 DApp](https://incentive.nebulas.io/cn/submit-dapp.html) - 提交自己的作品参赛
* [我的 DAPP](https://incentive.nebulas.io/cn/mydapp.html) - 已提交的作品，以及审核情况

#### 官方文档与公告 <a name="incentive--official-doc">&nbsp;</a>

* [审核规则指南](https://mp.weixin.qq.com/s?__biz=MzU2MTI5OTI3MA==&mid=2247484761&idx=3&sn=357580897604e90cef6bb68e1e6b8fc3) 
* [安全公告](https://mp.weixin.qq.com/s/bWmh5BRRx1qjUp-wJrXSTw)
* [常见问题](https://blog.nebulas.io/2018/05/03/nebulas-incentive-program-qa/)
* [加分指南](https://mp.weixin.qq.com/s/mspyU2DRENyonDA67VF40A) - 参见文章尾部
* [DApp 升级指南](https://mp.weixin.qq.com/s/MdVZ-iVc5ZNChp1RzDpzsw) - 如何重新申请审核
* [星云 DApp 设计规范](https://nebulas.io/docs/DAppDesignGuidelinesZh.pdf) - PDF 下载
* [每周入围应用](https://incentive.nebulas.io/cn/dapps-board.html)

#### 社区资源 <a name="incentive--community">&nbsp;</a>

* [领奖事宜](http://nasfans.io/forum.php?mod=viewthread&tid=230&extra=page%3D1) - 可能是官方公告
* [分析星云评奖结果](http://www.nasforce.io/index.php?c=read&id=110&page=1)

## 库 <a name="lib">&nbsp;</a>

* **nebPay** - 支付 SDK <a name="nebPay">&nbsp;</a>
    * [GitHub repo](https://github.com/nebulasio/nebPay)
    * [文档](https://github.com/nebulasio/nebPay/blob/master/doc/NebPay%E4%BB%8B%E7%BB%8D.md)
    * [教程：如何在Dapp中使用nebPay](https://blog.nebulas.io/2018/05/09/how-to-use-nebpay-in-your-dapp/)
* **neb.js** - JS SDK <a name="neb.js">&nbsp;</a>
	* [GitHub repo](https://github.com/nebulasio/neb.js)
	* [文档](https://nebulasio.github.io/neb.js/index.html)
* **BigNumber** - 合约和 SDK 内置库 <a name="BigNumber">&nbsp;</a>
	* [使用方法](https://github.com/MikeMcl/bignumber.js#use)
	* [文档](http://mikemcl.github.io/bignumber.js/)

## 星云币（NAS） <a name="nas">&nbsp;</a>

#### 测试网 <a name="nas--testnet">&nbsp;</a>

* [官方] 测试网每日申请 ~~10 NAS~~ 1 NAS： https://testnet.nebulas.io/claim/

#### 主网 <a name="nas--mainnet">&nbsp;</a>

* 在 [“CSS魔法” 微信公众号](https://cloud.githubusercontent.com/assets/1231359/13040994/04966808-d3ee-11e5-8eb5-7e3bf8767f4e.png) 内发送钱包地址，可获赠少量 NAS。
* [非官方] 付 gas 领 0.001 NAS： https://nas.biyouduo.com/
* [非官方] 付 gas 领 0.0002 NAS： http://givemenas.com/home.html
* [非官方] 付 gas 领 0.0005 NAS，每天可领 20 次： http://nasgo.top/

## DApp <a name="dapp">&nbsp;</a>

#### DApp 商店 <a name="dapp--store">&nbsp;</a>

* [官方 DApp 商场](https://incentive.nebulas.io/cn/dappstore.html)
* 第三方 DApp 商店
	* [Nebulas Cool：星云 DApp 商店](http://nebulas.cool/)
	* [DApp Review：星云 DApp 商店](https://dapp.review/explore/nas)
	* ……

#### DApp 推荐 <a name="dapp--commended">&nbsp;</a>

* [我是预言帝](http://dapp.applinzi.com/predictor/) - 这是本项目作者的小作品，欢迎体验
* ……

## 社区 <a name="community">&nbsp;</a>

#### 微信群 <a name="wechat-group">&nbsp;</a>

![qr-20180617](https://user-images.githubusercontent.com/1231359/41432298-1b00d1f2-7048-11e8-9980-18ae3e3d6640.png)

* **群规**：畅聊 DApp 技术；禁止闲聊，禁发与主题无关的动图、视频和外链，违者踢。

* 如果上面的二维码已过期，请在 [“CSS魔法” 微信公众号](https://cloud.githubusercontent.com/assets/1231359/13040994/04966808-d3ee-11e5-8eb5-7e3bf8767f4e.png) 内发送 “入群” 两个字，即可收到最新的群二维码。

#### 网友经验分享 <a name="community-tutorial">&nbsp;</a>

* 基于 web-wallet 开发 DApp 小白教程： https://www.jianshu.com/p/6a296bceb816
* 本地环境的智能合约编写： https://www.jianshu.com/p/62f2e8dc6d39
* 凯凯刘 DApp 开发全流程： https://mp.weixin.qq.com/s?__biz=MzI3NzExODg4OA==&mid=2650822384&idx=1&sn=e985d2b5bbdb88638e21959568dbdb0a&scene=21
* 凯凯刘实例讲解： https://mp.weixin.qq.com/s/_cJ1W9fFMAHR7KjwKwg1Gg
* Duke 的 DApp 开发教程： https://juejin.im/post/5b02301d51882542682e80a1
* Nebulas 星云链 DApp 开发全教程： https://zhuanlan.zhihu.com/p/36709518
* DApp 踩坑路： https://weyos.github.io/#/detail?id=1

## 其它 <a name="misc">&nbsp;</a>

#### 区块链入门 <a name="blockchain">&nbsp;</a>

> **请注意**：文中的某些细节可能和星云链不一致。

* [链表，哈希，挖矿等](https://mp.weixin.qq.com/s/wOAqfUrevdlIkdl1qWLHOA)
* [智能合约，代币（Token）等](https://mp.weixin.qq.com/s/-QgTqexfw9KAjuNMiztJ9g)
* [钱包，私钥，地址等](https://mp.weixin.qq.com/s/jOQo7SDV5eBhaCpTW039TA)
