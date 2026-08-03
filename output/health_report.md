# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-03 19:49:09 |
| 运行耗时 | 284.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 84754 |
| 去重后节点 | 25181 |
| TCP 可达 | 3000 |
| 真实可用 | 555 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25181 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.6 |
| geo | 1.6 |
| tcp | 37.3 |
| probe | 60.8 |
| real_test | 135.4 |
| generate | 39.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52044 |
| vmess | 12821 |
| shadowsocks | 10361 |
| trojan | 8537 |
| hysteria2 | 747 |
| http | 76 |
| socks | 74 |
| shadowsocksr | 72 |
| hysteria | 11 |
| tuic | 6 |
| anytls | 5 |

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
| 79.09 | hysteria2 | 239.8 | 647.7 | 22.23 | 0.0 | 10.0 | 11.84 | 16.12 | Au1rxx-base64 | 159.223.157.129 |
| 78.15 | trojan | 262.4 | 691.6 | 21.7 | 0.0 | 10.0 | 13.33 | 16.12 | Au1rxx-base64 | 153.75.250.171 |
| 77.17 | shadowsocks | 238.8 | 630.7 | 22.25 | 0.0 | 10.0 | 12.8 | 16.12 | Au1rxx-base64 | 37.19.198.160 |
| 76.99 | shadowsocks | 246.6 | 645.5 | 22.07 | 0.0 | 10.0 | 12.8 | 16.12 | Au1rxx-base64 | 37.19.198.244 |
| 76.61 | shadowsocks | 263.0 | 689.4 | 21.69 | 0.0 | 10.0 | 12.8 | 16.12 | Au1rxx-base64 | 37.19.198.243 |
| 75.99 | vless | 288.8 | 730.2 | 21.09 | 0.0 | 10.0 | 8.78 | 16.12 | Au1rxx-base64 | 88.218.44.4 |
| 75.64 | shadowsocks | 261.5 | 681.4 | 21.72 | 0.0 | 10.0 | 12.8 | 16.12 | Au1rxx-base64 | 37.19.198.236 |
| 75.21 | vless | 281.7 | 653.9 | 21.26 | 0.0 | 10.0 | 8.78 | 16.12 | Au1rxx-base64 | 169.40.42.15 |
| 74.81 | vless | 287.0 | 691.9 | 21.14 | 0.0 | 10.0 | 8.78 | 16.12 | Au1rxx-base64 | 216.152.147.28 |
| 74.77 | vless | 341.7 | 904.4 | 19.87 | 0.0 | 10.0 | 8.78 | 16.12 | Au1rxx-base64 | 167.17.69.171 |
| 73.87 | vless | 294.3 | 730.3 | 20.97 | 0.0 | 10.0 | 8.78 | 16.12 | Au1rxx-base64 | 159.195.12.98 |
| 73.58 | vless | 393.0 | 1019.6 | 18.68 | 0.0 | 10.0 | 8.78 | 16.12 | Au1rxx-base64 | 78.111.89.171 |
| 73.51 | trojan | 304.7 | 646.9 | 20.72 | 0.0 | 10.0 | 13.33 | 16.12 | Au1rxx-base64 | 163.245.196.68 |
| 73.17 | vless | 339.0 | 753.9 | 19.93 | 0.0 | 10.0 | 8.78 | 16.12 | Au1rxx-base64 | 169.40.42.75 |
| 72.99 | vless | 400.0 | 926.6 | 18.52 | 0.0 | 10.0 | 8.78 | 16.12 | Au1rxx-base64 | 67.220.73.204 |
| 72.65 | vless | 385.6 | 1063.2 | 18.85 | 0.0 | 10.0 | 8.78 | 16.12 | Au1rxx-base64 | 45.138.100.226 |
| 72.3 | trojan | 374.4 | 889.3 | 19.11 | 0.0 | 10.0 | 13.33 | 16.12 | Au1rxx-base64 | 64.94.95.118 |
| 72.26 | trojan | 369.1 | 868.1 | 19.23 | 0.0 | 10.0 | 13.33 | 16.12 | Au1rxx-base64 | 64.94.95.114 |
| 72.14 | trojan | 386.7 | 918.9 | 18.83 | 0.0 | 10.0 | 13.33 | 16.12 | Au1rxx-base64 | 64.94.95.115 |
| 72.14 | trojan | 395.6 | 939.2 | 18.62 | 0.0 | 10.0 | 13.33 | 16.12 | Au1rxx-base64 | 64.94.95.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 67 | 92 | prefer |
| Au1rxx-base64 | 0.807 | 0.74 | 526 | 1718 | prefer |
| Surfboard-tg-mixed | 0.674 | 0.6 | 30 | 5168 | observe |
| mheidari-all | 0.643 | 0.564 | 140 | 18750 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 5127 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5285 | observe |
| Epodonios-all | 0.255 | None | 0 | 5757 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6825 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4147 | observe |
| barry-far-vless | 0.255 | None | 0 | 4498 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5152 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1718 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 92 |
| speed | TimeoutError | - | 26 |
| 204 | ProxyError | - | 26 |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 20 |
| geo | ClientOSError | - | 17 |
| speed | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
