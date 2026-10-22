# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 11:37:36 |
| 运行耗时 | 527.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 95605 |
| 去重后节点 | 26650 |
| TCP 可达 | 3000 |
| 真实可用 | 292 |
| Verified 输出 | 292 |
| Global 输出 | 300 |
| All 输出 | 26650 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.6 |
| tcp | 44.9 |
| probe | 171.5 |
| real_test | 219.3 |
| generate | 82.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56547 |
| vmess | 17131 |
| shadowsocks | 12113 |
| trojan | 8090 |
| hysteria2 | 1273 |
| http | 193 |
| shadowsocksr | 161 |
| socks | 53 |
| anytls | 21 |
| hysteria | 17 |
| tuic | 6 |

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
| 81.64 | hysteria2 | 252.0 | 623.7 | 21.95 | 0.0 | 10.0 | 13.93 | 19.76 | Au1rxx-base64 | clash2.deep-links.com |
| 81.63 | shadowsocks | 254.7 | 619.8 | 21.88 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 156.146.38.167 |
| 80.87 | shadowsocks | 266.2 | 685.0 | 21.62 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 193.151.163.18 |
| 80.84 | shadowsocks | 267.4 | 701.7 | 21.59 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 185.230.230.18 |
| 80.25 | shadowsocks | 314.3 | 827.4 | 20.5 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 37.19.198.243 |
| 80.22 | shadowsocks | 315.8 | 619.5 | 20.47 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 37.19.198.160 |
| 80.18 | shadowsocks | 317.5 | 805.9 | 20.43 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 156.146.38.169 |
| 79.26 | shadowsocks | 335.4 | 892.1 | 20.01 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 185.215.132.18 |
| 78.91 | shadowsocks | 350.5 | 939.1 | 19.66 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 45.86.51.18 |
| 78.53 | shadowsocks | 302.2 | 780.7 | 20.78 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 37.19.198.236 |
| 78.52 | trojan | 284.3 | 669.6 | 21.2 | 0.0 | 10.0 | 10.98 | 19.76 | Au1rxx-base64 | 66.23.203.21 |
| 77.67 | shadowsocks | 365.4 | 921.3 | 19.32 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 193.151.160.18 |
| 76.61 | shadowsocks | 255.8 | 624.7 | 21.86 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 156.146.38.168 |
| 76.5 | shadowsocks | 338.8 | 818.1 | 19.94 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 51.222.136.236 |
| 76.18 | shadowsocks | 395.3 | 1006.5 | 18.63 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 193.151.160.9 |
| 75.99 | shadowsocks | 357.5 | 947.4 | 19.5 | 0.0 | 10.0 | 13.99 | 17.0 | Surfboard-tg-mixed | 185.215.132.9 |
| 75.97 | vless | 323.1 | 684.0 | 20.3 | 0.0 | 10.0 | 6.02 | 19.76 | Au1rxx-base64 | 169.40.42.104 |
| 75.89 | trojan | 308.0 | 822.5 | 20.65 | 0.0 | 10.0 | 10.98 | 19.76 | Au1rxx-base64 | 155.138.138.2 |
| 75.64 | shadowsocks | 297.5 | 750.5 | 20.89 | 0.0 | 10.0 | 13.99 | 19.76 | Au1rxx-base64 | 156.146.38.170 |
| 75.5 | vless | 286.2 | 692.7 | 21.15 | 0.0 | 10.0 | 6.02 | 19.76 | Au1rxx-base64 | 167.17.69.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.854 | 0.793 | 29 | 23951 | prefer |
| Au1rxx-base64 | 0.828 | 0.769 | 251 | 1526 | prefer |
| zhangkai | 0.82 | 0.85 | 20 | 45 | prefer |
| Surfboard-tg-mixed | 0.759 | 0.683 | 82 | 7043 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7460 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10067 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5382 | observe |
| barry-far-vless | 0.255 | None | 0 | 5666 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.236 | None | 0 | 1526 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 23 |
| 204 | ProxyError | - | 21 |
| 204 | TimeoutError | - | 21 |
| speed | TimeoutError | - | 11 |
| speed | ClientOSError | - | 11 |
| geo | ClientOSError | - | 7 |
| geo | TimeoutError | - | 7 |
| 204 | ProxyConnectionError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 292 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
