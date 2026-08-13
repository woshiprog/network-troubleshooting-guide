# 网络故障排查指南

面向普通用户的独立网络诊断站点，采用“现象 → 范围 → 测试 → 解释 → 下一步”的方式，覆盖 Wi-Fi、网页、DNS、速度、延迟、抖动、丢包、单设备和路由器故障。

站点地址：<https://woshiprog.github.io/network-troubleshooting-guide/>

## 内容入口

- [开始排查](https://woshiprog.github.io/network-troubleshooting-guide/)
- [网络质量怎么看](https://woshiprog.github.io/network-troubleshooting-guide/network-quality/)
- [Wi-Fi 已连接但无法上网](https://woshiprog.github.io/network-troubleshooting-guide/wifi-connected-no-internet/)
- [网页打不开](https://woshiprog.github.io/network-troubleshooting-guide/website-not-opening/)
- [DNS 异常判断](https://woshiprog.github.io/network-troubleshooting-guide/dns-troubleshooting/)
- [网络丢包测试](https://woshiprog.github.io/network-troubleshooting-guide/packet-loss-test/)
- [网络延迟和抖动测试](https://woshiprog.github.io/network-troubleshooting-guide/network-latency-test/)
- [网速突然变慢](https://woshiprog.github.io/network-troubleshooting-guide/internet-slow-troubleshooting/)
- [只有一台设备无法上网](https://woshiprog.github.io/network-troubleshooting-guide/one-device-no-internet/)
- [路由器网络异常](https://woshiprog.github.io/network-troubleshooting-guide/router-network-troubleshooting/)

## 本地结构

```text
network-troubleshooting-guide/
├── _config.yml
├── _layouts/default.html
├── assets/css/style.css
├── index.md
├── about.md
├── network-quality.md
├── *-troubleshooting.md / *-test.md
├── robots.txt
├── sitemap.xml
└── 404.html
```

## GitHub Pages

仓库使用 Jekyll，可在 GitHub 仓库的 **Settings → Pages** 中选择从默认分支根目录发布。发布成功后，检查首页、文章、`robots.txt` 和 `sitemap.xml` 是否能通过上方站点地址访问。

本站内容用于一般故障诊断。涉及单位网络、设备硬件、光纤线路或无法恢复的配置时，应联系管理员、运营商或设备售后。

