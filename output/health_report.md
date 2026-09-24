# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 04:22:48 |
| 运行耗时 | 1074.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 96874 |
| 去重后节点 | 26609 |
| TCP 可达 | 3000 |
| 真实可用 | 553 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26609 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 43.3 |
| probe | 350.3 |
| real_test | 577.1 |
| generate | 94.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59125 |
| vmess | 14786 |
| shadowsocks | 11178 |
| trojan | 9244 |
| hysteria2 | 1562 |
| http | 669 |
| shadowsocksr | 170 |
| socks | 89 |
| anytls | 24 |
| hysteria | 19 |
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
| 82.97 | vless | 247.8 | 621.1 | 22.04 | 0.0 | 9.21 | 12.38 | 19.34 | Au1rxx-base64 | 195.211.98.43 |
| 80.25 | vless | 294.9 | 640.9 | 20.95 | 0.0 | 10.0 | 12.38 | 19.34 | Au1rxx-base64 | 195.123.235.177 |
| 79.49 | shadowsocks | 256.2 | 630.2 | 21.85 | 0.0 | 10.0 | 13.64 | 18.12 | mheidari-all | 156.146.38.170 |
| 78.51 | shadowsocks | 258.9 | 631.4 | 21.79 | 0.0 | 10.0 | 13.64 | 17.08 | Surfboard-tg-mixed | 156.146.38.169 |
| 78.19 | hysteria2 | 321.2 | 766.5 | 20.34 | 0.0 | 9.29 | 12.0 | 19.34 | Au1rxx-base64 | 66.94.121.46 |
| 77.97 | shadowsocks | 306.0 | 757.0 | 20.69 | 0.0 | 10.0 | 13.64 | 18.12 | mheidari-all | 37.19.198.160 |
| 77.93 | shadowsocks | 268.7 | 617.7 | 21.56 | 0.0 | 10.0 | 13.64 | 18.12 | mheidari-all | 23.150.248.20 |
| 77.84 | vless | 379.0 | 669.2 | 19.0 | 0.0 | 10.0 | 12.38 | 18.12 | mheidari-all | 172.67.130.144 |
| 77.67 | vless | 391.8 | 934.4 | 18.71 | 0.0 | 9.25 | 12.38 | 19.34 | Au1rxx-base64 | 137.184.218.169 |
| 77.59 | shadowsocks | 305.4 | 754.8 | 20.71 | 0.0 | 10.0 | 13.64 | 18.12 | mheidari-all | 37.19.198.244 |
| 77.57 | vless | 379.6 | 785.1 | 18.99 | 0.0 | 9.47 | 12.38 | 19.34 | Au1rxx-base64 | 169.40.42.75 |
| 76.97 | vless | 392.6 | 940.5 | 18.69 | 0.0 | 9.29 | 12.38 | 19.34 | Au1rxx-base64 | 66.70.179.198 |
| 76.83 | vless | 461.8 | 1217.4 | 17.09 | 0.0 | 9.34 | 12.38 | 19.34 | Au1rxx-base64 | 34.85.179.6 |
| 76.74 | shadowsocks | 248.9 | 623.1 | 22.02 | 0.0 | 10.0 | 13.64 | 17.08 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.68 | vless | 327.2 | 797.0 | 20.2 | 0.0 | 10.0 | 12.38 | 18.12 | mheidari-all | 216.227.161.95 |
| 76.31 | vless | 304.1 | 621.1 | 20.74 | 0.0 | 9.19 | 12.38 | 19.34 | Au1rxx-base64 | 172.235.43.210 |
| 76.3 | vless | 290.1 | 718.2 | 21.06 | 0.0 | 9.2 | 12.38 | 19.34 | Au1rxx-base64 | 79.141.172.154 |
| 76.3 | vless | 350.4 | 776.4 | 19.67 | 0.0 | 10.0 | 12.38 | 18.12 | mheidari-all | 47.251.108.158 |
| 76.23 | shadowsocks | 295.1 | 667.0 | 20.95 | 0.0 | 10.0 | 13.64 | 18.12 | mheidari-all | 51.222.200.165 |
| 76.23 | vless | 357.3 | 600.6 | 19.51 | 0.0 | 9.17 | 12.38 | 19.34 | Au1rxx-base64 | 195.123.240.65 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.937 | 0.874 | 253 | 1648 | prefer |
| Surfboard-tg-mixed | 0.845 | 0.77 | 100 | 7099 | prefer |
| ermaozi | 0.58 | 0.571 | 28 | 339 | observe |
| mheidari-all | 0.406 | 0.326 | 724 | 22298 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4332 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 149 | observe |
| Epodonios-all | 0.255 | None | 0 | 7563 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8881 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5729 | observe |
| barry-far-vless | 0.255 | None | 0 | 5948 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1648 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 219 |
| speed | TimeoutError | - | 81 |
| geo | ClientOSError | - | 65 |
| cn-block | ClientOSError | - | 57 |
| speed | ClientOSError | - | 52 |
| 204 | ProxyError | - | 31 |
| 204 | TimeoutError | - | 29 |
| cn-block | TimeoutError | - | 27 |
| cn-block | ProxyError | - | 3 |
| 204 | ServerDisconnectedError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
