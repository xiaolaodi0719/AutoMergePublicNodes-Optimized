# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 21:34:28 |
| 运行耗时 | 528.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 94587 |
| 去重后节点 | 26417 |
| TCP 可达 | 3000 |
| 真实可用 | 347 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26417 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 44.5 |
| probe | 203.7 |
| real_test | 190.1 |
| generate | 81.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56389 |
| vmess | 16877 |
| shadowsocks | 11682 |
| trojan | 8110 |
| hysteria2 | 1140 |
| shadowsocksr | 163 |
| http | 97 |
| socks | 70 |
| anytls | 36 |
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
| 79.81 | hysteria2 | 270.3 | 676.9 | 21.52 | 0.0 | 9.07 | 12.5 | 18.22 | Au1rxx-base64 | 129.213.91.185 |
| 79.45 | shadowsocks | 235.9 | 605.7 | 22.32 | 0.0 | 9.08 | 13.83 | 18.22 | Au1rxx-base64 | 156.146.38.168 |
| 79.06 | shadowsocks | 242.5 | 584.5 | 22.16 | 0.0 | 10.0 | 13.83 | 17.6 | mheidari-all | 156.146.38.170 |
| 78.25 | shadowsocks | 289.7 | 739.3 | 21.07 | 0.0 | 9.13 | 13.83 | 18.22 | Au1rxx-base64 | 156.146.38.167 |
| 77.53 | shadowsocks | 249.6 | 609.5 | 22.0 | 0.0 | 10.0 | 13.83 | 15.7 | Surfboard-tg-mixed | 156.146.38.169 |
| 76.62 | shadowsocks | 296.6 | 714.5 | 20.91 | 0.0 | 9.09 | 13.83 | 18.22 | Au1rxx-base64 | 37.19.198.236 |
| 76.48 | vless | 336.3 | 724.7 | 19.99 | 0.0 | 9.15 | 11.42 | 18.22 | Au1rxx-base64 | 169.40.42.225 |
| 75.97 | vless | 288.4 | 572.4 | 21.1 | 0.0 | 9.26 | 11.42 | 18.22 | Au1rxx-base64 | 45.63.53.81 |
| 75.56 | vless | 296.2 | 737.0 | 20.92 | 0.0 | 10.0 | 11.42 | 18.22 | Au1rxx-base64 | 162.35.126.130 |
| 75.07 | vless | 417.1 | 1045.5 | 18.12 | 0.0 | 9.24 | 11.42 | 18.22 | Au1rxx-base64 | 185.95.231.156 |
| 74.69 | shadowsocks | 288.0 | 602.1 | 21.11 | 0.0 | 10.0 | 13.83 | 18.22 | Au1rxx-base64 | 173.244.56.9 |
| 74.58 | vless | 330.3 | 710.9 | 20.13 | 0.0 | 9.2 | 11.42 | 18.22 | Au1rxx-base64 | 167.17.69.171 |
| 74.51 | shadowsocks | 314.5 | 725.7 | 20.5 | 0.0 | 10.0 | 13.83 | 18.22 | Au1rxx-base64 | 15.204.246.132 |
| 74.34 | vless | 413.4 | 902.1 | 18.21 | 0.0 | 9.28 | 11.42 | 18.22 | Au1rxx-base64 | 169.40.42.74 |
| 74.01 | vless | 356.2 | 804.3 | 19.53 | 0.0 | 9.2 | 11.42 | 18.22 | Au1rxx-base64 | 66.70.179.198 |
| 73.92 | vless | 333.8 | 810.3 | 20.05 | 0.0 | 8.73 | 11.42 | 18.22 | Au1rxx-base64 | uspanel.unixzone.us |
| 73.87 | vless | 319.1 | 621.3 | 20.39 | 0.0 | 9.16 | 11.42 | 18.22 | Au1rxx-base64 | 154.29.145.196 |
| 73.82 | vless | 391.3 | 788.4 | 18.72 | 0.0 | 10.0 | 11.42 | 18.22 | Au1rxx-base64 | 154.12.38.159 |
| 73.7 | vless | 327.1 | 608.3 | 20.2 | 0.0 | 9.16 | 11.42 | 18.22 | Au1rxx-base64 | 44.248.233.99 |
| 73.53 | hysteria2 | 283.5 | 634.6 | 21.22 | 0.0 | 9.15 | 12.5 | 18.22 | Au1rxx-base64 | 66.94.121.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.893 | 0.822 | 73 | 23621 | prefer |
| Au1rxx-base64 | 0.887 | 0.832 | 256 | 1438 | prefer |
| Surfboard-tg-mixed | 0.808 | 0.734 | 79 | 6945 | prefer |
| tg-oneclickvpnkeys | 0.403 | 1.0 | 4 | 74 | observe |
| zhangkai | 0.346 | 0.333 | 27 | 31 | observe |
| DeltaKronecker-all | 0.324 | 0.375 | 8 | 3519 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| Epodonios-all | 0.255 | None | 0 | 7425 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9871 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5487 | observe |
| barry-far-vless | 0.255 | None | 0 | 5701 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 18 |
| speed | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 15 |
| speed | ClientOSError | - | 13 |
| 204 | ProxyError | - | 12 |
| 204 | ProxyConnectionError | - | 7 |
| geo | ClientOSError | - | 7 |
| geo | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 293 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
