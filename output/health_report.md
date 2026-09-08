# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 16:34:43 |
| 运行耗时 | 755.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 90488 |
| 去重后节点 | 25026 |
| TCP 可达 | 3000 |
| 真实可用 | 433 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25026 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 42.6 |
| probe | 283.5 |
| real_test | 329.2 |
| generate | 93.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56381 |
| vmess | 12339 |
| shadowsocks | 10207 |
| trojan | 8933 |
| hysteria2 | 1969 |
| http | 437 |
| shadowsocksr | 129 |
| socks | 54 |
| hysteria | 16 |
| tuic | 13 |
| anytls | 10 |

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
| 81.59 | vless | 231.6 | 598.0 | 22.42 | 0.0 | 9.25 | 11.04 | 18.88 | Au1rxx-base64 | 195.123.235.177 |
| 80.37 | vless | 280.5 | 751.9 | 21.28 | 0.0 | 9.17 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.179 |
| 80.24 | vless | 285.9 | 704.4 | 21.16 | 0.0 | 9.16 | 11.04 | 18.88 | Au1rxx-base64 | 66.70.179.198 |
| 79.7 | shadowsocks | 235.5 | 639.3 | 22.33 | 0.0 | 9.18 | 13.31 | 18.88 | Au1rxx-base64 | 37.19.198.236 |
| 79.18 | vless | 335.4 | 845.2 | 20.01 | 0.0 | 9.35 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.202 |
| 79.02 | vless | 342.9 | 941.9 | 19.84 | 0.0 | 9.26 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.89 |
| 79.0 | vless | 267.3 | 697.9 | 21.59 | 0.0 | 9.36 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.173 |
| 78.58 | vless | 356.1 | 923.4 | 19.53 | 0.0 | 9.13 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.225 |
| 78.55 | vless | 359.3 | 811.3 | 19.46 | 0.0 | 9.17 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.184 |
| 78.53 | vless | 275.1 | 675.5 | 21.41 | 0.0 | 9.17 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.35 |
| 78.41 | vless | 282.8 | 634.2 | 21.23 | 0.0 | 9.12 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.224 |
| 78.35 | hysteria2 | 298.6 | 820.3 | 20.87 | 0.0 | 10.0 | 12.22 | 16.36 | Surfboard-tg-mixed | 159.223.157.129 |
| 78.12 | shadowsocks | 230.2 | 635.3 | 22.45 | 0.0 | 10.0 | 13.31 | 16.36 | Surfboard-tg-mixed | 37.19.198.243 |
| 77.34 | vless | 341.5 | 858.9 | 19.87 | 0.0 | 9.26 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.235 |
| 76.72 | vless | 414.8 | 1071.7 | 18.18 | 0.0 | 9.39 | 11.04 | 18.88 | Au1rxx-base64 | 209.200.246.148 |
| 76.56 | shadowsocks | 243.3 | 666.7 | 22.15 | 0.0 | 10.0 | 13.31 | 15.1 | mheidari-all | 37.19.198.244 |
| 76.45 | vless | 368.1 | 892.1 | 19.26 | 0.0 | 9.21 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.75 |
| 76.41 | vless | 369.7 | 883.5 | 19.22 | 0.0 | 9.17 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.15 |
| 76.12 | shadowsocks | 363.6 | 952.1 | 19.36 | 0.0 | 9.07 | 13.31 | 18.88 | Au1rxx-base64 | 15.204.246.189 |
| 76.09 | vless | 389.0 | 950.9 | 18.77 | 0.0 | 9.17 | 11.04 | 18.88 | Au1rxx-base64 | 169.40.42.95 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | 0.92 | 289 | 1658 | prefer |
| Surfboard-tg-mixed | 0.759 | 0.681 | 135 | 7484 | prefer |
| ermaozi | 0.611 | 0.6 | 35 | 409 | observe |
| mheidari-all | 0.48 | 0.398 | 133 | 21582 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 212 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 6097 | observe |
| Epodonios-all | 0.255 | None | 0 | 7932 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8703 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6283 | observe |
| barry-far-vless | 0.255 | None | 0 | 6501 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4209 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1658 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 41 |
| cn-block | ClientOSError | - | 32 |
| 204 | TimeoutError | - | 31 |
| 204 | ProxyError | - | 21 |
| cn-block | TimeoutError | - | 17 |
| speed | ClientOSError | - | 6 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| speed | TimeoutError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
