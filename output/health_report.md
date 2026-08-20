# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-20 13:03:28 |
| 运行耗时 | 351.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 94317 |
| 去重后节点 | 25201 |
| TCP 可达 | 3000 |
| 真实可用 | 1067 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25201 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| geo | 0.6 |
| tcp | 39.2 |
| probe | 67.7 |
| real_test | 212.7 |
| generate | 23.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52876 |
| trojan | 18382 |
| shadowsocks | 10622 |
| vmess | 10196 |
| hysteria2 | 1682 |
| shadowsocksr | 202 |
| http | 164 |
| socks | 134 |
| anytls | 32 |
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
| 85.08 | trojan | 191.1 | 494.2 | 23.35 | 0.0 | 10.0 | 14.77 | 19.96 | mheidari-all | 14.1.28.76 |
| 84.97 | hysteria2 | 230.6 | 552.8 | 22.44 | 0.0 | 10.0 | 13.57 | 19.96 | mheidari-all | 150.241.102.127 |
| 83.18 | hysteria2 | 240.0 | 222.2 | 22.22 | 6.67 | 9.9 | 13.57 | 20.0 | Au1rxx-base64 | 45.32.252.144 |
| 82.87 | http | 247.2 | 666.5 | 22.06 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 82.68 | http | 255.1 | 676.8 | 21.87 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |
| 82.06 | shadowsocks | 254.5 | 626.5 | 21.89 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 81.81 | shadowsocks | 265.2 | 656.5 | 21.64 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.71 | shadowsocks | 269.6 | 669.4 | 21.54 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 81.27 | shadowsocks | 191.2 | 471.7 | 23.35 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 209.38.142.23 |
| 80.79 | shadowsocks | 259.5 | 631.2 | 21.77 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.36 | trojan | 277.3 | 580.7 | 21.36 | 0.0 | 10.0 | 14.77 | 19.96 | mheidari-all | 35.90.27.143 |
| 80.34 | trojan | 280.6 | 587.8 | 21.28 | 0.0 | 10.0 | 14.77 | 20.0 | Au1rxx-base64 | 100.22.163.167 |
| 80.31 | trojan | 268.0 | 553.8 | 21.57 | 0.0 | 10.0 | 14.77 | 19.96 | mheidari-all | 54.244.169.225 |
| 80.24 | trojan | 275.8 | 577.7 | 21.39 | 0.0 | 10.0 | 14.77 | 20.0 | Au1rxx-base64 | 35.91.138.234 |
| 80.22 | trojan | 284.9 | 600.8 | 21.18 | 0.0 | 10.0 | 14.77 | 20.0 | Au1rxx-base64 | 54.213.46.211 |
| 80.19 | vless | 261.7 | 583.7 | 21.72 | 0.0 | 10.0 | 9.98 | 19.96 | mheidari-all | 15.204.97.209 |
| 80.14 | trojan | 289.0 | 614.5 | 21.09 | 0.0 | 10.0 | 14.77 | 20.0 | Au1rxx-base64 | 34.221.30.108 |
| 79.98 | trojan | 282.9 | 589.1 | 21.23 | 0.0 | 10.0 | 14.77 | 19.96 | mheidari-all | 35.91.98.35 |
| 79.92 | trojan | 267.4 | 551.6 | 21.59 | 0.0 | 10.0 | 14.77 | 19.96 | mheidari-all | 44.251.158.80 |
| 79.89 | trojan | 288.1 | 609.0 | 21.11 | 0.0 | 10.0 | 14.77 | 20.0 | Au1rxx-base64 | 35.92.245.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.975 | 569 | 1789 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| mheidari-all | 0.871 | 0.792 | 495 | 21209 | prefer |
| Surfboard-tg-mixed | 0.515 | 0.636 | 11 | 6453 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| Epodonios-all | 0.255 | None | 0 | 7150 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7279 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5135 | observe |
| barry-far-vless | 0.255 | None | 0 | 5460 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4586 | observe |
| nscl5-all | 0.255 | None | 0 | 2418 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1789 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 47 |
| geo | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 14 |
| speed | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| speed | ClientOSError | - | 6 |
| 204 | ProxyError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
