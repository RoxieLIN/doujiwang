﻿---
weight: 
title: "域名币-Namecoin(NMC)"
description: "域名币（Namecoin，NMC）是一种实验性的开源技术，提供传统DNS（域名管理系统）服务商类似的功能，具有安全、不被审查、隐私和快速的特性。Namecoin是比特币的首个分支币，也是最具创新性的“山寨币”之一。首次实现了合并挖掘和去中心化DNS功能。"
date: 2022-07-13T21:57:40+08:00
lastmod: 2022-07-13T16:45:40+08:00
draft: false
authors: ["yangsi"]
featuredImage: "yumingbi-namecoinnmc.webp"
link: "https://www.namecoin.org/"
tags: ["数字代币","域名币-Namecoin(NMC)"]
categories: ["navigation"]
navigation: ["数字代币"]
lightgallery: true
toc: true
pinned: false
recommend: false
recommend1: false
---
域名币（Namecoin，NMC）是一种实验性的开源技术，提供传统DNS（域名管理系统）服务商类似的功能，具有安全、不被审查、隐私和快速的特性。Namecoin是比特币的首个分支币，也是最具创新性的“山寨币”之一。首次实现了合并挖掘和去中心化DNS功能。

**项目应用**

Namecoin是比特币的第一个分支，仍然是最具创新性的“ altcoins”之一。它首先实现了合并挖掘和分散DNS。 Namecoin还是Zooko的Triangle的第一个解决方案，Zooko的Triangle是一个长期存在的问题，即生产一种同时安全，分散和具有人类意义的命名系统。具体应用有：

- 通过使网络更不受审查，来在线保护自由言论权利。
  将身份信息（例如GPG和OTR密钥以及电子邮件，比特币和Bitmessage地址）附加到您选择的身份。

- 具有人类意义的Tor .onion域。
  分散式TLS（HTTPS）证书验证，并得到区块链共识的支持。

- 使用.bit顶级域访问网站。
  提议的想法，例如文件签名，投票，债券/股票/股票，信任网，公证服务和存在证明。

**Namecoin与比特币的关系**

Namecoin代码库由比特币代码库组成，其变化相对较小（约400行），并在其之上构建了其他功能。挖掘过程是相同的，但区块链是分开的，因此创建了Namecoin。之所以采用这种方法，是因为比特币开发者希望几乎全部专注于使比特币成为一种可行的货币，而名币开发者则对建立命名系统感兴趣。由于两个项目之间的预期用例不同，因此共识和协议规则可能在一个方面有意义，而在另一个方面则没有意义。

具有不同协议或共识规则的地方示例：

Namecoin的共识规则需要强制名称的唯一性。尽管可以将数据存储在比特币中（例如，OP_RETURN输出中的键/值对），但比特币并不强制唯一性。从理论上讲，有可能在比特币之上构建一个层，以丢弃OP_RETURN不尊重唯一性的输出（例如，窃取他人名字的名称操作），但矿工不会强制执行任何此类层。如果矿工未强制执行交易有效性规则，则PoW不会为其提供支持，这意味着基于SPV的轻量级客户端将无法实施这些有效性规则。

由于消费者期望金融交易与名称注册的费用不同，并且由于全球金融交易与全球名称注册的数量不同，因此Namecoin和比特币的最佳区块大小可能不同。

在货币中，通货膨胀攻击是致命的，而在命名系统中，通货膨胀攻击只是垃圾邮件或蹲便式攻击：很糟糕，但几乎没有致命危险。因此，Namecoin和比特币之间关于基于zk-SNARK的匿名性（会带来通货膨胀攻击的风险）之类的功能的决策可能得出不同的结论。

一些对Namecoin有意义的脚本功能可能对比特币没有意义，例如，允许scriptPubKey限制任何支出交易的scriptPubKeys。在命名系统中，类似这样的功能可以使更新和更新名称更加方便和安全，但是以货币为单位，它们可能会损害可替代性。

可以通过Namecoin共识规则来强制执行Coinbase对名称数据库的承诺，从而可以创建名称不存在的SPV证明。

通常，Namecoin开发人员会尝试最小化针对比特币的补丁集。如果某个功能可以在比特币中使用，我们尝试将其添加到比特币中，然后将其合并到Namecoin中。Namecoin通常仅在由于使用案例不同而对比特币没有意义的情况下才引入与比特币的区别。尽管从理论上讲可以将Namecoin用作通用货币，但Namecoin开发人员并不鼓励使用此用例。那里有很多专门用于这种用途的加密货币项目（例如比特币）。如果您正在寻找货币，则应使用其中一个项目。