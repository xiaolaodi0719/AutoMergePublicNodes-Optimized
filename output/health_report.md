# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 04:26:58 |
| 运行耗时 | 640.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94708 |
| 去重后节点 | 26191 |
| TCP 可达 | 3000 |
| 真实可用 | 390 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26191 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 43.9 |
| probe | 237.9 |
| real_test | 267.7 |
| generate | 82.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56637 |
| vmess | 17050 |
| shadowsocks | 11244 |
| trojan | 7995 |
| hysteria2 | 1214 |
| http | 276 |
| shadowsocksr | 168 |
| socks | 67 |
| anytls | 34 |
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
| 81.07 | vless | 255.1 | 670.2 | 21.87 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 159.89.87.21 |
| 80.22 | vless | 292.1 | 719.9 | 21.02 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 66.70.179.198 |
| 78.94 | vless | 347.4 | 909.3 | 19.74 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 169.40.42.168 |
| 78.91 | vless | 348.4 | 913.8 | 19.71 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 169.40.42.104 |
| 78.91 | vless | 348.4 | 939.6 | 19.71 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 185.95.231.156 |
| 78.49 | vless | 271.6 | 646.0 | 21.49 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 195.211.98.43 |
| 77.72 | vless | 369.7 | 916.4 | 19.22 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 169.40.42.235 |
| 77.68 | shadowsocks | 261.1 | 712.2 | 21.73 | 0.0 | 8.76 | 13.15 | 18.04 | Au1rxx-base64 | 37.19.198.236 |
| 77.62 | vless | 355.6 | 828.0 | 19.55 | 0.0 | 8.87 | 11.16 | 18.04 | Au1rxx-base64 | 169.40.42.74 |
| 77.28 | vless | 369.7 | 989.9 | 19.22 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 169.40.42.231 |
| 77.25 | vless | 420.0 | 1146.2 | 18.05 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 167.17.69.171 |
| 76.91 | shadowsocks | 261.6 | 709.0 | 21.72 | 0.0 | 10.0 | 13.15 | 18.04 | Au1rxx-base64 | 37.19.198.243 |
| 76.61 | vless | 447.7 | 1092.9 | 17.41 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 169.40.42.163 |
| 76.11 | shadowsocks | 274.8 | 637.5 | 21.42 | 0.0 | 10.0 | 13.15 | 18.04 | Au1rxx-base64 | 156.146.38.169 |
| 75.98 | vless | 371.5 | 927.2 | 19.18 | 0.0 | 10.0 | 11.16 | 18.04 | Au1rxx-base64 | 209.200.246.148 |
| 75.55 | shadowsocks | 296.4 | 696.2 | 20.92 | 0.0 | 10.0 | 13.15 | 17.34 | mheidari-all | 156.146.38.170 |
| 75.22 | hysteria2 | 353.9 | 674.1 | 19.59 | 0.0 | 8.83 | 14.06 | 18.04 | Au1rxx-base64 | 66.94.121.46 |
| 74.8 | vless | 321.8 | 843.4 | 20.33 | 0.0 | 8.83 | 11.16 | 18.04 | Au1rxx-base64 | 169.40.42.35 |
| 74.76 | shadowsocks | 283.6 | 644.9 | 21.21 | 0.0 | 8.85 | 13.15 | 18.04 | Au1rxx-base64 | 156.146.38.168 |
| 74.71 | trojan | 448.2 | 1249.5 | 17.4 | 0.0 | 8.83 | 13.44 | 18.04 | Au1rxx-base64 | 69.164.240.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.988 | 0.919 | 74 | 6911 | prefer |
| Au1rxx-base64 | 0.874 | 0.819 | 287 | 1424 | prefer |
| zhangkai | 0.819 | 0.85 | 20 | 27 | prefer |
| mheidari-all | 0.476 | 0.395 | 147 | 23317 | observe |
| ermaozi-get_subscribe | 0.354 | 0.323 | 31 | 510 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| Epodonios-all | 0.255 | None | 0 | 7516 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10162 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5797 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| DeltaKronecker-all | 0.239 | 0.167 | 12 | 3294 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 64 |
| geo | ClientOSError | - | 22 |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyConnectionError | - | 16 |
| 204 | ProxyError | - | 15 |
| speed | ClientOSError | - | 13 |
| speed | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
