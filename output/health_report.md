# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 11:13:55 |
| 运行耗时 | 709.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 85046 |
| 去重后节点 | 22056 |
| TCP 可达 | 3000 |
| 真实可用 | 507 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22056 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.7 |
| tcp | 37.0 |
| probe | 281.8 |
| real_test | 290.1 |
| generate | 92.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52691 |
| vmess | 12037 |
| shadowsocks | 9859 |
| trojan | 7993 |
| hysteria2 | 1628 |
| http | 639 |
| shadowsocksr | 124 |
| socks | 56 |
| hysteria | 9 |
| tuic | 8 |
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
| 81.41 | hysteria2 | 254.1 | 643.9 | 21.9 | 0.0 | 10.0 | 13.85 | 16.76 | Surfboard-tg-mixed | 159.223.157.129 |
| 79.59 | shadowsocks | 245.1 | 639.7 | 22.11 | 0.0 | 10.0 | 13.6 | 17.88 | mheidari-all | 37.19.198.243 |
| 79.57 | shadowsocks | 245.6 | 630.3 | 22.09 | 0.0 | 10.0 | 13.6 | 17.88 | mheidari-all | 37.19.198.236 |
| 79.32 | shadowsocks | 256.5 | 686.1 | 21.84 | 0.0 | 10.0 | 13.6 | 17.88 | mheidari-all | 37.19.198.160 |
| 78.79 | shadowsocks | 230.9 | 602.2 | 22.43 | 0.0 | 10.0 | 13.6 | 16.76 | Surfboard-tg-mixed | 198.98.53.130 |
| 77.09 | vless | 259.8 | 654.0 | 21.76 | 0.0 | 8.83 | 8.68 | 17.82 | Au1rxx-base64 | 169.40.42.179 |
| 76.99 | shadowsocks | 282.6 | 644.7 | 21.24 | 0.0 | 10.0 | 13.6 | 17.88 | mheidari-all | 156.146.38.168 |
| 76.87 | shadowsocks | 279.3 | 648.7 | 21.31 | 0.0 | 10.0 | 13.6 | 17.88 | mheidari-all | 156.146.38.170 |
| 76.84 | shadowsocks | 342.1 | 950.1 | 19.86 | 0.0 | 10.0 | 13.6 | 17.88 | mheidari-all | 15.204.246.111 |
| 76.76 | shadowsocks | 345.7 | 925.5 | 19.78 | 0.0 | 10.0 | 13.6 | 17.88 | mheidari-all | 38.180.135.156 |
| 76.75 | vless | 274.5 | 713.8 | 21.42 | 0.0 | 8.83 | 8.68 | 17.82 | Au1rxx-base64 | 185.95.231.156 |
| 76.71 | shadowsocks | 285.5 | 657.5 | 21.17 | 0.0 | 10.0 | 13.6 | 17.88 | mheidari-all | 156.146.38.169 |
| 76.57 | hysteria2 | 294.4 | 584.3 | 20.96 | 0.0 | 8.92 | 13.85 | 17.82 | Au1rxx-base64 | 66.94.121.46 |
| 76.54 | vless | 283.9 | 685.8 | 21.21 | 0.0 | 8.83 | 8.68 | 17.82 | Au1rxx-base64 | 169.40.42.89 |
| 76.54 | vless | 287.4 | 689.4 | 21.12 | 0.0 | 8.92 | 8.68 | 17.82 | Au1rxx-base64 | 169.40.42.231 |
| 76.44 | vless | 288.4 | 736.2 | 21.1 | 0.0 | 8.84 | 8.68 | 17.82 | Au1rxx-base64 | 169.40.42.182 |
| 76.35 | vless | 290.6 | 750.5 | 21.05 | 0.0 | 8.8 | 8.68 | 17.82 | Au1rxx-base64 | 169.40.42.232 |
| 76.15 | vless | 300.4 | 668.4 | 20.82 | 0.0 | 8.83 | 8.68 | 17.82 | Au1rxx-base64 | 169.40.42.95 |
| 76.05 | vless | 306.8 | 677.7 | 20.68 | 0.0 | 8.87 | 8.68 | 17.82 | Au1rxx-base64 | 169.40.42.74 |
| 75.55 | vless | 251.5 | 688.3 | 21.96 | 0.0 | 9.09 | 8.68 | 17.82 | Au1rxx-base64 | 47.253.226.114 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.962 | 0.896 | 249 | 1749 | prefer |
| Surfboard-tg-mixed | 0.795 | 0.718 | 177 | 7479 | prefer |
| mheidari-all | 0.786 | 0.709 | 117 | 16452 | prefer |
| DeltaKronecker-all | 0.739 | 0.667 | 42 | 5187 | prefer |
| ermaozi | 0.636 | 0.623 | 53 | 442 | observe |
| ermaozi-get_subscribe | 0.561 | 0.545 | 22 | 473 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 180 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4795 | observe |
| Epodonios-all | 0.255 | None | 0 | 7964 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9095 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6181 | observe |
| barry-far-vless | 0.255 | None | 0 | 6404 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 36 |
| 204 | ProxyError | - | 32 |
| geo | ClientOSError | - | 28 |
| cn-block | TimeoutError | - | 20 |
| cn-block | ClientOSError | - | 11 |
| geo | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 6 |
| 204 | ClientOSError | - | 5 |
| speed | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| speed | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
