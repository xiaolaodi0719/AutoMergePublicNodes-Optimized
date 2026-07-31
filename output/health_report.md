# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-31 09:00:23 |
| 运行耗时 | 220.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 77153 |
| 去重后节点 | 22423 |
| TCP 可达 | 3000 |
| 真实可用 | 366 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22423 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.3 |
| tcp | 31.9 |
| probe | 49.6 |
| real_test | 96.9 |
| generate | 36.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44560 |
| vmess | 11819 |
| shadowsocks | 10118 |
| trojan | 9780 |
| hysteria2 | 586 |
| http | 98 |
| shadowsocksr | 73 |
| socks | 63 |
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
| 82.34 | hysteria2 | 286.6 | 715.3 | 21.14 | 0.0 | 9.95 | 13.33 | 18.92 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.12 | trojan | 252.6 | 608.7 | 21.93 | 0.0 | 10.0 | 14.06 | 18.92 | Au1rxx-base64 | 163.245.196.68 |
| 80.85 | shadowsocks | 235.8 | 604.1 | 22.32 | 0.0 | 10.0 | 13.61 | 18.92 | Au1rxx-base64 | 156.146.38.170 |
| 80.62 | shadowsocks | 245.8 | 638.4 | 22.09 | 0.0 | 10.0 | 13.61 | 18.92 | Au1rxx-base64 | 156.146.38.169 |
| 80.6 | shadowsocks | 246.8 | 610.8 | 22.07 | 0.0 | 10.0 | 13.61 | 18.92 | Au1rxx-base64 | 156.146.38.168 |
| 79.41 | shadowsocks | 298.0 | 721.7 | 20.88 | 0.0 | 10.0 | 13.61 | 18.92 | Au1rxx-base64 | 37.19.198.236 |
| 79.33 | trojan | 364.0 | 937.7 | 19.35 | 0.0 | 10.0 | 14.06 | 18.92 | Au1rxx-base64 | 64.94.95.118 |
| 79.22 | trojan | 318.5 | 735.2 | 20.41 | 0.0 | 10.0 | 14.06 | 18.92 | Au1rxx-base64 | 153.75.250.171 |
| 78.66 | http | 281.1 | 561.4 | 21.27 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.196 |
| 78.48 | shadowsocks | 280.3 | 670.8 | 21.29 | 0.0 | 10.0 | 13.61 | 18.92 | Au1rxx-base64 | 37.19.198.244 |
| 77.98 | shadowsocks | 230.4 | 599.1 | 22.45 | 0.0 | 10.0 | 13.61 | 18.92 | Au1rxx-base64 | 156.146.38.167 |
| 77.75 | http | 283.3 | 574.9 | 21.22 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.202 |
| 77.67 | hysteria2 | 270.5 | 661.5 | 21.52 | 0.0 | 10.0 | 13.33 | 18.92 | Au1rxx-base64 | 159.223.157.129 |
| 77.66 | hysteria2 | 275.0 | 697.8 | 21.41 | 0.0 | 10.0 | 13.33 | 18.92 | Au1rxx-base64 | 138.124.68.188 |
| 77.65 | http | 287.2 | 584.8 | 21.13 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.218 |
| 77.6 | http | 278.9 | 561.0 | 21.32 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.199 |
| 77.42 | shadowsocks | 283.3 | 677.4 | 21.22 | 0.0 | 10.0 | 13.61 | 18.92 | Au1rxx-base64 | 37.19.198.243 |
| 76.86 | http | 291.5 | 590.7 | 21.03 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.204 |
| 76.84 | http | 290.6 | 594.1 | 21.05 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.198 |
| 76.84 | shadowsocks | 336.0 | 841.0 | 20.0 | 0.0 | 10.0 | 13.61 | 18.92 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 81 | 110 | prefer |
| Au1rxx-base64 | 0.865 | 0.816 | 190 | 1319 | prefer |
| Surfboard-tg-mixed | 0.62 | 0.541 | 148 | 5242 | observe |
| DeltaKronecker-all | 0.557 | 0.477 | 86 | 5144 | observe |
| mheidari-all | 0.474 | 0.6 | 10 | 16339 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 45 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5507 | observe |
| Epodonios-all | 0.255 | None | 0 | 5918 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6473 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4146 | observe |
| barry-far-vless | 0.255 | None | 0 | 4510 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5074 | observe |
| nscl5-all | 0.235 | 0.333 | 3 | 1400 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 48 |
| 204 | ProxyError | - | 21 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 14 |
| geo | ClientOSError | - | 13 |
| speed | TimeoutError | - | 13 |
| speed | ClientOSError | - | 11 |
| cn-block | ProxyError | - | 7 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
