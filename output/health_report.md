# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 12:09:11 |
| 运行耗时 | 301.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94664 |
| 去重后节点 | 24930 |
| TCP 可达 | 3000 |
| 真实可用 | 507 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24930 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.5 |
| tcp | 42.2 |
| probe | 91.2 |
| real_test | 115.3 |
| generate | 43.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59131 |
| vmess | 12762 |
| shadowsocks | 11079 |
| trojan | 9214 |
| hysteria2 | 2094 |
| http | 138 |
| shadowsocksr | 130 |
| socks | 61 |
| anytls | 22 |
| hysteria | 19 |
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
| 80.04 | hysteria2 | 252.8 | 550.6 | 21.92 | 0.0 | 9.88 | 12.5 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 79.92 | shadowsocks | 296.5 | 697.2 | 20.91 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 78.81 | shadowsocks | 304.5 | 750.4 | 20.73 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 77.0 | trojan | 292.1 | 720.7 | 21.02 | 0.0 | 10.0 | 9.35 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 76.95 | shadowsocks | 318.0 | 554.5 | 20.42 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 76.85 | shadowsocks | 305.4 | 785.3 | 20.71 | 0.0 | 10.0 | 14.1 | 16.04 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.71 | shadowsocks | 323.5 | 713.0 | 20.29 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 76.11 | trojan | 303.0 | 780.4 | 20.76 | 0.0 | 10.0 | 9.35 | 20.0 | Au1rxx-base64 | 64.94.95.115 |
| 75.77 | trojan | 361.0 | 957.2 | 19.42 | 0.0 | 10.0 | 9.35 | 20.0 | Au1rxx-base64 | 64.94.95.114 |
| 74.43 | vless | 333.7 | 812.6 | 20.05 | 0.0 | 10.0 | 7.81 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 74.31 | vless | 366.7 | 720.0 | 19.29 | 0.0 | 10.0 | 7.81 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 74.13 | shadowsocks | 390.6 | 932.1 | 18.74 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 51.79.64.198 |
| 74.09 | vless | 342.5 | 773.3 | 19.85 | 0.0 | 10.0 | 7.81 | 20.0 | Au1rxx-base64 | 169.40.42.89 |
| 74.06 | trojan | 367.1 | 979.9 | 19.28 | 0.0 | 10.0 | 9.35 | 20.0 | Au1rxx-base64 | 64.94.95.117 |
| 73.98 | vless | 412.9 | 978.0 | 18.22 | 0.0 | 10.0 | 7.81 | 20.0 | Au1rxx-base64 | 185.95.231.156 |
| 73.97 | vless | 324.3 | 651.1 | 20.27 | 0.0 | 10.0 | 7.81 | 20.0 | Au1rxx-base64 | 172.235.43.210 |
| 73.9 | vless | 367.1 | 727.0 | 19.28 | 0.0 | 10.0 | 7.81 | 20.0 | Au1rxx-base64 | 169.40.42.224 |
| 73.79 | vless | 392.4 | 931.3 | 18.7 | 0.0 | 10.0 | 7.81 | 20.0 | Au1rxx-base64 | 169.40.42.223 |
| 73.54 | shadowsocks | 392.7 | 1006.9 | 18.69 | 0.0 | 10.0 | 14.1 | 16.04 | Surfboard-tg-mixed | 15.204.246.108 |
| 73.54 | shadowsocks | 415.1 | 978.8 | 18.17 | 0.0 | 10.0 | 14.1 | 20.0 | Au1rxx-base64 | 51.222.200.165 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | 0.912 | 320 | 1781 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.84 | 0.764 | 148 | 7247 | prefer |
| mheidari-all | 0.637 | 0.558 | 120 | 21631 | observe |
| tg-oneclickvpnkeys | 0.494 | 0.875 | 8 | 151 | observe |
| DeltaKronecker-all | 0.391 | 1.0 | 2 | 6417 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 5750 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| Epodonios-all | 0.255 | None | 0 | 7707 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8442 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6030 | observe |
| barry-far-vless | 0.255 | None | 0 | 6245 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 39 |
| cn-block | ClientOSError | - | 22 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 11 |
| speed | TimeoutError | - | 6 |
| geo | TimeoutError | - | 5 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 4 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
