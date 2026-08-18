# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-18 13:01:00 |
| 运行耗时 | 384.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 91953 |
| 去重后节点 | 24182 |
| TCP 可达 | 3000 |
| 真实可用 | 1241 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24182 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| geo | 1.4 |
| tcp | 38.5 |
| probe | 75.1 |
| real_test | 234.3 |
| generate | 26.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52693 |
| trojan | 16396 |
| shadowsocks | 10453 |
| vmess | 9582 |
| hysteria2 | 2296 |
| http | 183 |
| socks | 144 |
| shadowsocksr | 131 |
| anytls | 43 |
| tuic | 19 |
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
| 83.88 | http | 248.5 | 643.1 | 22.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 83.77 | http | 253.5 | 651.3 | 21.91 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 83.75 | http | 254.3 | 657.4 | 21.89 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.74 | http | 254.6 | 656.4 | 21.88 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 83.71 | http | 255.9 | 664.1 | 21.85 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 83.63 | http | 259.3 | 659.2 | 21.77 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.57 | http | 262.2 | 683.4 | 21.71 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 83.55 | http | 263.2 | 686.2 | 21.69 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 83.54 | http | 263.3 | 679.4 | 21.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 83.52 | http | 264.4 | 687.0 | 21.66 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 83.52 | http | 264.4 | 689.2 | 21.66 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.51 | http | 264.8 | 680.8 | 21.65 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.46 | http | 267.0 | 680.2 | 21.6 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.46 | http | 267.0 | 679.2 | 21.6 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 83.42 | http | 268.7 | 678.2 | 21.56 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 83.4 | http | 269.5 | 684.2 | 21.54 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 83.29 | http | 274.2 | 681.9 | 21.43 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 82.32 | shadowsocks | 240.4 | 637.6 | 22.21 | 0.0 | 10.0 | 14.11 | 20.0 | Surfboard-tg-mixed | 37.19.198.236 |
| 81.65 | http | 266.6 | 675.3 | 21.61 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 81.08 | shadowsocks | 250.7 | 664.3 | 21.97 | 0.0 | 10.0 | 14.11 | 20.0 | Surfboard-tg-mixed | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 0.959 | 365 | 21086 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Au1rxx-base64 | 0.975 | 0.905 | 698 | 1759 | prefer |
| Surfboard-tg-mixed | 0.87 | 0.794 | 160 | 6253 | prefer |
| DeltaKronecker-all | 0.372 | 0.444 | 9 | 5725 | observe |
| nscl5-all | 0.335 | 1.0 | 1 | 2992 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5068 | observe |
| Epodonios-all | 0.255 | None | 0 | 6795 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3984 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6898 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4907 | observe |
| barry-far-vless | 0.255 | None | 0 | 5206 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4045 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6329 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 17 |
| geo | TimeoutError | - | 17 |
| geo | ClientOSError | - | 10 |
| speed | ClientOSError | - | 10 |
| speed | TimeoutError | - | 10 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:31282: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
