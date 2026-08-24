# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-24 18:52:10 |
| 运行耗时 | 262.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 84125 |
| 去重后节点 | 23818 |
| TCP 可达 | 3000 |
| 真实可用 | 590 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23818 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.5 |
| tcp | 37.3 |
| probe | 58.6 |
| real_test | 126.0 |
| generate | 32.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53013 |
| shadowsocks | 10666 |
| vmess | 10397 |
| trojan | 8172 |
| hysteria2 | 1489 |
| http | 164 |
| shadowsocksr | 128 |
| socks | 76 |
| hysteria | 13 |
| tuic | 5 |
| anytls | 2 |

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
| 79.8 | shadowsocks | 263.5 | 623.8 | 21.68 | 0.0 | 10.0 | 13.8 | 18.72 | Au1rxx-base64 | 155.138.136.240 |
| 79.53 | vless | 284.3 | 659.1 | 21.2 | 0.0 | 10.0 | 11.11 | 18.72 | Au1rxx-base64 | 198.251.78.29 |
| 79.14 | hysteria2 | 346.9 | 692.9 | 19.75 | 0.0 | 10.0 | 14.32 | 16.6 | mheidari-all | 159.223.157.129 |
| 78.67 | trojan | 332.0 | 852.7 | 20.09 | 0.0 | 10.0 | 12.86 | 18.72 | Au1rxx-base64 | 64.94.95.118 |
| 78.56 | shadowsocks | 235.1 | 599.9 | 22.34 | 0.0 | 10.0 | 13.8 | 16.42 | Surfboard-tg-mixed | 156.146.38.169 |
| 77.98 | shadowsocks | 259.8 | 626.1 | 21.76 | 0.0 | 10.0 | 13.8 | 16.42 | Surfboard-tg-mixed | 156.146.38.168 |
| 77.83 | shadowsocks | 266.6 | 625.3 | 21.61 | 0.0 | 10.0 | 13.8 | 16.42 | Surfboard-tg-mixed | 156.146.38.167 |
| 77.23 | shadowsocks | 278.7 | 646.5 | 21.33 | 0.0 | 10.0 | 13.8 | 16.6 | mheidari-all | 37.19.198.160 |
| 77.14 | trojan | 325.7 | 847.1 | 20.24 | 0.0 | 10.0 | 12.86 | 18.72 | Au1rxx-base64 | 64.94.95.115 |
| 76.3 | shadowsocks | 307.3 | 755.9 | 20.66 | 0.0 | 10.0 | 13.8 | 18.72 | Au1rxx-base64 | 15.204.247.175 |
| 76.25 | vless | 376.7 | 887.9 | 19.06 | 0.0 | 10.0 | 11.11 | 18.72 | Au1rxx-base64 | 137.184.218.169 |
| 76.21 | shadowsocks | 275.7 | 585.0 | 21.4 | 0.0 | 10.0 | 13.8 | 18.72 | Au1rxx-base64 | 154.12.240.141 |
| 76.08 | shadowsocks | 248.8 | 598.5 | 22.02 | 0.0 | 10.0 | 13.8 | 16.6 | mheidari-all | 23.150.248.20 |
| 76.06 | vless | 283.0 | 651.4 | 21.23 | 0.0 | 10.0 | 11.11 | 18.72 | Au1rxx-base64 | 195.211.99.49 |
| 75.91 | trojan | 359.8 | 932.9 | 19.45 | 0.0 | 10.0 | 12.86 | 16.6 | mheidari-all | 64.94.95.117 |
| 75.91 | vless | 388.0 | 941.7 | 18.8 | 0.0 | 10.0 | 11.11 | 18.72 | Au1rxx-base64 | 216.152.147.28 |
| 75.68 | vless | 325.0 | 637.0 | 20.25 | 0.0 | 10.0 | 11.11 | 18.72 | Au1rxx-base64 | 15.204.97.195 |
| 75.53 | vless | 406.2 | 670.7 | 18.37 | 0.0 | 10.0 | 11.11 | 18.72 | Au1rxx-base64 | 38.180.242.205 |
| 75.5 | trojan | 320.7 | 832.0 | 20.36 | 0.0 | 10.0 | 12.86 | 16.6 | mheidari-all | 64.94.95.114 |
| 75.24 | shadowsocks | 273.7 | 573.7 | 21.44 | 0.0 | 10.0 | 13.8 | 18.72 | Au1rxx-base64 | 94.72.127.58 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.961 | 0.892 | 370 | 1779 | prefer |
| Surfboard-tg-mixed | 0.942 | 0.87 | 92 | 6457 | prefer |
| mheidari-all | 0.805 | 0.729 | 118 | 19577 | prefer |
| DeltaKronecker-all | 0.653 | 0.574 | 122 | 5914 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4899 | observe |
| Epodonios-all | 0.255 | None | 0 | 6977 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7298 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5373 | observe |
| barry-far-vless | 0.255 | None | 0 | 5662 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4132 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1780 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 36 |
| 204 | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 24 |
| geo | ClientOSError | - | 22 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| 204 | ProxyError | - | 4 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
