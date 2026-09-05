# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-05 20:13:54 |
| 运行耗时 | 296.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 97140 |
| 去重后节点 | 25671 |
| TCP 可达 | 3000 |
| 真实可用 | 489 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25671 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.4 |
| tcp | 42.1 |
| probe | 87.6 |
| real_test | 121.5 |
| generate | 36.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 62024 |
| vmess | 12476 |
| shadowsocks | 11142 |
| trojan | 9208 |
| hysteria2 | 1879 |
| http | 144 |
| shadowsocksr | 132 |
| socks | 63 |
| anytls | 38 |
| hysteria | 20 |
| tuic | 14 |

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
| 84.04 | vless | 199.6 | 511.7 | 23.16 | 0.0 | 9.13 | 12.15 | 19.6 | Au1rxx-base64 | 172.235.38.85 |
| 83.98 | vless | 205.6 | 522.3 | 23.02 | 0.0 | 9.21 | 12.15 | 19.6 | Au1rxx-base64 | 172.233.139.46 |
| 83.71 | vless | 214.9 | 553.2 | 22.8 | 0.0 | 9.16 | 12.15 | 19.6 | Au1rxx-base64 | 38.209.125.45 |
| 83.42 | hysteria2 | 216.0 | 530.1 | 22.78 | 0.0 | 9.18 | 12.86 | 19.6 | Au1rxx-base64 | 66.94.121.46 |
| 82.74 | vless | 213.6 | 538.1 | 22.83 | 0.0 | 9.16 | 12.15 | 19.6 | Au1rxx-base64 | 23.94.227.94 |
| 82.01 | vless | 303.0 | 795.9 | 20.76 | 0.0 | 9.5 | 12.15 | 19.6 | Au1rxx-base64 | 15.204.97.216 |
| 81.45 | shadowsocks | 201.5 | 488.6 | 23.11 | 0.0 | 9.14 | 14.1 | 19.6 | Au1rxx-base64 | 108.181.118.10 |
| 80.19 | shadowsocks | 275.0 | 652.2 | 21.41 | 0.0 | 9.08 | 14.1 | 19.6 | Au1rxx-base64 | 173.244.56.6 |
| 80.04 | vless | 201.8 | 518.4 | 23.11 | 0.0 | 10.0 | 12.15 | 19.6 | Au1rxx-base64 | 172.235.43.210 |
| 79.54 | shadowsocks | 216.0 | 507.8 | 22.78 | 0.0 | 10.0 | 14.1 | 16.66 | Surfboard-tg-mixed | 149.22.95.183 |
| 79.2 | vless | 199.1 | 497.2 | 23.17 | 0.0 | 9.28 | 12.15 | 19.6 | Au1rxx-base64 | 5.253.38.67 |
| 79.0 | vless | 216.5 | 509.8 | 22.77 | 0.0 | 10.0 | 12.15 | 19.6 | Au1rxx-base64 | 38.246.229.58 |
| 78.96 | shadowsocks | 219.5 | 542.1 | 22.7 | 0.0 | 10.0 | 14.1 | 16.66 | Surfboard-tg-mixed | 108.181.0.177 |
| 77.62 | shadowsocks | 294.5 | 651.6 | 20.96 | 0.0 | 10.0 | 14.1 | 16.56 | mheidari-all | 173.244.56.9 |
| 76.74 | vless | 315.2 | 827.0 | 20.48 | 0.0 | 9.51 | 12.15 | 19.6 | Au1rxx-base64 | 15.204.97.214 |
| 76.65 | vless | 234.1 | 588.5 | 22.36 | 0.0 | 9.51 | 12.15 | 19.6 | Au1rxx-base64 | 38.127.121.44 |
| 76.61 | vless | 318.0 | 837.9 | 20.42 | 0.0 | 9.44 | 12.15 | 19.6 | Au1rxx-base64 | 15.204.97.219 |
| 76.61 | vless | 385.9 | 281.9 | 18.84 | 4.43 | 9.09 | 12.15 | 19.6 | Au1rxx-base64 | 13.231.129.39 |
| 76.28 | trojan | 356.2 | 989.3 | 19.53 | 0.0 | 10.0 | 12.69 | 16.56 | mheidari-all | 34.94.125.227 |
| 76.09 | vless | 389.6 | 289.9 | 18.76 | 4.13 | 9.12 | 12.15 | 19.6 | Au1rxx-base64 | 13.231.156.101 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.886 | 0.817 | 356 | 1764 | prefer |
| Surfboard-tg-mixed | 0.877 | 0.801 | 151 | 7292 | prefer |
| mheidari-all | 0.621 | 0.541 | 109 | 22630 | observe |
| zhangkai | 0.606 | 0.609 | 23 | 144 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6965 | observe |
| tg-oneclickvpnkeys | 0.278 | 0.5 | 6 | 132 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4887 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 6212 | observe |
| Epodonios-all | 0.255 | None | 0 | 7653 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8694 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6126 | observe |
| barry-far-vless | 0.255 | None | 0 | 6249 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4087 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 47 |
| 204 | ProxyError | - | 38 |
| geo | ClientOSError | - | 18 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyConnectionError | - | 12 |
| speed | ClientOSError | - | 3 |
| speed | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
