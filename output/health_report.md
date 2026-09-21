# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 12:36:22 |
| 运行耗时 | 553.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84513 |
| 去重后节点 | 23453 |
| TCP 可达 | 3000 |
| 真实可用 | 463 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23453 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.4 |
| tcp | 39.0 |
| probe | 215.9 |
| real_test | 217.6 |
| generate | 75.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51112 |
| vmess | 13408 |
| shadowsocks | 9643 |
| trojan | 8380 |
| hysteria2 | 1105 |
| http | 632 |
| shadowsocksr | 140 |
| socks | 75 |
| hysteria | 10 |
| tuic | 4 |
| anytls | 4 |

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
| 80.74 | hysteria2 | 294.3 | 646.2 | 20.97 | 0.0 | 10.0 | 14.17 | 18.72 | Au1rxx-base64 | 66.94.121.46 |
| 79.59 | shadowsocks | 270.6 | 614.5 | 21.51 | 0.0 | 10.0 | 13.86 | 18.72 | Au1rxx-base64 | 23.150.248.20 |
| 78.26 | vless | 260.6 | 650.6 | 21.74 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 195.211.98.43 |
| 77.67 | vless | 286.4 | 722.4 | 21.15 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 79.141.172.154 |
| 74.37 | shadowsocks | 364.5 | 951.8 | 19.34 | 0.0 | 6.95 | 13.86 | 18.72 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 74.29 | vless | 320.5 | 764.7 | 20.36 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 47.253.226.114 |
| 73.79 | shadowsocks | 434.1 | 1102.5 | 17.73 | 0.0 | 10.0 | 13.86 | 18.72 | Au1rxx-base64 | 142.4.216.225 |
| 71.86 | hysteria2 | 459.9 | 712.3 | 17.13 | 0.0 | 9.82 | 14.17 | 18.72 | Au1rxx-base64 | 62.210.124.146 |
| 71.75 | vless | 329.6 | 635.8 | 20.15 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 15.204.97.216 |
| 71.51 | vless | 394.1 | 895.1 | 18.65 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 158.69.112.254 |
| 71.19 | hysteria2 | 510.7 | 1010.9 | 15.95 | 0.0 | 9.7 | 14.17 | 18.72 | Au1rxx-base64 | 91.196.32.163 |
| 70.98 | vless | 405.5 | 977.8 | 18.39 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 169.40.42.202 |
| 70.87 | vless | 365.2 | 678.1 | 19.32 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 138.124.60.146 |
| 70.86 | vless | 428.4 | 886.3 | 17.86 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 169.40.42.15 |
| 70.84 | vless | 357.3 | 838.1 | 19.51 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 169.40.42.212 |
| 70.83 | hysteria2 | 438.0 | 793.5 | 17.64 | 0.0 | 9.63 | 14.17 | 18.72 | Au1rxx-base64 | 45.192.12.93 |
| 70.8 | vless | 387.9 | 862.7 | 18.8 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 169.40.42.90 |
| 70.66 | vless | 472.0 | 1041.0 | 16.85 | 0.0 | 10.0 | 7.8 | 18.72 | Au1rxx-base64 | 169.40.42.163 |
| 70.24 | shadowsocks | 320.1 | 763.7 | 20.37 | 0.0 | 10.0 | 13.86 | 12.34 | Surfboard-tg-mixed | 37.19.198.243 |
| 70.14 | shadowsocks | 314.5 | 754.4 | 20.5 | 0.0 | 10.0 | 13.86 | 11.22 | mheidari-all | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.938 | 0.875 | 272 | 1649 | prefer |
| mheidari-all | 0.937 | 0.879 | 33 | 16192 | prefer |
| Surfboard-tg-mixed | 0.709 | 0.63 | 200 | 7246 | prefer |
| DeltaKronecker-all | 0.62 | 0.541 | 61 | 6181 | observe |
| ermaozi | 0.53 | 0.516 | 62 | 350 | observe |
| Au1rxx-clash | 0.424 | 1.0 | 3 | 1638 | observe |
| tg-oneclickvpnkeys | 0.273 | 0.667 | 3 | 108 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5290 | observe |
| Epodonios-all | 0.255 | None | 0 | 7697 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8900 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5845 | observe |
| barry-far-vless | 0.255 | None | 0 | 6062 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 38 |
| geo | ClientOSError | - | 36 |
| 204 | ProxyError | - | 32 |
| speed | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 12 |
| speed | TimeoutError | - | 12 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
