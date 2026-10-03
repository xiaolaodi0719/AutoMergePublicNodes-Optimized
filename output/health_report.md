# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 04:53:51 |
| 运行耗时 | 723.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98934 |
| 去重后节点 | 27176 |
| TCP 可达 | 3000 |
| 真实可用 | 453 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27176 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.1 |
| tcp | 47.5 |
| probe | 257.8 |
| real_test | 336.6 |
| generate | 73.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60524 |
| vmess | 15585 |
| shadowsocks | 11421 |
| trojan | 8975 |
| hysteria2 | 1616 |
| http | 522 |
| shadowsocksr | 164 |
| socks | 68 |
| anytls | 30 |
| hysteria | 17 |
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
| 81.99 | hysteria2 | 250.0 | 551.8 | 21.99 | 0.0 | 10.0 | 12.35 | 19.28 | Au1rxx-base64 | 192.255.128.123 |
| 81.61 | vless | 269.1 | 592.9 | 21.55 | 0.0 | 10.0 | 12.8 | 19.28 | Au1rxx-base64 | 15.204.97.216 |
| 81.45 | shadowsocks | 238.6 | 609.4 | 22.25 | 0.0 | 10.0 | 13.92 | 19.28 | Au1rxx-base64 | 156.146.38.167 |
| 81.41 | shadowsocks | 240.7 | 616.1 | 22.21 | 0.0 | 10.0 | 13.92 | 19.28 | Au1rxx-base64 | 156.146.38.170 |
| 80.91 | vless | 256.9 | 572.6 | 21.83 | 0.0 | 10.0 | 12.8 | 19.28 | Au1rxx-base64 | 140.150.227.51 |
| 80.43 | vless | 275.4 | 587.1 | 21.4 | 0.0 | 10.0 | 12.8 | 19.28 | Au1rxx-base64 | 172.235.43.210 |
| 80.3 | vless | 245.5 | 607.3 | 22.09 | 0.0 | 8.13 | 12.8 | 19.28 | Au1rxx-base64 | us51.mech-pro.online |
| 80.22 | vless | 316.4 | 698.0 | 20.45 | 0.0 | 10.0 | 12.8 | 19.28 | Au1rxx-base64 | 198.251.78.29 |
| 80.07 | vless | 271.9 | 575.2 | 21.48 | 0.0 | 10.0 | 12.8 | 19.28 | Au1rxx-base64 | 172.233.139.46 |
| 79.84 | vless | 280.3 | 544.7 | 21.29 | 0.0 | 10.0 | 12.8 | 19.28 | Au1rxx-base64 | 137.175.82.40 |
| 79.79 | shadowsocks | 241.5 | 560.1 | 22.19 | 0.0 | 10.0 | 13.92 | 19.14 | Surfboard-tg-mixed | 5.78.51.123 |
| 79.39 | shadowsocks | 241.2 | 622.1 | 22.19 | 0.0 | 10.0 | 13.92 | 19.28 | Au1rxx-base64 | 156.146.38.168 |
| 79.06 | vless | 263.5 | 549.9 | 21.68 | 0.0 | 10.0 | 12.8 | 19.14 | Surfboard-tg-mixed | 2.27.160.4 |
| 78.7 | http | 250.7 | 568.7 | 21.97 | 0.0 | 10.0 | 13.85 | 18.28 | ermaozi | 138.199.35.216 |
| 78.41 | vless | 275.6 | 591.7 | 21.4 | 0.0 | 10.0 | 12.8 | 19.28 | Au1rxx-base64 | 172.235.38.85 |
| 78.33 | shadowsocks | 244.0 | 628.1 | 22.13 | 0.0 | 10.0 | 13.92 | 19.28 | Au1rxx-base64 | 156.146.38.169 |
| 78.05 | vless | 342.9 | 538.6 | 19.84 | 0.0 | 10.0 | 12.8 | 19.28 | Au1rxx-base64 | 195.123.240.65 |
| 78.02 | hysteria2 | 328.7 | 740.0 | 20.17 | 0.0 | 10.0 | 12.35 | 19.12 | mheidari-all | 159.223.157.129 |
| 76.93 | vless | 459.2 | 1144.1 | 17.15 | 0.0 | 10.0 | 12.8 | 19.28 | Au1rxx-base64 | 51.81.203.63 |
| 76.57 | shadowsocks | 273.5 | 538.8 | 21.45 | 0.0 | 10.0 | 13.92 | 19.28 | Au1rxx-base64 | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.96 | 0.893 | 271 | 1751 | prefer |
| ermaozi | 0.767 | 0.76 | 25 | 645 | prefer |
| Surfboard-tg-mixed | 0.756 | 0.678 | 183 | 7256 | prefer |
| mheidari-all | 0.364 | 0.282 | 216 | 23323 | observe |
| DeltaKronecker-all | 0.352 | 0.5 | 6 | 4981 | observe |
| ermaozi-get_subscribe | 0.341 | 0.75 | 4 | 516 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5276 | observe |
| Epodonios-all | 0.255 | None | 0 | 7743 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9351 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5980 | observe |
| barry-far-vless | 0.255 | None | 0 | 6214 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4357 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 109 |
| speed | TimeoutError | - | 47 |
| cn-block | TimeoutError | - | 23 |
| geo | ClientOSError | - | 20 |
| 204 | TimeoutError | - | 17 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 10 |
| 204 | ProxyConnectionError | - | 4 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
