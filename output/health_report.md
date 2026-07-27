# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-27 03:43:08 |
| 运行耗时 | 380.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83507 |
| 去重后节点 | 22089 |
| TCP 可达 | 3000 |
| 真实可用 | 978 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22089 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 0.9 |
| tcp | 31.6 |
| probe | 75.5 |
| real_test | 232.5 |
| generate | 33.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46240 |
| trojan | 15466 |
| shadowsocks | 10588 |
| vmess | 10270 |
| hysteria2 | 613 |
| shadowsocksr | 106 |
| socks | 93 |
| http | 84 |
| anytls | 22 |
| hysteria | 13 |
| tuic | 12 |

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
| 79.57 | shadowsocks | 213.6 | 567.2 | 22.83 | 0.0 | 10.0 | 11.56 | 19.18 | Au1rxx-base64 | 149.22.95.183 |
| 76.1 | trojan | 306.9 | 315.5 | 20.67 | 3.17 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 31.223.184.109 |
| 75.98 | trojan | 308.2 | 319.0 | 20.64 | 3.04 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 95.85.94.96 |
| 75.91 | trojan | 308.4 | 319.4 | 20.64 | 3.02 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 31.223.184.164 |
| 75.9 | trojan | 307.5 | 320.4 | 20.66 | 2.99 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 31.223.184.149 |
| 75.79 | trojan | 309.0 | 321.3 | 20.62 | 2.95 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 95.85.94.148 |
| 75.74 | trojan | 307.3 | 320.3 | 20.66 | 2.99 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 95.85.94.112 |
| 75.08 | trojan | 307.2 | 316.7 | 20.67 | 3.12 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 31.223.184.249 |
| 74.71 | trojan | 307.0 | 309.4 | 20.67 | 3.4 | 8.41 | 12.79 | 19.18 | Au1rxx-base64 | inspired-hound.rooster465.autos |
| 74.06 | trojan | 307.2 | 315.8 | 20.67 | 3.16 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 95.85.94.137 |
| 73.91 | trojan | 309.2 | 316.7 | 20.62 | 3.12 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 31.223.184.172 |
| 73.8 | trojan | 326.2 | 365.0 | 20.23 | 1.31 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 31.223.184.218 |
| 73.76 | trojan | 339.3 | 684.6 | 19.92 | 0.0 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 163.245.196.68 |
| 73.66 | shadowsocks | 278.3 | 333.0 | 21.33 | 2.51 | 10.0 | 11.56 | 19.18 | Au1rxx-base64 | 149.22.87.240 |
| 73.41 | trojan | 327.1 | 374.9 | 20.21 | 0.94 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 95.85.94.165 |
| 73.13 | shadowsocks | 315.9 | 676.1 | 20.47 | 0.0 | 10.0 | 11.56 | 19.18 | Au1rxx-base64 | 156.146.38.170 |
| 73.12 | trojan | 328.9 | 380.7 | 20.16 | 0.72 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 31.223.184.238 |
| 73.12 | trojan | 330.7 | 379.3 | 20.12 | 0.78 | 10.0 | 12.79 | 19.18 | Au1rxx-base64 | 31.223.184.82 |
| 73.0 | shadowsocks | 254.7 | 562.1 | 21.88 | 0.0 | 10.0 | 11.56 | 19.18 | Au1rxx-base64 | 173.244.56.6 |
| 72.74 | shadowsocks | 313.4 | 651.4 | 20.52 | 0.0 | 10.0 | 11.56 | 19.18 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 1.0 | 76 | 86 | prefer |
| Au1rxx-base64 | 0.987 | 0.93 | 554 | 1476 | prefer |
| Surfboard-tg-mixed | 0.554 | 0.474 | 114 | 5483 | observe |
| DeltaKronecker-all | 0.529 | 0.448 | 67 | 4320 | observe |
| mheidari-all | 0.519 | 0.439 | 668 | 19312 | observe |
| tg-oneclickvpnkeys | 0.483 | 1.0 | 6 | 149 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3959 | observe |
| tg-Farah_VPN | 0.263 | 1.0 | 1 | 200 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6493 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3963 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6284 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4173 | observe |
| barry-far-vless | 0.255 | None | 0 | 4841 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5003 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 193 |
| speed | ClientOSError | - | 179 |
| speed | TimeoutError | - | 50 |
| geo | ClientOSError | - | 42 |
| cn-block | TimeoutError | - | 24 |
| 204 | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
