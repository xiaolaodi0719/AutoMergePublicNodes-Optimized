# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 20:52:03 |
| 运行耗时 | 707.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83486 |
| 去重后节点 | 22839 |
| TCP 可达 | 3000 |
| 真实可用 | 391 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22839 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.5 |
| tcp | 37.9 |
| probe | 284.9 |
| real_test | 225.2 |
| generate | 152.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50612 |
| vmess | 12528 |
| shadowsocks | 9806 |
| trojan | 8072 |
| hysteria2 | 1700 |
| http | 567 |
| shadowsocksr | 124 |
| socks | 55 |
| tuic | 10 |
| hysteria | 8 |
| anytls | 4 |

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
| 79.73 | vless | 286.1 | 722.4 | 21.16 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 47.253.226.114 |
| 79.54 | vless | 275.0 | 634.2 | 21.41 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 195.123.235.177 |
| 78.15 | vless | 303.0 | 720.9 | 20.77 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 66.70.179.198 |
| 77.97 | vless | 360.2 | 849.9 | 19.44 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.35 |
| 77.41 | vless | 319.1 | 773.7 | 20.39 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.74 |
| 77.17 | vless | 302.8 | 686.7 | 20.77 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.212 |
| 77.14 | vless | 287.2 | 677.8 | 21.13 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.179 |
| 76.99 | shadowsocks | 246.0 | 608.7 | 22.08 | 0.0 | 10.0 | 13.31 | 15.6 | Surfboard-tg-mixed | 198.98.53.130 |
| 76.86 | vless | 360.9 | 866.9 | 19.42 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.15 |
| 76.52 | vless | 294.0 | 694.2 | 20.97 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.225 |
| 76.1 | shadowsocks | 393.6 | 1046.0 | 18.67 | 0.0 | 10.0 | 13.31 | 18.62 | Au1rxx-base64 | 15.204.247.206 |
| 76.0 | vless | 357.3 | 847.8 | 19.51 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.231 |
| 75.97 | shadowsocks | 357.0 | 917.7 | 19.51 | 0.0 | 10.0 | 13.31 | 18.62 | Au1rxx-base64 | 51.79.64.198 |
| 75.93 | vless | 357.3 | 844.5 | 19.51 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.52 |
| 75.82 | vless | 281.5 | 669.0 | 21.26 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.235 |
| 75.36 | shadowsocks | 425.4 | 1066.4 | 17.93 | 0.0 | 10.0 | 13.31 | 18.62 | Au1rxx-base64 | 15.204.247.175 |
| 75.2 | vless | 258.6 | 662.8 | 21.79 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 188.137.243.243 |
| 75.09 | shadowsocks | 323.7 | 790.1 | 20.29 | 0.0 | 10.0 | 13.31 | 18.62 | Au1rxx-base64 | 51.222.200.165 |
| 74.94 | vless | 372.2 | 931.4 | 19.16 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.75 |
| 74.64 | vless | 321.8 | 740.2 | 20.33 | 0.0 | 10.0 | 9.95 | 18.62 | Au1rxx-base64 | 169.40.42.184 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.928 | 0.865 | 260 | 1642 | prefer |
| DeltaKronecker-all | 0.83 | 0.773 | 22 | 5853 | prefer |
| Surfboard-tg-mixed | 0.751 | 0.674 | 138 | 7221 | prefer |
| ermaozi | 0.683 | 0.68 | 25 | 405 | observe |
| mheidari-all | 0.68 | 0.603 | 58 | 15823 | observe |
| roosterkid-openproxylist-v2ray | 0.364 | 1.0 | 3 | 150 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 194 | observe |
| Epodonios-all | 0.255 | None | 0 | 7677 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8881 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5840 | observe |
| barry-far-vless | 0.255 | None | 0 | 6058 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1642 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 21 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 19 |
| cn-block | ClientOSError | - | 12 |
| geo | TimeoutError | - | 12 |
| 204 | ProxyError | - | 9 |
| 204 | ProxyConnectionError | - | 7 |
| 204 | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
