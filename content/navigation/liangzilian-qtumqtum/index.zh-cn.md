﻿---
weight: 
title: "量子链-Qtum(QTUM)"
description: "Qtum Blockchain（简称“量子链”或“Qtum”）致力于开发比特币和以太坊之外的第三种区块链生态系统，通过价值传输协议（“Value Transfer Protocol”）来实现点对点的价值转移，并根据..."
date: 2022-07-20T21:57:40+08:00
lastmod: 2022-07-20T16:45:40+08:00
draft: false
authors: ["seven"]
featuredImage: "liangzilian-qtumqtum.webp"
link: "https://qtum.org/"
tags: ["数字代币","量子链-Qtum(QTUM)"]
categories: ["navigation"]
navigation: ["数字代币"]
lightgallery: true
toc: true
pinned: false
recommend: false
recommend1: false
---
Qtum Blockchain（简称“量子链”或“Qtum”）致力于开发比特币和以太坊之外的第三种区块链生态系统，通过价值传输协议（“Value Transfer Protocol”）来实现点对点的价值转移，并根据此协议，构建一个支持多个行业（包括金融、物联网、供应链、社交、游戏等）的去中心化的应用开发平台（“DApp Platform”）。通过合并改进版本的比特币核心基础架构和可以相互兼容的以太坊虚拟机版本，量子链既拥有比特币坚不可摧的区块链网络又能发挥智能合约的无限可能。QTUM币用于访问Dapp、代币投票、社区自治、应用功能消耗/支付。

账户抽象层（Account Abstraction Layer, AAL）是 Qtum 连接 UTXO 流通层和智能合约平台层的关键，也是量子链实现的一大创新。通过 AAL 可以将 UTXO 模型转换成可供不同虚拟机执行的账户模型，比如以太坊 EVM，或是 x86 虚拟机，并且可以把虚拟机的帐户余额通过 AAL 转换为 UTXO。
这实现了余额和智能合约平台的分层设计，流动性采用比特币的 UTXO，并且原生支持多重签名算法，作为余额的记账、转账更具有安全性；而由于智能合约平台是图灵完备的，很难避免编程出现 bug，把流通层和和智能合约平台分离比以太坊更具优势。为了使区块链的智能合约平台能力得到进一步的扩展，Qtum 计划实现的 x86 高性能虚拟机可以直接通过 C、C++、rust、go 等语言进行智能合约的编程，也可以支持其他可以在 x86 架构上运行的编程语言。x86 架构虚拟机可以解决以太坊EVM中一些问题，比如不支持标准库、生成的字节码过大、不支持浮点、难以调试等。

量子链的主要特点如下：
1.从技术角度分析，Qtum致力于实现首个兼容BIP（基于UTXO模型 ）的POS智能合约平台，兼容比特币交易模式以及以太坊虚拟机优势；
2.量子链通过“去中心应用”和“主控合约”将链下因素引入，形成符合现实世界商业逻辑的区块链主控合约，支持多个行业、多种渠道，最终实现走向移动端策略；
3.加强公有链中和联盟链中共识机制的灵活性，同时考虑行业合规性。