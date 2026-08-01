# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-01 13:42:48 |
| 运行耗时 | 263.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78943 |
| 去重后节点 | 23426 |
| TCP 可达 | 3000 |
| 真实可用 | 610 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23426 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.5 |
| tcp | 34.7 |
| probe | 51.6 |
| real_test | 140.3 |
| generate | 28.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47480 |
| vmess | 12385 |
| shadowsocks | 10145 |
| trojan | 7979 |
| hysteria2 | 609 |
| http | 157 |
| shadowsocksr | 74 |
| socks | 66 |
| anytls | 26 |
| hysteria | 14 |
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
| 82.51 | http | 286.1 | 685.5 | 21.16 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.8 |
| 82.43 | http | 289.1 | 703.2 | 21.08 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.25 |
| 82.29 | http | 304.0 | 736.1 | 20.74 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.50 |
| 81.76 | http | 301.0 | 736.1 | 20.81 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.21 |
| 81.72 | http | 290.1 | 697.7 | 21.06 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.7 |
| 81.32 | http | 280.6 | 684.0 | 21.28 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.16 |
| 80.18 | http | 280.8 | 681.9 | 21.28 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.49 |
| 79.98 | http | 312.0 | 752.4 | 20.56 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.33 |
| 79.26 | http | 277.1 | 666.4 | 21.36 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.43 |
| 78.01 | http | 280.4 | 687.0 | 21.29 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.41 |
| 77.39 | hysteria2 | 283.2 | 720.4 | 21.22 | 0.0 | 9.39 | 12.5 | 15.38 | Au1rxx-base64 | 159.223.157.129 |
| 76.68 | http | 319.6 | 596.1 | 20.38 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.213 |
| 76.68 | http | 323.4 | 606.6 | 20.29 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.206 |
| 76.63 | http | 321.8 | 598.5 | 20.33 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.199 |
| 76.62 | http | 321.0 | 603.1 | 20.35 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.202 |
| 76.59 | http | 329.0 | 624.7 | 20.16 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.198 |
| 76.56 | http | 328.7 | 622.4 | 20.17 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.200 |
| 76.55 | http | 329.6 | 620.5 | 20.15 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.216 |
| 76.54 | http | 326.9 | 616.3 | 20.21 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.205 |
| 76.49 | http | 327.9 | 620.5 | 20.19 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.217 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.994 | 0.993 | 148 | 194 | prefer |
| DeltaKronecker-all | 0.889 | 0.822 | 45 | 5502 | prefer |
| Au1rxx-base64 | 0.81 | 0.743 | 487 | 1689 | prefer |
| Surfboard-tg-mixed | 0.662 | 0.583 | 96 | 5351 | observe |
| mheidari-all | 0.421 | 0.667 | 6 | 16460 | observe |
| SoliSpirit-all | 0.391 | 1.0 | 2 | 6948 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| tg-v2nodes | 0.256 | 1.0 | 1 | 20 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5391 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4224 | observe |
| barry-far-vless | 0.255 | None | 0 | 4602 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5039 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1689 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 48 |
| geo | TimeoutError | - | 37 |
| speed | TimeoutError | - | 30 |
| 204 | ProxyError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 14 |
| geo | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
