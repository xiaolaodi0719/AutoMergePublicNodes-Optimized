# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 20:43:41 |
| 运行耗时 | 559.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83613 |
| 去重后节点 | 23435 |
| TCP 可达 | 3000 |
| 真实可用 | 487 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23435 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.6 |
| tcp | 38.7 |
| probe | 218.3 |
| real_test | 207.7 |
| generate | 86.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49870 |
| vmess | 13666 |
| shadowsocks | 9917 |
| trojan | 8217 |
| hysteria2 | 1150 |
| http | 580 |
| shadowsocksr | 131 |
| socks | 66 |
| hysteria | 11 |
| tuic | 4 |
| anytls | 1 |

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
| 80.14 | vless | 320.2 | 824.2 | 20.36 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 15.204.97.216 |
| 79.83 | vless | 193.3 | 499.2 | 23.3 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 172.235.43.210 |
| 78.76 | trojan | 186.0 | 476.2 | 23.47 | 0.0 | 10.0 | 8.57 | 19.22 | Au1rxx-base64 | 100.42.228.109 |
| 78.13 | vless | 320.9 | 827.6 | 20.35 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 15.204.97.209 |
| 77.97 | hysteria2 | 245.4 | 578.5 | 22.1 | 0.0 | 10.0 | 13.42 | 19.22 | Au1rxx-base64 | 66.94.121.46 |
| 77.9 | vless | 223.0 | 496.9 | 22.62 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 162.159.38.127 |
| 77.64 | vless | 204.3 | 479.6 | 23.05 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 162.159.43.187 |
| 77.37 | vless | 245.7 | 466.8 | 22.09 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 108.162.198.178 |
| 76.48 | shadowsocks | 221.4 | 530.8 | 22.65 | 0.0 | 10.0 | 13.37 | 19.22 | Au1rxx-base64 | 149.22.95.183 |
| 75.26 | vless | 260.2 | 412.1 | 21.75 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 172.64.229.170 |
| 75.24 | vless | 470.1 | 1215.3 | 16.9 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 51.81.203.63 |
| 74.79 | vless | 215.5 | 475.3 | 22.79 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 172.64.32.103 |
| 74.4 | vless | 266.8 | 405.9 | 21.6 | 0.0 | 10.0 | 10.56 | 14.68 | Surfboard-tg-mixed | 45.131.5.35 |
| 74.39 | vless | 439.2 | 642.0 | 17.61 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 139.64.235.204 |
| 74.32 | vless | 389.9 | 880.1 | 18.75 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 79.141.172.154 |
| 74.24 | shadowsocks | 324.5 | 659.4 | 20.27 | 0.0 | 10.0 | 13.37 | 19.22 | Au1rxx-base64 | 23.150.248.20 |
| 73.77 | vless | 275.5 | 600.2 | 21.4 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 172.64.229.2 |
| 73.35 | vless | 201.5 | 491.2 | 23.11 | 0.0 | 10.0 | 10.56 | 14.68 | Surfboard-tg-mixed | 172.235.38.85 |
| 73.13 | vless | 376.1 | 705.8 | 19.07 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 5.78.159.97 |
| 73.02 | vless | 386.9 | 769.2 | 18.82 | 0.0 | 10.0 | 10.56 | 19.22 | Au1rxx-base64 | 216.152.147.28 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | 0.915 | 284 | 1574 | prefer |
| DeltaKronecker-all | 0.886 | 0.828 | 29 | 6092 | prefer |
| ermaozi | 0.834 | 0.846 | 26 | 314 | prefer |
| mheidari-all | 0.802 | 0.731 | 52 | 16265 | prefer |
| Surfboard-tg-mixed | 0.722 | 0.643 | 213 | 7207 | prefer |
| tg-oneclickvpnkeys | 0.403 | 1.0 | 4 | 74 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7615 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8753 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5768 | observe |
| barry-far-vless | 0.255 | None | 0 | 5924 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4315 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| 10ium-ScrapeCategorize-Vless | 0.24 | 0.25 | 4 | 5238 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 29 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 16 |
| 204 | ProxyError | - | 15 |
| geo | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 11 |
| speed | ClientOSError | - | 8 |
| 204 | ProxyConnectionError | - | 5 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
