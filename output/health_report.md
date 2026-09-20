# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 11:10:08 |
| 运行耗时 | 570.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83340 |
| 去重后节点 | 23416 |
| TCP 可达 | 3000 |
| 真实可用 | 493 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23416 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.5 |
| tcp | 38.5 |
| probe | 251.8 |
| real_test | 182.0 |
| generate | 90.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49642 |
| vmess | 13449 |
| shadowsocks | 9955 |
| trojan | 8247 |
| hysteria2 | 1172 |
| http | 667 |
| shadowsocksr | 120 |
| socks | 72 |
| hysteria | 11 |
| tuic | 3 |
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
| 81.8 | shadowsocks | 234.1 | 594.6 | 22.36 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | 156.146.38.167 |
| 81.76 | shadowsocks | 235.7 | 602.3 | 22.32 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | 156.146.38.168 |
| 81.67 | shadowsocks | 239.9 | 613.1 | 22.23 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | 156.146.38.169 |
| 80.63 | shadowsocks | 263.2 | 623.4 | 21.69 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | 23.150.248.20 |
| 80.51 | shadowsocks | 289.9 | 761.6 | 21.07 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | 156.146.38.170 |
| 78.99 | hysteria2 | 318.5 | 671.3 | 20.4 | 0.0 | 10.0 | 13.5 | 19.16 | Au1rxx-base64 | 66.94.121.46 |
| 77.33 | shadowsocks | 275.4 | 577.8 | 21.4 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | 173.244.56.6 |
| 75.43 | shadowsocks | 328.8 | 740.6 | 20.17 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | 37.19.198.236 |
| 75.26 | shadowsocks | 321.8 | 720.6 | 20.33 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | 37.19.198.243 |
| 74.54 | hysteria2 | 319.3 | 727.2 | 20.39 | 0.0 | 8.82 | 13.5 | 19.16 | Au1rxx-base64 | docs.fastline-labs.com |
| 74.18 | shadowsocks | 384.7 | 921.6 | 18.87 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 73.11 | vless | 335.0 | 735.9 | 20.02 | 0.0 | 10.0 | 7.43 | 19.16 | Au1rxx-base64 | 216.152.147.28 |
| 72.95 | trojan | 374.5 | 842.5 | 19.11 | 0.0 | 10.0 | 11.05 | 19.16 | Au1rxx-base64 | 100.42.228.109 |
| 72.51 | http | 244.6 | 543.6 | 22.12 | 0.0 | 10.0 | 10.5 | 14.26 | ermaozi | 138.199.35.198 |
| 71.85 | http | 276.6 | 643.4 | 21.38 | 0.0 | 10.0 | 10.5 | 14.26 | ermaozi | 138.199.35.210 |
| 71.78 | shadowsocks | 416.1 | 908.1 | 18.15 | 0.0 | 10.0 | 14.28 | 19.16 | Au1rxx-base64 | 38.180.135.156 |
| 71.61 | vless | 303.9 | 675.5 | 20.74 | 0.0 | 10.0 | 7.43 | 19.16 | Au1rxx-base64 | 195.211.98.43 |
| 71.58 | http | 273.1 | 632.5 | 21.46 | 0.0 | 10.0 | 10.5 | 14.26 | ermaozi | 138.199.35.196 |
| 71.58 | hysteria2 | 461.5 | 875.0 | 17.09 | 0.0 | 9.78 | 13.5 | 19.16 | Au1rxx-base64 | 5.129.235.85 |
| 71.51 | http | 280.8 | 649.8 | 21.28 | 0.0 | 10.0 | 10.5 | 14.26 | ermaozi | 138.199.35.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.94 | 268 | 1589 | prefer |
| mheidari-all | 0.94 | 0.878 | 41 | 15979 | prefer |
| ermaozi | 0.76 | 0.755 | 53 | 365 | prefer |
| Surfboard-tg-mixed | 0.748 | 0.67 | 197 | 7118 | prefer |
| DeltaKronecker-all | 0.588 | 0.508 | 59 | 6092 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4315 | observe |
| 10ium-ScrapeCategorize-Vless | 0.259 | 0.333 | 3 | 5238 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 89 | observe |
| Epodonios-all | 0.255 | None | 0 | 7603 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8786 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5686 | observe |
| barry-far-vless | 0.255 | None | 0 | 5912 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1589 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 36 |
| geo | TimeoutError | - | 21 |
| 204 | ProxyError | - | 19 |
| cn-block | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 12 |
| speed | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| speed | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
