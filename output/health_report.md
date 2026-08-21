# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-21 01:45:18 |
| 运行耗时 | 382.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 95323 |
| 去重后节点 | 25208 |
| TCP 可达 | 3000 |
| 真实可用 | 1235 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25208 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 40.0 |
| probe | 74.7 |
| real_test | 232.4 |
| generate | 26.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51235 |
| trojan | 19319 |
| shadowsocks | 11363 |
| vmess | 10413 |
| hysteria2 | 2456 |
| shadowsocksr | 192 |
| http | 164 |
| socks | 124 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 10 |

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
| 82.93 | hysteria2 | 284.4 | 706.2 | 21.19 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 81.89 | shadowsocks | 261.1 | 660.1 | 21.73 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 81.66 | shadowsocks | 271.1 | 691.4 | 21.5 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 81.28 | vless | 216.0 | 592.9 | 22.78 | 0.0 | 10.0 | 10.54 | 17.96 | mheidari-all | 195.211.98.214 |
| 81.25 | vless | 217.1 | 592.0 | 22.75 | 0.0 | 10.0 | 10.54 | 17.96 | mheidari-all | 195.211.99.49 |
| 81.04 | shadowsocks | 260.0 | 640.2 | 21.76 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 80.9 | shadowsocks | 293.4 | 790.6 | 20.99 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 80.84 | shadowsocks | 306.4 | 797.8 | 20.68 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 80.75 | shadowsocks | 262.2 | 642.4 | 21.71 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.62 | shadowsocks | 273.0 | 697.5 | 21.46 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 80.61 | shadowsocks | 259.0 | 628.4 | 21.78 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 80.47 | shadowsocks | 322.8 | 824.8 | 20.31 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 142.4.216.225 |
| 80.44 | shadowsocks | 283.3 | 641.2 | 21.22 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 80.03 | hysteria2 | 298.0 | 293.5 | 20.88 | 3.99 | 8.9 | 14.17 | 20.0 | Au1rxx-base64 | 45.32.252.144 |
| 79.84 | hysteria2 | 325.6 | 617.3 | 20.24 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 150.241.102.127 |
| 78.99 | vless | 296.1 | 730.2 | 20.92 | 0.0 | 10.0 | 10.54 | 17.96 | mheidari-all | 204.48.20.223 |
| 78.61 | vless | 331.1 | 890.7 | 20.11 | 0.0 | 10.0 | 10.54 | 17.96 | mheidari-all | 216.152.147.28 |
| 77.81 | vless | 365.6 | 922.4 | 19.31 | 0.0 | 10.0 | 10.54 | 17.96 | mheidari-all | 167.17.69.171 |
| 77.33 | shadowsocks | 404.7 | 981.6 | 18.41 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 51.222.12.127 |
| 77.32 | vless | 360.1 | 900.8 | 19.44 | 0.0 | 10.0 | 10.54 | 17.96 | mheidari-all | 169.40.42.231 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.984 | 567 | 1663 | prefer |
| Surfboard-tg-mixed | 1.0 | 0.936 | 109 | 6412 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| mheidari-all | 0.686 | 0.607 | 750 | 21987 | observe |
| nscl5-all | 0.391 | 1.0 | 2 | 3031 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| Epodonios-all | 0.255 | None | 0 | 7184 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7304 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5053 | observe |
| barry-far-vless | 0.255 | None | 0 | 5451 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4586 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |
| DeltaKronecker-all | 0.251 | 0.154 | 39 | 6781 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1663 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 131 |
| geo | ClientOSError | - | 101 |
| speed | TimeoutError | - | 71 |
| speed | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 9 |
| 204 | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 2 |
| 204 | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
