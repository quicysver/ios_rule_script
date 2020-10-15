# 

## 前言

本项目的分流规则由爬虫程序自动维护。

定时爬取互联网上开源的分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。


最后检查时间：2020-10-15 14:49:09。

## 规则统计

总计规则：773 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 1 |
| DOMAIN-KEYWORD | 12 |
| DOMAIN-SUFFIX | 697 |
| IP-CIDR | 60 |
| USER-AGENT | 3 |
## 重复统计

分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Advertising)    | 156031   | [24](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Advertising.list)   |   0.02%  |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite)    | 131289   | [11](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/AdvertisingLite.list)   |   0.01%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/China)    | 593   | [12](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/China.list)   |   2.02%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/BlackList)    | 778   | [772](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/BlackList.list)   |   99.23%  |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Google)    | 64   | [37](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Google.list)   |   57.81%  |
|  [Youtube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Youtube)    | 14   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Youtube.list)   |   21.43%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Microsoft)    | 31   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Microsoft.list)   |   9.68%  |
|  [Cloudflare](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Cloudflare)    | 15   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Cloudflare.list)   |   6.67%  |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Facebook)    | 25   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Facebook.list)   |   24.00%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Global)    | 842   | [230](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Global.list)   |   27.32%  |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/GlobalMedia)    | 192   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/GlobalMedia.list)   |   5.21%  |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Spotify)    | 8   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Spotify.list)   |   12.50%  |
|  [TestFlight](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/TestFlight)    | 2   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/TestFlight.list)   |   50.00%  |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Twitter)    | 8   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Proxy/Twitter.list)   |   87.50%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Loon 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/Proxy/Proxy.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Loon/Proxy/Proxy.list

## 数据来源

本项目的分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，请先删除后再使用本项目的分流规则，以免造成规则重复。

- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/BlackList/BlackList.list
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

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的分流规则。

感谢

[@zjcfynn](https://github.com/zjcfynn)

提供规则数据及改进建议