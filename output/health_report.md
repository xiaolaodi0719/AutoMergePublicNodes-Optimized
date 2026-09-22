# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 16:47:40 |
| 运行耗时 | 512.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 84228 |
| 去重后节点 | 23642 |
| TCP 可达 | 3000 |
| 真实可用 | 419 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23642 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.6 |
| tcp | 39.0 |
| probe | 214.7 |
| real_test | 169.8 |
| generate | 81.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50245 |
| vmess | 14082 |
| shadowsocks | 9646 |
| trojan | 8453 |
| hysteria2 | 1006 |
| http | 576 |
| shadowsocksr | 134 |
| socks | 68 |
| hysteria | 11 |
| tuic | 4 |
| anytls | 3 |

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
| 81.63 | hysteria2 | 285.2 | 718.2 | 21.18 | 0.0 | 10.0 | 12.63 | 18.92 | Au1rxx-base64 | 159.223.157.129 |
| 80.4 | shadowsocks | 246.1 | 610.7 | 22.08 | 0.0 | 10.0 | 14.13 | 18.92 | Au1rxx-base64 | 198.98.53.130 |
| 79.99 | shadowsocks | 295.3 | 747.1 | 20.94 | 0.0 | 10.0 | 14.13 | 18.92 | Au1rxx-base64 | 37.19.198.243 |
| 79.83 | shadowsocks | 295.4 | 747.7 | 20.94 | 0.0 | 10.0 | 14.13 | 18.92 | Au1rxx-base64 | 37.19.198.244 |
| 78.94 | shadowsocks | 293.7 | 744.3 | 20.98 | 0.0 | 10.0 | 14.13 | 18.92 | Au1rxx-base64 | 37.19.198.236 |
| 78.77 | hysteria2 | 292.2 | 637.3 | 21.01 | 0.0 | 10.0 | 12.63 | 18.92 | Au1rxx-base64 | 66.94.121.46 |
| 76.87 | shadowsocks | 357.9 | 893.0 | 19.49 | 0.0 | 10.0 | 14.13 | 18.92 | Au1rxx-base64 | 23.150.248.20 |
| 76.07 | vless | 353.1 | 929.1 | 19.6 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 34.85.179.6 |
| 75.7 | shadowsocks | 264.6 | 643.0 | 21.65 | 0.0 | 10.0 | 14.13 | 18.92 | Au1rxx-base64 | 156.146.38.170 |
| 75.36 | shadowsocks | 360.2 | 944.6 | 19.44 | 0.0 | 10.0 | 14.13 | 18.92 | Au1rxx-base64 | 38.180.135.156 |
| 75.04 | vless | 371.9 | 913.0 | 19.17 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 138.124.60.146 |
| 73.84 | vless | 424.7 | 1108.6 | 17.95 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 185.95.231.156 |
| 73.68 | shadowsocks | 546.5 | 1551.1 | 15.13 | 0.0 | 10.0 | 14.13 | 18.92 | Au1rxx-base64 | 185.156.47.97 |
| 72.67 | vless | 388.7 | 985.5 | 18.78 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 169.40.42.95 |
| 72.4 | vless | 453.6 | 1086.2 | 17.28 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 137.184.218.169 |
| 72.3 | vless | 310.6 | 610.4 | 20.59 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 172.235.43.210 |
| 72.21 | vless | 469.3 | 1241.7 | 16.91 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 169.40.42.35 |
| 72.11 | vless | 338.9 | 788.2 | 19.93 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 169.40.42.52 |
| 72.08 | vless | 399.2 | 984.3 | 18.54 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 158.69.112.254 |
| 71.76 | vless | 539.4 | 1558.2 | 15.29 | 0.0 | 10.0 | 7.55 | 18.92 | Au1rxx-base64 | 195.211.98.43 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | 0.866 | 299 | 1703 | prefer |
| mheidari-all | 0.905 | 0.842 | 38 | 16289 | prefer |
| DeltaKronecker-all | 0.858 | 0.794 | 34 | 6324 | prefer |
| ermaozi | 0.737 | 0.741 | 27 | 325 | prefer |
| Surfboard-tg-mixed | 0.586 | 0.507 | 152 | 7076 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 132 | observe |
| 10ium-ScrapeCategorize-Vless | 0.259 | 0.333 | 3 | 4915 | observe |
| Epodonios-all | 0.255 | None | 0 | 7611 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9154 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5712 | observe |
| barry-far-vless | 0.255 | None | 0 | 6010 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 35 |
| geo | ClientOSError | - | 33 |
| 204 | TimeoutError | - | 21 |
| 204 | ProxyError | - | 11 |
| speed | TimeoutError | - | 11 |
| cn-block | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
