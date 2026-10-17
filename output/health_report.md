# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 20:33:40 |
| 运行耗时 | 703.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99282 |
| 去重后节点 | 27771 |
| TCP 可达 | 3000 |
| 真实可用 | 399 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27771 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 48.0 |
| probe | 273.4 |
| real_test | 289.8 |
| generate | 82.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58446 |
| vmess | 16713 |
| shadowsocks | 11943 |
| trojan | 9966 |
| hysteria2 | 1333 |
| http | 611 |
| shadowsocksr | 160 |
| socks | 61 |
| anytls | 26 |
| hysteria | 17 |
| tuic | 6 |

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
| 80.39 | vless | 228.5 | 597.8 | 22.49 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 195.123.235.183 |
| 80.06 | vless | 242.5 | 651.4 | 22.16 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 147.45.60.160 |
| 79.63 | vless | 261.1 | 625.0 | 21.73 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 195.211.98.43 |
| 79.12 | vless | 283.3 | 714.4 | 21.22 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 66.70.179.198 |
| 78.37 | vless | 315.6 | 880.2 | 20.47 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 159.89.87.21 |
| 78.1 | vless | 240.9 | 677.2 | 22.2 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 47.253.226.114 |
| 78.02 | vless | 331.0 | 898.9 | 20.12 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 167.17.69.171 |
| 77.8 | hysteria2 | 365.8 | 1026.0 | 19.31 | 0.0 | 10.0 | 12.35 | 17.64 | Au1rxx-base64 | 129.213.91.185 |
| 77.35 | vless | 302.9 | 663.3 | 20.77 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 169.40.42.225 |
| 77.31 | vless | 361.6 | 788.2 | 19.41 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 169.40.42.104 |
| 77.13 | vless | 369.4 | 1028.0 | 19.23 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 185.95.231.156 |
| 76.53 | vless | 313.7 | 697.3 | 20.52 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 198.23.169.170 |
| 76.15 | trojan | 387.0 | 1082.8 | 18.82 | 0.0 | 10.0 | 12.69 | 17.64 | Au1rxx-base64 | 69.164.240.85 |
| 75.04 | vless | 330.0 | 896.1 | 20.14 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 169.40.42.168 |
| 74.1 | vless | 469.6 | 1101.4 | 16.91 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 209.200.246.148 |
| 73.66 | vless | 312.1 | 681.9 | 20.55 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 212.104.141.233 |
| 73.45 | vless | 333.7 | 934.4 | 20.05 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 104.243.33.154 |
| 73.34 | vless | 272.1 | 638.3 | 21.48 | 0.0 | 9.13 | 10.26 | 17.64 | Au1rxx-base64 | 216.227.161.95 |
| 73.32 | vless | 310.1 | 857.0 | 20.6 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 137.184.218.169 |
| 73.1 | vless | 300.4 | 664.9 | 20.82 | 0.0 | 10.0 | 10.26 | 17.64 | Au1rxx-base64 | 69.48.201.136 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.887 | 0.809 | 444 | 1992 | prefer |
| ermaozi | 0.819 | 0.812 | 32 | 623 | prefer |
| mheidari-all | 0.646 | 0.769 | 13 | 23876 | observe |
| Surfboard-tg-mixed | 0.385 | 0.5 | 8 | 7109 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1992 | observe |
| Epodonios-all | 0.255 | None | 0 | 7590 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10112 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5614 | observe |
| barry-far-vless | 0.255 | None | 0 | 5860 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 20 |
| 204 | ProxyConnectionError | - | 17 |
| speed | ClientOSError | - | 16 |
| speed | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| geo | TimeoutError | - | 8 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
