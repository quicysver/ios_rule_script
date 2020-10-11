# DomesticMedia

## 前言

本项目的DomesticMedia分流规则由爬虫程序自动维护。

定时爬取互联网上开源的DomesticMedia分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。


最后检查时间：2020-10-11 11:06:40。

## 规则统计

总计规则：77 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 4 |
| DOMAIN-KEYWORD | 2 |
| DOMAIN-SUFFIX | 44 |
| IP-CIDR | 4 |
| USER-AGENT | 23 |
## 重复统计

DomesticMedia分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Advertising)    | 156173   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/DomesticMedia/Repeat/Advertising.list)   |   0.00%  |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AdvertisingLite)    | 131289   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/DomesticMedia/Repeat/AdvertisingLite.list)   |   0.00%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/China)    | 593   | [21](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/DomesticMedia/Repeat/China.list)   |   3.54%  |
|  [Bilibili](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/Bilibili)    | 13   | [13](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/DomesticMedia/Repeat/Bilibili.list)   |   100.00%  |
|  [NetEaseMusic](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/NetEaseMusic)    | 41   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/DomesticMedia/Repeat/NetEaseMusic.list)   |   4.88%  |
|  [AsianMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/AsianMedia)    | 28   | [28](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/DomesticMedia/Repeat/AsianMedia.list)   |   100.00%  |
|  [ChinaIPs](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/ChinaIPs)    | 6607   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/DomesticMedia/Repeat/ChinaIPs.list)   |   0.03%  |
|  [iQiyi](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/iQiyi)    | 7   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/DomesticMedia/Repeat/iQiyi.list)   |   100.00%  |
|  [TencentVideo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/TencentVideo)    | 2   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX/DomesticMedia/Repeat/TencentVideo.list)   |   50.00%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### QuantumultX 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/DomesticMedia/DomesticMedia.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/QuantumultX/DomesticMedia/DomesticMedia.list

## 数据来源

本项目的DomesticMedia分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，请先删除后再使用本项目的DomesticMedia分流规则，以免造成规则重复。

- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/DomesticMedia.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/AsianMedia.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/ChinaMedia.list


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

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的DomesticMedia分流规则。
