# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-18 18:50:17 |
| 运行耗时 | 386.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 93067 |
| 去重后节点 | 24081 |
| TCP 可达 | 3000 |
| 真实可用 | 1075 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24081 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 0.8 |
| tcp | 36.6 |
| probe | 76.8 |
| real_test | 237.0 |
| generate | 27.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52158 |
| trojan | 18723 |
| shadowsocks | 10565 |
| vmess | 9543 |
| hysteria2 | 1521 |
| http | 179 |
| socks | 154 |
| shadowsocksr | 149 |
| anytls | 47 |
| tuic | 15 |
| hysteria | 13 |

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
| 83.9 | http | 247.9 | 653.3 | 22.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 83.7 | http | 256.4 | 686.8 | 21.84 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.48 | http | 265.9 | 713.6 | 21.62 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 83.42 | http | 268.5 | 722.2 | 21.56 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 83.32 | http | 272.8 | 726.8 | 21.46 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 83.32 | http | 272.9 | 733.1 | 21.46 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 83.2 | http | 278.0 | 740.9 | 21.34 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 82.93 | http | 289.7 | 744.2 | 21.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 82.77 | http | 296.5 | 808.7 | 20.91 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 82.66 | http | 301.5 | 814.0 | 20.8 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 82.5 | http | 308.5 | 832.0 | 20.64 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 82.35 | http | 314.8 | 849.3 | 20.49 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 82.32 | http | 316.3 | 847.3 | 20.46 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 82.24 | http | 319.4 | 873.5 | 20.38 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 82.22 | http | 320.6 | 867.2 | 20.36 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 82.2 | http | 321.1 | 877.0 | 20.34 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 82.18 | http | 322.2 | 873.8 | 20.32 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 82.14 | http | 323.8 | 880.1 | 20.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 80.15 | vless | 366.6 | 965.8 | 19.29 | 0.0 | 10.0 | 10.86 | 20.0 | mheidari-all | 66.70.179.198 |
| 79.66 | vless | 258.1 | 704.9 | 21.8 | 0.0 | 10.0 | 10.86 | 20.0 | mheidari-all | 147.182.212.232 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.987 | 639 | 1643 | prefer |
| zhangkai | 0.991 | 0.992 | 127 | 159 | prefer |
| mheidari-all | 0.872 | 0.794 | 378 | 22150 | prefer |
| Surfboard-tg-mixed | 0.828 | 0.833 | 18 | 6301 | prefer |
| nscl5-all | 0.349 | 0.667 | 3 | 2992 | observe |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 5725 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5068 | observe |
| Epodonios-all | 0.255 | None | 0 | 6927 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7150 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4855 | observe |
| barry-far-vless | 0.255 | None | 0 | 5149 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4035 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1643 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 36 |
| speed | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 8 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 5 |
| speed | ClientOSError | - | 3 |
| 204 | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
