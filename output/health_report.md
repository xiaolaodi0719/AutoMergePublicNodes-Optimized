# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 16:43:28 |
| 运行耗时 | 665.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89597 |
| 去重后节点 | 24457 |
| TCP 可达 | 3000 |
| 真实可用 | 417 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24457 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.5 |
| tcp | 42.3 |
| probe | 289.9 |
| real_test | 249.5 |
| generate | 75.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53290 |
| vmess | 14347 |
| shadowsocks | 10573 |
| trojan | 9133 |
| hysteria2 | 1493 |
| http | 561 |
| shadowsocksr | 127 |
| socks | 60 |
| hysteria | 8 |
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
| 80.11 | shadowsocks | 258.8 | 662.2 | 21.79 | 0.0 | 10.0 | 13.8 | 18.52 | Au1rxx-base64 | 156.146.38.169 |
| 79.05 | shadowsocks | 261.1 | 671.5 | 21.73 | 0.0 | 10.0 | 13.8 | 18.52 | Au1rxx-base64 | 156.146.38.168 |
| 79.02 | hysteria2 | 268.9 | 631.4 | 21.55 | 0.0 | 10.0 | 13.04 | 18.86 | mheidari-all | 45.149.172.80 |
| 78.3 | hysteria2 | 317.1 | 700.3 | 20.44 | 0.0 | 10.0 | 13.04 | 18.86 | mheidari-all | 159.223.157.129 |
| 78.0 | vless | 407.2 | 843.8 | 18.35 | 0.0 | 10.0 | 11.46 | 18.52 | Au1rxx-base64 | 38.180.242.205 |
| 76.36 | hysteria2 | 226.0 | 512.3 | 22.55 | 0.0 | 10.0 | 13.04 | 18.86 | mheidari-all | 45.149.172.74 |
| 76.32 | shadowsocks | 285.5 | 682.5 | 21.17 | 0.0 | 10.0 | 13.8 | 18.52 | Au1rxx-base64 | 5.78.51.123 |
| 75.36 | shadowsocks | 283.3 | 540.3 | 21.22 | 0.0 | 10.0 | 13.8 | 18.52 | Au1rxx-base64 | 108.181.0.177 |
| 75.19 | shadowsocks | 314.8 | 697.8 | 20.49 | 0.0 | 10.0 | 13.8 | 18.86 | mheidari-all | 173.244.56.9 |
| 74.95 | shadowsocks | 292.3 | 598.2 | 21.01 | 0.0 | 10.0 | 13.8 | 18.86 | mheidari-all | 108.181.118.10 |
| 74.8 | vless | 278.9 | 587.1 | 21.32 | 0.0 | 10.0 | 11.46 | 18.52 | Au1rxx-base64 | 107.173.237.146 |
| 74.63 | vless | 235.1 | 523.8 | 22.33 | 0.0 | 10.0 | 11.46 | 14.16 | DeltaKronecker-all | 47.251.108.158 |
| 74.48 | vless | 402.1 | 926.1 | 18.47 | 0.0 | 10.0 | 11.46 | 18.52 | Au1rxx-base64 | 216.152.147.28 |
| 74.47 | vless | 287.2 | 544.4 | 21.13 | 0.0 | 10.0 | 11.46 | 18.52 | Au1rxx-base64 | 144.172.104.26 |
| 74.47 | shadowsocks | 294.6 | 583.3 | 20.96 | 0.0 | 10.0 | 13.8 | 18.52 | Au1rxx-base64 | 149.22.95.183 |
| 74.25 | vless | 350.3 | 691.7 | 19.67 | 0.0 | 10.0 | 11.46 | 18.52 | Au1rxx-base64 | 195.123.235.177 |
| 73.62 | shadowsocks | 326.5 | 705.8 | 20.22 | 0.0 | 10.0 | 13.8 | 18.86 | mheidari-all | 37.19.198.244 |
| 73.61 | vless | 442.1 | 1025.1 | 17.54 | 0.0 | 10.0 | 11.46 | 18.52 | Au1rxx-base64 | 198.251.78.29 |
| 73.23 | vless | 273.0 | 562.7 | 21.46 | 0.0 | 10.0 | 11.46 | 18.52 | Au1rxx-base64 | 45.149.172.80 |
| 73.23 | vless | 409.4 | 881.3 | 18.3 | 0.0 | 10.0 | 11.46 | 18.52 | Au1rxx-base64 | 66.70.179.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.875 | 0.81 | 268 | 1698 | prefer |
| mheidari-all | 0.866 | 0.793 | 82 | 17973 | prefer |
| ermaozi | 0.842 | 0.852 | 27 | 353 | prefer |
| DeltaKronecker-all | 0.702 | 0.624 | 109 | 6081 | prefer |
| Surfboard-tg-mixed | 0.669 | 0.592 | 71 | 7470 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4206 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 207 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5115 | observe |
| Epodonios-all | 0.255 | None | 0 | 7938 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9093 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5979 | observe |
| barry-far-vless | 0.255 | None | 0 | 6195 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 27 |
| geo | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 12 |
| speed | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
