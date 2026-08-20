# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-20 18:52:09 |
| 运行耗时 | 334.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 95001 |
| 去重后节点 | 25243 |
| TCP 可达 | 3000 |
| 真实可用 | 1065 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25243 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 0.6 |
| tcp | 38.9 |
| probe | 65.6 |
| real_test | 179.4 |
| generate | 44.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53036 |
| trojan | 18758 |
| shadowsocks | 10564 |
| vmess | 10414 |
| hysteria2 | 1673 |
| shadowsocksr | 202 |
| http | 164 |
| socks | 131 |
| anytls | 32 |
| hysteria | 15 |
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
| 82.48 | hysteria2 | 271.5 | 260.2 | 21.49 | 5.24 | 9.6 | 13.75 | 20.0 | Au1rxx-base64 | 45.32.252.144 |
| 82.16 | shadowsocks | 249.8 | 624.1 | 21.99 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 81.2 | shadowsocks | 291.4 | 732.2 | 21.03 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 80.83 | trojan | 262.0 | 604.2 | 21.71 | 0.0 | 10.0 | 14.82 | 17.42 | mheidari-all | 64.94.95.117 |
| 79.36 | trojan | 266.5 | 674.3 | 21.61 | 0.0 | 10.0 | 14.82 | 17.42 | mheidari-all | 64.94.95.114 |
| 78.95 | shadowsocks | 289.7 | 678.6 | 21.07 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 78.93 | vless | 259.6 | 613.9 | 21.77 | 0.0 | 10.0 | 10.58 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 78.28 | http | 298.7 | 590.5 | 20.86 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |
| 77.75 | http | 301.7 | 562.5 | 20.79 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 77.53 | vless | 336.0 | 778.0 | 20.0 | 0.0 | 10.0 | 10.58 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 77.52 | vless | 314.1 | 691.0 | 20.51 | 0.0 | 10.0 | 10.58 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 77.4 | trojan | 319.8 | 606.3 | 20.37 | 0.0 | 10.0 | 14.82 | 20.0 | Au1rxx-base64 | 35.160.249.189 |
| 77.35 | trojan | 324.6 | 607.2 | 20.26 | 0.0 | 10.0 | 14.82 | 20.0 | Au1rxx-base64 | 34.221.30.108 |
| 77.34 | trojan | 316.2 | 594.7 | 20.46 | 0.0 | 10.0 | 14.82 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 77.2 | trojan | 325.5 | 619.9 | 20.24 | 0.0 | 10.0 | 14.82 | 20.0 | Au1rxx-base64 | 34.220.224.252 |
| 77.18 | shadowsocks | 292.2 | 568.6 | 21.01 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 77.18 | trojan | 326.7 | 622.7 | 20.22 | 0.0 | 10.0 | 14.82 | 20.0 | Au1rxx-base64 | 35.88.120.18 |
| 77.16 | trojan | 426.0 | 1139.2 | 17.92 | 0.0 | 10.0 | 14.82 | 17.42 | mheidari-all | 64.94.95.115 |
| 77.11 | trojan | 328.4 | 625.9 | 20.18 | 0.0 | 10.0 | 14.82 | 20.0 | Au1rxx-base64 | 34.210.213.17 |
| 76.84 | shadowsocks | 245.4 | 520.9 | 22.1 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 209.38.142.23 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.961 | 566 | 1789 | prefer |
| zhangkai | 0.997 | 1.0 | 111 | 144 | prefer |
| mheidari-all | 0.898 | 0.819 | 481 | 22064 | prefer |
| Surfboard-tg-mixed | 0.853 | 0.938 | 16 | 6440 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| Epodonios-all | 0.255 | None | 0 | 7181 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7349 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5117 | observe |
| barry-far-vless | 0.255 | None | 0 | 5501 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4586 | observe |
| nscl5-all | 0.255 | None | 0 | 2418 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1789 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 44 |
| geo | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 11 |
| speed | TimeoutError | - | 10 |
| cn-block | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| speed | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
