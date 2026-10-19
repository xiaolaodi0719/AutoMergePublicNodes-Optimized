# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 04:15:15 |
| 运行耗时 | 726.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 97333 |
| 去重后节点 | 27722 |
| TCP 可达 | 3000 |
| 真实可用 | 496 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27722 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.4 |
| tcp | 48.9 |
| probe | 266.1 |
| real_test | 320.2 |
| generate | 84.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56869 |
| vmess | 16696 |
| shadowsocks | 11624 |
| trojan | 9518 |
| hysteria2 | 1576 |
| http | 761 |
| shadowsocksr | 167 |
| socks | 70 |
| anytls | 29 |
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
| 80.96 | vless | 236.0 | 622.1 | 22.31 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 195.123.235.183 |
| 80.13 | hysteria2 | 276.0 | 798.0 | 21.39 | 0.0 | 10.0 | 12.5 | 17.74 | Au1rxx-base64 | 129.213.91.185 |
| 80.04 | vless | 275.8 | 699.1 | 21.39 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 66.70.179.198 |
| 79.84 | vless | 284.4 | 705.2 | 21.19 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.90 |
| 79.25 | vless | 310.1 | 761.6 | 20.6 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.168 |
| 79.05 | vless | 318.6 | 730.6 | 20.4 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.35 |
| 78.82 | vless | 328.5 | 899.8 | 20.17 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 185.95.231.156 |
| 78.78 | vless | 330.5 | 837.0 | 20.13 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.231 |
| 78.31 | vless | 244.1 | 659.7 | 22.13 | 0.0 | 10.0 | 10.91 | 16.24 | Surfboard-tg-mixed | 147.45.60.160 |
| 78.17 | vless | 356.8 | 921.6 | 19.52 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.89 |
| 77.99 | vless | 364.6 | 863.5 | 19.34 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.163 |
| 77.32 | vless | 393.4 | 951.1 | 18.67 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.229 |
| 77.26 | trojan | 368.2 | 1033.4 | 19.25 | 0.0 | 10.0 | 13.27 | 17.74 | Au1rxx-base64 | 69.164.240.85 |
| 76.58 | vless | 296.1 | 671.5 | 20.92 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.74 |
| 76.5 | vless | 360.5 | 929.7 | 19.43 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.104 |
| 75.81 | shadowsocks | 254.0 | 698.0 | 21.9 | 0.0 | 10.0 | 12.88 | 17.74 | Au1rxx-base64 | 198.98.53.130 |
| 75.8 | vless | 264.8 | 725.1 | 21.65 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 104.243.33.154 |
| 75.55 | vless | 253.9 | 709.6 | 21.9 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 162.35.126.130 |
| 75.37 | shadowsocks | 265.7 | 741.8 | 21.63 | 0.0 | 10.0 | 12.88 | 15.86 | mheidari-all | 37.19.198.236 |
| 75.32 | vless | 368.9 | 892.5 | 19.24 | 0.0 | 10.0 | 10.91 | 17.74 | Au1rxx-base64 | 169.40.42.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.905 | 0.838 | 396 | 1698 | prefer |
| Surfboard-tg-mixed | 0.787 | 0.711 | 114 | 7003 | prefer |
| ermaozi | 0.518 | 0.489 | 47 | 696 | observe |
| mheidari-all | 0.481 | 0.4 | 140 | 23518 | observe |
| DeltaKronecker-all | 0.318 | 0.235 | 17 | 4750 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| Epodonios-all | 0.255 | None | 0 | 7467 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9820 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5523 | observe |
| barry-far-vless | 0.255 | None | 0 | 5700 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1698 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 73 |
| geo | ClientOSError | - | 31 |
| 204 | ProxyError | - | 30 |
| speed | ClientOSError | - | 22 |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 14 |
| speed | TimeoutError | - | 14 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
