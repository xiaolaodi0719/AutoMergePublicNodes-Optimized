# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 04:30:07 |
| 运行耗时 | 1047.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85237 |
| 去重后节点 | 23245 |
| TCP 可达 | 3000 |
| 真实可用 | 574 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23245 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 38.3 |
| probe | 350.4 |
| real_test | 569.8 |
| generate | 82.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52006 |
| vmess | 12921 |
| shadowsocks | 9526 |
| trojan | 8329 |
| hysteria2 | 1561 |
| http | 680 |
| shadowsocksr | 130 |
| socks | 68 |
| hysteria | 9 |
| tuic | 5 |
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
| 83.35 | vless | 215.5 | 553.9 | 22.79 | 0.0 | 10.0 | 11.26 | 19.3 | Au1rxx-base64 | 45.149.172.74 |
| 81.89 | shadowsocks | 191.1 | 505.9 | 23.35 | 0.0 | 10.0 | 13.74 | 19.3 | Au1rxx-base64 | 192.3.247.109 |
| 81.61 | shadowsocks | 203.2 | 500.0 | 23.07 | 0.0 | 10.0 | 13.74 | 19.3 | Au1rxx-base64 | 108.181.0.177 |
| 80.81 | trojan | 313.8 | 772.0 | 20.51 | 0.0 | 10.0 | 13.5 | 19.3 | Au1rxx-base64 | 100.42.228.109 |
| 80.74 | vless | 198.6 | 511.8 | 23.18 | 0.0 | 10.0 | 11.26 | 19.3 | Au1rxx-base64 | 192.3.247.109 |
| 80.65 | hysteria2 | 315.2 | 808.0 | 20.48 | 0.0 | 10.0 | 12.0 | 19.3 | Au1rxx-base64 | 107.175.219.48 |
| 78.38 | vless | 235.7 | 516.5 | 22.32 | 0.0 | 10.0 | 11.26 | 19.3 | Au1rxx-base64 | 162.159.43.187 |
| 78.25 | vless | 366.6 | 898.2 | 19.29 | 0.0 | 10.0 | 11.26 | 19.3 | Au1rxx-base64 | 15.204.97.216 |
| 77.13 | shadowsocks | 275.8 | 658.4 | 21.39 | 0.0 | 10.0 | 13.74 | 16.0 | mheidari-all | 173.244.56.6 |
| 76.87 | shadowsocks | 274.3 | 577.3 | 21.43 | 0.0 | 10.0 | 13.74 | 19.3 | Au1rxx-base64 | 149.22.95.183 |
| 76.72 | hysteria2 | 263.2 | 672.4 | 21.68 | 0.0 | 10.0 | 12.0 | 14.04 | Surfboard-tg-mixed | 45.149.172.74 |
| 76.72 | vless | 306.6 | 436.5 | 20.68 | 0.0 | 10.0 | 11.26 | 19.3 | Au1rxx-base64 | 172.64.229.2 |
| 76.55 | vless | 233.4 | 535.9 | 22.37 | 0.0 | 10.0 | 11.26 | 19.3 | Au1rxx-base64 | 31.58.50.200 |
| 76.55 | shadowsocks | 279.5 | 721.5 | 21.31 | 0.0 | 10.0 | 13.74 | 16.0 | mheidari-all | 108.181.118.10 |
| 76.48 | vless | 261.8 | 538.8 | 21.72 | 0.0 | 10.0 | 11.26 | 19.3 | Au1rxx-base64 | 144.172.104.26 |
| 76.39 | shadowsocks | 261.7 | 636.9 | 21.72 | 0.0 | 10.0 | 13.74 | 16.0 | mheidari-all | 156.146.38.169 |
| 76.28 | hysteria2 | 282.6 | 762.6 | 21.24 | 0.0 | 10.0 | 12.0 | 14.04 | Surfboard-tg-mixed | 45.149.172.80 |
| 75.89 | vless | 234.4 | 518.0 | 22.35 | 0.0 | 10.0 | 11.26 | 19.3 | Au1rxx-base64 | 172.64.229.170 |
| 75.8 | vless | 269.6 | 443.9 | 21.54 | 0.0 | 10.0 | 11.26 | 19.3 | Au1rxx-base64 | 104.18.47.113 |
| 74.61 | http | 197.3 | 498.1 | 23.21 | 0.0 | 10.0 | 10.5 | 13.9 | ermaozi | 138.199.35.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.947 | 0.885 | 260 | 1634 | prefer |
| ermaozi | 0.868 | 0.88 | 25 | 407 | prefer |
| Surfboard-tg-mixed | 0.864 | 0.791 | 86 | 7549 | prefer |
| mheidari-all | 0.663 | 0.584 | 113 | 16114 | observe |
| ermaozi-get_subscribe | 0.485 | 0.778 | 9 | 438 | observe |
| DeltaKronecker-all | 0.441 | 0.36 | 497 | 5932 | observe |
| ninja-vless | 0.279 | 0.5 | 2 | 1791 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 163 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 8042 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8939 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6134 | observe |
| barry-far-vless | 0.255 | None | 0 | 6344 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 222 |
| geo | ClientOSError | - | 56 |
| speed | TimeoutError | - | 47 |
| speed | ClientOSError | - | 33 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 15 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 12 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
