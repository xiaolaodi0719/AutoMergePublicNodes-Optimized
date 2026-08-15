# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-15 01:34:11 |
| 运行耗时 | 314.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 75507 |
| 去重后节点 | 20655 |
| TCP 可达 | 3000 |
| 真实可用 | 984 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 20655 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.6 |
| tcp | 33.6 |
| probe | 61.8 |
| real_test | 182.5 |
| generate | 28.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 41333 |
| trojan | 11666 |
| vmess | 10499 |
| shadowsocks | 10253 |
| hysteria2 | 1411 |
| http | 180 |
| socks | 78 |
| shadowsocksr | 72 |
| tuic | 8 |
| hysteria | 7 |

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
| 82.29 | hysteria2 | 325.5 | 788.2 | 20.24 | 0.0 | 10.0 | 13.33 | 19.86 | Au1rxx-base64 | 159.223.157.129 |
| 82.19 | hysteria2 | 336.0 | 837.8 | 20.0 | 0.0 | 10.0 | 13.33 | 19.86 | Au1rxx-base64 | 138.124.68.188 |
| 81.31 | shadowsocks | 242.9 | 620.4 | 22.16 | 0.0 | 10.0 | 13.29 | 19.86 | Au1rxx-base64 | 156.146.38.170 |
| 81.26 | shadowsocks | 244.9 | 634.2 | 22.11 | 0.0 | 10.0 | 13.29 | 19.86 | Au1rxx-base64 | 156.146.38.168 |
| 80.61 | shadowsocks | 251.2 | 598.9 | 21.96 | 0.0 | 10.0 | 13.29 | 19.86 | Au1rxx-base64 | 23.150.248.20 |
| 79.55 | http | 313.5 | 707.2 | 20.52 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 79.32 | http | 333.2 | 708.2 | 20.06 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 79.22 | http | 320.3 | 706.5 | 20.36 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 79.1 | http | 314.5 | 708.0 | 20.5 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 79.09 | http | 317.7 | 724.0 | 20.42 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 79.06 | http | 337.5 | 752.4 | 19.97 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 79.0 | http | 286.0 | 573.0 | 21.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 78.97 | http | 342.3 | 783.5 | 19.85 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 78.92 | http | 309.3 | 712.1 | 20.62 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 78.85 | http | 327.3 | 741.1 | 20.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 78.75 | http | 326.1 | 749.6 | 20.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 78.72 | http | 283.4 | 569.0 | 21.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 78.72 | http | 289.7 | 582.7 | 21.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 78.66 | http | 289.5 | 589.0 | 21.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 78.63 | http | 291.8 | 598.4 | 21.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.972 | 737 | 1681 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| DeltaKronecker-all | 0.89 | 0.821 | 56 | 3485 | prefer |
| mheidari-all | 0.447 | 0.366 | 194 | 15517 | observe |
| nscl5-all | 0.446 | 0.625 | 8 | 2081 | observe |
| Surfboard-tg-mixed | 0.42 | 0.333 | 45 | 5718 | observe |
| 10ium-ScrapeCategorize-Vless | 0.3 | 0.4 | 5 | 5157 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 160 | observe |
| Epodonios-all | 0.255 | None | 0 | 6388 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| Pawdroid | 0.255 | 1.0 | 1 | 7 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7639 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4415 | observe |
| barry-far-vless | 0.255 | None | 0 | 4744 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3992 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 53 |
| geo | TimeoutError | - | 47 |
| cn-block | TimeoutError | - | 39 |
| geo | ClientOSError | - | 23 |
| 204 | TimeoutError | - | 11 |
| speed | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
