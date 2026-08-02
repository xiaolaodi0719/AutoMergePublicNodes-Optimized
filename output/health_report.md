# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-02 08:35:20 |
| 运行耗时 | 292.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 77313 |
| 去重后节点 | 22742 |
| TCP 可达 | 3000 |
| 真实可用 | 673 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22742 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 34.5 |
| probe | 60.6 |
| real_test | 158.0 |
| generate | 31.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45662 |
| vmess | 12301 |
| shadowsocks | 10254 |
| trojan | 8122 |
| hysteria2 | 613 |
| http | 165 |
| socks | 77 |
| shadowsocksr | 72 |
| anytls | 26 |
| hysteria | 14 |
| tuic | 7 |

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
| 82.34 | hysteria2 | 279.0 | 676.5 | 21.32 | 0.0 | 9.48 | 13.64 | 19.0 | Au1rxx-base64 | 159.223.157.129 |
| 81.97 | hysteria2 | 298.4 | 734.1 | 20.87 | 0.0 | 9.49 | 13.64 | 19.0 | Au1rxx-base64 | 138.124.68.188 |
| 81.43 | hysteria2 | 291.5 | 722.0 | 21.03 | 0.0 | 8.76 | 13.64 | 19.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 80.24 | shadowsocks | 247.9 | 642.8 | 22.04 | 0.0 | 9.56 | 13.64 | 19.0 | Au1rxx-base64 | 156.146.38.168 |
| 79.28 | shadowsocks | 289.2 | 750.9 | 21.08 | 0.0 | 9.56 | 13.64 | 19.0 | Au1rxx-base64 | 156.146.38.169 |
| 78.97 | http | 286.6 | 584.1 | 21.14 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.211 |
| 78.96 | http | 282.1 | 570.3 | 21.25 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.204 |
| 78.96 | http | 284.8 | 576.0 | 21.19 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.216 |
| 78.96 | http | 288.2 | 588.7 | 21.11 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.212 |
| 78.96 | http | 289.5 | 591.8 | 21.08 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.208 |
| 78.93 | http | 288.7 | 587.5 | 21.1 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.195 |
| 78.92 | http | 283.4 | 570.3 | 21.22 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.210 |
| 78.92 | http | 284.3 | 577.5 | 21.2 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.207 |
| 78.89 | http | 288.8 | 576.3 | 21.09 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.198 |
| 78.87 | http | 285.7 | 579.2 | 21.16 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.213 |
| 78.86 | http | 283.8 | 575.2 | 21.21 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.214 |
| 78.85 | http | 282.8 | 571.8 | 21.23 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.205 |
| 78.84 | http | 285.9 | 582.5 | 21.16 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.220 |
| 78.83 | http | 290.2 | 594.0 | 21.06 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.202 |
| 78.82 | http | 288.1 | 581.3 | 21.11 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.206 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.978 | 0.968 | 219 | 344 | prefer |
| Au1rxx-base64 | 0.787 | 0.724 | 511 | 1589 | prefer |
| Surfboard-tg-mixed | 0.653 | 0.574 | 108 | 5167 | observe |
| DeltaKronecker-all | 0.591 | 0.511 | 45 | 4549 | observe |
| Epodonios-all | 0.335 | 1.0 | 1 | 5764 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| chromego_merge | 0.258 | 1.0 | 1 | 70 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5486 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3969 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6688 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3990 | observe |
| barry-far-vless | 0.255 | None | 0 | 4406 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5071 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 94 |
| speed | TimeoutError | - | 44 |
| cn-block | TimeoutError | - | 20 |
| geo | ClientOSError | - | 19 |
| 204 | TimeoutError | - | 17 |
| speed | ClientOSError | - | 14 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 5 |
| geo | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
