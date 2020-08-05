# AD-GONE

#### anti-AD是目前中文区命中率最高的广告过滤列表，实现了精确的广告屏蔽和隐私保护。现已支持AdGuardHome，dnsmasq， Surge，Pi-Hole，SmartDNS等网络组件。anti-AD的多种输出格式，完全满足常见的广告屏蔽工具、广告过滤工具的要求，我们始终坚持尽可能的保障每种输出格式的广告过滤效果一致。

使用anti-AD能够屏蔽广告域名，能屏蔽电视盒子广告，屏蔽app内置广告，同时屏蔽了一些日志收集、大数据统计等涉及个人隐私信息的站点，能够保护个人隐私不被偷偷上传。

本工具是通过域名解析层来屏蔽广告和保护隐私的，其将各大著名的hosts，ad filter lists，adblock list等的列表进行合并去重，再进行一系列的抽象化，例如主动剔除失效域名、easylist优化模糊匹配、增强的黑白名单机制等措施，最终生成期望的高命中率列表。

## 快速使用(使用官网地址，速度更稳定)

| 文件 	| raw 	| 官网地址 	| 适用于 	|
| --------------------------------	|:------------------:	| ----------------	|---------------------------------------------	|
| `adblock-for-dnsmasq.conf` 	| [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/adblock-for-dnsmasq.conf) 	| [官网地址，更稳定](https://anti-ad.net/anti-ad-for-dnsmasq.conf) 	| dnsmasq及其衍生版本 	|
| `anti-ad-easylist.txt` 	| [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-easylist.txt) 	| [官网地址，更稳定](https://anti-ad.net/easylist.txt)	| AdGuardHome 	|
| `anti-ad-domains.txt` 	| [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-domains.txt) 	| [官网地址，更稳定](https://anti-ad.net/domains.txt)	| Pi-Hole或其他。 	|
| `anti-ad-surge.txt` 	| [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-surge.txt) 	| [官网地址，更稳定](https://anti-ad.net/surge.txt)	| Surge或其他工具。 	|
| `anti-ad-smartdns.conf` 	| [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-smartdns.conf) 	| [官网地址，更稳定](https://anti-ad.net/anti-ad-for-smartdns.conf) | SmartDNS 	|



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
