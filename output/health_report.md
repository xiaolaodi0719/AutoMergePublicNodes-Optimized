# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-20 07:00:02 |
| 运行耗时 | 366.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 93905 |
| 去重后节点 | 25131 |
| TCP 可达 | 3000 |
| 真实可用 | 1283 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25131 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 0.9 |
| tcp | 38.3 |
| probe | 75.8 |
| real_test | 217.1 |
| generate | 28.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52552 |
| trojan | 18403 |
| shadowsocks | 10546 |
| vmess | 10176 |
| hysteria2 | 1675 |
| shadowsocksr | 197 |
| http | 165 |
| socks | 131 |
| anytls | 33 |
| hysteria | 15 |
| tuic | 12 |

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
| 82.43 | shadowsocks | 241.6 | 636.0 | 22.18 | 0.0 | 10.0 | 14.25 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 82.35 | shadowsocks | 245.1 | 597.9 | 22.1 | 0.0 | 10.0 | 14.25 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 82.18 | shadowsocks | 252.6 | 591.2 | 21.93 | 0.0 | 10.0 | 14.25 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 81.0 | vless | 292.3 | 671.8 | 21.01 | 0.0 | 10.0 | 9.99 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 80.67 | trojan | 237.6 | 588.3 | 22.28 | 0.0 | 10.0 | 14.61 | 16.78 | mheidari-all | 64.94.95.115 |
| 80.0 | vless | 335.7 | 759.3 | 20.01 | 0.0 | 10.0 | 9.99 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 79.75 | vless | 281.5 | 647.7 | 21.26 | 0.0 | 10.0 | 9.99 | 20.0 | Au1rxx-base64 | 195.211.99.45 |
| 79.65 | vless | 285.8 | 638.3 | 21.16 | 0.0 | 10.0 | 9.99 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 79.56 | trojan | 285.6 | 721.6 | 21.17 | 0.0 | 10.0 | 14.61 | 16.78 | mheidari-all | 64.94.95.117 |
| 79.55 | hysteria2 | 275.7 | 265.5 | 21.4 | 5.04 | 9.53 | 13.5 | 20.0 | Au1rxx-base64 | 45.32.252.144 |
| 79.39 | shadowsocks | 287.2 | 671.6 | 21.13 | 0.0 | 10.0 | 14.25 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 79.33 | shadowsocks | 236.8 | 605.2 | 22.3 | 0.0 | 10.0 | 14.25 | 16.78 | mheidari-all | 156.146.38.170 |
| 79.17 | shadowsocks | 328.6 | 839.9 | 20.17 | 0.0 | 10.0 | 14.25 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 78.33 | shadowsocks | 258.3 | 625.9 | 21.8 | 0.0 | 10.0 | 14.25 | 16.78 | mheidari-all | 23.150.248.20 |
| 78.16 | shadowsocks | 355.8 | 812.1 | 19.54 | 0.0 | 10.0 | 14.25 | 20.0 | Au1rxx-base64 | 142.4.216.225 |
| 77.62 | vless | 339.2 | 735.9 | 19.93 | 0.0 | 10.0 | 9.99 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 77.41 | trojan | 313.9 | 589.0 | 20.51 | 0.0 | 10.0 | 14.61 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 77.23 | vless | 325.5 | 664.9 | 20.24 | 0.0 | 10.0 | 9.99 | 20.0 | Au1rxx-base64 | 169.40.42.184 |
| 77.2 | trojan | 322.8 | 614.0 | 20.31 | 0.0 | 10.0 | 14.61 | 20.0 | Au1rxx-base64 | 35.88.120.18 |
| 77.18 | trojan | 323.8 | 618.3 | 20.28 | 0.0 | 10.0 | 14.61 | 20.0 | Au1rxx-base64 | 35.92.245.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.969 | 712 | 1789 | prefer |
| mheidari-all | 0.998 | 0.92 | 327 | 21143 | prefer |
| zhangkai | 0.997 | 1.0 | 110 | 144 | prefer |
| Surfboard-tg-mixed | 0.849 | 0.772 | 232 | 6418 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5974 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| Epodonios-all | 0.255 | None | 0 | 7111 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7230 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5062 | observe |
| barry-far-vless | 0.255 | None | 0 | 5404 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4586 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1789 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 43 |
| geo | ClientOSError | - | 25 |
| speed | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 9 |
| speed | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
