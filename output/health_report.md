# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-23 14:17:29 |
| 运行耗时 | 301.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83515 |
| 去重后节点 | 22816 |
| TCP 可达 | 3000 |
| 真实可用 | 712 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22816 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.2 |
| tcp | 32.7 |
| probe | 58.7 |
| real_test | 171.3 |
| generate | 33.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48321 |
| trojan | 14125 |
| shadowsocks | 10289 |
| vmess | 10137 |
| hysteria2 | 429 |
| shadowsocksr | 73 |
| socks | 57 |
| http | 50 |
| tuic | 17 |
| hysteria | 14 |
| anytls | 3 |

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
| 73.99 | trojan | 314.9 | 687.3 | 20.49 | 0.0 | 10.0 | 12.83 | 17.54 | mheidari-all | 163.245.196.68 |
| 73.74 | shadowsocks | 217.1 | 589.4 | 22.75 | 0.0 | 10.0 | 11.91 | 13.08 | Au1rxx-base64 | 198.98.53.130 |
| 73.38 | shadowsocks | 232.5 | 647.3 | 22.39 | 0.0 | 10.0 | 11.91 | 13.08 | Au1rxx-base64 | 37.19.198.160 |
| 73.33 | shadowsocks | 235.0 | 641.8 | 22.34 | 0.0 | 10.0 | 11.91 | 13.08 | Au1rxx-base64 | 37.19.198.236 |
| 73.1 | vmess | 368.1 | 1071.5 | 19.26 | 0.0 | 10.0 | 10.0 | 18.34 | Surfboard-tg-mixed | 67.220.95.3 |
| 72.24 | shadowsocks | 260.5 | 677.3 | 21.75 | 0.0 | 10.0 | 11.91 | 13.08 | Au1rxx-base64 | 68.168.222.210 |
| 72.2 | shadowsocks | 283.9 | 799.3 | 21.21 | 0.0 | 10.0 | 11.91 | 13.08 | Au1rxx-base64 | 37.19.198.243 |
| 72.06 | trojan | 374.5 | 704.0 | 19.11 | 0.0 | 10.0 | 12.83 | 17.54 | mheidari-all | 91.107.145.13 |
| 70.89 | vless | 333.5 | 941.0 | 20.06 | 0.0 | 10.0 | 3.49 | 18.34 | Surfboard-tg-mixed | 47.89.186.170 |
| 70.38 | shadowsocks | 286.1 | 651.6 | 21.16 | 0.0 | 10.0 | 11.91 | 13.08 | Au1rxx-base64 | 156.146.38.167 |
| 70.37 | trojan | 457.0 | 810.5 | 17.2 | 0.0 | 10.0 | 12.83 | 18.34 | Surfboard-tg-mixed | 198.62.62.23 |
| 70.13 | trojan | 403.8 | 755.1 | 18.43 | 0.0 | 10.0 | 12.83 | 17.54 | mheidari-all | 3.255.100.31 |
| 70.13 | trojan | 405.6 | 780.6 | 18.39 | 0.0 | 10.0 | 12.83 | 17.54 | mheidari-all | 18.202.244.191 |
| 70.08 | shadowsocks | 337.6 | 847.5 | 19.96 | 0.0 | 10.0 | 11.91 | 13.08 | Au1rxx-base64 | 185.196.61.82 |
| 70.05 | shadowsocks | 284.5 | 649.1 | 21.19 | 0.0 | 10.0 | 11.91 | 13.08 | Au1rxx-base64 | 156.146.38.168 |
| 70.03 | trojan | 405.6 | 769.5 | 18.39 | 0.0 | 10.0 | 12.83 | 17.54 | mheidari-all | 3.255.155.50 |
| 70.02 | trojan | 405.1 | 760.9 | 18.4 | 0.0 | 10.0 | 12.83 | 17.54 | mheidari-all | 54.216.163.119 |
| 69.96 | trojan | 404.8 | 761.5 | 18.41 | 0.0 | 10.0 | 12.83 | 17.54 | mheidari-all | 108.131.197.101 |
| 69.85 | trojan | 296.9 | 643.9 | 20.91 | 0.0 | 10.0 | 12.83 | 13.08 | Au1rxx-base64 | 64.94.95.118 |
| 69.76 | trojan | 447.1 | 783.9 | 17.43 | 0.0 | 10.0 | 12.83 | 17.54 | mheidari-all | 212.183.88.136 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.818 | 0.804 | 199 | 432 | prefer |
| mheidari-all | 0.764 | 0.685 | 498 | 19424 | prefer |
| DeltaKronecker-all | 0.683 | 0.607 | 56 | 5572 | observe |
| Surfboard-tg-mixed | 0.668 | 0.589 | 236 | 5390 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 4399 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4757 | observe |
| Epodonios-all | 0.255 | None | 0 | 6487 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7332 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4196 | observe |
| barry-far-vless | 0.255 | None | 0 | 4823 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4954 | observe |
| nscl5-all | 0.255 | None | 0 | 2435 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 132 |
| speed | ClientOSError | - | 58 |
| cn-block | TimeoutError | - | 54 |
| geo | ClientOSError | - | 17 |
| 204 | ProxyError | - | 14 |
| 204 | TimeoutError | - | 13 |
| speed | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
