# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-02 19:22:54 |
| 运行耗时 | 307.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 81351 |
| 去重后节点 | 22692 |
| TCP 可达 | 3000 |
| 真实可用 | 629 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22692 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.4 |
| tcp | 34.6 |
| probe | 63.9 |
| real_test | 157.7 |
| generate | 43.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49692 |
| vmess | 12547 |
| shadowsocks | 10287 |
| trojan | 7755 |
| hysteria2 | 738 |
| http | 165 |
| shadowsocksr | 73 |
| socks | 72 |
| hysteria | 10 |
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
| 82.85 | http | 295.0 | 806.5 | 20.95 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.8 |
| 82.78 | http | 297.9 | 811.4 | 20.88 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.5 |
| 82.75 | http | 299.4 | 812.6 | 20.85 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.23 |
| 82.66 | http | 303.0 | 825.1 | 20.76 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.7 |
| 82.57 | http | 307.1 | 842.3 | 20.67 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.20 |
| 82.5 | http | 310.2 | 860.7 | 20.6 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.25 |
| 82.49 | http | 310.4 | 851.5 | 20.59 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.21 |
| 80.64 | hysteria2 | 245.3 | 669.4 | 22.1 | 0.0 | 10.0 | 13.8 | 15.74 | Au1rxx-base64 | 138.124.68.188 |
| 80.31 | hysteria2 | 255.2 | 697.8 | 21.87 | 0.0 | 10.0 | 13.8 | 15.74 | Au1rxx-base64 | 159.223.157.129 |
| 78.77 | hysteria2 | 245.0 | 667.7 | 22.11 | 0.0 | 8.12 | 13.8 | 15.74 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 77.14 | vless | 249.9 | 656.2 | 21.99 | 0.0 | 10.0 | 9.41 | 15.74 | Au1rxx-base64 | 167.17.69.171 |
| 76.33 | vless | 284.8 | 722.9 | 21.18 | 0.0 | 10.0 | 9.41 | 15.74 | Au1rxx-base64 | 159.195.12.98 |
| 75.73 | shadowsocks | 242.2 | 669.7 | 22.17 | 0.0 | 10.0 | 11.82 | 15.74 | Au1rxx-base64 | 37.19.198.243 |
| 75.68 | trojan | 320.4 | 598.8 | 20.36 | 0.0 | 10.0 | 12.5 | 13.82 | Surfboard-tg-mixed | 104.16.100.215 |
| 75.63 | shadowsocks | 246.6 | 684.9 | 22.07 | 0.0 | 10.0 | 11.82 | 15.74 | Au1rxx-base64 | 37.19.198.160 |
| 75.12 | http | 360.2 | 633.7 | 19.44 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.216 |
| 75.06 | http | 353.2 | 636.7 | 19.6 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.204 |
| 74.86 | shadowsocks | 279.8 | 784.9 | 21.3 | 0.0 | 10.0 | 11.82 | 15.74 | Au1rxx-base64 | 37.19.198.244 |
| 74.83 | http | 369.0 | 661.2 | 19.24 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.197 |
| 74.76 | http | 365.2 | 652.5 | 19.32 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.209 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 143 | 344 | prefer |
| Au1rxx-base64 | 0.784 | 0.718 | 529 | 1651 | prefer |
| DeltaKronecker-all | 0.511 | 0.43 | 135 | 3437 | observe |
| Surfboard-tg-mixed | 0.433 | 0.35 | 117 | 5222 | observe |
| mheidari-all | 0.418 | 0.5 | 10 | 18817 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3833 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 56 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5486 | observe |
| Epodonios-all | 0.255 | None | 0 | 5783 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3975 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7117 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4122 | observe |
| barry-far-vless | 0.255 | None | 0 | 4490 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5208 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 108 |
| 204 | TimeoutError | - | 57 |
| 204 | ProxyError | - | 37 |
| speed | TimeoutError | - | 35 |
| geo | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 13 |
| cn-block | ProxyError | - | 9 |
| geo | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
