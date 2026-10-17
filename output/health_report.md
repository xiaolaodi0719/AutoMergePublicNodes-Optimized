# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 04:00:51 |
| 运行耗时 | 774.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99741 |
| 去重后节点 | 27742 |
| TCP 可达 | 3000 |
| 真实可用 | 550 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27742 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 49.3 |
| probe | 284.6 |
| real_test | 345.9 |
| generate | 84.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58481 |
| vmess | 16649 |
| shadowsocks | 12109 |
| trojan | 10166 |
| hysteria2 | 1340 |
| http | 717 |
| shadowsocksr | 168 |
| socks | 62 |
| anytls | 26 |
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
| 80.88 | hysteria2 | 225.1 | 230.4 | 22.57 | 6.36 | 9.15 | 12.14 | 17.34 | Au1rxx-base64 | 45.32.10.7 |
| 80.12 | hysteria2 | 213.8 | 231.8 | 22.83 | 6.31 | 8.17 | 12.14 | 17.34 | Au1rxx-base64 | vp3.yysyy.online |
| 78.14 | vless | 246.2 | 560.5 | 22.08 | 0.0 | 8.49 | 10.23 | 17.34 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 77.82 | shadowsocks | 207.6 | 558.3 | 22.97 | 0.0 | 9.1 | 12.41 | 17.34 | Au1rxx-base64 | 149.22.95.183 |
| 77.39 | vless | 235.7 | 514.6 | 22.32 | 0.0 | 10.0 | 10.23 | 17.34 | Au1rxx-base64 | 47.251.108.158 |
| 75.16 | vless | 269.0 | 585.2 | 21.55 | 0.0 | 9.3 | 10.23 | 17.34 | Au1rxx-base64 | 154.29.159.211 |
| 75.06 | shadowsocks | 257.6 | 265.2 | 21.82 | 5.05 | 9.32 | 12.41 | 17.34 | Au1rxx-base64 | 149.22.87.204 |
| 74.57 | hysteria2 | 334.7 | 748.7 | 20.03 | 0.0 | 9.46 | 12.14 | 17.34 | Au1rxx-base64 | 129.213.91.185 |
| 74.46 | shadowsocks | 259.0 | 270.0 | 21.78 | 4.88 | 9.08 | 12.41 | 17.34 | Au1rxx-base64 | 149.22.87.241 |
| 74.37 | vless | 243.1 | 532.0 | 22.15 | 0.0 | 9.25 | 10.23 | 17.34 | Au1rxx-base64 | 131.143.180.110 |
| 74.25 | vless | 315.8 | 716.5 | 20.47 | 0.0 | 9.25 | 10.23 | 17.34 | Au1rxx-base64 | 23.95.222.127 |
| 74.08 | vless | 290.6 | 619.5 | 21.05 | 0.0 | 9.31 | 10.23 | 17.34 | Au1rxx-base64 | 154.9.241.170 |
| 73.54 | vless | 476.3 | 1320.7 | 16.75 | 0.0 | 9.22 | 10.23 | 17.34 | Au1rxx-base64 | 51.81.203.63 |
| 73.49 | vless | 321.2 | 703.5 | 20.34 | 0.0 | 9.19 | 10.23 | 17.34 | Au1rxx-base64 | 147.45.60.160 |
| 73.15 | trojan | 308.3 | 318.1 | 20.64 | 3.07 | 9.12 | 13.2 | 17.34 | Au1rxx-base64 | 45.32.52.173 |
| 73.15 | vless | 308.9 | 315.9 | 20.63 | 3.15 | 9.11 | 10.23 | 17.34 | Au1rxx-base64 | 154.31.114.248 |
| 72.88 | vless | 310.1 | 324.8 | 20.6 | 2.82 | 9.1 | 10.23 | 17.34 | Au1rxx-base64 | 156.246.88.125 |
| 72.81 | trojan | 307.9 | 312.6 | 20.65 | 3.28 | 9.17 | 13.2 | 17.34 | Au1rxx-base64 | 108.61.186.37 |
| 72.77 | vless | 315.9 | 325.4 | 20.46 | 2.8 | 9.12 | 10.23 | 17.34 | Au1rxx-base64 | 43.167.232.174 |
| 72.66 | trojan | 307.3 | 315.2 | 20.67 | 3.18 | 8.15 | 13.2 | 17.34 | Au1rxx-base64 | jp.tronsg.com |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | 0.876 | 524 | 1993 | prefer |
| Surfboard-tg-mixed | 0.689 | 0.612 | 67 | 7128 | observe |
| ermaozi | 0.439 | 0.407 | 54 | 702 | observe |
| DeltaKronecker-all | 0.384 | 0.286 | 21 | 4946 | observe |
| ermaozi-get_subscribe | 0.335 | 1.0 | 2 | 601 | observe |
| mheidari-all | 0.306 | 0.22 | 91 | 24092 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1993 | observe |
| Epodonios-all | 0.255 | None | 0 | 7692 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10039 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5602 | observe |
| barry-far-vless | 0.255 | None | 0 | 5847 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 64 |
| 204 | ProxyError | - | 44 |
| geo | ClientOSError | - | 27 |
| speed | ClientOSError | - | 23 |
| speed | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 5 |
| 204 | TimeoutError | - | 5 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
