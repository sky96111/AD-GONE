# AD-GONE

#### anti-AD是目前中文区命中率最高的广告过滤列表，实现了精确的广告屏蔽和隐私保护。现已支持AdGuardHome，dnsmasq， Surge，Pi-Hole，SmartDNS等网络组件。anti-AD的多种输出格式，完全满足常见的广告屏蔽工具、广告过滤工具的要求，我们始终坚持尽可能的保障每种输出格式的广告过滤效果一致。
#### AD-GONE过滤列表基于anti-AD，将额外提供Clash规则。同时，对于某些既是正常使用到的域名又是广告域名，AD-GONE将予以放行。通过细化规则分类，针对不通人群需求，对日常使用影响降至最低。

## 使用

## TODO

- [ ] 移除anti-AD中对日常有影响的域名
- [x] 初步Clash规则支持
- [ ] 化简的Clash规则支持
- [ ] 规则分类为宽容、严格
- [ ] CI自动生成各规则
- [ ] 标记失效的域名，定期检查，自动删除或回补

## Special Thanks to

- [privacy-protection-tools/anti-AD](https://github.com/privacy-protection-tools/anti-AD) - 主要过滤列表提供
- [notracking/hosts-blocklists-scripts](https://github.com/notracking/hosts-blocklists-scripts) - 提供无效域名和无效hosts列表
- [Adblock Plus](https://adblockplus.org/) - 畅游清爽洁净的网络！
- [neoFelhz/neohosts](https://github.com/neoFelhz/neohosts) - 自由·负责·克制 去广告 Hosts 项目
- [vokins/yhosts](https://github.com/vokins/yhosts) - yhosts
- [cjx82630/cjxlist](https://github.com/cjx82630/cjxlist) - Adblock Plus EasyList Lite与CJX's Annoyance List
- _[@rufengsuixing](https://github.com/rufengsuixing) 提出的jsDelivr加速过滤列表下载的建议_
- _[@xlighting2017](https://github.com/xlighting2017) 提供的[surge格式建议](https://github.com/privacy-protection-tools/anti-AD/issues/29)_
- [ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR) - 一些常见APP的广告 @[wchqybs](https://github.com/wchqybs) in [#79](https://github.com/privacy-protection-tools/anti-AD/issues/79)
- [ADgk.txt](https://github.com/banbendalao/ADgk) - 鸣谢 坂本dalao
- [malwaredomainlist](https://www.malwaredomainlist.com/hostslist/hosts.txt) - 恶意域名屏蔽列表
- [hoshsadiq/adblock-nocoin-list](https://github.com/hoshsadiq/adblock-nocoin-list) - 恶意挖矿屏蔽列表
- [easylist.to](https://easylist.to/) - 感谢提供出色的easylist
- [ZeroDot1/CoinBlockerLists](https://gitlab.com/ZeroDot1/CoinBlockerLists) - 屏蔽恶意劫持挖矿
