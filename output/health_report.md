# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 11:11:38 |
| 运行耗时 | 767.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91201 |
| 去重后节点 | 24193 |
| TCP 可达 | 3000 |
| 真实可用 | 467 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24193 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.7 |
| tcp | 41.3 |
| probe | 336.1 |
| real_test | 295.1 |
| generate | 86.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55435 |
| vmess | 13056 |
| shadowsocks | 10980 |
| trojan | 8869 |
| hysteria2 | 1964 |
| http | 685 |
| shadowsocksr | 124 |
| socks | 56 |
| hysteria | 15 |
| tuic | 10 |
| anytls | 7 |

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
| 80.44 | shadowsocks | 256.4 | 641.1 | 21.84 | 0.0 | 9.14 | 14.18 | 19.28 | Au1rxx-base64 | 156.146.38.169 |
| 77.87 | shadowsocks | 303.0 | 736.5 | 20.76 | 0.0 | 10.0 | 14.18 | 19.28 | Au1rxx-base64 | 37.19.198.160 |
| 77.61 | vless | 313.7 | 753.0 | 20.52 | 0.0 | 10.0 | 9.22 | 19.28 | Au1rxx-base64 | 47.253.226.114 |
| 77.06 | shadowsocks | 351.2 | 807.1 | 19.65 | 0.0 | 10.0 | 14.18 | 19.28 | Au1rxx-base64 | 15.204.247.175 |
| 77.02 | hysteria2 | 286.9 | 687.4 | 21.14 | 0.0 | 10.0 | 13.64 | 13.34 | mheidari-all | 159.223.157.129 |
| 76.62 | vless | 300.6 | 739.3 | 20.82 | 0.0 | 8.77 | 9.22 | 19.28 | Au1rxx-base64 | 79.141.172.154 |
| 76.47 | shadowsocks | 365.5 | 870.5 | 19.32 | 0.0 | 8.95 | 14.18 | 19.28 | Au1rxx-base64 | 15.204.246.132 |
| 76.4 | shadowsocks | 252.0 | 634.0 | 21.94 | 0.0 | 10.0 | 14.18 | 19.28 | Au1rxx-base64 | 156.146.38.167 |
| 76.3 | vless | 380.7 | 975.3 | 18.97 | 0.0 | 8.83 | 9.22 | 19.28 | Au1rxx-base64 | 216.152.147.28 |
| 75.66 | vless | 302.9 | 662.4 | 20.77 | 0.0 | 10.0 | 9.22 | 19.28 | Au1rxx-base64 | 195.123.235.177 |
| 75.49 | shadowsocks | 314.4 | 711.1 | 20.5 | 0.0 | 10.0 | 14.18 | 17.72 | Surfboard-tg-mixed | 198.98.53.130 |
| 74.07 | shadowsocks | 290.3 | 529.9 | 21.06 | 0.0 | 8.88 | 14.18 | 19.28 | Au1rxx-base64 | 108.181.118.10 |
| 74.05 | shadowsocks | 316.3 | 644.1 | 20.46 | 0.0 | 8.84 | 14.18 | 19.28 | Au1rxx-base64 | 51.222.200.165 |
| 73.97 | vless | 302.6 | 594.0 | 20.77 | 0.0 | 9.17 | 9.22 | 19.28 | Au1rxx-base64 | 172.235.43.210 |
| 73.8 | shadowsocks | 301.2 | 552.3 | 20.81 | 0.0 | 8.74 | 14.18 | 19.28 | Au1rxx-base64 | 108.181.0.177 |
| 73.71 | vless | 356.8 | 755.0 | 19.52 | 0.0 | 8.92 | 9.22 | 19.28 | Au1rxx-base64 | 66.70.179.198 |
| 73.69 | shadowsocks | 397.0 | 894.4 | 18.59 | 0.0 | 8.85 | 14.18 | 19.28 | Au1rxx-base64 | 38.180.135.156 |
| 73.59 | vless | 375.3 | 747.7 | 19.09 | 0.0 | 8.82 | 9.22 | 19.28 | Au1rxx-base64 | 169.40.42.202 |
| 73.48 | vless | 308.6 | 718.3 | 20.64 | 0.0 | 10.0 | 9.22 | 17.72 | Surfboard-tg-mixed | 130.94.115.231 |
| 73.47 | shadowsocks | 307.4 | 739.3 | 20.66 | 0.0 | 8.78 | 14.18 | 19.28 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.948 | 0.886 | 263 | 1628 | prefer |
| Surfboard-tg-mixed | 0.815 | 0.738 | 164 | 7439 | prefer |
| ermaozi | 0.75 | 0.741 | 54 | 449 | prefer |
| mheidari-all | 0.522 | 0.441 | 161 | 19290 | observe |
| ermaozi-get_subscribe | 0.274 | 1.0 | 1 | 469 | observe |
| tg-oneclickvpnkeys | 0.264 | 1.0 | 1 | 214 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7808 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8703 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6025 | observe |
| barry-far-vless | 0.255 | None | 0 | 6215 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3508 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 57 |
| 204 | TimeoutError | - | 38 |
| 204 | ProxyError | - | 23 |
| cn-block | ClientOSError | - | 23 |
| cn-block | TimeoutError | - | 14 |
| geo | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 7 |
| speed | ClientOSError | - | 6 |
| speed | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
