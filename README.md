# 适配说明

本仓库修改自[@Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)，适用于[SmartDNS](https://github.com/pymumu/smartdns)，移除了SmartDNS不支持的regexp与keyword规则。

使用 GitHub Actions 北京时间每天早上 6 点自动构建，保证规则最新。

## 规则文件下载地址

> 如果无法访问域名 `raw.githubusercontent.com`，可以使用第二个地址 `fastly.jsdelivr.net`。
>
> *.sha256sum 为校验文件。

  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/geosite.dat](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/geosite.dat)
- **直连域名列表 direct-list.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/direct-list.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/direct-list.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/direct-list.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/direct-list.txt)
- **代理域名列表 proxy-list.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/proxy-list.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/proxy-list.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/proxy-list.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/proxy-list.txt)
- **广告域名列表 reject-list.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/reject-list.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/reject-list.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/reject-list.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/reject-list.txt)
- **@felixonmars/dnsmasq-china-list 仓库收集的在中国大陆可直连的域名列表 china-list.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/china-list.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/china-list.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/china-list.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/china-list.txt)
- **Apple 在中国大陆可直连的域名列表 apple-cn.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/apple-cn.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/apple-cn.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/apple-cn.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/apple-cn.txt)
- **Google 在中国大陆可直连的域名列表 google-cn.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/google-cn.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/google-cn.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/google-cn.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/google-cn.txt)
- **GFWList 域名列表 gfw.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/gfw.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/gfw.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/gfw.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/gfw.txt)
- **Windows 操作系统使用的隐私跟踪域名列表 win-spy.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/win-spy.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/win-spy.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/win-spy.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/win-spy.txt)
- **Windows 操作系统使用的系统升级域名列表 win-update.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/win-update.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/win-update.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/win-update.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/win-update.txt)
- **Windows 操作系统使用的附加隐私跟踪域名列表 win-extra.txt**：
  - [https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/win-extra.txt](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat-smartdns/release/win-extra.txt)
  - [https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/win-extra.txt](https://fastly.jsdelivr.net/gh/jianxinzhang/v2ray-rules-dat-smartdns@release/win-extra.txt)
