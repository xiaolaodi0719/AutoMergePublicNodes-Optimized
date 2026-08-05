# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-05 08:47:08 |
| 运行耗时 | 238.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85532 |
| 去重后节点 | 23905 |
| TCP 可达 | 3000 |
| 真实可用 | 511 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23905 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.4 |
| tcp | 35.4 |
| probe | 52.7 |
| real_test | 111.3 |
| generate | 29.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49981 |
| vmess | 13062 |
| trojan | 10665 |
| shadowsocks | 10250 |
| hysteria2 | 1291 |
| socks | 80 |
| http | 76 |
| shadowsocksr | 73 |
| anytls | 21 |
| hysteria | 19 |
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
| 84.94 | hysteria2 | 232.4 | 640.9 | 22.4 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 84.85 | hysteria2 | 240.5 | 670.7 | 22.21 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 84.06 | hysteria2 | 246.3 | 675.4 | 22.08 | 0.0 | 9.34 | 13.64 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 82.31 | shadowsocks | 236.9 | 656.8 | 22.29 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 82.29 | shadowsocks | 238.1 | 655.4 | 22.27 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 79.26 | hysteria2 | 314.8 | 292.2 | 20.49 | 4.04 | 9.36 | 13.64 | 20.0 | Au1rxx-base64 | 45.76.202.45 |
| 79.18 | shadowsocks | 242.9 | 667.3 | 22.16 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 79.18 | shadowsocks | 282.4 | 653.5 | 21.24 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 78.76 | shadowsocks | 347.3 | 878.0 | 19.74 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 185.196.61.82 |
| 78.28 | shadowsocks | 275.0 | 623.1 | 21.41 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 78.12 | shadowsocks | 279.8 | 648.9 | 21.3 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 77.81 | http | 479.6 | 1356.3 | 16.68 | 0.0 | 10.0 | 14.45 | 19.68 | zhangkai | 156.146.59.33 |
| 77.59 | trojan | 307.7 | 668.7 | 20.66 | 0.0 | 10.0 | 13.66 | 20.0 | Au1rxx-base64 | 163.245.196.68 |
| 76.76 | hysteria2 | 351.3 | 683.0 | 19.65 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 62.210.124.146 |
| 76.54 | shadowsocks | 311.6 | 869.3 | 20.57 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 68.168.222.210 |
| 76.26 | shadowsocks | 321.0 | 729.6 | 20.35 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 76.25 | shadowsocks | 287.0 | 658.7 | 21.14 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 76.17 | trojan | 529.8 | 1521.7 | 15.51 | 0.0 | 10.0 | 13.66 | 20.0 | Au1rxx-base64 | 153.75.250.171 |
| 75.63 | shadowsocks | 230.2 | 585.4 | 22.45 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 198.98.53.130 |
| 75.63 | hysteria2 | 418.0 | 857.0 | 18.1 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 194.180.174.69 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.984 | 1.0 | 50 | 72 | prefer |
| Au1rxx-base64 | 0.969 | 0.915 | 401 | 1403 | prefer |
| Surfboard-tg-mixed | 0.68 | 0.602 | 128 | 5560 | observe |
| DeltaKronecker-all | 0.413 | 0.318 | 22 | 5316 | observe |
| mheidari-all | 0.369 | 0.278 | 36 | 20226 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5260 | observe |
| Epodonios-all | 0.255 | None | 0 | 6163 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6818 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4397 | observe |
| barry-far-vless | 0.255 | None | 0 | 4823 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5147 | observe |
| nscl5-all | 0.239 | None | 0 | 1594 | observe |
| Au1rxx-clash | 0.231 | None | 0 | 1403 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 41 |
| 204 | TimeoutError | - | 17 |
| speed | TimeoutError | - | 15 |
| 204 | ProxyError | - | 14 |
| geo | ClientOSError | - | 12 |
| 204 | ClientOSError | - | 9 |
| speed | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
