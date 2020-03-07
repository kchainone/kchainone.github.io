---
layout: post
title:  "图解：区块链应用堆栈（Blockchain Application Stack）"
author: jane
categories: [ primer ]
image: assets/postimages/books-3322275_1280.jpg
---

网络、链、中间件、用户

区块链带来的底层技术的变革，它正在重构一整套的技术堆栈。这里，综合行业的研究，我们梳理提出一个“区块链应用堆栈”（Blockchain Application Stack）。

之前对于区块链技术应用的分层有多个：

- 简单的有“胖协议”所说的，仅分为协议与应用两层。在2020年他们又提出了“瘦应用”的新理念。

- 复杂的有MultiCoin基金提出的“Web3 Stack”的多层次分类，Web3 Stack有2018、2019两个版本。

- 企业以太坊基金会也有一个企业以太坊架构堆栈（The Enterprise Ethereum Architecture Stack，[EEAS](https://entethalliance.org/wp-content/uploads/2019/10/arc-stack-pdf.pdf)）。

- 更早前还有Vitalik Buterin 早在2014年12月提出的“[Silos](https://blog.ethereum.org/2014/12/31/silos/)”。

## 区块链应用堆栈（Blockchain Application Stack）

![Untitled.002.png](/assets/postimages/F325B69BF0366A18E9F9386E7259B467.png)

我们认为，区块链整个技术堆栈可以分成四层，每层又可细分成三组。自上而下各层分别是：

- 网络与基础设施（Infrastructure Stack）
- 链层（Blockchain Stack）
- 中间件（Middleware Stack）
- 用户层（Client Stack）

各层又可进一步细分：

网络与基础设施包括：

- 点对点网路
- 编程语言与虚拟机
- 共识算法与密码学研究

链层包括：

- 公链
- 联盟链
- BaaS（区块链云服务）

中间件包括：

- 链上协议(On-chain protocols)
- 链下服务(Off-chain Services)
- 跨链服务(Interoperability Services)

用户层包括：

- DAPP去中心化应用
- 产业区块链（Industry blockchain）
- 开放金融（Open Finance）

## 用区块链应用堆栈看排名前50的项目

用区块链技术堆栈开CoinMarketCap排名前100的项目，汇总成下图：

![Untitled.004.png](/assets/postimages/D80887D43E657D6FAA2D39B48E9B51B8.png)

我们可以看到：

- 排名前50的项目集中在公链与开放金融两个部分，DAPP和跨链服务仅有少量。

- 公链的部分可细分为两类：1）单纯的加密数字货币，2）类以太坊的去中心化应用平台。

- 开放金融的部分中，2019-2020中特别现象是涌现了众多的交易平台通证。

## 用区块链应用堆栈看排名前100的项目

用区块链技术堆栈开CoinMarketCap排名前100的项目，汇总成下图（仅包括51-100的项目）。它所展现的格局与前50有很大的差别。

![Untitled.006.png](/assets/postimages/14555782ECBEBE30E08441D4D5093FBB.png)

我们可以看到：

- 排名51-100的项目中，公链中的应用平台、DAPP去中心化应用较多。
- 开放金融类别也有不少项目。其他版块依然较少。

## 用区块链应用分析热门产业应用

如果将其他一些无CoinMarketCap市值的项目纳入，我们则得到下图：

![Untitled.005.png](/assets/postimages/B048E2FA96716F69880B6D06AB8750EC.png)

我们看到重点新增的板块：

- 用户工具类，包括MetaMask、CoinDesk、Etherscan等工具；
- 产业区块链类，包括Consensys、IBM Blockchain、万向、趣链等；
- BaaS区块链即服务，包括Micrsoft Azure、Amazon AWS、蚂蚁区块链、Google Clouds等；

在设计区块链应用堆栈时，我们未将矿机、矿场、矿池纳入，但它们也是产业的极其重要的的成员，在这张图中标识出了比特大陆、嘉楠耘智两大矿机公司。

## 从市值看区块链产业情况

观察区块链产业的一个指标是加密数字货币的市值占比，根据2020年2月10日的数据，我们可以看到：

比特币占比仍处于历史较高点，达到63.62%。

以太坊占比为8.65%。

从市值、技术社区活跃度以及开发工具的普及度，我们认为以太坊及Solidity语言将会是主要的智能合约开发平台。

较为值得关注的是：

- 亚马逊云即将推出以太坊托管联盟链；
- JP摩根推出的企业以太坊联盟链Quorum；
- 蚂蚁区块链、FIBOS(微众银行)等均支持Solidity开发智能合约。


