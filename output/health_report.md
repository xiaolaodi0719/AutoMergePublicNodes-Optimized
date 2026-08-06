# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-06 08:48:49 |
| 运行耗时 | 221.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 88936 |
| 去重后节点 | 24432 |
| TCP 可达 | 3000 |
| 真实可用 | 447 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24432 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.5 |
| tcp | 36.6 |
| probe | 50.9 |
| real_test | 92.6 |
| generate | 34.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51846 |
| vmess | 13334 |
| trojan | 11885 |
| shadowsocks | 10161 |
| hysteria2 | 1453 |
| socks | 89 |
| shadowsocksr | 79 |
| anytls | 30 |
| http | 24 |
| hysteria | 21 |
| tuic | 14 |

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
| 84.51 | hysteria2 | 228.3 | 628.2 | 22.49 | 0.0 | 10.0 | 13.12 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 84.07 | hysteria2 | 251.8 | 697.3 | 21.95 | 0.0 | 10.0 | 13.12 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.87 | hysteria2 | 260.6 | 720.0 | 21.75 | 0.0 | 10.0 | 13.12 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 82.35 | shadowsocks | 245.8 | 670.6 | 22.09 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 79.77 | shadowsocks | 357.3 | 1014.4 | 19.51 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 78.66 | shadowsocks | 405.0 | 1144.4 | 18.4 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 77.15 | shadowsocks | 384.6 | 957.2 | 18.87 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 76.83 | shadowsocks | 394.4 | 987.7 | 18.65 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 76.77 | shadowsocks | 389.4 | 975.6 | 18.76 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 76.5 | trojan | 539.0 | 1550.0 | 15.3 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 153.75.250.171 |
| 76.45 | trojan | 383.1 | 887.4 | 18.91 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 163.245.196.68 |
| 76.32 | shadowsocks | 393.9 | 974.9 | 18.66 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 75.74 | hysteria2 | 355.7 | 688.3 | 19.54 | 0.0 | 10.0 | 13.12 | 20.0 | Au1rxx-base64 | 62.210.124.146 |
| 75.67 | shadowsocks | 303.6 | 591.2 | 20.75 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 75.52 | shadowsocks | 308.4 | 606.0 | 20.64 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 75.17 | shadowsocks | 318.5 | 586.7 | 20.41 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 74.84 | shadowsocks | 413.5 | 995.5 | 18.2 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 74.06 | vless | 269.2 | 642.6 | 21.55 | 0.0 | 10.0 | 5.51 | 20.0 | Au1rxx-base64 | 170.114.45.239 |
| 73.29 | trojan | 399.8 | 659.2 | 18.52 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 73.2 | shadowsocks | 383.2 | 733.7 | 18.91 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 108.181.118.10 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.986 | 0.932 | 353 | 1409 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.662 | 0.583 | 132 | 5873 | observe |
| DeltaKronecker-all | 0.515 | 0.429 | 21 | 5897 | observe |
| mheidari-all | 0.366 | 0.275 | 40 | 20781 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5219 | observe |
| Epodonios-all | 0.255 | None | 0 | 6505 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7196 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4677 | observe |
| barry-far-vless | 0.255 | None | 0 | 5049 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5212 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.24 | None | 0 | 1621 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 40 |
| geo | ClientOSError | - | 19 |
| 204 | ProxyError | - | 13 |
| 204 | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 9 |
| cn-block | TimeoutError | - | 9 |
| speed | TimeoutError | - | 9 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
