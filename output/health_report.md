# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-07 13:10:01 |
| 运行耗时 | 601.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98660 |
| 去重后节点 | 27303 |
| TCP 可达 | 3000 |
| 真实可用 | 418 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27303 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.4 |
| tcp | 46.3 |
| probe | 237.8 |
| real_test | 233.6 |
| generate | 77.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57832 |
| vmess | 15977 |
| shadowsocks | 11587 |
| trojan | 10877 |
| hysteria2 | 1463 |
| http | 610 |
| shadowsocksr | 161 |
| socks | 92 |
| anytls | 34 |
| hysteria | 17 |
| tuic | 10 |

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
| 81.88 | shadowsocks | 193.1 | 478.8 | 23.31 | 0.0 | 10.0 | 13.75 | 19.32 | Au1rxx-base64 | 108.181.0.177 |
| 81.65 | shadowsocks | 203.0 | 482.5 | 23.08 | 0.0 | 10.0 | 13.75 | 19.32 | Au1rxx-base64 | 108.181.118.10 |
| 80.86 | shadowsocks | 256.8 | 629.5 | 21.83 | 0.0 | 10.0 | 13.75 | 19.32 | Au1rxx-base64 | 156.146.38.168 |
| 80.86 | shadowsocks | 258.6 | 632.9 | 21.79 | 0.0 | 10.0 | 13.75 | 19.32 | Au1rxx-base64 | 156.146.38.169 |
| 80.2 | shadowsocks | 248.4 | 504.1 | 22.03 | 0.0 | 10.0 | 13.75 | 19.32 | Au1rxx-base64 | 173.244.56.6 |
| 79.59 | shadowsocks | 261.9 | 618.1 | 21.72 | 0.0 | 10.0 | 13.75 | 19.32 | Au1rxx-base64 | 5.78.51.123 |
| 78.86 | hysteria2 | 266.5 | 273.8 | 21.61 | 4.73 | 9.9 | 12.39 | 19.32 | Au1rxx-base64 | 158.101.148.79 |
| 78.82 | shadowsocks | 258.7 | 625.9 | 21.79 | 0.0 | 10.0 | 13.75 | 19.32 | Au1rxx-base64 | 156.146.38.170 |
| 78.36 | hysteria2 | 264.4 | 318.2 | 21.66 | 3.07 | 9.05 | 12.39 | 19.32 | Au1rxx-base64 | open.2ml.bid |
| 78.32 | hysteria2 | 323.1 | 754.7 | 20.3 | 0.0 | 10.0 | 12.39 | 19.32 | Au1rxx-base64 | 129.213.91.185 |
| 78.15 | vless | 216.1 | 512.7 | 22.78 | 0.0 | 10.0 | 6.05 | 19.32 | Au1rxx-base64 | 47.251.108.158 |
| 77.82 | vless | 230.3 | 559.0 | 22.45 | 0.0 | 10.0 | 6.05 | 19.32 | Au1rxx-base64 | 137.175.82.40 |
| 77.56 | vless | 241.5 | 643.2 | 22.19 | 0.0 | 10.0 | 6.05 | 19.32 | Au1rxx-base64 | 107.173.237.146 |
| 77.0 | shadowsocks | 287.4 | 621.2 | 21.13 | 0.0 | 10.0 | 13.75 | 19.32 | Au1rxx-base64 | 149.22.95.183 |
| 76.76 | vless | 189.7 | 497.2 | 23.39 | 0.0 | 10.0 | 6.05 | 19.32 | Au1rxx-base64 | 154.17.1.248 |
| 76.48 | trojan | 332.5 | 740.6 | 20.08 | 0.0 | 10.0 | 12.82 | 19.32 | Au1rxx-base64 | 34.220.15.24 |
| 76.31 | shadowsocks | 284.8 | 283.2 | 21.18 | 4.38 | 9.89 | 13.75 | 19.32 | Au1rxx-base64 | 149.22.87.204 |
| 75.7 | trojan | 292.7 | 623.0 | 21.0 | 0.0 | 8.48 | 12.82 | 19.32 | Au1rxx-base64 | guided-ferret.rooster465.autos |
| 75.67 | shadowsocks | 469.3 | 1261.9 | 16.91 | 0.0 | 10.0 | 13.75 | 19.32 | Au1rxx-base64 | 156.146.38.167 |
| 75.02 | shadowsocks | 303.4 | 329.2 | 20.75 | 2.66 | 9.91 | 13.75 | 19.32 | Au1rxx-base64 | 149.22.87.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | 0.895 | 332 | 1830 | prefer |
| mheidari-all | 0.862 | 0.792 | 53 | 23381 | prefer |
| Surfboard-tg-mixed | 0.633 | 0.554 | 83 | 7069 | observe |
| ermaozi | 0.631 | 0.61 | 41 | 664 | observe |
| DeltaKronecker-all | 0.449 | 0.368 | 19 | 5344 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7480 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9550 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5616 | observe |
| barry-far-vless | 0.255 | None | 0 | 5861 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4418 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1830 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 36 |
| 204 | ProxyError | - | 24 |
| cn-block | TimeoutError | - | 21 |
| speed | ClientOSError | - | 10 |
| geo | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
