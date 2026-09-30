# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-30 12:24:13 |
| 运行耗时 | 592.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96400 |
| 去重后节点 | 26890 |
| TCP 可达 | 3000 |
| 真实可用 | 396 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26890 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.6 |
| tcp | 45.4 |
| probe | 265.6 |
| real_test | 183.7 |
| generate | 89.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58466 |
| vmess | 15245 |
| shadowsocks | 11270 |
| trojan | 9047 |
| hysteria2 | 1430 |
| http | 639 |
| shadowsocksr | 171 |
| socks | 72 |
| anytls | 37 |
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
| 78.48 | shadowsocks | 254.2 | 634.1 | 21.89 | 0.0 | 10.0 | 13.37 | 17.22 | Au1rxx-base64 | 156.146.38.167 |
| 78.02 | shadowsocks | 250.2 | 625.1 | 21.99 | 0.0 | 10.0 | 13.37 | 17.22 | Au1rxx-base64 | 156.146.38.170 |
| 77.41 | hysteria2 | 360.4 | 856.1 | 19.43 | 0.0 | 10.0 | 13.64 | 17.22 | Au1rxx-base64 | 192.255.128.123 |
| 76.85 | shadowsocks | 289.7 | 743.0 | 21.07 | 0.0 | 10.0 | 13.37 | 17.22 | Au1rxx-base64 | 37.19.198.243 |
| 76.85 | shadowsocks | 324.8 | 849.4 | 20.26 | 0.0 | 10.0 | 13.37 | 17.22 | Au1rxx-base64 | 37.19.198.236 |
| 76.58 | shadowsocks | 265.1 | 708.1 | 21.64 | 0.0 | 8.85 | 13.37 | 17.22 | Au1rxx-base64 | 185.156.47.97 |
| 76.5 | shadowsocks | 290.7 | 739.7 | 21.05 | 0.0 | 8.86 | 13.37 | 17.22 | Au1rxx-base64 | 37.19.198.160 |
| 76.47 | shadowsocks | 255.8 | 636.3 | 21.86 | 0.0 | 10.0 | 13.37 | 15.24 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.99 | shadowsocks | 312.1 | 808.0 | 20.55 | 0.0 | 8.85 | 13.37 | 17.22 | Au1rxx-base64 | 37.19.198.244 |
| 75.38 | shadowsocks | 252.6 | 636.7 | 21.93 | 0.0 | 8.86 | 13.37 | 17.22 | Au1rxx-base64 | 198.98.53.130 |
| 75.34 | hysteria2 | 296.5 | 280.5 | 20.91 | 4.48 | 7.08 | 13.64 | 17.22 | Au1rxx-base64 | open.w2m.ink |
| 75.12 | shadowsocks | 364.8 | 922.9 | 19.33 | 0.0 | 10.0 | 13.37 | 17.22 | Au1rxx-base64 | 140.82.63.79 |
| 74.66 | shadowsocks | 268.3 | 773.9 | 21.57 | 0.0 | 10.0 | 13.37 | 17.22 | Au1rxx-base64 | 66.23.204.219 |
| 73.92 | vless | 303.3 | 760.2 | 20.76 | 0.0 | 10.0 | 5.94 | 17.22 | Au1rxx-base64 | 136.0.213.120 |
| 73.43 | http | 266.5 | 668.1 | 21.61 | 0.0 | 10.0 | 12.56 | 16.76 | ermaozi | 172.64.68.89 |
| 72.63 | shadowsocks | 332.3 | 756.0 | 20.09 | 0.0 | 10.0 | 13.37 | 17.22 | Au1rxx-base64 | 108.181.57.93 |
| 71.96 | vless | 386.1 | 998.9 | 18.84 | 0.0 | 10.0 | 5.94 | 17.22 | Au1rxx-base64 | 185.95.231.156 |
| 71.95 | shadowsocks | 305.1 | 641.4 | 20.72 | 0.0 | 8.85 | 13.37 | 17.22 | Au1rxx-base64 | 149.22.95.183 |
| 71.73 | shadowsocks | 344.9 | 910.3 | 19.79 | 0.0 | 8.85 | 13.37 | 17.22 | Au1rxx-base64 | 64.74.161.148 |
| 71.51 | shadowsocks | 290.9 | 583.2 | 21.04 | 0.0 | 10.0 | 13.37 | 15.24 | Surfboard-tg-mixed | 192.3.247.109 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.87 | 0.802 | 278 | 1752 | prefer |
| mheidari-all | 0.807 | 0.736 | 53 | 22755 | prefer |
| ermaozi | 0.795 | 0.792 | 53 | 335 | prefer |
| Surfboard-tg-mixed | 0.683 | 0.604 | 134 | 6952 | observe |
| DeltaKronecker-all | 0.474 | 0.467 | 15 | 5434 | observe |
| tg-oneclickvpnkeys | 0.36 | 1.0 | 3 | 53 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 164 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7458 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9148 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5632 | observe |
| barry-far-vless | 0.255 | None | 0 | 5879 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4183 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 52 |
| 204 | TimeoutError | - | 24 |
| 204 | ProxyError | - | 17 |
| cn-block | TimeoutError | - | 15 |
| geo | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 10 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 2 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
