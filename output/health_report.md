# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 10:36:45 |
| 运行耗时 | 763.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99304 |
| 去重后节点 | 27773 |
| TCP 可达 | 3000 |
| 真实可用 | 443 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27773 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.5 |
| tcp | 49.1 |
| probe | 347.3 |
| real_test | 279.8 |
| generate | 81.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58103 |
| vmess | 16599 |
| shadowsocks | 12041 |
| trojan | 10223 |
| hysteria2 | 1343 |
| http | 717 |
| shadowsocksr | 168 |
| socks | 61 |
| anytls | 26 |
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
| 83.28 | hysteria2 | 273.5 | 711.7 | 21.45 | 0.0 | 10.0 | 14.25 | 19.08 | Au1rxx-base64 | 129.213.91.185 |
| 81.57 | shadowsocks | 234.3 | 601.2 | 22.35 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 156.146.38.169 |
| 81.52 | shadowsocks | 236.8 | 607.9 | 22.3 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 156.146.38.167 |
| 81.36 | shadowsocks | 243.4 | 595.6 | 22.14 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 156.146.38.168 |
| 81.17 | hysteria2 | 320.9 | 627.8 | 20.35 | 0.0 | 10.0 | 14.25 | 19.08 | Au1rxx-base64 | 66.94.121.46 |
| 81.12 | shadowsocks | 254.1 | 629.4 | 21.9 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 156.146.38.170 |
| 80.62 | vless | 255.0 | 653.8 | 21.88 | 0.0 | 10.0 | 9.66 | 19.08 | Au1rxx-base64 | 195.211.98.43 |
| 80.35 | vless | 266.4 | 665.7 | 21.61 | 0.0 | 10.0 | 9.66 | 19.08 | Au1rxx-base64 | 147.45.60.160 |
| 78.8 | shadowsocks | 300.3 | 755.5 | 20.83 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 37.19.198.160 |
| 78.63 | shadowsocks | 305.5 | 745.8 | 20.71 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 37.19.198.236 |
| 78.54 | shadowsocks | 332.7 | 833.1 | 20.08 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 37.19.198.243 |
| 77.89 | shadowsocks | 371.5 | 933.8 | 19.18 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 37.19.198.244 |
| 76.32 | shadowsocks | 371.7 | 936.0 | 19.17 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 15.204.247.206 |
| 75.55 | vless | 325.3 | 759.0 | 20.25 | 0.0 | 9.02 | 9.66 | 19.08 | Au1rxx-base64 | 195.123.235.183 |
| 75.42 | vless | 285.1 | 686.9 | 21.18 | 0.0 | 10.0 | 9.66 | 19.08 | Au1rxx-base64 | 69.48.201.136 |
| 75.41 | shadowsocks | 295.2 | 631.0 | 20.94 | 0.0 | 10.0 | 14.14 | 19.08 | Au1rxx-base64 | 173.244.56.9 |
| 75.4 | vless | 384.3 | 923.7 | 18.88 | 0.0 | 10.0 | 9.66 | 19.08 | Au1rxx-base64 | 159.89.87.21 |
| 75.07 | vless | 407.5 | 1034.4 | 18.35 | 0.0 | 10.0 | 9.66 | 19.08 | Au1rxx-base64 | 185.95.231.156 |
| 74.78 | vless | 337.4 | 738.1 | 19.97 | 0.0 | 10.0 | 9.66 | 19.08 | Au1rxx-base64 | 167.17.69.171 |
| 74.53 | vless | 301.3 | 586.5 | 20.8 | 0.0 | 8.89 | 9.66 | 19.08 | Au1rxx-base64 | 154.29.159.211 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.923 | 0.845 | 451 | 1994 | prefer |
| ermaozi | 0.607 | 0.582 | 55 | 702 | observe |
| Surfboard-tg-mixed | 0.493 | 0.409 | 44 | 7171 | observe |
| mheidari-all | 0.446 | 0.625 | 8 | 23828 | observe |
| ermaozi-get_subscribe | 0.279 | 1.0 | 1 | 601 | observe |
| DeltaKronecker-all | 0.259 | 0.162 | 37 | 4999 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1994 | observe |
| Epodonios-all | 0.255 | None | 0 | 7611 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9902 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5617 | observe |
| barry-far-vless | 0.255 | None | 0 | 5842 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 44 |
| 204 | ProxyError | - | 28 |
| geo | ClientOSError | - | 18 |
| speed | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 15 |
| speed | TimeoutError | - | 14 |
| geo | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
