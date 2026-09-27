# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 16:51:00 |
| 运行耗时 | 455.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 96135 |
| 去重后节点 | 26661 |
| TCP 可达 | 3000 |
| 真实可用 | 334 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26661 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.5 |
| tcp | 44.2 |
| probe | 185.6 |
| real_test | 139.5 |
| generate | 78.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58742 |
| vmess | 14608 |
| shadowsocks | 11295 |
| trojan | 9175 |
| hysteria2 | 1454 |
| http | 574 |
| shadowsocksr | 170 |
| socks | 69 |
| anytls | 25 |
| hysteria | 15 |
| tuic | 8 |

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
| 81.29 | vless | 284.0 | 685.0 | 21.2 | 0.0 | 9.74 | 11.57 | 18.78 | Au1rxx-base64 | 198.251.78.29 |
| 79.91 | shadowsocks | 246.7 | 614.8 | 22.07 | 0.0 | 9.89 | 13.17 | 18.78 | Au1rxx-base64 | 156.146.38.169 |
| 78.72 | shadowsocks | 254.4 | 631.6 | 21.89 | 0.0 | 10.0 | 13.17 | 17.66 | mheidari-all | 156.146.38.168 |
| 77.92 | vless | 286.8 | 584.2 | 21.14 | 0.0 | 9.89 | 11.57 | 18.78 | Au1rxx-base64 | 192.3.247.109 |
| 77.59 | shadowsocks | 302.6 | 752.4 | 20.77 | 0.0 | 9.78 | 13.17 | 18.78 | Au1rxx-base64 | 37.19.198.244 |
| 77.27 | vless | 366.4 | 784.6 | 19.3 | 0.0 | 9.76 | 11.57 | 18.78 | Au1rxx-base64 | 169.40.42.179 |
| 76.97 | vless | 321.0 | 769.0 | 20.35 | 0.0 | 9.74 | 11.57 | 18.78 | Au1rxx-base64 | 47.253.144.114 |
| 76.93 | vless | 400.3 | 916.5 | 18.51 | 0.0 | 9.77 | 11.57 | 18.78 | Au1rxx-base64 | 169.40.42.16 |
| 76.91 | vless | 315.0 | 706.6 | 20.49 | 0.0 | 9.72 | 11.57 | 18.78 | Au1rxx-base64 | 23.191.200.207 |
| 76.58 | vless | 319.5 | 670.2 | 20.38 | 0.0 | 9.75 | 11.57 | 18.78 | Au1rxx-base64 | 5.78.159.214 |
| 76.31 | shadowsocks | 255.5 | 638.2 | 21.86 | 0.0 | 10.0 | 13.17 | 15.28 | Surfboard-tg-mixed | 156.146.38.170 |
| 76.15 | shadowsocks | 340.7 | 867.6 | 19.89 | 0.0 | 8.81 | 13.17 | 18.78 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 75.86 | vless | 431.1 | 1083.0 | 17.8 | 0.0 | 9.77 | 11.57 | 18.78 | Au1rxx-base64 | 185.95.231.156 |
| 75.85 | vless | 345.6 | 695.9 | 19.78 | 0.0 | 9.74 | 11.57 | 18.78 | Au1rxx-base64 | 169.40.42.202 |
| 75.63 | vless | 331.9 | 702.7 | 20.1 | 0.0 | 9.73 | 11.57 | 18.78 | Au1rxx-base64 | 38.244.20.25 |
| 75.55 | hysteria2 | 376.0 | 890.9 | 19.07 | 0.0 | 9.67 | 12.95 | 18.78 | Au1rxx-base64 | 192.255.128.123 |
| 75.49 | vless | 296.0 | 599.7 | 20.93 | 0.0 | 9.71 | 11.57 | 18.78 | Au1rxx-base64 | 172.235.43.210 |
| 75.29 | vless | 330.9 | 664.7 | 20.12 | 0.0 | 9.79 | 11.57 | 18.78 | Au1rxx-base64 | 15.204.97.216 |
| 75.24 | vless | 312.1 | 750.9 | 20.55 | 0.0 | 9.76 | 11.57 | 18.78 | Au1rxx-base64 | 47.90.153.88 |
| 75.12 | vless | 293.6 | 648.1 | 20.98 | 0.0 | 9.93 | 11.57 | 18.78 | Au1rxx-base64 | 195.123.235.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.916 | 0.855 | 296 | 1601 | prefer |
| Surfboard-tg-mixed | 0.84 | 0.882 | 17 | 7109 | prefer |
| mheidari-all | 0.834 | 0.764 | 55 | 22413 | prefer |
| ermaozi | 0.65 | 0.647 | 34 | 289 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7600 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9194 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5703 | observe |
| barry-far-vless | 0.255 | None | 0 | 5938 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4277 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1601 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 20 |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 15 |
| speed | TimeoutError | - | 8 |
| speed | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| geo | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
