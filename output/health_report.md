# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-06 15:19:38 |
| 运行耗时 | 300.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94591 |
| 去重后节点 | 24561 |
| TCP 可达 | 3000 |
| 真实可用 | 488 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24561 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 41.0 |
| probe | 87.6 |
| real_test | 118.4 |
| generate | 44.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59022 |
| vmess | 12855 |
| shadowsocks | 11277 |
| trojan | 9058 |
| hysteria2 | 2001 |
| http | 138 |
| shadowsocksr | 127 |
| socks | 62 |
| hysteria | 19 |
| anytls | 18 |
| tuic | 14 |

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
| 80.69 | shadowsocks | 236.2 | 565.0 | 22.31 | 0.0 | 10.0 | 14.08 | 18.3 | Au1rxx-base64 | 149.22.95.183 |
| 80.37 | vless | 197.3 | 504.9 | 23.21 | 0.0 | 8.84 | 10.02 | 18.3 | Au1rxx-base64 | 23.94.227.94 |
| 79.9 | shadowsocks | 201.4 | 484.0 | 23.12 | 0.0 | 8.9 | 14.08 | 18.3 | Au1rxx-base64 | 108.181.0.177 |
| 79.82 | shadowsocks | 196.2 | 474.4 | 23.24 | 0.0 | 10.0 | 14.08 | 17.0 | Surfboard-tg-mixed | 108.181.118.10 |
| 79.62 | vless | 228.1 | 587.0 | 22.5 | 0.0 | 8.8 | 10.02 | 18.3 | Au1rxx-base64 | 38.209.125.45 |
| 79.62 | vless | 230.3 | 605.5 | 22.45 | 0.0 | 8.85 | 10.02 | 18.3 | Au1rxx-base64 | 172.235.38.85 |
| 78.42 | hysteria2 | 211.5 | 532.7 | 22.88 | 0.0 | 8.95 | 14.29 | 18.3 | Au1rxx-base64 | 66.94.121.46 |
| 78.04 | shadowsocks | 296.4 | 682.4 | 20.92 | 0.0 | 8.83 | 14.08 | 18.3 | Au1rxx-base64 | 173.244.56.9 |
| 77.91 | vless | 314.0 | 822.7 | 20.51 | 0.0 | 9.08 | 10.02 | 18.3 | Au1rxx-base64 | 15.204.97.216 |
| 77.76 | vless | 308.3 | 827.2 | 20.64 | 0.0 | 8.8 | 10.02 | 18.3 | Au1rxx-base64 | 216.167.94.71 |
| 76.61 | http | 309.5 | 823.4 | 20.61 | 0.0 | 10.0 | 12.22 | 16.78 | zhangkai | 138.199.35.198 |
| 76.59 | vless | 194.7 | 500.7 | 23.27 | 0.0 | 10.0 | 10.02 | 18.3 | Au1rxx-base64 | 104.194.74.73 |
| 75.83 | vless | 227.4 | 596.7 | 22.51 | 0.0 | 10.0 | 10.02 | 18.3 | Au1rxx-base64 | 172.236.233.59 |
| 75.51 | vless | 284.1 | 297.2 | 21.2 | 3.86 | 9.9 | 10.02 | 17.0 | Surfboard-tg-mixed | 31.76.91.72 |
| 74.97 | vless | 311.9 | 824.1 | 20.56 | 0.0 | 9.09 | 10.02 | 18.3 | Au1rxx-base64 | 15.204.97.214 |
| 74.79 | vless | 272.3 | 525.4 | 21.47 | 0.0 | 10.0 | 10.02 | 18.3 | Au1rxx-base64 | 31.58.50.200 |
| 74.46 | vless | 452.5 | 1226.6 | 17.3 | 0.0 | 8.84 | 10.02 | 18.3 | Au1rxx-base64 | 51.81.203.63 |
| 74.36 | shadowsocks | 301.5 | 666.1 | 20.8 | 0.0 | 10.0 | 14.08 | 17.0 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.09 | vless | 255.8 | 556.6 | 21.86 | 0.0 | 10.0 | 10.02 | 17.0 | Surfboard-tg-mixed | 172.67.213.31 |
| 74.02 | shadowsocks | 310.6 | 241.2 | 20.59 | 5.95 | 9.95 | 14.08 | 17.0 | Surfboard-tg-mixed | 45.32.16.53 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | 0.894 | 348 | 1876 | prefer |
| Surfboard-tg-mixed | 0.835 | 0.758 | 161 | 7393 | prefer |
| mheidari-all | 0.789 | 0.717 | 53 | 21148 | prefer |
| DeltaKronecker-all | 0.529 | 0.857 | 7 | 5856 | observe |
| zhangkai | 0.46 | 0.45 | 20 | 144 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 5750 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4791 | observe |
| Epodonios-all | 0.255 | None | 0 | 7776 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8812 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6147 | observe |
| barry-far-vless | 0.255 | None | 0 | 6226 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4111 | observe |
| Au1rxx-clash | 0.25 | None | 0 | 1876 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 20 |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 15 |
| 204 | ProxyConnectionError | - | 14 |
| geo | ClientOSError | - | 12 |
| speed | TimeoutError | - | 8 |
| 204 | ProxyError | - | 7 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
