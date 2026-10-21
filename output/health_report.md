# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 11:39:13 |
| 运行耗时 | 607.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 95751 |
| 去重后节点 | 26901 |
| TCP 可达 | 3000 |
| 真实可用 | 351 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26901 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.6 |
| tcp | 44.7 |
| probe | 240.2 |
| real_test | 232.2 |
| generate | 82.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56941 |
| vmess | 16911 |
| shadowsocks | 11797 |
| trojan | 8438 |
| hysteria2 | 1216 |
| http | 173 |
| shadowsocksr | 165 |
| socks | 63 |
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
| 80.77 | hysteria2 | 287.4 | 598.6 | 21.12 | 0.0 | 10.0 | 12.86 | 18.38 | Au1rxx-base64 | 66.94.121.46 |
| 80.14 | vless | 189.9 | 483.9 | 23.38 | 0.0 | 10.0 | 8.38 | 18.38 | Au1rxx-base64 | 45.63.53.81 |
| 80.06 | shadowsocks | 254.9 | 616.6 | 21.88 | 0.0 | 10.0 | 13.86 | 18.38 | Au1rxx-base64 | 156.146.38.170 |
| 80.06 | shadowsocks | 257.3 | 627.9 | 21.82 | 0.0 | 10.0 | 13.86 | 18.38 | Au1rxx-base64 | 156.146.38.167 |
| 79.89 | shadowsocks | 259.2 | 632.4 | 21.78 | 0.0 | 10.0 | 13.86 | 18.38 | Au1rxx-base64 | 156.146.38.168 |
| 79.77 | vless | 206.0 | 523.5 | 23.01 | 0.0 | 10.0 | 8.38 | 18.38 | Au1rxx-base64 | 154.29.145.196 |
| 78.65 | hysteria2 | 316.3 | 727.0 | 20.46 | 0.0 | 10.0 | 12.86 | 18.38 | Au1rxx-base64 | 129.213.91.185 |
| 77.91 | vless | 286.4 | 456.3 | 21.15 | 0.0 | 10.0 | 8.38 | 18.38 | Au1rxx-base64 | 195.123.240.65 |
| 77.34 | shadowsocks | 310.0 | 862.4 | 20.6 | 0.0 | 10.0 | 13.86 | 18.38 | Au1rxx-base64 | 95.215.201.18 |
| 76.81 | vless | 305.8 | 741.4 | 20.7 | 0.0 | 10.0 | 8.38 | 18.2 | Surfboard-tg-mixed | 147.45.60.160 |
| 76.66 | shadowsocks | 280.4 | 281.6 | 21.29 | 4.44 | 9.91 | 13.86 | 18.38 | Au1rxx-base64 | 149.22.87.241 |
| 76.12 | vless | 237.5 | 577.4 | 22.28 | 0.0 | 8.53 | 8.38 | 18.38 | Au1rxx-base64 | 154.40.55.185 |
| 75.64 | shadowsocks | 287.3 | 296.6 | 21.13 | 3.88 | 9.91 | 13.86 | 18.2 | Surfboard-tg-mixed | 149.22.87.240 |
| 75.62 | shadowsocks | 225.5 | 545.0 | 22.56 | 0.0 | 10.0 | 13.86 | 18.2 | Surfboard-tg-mixed | 176.122.177.140 |
| 75.54 | shadowsocks | 289.2 | 628.4 | 21.08 | 0.0 | 10.0 | 13.86 | 18.38 | Au1rxx-base64 | 149.22.95.183 |
| 74.94 | vless | 198.6 | 510.8 | 23.18 | 0.0 | 10.0 | 8.38 | 18.38 | Au1rxx-base64 | 67.209.190.18 |
| 74.61 | vless | 213.1 | 558.5 | 22.85 | 0.0 | 10.0 | 8.38 | 18.38 | Au1rxx-base64 | 45.76.172.197 |
| 74.52 | vless | 217.0 | 543.7 | 22.76 | 0.0 | 10.0 | 8.38 | 18.38 | Au1rxx-base64 | 156.229.164.4 |
| 74.24 | vless | 289.0 | 590.2 | 21.09 | 0.0 | 10.0 | 8.38 | 18.38 | Au1rxx-base64 | 44.248.233.99 |
| 73.96 | trojan | 277.4 | 624.7 | 21.36 | 0.0 | 7.83 | 12.8 | 18.38 | Au1rxx-base64 | www.findlocaljobnetworkandbuildcommunityconnections.com |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.906 | 0.841 | 44 | 23726 | prefer |
| Au1rxx-base64 | 0.82 | 0.761 | 272 | 1528 | prefer |
| Surfboard-tg-mixed | 0.726 | 0.649 | 97 | 6977 | prefer |
| ermaozi-get_subscribe | 0.475 | 0.453 | 64 | 516 | observe |
| DeltaKronecker-all | 0.382 | 0.357 | 14 | 4067 | observe |
| zhangkai | 0.358 | 0.346 | 26 | 31 | observe |
| Au1rxx-clash | 0.317 | 1.0 | 1 | 1541 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| Epodonios-all | 0.255 | None | 0 | 7465 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10023 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5462 | observe |
| barry-far-vless | 0.255 | None | 0 | 5674 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 44 |
| 204 | TimeoutError | - | 29 |
| cn-block | TimeoutError | - | 24 |
| speed | TimeoutError | - | 17 |
| geo | ClientOSError | - | 14 |
| speed | ClientOSError | - | 13 |
| 204 | ProxyConnectionError | - | 10 |
| geo | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
