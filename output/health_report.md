# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 11:26:43 |
| 运行耗时 | 576.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 91703 |
| 去重后节点 | 25251 |
| TCP 可达 | 3000 |
| 真实可用 | 461 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25251 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.4 |
| tcp | 42.3 |
| probe | 232.0 |
| real_test | 199.7 |
| generate | 93.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53889 |
| vmess | 14816 |
| shadowsocks | 11214 |
| trojan | 9282 |
| hysteria2 | 1600 |
| http | 634 |
| shadowsocksr | 142 |
| socks | 80 |
| anytls | 21 |
| hysteria | 17 |
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
| 83.52 | hysteria2 | 253.4 | 621.5 | 21.91 | 0.0 | 10.0 | 14.25 | 18.36 | Au1rxx-base64 | 66.94.121.46 |
| 77.84 | hysteria2 | 343.9 | 749.5 | 19.82 | 0.0 | 8.91 | 14.25 | 18.36 | Au1rxx-base64 | 159.223.157.129 |
| 75.37 | shadowsocks | 241.5 | 616.8 | 22.19 | 0.0 | 10.0 | 14.04 | 13.14 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.69 | vless | 290.8 | 656.8 | 21.05 | 0.0 | 10.0 | 7.45 | 18.36 | Au1rxx-base64 | 15.204.97.216 |
| 74.14 | vless | 274.3 | 577.7 | 21.43 | 0.0 | 10.0 | 7.45 | 18.36 | Au1rxx-base64 | 172.235.43.210 |
| 73.53 | vless | 325.2 | 735.0 | 20.25 | 0.0 | 10.0 | 7.45 | 18.36 | Au1rxx-base64 | 195.211.98.43 |
| 73.29 | shadowsocks | 377.8 | 876.5 | 19.03 | 0.0 | 10.0 | 14.04 | 18.36 | Au1rxx-base64 | 142.4.216.225 |
| 72.05 | vless | 317.6 | 744.8 | 20.43 | 0.0 | 8.74 | 7.45 | 18.36 | Au1rxx-base64 | 79.141.172.154 |
| 71.91 | shadowsocks | 405.4 | 995.2 | 18.39 | 0.0 | 10.0 | 14.04 | 18.36 | Au1rxx-base64 | 185.156.47.97 |
| 71.38 | shadowsocks | 259.8 | 598.3 | 21.76 | 0.0 | 10.0 | 14.04 | 10.08 | mheidari-all | 23.150.248.20 |
| 71.35 | shadowsocks | 359.1 | 767.0 | 19.47 | 0.0 | 8.97 | 14.04 | 18.36 | Au1rxx-base64 | 108.181.57.93 |
| 71.11 | shadowsocks | 242.2 | 619.3 | 22.17 | 0.0 | 10.0 | 14.04 | 18.36 | Au1rxx-base64 | 156.146.38.167 |
| 70.96 | shadowsocks | 292.7 | 636.5 | 21.0 | 0.0 | 10.0 | 14.04 | 13.14 | Surfboard-tg-mixed | 198.98.53.130 |
| 70.29 | hysteria2 | 463.5 | 804.5 | 17.05 | 0.0 | 8.53 | 14.25 | 18.36 | Au1rxx-base64 | 45.192.12.93 |
| 70.22 | shadowsocks | 453.0 | 1122.3 | 17.29 | 0.0 | 8.81 | 14.04 | 18.36 | Au1rxx-base64 | 15.204.246.132 |
| 70.1 | vless | 374.3 | 795.0 | 19.11 | 0.0 | 10.0 | 7.45 | 18.36 | Au1rxx-base64 | 66.70.179.198 |
| 68.96 | shadowsocks | 345.7 | 787.3 | 19.77 | 0.0 | 10.0 | 14.04 | 13.14 | Surfboard-tg-mixed | 37.19.198.243 |
| 68.7 | shadowsocks | 375.7 | 884.5 | 19.08 | 0.0 | 10.0 | 14.04 | 13.14 | Surfboard-tg-mixed | 173.244.56.6 |
| 68.58 | vless | 267.0 | 576.7 | 21.6 | 0.0 | 10.0 | 7.45 | 13.14 | Surfboard-tg-mixed | 172.235.38.85 |
| 68.45 | shadowsocks | 393.7 | 572.9 | 18.66 | 0.0 | 8.94 | 14.04 | 18.36 | Au1rxx-base64 | 149.22.87.204 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.946 | 0.884 | 292 | 1630 | prefer |
| ermaozi | 0.689 | 0.682 | 44 | 369 | observe |
| Surfboard-tg-mixed | 0.594 | 0.514 | 179 | 7157 | observe |
| mheidari-all | 0.434 | 0.353 | 204 | 19835 | observe |
| DeltaKronecker-all | 0.382 | 0.357 | 14 | 6324 | observe |
| ermaozi-get_subscribe | 0.309 | 0.6 | 5 | 393 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 4242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7495 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9028 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5792 | observe |
| barry-far-vless | 0.255 | None | 0 | 5817 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1630 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 80 |
| geo | ClientOSError | - | 67 |
| speed | ClientOSError | - | 43 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 21 |
| geo | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 17 |
| speed | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
