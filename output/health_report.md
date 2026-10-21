# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 04:15:24 |
| 运行耗时 | 654.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 95343 |
| 去重后节点 | 26611 |
| TCP 可达 | 3000 |
| 真实可用 | 445 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26611 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.4 |
| tcp | 44.9 |
| probe | 217.4 |
| real_test | 305.8 |
| generate | 77.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56794 |
| vmess | 16861 |
| shadowsocks | 11914 |
| trojan | 8115 |
| hysteria2 | 1212 |
| http | 171 |
| shadowsocksr | 164 |
| socks | 65 |
| anytls | 24 |
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
| 79.72 | hysteria2 | 320.3 | 801.2 | 20.36 | 0.0 | 10.0 | 13.12 | 17.74 | Au1rxx-base64 | 129.213.91.185 |
| 79.48 | hysteria2 | 283.9 | 601.1 | 21.21 | 0.0 | 9.97 | 13.12 | 17.74 | Au1rxx-base64 | 66.94.121.46 |
| 78.87 | shadowsocks | 246.2 | 620.5 | 22.08 | 0.0 | 9.93 | 13.12 | 17.74 | Au1rxx-base64 | 156.146.38.168 |
| 78.78 | shadowsocks | 251.1 | 609.0 | 21.96 | 0.0 | 9.96 | 13.12 | 17.74 | Au1rxx-base64 | 156.146.38.167 |
| 77.55 | vless | 329.2 | 785.4 | 20.16 | 0.0 | 10.0 | 11.02 | 17.74 | Au1rxx-base64 | 185.95.231.156 |
| 77.46 | trojan | 337.7 | 854.4 | 19.96 | 0.0 | 9.99 | 12.77 | 17.74 | Au1rxx-base64 | 66.23.203.21 |
| 77.4 | shadowsocks | 244.5 | 603.7 | 22.12 | 0.0 | 10.0 | 13.12 | 16.16 | Surfboard-tg-mixed | 156.146.38.169 |
| 77.02 | vless | 291.2 | 659.7 | 21.04 | 0.0 | 10.0 | 11.02 | 17.74 | Au1rxx-base64 | 195.123.235.183 |
| 76.44 | shadowsocks | 301.7 | 772.5 | 20.79 | 0.0 | 10.0 | 13.12 | 17.86 | mheidari-all | 156.146.38.170 |
| 76.4 | shadowsocks | 308.6 | 764.4 | 20.63 | 0.0 | 10.0 | 13.12 | 17.86 | mheidari-all | 37.19.198.243 |
| 75.31 | vless | 275.6 | 551.4 | 21.4 | 0.0 | 10.0 | 11.02 | 17.86 | mheidari-all | 47.251.108.158 |
| 75.22 | shadowsocks | 296.9 | 734.6 | 20.91 | 0.0 | 10.0 | 13.12 | 17.86 | mheidari-all | 37.19.198.160 |
| 75.16 | shadowsocks | 290.9 | 700.5 | 21.04 | 0.0 | 10.0 | 13.12 | 17.74 | Au1rxx-base64 | 37.19.198.244 |
| 75.1 | shadowsocks | 311.6 | 762.9 | 20.56 | 0.0 | 10.0 | 13.12 | 16.16 | Surfboard-tg-mixed | 37.19.198.236 |
| 74.96 | vless | 319.2 | 652.9 | 20.39 | 0.0 | 10.0 | 11.02 | 17.74 | Au1rxx-base64 | 45.63.53.81 |
| 74.95 | vless | 426.9 | 982.1 | 17.9 | 0.0 | 10.0 | 11.02 | 17.74 | Au1rxx-base64 | 169.40.42.225 |
| 74.93 | vless | 314.5 | 583.5 | 20.5 | 0.0 | 10.0 | 11.02 | 17.74 | Au1rxx-base64 | 144.202.126.147 |
| 74.63 | vless | 345.2 | 746.8 | 19.79 | 0.0 | 10.0 | 11.02 | 17.74 | Au1rxx-base64 | 167.17.69.171 |
| 74.39 | vless | 349.5 | 746.0 | 19.69 | 0.0 | 10.0 | 11.02 | 17.74 | Au1rxx-base64 | 45.32.69.110 |
| 73.92 | vless | 287.1 | 668.8 | 21.13 | 0.0 | 10.0 | 11.02 | 17.74 | Au1rxx-base64 | 69.48.201.136 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.919 | 0.864 | 301 | 1433 | prefer |
| Surfboard-tg-mixed | 0.91 | 0.843 | 51 | 7115 | prefer |
| zhangkai | 0.592 | 0.6 | 20 | 31 | observe |
| ermaozi-get_subscribe | 0.579 | 0.561 | 41 | 516 | observe |
| mheidari-all | 0.533 | 0.453 | 234 | 23653 | observe |
| DeltaKronecker-all | 0.259 | 0.333 | 3 | 3519 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| Epodonios-all | 0.255 | None | 0 | 7598 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10016 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5552 | observe |
| barry-far-vless | 0.255 | None | 0 | 5764 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.232 | None | 0 | 1433 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 72 |
| 204 | ProxyError | - | 38 |
| geo | ClientOSError | - | 29 |
| speed | ClientOSError | - | 24 |
| speed | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
