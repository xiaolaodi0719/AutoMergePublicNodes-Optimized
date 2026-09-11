# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 11:08:49 |
| 运行耗时 | 720.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84388 |
| 去重后节点 | 23243 |
| TCP 可达 | 3000 |
| 真实可用 | 426 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23243 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 40.1 |
| probe | 284.7 |
| real_test | 309.0 |
| generate | 79.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51448 |
| vmess | 12338 |
| shadowsocks | 10033 |
| trojan | 8112 |
| hysteria2 | 1598 |
| http | 650 |
| shadowsocksr | 132 |
| socks | 55 |
| tuic | 12 |
| hysteria | 8 |
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
| 81.75 | hysteria2 | 233.5 | 627.9 | 22.37 | 0.0 | 10.0 | 12.86 | 17.62 | Au1rxx-base64 | 159.223.157.129 |
| 80.41 | shadowsocks | 228.1 | 598.7 | 22.5 | 0.0 | 10.0 | 14.29 | 17.62 | Au1rxx-base64 | 198.98.53.130 |
| 79.9 | shadowsocks | 250.2 | 677.8 | 21.99 | 0.0 | 10.0 | 14.29 | 17.62 | Au1rxx-base64 | 37.19.198.243 |
| 79.72 | shadowsocks | 257.6 | 694.6 | 21.81 | 0.0 | 10.0 | 14.29 | 17.62 | Au1rxx-base64 | 37.19.198.244 |
| 79.61 | shadowsocks | 274.3 | 629.8 | 21.43 | 0.0 | 10.0 | 14.29 | 20.0 | mheidari-all | 156.146.38.169 |
| 78.15 | shadowsocks | 303.9 | 764.5 | 20.74 | 0.0 | 10.0 | 14.29 | 17.62 | Au1rxx-base64 | 51.222.200.165 |
| 77.95 | shadowsocks | 253.2 | 679.9 | 21.92 | 0.0 | 10.0 | 14.29 | 15.74 | Surfboard-tg-mixed | 37.19.198.160 |
| 77.8 | shadowsocks | 259.5 | 704.9 | 21.77 | 0.0 | 10.0 | 14.29 | 15.74 | Surfboard-tg-mixed | 37.19.198.236 |
| 76.94 | shadowsocks | 356.2 | 925.9 | 19.53 | 0.0 | 10.0 | 14.29 | 17.62 | Au1rxx-base64 | 38.180.135.156 |
| 76.72 | vless | 244.4 | 685.1 | 22.12 | 0.0 | 10.0 | 6.98 | 17.62 | Au1rxx-base64 | 79.141.172.154 |
| 76.69 | shadowsocks | 282.8 | 654.4 | 21.23 | 0.0 | 10.0 | 14.29 | 17.62 | Au1rxx-base64 | 156.146.38.168 |
| 76.67 | vless | 246.6 | 632.7 | 22.07 | 0.0 | 10.0 | 6.98 | 17.62 | Au1rxx-base64 | 195.123.235.177 |
| 76.51 | vless | 253.5 | 697.3 | 21.91 | 0.0 | 10.0 | 6.98 | 17.62 | Au1rxx-base64 | 47.253.226.114 |
| 76.4 | shadowsocks | 286.0 | 656.1 | 21.16 | 0.0 | 10.0 | 14.29 | 17.62 | Au1rxx-base64 | 156.146.38.170 |
| 76.27 | vless | 264.0 | 669.9 | 21.67 | 0.0 | 10.0 | 6.98 | 17.62 | Au1rxx-base64 | 169.40.42.95 |
| 76.09 | vless | 271.6 | 691.5 | 21.49 | 0.0 | 10.0 | 6.98 | 17.62 | Au1rxx-base64 | 167.17.69.171 |
| 76.06 | vless | 248.3 | 652.3 | 22.03 | 0.0 | 10.0 | 6.98 | 17.62 | Au1rxx-base64 | 137.184.218.169 |
| 75.88 | vless | 280.6 | 669.7 | 21.28 | 0.0 | 10.0 | 6.98 | 17.62 | Au1rxx-base64 | 169.40.42.15 |
| 75.85 | vless | 282.1 | 725.1 | 21.25 | 0.0 | 10.0 | 6.98 | 17.62 | Au1rxx-base64 | 169.40.42.229 |
| 75.6 | shadowsocks | 414.1 | 1155.3 | 18.19 | 0.0 | 10.0 | 14.29 | 17.62 | Au1rxx-base64 | 15.204.247.206 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | 0.865 | 274 | 1772 | prefer |
| DeltaKronecker-all | 0.823 | 0.758 | 33 | 6070 | prefer |
| ermaozi | 0.79 | 0.786 | 42 | 431 | prefer |
| Surfboard-tg-mixed | 0.756 | 0.679 | 137 | 7422 | prefer |
| mheidari-all | 0.724 | 0.649 | 57 | 15701 | prefer |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 199 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7889 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8749 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5995 | observe |
| barry-far-vless | 0.255 | None | 0 | 6213 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1772 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 26 |
| 204 | TimeoutError | - | 23 |
| speed | TimeoutError | - | 17 |
| 204 | ProxyError | - | 15 |
| cn-block | TimeoutError | - | 15 |
| 204 | ClientOSError | - | 7 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
