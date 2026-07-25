# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-25 13:50:42 |
| 运行耗时 | 329.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78947 |
| 去重后节点 | 22518 |
| TCP 可达 | 3000 |
| 真实可用 | 667 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22518 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.3 |
| tcp | 31.4 |
| probe | 64.9 |
| real_test | 188.0 |
| generate | 39.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44190 |
| trojan | 14067 |
| vmess | 10128 |
| shadowsocks | 9879 |
| hysteria2 | 432 |
| http | 81 |
| shadowsocksr | 76 |
| socks | 67 |
| hysteria | 15 |
| tuic | 11 |
| anytls | 1 |

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
| 73.5 | shadowsocks | 249.8 | 674.0 | 22.0 | 0.0 | 10.0 | 9.0 | 16.5 | mheidari-all | 37.19.198.236 |
| 71.49 | trojan | 438.1 | 767.8 | 17.64 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 5.10.214.34 |
| 71.45 | trojan | 441.3 | 780.7 | 17.56 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 162.159.193.138 |
| 71.44 | trojan | 440.6 | 762.9 | 17.58 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 141.193.213.10 |
| 71.43 | trojan | 442.4 | 787.2 | 17.54 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 162.159.153.4 |
| 71.43 | trojan | 443.0 | 776.3 | 17.52 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 5.10.214.53 |
| 71.42 | trojan | 436.5 | 760.8 | 17.67 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 162.159.193.22 |
| 71.42 | trojan | 440.9 | 773.6 | 17.57 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 45.85.118.176 |
| 71.24 | trojan | 440.1 | 773.4 | 17.59 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 199.181.197.111 |
| 71.2 | trojan | 452.0 | 779.6 | 17.31 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 91.193.58.77 |
| 70.86 | vmess | 385.3 | 1084.3 | 18.86 | 0.0 | 10.0 | 10.0 | 16.5 | mheidari-all | 67.220.95.3 |
| 70.2 | trojan | 444.8 | 775.1 | 17.48 | 0.0 | 10.0 | 14.19 | 16.5 | mheidari-all | 8.6.112.6 |
| 69.73 | trojan | 504.4 | 770.4 | 16.1 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 162.159.253.41 |
| 69.4 | trojan | 514.3 | 849.6 | 15.87 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 104.16.174.101 |
| 69.17 | trojan | 505.9 | 823.8 | 16.07 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 104.18.152.133 |
| 68.96 | trojan | 525.9 | 846.1 | 15.6 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 104.17.111.3 |
| 68.79 | trojan | 531.8 | 817.1 | 15.47 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 104.18.152.244 |
| 68.72 | trojan | 527.0 | 902.9 | 15.58 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 104.18.152.210 |
| 68.57 | trojan | 549.0 | 819.5 | 15.07 | 0.0 | 10.0 | 14.19 | 17.6 | DeltaKronecker-all | 172.67.188.109 |
| 68.56 | trojan | 503.3 | 830.9 | 16.13 | 0.0 | 10.0 | 14.19 | 16.5 | mheidari-all | 104.16.174.121 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 0.946 | 258 | 17158 | prefer |
| zhangkai | 0.992 | 1.0 | 76 | 119 | prefer |
| Surfboard-tg-mixed | 0.73 | 0.655 | 58 | 5379 | prefer |
| DeltaKronecker-all | 0.469 | 0.389 | 777 | 5838 | observe |
| Au1rxx-base64 | 0.417 | 0.714 | 7 | 803 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 180 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4879 | observe |
| Epodonios-all | 0.255 | None | 0 | 6540 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3969 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6338 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4058 | observe |
| barry-far-vless | 0.255 | None | 0 | 4746 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5009 | observe |
| nscl5-all | 0.255 | None | 0 | 2974 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 188 |
| geo | TimeoutError | - | 147 |
| 204 | ProxyError | - | 56 |
| geo | ClientOSError | - | 39 |
| speed | TimeoutError | - | 31 |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 18 |
| cn-block | ProxyError | - | 10 |
| geo | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
