# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 20:43:43 |
| 运行耗时 | 600.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90275 |
| 去重后节点 | 25551 |
| TCP 可达 | 3000 |
| 真实可用 | 455 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25551 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.6 |
| tcp | 43.2 |
| probe | 268.5 |
| real_test | 199.8 |
| generate | 81.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55134 |
| vmess | 13460 |
| shadowsocks | 10617 |
| trojan | 8291 |
| hysteria2 | 1937 |
| http | 613 |
| shadowsocksr | 128 |
| socks | 59 |
| hysteria | 14 |
| tuic | 14 |
| anytls | 8 |

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
| 80.43 | vless | 202.9 | 505.1 | 23.08 | 0.0 | 10.0 | 9.13 | 18.22 | Au1rxx-base64 | 172.235.43.210 |
| 79.97 | shadowsocks | 250.1 | 606.3 | 21.99 | 0.0 | 10.0 | 13.76 | 18.22 | Au1rxx-base64 | 156.146.38.169 |
| 78.89 | shadowsocks | 248.8 | 597.8 | 22.02 | 0.0 | 8.89 | 13.76 | 18.22 | Au1rxx-base64 | 156.146.38.170 |
| 78.83 | shadowsocks | 250.8 | 644.1 | 21.97 | 0.0 | 8.88 | 13.76 | 18.22 | Au1rxx-base64 | 173.244.56.6 |
| 78.75 | hysteria2 | 234.7 | 525.6 | 22.34 | 0.0 | 8.99 | 10.2 | 18.22 | Au1rxx-base64 | 66.94.121.46 |
| 78.74 | shadowsocks | 238.3 | 578.9 | 22.26 | 0.0 | 10.0 | 13.76 | 18.22 | Au1rxx-base64 | 108.181.118.10 |
| 78.58 | shadowsocks | 251.3 | 610.0 | 21.96 | 0.0 | 8.92 | 13.76 | 18.22 | Au1rxx-base64 | 156.146.38.167 |
| 77.65 | shadowsocks | 259.7 | 626.1 | 21.77 | 0.0 | 8.9 | 13.76 | 18.22 | Au1rxx-base64 | 173.244.56.9 |
| 77.2 | trojan | 284.8 | 637.7 | 21.19 | 0.0 | 10.0 | 13.5 | 18.22 | Au1rxx-base64 | 64.94.95.118 |
| 77.06 | trojan | 283.2 | 624.8 | 21.22 | 0.0 | 10.0 | 13.5 | 18.22 | Au1rxx-base64 | 64.94.95.114 |
| 76.92 | trojan | 285.0 | 623.7 | 21.18 | 0.0 | 10.0 | 13.5 | 18.22 | Au1rxx-base64 | 64.94.95.117 |
| 76.84 | shadowsocks | 271.0 | 624.9 | 21.51 | 0.0 | 8.96 | 13.76 | 18.22 | Au1rxx-base64 | 23.150.248.20 |
| 76.72 | shadowsocks | 245.1 | 563.5 | 22.11 | 0.0 | 10.0 | 13.76 | 16.0 | Surfboard-tg-mixed | 5.78.51.123 |
| 76.62 | vless | 192.3 | 479.1 | 23.33 | 0.0 | 8.94 | 9.13 | 18.22 | Au1rxx-base64 | 45.149.172.80 |
| 75.37 | vless | 346.2 | 835.5 | 19.76 | 0.0 | 10.0 | 9.13 | 18.22 | Au1rxx-base64 | 15.204.97.216 |
| 75.29 | shadowsocks | 272.1 | 572.0 | 21.48 | 0.0 | 8.87 | 13.76 | 18.22 | Au1rxx-base64 | 149.22.95.183 |
| 75.22 | vless | 285.4 | 558.6 | 21.17 | 0.0 | 8.98 | 9.13 | 18.22 | Au1rxx-base64 | 144.172.104.26 |
| 75.08 | hysteria2 | 306.1 | 809.8 | 20.69 | 0.0 | 8.92 | 10.2 | 18.22 | Au1rxx-base64 | 107.175.219.48 |
| 74.11 | vless | 326.5 | 731.3 | 20.22 | 0.0 | 8.97 | 9.13 | 18.22 | Au1rxx-base64 | 79.141.172.154 |
| 74.08 | vless | 234.9 | 469.7 | 22.34 | 0.0 | 10.0 | 9.13 | 18.22 | Au1rxx-base64 | 162.159.45.19 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | 0.908 | 306 | 1781 | prefer |
| Surfboard-tg-mixed | 0.787 | 0.71 | 155 | 7511 | prefer |
| mheidari-all | 0.735 | 0.661 | 56 | 16210 | prefer |
| ermaozi | 0.637 | 0.629 | 35 | 382 | observe |
| xiaoji235-airport-v2ray-all | 0.412 | 0.353 | 17 | 5301 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4222 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| Epodonios-all | 0.255 | None | 0 | 8029 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8804 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6079 | observe |
| barry-far-vless | 0.255 | None | 0 | 6390 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1781 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 29 |
| 204 | ProxyError | - | 22 |
| cn-block | ClientOSError | - | 17 |
| cn-block | TimeoutError | - | 16 |
| speed | ClientOSError | - | 11 |
| 204 | TimeoutError | - | 10 |
| speed | TimeoutError | - | 7 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | exit-country | CN | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
