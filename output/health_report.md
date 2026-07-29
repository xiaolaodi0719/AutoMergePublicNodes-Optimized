# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-29 08:53:29 |
| 运行耗时 | 318.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 77963 |
| 去重后节点 | 22462 |
| TCP 可达 | 3000 |
| 真实可用 | 607 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22462 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.3 |
| tcp | 31.2 |
| probe | 67.5 |
| real_test | 179.5 |
| generate | 33.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45822 |
| shadowsocks | 10689 |
| trojan | 10522 |
| vmess | 10159 |
| hysteria2 | 501 |
| http | 98 |
| shadowsocksr | 75 |
| socks | 56 |
| anytls | 26 |
| hysteria | 12 |
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
| 83.84 | hysteria2 | 232.4 | 645.3 | 22.4 | 0.0 | 10.0 | 14.12 | 18.42 | Au1rxx-base64 | 159.223.157.129 |
| 80.89 | trojan | 248.9 | 679.0 | 22.02 | 0.0 | 10.0 | 13.45 | 18.42 | Au1rxx-base64 | 153.75.250.171 |
| 79.34 | shadowsocks | 230.3 | 640.1 | 22.45 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 37.19.198.160 |
| 79.32 | shadowsocks | 231.0 | 638.5 | 22.43 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 37.19.198.244 |
| 78.55 | shadowsocks | 242.5 | 644.8 | 22.16 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 108.181.57.93 |
| 78.19 | shadowsocks | 280.0 | 788.1 | 21.3 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 37.19.198.236 |
| 77.87 | shadowsocks | 293.7 | 826.4 | 20.98 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 37.19.198.243 |
| 77.59 | shadowsocks | 284.1 | 656.0 | 21.2 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 68.168.222.210 |
| 76.02 | shadowsocks | 278.6 | 634.6 | 21.33 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 156.146.38.168 |
| 75.82 | shadowsocks | 348.6 | 859.8 | 19.71 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 185.196.61.82 |
| 75.36 | shadowsocks | 287.7 | 669.2 | 21.12 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 156.146.38.167 |
| 74.92 | trojan | 317.8 | 661.9 | 20.42 | 0.0 | 10.0 | 13.45 | 18.42 | Au1rxx-base64 | 163.245.196.68 |
| 74.75 | hysteria2 | 369.3 | 710.3 | 19.23 | 0.0 | 9.8 | 14.12 | 18.42 | Au1rxx-base64 | 178.215.238.30 |
| 74.7 | shadowsocks | 322.8 | 892.9 | 20.31 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 185.232.22.18 |
| 74.44 | shadowsocks | 333.7 | 894.5 | 20.05 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 146.70.34.226 |
| 74.28 | shadowsocks | 287.8 | 658.2 | 21.11 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 156.146.38.170 |
| 74.2 | shadowsocks | 348.1 | 838.5 | 19.72 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 156.146.38.169 |
| 74.18 | vless | 271.8 | 708.4 | 21.49 | 0.0 | 10.0 | 9.21 | 14.48 | DeltaKronecker-all | 78.153.155.112 |
| 74.0 | trojan | 328.7 | 742.0 | 20.17 | 0.0 | 10.0 | 13.45 | 18.42 | Au1rxx-base64 | 64.94.95.114 |
| 73.93 | shadowsocks | 312.7 | 851.3 | 20.54 | 0.0 | 10.0 | 12.47 | 18.42 | Au1rxx-base64 | 185.232.22.28 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | 1.0 | 95 | 167 | prefer |
| Au1rxx-base64 | 0.905 | 0.858 | 268 | 1232 | prefer |
| Surfboard-tg-mixed | 0.68 | 0.609 | 23 | 5706 | observe |
| DeltaKronecker-all | 0.461 | 0.381 | 693 | 5519 | observe |
| mheidari-all | 0.286 | 0.231 | 13 | 15942 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5118 | observe |
| Epodonios-all | 0.255 | None | 0 | 6451 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6039 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4505 | observe |
| barry-far-vless | 0.255 | None | 0 | 4902 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5089 | observe |
| nscl5-all | 0.246 | None | 0 | 1774 | observe |
| Au1rxx-clash | 0.224 | None | 0 | 1232 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 217 |
| speed | TimeoutError | - | 58 |
| geo | ClientOSError | - | 50 |
| speed | ClientOSError | - | 47 |
| 204 | ProxyError | - | 42 |
| 204 | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 25 |
| cn-block | ProxyError | - | 11 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| geo | ProxyError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
