# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-31 03:33:34 |
| 运行耗时 | 365.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78323 |
| 去重后节点 | 23087 |
| TCP 可达 | 3000 |
| 真实可用 | 672 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23087 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.4 |
| geo | 1.3 |
| tcp | 33.5 |
| probe | 74.3 |
| real_test | 225.7 |
| generate | 27.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45463 |
| vmess | 11409 |
| shadowsocks | 10270 |
| trojan | 10263 |
| hysteria2 | 599 |
| http | 127 |
| shadowsocksr | 75 |
| socks | 57 |
| anytls | 26 |
| tuic | 20 |
| hysteria | 14 |

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
| 77.63 | http | 329.5 | 712.3 | 20.15 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.196 |
| 76.86 | http | 284.2 | 568.2 | 21.2 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.213 |
| 76.78 | http | 279.2 | 556.8 | 21.31 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.218 |
| 76.7 | http | 280.8 | 567.0 | 21.28 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.216 |
| 76.52 | http | 290.5 | 583.9 | 21.05 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.204 |
| 76.5 | http | 292.3 | 565.1 | 21.01 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.199 |
| 76.42 | http | 285.7 | 578.0 | 21.16 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.215 |
| 76.31 | http | 331.3 | 720.4 | 20.11 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.23 |
| 76.28 | http | 293.9 | 603.1 | 20.97 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.217 |
| 76.28 | http | 302.5 | 592.0 | 20.78 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.206 |
| 76.23 | http | 283.3 | 567.2 | 21.22 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.209 |
| 76.23 | http | 295.8 | 607.5 | 20.93 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.208 |
| 76.2 | http | 280.4 | 561.2 | 21.29 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.210 |
| 76.2 | http | 285.3 | 576.3 | 21.17 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.207 |
| 76.17 | shadowsocks | 244.9 | 614.4 | 22.11 | 0.0 | 10.0 | 11.73 | 16.66 | Au1rxx-base64 | 156.146.38.168 |
| 76.1 | http | 283.7 | 569.2 | 21.21 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.200 |
| 76.07 | http | 290.5 | 586.3 | 21.05 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.214 |
| 75.97 | http | 341.8 | 762.6 | 19.87 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.21 |
| 75.93 | http | 349.1 | 788.1 | 19.7 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.5 |
| 75.88 | http | 298.0 | 614.5 | 20.88 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.212 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | 1.0 | 113 | 129 | prefer |
| Au1rxx-base64 | 0.946 | 0.899 | 237 | 1272 | prefer |
| Surfboard-tg-mixed | 0.734 | 0.722 | 18 | 5223 | prefer |
| DeltaKronecker-all | 0.431 | 0.351 | 937 | 5759 | observe |
| mheidari-all | 0.291 | 0.25 | 12 | 16264 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 43 | observe |
| Epodonios-all | 0.255 | None | 0 | 6141 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7041 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4144 | observe |
| barry-far-vless | 0.255 | None | 0 | 4647 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5047 | observe |
| xiaoji235-airport-v2ray-all | 0.249 | None | 0 | 1861 | observe |
| nscl5-all | 0.231 | None | 0 | 1400 | observe |
| Au1rxx-clash | 0.226 | None | 0 | 1272 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 297 |
| speed | ClientOSError | - | 105 |
| cn-block | TimeoutError | - | 70 |
| geo | ClientOSError | - | 68 |
| speed | TimeoutError | - | 44 |
| 204 | ProxyError | - | 31 |
| cn-block | ProxyError | - | 13 |
| 204 | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 5 |
| speed | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
