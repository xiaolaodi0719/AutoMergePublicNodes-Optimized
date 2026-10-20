# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 11:22:27 |
| 运行耗时 | 582.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94099 |
| 去重后节点 | 26435 |
| TCP 可达 | 3000 |
| 真实可用 | 399 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26435 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.6 |
| tcp | 45.4 |
| probe | 222.5 |
| real_test | 219.8 |
| generate | 86.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55981 |
| vmess | 16884 |
| shadowsocks | 11192 |
| trojan | 8371 |
| hysteria2 | 1107 |
| http | 278 |
| shadowsocksr | 165 |
| socks | 64 |
| anytls | 34 |
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
| 81.95 | hysteria2 | 310.0 | 735.8 | 20.6 | 0.0 | 10.0 | 14.21 | 19.76 | Surfboard-tg-mixed | 129.213.91.185 |
| 81.92 | shadowsocks | 239.8 | 616.8 | 22.23 | 0.0 | 10.0 | 13.93 | 19.76 | Surfboard-tg-mixed | 156.146.38.169 |
| 79.58 | shadowsocks | 242.4 | 622.5 | 22.17 | 0.0 | 10.0 | 13.93 | 17.48 | Au1rxx-base64 | 156.146.38.167 |
| 79.07 | vless | 282.0 | 683.0 | 21.25 | 0.0 | 10.0 | 8.06 | 19.76 | Surfboard-tg-mixed | 147.45.60.160 |
| 77.25 | trojan | 363.9 | 956.2 | 19.35 | 0.0 | 10.0 | 13.42 | 17.48 | Au1rxx-base64 | 66.23.203.21 |
| 74.74 | shadowsocks | 269.2 | 569.2 | 21.55 | 0.0 | 9.04 | 13.93 | 17.48 | Au1rxx-base64 | 173.244.56.9 |
| 73.49 | shadowsocks | 423.8 | 544.8 | 17.97 | 0.0 | 10.0 | 13.93 | 19.76 | Surfboard-tg-mixed | 103.11.76.248 |
| 73.25 | shadowsocks | 303.3 | 302.9 | 20.76 | 3.64 | 8.94 | 13.93 | 17.48 | Au1rxx-base64 | 149.22.87.240 |
| 73.13 | shadowsocks | 305.4 | 305.5 | 20.71 | 3.55 | 8.94 | 13.93 | 17.48 | Au1rxx-base64 | 149.22.87.204 |
| 72.26 | vless | 234.8 | 521.2 | 22.34 | 0.0 | 9.12 | 8.06 | 17.48 | Au1rxx-base64 | 47.251.108.158 |
| 72.13 | vless | 329.6 | 743.9 | 20.15 | 0.0 | 9.12 | 8.06 | 17.48 | Au1rxx-base64 | 195.123.240.65 |
| 71.98 | vless | 295.6 | 656.8 | 20.93 | 0.0 | 9.27 | 8.06 | 17.48 | Au1rxx-base64 | 195.211.98.43 |
| 71.48 | http | 259.9 | 567.9 | 21.76 | 0.0 | 10.0 | 8.08 | 16.38 | zhangkai | 138.199.35.214 |
| 71.4 | shadowsocks | 251.8 | 647.8 | 21.95 | 0.0 | 10.0 | 13.93 | 9.52 | mheidari-all | 156.146.38.170 |
| 70.56 | hysteria2 | 431.3 | 746.3 | 17.79 | 0.0 | 9.11 | 14.21 | 17.48 | Au1rxx-base64 | 62.210.124.146 |
| 70.4 | shadowsocks | 295.0 | 774.4 | 20.95 | 0.0 | 10.0 | 13.93 | 9.52 | mheidari-all | 156.146.38.168 |
| 69.9 | shadowsocks | 438.1 | 1044.2 | 17.64 | 0.0 | 8.97 | 13.93 | 17.48 | Au1rxx-base64 | 15.204.233.41 |
| 69.81 | vless | 468.8 | 1191.9 | 16.93 | 0.0 | 9.18 | 8.06 | 17.48 | Au1rxx-base64 | 51.81.203.63 |
| 69.81 | hysteria2 | 522.4 | 934.3 | 15.69 | 0.0 | 9.36 | 14.21 | 19.76 | Surfboard-tg-mixed | 130.49.161.70 |
| 69.66 | shadowsocks | 299.1 | 702.6 | 20.85 | 0.0 | 9.07 | 13.93 | 17.48 | Au1rxx-base64 | 185.215.132.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.957 | 0.891 | 55 | 23400 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 27 | prefer |
| Au1rxx-base64 | 0.901 | 0.855 | 304 | 1192 | prefer |
| Surfboard-tg-mixed | 0.72 | 0.644 | 87 | 6911 | prefer |
| ermaozi-get_subscribe | 0.469 | 0.444 | 27 | 510 | observe |
| DeltaKronecker-all | 0.272 | 0.286 | 7 | 3519 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| Epodonios-all | 0.255 | None | 0 | 7377 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9884 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5733 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 21 |
| 204 | TimeoutError | - | 16 |
| cn-block | TimeoutError | - | 15 |
| geo | ClientOSError | - | 13 |
| speed | TimeoutError | - | 12 |
| speed | ClientOSError | - | 11 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
