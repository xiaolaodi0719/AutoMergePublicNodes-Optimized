# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-12 05:36:33 |
| 运行耗时 | 1100.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99742 |
| 去重后节点 | 27633 |
| TCP 可达 | 3000 |
| 真实可用 | 530 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27633 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.3 |
| tcp | 47.4 |
| probe | 414.5 |
| real_test | 559.0 |
| generate | 72.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58167 |
| vmess | 15773 |
| shadowsocks | 11934 |
| trojan | 11407 |
| hysteria2 | 1489 |
| http | 683 |
| shadowsocksr | 165 |
| socks | 69 |
| anytls | 31 |
| hysteria | 16 |
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
| 84.94 | vless | 213.3 | 535.9 | 22.84 | 0.0 | 10.0 | 12.26 | 19.84 | Au1rxx-base64 | 154.9.241.170 |
| 84.63 | vless | 226.6 | 564.0 | 22.53 | 0.0 | 10.0 | 12.26 | 19.84 | Au1rxx-base64 | 154.12.38.202 |
| 84.41 | hysteria2 | 230.6 | 231.6 | 22.44 | 6.31 | 9.42 | 13.5 | 19.84 | Au1rxx-base64 | vp3.yysyy.online |
| 84.26 | hysteria2 | 235.5 | 225.0 | 22.33 | 6.56 | 9.58 | 13.5 | 19.84 | Au1rxx-base64 | 45.32.10.7 |
| 83.57 | vless | 272.7 | 717.4 | 21.47 | 0.0 | 10.0 | 12.26 | 19.84 | Au1rxx-base64 | 154.29.145.196 |
| 83.27 | vless | 218.9 | 512.8 | 22.71 | 0.0 | 10.0 | 12.26 | 18.3 | mheidari-all | 47.251.108.158 |
| 82.69 | vless | 300.0 | 718.5 | 20.83 | 0.0 | 10.0 | 12.26 | 19.84 | Au1rxx-base64 | 23.95.222.127 |
| 82.57 | shadowsocks | 217.6 | 542.3 | 22.74 | 0.0 | 10.0 | 13.99 | 19.84 | Au1rxx-base64 | 173.244.56.9 |
| 81.73 | vless | 274.2 | 610.0 | 21.43 | 0.0 | 10.0 | 12.26 | 19.84 | Au1rxx-base64 | 15.204.97.216 |
| 81.68 | shadowsocks | 256.1 | 626.9 | 21.85 | 0.0 | 10.0 | 13.99 | 19.84 | Au1rxx-base64 | 156.146.38.168 |
| 81.65 | shadowsocks | 257.3 | 624.9 | 21.82 | 0.0 | 10.0 | 13.99 | 19.84 | Au1rxx-base64 | 156.146.38.169 |
| 81.51 | shadowsocks | 263.3 | 643.6 | 21.68 | 0.0 | 10.0 | 13.99 | 19.84 | Au1rxx-base64 | 156.146.38.170 |
| 80.9 | shadowsocks | 260.0 | 636.4 | 21.76 | 0.0 | 10.0 | 13.99 | 19.84 | Au1rxx-base64 | 156.146.38.167 |
| 80.43 | shadowsocks | 265.0 | 616.4 | 21.64 | 0.0 | 10.0 | 13.99 | 19.84 | Au1rxx-base64 | 5.78.51.123 |
| 80.43 | vless | 272.8 | 605.7 | 21.46 | 0.0 | 10.0 | 12.26 | 19.84 | Au1rxx-base64 | 15.204.97.197 |
| 80.09 | hysteria2 | 316.2 | 730.7 | 20.46 | 0.0 | 10.0 | 13.5 | 19.84 | Au1rxx-base64 | 129.213.91.185 |
| 79.75 | vless | 292.8 | 702.9 | 21.0 | 0.0 | 10.0 | 12.26 | 19.84 | Au1rxx-base64 | 147.45.60.160 |
| 79.19 | shadowsocks | 275.7 | 757.3 | 21.4 | 0.0 | 10.0 | 13.99 | 18.3 | mheidari-all | 173.234.25.90 |
| 79.01 | hysteria2 | 320.0 | 259.6 | 20.37 | 5.27 | 9.57 | 13.5 | 19.84 | Au1rxx-base64 | 158.101.148.79 |
| 77.89 | shadowsocks | 279.2 | 282.5 | 21.32 | 4.4 | 9.58 | 13.99 | 19.84 | Au1rxx-base64 | 149.22.87.204 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | 0.916 | 383 | 1810 | prefer |
| ermaozi | 0.701 | 0.679 | 53 | 708 | prefer |
| Surfboard-tg-mixed | 0.519 | 1.0 | 5 | 7200 | observe |
| mheidari-all | 0.436 | 0.355 | 369 | 23656 | observe |
| DeltaKronecker-all | 0.385 | 0.5 | 8 | 5372 | observe |
| ermaozi-get_subscribe | 0.279 | 1.0 | 1 | 600 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| Epodonios-all | 0.255 | None | 0 | 7699 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9920 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5717 | observe |
| barry-far-vless | 0.255 | None | 0 | 5961 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4284 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 130 |
| speed | TimeoutError | - | 53 |
| geo | ClientOSError | - | 29 |
| 204 | ProxyError | - | 24 |
| speed | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
