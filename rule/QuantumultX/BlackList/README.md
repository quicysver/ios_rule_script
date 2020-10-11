# 黑名单

## 前言

本项目的黑名单分流规则由爬虫程序自动维护。

定时爬取互联网上开源的黑名单分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。


最后检查时间：2020-10-11 10:01:30。

## 规则统计

总计规则：778 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 6 |
| DOMAIN-KEYWORD | 12 |
| DOMAIN-SUFFIX | 697 |
| IP-CIDR | 60 |
| USER-AGENT | 3 |
## 重复统计

黑名单分流规则，与本项目其他分流规则重复情况统计。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Advertising)    | 156173   | 24   |   0.02%  |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AdvertisingLite)    | 131289   | 11   |   0.01%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/China)    | 593   | 12   |   2.02%  |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Google)    | 64   | 37   |   57.81%  |
|  [Youtube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Youtube)    | 14   | 3   |   21.43%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Microsoft)    | 31   | 4   |   12.90%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Apple)    | 49   | 3   |   6.12%  |
|  [AppleNews](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AppleNews)    | 9   | 1   |   11.11%  |
|  [AppleBlock](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AppleBlock)    | 6   | 6   |   100.00%  |
|  [Cloudflare](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Cloudflare)    | 15   | 1   |   6.67%  |
|  [Download](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Download)    | 7   | 1   |   14.29%  |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Facebook)    | 25   | 6   |   24.00%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Global)    | 842   | 236   |   28.03%  |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/GlobalMedia)    | 192   | 10   |   5.21%  |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Spotify)    | 8   | 1   |   12.50%  |
|  [TestFlight](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/TestFlight)    | 2   | 1   |   50.00%  |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Twitter)    | 8   | 7   |   87.50%  |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Proxy)    | 773   | 772   |   99.87%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### QuantumultX 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/BlackList/BlackList.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/QuantumultX/BlackList/BlackList.list

## 数据来源

本项目的黑名单分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，请先删除后再使用本项目的黑名单分流规则，以免造成规则重复。

- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/BlackList/BlackList.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/AppleBlock/AppleBlock.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Proxy.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果你有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 最后

### 正则过滤

爬虫程序在清洗原始规则数据时，可根据正则定向过滤规则，以达到保留特定规则的目的。经过正则过滤的规则，无法100%涵盖原始规则数据，请知悉。

### 黑名单

爬虫程序内置部分规则黑名单，在对原始数据进行清洗时，自动将可能引起异常的黑名单规则去除。经过黑名单去除的规则，无法100%涵盖原始规则数据，请知悉。

### 完善规则

如果你：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的黑名单分流规则。
