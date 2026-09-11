# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 20:55:38 |
| 运行耗时 | 612.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83905 |
| 去重后节点 | 23390 |
| TCP 可达 | 3000 |
| 真实可用 | 416 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23390 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.4 |
| tcp | 40.3 |
| probe | 273.1 |
| real_test | 216.9 |
| generate | 76.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51162 |
| vmess | 12565 |
| shadowsocks | 9764 |
| trojan | 8006 |
| hysteria2 | 1608 |
| http | 599 |
| shadowsocksr | 125 |
| socks | 53 |
| tuic | 12 |
| hysteria | 9 |
| anytls | 2 |

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
| 81.28 | vless | 204.5 | 517.6 | 23.04 | 0.0 | 10.0 | 10.34 | 17.9 | Au1rxx-base64 | 172.233.139.46 |
| 81.17 | vless | 209.6 | 524.0 | 22.93 | 0.0 | 10.0 | 10.34 | 17.9 | Au1rxx-base64 | 172.235.43.210 |
| 80.9 | vless | 221.2 | 548.6 | 22.66 | 0.0 | 10.0 | 10.34 | 17.9 | Au1rxx-base64 | 172.235.38.85 |
| 80.73 | shadowsocks | 237.2 | 602.6 | 22.29 | 0.0 | 10.0 | 13.62 | 18.82 | mheidari-all | 173.244.56.9 |
| 80.64 | vless | 232.3 | 577.2 | 22.4 | 0.0 | 10.0 | 10.34 | 17.9 | Au1rxx-base64 | 38.209.125.45 |
| 80.61 | shadowsocks | 242.1 | 600.0 | 22.17 | 0.0 | 10.0 | 13.62 | 18.82 | mheidari-all | 173.244.56.6 |
| 79.77 | shadowsocks | 265.7 | 647.4 | 21.63 | 0.0 | 10.0 | 13.62 | 18.82 | mheidari-all | 156.146.38.169 |
| 79.14 | shadowsocks | 268.5 | 649.5 | 21.56 | 0.0 | 10.0 | 13.62 | 18.82 | mheidari-all | 156.146.38.170 |
| 78.89 | shadowsocks | 258.6 | 619.6 | 21.79 | 0.0 | 10.0 | 13.62 | 18.82 | mheidari-all | 156.146.38.168 |
| 77.46 | shadowsocks | 261.0 | 632.3 | 21.74 | 0.0 | 10.0 | 13.62 | 16.32 | Surfboard-tg-mixed | 156.146.38.167 |
| 77.45 | shadowsocks | 231.2 | 429.1 | 22.43 | 0.0 | 10.0 | 13.62 | 17.9 | Au1rxx-base64 | 129.146.122.135 |
| 76.72 | shadowsocks | 296.7 | 760.9 | 20.91 | 0.0 | 10.0 | 13.62 | 18.82 | mheidari-all | 108.181.118.10 |
| 76.24 | vless | 228.1 | 508.7 | 22.5 | 0.0 | 10.0 | 10.34 | 17.9 | Au1rxx-base64 | 104.18.46.234 |
| 76.09 | vless | 213.1 | 533.5 | 22.85 | 0.0 | 10.0 | 10.34 | 17.9 | Au1rxx-base64 | 107.173.237.146 |
| 76.09 | hysteria2 | 316.4 | 700.9 | 20.45 | 0.0 | 10.0 | 12.95 | 17.9 | Au1rxx-base64 | 159.223.157.129 |
| 76.08 | shadowsocks | 294.8 | 275.7 | 20.95 | 4.66 | 9.88 | 13.62 | 18.82 | mheidari-all | 45.32.16.53 |
| 75.72 | vless | 350.5 | 844.6 | 19.66 | 0.0 | 10.0 | 10.34 | 17.9 | Au1rxx-base64 | 15.204.97.216 |
| 75.36 | vless | 233.5 | 482.4 | 22.37 | 0.0 | 10.0 | 10.34 | 17.9 | Au1rxx-base64 | 104.18.46.46 |
| 75.25 | vless | 333.2 | 755.8 | 20.06 | 0.0 | 10.0 | 10.34 | 17.9 | Au1rxx-base64 | 79.141.172.154 |
| 75.03 | shadowsocks | 291.1 | 613.0 | 21.04 | 0.0 | 10.0 | 13.62 | 18.82 | mheidari-all | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.931 | 0.869 | 274 | 1630 | prefer |
| mheidari-all | 0.78 | 0.705 | 88 | 15494 | prefer |
| DeltaKronecker-all | 0.776 | 0.714 | 21 | 6070 | prefer |
| Surfboard-tg-mixed | 0.674 | 0.595 | 153 | 7355 | observe |
| ermaozi | 0.458 | 0.533 | 15 | 377 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 194 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7810 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9022 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5993 | observe |
| barry-far-vless | 0.255 | None | 0 | 6209 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1630 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 48 |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyError | - | 19 |
| speed | ClientOSError | - | 12 |
| cn-block | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 6 |
| geo | TimeoutError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
