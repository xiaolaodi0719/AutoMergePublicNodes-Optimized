# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 17:04:36 |
| 运行耗时 | 532.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97420 |
| 去重后节点 | 26475 |
| TCP 可达 | 3000 |
| 真实可用 | 379 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26475 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 43.5 |
| probe | 231.3 |
| real_test | 168.6 |
| generate | 82.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59595 |
| vmess | 15139 |
| shadowsocks | 11280 |
| trojan | 8912 |
| hysteria2 | 1600 |
| http | 599 |
| shadowsocksr | 170 |
| socks | 76 |
| anytls | 27 |
| hysteria | 15 |
| tuic | 7 |

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
| 83.68 | vless | 260.3 | 614.8 | 21.75 | 0.0 | 9.85 | 12.54 | 19.54 | Au1rxx-base64 | 195.211.98.43 |
| 82.39 | vless | 298.2 | 740.3 | 20.87 | 0.0 | 9.85 | 12.54 | 19.54 | Au1rxx-base64 | 79.141.172.154 |
| 79.32 | vless | 444.9 | 1128.3 | 17.48 | 0.0 | 9.83 | 12.54 | 19.54 | Au1rxx-base64 | 198.251.78.29 |
| 79.23 | vless | 356.1 | 798.2 | 19.53 | 0.0 | 10.0 | 12.54 | 19.54 | Au1rxx-base64 | 195.123.235.177 |
| 78.5 | vless | 411.5 | 1010.3 | 18.25 | 0.0 | 9.85 | 12.54 | 19.54 | Au1rxx-base64 | 169.40.42.235 |
| 78.41 | vless | 332.6 | 765.2 | 20.08 | 0.0 | 9.86 | 12.54 | 19.54 | Au1rxx-base64 | 169.40.42.15 |
| 78.19 | vless | 291.1 | 585.9 | 21.04 | 0.0 | 9.84 | 12.54 | 19.54 | Au1rxx-base64 | 192.3.247.109 |
| 78.01 | shadowsocks | 350.2 | 893.0 | 19.67 | 0.0 | 9.84 | 13.46 | 19.54 | Au1rxx-base64 | 185.156.47.97 |
| 77.96 | vless | 402.5 | 943.7 | 18.46 | 0.0 | 9.85 | 12.54 | 19.54 | Au1rxx-base64 | 169.40.42.104 |
| 77.26 | shadowsocks | 314.2 | 747.2 | 20.5 | 0.0 | 10.0 | 13.46 | 19.54 | Au1rxx-base64 | 37.19.198.243 |
| 77.23 | vless | 277.1 | 556.8 | 21.36 | 0.0 | 10.0 | 12.54 | 18.02 | mheidari-all | 47.251.108.158 |
| 77.2 | vless | 364.5 | 750.5 | 19.34 | 0.0 | 9.86 | 12.54 | 19.54 | Au1rxx-base64 | 169.40.42.16 |
| 77.11 | vless | 391.7 | 771.9 | 18.71 | 0.0 | 9.85 | 12.54 | 19.54 | Au1rxx-base64 | 169.40.42.35 |
| 76.98 | vless | 416.2 | 1014.6 | 18.14 | 0.0 | 9.89 | 12.54 | 19.54 | Au1rxx-base64 | 185.95.231.233 |
| 76.96 | shadowsocks | 310.7 | 750.4 | 20.58 | 0.0 | 10.0 | 13.46 | 18.02 | mheidari-all | 37.19.198.236 |
| 76.92 | vless | 291.5 | 576.7 | 21.03 | 0.0 | 9.83 | 12.54 | 19.54 | Au1rxx-base64 | 172.235.43.210 |
| 76.91 | vless | 340.0 | 761.2 | 19.91 | 0.0 | 9.85 | 12.54 | 19.54 | Au1rxx-base64 | 169.40.42.225 |
| 76.46 | vless | 385.1 | 872.9 | 18.86 | 0.0 | 9.88 | 12.54 | 19.54 | Au1rxx-base64 | 5.78.159.214 |
| 76.14 | vless | 428.9 | 944.6 | 17.85 | 0.0 | 9.83 | 12.54 | 19.54 | Au1rxx-base64 | 169.40.42.75 |
| 76.13 | vless | 413.5 | 902.1 | 18.21 | 0.0 | 9.83 | 12.54 | 19.54 | Au1rxx-base64 | 169.40.42.163 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.959 | 0.894 | 263 | 1699 | prefer |
| Surfboard-tg-mixed | 0.784 | 0.712 | 52 | 7258 | prefer |
| DeltaKronecker-all | 0.629 | 1.0 | 8 | 5452 | observe |
| mheidari-all | 0.623 | 0.544 | 160 | 22782 | observe |
| ermaozi | 0.473 | 0.474 | 19 | 304 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 176 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 67 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7757 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9237 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5857 | observe |
| barry-far-vless | 0.255 | None | 0 | 6083 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4324 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 42 |
| 204 | TimeoutError | - | 29 |
| 204 | ProxyError | - | 24 |
| cn-block | TimeoutError | - | 16 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
