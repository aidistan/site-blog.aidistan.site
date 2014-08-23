---
layout: post
title: 智能家居无线技术调研
modified: 2014-07-03 09:30:34 +0800
tags: [调研, 智能家居]
image:
  feature: 2014/0601.jpg
  credit: 
  creditlink:
comments: post-20140630-0
share: true
link: 
---

调研智能家居无线技术的现状，为项目选择合适的实现方案，便是我来创能做的第一件事。

当前智能家居的无线技术大致有以下四种方案：

## 1. ZigBee

ZigBee是基于IEEE802.15.4标准的低功耗局域网协议，专用于智能家居领域，频段与WIFI有所重叠。其与WIFI的性能比较，网上是众说纷纭，但从产品层面上来说，历史最久、性能最佳的产品大都是此类。比如鼎鼎大名、大名鼎鼎的[Control4](http://www.control4.com/)，以及最近低调进入智能家居领域的联想。

而另一方面如果直接在百度上搜索ZigBee，则往往会被推广一些神奇的公司。他们重新包装了Control4的产品，腰身一变成了国内专业的智能家居解决方案提供商。这些商家极力地吹嘘他们的产品，目的不是为了找到客户，而是找经销商...

## 2. HomeKit

HomeKit是苹果在今年WWDC大会上推出的智能家居框架，目前还不确定前景如何，但值得看好。但是如需开发符合HomeKit硬件则要加入苹果的MFi项目，其中的排他协议在面对安卓占据半壁江山的市场时限制较大。

## 3. WiFi

虽然WiFi已经走进千家万户，但是基于WIFI的产品并不是很多，其中在国内比较知名的产品要数这款起源自[点名时间](http://www.demohour.com/projects/337763/)的[坎坤智能插座(小K)](http://www.kankunit.com/)了。来自TI的[新闻](http://www.eechina.com/thread-130168-1-1.html)则更加振奋人心一些，来自电子器件生产厂家的表态对应用级的开发者们真是莫大的激励。

## 4. GMS

基于移动服务的物联网模式，每个终端都需要插入SIM卡，通过短信或者电话(拨通即挂断)的方式来进行通讯。在网络条件较差的地方，此类产品有奇效，因而有不少工业级的应用，而且听朋友说此类产品利润不菲；但就商业级应用而言，随着越来越多人对终端App模式的熟悉，GMS前景有限。

## 结语

WiFi的速率可以满足高清视频、音频传输的需求，软硬件实现合理的产品在单兵性能上远胜于ZigBee，但后者在支持终端数量和组网模式上有天生的优势。因此，也许正如EEChina所说：

> 作为智能家居企业，应当抛开技术孰优孰劣的成见，根据具体情况考虑适合的技术。企业应把重心放在如何给用户提供更好的应用，更流畅的用户体验，更可靠的安全保障。当智能家居逐渐普及到千家万户时，智能家居的无线技术标准自然会浮出水面。<small>[《比较智能家居无线技术：Zigbee/蓝牙/Wi-Fi》](http://www.eechina.com/thread-130439-1-1.html)</small>