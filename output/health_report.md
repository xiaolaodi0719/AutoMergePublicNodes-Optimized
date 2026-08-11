# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-11 07:19:19 |
| 运行耗时 | 238.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 84663 |
| 去重后节点 | 24209 |
| TCP 可达 | 3000 |
| 真实可用 | 506 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24209 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.4 |
| tcp | 36.7 |
| probe | 52.8 |
| real_test | 110.3 |
| generate | 32.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49256 |
| vmess | 13332 |
| trojan | 10676 |
| shadowsocks | 9835 |
| hysteria2 | 1301 |
| socks | 74 |
| http | 73 |
| shadowsocksr | 65 |
| anytls | 26 |
| hysteria | 13 |
| tuic | 12 |

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
| 83.5 | hysteria2 | 236.5 | 658.2 | 22.3 | 0.0 | 10.0 | 13.5 | 18.8 | Au1rxx-base64 | 159.223.157.129 |
| 81.19 | shadowsocks | 245.1 | 685.4 | 22.1 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 37.19.198.236 |
| 81.13 | shadowsocks | 247.9 | 690.3 | 22.04 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 37.19.198.244 |
| 79.04 | shadowsocks | 251.6 | 705.9 | 21.95 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 37.19.198.160 |
| 78.24 | shadowsocks | 278.6 | 646.9 | 21.33 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 156.146.38.170 |
| 77.48 | shadowsocks | 291.9 | 644.2 | 21.02 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 156.146.38.168 |
| 76.29 | trojan | 294.2 | 634.2 | 20.97 | 0.0 | 10.0 | 12.63 | 18.8 | Au1rxx-base64 | 64.94.95.117 |
| 75.92 | shadowsocks | 319.6 | 719.5 | 20.38 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 108.181.57.93 |
| 75.85 | trojan | 314.0 | 698.4 | 20.51 | 0.0 | 10.0 | 12.63 | 18.8 | Au1rxx-base64 | 64.94.95.114 |
| 75.34 | vless | 270.4 | 659.7 | 21.52 | 0.0 | 10.0 | 8.02 | 18.8 | Au1rxx-base64 | 77.110.125.143 |
| 74.86 | shadowsocks | 497.2 | 1362.5 | 16.27 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 68.168.222.210 |
| 74.66 | hysteria2 | 384.1 | 779.6 | 18.89 | 0.0 | 9.96 | 13.5 | 18.8 | Au1rxx-base64 | 62.210.124.146 |
| 74.52 | trojan | 374.8 | 876.7 | 19.1 | 0.0 | 10.0 | 12.63 | 18.8 | Au1rxx-base64 | 64.94.95.118 |
| 74.18 | shadowsocks | 301.1 | 583.5 | 20.81 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 70.39.178.204 |
| 74.08 | shadowsocks | 316.8 | 598.2 | 20.44 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 149.22.95.183 |
| 74.07 | hysteria2 | 400.8 | 754.3 | 18.5 | 0.0 | 10.0 | 13.5 | 18.8 | Au1rxx-base64 | 144.31.207.60 |
| 73.97 | hysteria2 | 412.2 | 851.9 | 18.24 | 0.0 | 10.0 | 13.5 | 18.8 | Au1rxx-base64 | 5.129.235.85 |
| 73.94 | vless | 349.7 | 836.9 | 19.68 | 0.0 | 10.0 | 8.02 | 16.24 | Surfboard-tg-mixed | 169.40.42.179 |
| 73.8 | hysteria2 | 431.9 | 889.7 | 17.78 | 0.0 | 10.0 | 13.5 | 18.8 | Au1rxx-base64 | 5.255.102.165 |
| 73.76 | shadowsocks | 305.9 | 532.2 | 20.7 | 0.0 | 10.0 | 14.29 | 18.8 | Au1rxx-base64 | 108.181.118.10 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | 1.0 | 49 | 67 | prefer |
| Au1rxx-base64 | 0.97 | 0.916 | 381 | 1409 | prefer |
| Surfboard-tg-mixed | 0.802 | 0.726 | 106 | 6265 | prefer |
| DeltaKronecker-all | 0.447 | 0.362 | 47 | 5522 | observe |
| mheidari-all | 0.378 | 0.289 | 45 | 20272 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 5419 | observe |
| Epodonios-all | 0.255 | None | 0 | 6871 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7470 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5103 | observe |
| barry-far-vless | 0.255 | None | 0 | 5410 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5209 | observe |
| nscl5-all | 0.239 | None | 0 | 1607 | observe |
| Au1rxx-clash | 0.231 | None | 0 | 1409 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 30 |
| geo | ClientOSError | - | 29 |
| 204 | TimeoutError | - | 16 |
| speed | TimeoutError | - | 16 |
| speed | ClientOSError | - | 12 |
| cn-block | TimeoutError | - | 8 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
