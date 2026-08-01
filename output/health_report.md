# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-01 08:32:44 |
| 运行耗时 | 311.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78775 |
| 去重后节点 | 23170 |
| TCP 可达 | 3000 |
| 真实可用 | 621 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23170 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.3 |
| tcp | 34.1 |
| probe | 65.8 |
| real_test | 167.7 |
| generate | 35.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47189 |
| vmess | 12309 |
| shadowsocks | 10141 |
| trojan | 8175 |
| hysteria2 | 601 |
| http | 173 |
| shadowsocksr | 76 |
| socks | 63 |
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
| 83.89 | http | 239.8 | 633.7 | 22.23 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.5 |
| 83.45 | http | 258.7 | 668.0 | 21.79 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.8 |
| 83.16 | http | 271.2 | 693.3 | 21.5 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.7 |
| 82.72 | http | 247.0 | 640.2 | 22.06 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.50 |
| 82.72 | http | 247.1 | 634.0 | 22.06 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.23 |
| 82.26 | http | 267.0 | 685.0 | 21.6 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.21 |
| 82.24 | http | 267.7 | 691.2 | 21.58 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.25 |
| 82.11 | hysteria2 | 258.7 | 686.5 | 21.79 | 0.0 | 8.61 | 14.25 | 18.46 | Au1rxx-base64 | 138.124.68.188 |
| 82.09 | http | 274.1 | 682.4 | 21.43 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.20 |
| 81.96 | http | 236.6 | 614.4 | 22.3 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.16 |
| 81.95 | hysteria2 | 252.5 | 683.5 | 21.93 | 0.0 | 8.31 | 14.25 | 18.46 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.5 | hysteria2 | 236.9 | 652.6 | 22.29 | 0.0 | 8.6 | 14.25 | 18.46 | Au1rxx-base64 | 159.223.157.129 |
| 81.49 | http | 256.9 | 646.0 | 21.83 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.33 |
| 79.59 | shadowsocks | 223.4 | 616.4 | 22.61 | 0.0 | 8.7 | 13.82 | 18.46 | Au1rxx-base64 | 37.19.198.236 |
| 79.24 | shadowsocks | 238.4 | 664.1 | 22.26 | 0.0 | 8.7 | 13.82 | 18.46 | Au1rxx-base64 | 37.19.198.244 |
| 79.2 | shadowsocks | 240.3 | 671.7 | 22.22 | 0.0 | 8.7 | 13.82 | 18.46 | Au1rxx-base64 | 37.19.198.243 |
| 79.03 | shadowsocks | 247.8 | 687.9 | 22.04 | 0.0 | 8.71 | 13.82 | 18.46 | Au1rxx-base64 | 37.19.198.160 |
| 78.49 | http | 256.8 | 681.5 | 21.83 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.43 |
| 78.31 | shadowsocks | 312.9 | 874.1 | 20.53 | 0.0 | 10.0 | 13.82 | 18.46 | Au1rxx-base64 | 68.168.222.210 |
| 78.29 | http | 265.4 | 677.0 | 21.63 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.41 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 157 | 228 | prefer |
| Au1rxx-base64 | 0.769 | 0.704 | 506 | 1655 | prefer |
| Surfboard-tg-mixed | 0.506 | 0.424 | 92 | 5316 | observe |
| DeltaKronecker-all | 0.354 | 0.272 | 232 | 5502 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| mheidari-all | 0.314 | 0.333 | 9 | 16723 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| tg-v2nodes | 0.256 | 1.0 | 1 | 20 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5391 | observe |
| Epodonios-all | 0.255 | None | 0 | 5937 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6670 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4168 | observe |
| barry-far-vless | 0.255 | None | 0 | 4552 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5039 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 140 |
| speed | TimeoutError | - | 53 |
| geo | ClientOSError | - | 51 |
| speed | ClientOSError | - | 39 |
| 204 | TimeoutError | - | 39 |
| cn-block | TimeoutError | - | 26 |
| 204 | ProxyError | - | 21 |
| 204 | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
