# China

## 前言

本项目的China分流规则由爬虫程序自动维护。

定时爬取互联网上开源的China分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。


最后检查时间：2020-10-13 14:32:14。

## 规则统计

总计规则：593 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 16 |
| DOMAIN-KEYWORD | 4 |
| DOMAIN-SUFFIX | 552 |
| IP-CIDR | 7 |
| IP-CIDR6 | 4 |
| USER-AGENT | 10 |
## 重复统计

China分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Advertising)    | 156031   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Advertising.list)   |   0.01%  |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AdvertisingLite)    | 131289   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/AdvertisingLite.list)   |   0.01%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BlackList)    | 778   | [12](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/BlackList.list)   |   1.54%  |
|  [PayPal](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/PayPal)    | 5   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/PayPal.list)   |   80.00%  |
|  [Steam](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Steam)    | 16   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Steam.list)   |   43.75%  |
|  [Blizzard](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Blizzard)    | 6   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Blizzard.list)   |   50.00%  |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Game)    | 28   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Game.list)   |   35.71%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Microsoft)    | 31   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Microsoft.list)   |   19.35%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Apple)    | 49   | [12](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Apple.list)   |   24.49%  |
|  [Speedtest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Speedtest)    | 5   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Speedtest.list)   |   40.00%  |
|  [Bilibili](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Bilibili)    | 13   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Bilibili.list)   |   46.15%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Global)    | 842   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Global.list)   |   0.48%  |
|  [ChinaMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ChinaMedia)    | 75   | [21](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/ChinaMedia.list)   |   28.00%  |
|  [Privacy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Privacy)    | 28   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Privacy.list)   |   3.57%  |
|  [ByteDance](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ByteDance)    | 4   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/ByteDance.list)   |   50.00%  |
|  [Weibo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Weibo)    | 4   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Weibo.list)   |   75.00%  |
|  [AsianMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AsianMedia)    | 28   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/AsianMedia.list)   |   25.00%  |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Proxy)    | 773   | [12](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/China/Proxy.list)   |   1.55%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Surge 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/China/China.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/China/China.list

## 数据来源

本项目的China分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，请先删除后再使用本项目的China分流规则，以免造成规则重复。

- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/China.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Domestic.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/China.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Domestic.list


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

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的China分流规则。

感谢

[@zjcfynn](https://github.com/zjcfynn)

提供规则数据及改进建议