# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 21:18:18 |
| 运行耗时 | 573.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84619 |
| 去重后节点 | 23068 |
| TCP 可达 | 3000 |
| 真实可用 | 427 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23068 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.5 |
| tcp | 38.2 |
| probe | 252.7 |
| real_test | 195.4 |
| generate | 80.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50816 |
| vmess | 13348 |
| shadowsocks | 10081 |
| trojan | 8230 |
| hysteria2 | 1351 |
| http | 595 |
| shadowsocksr | 120 |
| socks | 66 |
| hysteria | 8 |
| tuic | 2 |
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
| 76.65 | shadowsocks | 240.3 | 605.0 | 22.22 | 0.0 | 10.0 | 13.33 | 15.1 | mheidari-all | 156.146.38.168 |
| 75.79 | vless | 284.9 | 588.8 | 21.18 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 172.235.43.210 |
| 75.59 | vless | 326.1 | 740.4 | 20.23 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 79.141.172.154 |
| 75.43 | shadowsocks | 273.0 | 647.9 | 21.46 | 0.0 | 10.0 | 13.33 | 18.42 | Au1rxx-base64 | 5.78.51.123 |
| 75.03 | shadowsocks | 246.3 | 625.5 | 22.08 | 0.0 | 10.0 | 13.33 | 13.62 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.87 | shadowsocks | 313.9 | 686.5 | 20.51 | 0.0 | 10.0 | 13.33 | 18.42 | Au1rxx-base64 | 173.244.56.9 |
| 74.22 | shadowsocks | 237.8 | 588.8 | 22.27 | 0.0 | 10.0 | 13.33 | 13.62 | Surfboard-tg-mixed | 156.146.38.167 |
| 73.68 | hysteria2 | 220.0 | 529.8 | 22.69 | 0.0 | 0.0 | 13.57 | 18.42 | Au1rxx-base64 | 66.94.121.46 |
| 73.21 | vless | 323.3 | 582.5 | 20.29 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 38.180.242.205 |
| 73.15 | shadowsocks | 297.2 | 732.3 | 20.9 | 0.0 | 10.0 | 13.33 | 18.42 | Au1rxx-base64 | 23.150.248.20 |
| 73.03 | hysteria2 | 331.5 | 756.6 | 20.1 | 0.0 | 10.0 | 13.57 | 15.1 | mheidari-all | 159.223.157.129 |
| 72.78 | vless | 368.3 | 774.1 | 19.25 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 185.95.231.156 |
| 72.45 | vless | 357.8 | 720.7 | 19.5 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 130.107.73.148 |
| 72.17 | vless | 305.2 | 588.6 | 20.71 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 45.149.172.74 |
| 71.87 | vless | 375.5 | 750.1 | 19.08 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 169.40.42.35 |
| 71.83 | hysteria2 | 419.6 | 735.6 | 18.06 | 0.0 | 9.72 | 13.57 | 18.42 | Au1rxx-base64 | 62.210.124.146 |
| 71.42 | vless | 390.0 | 747.7 | 18.75 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 169.40.42.95 |
| 71.39 | vless | 388.3 | 773.1 | 18.79 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 169.40.42.235 |
| 71.37 | vless | 393.1 | 804.6 | 18.68 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 169.40.42.75 |
| 71.3 | vless | 392.0 | 798.5 | 18.7 | 0.0 | 10.0 | 9.87 | 18.42 | Au1rxx-base64 | 169.40.42.16 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.961 | 0.899 | 267 | 1619 | prefer |
| Surfboard-tg-mixed | 0.83 | 0.759 | 58 | 7499 | prefer |
| DeltaKronecker-all | 0.788 | 0.712 | 118 | 5931 | prefer |
| ermaozi | 0.742 | 0.742 | 31 | 357 | prefer |
| mheidari-all | 0.71 | 0.635 | 52 | 16164 | prefer |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4261 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5093 | observe |
| Epodonios-all | 0.255 | None | 0 | 7954 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8875 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5936 | observe |
| barry-far-vless | 0.255 | None | 0 | 6157 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1619 | observe |
| ermaozi-get_subscribe | 0.234 | 0.4 | 5 | 361 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 23 |
| geo | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 13 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyConnectionError | - | 6 |
| speed | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
