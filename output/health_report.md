# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 21:28:40 |
| 运行耗时 | 549.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 96813 |
| 去重后节点 | 26642 |
| TCP 可达 | 3000 |
| 真实可用 | 414 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26642 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.4 |
| tcp | 43.1 |
| probe | 269.1 |
| real_test | 158.9 |
| generate | 71.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59376 |
| vmess | 14844 |
| shadowsocks | 11129 |
| trojan | 9067 |
| hysteria2 | 1486 |
| http | 601 |
| shadowsocksr | 177 |
| socks | 82 |
| anytls | 25 |
| hysteria | 18 |
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
| 81.08 | shadowsocks | 217.7 | 545.0 | 22.74 | 0.0 | 10.0 | 13.14 | 19.2 | Au1rxx-base64 | 173.244.56.6 |
| 80.57 | vless | 200.9 | 524.6 | 23.13 | 0.0 | 8.91 | 9.33 | 19.2 | Au1rxx-base64 | 172.235.43.210 |
| 80.24 | vless | 215.1 | 535.3 | 22.8 | 0.0 | 8.91 | 9.33 | 19.2 | Au1rxx-base64 | 195.123.240.65 |
| 80.17 | shadowsocks | 256.8 | 623.4 | 21.83 | 0.0 | 10.0 | 13.14 | 19.2 | Au1rxx-base64 | 156.146.38.169 |
| 79.09 | hysteria2 | 296.1 | 701.6 | 20.92 | 0.0 | 10.0 | 13.24 | 19.2 | Au1rxx-base64 | 66.94.121.46 |
| 76.78 | vless | 273.7 | 604.5 | 21.44 | 0.0 | 10.0 | 9.33 | 19.2 | Au1rxx-base64 | 15.204.97.216 |
| 76.63 | vless | 200.2 | 519.2 | 23.14 | 0.0 | 10.0 | 9.33 | 14.16 | Surfboard-tg-mixed | 172.235.38.85 |
| 76.49 | shadowsocks | 291.4 | 627.9 | 21.03 | 0.0 | 10.0 | 13.14 | 19.2 | Au1rxx-base64 | 149.22.95.183 |
| 76.01 | http | 211.0 | 538.8 | 22.89 | 0.0 | 10.0 | 10.26 | 15.86 | ermaozi | 138.199.35.207 |
| 75.99 | http | 211.8 | 537.0 | 22.87 | 0.0 | 10.0 | 10.26 | 15.86 | ermaozi | 138.199.35.216 |
| 75.61 | shadowsocks | 214.5 | 535.3 | 22.81 | 0.0 | 10.0 | 13.14 | 14.16 | Surfboard-tg-mixed | 108.181.0.177 |
| 75.13 | vless | 222.0 | 568.8 | 22.64 | 0.0 | 8.96 | 9.33 | 19.2 | Au1rxx-base64 | 192.3.247.109 |
| 74.9 | vless | 229.4 | 541.7 | 22.47 | 0.0 | 10.0 | 9.33 | 19.2 | Au1rxx-base64 | 172.67.130.159 |
| 74.88 | http | 216.6 | 534.4 | 22.76 | 0.0 | 10.0 | 10.26 | 15.86 | ermaozi | 138.199.35.198 |
| 74.45 | vless | 206.2 | 518.2 | 23.0 | 0.0 | 10.0 | 9.33 | 19.2 | Au1rxx-base64 | 144.34.183.80 |
| 74.02 | shadowsocks | 257.8 | 630.8 | 21.81 | 0.0 | 8.92 | 13.14 | 19.2 | Au1rxx-base64 | 156.146.38.168 |
| 73.98 | shadowsocks | 189.3 | 509.5 | 23.4 | 0.0 | 10.0 | 13.14 | 11.94 | mheidari-all | 192.3.247.109 |
| 73.64 | trojan | 289.2 | 794.5 | 21.08 | 0.0 | 10.0 | 13.12 | 11.94 | mheidari-all | 34.94.125.227 |
| 73.43 | shadowsocks | 212.8 | 502.1 | 22.85 | 0.0 | 10.0 | 13.14 | 11.94 | mheidari-all | 108.181.118.10 |
| 73.01 | vless | 307.5 | 711.3 | 20.66 | 0.0 | 8.91 | 9.33 | 19.2 | Au1rxx-base64 | 5.78.28.48 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.967 | 0.905 | 252 | 1635 | prefer |
| mheidari-all | 0.906 | 0.833 | 84 | 22531 | prefer |
| Surfboard-tg-mixed | 0.854 | 0.779 | 113 | 7072 | prefer |
| ermaozi | 0.793 | 0.8 | 30 | 291 | prefer |
| DeltaKronecker-all | 0.391 | 1.0 | 2 | 6471 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4332 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5131 | observe |
| Epodonios-all | 0.255 | None | 0 | 7534 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8842 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5711 | observe |
| barry-far-vless | 0.255 | None | 0 | 5930 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1635 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 14 |
| cn-block | ClientOSError | - | 9 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
