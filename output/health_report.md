# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-16 06:53:20 |
| 运行耗时 | 365.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 78586 |
| 去重后节点 | 21818 |
| TCP 可达 | 3000 |
| 真实可用 | 1146 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21818 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 0.7 |
| tcp | 31.7 |
| probe | 69.7 |
| real_test | 224.5 |
| generate | 31.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43148 |
| trojan | 13542 |
| vmess | 10733 |
| shadowsocks | 9805 |
| hysteria2 | 1023 |
| http | 170 |
| shadowsocksr | 74 |
| socks | 72 |
| tuic | 10 |
| hysteria | 7 |
| anytls | 2 |

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
| 85.28 | http | 188.2 | 480.9 | 23.42 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 85.23 | http | 190.2 | 494.9 | 23.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 85.17 | http | 192.9 | 491.8 | 23.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 85.13 | http | 194.7 | 484.8 | 23.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 85.11 | http | 195.8 | 498.4 | 23.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 85.09 | http | 196.4 | 496.1 | 23.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 85.09 | http | 196.6 | 500.8 | 23.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 85.02 | http | 199.4 | 499.7 | 23.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 85.02 | http | 199.6 | 500.4 | 23.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 84.99 | http | 200.9 | 505.8 | 23.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 84.9 | http | 204.5 | 508.7 | 23.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 84.89 | http | 205.1 | 520.1 | 23.03 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 84.56 | trojan | 237.7 | 552.4 | 22.28 | 0.0 | 10.0 | 14.78 | 20.0 | Au1rxx-base64 | 54.245.126.186 |
| 84.49 | trojan | 232.6 | 529.5 | 22.39 | 0.0 | 10.0 | 14.78 | 20.0 | Au1rxx-base64 | 44.251.158.80 |
| 84.46 | http | 223.5 | 574.5 | 22.6 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 84.04 | trojan | 241.0 | 563.2 | 22.2 | 0.0 | 9.56 | 14.78 | 20.0 | Au1rxx-base64 | 34.221.30.108 |
| 84.0 | trojan | 243.2 | 562.0 | 22.15 | 0.0 | 9.57 | 14.78 | 20.0 | Au1rxx-base64 | 35.88.210.26 |
| 83.96 | trojan | 220.2 | 497.5 | 22.68 | 0.0 | 10.0 | 14.78 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 83.9 | trojan | 234.6 | 539.8 | 22.35 | 0.0 | 9.56 | 14.78 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 83.73 | trojan | 241.4 | 566.5 | 22.19 | 0.0 | 9.43 | 14.78 | 20.0 | Au1rxx-base64 | 44.242.235.129 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.966 | 800 | 1997 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.789 | 0.711 | 204 | 5641 | prefer |
| mheidari-all | 0.768 | 0.691 | 136 | 16464 | prefer |
| nscl5-all | 0.287 | 0.5 | 2 | 2601 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1997 | observe |
| Epodonios-all | 0.255 | None | 0 | 6328 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7355 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4360 | observe |
| barry-far-vless | 0.255 | None | 0 | 4736 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3950 | observe |
| DeltaKronecker-all | 0.243 | 0.146 | 41 | 5092 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 59 |
| speed | TimeoutError | - | 38 |
| geo | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 12 |
| speed | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 11 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
