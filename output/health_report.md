# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-04 16:09:16 |
| 运行耗时 | 301.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84288 |
| 去重后节点 | 23436 |
| TCP 可达 | 3000 |
| 真实可用 | 588 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23436 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.4 |
| tcp | 39.0 |
| probe | 85.9 |
| real_test | 126.5 |
| generate | 40.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53565 |
| vmess | 11419 |
| shadowsocks | 9598 |
| trojan | 7954 |
| hysteria2 | 1388 |
| http | 144 |
| shadowsocksr | 131 |
| socks | 63 |
| tuic | 15 |
| hysteria | 10 |
| anytls | 1 |

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
| 79.82 | shadowsocks | 287.4 | 734.9 | 21.12 | 0.0 | 10.0 | 13.8 | 18.9 | Au1rxx-base64 | 156.146.38.169 |
| 79.44 | shadowsocks | 293.0 | 751.4 | 21.0 | 0.0 | 10.0 | 13.8 | 18.9 | Au1rxx-base64 | 156.146.38.168 |
| 79.31 | vless | 289.0 | 266.8 | 21.09 | 5.0 | 9.67 | 12.08 | 18.44 | Surfboard-tg-mixed | 31.76.91.72 |
| 78.53 | vless | 348.2 | 840.3 | 19.72 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 15.204.97.197 |
| 77.61 | shadowsocks | 361.7 | 914.7 | 19.41 | 0.0 | 10.0 | 13.8 | 18.9 | Au1rxx-base64 | 23.150.248.20 |
| 77.2 | vless | 349.0 | 602.5 | 19.7 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 172.233.139.46 |
| 76.61 | shadowsocks | 289.6 | 571.1 | 21.07 | 0.0 | 10.0 | 13.8 | 18.9 | Au1rxx-base64 | 173.244.56.6 |
| 76.54 | vless | 275.8 | 576.6 | 21.39 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 38.127.121.44 |
| 76.5 | vless | 251.9 | 557.9 | 21.95 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 204.44.127.222 |
| 76.47 | trojan | 316.7 | 795.8 | 20.45 | 0.0 | 10.0 | 10.12 | 18.9 | Au1rxx-base64 | 64.94.95.117 |
| 76.29 | shadowsocks | 280.7 | 567.8 | 21.28 | 0.0 | 10.0 | 13.8 | 18.9 | Au1rxx-base64 | 173.244.56.9 |
| 76.27 | vless | 297.9 | 652.9 | 20.88 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 172.235.38.85 |
| 75.83 | shadowsocks | 277.0 | 553.4 | 21.37 | 0.0 | 10.0 | 13.8 | 18.9 | Au1rxx-base64 | 108.181.118.10 |
| 75.24 | vless | 395.9 | 872.1 | 18.61 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 23.237.192.18 |
| 75.02 | vless | 360.6 | 871.6 | 19.43 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 15.204.97.216 |
| 75.0 | vless | 372.3 | 741.7 | 19.16 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 204.48.20.223 |
| 74.92 | trojan | 282.9 | 694.0 | 21.23 | 0.0 | 10.0 | 10.12 | 18.9 | Au1rxx-base64 | 64.94.95.115 |
| 74.56 | vless | 400.8 | 840.6 | 18.5 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 2.24.124.64 |
| 74.47 | shadowsocks | 324.6 | 701.5 | 20.26 | 0.0 | 10.0 | 13.8 | 18.9 | Au1rxx-base64 | 37.19.198.160 |
| 74.06 | vless | 346.5 | 595.4 | 19.76 | 0.0 | 10.0 | 12.08 | 18.9 | Au1rxx-base64 | 31.58.50.200 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | 0.919 | 359 | 1751 | prefer |
| Surfboard-tg-mixed | 0.856 | 0.78 | 159 | 7209 | prefer |
| mheidari-all | 0.85 | 0.774 | 137 | 15927 | prefer |
| DeltaKronecker-all | 0.732 | 0.667 | 21 | 7089 | prefer |
| zhangkai | 0.486 | 0.478 | 23 | 144 | observe |
| tg-oneclickvpnkeys | 0.277 | 0.5 | 6 | 104 | observe |
| Epodonios-all | 0.255 | None | 0 | 7667 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8718 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6091 | observe |
| barry-far-vless | 0.255 | None | 0 | 6339 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4123 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 26 |
| cn-block | TimeoutError | - | 23 |
| 204 | ProxyConnectionError | - | 16 |
| geo | ClientOSError | - | 15 |
| cn-block | ClientOSError | - | 11 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyError | - | 7 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
