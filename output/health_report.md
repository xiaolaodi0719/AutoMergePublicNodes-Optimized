# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-03 10:00:12 |
| 运行耗时 | 296.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83372 |
| 去重后节点 | 24502 |
| TCP 可达 | 3000 |
| 真实可用 | 597 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24502 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 37.0 |
| probe | 61.4 |
| real_test | 154.4 |
| generate | 35.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50617 |
| vmess | 12727 |
| shadowsocks | 10517 |
| trojan | 8428 |
| hysteria2 | 735 |
| http | 176 |
| shadowsocksr | 77 |
| socks | 71 |
| hysteria | 12 |
| anytls | 7 |
| tuic | 5 |

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
| 81.51 | hysteria2 | 290.4 | 707.3 | 21.06 | 0.0 | 10.0 | 13.57 | 17.88 | Au1rxx-base64 | 138.124.68.188 |
| 80.02 | hysteria2 | 286.1 | 697.3 | 21.16 | 0.0 | 8.41 | 13.57 | 17.88 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 79.84 | shadowsocks | 245.5 | 607.0 | 22.09 | 0.0 | 10.0 | 13.87 | 17.88 | Au1rxx-base64 | 156.146.38.169 |
| 79.74 | shadowsocks | 250.0 | 626.2 | 21.99 | 0.0 | 10.0 | 13.87 | 17.88 | Au1rxx-base64 | 156.146.38.167 |
| 79.67 | shadowsocks | 253.2 | 642.9 | 21.92 | 0.0 | 10.0 | 13.87 | 17.88 | Au1rxx-base64 | 156.146.38.170 |
| 79.58 | trojan | 240.9 | 587.3 | 22.2 | 0.0 | 10.0 | 12.5 | 17.88 | Au1rxx-base64 | 64.94.95.118 |
| 79.12 | http | 331.7 | 728.4 | 20.1 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.23 |
| 79.06 | trojan | 263.4 | 615.8 | 21.68 | 0.0 | 10.0 | 12.5 | 17.88 | Au1rxx-base64 | 64.94.95.115 |
| 78.93 | shadowsocks | 284.9 | 717.9 | 21.18 | 0.0 | 10.0 | 13.87 | 17.88 | Au1rxx-base64 | 156.146.38.168 |
| 78.89 | http | 284.6 | 575.4 | 21.19 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.207 |
| 78.86 | http | 326.2 | 735.8 | 20.23 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.8 |
| 78.82 | http | 286.0 | 580.0 | 21.16 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.197 |
| 78.76 | http | 289.1 | 561.1 | 21.08 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.217 |
| 78.65 | http | 294.8 | 607.1 | 20.95 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.198 |
| 78.59 | http | 286.3 | 573.1 | 21.15 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.202 |
| 78.53 | http | 301.0 | 613.8 | 20.81 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.200 |
| 78.51 | http | 283.4 | 575.0 | 21.22 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.205 |
| 78.48 | http | 311.0 | 697.1 | 20.58 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.25 |
| 78.46 | trojan | 263.1 | 617.5 | 21.69 | 0.0 | 10.0 | 12.5 | 17.88 | Au1rxx-base64 | 64.94.95.114 |
| 78.38 | http | 309.9 | 652.2 | 20.6 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.213 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 143 | 344 | prefer |
| Au1rxx-base64 | 0.812 | 0.748 | 543 | 1629 | prefer |
| mheidari-all | 0.426 | 0.333 | 24 | 18806 | observe |
| Surfboard-tg-mixed | 0.393 | 0.309 | 94 | 5244 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3833 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 54 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5285 | observe |
| Epodonios-all | 0.255 | None | 0 | 5831 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6567 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4132 | observe |
| barry-far-vless | 0.255 | None | 0 | 4492 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| DeltaKronecker-all | 0.241 | 0.15 | 60 | 6205 | downweight |
| Au1rxx-clash | 0.24 | None | 0 | 1629 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 151 |
| speed | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyError | - | 17 |
| geo | ClientOSError | - | 14 |
| speed | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 11 |
| cn-block | ProxyError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
