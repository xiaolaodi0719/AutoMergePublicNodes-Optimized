# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-03 14:54:22 |
| 运行耗时 | 261.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83610 |
| 去重后节点 | 24688 |
| TCP 可达 | 3000 |
| 真实可用 | 556 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24688 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 37.4 |
| probe | 59.2 |
| real_test | 131.5 |
| generate | 27.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50828 |
| vmess | 12741 |
| shadowsocks | 10446 |
| trojan | 8614 |
| hysteria2 | 731 |
| http | 86 |
| socks | 71 |
| shadowsocksr | 71 |
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
| 79.91 | hysteria2 | 281.7 | 680.3 | 21.26 | 0.0 | 10.0 | 13.57 | 16.24 | Au1rxx-base64 | 159.223.157.129 |
| 78.59 | http | 286.0 | 579.8 | 21.16 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.211 |
| 78.55 | http | 282.3 | 569.8 | 21.24 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.218 |
| 77.82 | shadowsocks | 229.6 | 587.8 | 22.46 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 156.146.38.170 |
| 77.62 | shadowsocks | 238.5 | 596.4 | 22.26 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 156.146.38.167 |
| 77.37 | shadowsocks | 249.3 | 608.6 | 22.01 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 156.146.38.169 |
| 77.35 | shadowsocks | 249.8 | 647.3 | 21.99 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 156.146.38.168 |
| 77.19 | trojan | 256.0 | 608.4 | 21.85 | 0.0 | 10.0 | 12.1 | 16.24 | Au1rxx-base64 | 64.94.95.118 |
| 76.61 | trojan | 281.0 | 677.8 | 21.27 | 0.0 | 10.0 | 12.1 | 16.24 | Au1rxx-base64 | 64.94.95.114 |
| 76.45 | shadowsocks | 266.6 | 644.0 | 21.61 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 37.19.198.243 |
| 76.01 | shadowsocks | 308.0 | 727.4 | 20.65 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 37.19.198.244 |
| 75.94 | http | 392.8 | 648.2 | 18.69 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.216 |
| 75.63 | trojan | 249.8 | 595.8 | 22.0 | 0.0 | 10.0 | 12.1 | 16.24 | Au1rxx-base64 | 64.94.95.115 |
| 74.5 | trojan | 307.8 | 702.5 | 20.65 | 0.0 | 10.0 | 12.1 | 16.24 | Au1rxx-base64 | 153.75.250.171 |
| 74.31 | shadowsocks | 294.8 | 738.6 | 20.95 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 37.19.198.236 |
| 74.3 | shadowsocks | 286.2 | 674.0 | 21.15 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 37.19.198.160 |
| 74.21 | trojan | 337.1 | 825.3 | 19.97 | 0.0 | 10.0 | 12.1 | 16.24 | Au1rxx-base64 | 163.245.196.68 |
| 73.98 | trojan | 325.2 | 811.4 | 20.25 | 0.0 | 10.0 | 12.1 | 16.24 | Au1rxx-base64 | 64.94.95.117 |
| 73.51 | shadowsocks | 360.5 | 841.9 | 19.43 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 185.196.61.82 |
| 73.07 | shadowsocks | 278.7 | 599.2 | 21.33 | 0.0 | 10.0 | 13.12 | 16.24 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.99 | 1.0 | 69 | 92 | prefer |
| Au1rxx-base64 | 0.806 | 0.739 | 518 | 1692 | prefer |
| mheidari-all | 0.55 | 0.469 | 196 | 18776 | observe |
| Surfboard-tg-mixed | 0.459 | 0.37 | 27 | 5293 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3833 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 54 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5285 | observe |
| Epodonios-all | 0.255 | None | 0 | 5890 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6783 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4162 | observe |
| barry-far-vless | 0.255 | None | 0 | 4526 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1692 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 70 |
| 204 | ProxyError | - | 34 |
| 204 | TimeoutError | - | 32 |
| geo | TimeoutError | - | 30 |
| speed | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 23 |
| speed | ClientOSError | - | 21 |
| 204 | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
