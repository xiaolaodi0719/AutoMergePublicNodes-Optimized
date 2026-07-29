# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-29 03:17:17 |
| 运行耗时 | 284.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 76585 |
| 去重后节点 | 21579 |
| TCP 可达 | 3000 |
| 真实可用 | 694 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21579 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 31.3 |
| probe | 54.1 |
| real_test | 146.6 |
| generate | 46.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44036 |
| trojan | 10978 |
| shadowsocks | 10548 |
| vmess | 10285 |
| hysteria2 | 496 |
| http | 98 |
| shadowsocksr | 74 |
| socks | 59 |
| hysteria | 8 |
| tuic | 3 |

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
| 80.82 | hysteria2 | 260.7 | 666.5 | 21.74 | 0.0 | 10.0 | 12.86 | 17.32 | Au1rxx-base64 | 159.223.157.129 |
| 76.51 | shadowsocks | 263.1 | 655.2 | 21.69 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 37.19.198.243 |
| 76.44 | shadowsocks | 256.4 | 627.0 | 21.84 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 156.146.38.167 |
| 76.42 | shadowsocks | 266.8 | 666.8 | 21.6 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 37.19.198.160 |
| 76.25 | shadowsocks | 261.5 | 602.0 | 21.73 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 156.146.38.169 |
| 76.18 | shadowsocks | 277.2 | 708.9 | 21.36 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 37.19.198.244 |
| 76.13 | shadowsocks | 279.6 | 704.1 | 21.31 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 37.19.198.236 |
| 76.04 | shadowsocks | 244.2 | 617.4 | 22.13 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 198.98.53.130 |
| 75.81 | hysteria2 | 269.1 | 697.0 | 21.55 | 0.0 | 7.08 | 12.86 | 17.32 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 75.42 | trojan | 294.1 | 723.5 | 20.97 | 0.0 | 10.0 | 10.85 | 17.32 | Au1rxx-base64 | 153.75.250.171 |
| 74.38 | shadowsocks | 333.4 | 873.0 | 20.06 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 185.196.61.82 |
| 74.37 | shadowsocks | 263.0 | 651.3 | 21.69 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 156.146.38.170 |
| 74.28 | shadowsocks | 333.1 | 834.9 | 20.07 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 68.168.116.6 |
| 74.06 | shadowsocks | 366.1 | 950.4 | 19.3 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 156.146.38.168 |
| 73.72 | trojan | 283.7 | 633.1 | 21.21 | 0.0 | 10.0 | 10.85 | 17.32 | Au1rxx-base64 | 163.245.196.68 |
| 71.9 | hysteria2 | 380.1 | 710.9 | 18.98 | 0.0 | 9.91 | 12.86 | 17.32 | Au1rxx-base64 | 62.210.124.146 |
| 71.74 | hysteria2 | 391.2 | 718.2 | 18.72 | 0.0 | 9.88 | 12.86 | 17.32 | Au1rxx-base64 | 178.215.238.30 |
| 71.57 | shadowsocks | 325.2 | 833.3 | 20.25 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 185.232.22.18 |
| 71.45 | shadowsocks | 322.6 | 819.7 | 20.31 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 68.168.114.226 |
| 71.35 | shadowsocks | 334.5 | 869.6 | 20.03 | 0.0 | 10.0 | 11.5 | 17.32 | Au1rxx-base64 | 37.120.139.234 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 64 | 167 | prefer |
| Au1rxx-base64 | 0.921 | 0.877 | 301 | 1151 | prefer |
| DeltaKronecker-all | 0.724 | 0.644 | 489 | 4038 | prefer |
| Surfboard-tg-mixed | 0.654 | 0.576 | 59 | 5708 | observe |
| mheidari-all | 0.501 | 0.417 | 36 | 17232 | observe |
| 10ium-ScrapeCategorize-Vless | 0.287 | 0.5 | 2 | 4972 | observe |
| tg-Farah_VPN | 0.263 | 1.0 | 1 | 200 | observe |
| Epodonios-all | 0.255 | None | 0 | 6752 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3968 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6491 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4480 | observe |
| barry-far-vless | 0.255 | None | 0 | 5026 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5059 | observe |
| nscl5-all | 0.246 | None | 0 | 1774 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 90 |
| geo | TimeoutError | - | 69 |
| speed | TimeoutError | - | 24 |
| geo | ClientOSError | - | 21 |
| speed | ClientOSError | - | 18 |
| 204 | TimeoutError | - | 11 |
| 204 | ProxyError | - | 9 |
| 204 | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
