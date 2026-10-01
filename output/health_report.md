# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 05:22:45 |
| 运行耗时 | 813.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97843 |
| 去重后节点 | 27292 |
| TCP 可达 | 3000 |
| 真实可用 | 336 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27292 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.6 |
| tcp | 45.7 |
| probe | 296.0 |
| real_test | 381.5 |
| generate | 81.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59749 |
| vmess | 15334 |
| shadowsocks | 11441 |
| trojan | 9068 |
| hysteria2 | 1406 |
| http | 551 |
| shadowsocksr | 164 |
| socks | 66 |
| anytls | 40 |
| hysteria | 16 |
| tuic | 8 |

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
| 79.4 | shadowsocks | 253.2 | 708.1 | 21.92 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 37.19.198.243 |
| 79.32 | shadowsocks | 256.6 | 718.6 | 21.84 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 37.19.198.244 |
| 78.96 | shadowsocks | 250.7 | 653.8 | 21.98 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 140.82.63.79 |
| 78.05 | vless | 355.6 | 914.4 | 19.55 | 0.0 | 10.0 | 10.85 | 18.06 | mheidari-all | 209.200.246.148 |
| 77.62 | shadowsocks | 278.7 | 636.5 | 21.33 | 0.0 | 10.0 | 14.02 | 18.06 | mheidari-all | 156.146.38.168 |
| 77.48 | hysteria2 | 251.8 | 689.4 | 21.95 | 0.0 | 10.0 | 11.67 | 17.46 | Au1rxx-base64 | 159.223.157.129 |
| 77.16 | shadowsocks | 328.2 | 938.0 | 20.18 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 15.204.246.132 |
| 77.14 | shadowsocks | 280.9 | 655.4 | 21.27 | 0.0 | 10.0 | 14.02 | 18.06 | mheidari-all | 156.146.38.170 |
| 76.84 | shadowsocks | 279.8 | 648.3 | 21.3 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 156.146.38.169 |
| 76.67 | shadowsocks | 370.9 | 1058.5 | 19.19 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 37.19.198.160 |
| 76.49 | shadowsocks | 357.0 | 925.1 | 19.51 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 185.156.47.97 |
| 76.46 | shadowsocks | 315.4 | 819.1 | 20.48 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 66.23.204.219 |
| 76.04 | shadowsocks | 395.8 | 947.7 | 18.62 | 0.0 | 10.0 | 14.02 | 17.9 | Surfboard-tg-mixed | 51.222.200.165 |
| 74.35 | shadowsocks | 406.3 | 1111.0 | 18.37 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 64.74.161.148 |
| 73.71 | vless | 366.2 | 1030.4 | 19.3 | 0.0 | 10.0 | 10.85 | 18.06 | mheidari-all | 162.35.104.144 |
| 73.69 | vless | 292.6 | 645.4 | 21.0 | 0.0 | 10.0 | 10.85 | 18.06 | mheidari-all | 216.227.161.95 |
| 73.37 | shadowsocks | 405.5 | 1102.0 | 18.39 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 103.214.111.162 |
| 73.21 | hysteria2 | 378.7 | 719.1 | 19.01 | 0.0 | 10.0 | 11.67 | 17.46 | Au1rxx-base64 | 66.94.121.46 |
| 73.15 | hysteria2 | 358.8 | 752.6 | 19.47 | 0.0 | 10.0 | 11.67 | 17.46 | Au1rxx-base64 | 192.255.128.123 |
| 72.93 | shadowsocks | 231.6 | 633.9 | 22.42 | 0.0 | 10.0 | 14.02 | 17.46 | Au1rxx-base64 | 198.98.53.130 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | 0.921 | 114 | 1694 | prefer |
| ermaozi | 0.857 | 0.864 | 22 | 588 | prefer |
| Surfboard-tg-mixed | 0.714 | 0.637 | 80 | 7136 | prefer |
| mheidari-all | 0.427 | 0.346 | 442 | 22835 | observe |
| DeltaKronecker-all | 0.397 | 0.417 | 12 | 5434 | observe |
| tg-oneclickvpnkeys | 0.314 | 1.0 | 2 | 66 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7637 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9403 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5815 | observe |
| barry-far-vless | 0.255 | None | 0 | 6001 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4183 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 158 |
| speed | TimeoutError | - | 68 |
| geo | ClientOSError | - | 41 |
| speed | ClientOSError | - | 23 |
| 204 | ProxyError | - | 18 |
| 204 | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 4 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
