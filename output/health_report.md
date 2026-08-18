# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-18 06:58:18 |
| 运行耗时 | 416.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 91021 |
| 去重后节点 | 23861 |
| TCP 可达 | 3000 |
| 真实可用 | 1200 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23861 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.0 |
| tcp | 36.7 |
| probe | 77.8 |
| real_test | 259.6 |
| generate | 35.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51744 |
| trojan | 17415 |
| shadowsocks | 10460 |
| vmess | 9396 |
| hysteria2 | 1462 |
| http | 186 |
| socks | 148 |
| shadowsocksr | 133 |
| anytls | 44 |
| tuic | 20 |
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
| 83.28 | http | 274.6 | 663.1 | 21.42 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 83.13 | http | 281.1 | 672.8 | 21.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 83.08 | http | 283.1 | 682.2 | 21.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.07 | http | 283.7 | 687.1 | 21.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 83.03 | http | 278.3 | 664.5 | 21.34 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 83.01 | http | 286.4 | 698.6 | 21.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 82.92 | http | 290.1 | 712.3 | 21.06 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 82.82 | hysteria2 | 267.6 | 694.1 | 21.58 | 0.0 | 10.0 | 13.42 | 18.82 | mheidari-all | 138.124.68.188 |
| 82.81 | http | 294.9 | 725.5 | 20.95 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 82.8 | http | 295.6 | 723.6 | 20.94 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 82.75 | http | 293.1 | 715.5 | 20.99 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 82.62 | http | 289.3 | 691.3 | 21.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 82.61 | http | 290.5 | 699.3 | 21.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 82.48 | http | 295.6 | 714.8 | 20.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 82.11 | http | 298.3 | 711.4 | 20.87 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 81.94 | http | 290.5 | 693.4 | 21.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 81.82 | http | 295.0 | 704.5 | 20.95 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 81.78 | http | 290.8 | 695.1 | 21.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 81.73 | http | 281.8 | 669.7 | 21.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 81.33 | shadowsocks | 251.7 | 622.5 | 21.95 | 0.0 | 10.0 | 14.56 | 18.82 | mheidari-all | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | 0.93 | 172 | 6138 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Au1rxx-base64 | 0.901 | 0.846 | 816 | 1408 | prefer |
| mheidari-all | 0.568 | 0.487 | 439 | 21284 | observe |
| nscl5-all | 0.438 | 1.0 | 3 | 2992 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 6329 | observe |
| DeltaKronecker-all | 0.332 | 0.286 | 14 | 5725 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5068 | observe |
| Epodonios-all | 0.255 | None | 0 | 6730 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6856 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4777 | observe |
| barry-far-vless | 0.255 | None | 0 | 5074 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4045 | observe |
| Au1rxx-clash | 0.231 | None | 0 | 1408 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 127 |
| speed | TimeoutError | - | 96 |
| geo | ClientOSError | - | 72 |
| speed | ClientOSError | - | 32 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 6 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
