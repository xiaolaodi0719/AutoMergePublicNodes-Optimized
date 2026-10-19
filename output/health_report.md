# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 22:19:33 |
| 运行耗时 | 548.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94419 |
| 去重后节点 | 25980 |
| TCP 可达 | 3000 |
| 真实可用 | 400 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25980 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.5 |
| tcp | 44.5 |
| probe | 219.7 |
| real_test | 197.9 |
| generate | 79.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56384 |
| vmess | 17064 |
| shadowsocks | 11209 |
| trojan | 7913 |
| hysteria2 | 1206 |
| http | 338 |
| shadowsocksr | 168 |
| socks | 68 |
| anytls | 46 |
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
| 82.73 | hysteria2 | 255.6 | 571.9 | 21.86 | 0.0 | 10.0 | 14.17 | 17.7 | Au1rxx-base64 | 66.94.121.46 |
| 78.57 | vless | 254.3 | 565.2 | 21.89 | 0.0 | 9.71 | 10.81 | 17.7 | Au1rxx-base64 | 144.202.126.147 |
| 78.28 | shadowsocks | 247.2 | 633.3 | 22.05 | 0.0 | 10.0 | 12.53 | 17.7 | Au1rxx-base64 | 156.146.38.168 |
| 78.01 | vless | 264.9 | 604.5 | 21.65 | 0.0 | 9.77 | 10.81 | 17.7 | Au1rxx-base64 | 45.63.53.81 |
| 77.92 | shadowsocks | 247.8 | 625.3 | 22.04 | 0.0 | 9.65 | 12.53 | 17.7 | Au1rxx-base64 | 156.146.38.170 |
| 76.96 | shadowsocks | 245.9 | 624.5 | 22.08 | 0.0 | 9.65 | 12.53 | 17.7 | Au1rxx-base64 | 156.146.38.169 |
| 76.17 | shadowsocks | 240.9 | 610.2 | 22.2 | 0.0 | 9.74 | 12.53 | 17.7 | Au1rxx-base64 | 156.146.38.167 |
| 76.11 | vless | 264.2 | 548.6 | 21.66 | 0.0 | 9.68 | 10.81 | 17.7 | Au1rxx-base64 | 131.143.180.87 |
| 75.19 | vless | 296.0 | 612.0 | 20.93 | 0.0 | 9.73 | 10.81 | 17.7 | Au1rxx-base64 | 154.9.241.170 |
| 75.09 | vless | 301.4 | 623.2 | 20.8 | 0.0 | 9.65 | 10.81 | 17.7 | Au1rxx-base64 | 44.248.233.99 |
| 74.8 | vless | 298.1 | 603.3 | 20.88 | 0.0 | 9.25 | 10.81 | 17.7 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 74.53 | trojan | 348.1 | 905.3 | 19.72 | 0.0 | 9.75 | 10.45 | 17.7 | Au1rxx-base64 | 66.23.203.21 |
| 73.93 | vless | 241.2 | 539.2 | 22.19 | 0.0 | 9.78 | 10.81 | 17.7 | Au1rxx-base64 | 136.175.179.94 |
| 73.76 | vless | 278.9 | 615.0 | 21.32 | 0.0 | 9.75 | 10.81 | 17.7 | Au1rxx-base64 | 15.204.97.206 |
| 73.58 | vless | 442.5 | 1103.1 | 17.54 | 0.0 | 9.71 | 10.81 | 17.7 | Au1rxx-base64 | 51.81.203.63 |
| 72.56 | shadowsocks | 306.9 | 306.9 | 20.67 | 3.49 | 9.7 | 12.53 | 17.7 | Au1rxx-base64 | 149.22.87.204 |
| 72.3 | vless | 374.9 | 788.6 | 19.1 | 0.0 | 9.78 | 10.81 | 17.7 | Au1rxx-base64 | 66.70.179.198 |
| 72.11 | shadowsocks | 339.3 | 785.1 | 19.92 | 0.0 | 10.0 | 12.53 | 17.7 | Au1rxx-base64 | 37.19.198.236 |
| 71.96 | vless | 306.8 | 662.0 | 20.68 | 0.0 | 9.0 | 10.81 | 17.7 | Au1rxx-base64 | freeus.aiage.work |
| 71.79 | vless | 431.8 | 1004.9 | 17.78 | 0.0 | 9.77 | 10.81 | 17.7 | Au1rxx-base64 | 185.95.231.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | 1.0 | 20 | 27 | prefer |
| Au1rxx-base64 | 0.902 | 0.849 | 278 | 1390 | prefer |
| mheidari-all | 0.867 | 0.797 | 59 | 23238 | prefer |
| Surfboard-tg-mixed | 0.812 | 0.736 | 125 | 7064 | prefer |
| DeltaKronecker-all | 0.401 | 0.571 | 7 | 3294 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 72 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| Epodonios-all | 0.255 | None | 0 | 7515 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9850 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5579 | observe |
| barry-far-vless | 0.255 | None | 0 | 5797 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 14 |
| speed | ClientOSError | - | 13 |
| geo | ClientOSError | - | 11 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 6 |
| geo | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
