# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 20:59:09 |
| 运行耗时 | 539.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99458 |
| 去重后节点 | 27317 |
| TCP 可达 | 3000 |
| 真实可用 | 437 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27317 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 0.8 |
| tcp | 47.7 |
| probe | 239.8 |
| real_test | 168.4 |
| generate | 78.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60561 |
| vmess | 15732 |
| shadowsocks | 11337 |
| trojan | 9467 |
| hysteria2 | 1552 |
| http | 521 |
| shadowsocksr | 173 |
| socks | 68 |
| anytls | 24 |
| hysteria | 17 |
| tuic | 6 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 78.26 | shadowsocks | 249.0 | 627.6 | 22.01 | 0.0 | 10.0 | 12.89 | 17.36 | mheidari-all | 156.146.38.168 |
| 78.2 | hysteria2 | 332.0 | 584.2 | 20.09 | 0.0 | 10.0 | 14.12 | 18.68 | Au1rxx-base64 | 66.94.121.46 |
| 78.14 | shadowsocks | 254.3 | 646.5 | 21.89 | 0.0 | 10.0 | 12.89 | 17.36 | mheidari-all | 156.146.38.170 |
| 78.08 | vless | 330.3 | 746.4 | 20.13 | 0.0 | 10.0 | 11.88 | 18.68 | Au1rxx-base64 | 66.70.179.198 |
| 78.06 | vless | 309.3 | 780.1 | 20.62 | 0.0 | 10.0 | 11.88 | 17.36 | mheidari-all | 216.227.161.95 |
| 77.92 | vless | 337.4 | 676.0 | 19.97 | 0.0 | 10.0 | 11.88 | 18.68 | Au1rxx-base64 | 169.40.42.90 |
| 77.8 | shadowsocks | 298.2 | 731.8 | 20.87 | 0.0 | 10.0 | 12.89 | 18.68 | Au1rxx-base64 | 37.19.198.244 |
| 77.77 | vless | 316.2 | 720.7 | 20.46 | 0.0 | 10.0 | 11.88 | 18.68 | Au1rxx-base64 | 159.89.87.21 |
| 77.34 | vless | 327.1 | 728.3 | 20.21 | 0.0 | 10.0 | 11.88 | 18.68 | Au1rxx-base64 | 137.184.218.169 |
| 77.25 | vless | 298.9 | 600.8 | 20.86 | 0.0 | 10.0 | 11.88 | 18.68 | Au1rxx-base64 | 172.233.139.46 |
| 77.19 | shadowsocks | 307.8 | 760.9 | 20.65 | 0.0 | 10.0 | 12.89 | 18.68 | Au1rxx-base64 | 37.19.198.243 |
| 77.19 | hysteria2 | 345.1 | 793.7 | 19.79 | 0.0 | 10.0 | 14.12 | 17.36 | mheidari-all | 159.223.157.129 |
| 77.16 | vless | 306.6 | 590.5 | 20.68 | 0.0 | 10.0 | 11.88 | 18.68 | Au1rxx-base64 | 195.123.240.65 |
| 77.11 | vless | 293.7 | 605.9 | 20.98 | 0.0 | 10.0 | 11.88 | 18.68 | Au1rxx-base64 | 172.235.38.85 |
| 76.91 | vless | 301.5 | 617.9 | 20.8 | 0.0 | 10.0 | 11.88 | 18.68 | Au1rxx-base64 | 172.235.43.210 |
| 76.89 | vless | 270.5 | 548.3 | 21.52 | 0.0 | 10.0 | 11.88 | 17.36 | mheidari-all | 47.251.108.158 |
| 76.67 | shadowsocks | 242.6 | 601.4 | 22.16 | 0.0 | 10.0 | 12.89 | 15.62 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.47 | shadowsocks | 251.2 | 629.5 | 21.96 | 0.0 | 10.0 | 12.89 | 15.62 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.83 | vless | 413.8 | 1027.3 | 18.2 | 0.0 | 10.0 | 11.88 | 18.68 | Au1rxx-base64 | 185.95.231.233 |
| 75.64 | shadowsocks | 296.8 | 730.8 | 20.91 | 0.0 | 10.0 | 12.89 | 18.68 | Au1rxx-base64 | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | 0.901 | 323 | 1802 | prefer |
| Surfboard-tg-mixed | 0.928 | 0.864 | 44 | 7340 | prefer |
| ermaozi | 0.878 | 0.88 | 25 | 656 | prefer |
| mheidari-all | 0.832 | 0.757 | 111 | 23599 | prefer |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 5207 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5192 | observe |
| Epodonios-all | 0.255 | None | 0 | 7819 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9376 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5938 | observe |
| barry-far-vless | 0.255 | None | 0 | 6176 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4285 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1802 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 23 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 7 |
| speed | ClientOSError | - | 4 |
| geo | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:38387: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
