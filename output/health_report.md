# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-09 13:07:49 |
| 运行耗时 | 810.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98198 |
| 去重后节点 | 27457 |
| TCP 可达 | 3000 |
| 真实可用 | 407 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27457 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.7 |
| tcp | 47.3 |
| probe | 305.5 |
| real_test | 360.4 |
| generate | 87.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57720 |
| vmess | 15607 |
| shadowsocks | 11985 |
| trojan | 10661 |
| hysteria2 | 1482 |
| http | 437 |
| shadowsocksr | 166 |
| socks | 80 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 13 |

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
| 81.62 | shadowsocks | 243.7 | 625.3 | 22.14 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 156.146.38.169 |
| 80.23 | hysteria2 | 318.9 | 740.3 | 20.4 | 0.0 | 10.0 | 13.85 | 19.58 | Au1rxx-base64 | 129.213.91.185 |
| 79.63 | shadowsocks | 243.1 | 613.5 | 22.15 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 156.146.38.170 |
| 79.62 | shadowsocks | 243.5 | 624.7 | 22.14 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 156.146.38.167 |
| 78.26 | hysteria2 | 332.3 | 678.0 | 20.09 | 0.0 | 10.0 | 13.85 | 19.58 | Au1rxx-base64 | 66.94.121.46 |
| 77.74 | hysteria2 | 294.9 | 274.4 | 20.95 | 4.71 | 6.52 | 13.85 | 19.58 | Au1rxx-base64 | open.2ml.bid |
| 76.78 | hysteria2 | 320.6 | 370.7 | 20.36 | 1.1 | 9.76 | 13.85 | 19.58 | Au1rxx-base64 | 158.101.148.79 |
| 76.22 | shadowsocks | 302.3 | 297.6 | 20.78 | 3.84 | 9.76 | 13.9 | 19.58 | Au1rxx-base64 | 149.22.87.240 |
| 76.02 | shadowsocks | 305.1 | 304.5 | 20.72 | 3.58 | 9.79 | 13.9 | 19.58 | Au1rxx-base64 | 149.22.87.241 |
| 75.95 | shadowsocks | 351.9 | 888.8 | 19.63 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 66.23.204.214 |
| 75.8 | shadowsocks | 340.3 | 771.2 | 19.9 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 37.19.198.244 |
| 75.68 | shadowsocks | 347.0 | 786.8 | 19.74 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 37.19.198.243 |
| 75.59 | shadowsocks | 346.0 | 786.0 | 19.77 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 37.19.198.236 |
| 75.22 | shadowsocks | 314.7 | 658.2 | 20.49 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 149.22.95.183 |
| 75.12 | vless | 305.8 | 735.2 | 20.7 | 0.0 | 10.0 | 5.87 | 19.58 | Au1rxx-base64 | 144.202.126.147 |
| 75.01 | shadowsocks | 309.6 | 672.9 | 20.61 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 173.244.56.9 |
| 74.62 | vless | 274.2 | 607.8 | 21.43 | 0.0 | 10.0 | 5.87 | 19.58 | Au1rxx-base64 | 15.204.97.197 |
| 73.81 | vless | 271.3 | 594.7 | 21.5 | 0.0 | 10.0 | 5.87 | 19.58 | Au1rxx-base64 | 15.204.97.216 |
| 73.47 | shadowsocks | 306.1 | 747.5 | 20.69 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 5.78.51.123 |
| 73.26 | vless | 237.1 | 523.0 | 22.29 | 0.0 | 10.0 | 5.87 | 19.58 | Au1rxx-base64 | 47.251.108.158 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.904 | 0.833 | 342 | 1810 | prefer |
| zhangkai | 0.881 | 0.909 | 22 | 144 | prefer |
| mheidari-all | 0.747 | 0.675 | 40 | 23165 | prefer |
| Surfboard-tg-mixed | 0.649 | 0.57 | 100 | 7139 | observe |
| DeltaKronecker-all | 0.465 | 0.375 | 24 | 5154 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4984 | observe |
| Epodonios-all | 0.255 | None | 0 | 7541 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10038 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5578 | observe |
| barry-far-vless | 0.255 | None | 0 | 5830 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4362 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 49 |
| cn-block | TimeoutError | - | 32 |
| 204 | ProxyError | - | 30 |
| 204 | ProxyConnectionError | - | 10 |
| geo | ClientOSError | - | 10 |
| speed | TimeoutError | - | 9 |
| geo | TimeoutError | - | 9 |
| speed | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
