# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-22 01:33:06 |
| 运行耗时 | 324.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 92902 |
| 去重后节点 | 23044 |
| TCP 可达 | 3000 |
| 真实可用 | 790 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23044 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.0 |
| tcp | 39.2 |
| probe | 57.5 |
| real_test | 179.1 |
| generate | 40.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50858 |
| trojan | 19042 |
| shadowsocks | 10578 |
| vmess | 10297 |
| hysteria2 | 1570 |
| shadowsocksr | 207 |
| http | 167 |
| socks | 123 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 13 |

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
| 83.9 | vless | 220.9 | 605.2 | 22.66 | 0.0 | 10.0 | 11.24 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 83.83 | vless | 224.1 | 609.4 | 22.59 | 0.0 | 10.0 | 11.24 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 83.21 | vless | 250.7 | 648.2 | 21.97 | 0.0 | 10.0 | 11.24 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 81.44 | shadowsocks | 238.2 | 621.2 | 22.26 | 0.0 | 10.0 | 13.43 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 81.4 | shadowsocks | 251.1 | 611.3 | 21.97 | 0.0 | 10.0 | 13.43 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 81.39 | shadowsocks | 251.2 | 621.6 | 21.96 | 0.0 | 10.0 | 13.43 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.29 | vless | 300.2 | 718.8 | 20.83 | 0.0 | 10.0 | 11.24 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 81.17 | trojan | 352.8 | 875.2 | 19.61 | 0.0 | 10.0 | 14.9 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 80.73 | shadowsocks | 264.0 | 662.3 | 21.67 | 0.0 | 10.0 | 13.43 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 80.63 | vless | 232.8 | 590.4 | 22.39 | 0.0 | 10.0 | 11.24 | 20.0 | Au1rxx-base64 | 154.40.137.160 |
| 80.56 | shadowsocks | 287.4 | 732.2 | 21.13 | 0.0 | 10.0 | 13.43 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 80.22 | shadowsocks | 258.9 | 644.1 | 21.79 | 0.0 | 10.0 | 13.43 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 80.1 | vless | 279.1 | 679.1 | 21.32 | 0.0 | 10.0 | 11.24 | 20.0 | Au1rxx-base64 | 179.255.185.74 |
| 79.79 | trojan | 264.6 | 615.1 | 21.65 | 0.0 | 10.0 | 14.9 | 17.32 | mheidari-all | 64.94.95.114 |
| 79.7 | vless | 239.7 | 633.7 | 22.23 | 0.0 | 10.0 | 11.24 | 17.32 | mheidari-all | 67.220.73.204 |
| 79.45 | vless | 343.4 | 845.4 | 19.83 | 0.0 | 10.0 | 11.24 | 20.0 | Au1rxx-base64 | 130.107.73.148 |
| 79.26 | vless | 374.1 | 998.1 | 19.12 | 0.0 | 10.0 | 11.24 | 20.0 | Au1rxx-base64 | 45.138.100.226 |
| 79.24 | vless | 306.5 | 857.9 | 20.68 | 0.0 | 10.0 | 11.24 | 17.32 | mheidari-all | 195.211.99.45 |
| 78.86 | trojan | 279.9 | 661.2 | 21.3 | 0.0 | 10.0 | 14.9 | 17.32 | mheidari-all | 64.94.95.115 |
| 78.71 | vless | 327.9 | 745.2 | 20.19 | 0.0 | 10.0 | 11.24 | 20.0 | Au1rxx-base64 | 107.151.201.59 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.93 | 330 | 1933 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| Surfboard-tg-mixed | 0.878 | 0.8 | 250 | 6361 | prefer |
| mheidari-all | 0.457 | 0.376 | 436 | 21889 | observe |
| DeltaKronecker-all | 0.337 | 0.429 | 7 | 4245 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 162 | observe |
| 10ium-ScrapeCategorize-Vless | 0.259 | 0.333 | 3 | 5148 | observe |
| Pawdroid | 0.256 | 1.0 | 1 | 20 | observe |
| Epodonios-all | 0.255 | None | 0 | 7089 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3985 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7133 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5127 | observe |
| barry-far-vless | 0.255 | None | 0 | 5449 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4091 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 131 |
| geo | ClientOSError | - | 91 |
| speed | TimeoutError | - | 81 |
| speed | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 8 |
| 204 | ProxyError | - | 5 |
| 204 | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
