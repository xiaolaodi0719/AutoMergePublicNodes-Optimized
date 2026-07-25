# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-25 19:19:45 |
| 运行耗时 | 255.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80536 |
| 去重后节点 | 22511 |
| TCP 可达 | 3000 |
| 真实可用 | 356 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22511 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 31.8 |
| probe | 64.1 |
| real_test | 112.5 |
| generate | 39.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45402 |
| trojan | 14511 |
| vmess | 10179 |
| shadowsocks | 9756 |
| hysteria2 | 433 |
| http | 81 |
| shadowsocksr | 79 |
| socks | 68 |
| hysteria | 15 |
| tuic | 11 |
| anytls | 1 |

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
| 76.62 | vless | 200.0 | 472.6 | 23.15 | 0.0 | 10.0 | 4.47 | 20.0 | mheidari-all | 104.16.9.20 |
| 71.12 | vless | 204.2 | 481.0 | 23.05 | 0.0 | 10.0 | 4.47 | 14.6 | Surfboard-tg-mixed | 198.41.209.87 |
| 69.3 | trojan | 490.0 | 516.2 | 16.44 | 0.0 | 9.53 | 14.03 | 20.0 | mheidari-all | 82.117.226.237 |
| 69.13 | trojan | 498.5 | 523.6 | 16.24 | 0.0 | 9.54 | 14.03 | 20.0 | mheidari-all | 109.61.127.143 |
| 69.03 | trojan | 503.0 | 545.6 | 16.13 | 0.0 | 9.55 | 14.03 | 20.0 | mheidari-all | 82.117.226.88 |
| 68.56 | vless | 345.9 | 347.3 | 19.77 | 1.98 | 9.84 | 4.47 | 20.0 | mheidari-all | 3.114.220.22 |
| 68.49 | trojan | 528.3 | 617.8 | 15.55 | 0.0 | 9.52 | 14.03 | 20.0 | mheidari-all | 82.117.226.104 |
| 67.94 | trojan | 551.7 | 682.5 | 15.01 | 0.0 | 9.58 | 14.03 | 20.0 | mheidari-all | 82.117.226.159 |
| 67.9 | trojan | 551.3 | 683.1 | 15.02 | 0.0 | 9.53 | 14.03 | 20.0 | mheidari-all | 109.61.127.166 |
| 67.61 | trojan | 567.2 | 753.9 | 14.65 | 0.0 | 9.58 | 14.03 | 20.0 | mheidari-all | 82.117.226.249 |
| 67.51 | trojan | 532.1 | 487.6 | 15.46 | 0.0 | 9.09 | 14.03 | 20.0 | mheidari-all | 45.135.228.220 |
| 67.49 | trojan | 533.0 | 487.0 | 15.44 | 0.0 | 9.09 | 14.03 | 20.0 | mheidari-all | 81.28.13.92 |
| 67.47 | trojan | 534.3 | 496.6 | 15.41 | 0.0 | 9.09 | 14.03 | 20.0 | mheidari-all | 45.135.228.28 |
| 67.44 | trojan | 535.1 | 488.1 | 15.39 | 0.0 | 9.08 | 14.03 | 20.0 | mheidari-all | 81.28.13.68 |
| 67.36 | trojan | 538.4 | 501.3 | 15.31 | 0.0 | 9.09 | 14.03 | 20.0 | mheidari-all | 91.243.81.50 |
| 67.34 | trojan | 536.0 | 495.2 | 15.37 | 0.0 | 9.09 | 14.03 | 20.0 | mheidari-all | 45.135.228.63 |
| 67.27 | vless | 396.2 | 768.6 | 18.61 | 0.0 | 10.0 | 4.47 | 20.0 | mheidari-all | 216.227.169.104 |
| 67.2 | trojan | 545.6 | 521.3 | 15.15 | 0.0 | 9.09 | 14.03 | 20.0 | mheidari-all | 45.135.228.68 |
| 67.19 | trojan | 546.1 | 526.3 | 15.14 | 0.0 | 9.08 | 14.03 | 20.0 | mheidari-all | 81.28.13.159 |
| 67.17 | trojan | 546.7 | 529.6 | 15.12 | 0.0 | 9.08 | 14.03 | 20.0 | mheidari-all | 45.135.228.21 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 74 | 119 | prefer |
| mheidari-all | 0.742 | 0.664 | 223 | 17275 | prefer |
| Surfboard-tg-mixed | 0.575 | 0.495 | 184 | 5515 | observe |
| DeltaKronecker-all | 0.538 | 0.457 | 81 | 5838 | observe |
| Au1rxx-base64 | 0.487 | 1.0 | 5 | 1199 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4879 | observe |
| Epodonios-all | 0.255 | None | 0 | 6622 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6305 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4371 | observe |
| barry-far-vless | 0.255 | None | 0 | 4959 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4980 | observe |
| nscl5-all | 0.255 | None | 0 | 2974 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 81 |
| speed | ClientOSError | - | 56 |
| 204 | ProxyError | - | 22 |
| 204 | TimeoutError | - | 20 |
| geo | ClientOSError | - | 13 |
| speed | TimeoutError | - | 8 |
| cn-block | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
