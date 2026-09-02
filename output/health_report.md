# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-02 11:03:04 |
| 运行耗时 | 289.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82681 |
| 去重后节点 | 23587 |
| TCP 可达 | 3000 |
| 真实可用 | 598 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23587 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.4 |
| tcp | 38.5 |
| probe | 85.7 |
| real_test | 121.7 |
| generate | 36.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51879 |
| vmess | 11142 |
| shadowsocks | 9912 |
| trojan | 7811 |
| hysteria2 | 1571 |
| http | 144 |
| shadowsocksr | 126 |
| socks | 78 |
| tuic | 11 |
| hysteria | 7 |

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
| 82.05 | shadowsocks | 236.0 | 622.3 | 22.31 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 156.146.38.170 |
| 81.99 | shadowsocks | 239.0 | 593.2 | 22.25 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 156.146.38.167 |
| 81.49 | shadowsocks | 260.3 | 618.1 | 21.75 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 156.146.38.169 |
| 80.57 | shadowsocks | 300.0 | 794.0 | 20.83 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 156.146.38.168 |
| 80.56 | shadowsocks | 286.0 | 664.7 | 21.16 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 37.19.198.243 |
| 79.96 | shadowsocks | 283.4 | 658.9 | 21.22 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 37.19.198.244 |
| 79.91 | hysteria2 | 260.8 | 572.3 | 21.74 | 0.0 | 10.0 | 12.0 | 19.4 | Au1rxx-base64 | 66.94.121.46 |
| 79.29 | shadowsocks | 288.9 | 701.2 | 21.09 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 37.19.198.160 |
| 79.26 | shadowsocks | 291.5 | 681.5 | 21.03 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 37.19.198.236 |
| 78.25 | vless | 266.7 | 611.8 | 21.6 | 0.0 | 10.0 | 8.16 | 19.4 | Au1rxx-base64 | 195.211.99.45 |
| 77.52 | vless | 257.5 | 628.2 | 21.82 | 0.0 | 10.0 | 8.16 | 19.4 | Au1rxx-base64 | 195.211.99.49 |
| 76.21 | shadowsocks | 282.2 | 558.3 | 21.24 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 149.22.95.183 |
| 75.97 | vless | 349.2 | 850.0 | 19.69 | 0.0 | 10.0 | 8.16 | 19.4 | Au1rxx-base64 | 172.105.104.54 |
| 75.95 | trojan | 336.0 | 821.7 | 20.0 | 0.0 | 10.0 | 9.55 | 19.4 | Au1rxx-base64 | 64.94.95.117 |
| 75.69 | trojan | 347.1 | 914.7 | 19.74 | 0.0 | 10.0 | 9.55 | 19.4 | Au1rxx-base64 | 64.94.95.115 |
| 75.68 | shadowsocks | 347.7 | 750.6 | 19.73 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 108.181.57.93 |
| 75.42 | shadowsocks | 352.9 | 702.1 | 19.61 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 173.244.56.6 |
| 74.89 | vless | 328.0 | 739.6 | 20.18 | 0.0 | 10.0 | 8.16 | 19.4 | Au1rxx-base64 | 169.40.42.232 |
| 74.89 | shadowsocks | 402.5 | 985.6 | 18.46 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 38.180.135.156 |
| 74.75 | shadowsocks | 364.5 | 849.7 | 19.34 | 0.0 | 10.0 | 14.34 | 19.4 | Au1rxx-base64 | 142.4.216.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| Au1rxx-base64 | 0.952 | 0.881 | 411 | 1826 | prefer |
| mheidari-all | 0.819 | 0.744 | 117 | 15813 | prefer |
| Surfboard-tg-mixed | 0.784 | 0.706 | 160 | 7112 | prefer |
| DeltaKronecker-all | 0.618 | 0.542 | 24 | 7295 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 102 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 47 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4765 | observe |
| Epodonios-all | 0.255 | None | 0 | 7428 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7727 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5992 | observe |
| barry-far-vless | 0.255 | None | 0 | 6070 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4066 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1826 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 26 |
| geo | ClientOSError | - | 23 |
| 204 | TimeoutError | - | 23 |
| 204 | ProxyError | - | 15 |
| geo | TimeoutError | - | 12 |
| speed | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 9 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
