# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-31 14:24:39 |
| 运行耗时 | 267.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 79052 |
| 去重后节点 | 22809 |
| TCP 可达 | 3000 |
| 真实可用 | 480 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22809 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.6 |
| geo | 1.7 |
| tcp | 33.0 |
| probe | 54.5 |
| real_test | 126.8 |
| generate | 43.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46556 |
| vmess | 11996 |
| shadowsocks | 10336 |
| trojan | 9310 |
| hysteria2 | 575 |
| http | 98 |
| shadowsocksr | 70 |
| socks | 55 |
| anytls | 26 |
| tuic | 16 |
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
| 81.68 | http | 284.7 | 670.0 | 21.19 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.5 |
| 81.32 | http | 298.9 | 703.8 | 20.86 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.8 |
| 80.35 | http | 304.6 | 741.3 | 20.73 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.7 |
| 79.84 | hysteria2 | 270.9 | 702.8 | 21.51 | 0.0 | 9.84 | 12.19 | 17.3 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 77.73 | shadowsocks | 256.9 | 633.7 | 21.83 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 156.146.38.168 |
| 77.67 | shadowsocks | 259.5 | 634.1 | 21.77 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 156.146.38.169 |
| 77.59 | shadowsocks | 263.2 | 660.0 | 21.69 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 37.19.198.236 |
| 77.56 | shadowsocks | 264.1 | 661.5 | 21.66 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 37.19.198.244 |
| 77.54 | shadowsocks | 265.0 | 669.1 | 21.64 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 37.19.198.160 |
| 77.42 | shadowsocks | 270.3 | 682.5 | 21.52 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 37.19.198.243 |
| 77.0 | hysteria2 | 270.8 | 695.2 | 21.51 | 0.0 | 10.0 | 12.19 | 17.3 | Au1rxx-base64 | 138.124.68.188 |
| 76.8 | shadowsocks | 297.0 | 741.1 | 20.9 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 156.146.38.170 |
| 76.24 | shadowsocks | 284.2 | 693.8 | 21.2 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 68.168.222.210 |
| 75.51 | trojan | 291.9 | 703.8 | 21.02 | 0.0 | 10.0 | 11.71 | 17.3 | Au1rxx-base64 | 153.75.250.171 |
| 75.21 | hysteria2 | 257.5 | 661.8 | 21.82 | 0.0 | 10.0 | 12.19 | 17.3 | Au1rxx-base64 | 159.223.157.129 |
| 75.13 | shadowsocks | 261.7 | 636.0 | 21.72 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 156.146.38.167 |
| 73.35 | vless | 277.5 | 616.7 | 21.35 | 0.0 | 10.0 | 7.28 | 17.3 | Au1rxx-base64 | 216.227.161.95 |
| 73.29 | vless | 297.9 | 704.0 | 20.88 | 0.0 | 10.0 | 7.28 | 17.3 | Au1rxx-base64 | 78.111.89.171 |
| 72.63 | shadowsocks | 283.4 | 557.9 | 21.22 | 0.0 | 10.0 | 12.6 | 17.3 | Au1rxx-base64 | 173.244.56.6 |
| 72.49 | vless | 288.5 | 691.4 | 21.1 | 0.0 | 10.0 | 7.28 | 17.3 | Au1rxx-base64 | 167.17.69.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 80 | 110 | prefer |
| Au1rxx-base64 | 0.889 | 0.829 | 392 | 1533 | prefer |
| DeltaKronecker-all | 0.589 | 0.51 | 51 | 5144 | observe |
| Surfboard-tg-mixed | 0.575 | 0.494 | 89 | 5429 | observe |
| mheidari-all | 0.421 | 0.667 | 6 | 16815 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 48 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5507 | observe |
| Epodonios-all | 0.255 | None | 0 | 5989 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3966 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7049 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4260 | observe |
| barry-far-vless | 0.255 | None | 0 | 4528 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5074 | observe |
| xiaoji235-airport-v2ray-all | 0.249 | None | 0 | 1861 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 41 |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 24 |
| speed | TimeoutError | - | 18 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
