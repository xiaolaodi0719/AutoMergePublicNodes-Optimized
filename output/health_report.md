# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-19 18:47:36 |
| 运行耗时 | 386.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 93105 |
| 去重后节点 | 24449 |
| TCP 可达 | 3000 |
| 真实可用 | 1240 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24449 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 0.6 |
| tcp | 38.8 |
| probe | 73.1 |
| real_test | 241.2 |
| generate | 25.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50811 |
| trojan | 19383 |
| shadowsocks | 11007 |
| vmess | 9600 |
| hysteria2 | 1738 |
| shadowsocksr | 202 |
| http | 165 |
| socks | 136 |
| anytls | 36 |
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
| 84.11 | trojan | 239.1 | 636.5 | 22.24 | 0.0 | 10.0 | 14.87 | 20.0 | Au1rxx-base64 | 128.14.181.220 |
| 83.79 | trojan | 243.6 | 648.9 | 22.14 | 0.0 | 10.0 | 14.87 | 19.78 | mheidari-all | 14.1.28.76 |
| 83.65 | vless | 202.5 | 472.7 | 23.09 | 0.0 | 10.0 | 11.48 | 20.0 | Au1rxx-base64 | 70.39.198.183 |
| 83.61 | hysteria2 | 212.8 | 491.5 | 22.85 | 0.0 | 10.0 | 13.42 | 18.34 | Surfboard-tg-mixed | 150.241.102.127 |
| 83.04 | vless | 238.8 | 519.2 | 22.25 | 0.0 | 10.0 | 11.48 | 20.0 | Au1rxx-base64 | 150.241.102.202 |
| 82.2 | shadowsocks | 220.4 | 515.1 | 22.68 | 0.0 | 10.0 | 13.52 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 82.09 | shadowsocks | 193.8 | 473.3 | 23.29 | 0.0 | 10.0 | 13.52 | 19.78 | mheidari-all | 108.181.0.177 |
| 81.74 | shadowsocks | 209.1 | 552.9 | 22.94 | 0.0 | 10.0 | 13.52 | 19.78 | mheidari-all | 108.181.118.10 |
| 81.41 | vless | 252.8 | 608.5 | 21.93 | 0.0 | 10.0 | 11.48 | 20.0 | Au1rxx-base64 | 38.244.21.216 |
| 81.09 | shadowsocks | 258.6 | 628.9 | 21.79 | 0.0 | 10.0 | 13.52 | 19.78 | mheidari-all | 156.146.38.170 |
| 80.11 | trojan | 291.2 | 569.8 | 21.04 | 0.0 | 10.0 | 14.87 | 20.0 | Au1rxx-base64 | 34.222.243.142 |
| 79.66 | trojan | 291.2 | 557.8 | 21.04 | 0.0 | 10.0 | 14.87 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 79.62 | trojan | 308.4 | 564.3 | 20.64 | 0.0 | 10.0 | 14.87 | 19.78 | mheidari-all | 35.88.120.18 |
| 79.56 | http | 195.7 | 500.1 | 23.25 | 0.0 | 10.0 | 14.73 | 19.58 | zhangkai | 138.199.35.198 |
| 79.47 | trojan | 293.0 | 577.7 | 21.0 | 0.0 | 10.0 | 14.87 | 19.78 | mheidari-all | 35.88.210.26 |
| 79.43 | http | 201.3 | 517.2 | 23.12 | 0.0 | 10.0 | 14.73 | 19.58 | zhangkai | 138.199.35.216 |
| 79.43 | shadowsocks | 314.9 | 793.3 | 20.49 | 0.0 | 10.0 | 13.52 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 79.41 | vless | 263.6 | 531.6 | 21.68 | 0.0 | 10.0 | 11.48 | 20.0 | Au1rxx-base64 | 150.241.82.19 |
| 79.23 | vless | 348.7 | 845.1 | 19.71 | 0.0 | 10.0 | 11.48 | 19.78 | mheidari-all | 15.204.97.209 |
| 79.07 | trojan | 333.1 | 746.3 | 20.07 | 0.0 | 10.0 | 14.87 | 20.0 | Au1rxx-base64 | 35.92.245.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.986 | 690 | 1890 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| Surfboard-tg-mixed | 0.987 | 0.927 | 41 | 6336 | prefer |
| mheidari-all | 0.909 | 0.831 | 490 | 20423 | prefer |
| nscl5-all | 0.335 | 1.0 | 1 | 3330 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5974 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5067 | observe |
| Epodonios-all | 0.255 | None | 0 | 7060 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7318 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5003 | observe |
| barry-far-vless | 0.255 | None | 0 | 5325 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4086 | observe |
| Au1rxx-clash | 0.251 | None | 0 | 1890 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 40 |
| speed | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 12 |
| geo | TimeoutError | - | 8 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
