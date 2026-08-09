# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-09 18:52:12 |
| 运行耗时 | 221.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86183 |
| 去重后节点 | 24016 |
| TCP 可达 | 3000 |
| 真实可用 | 455 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24016 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 34.9 |
| probe | 51.2 |
| real_test | 94.4 |
| generate | 32.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51603 |
| vmess | 13184 |
| trojan | 10057 |
| shadowsocks | 9651 |
| hysteria2 | 1464 |
| shadowsocksr | 75 |
| socks | 67 |
| http | 33 |
| anytls | 26 |
| hysteria | 15 |
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
| 83.81 | hysteria2 | 241.6 | 671.6 | 22.18 | 0.0 | 8.85 | 14.32 | 19.46 | Au1rxx-base64 | 138.124.68.188 |
| 83.41 | hysteria2 | 243.2 | 672.4 | 22.15 | 0.0 | 8.48 | 14.32 | 19.46 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 82.25 | hysteria2 | 298.4 | 824.7 | 20.87 | 0.0 | 8.7 | 14.32 | 19.46 | Au1rxx-base64 | 159.223.157.129 |
| 81.58 | shadowsocks | 234.6 | 629.1 | 22.35 | 0.0 | 10.0 | 13.77 | 19.46 | Au1rxx-base64 | 37.19.198.244 |
| 79.41 | vless | 299.7 | 719.2 | 20.84 | 0.0 | 10.0 | 9.11 | 19.46 | Au1rxx-base64 | 169.40.42.173 |
| 78.77 | shadowsocks | 282.2 | 650.5 | 21.24 | 0.0 | 10.0 | 13.77 | 19.46 | Au1rxx-base64 | 156.146.38.169 |
| 78.61 | vless | 334.1 | 845.4 | 20.04 | 0.0 | 10.0 | 9.11 | 19.46 | Au1rxx-base64 | 158.69.112.254 |
| 78.41 | vless | 285.0 | 697.6 | 21.18 | 0.0 | 8.66 | 9.11 | 19.46 | Au1rxx-base64 | 216.152.147.28 |
| 78.28 | shadowsocks | 245.3 | 668.0 | 22.1 | 0.0 | 8.95 | 13.77 | 19.46 | Au1rxx-base64 | 37.19.198.236 |
| 77.68 | vless | 298.4 | 799.9 | 20.87 | 0.0 | 10.0 | 9.11 | 19.46 | Au1rxx-base64 | 169.40.42.184 |
| 76.8 | vless | 347.9 | 825.6 | 19.72 | 0.0 | 10.0 | 9.11 | 19.46 | Au1rxx-base64 | 169.40.42.75 |
| 76.62 | vless | 368.1 | 896.4 | 19.26 | 0.0 | 8.79 | 9.11 | 19.46 | Au1rxx-base64 | 169.40.42.15 |
| 76.32 | shadowsocks | 245.8 | 680.5 | 22.09 | 0.0 | 10.0 | 13.77 | 19.46 | Au1rxx-base64 | 37.19.198.160 |
| 75.67 | vless | 353.6 | 915.4 | 19.59 | 0.0 | 10.0 | 9.11 | 19.46 | Au1rxx-base64 | 169.40.42.192 |
| 75.49 | vless | 325.4 | 880.8 | 20.24 | 0.0 | 8.68 | 9.11 | 19.46 | Au1rxx-base64 | 167.17.69.171 |
| 75.03 | hysteria2 | 370.1 | 702.5 | 19.21 | 0.0 | 8.89 | 14.32 | 19.46 | Au1rxx-base64 | 62.210.124.146 |
| 74.92 | vless | 363.9 | 938.2 | 19.35 | 0.0 | 10.0 | 9.11 | 19.46 | Au1rxx-base64 | 169.40.42.182 |
| 74.82 | shadowsocks | 299.6 | 706.7 | 20.84 | 0.0 | 8.96 | 13.77 | 19.46 | Au1rxx-base64 | 108.181.57.93 |
| 73.56 | shadowsocks | 351.1 | 696.7 | 19.65 | 0.0 | 10.0 | 13.77 | 19.46 | Au1rxx-base64 | 173.244.56.6 |
| 73.4 | shadowsocks | 315.2 | 599.5 | 20.48 | 0.0 | 8.96 | 13.77 | 19.46 | Au1rxx-base64 | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | 0.914 | 374 | 1688 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.753 | 0.676 | 102 | 6634 | prefer |
| mheidari-all | 0.633 | 0.579 | 19 | 20206 | observe |
| DeltaKronecker-all | 0.46 | 0.412 | 17 | 4998 | observe |
| tg-oneclickvpnkeys | 0.444 | 1.0 | 5 | 107 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5505 | observe |
| Epodonios-all | 0.255 | None | 0 | 7178 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7585 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5470 | observe |
| barry-far-vless | 0.255 | None | 0 | 5784 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5189 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 33 |
| cn-block | TimeoutError | - | 9 |
| 204 | ProxyError | - | 9 |
| geo | TimeoutError | - | 7 |
| speed | ClientOSError | - | 6 |
| speed | TimeoutError | - | 6 |
| geo | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
