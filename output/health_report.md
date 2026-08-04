# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-04 08:50:38 |
| 运行耗时 | 268.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85567 |
| 去重后节点 | 24255 |
| TCP 可达 | 3000 |
| 真实可用 | 562 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24255 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.3 |
| tcp | 36.7 |
| probe | 62.2 |
| real_test | 129.8 |
| generate | 29.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52325 |
| vmess | 13001 |
| shadowsocks | 10047 |
| trojan | 8931 |
| hysteria2 | 1002 |
| http | 76 |
| shadowsocksr | 74 |
| socks | 72 |
| hysteria | 19 |
| tuic | 10 |
| anytls | 10 |

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
| 80.84 | hysteria2 | 340.5 | 910.1 | 19.9 | 0.0 | 10.0 | 14.32 | 17.72 | Au1rxx-base64 | 159.223.157.129 |
| 79.62 | shadowsocks | 257.0 | 624.8 | 21.83 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 156.146.38.170 |
| 79.57 | shadowsocks | 259.0 | 636.8 | 21.78 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 156.146.38.168 |
| 79.33 | shadowsocks | 269.5 | 689.9 | 21.54 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 37.19.198.160 |
| 79.24 | shadowsocks | 273.4 | 700.3 | 21.45 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 37.19.198.244 |
| 79.17 | shadowsocks | 276.4 | 702.4 | 21.38 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 37.19.198.243 |
| 78.79 | trojan | 293.5 | 732.4 | 20.98 | 0.0 | 10.0 | 13.09 | 17.72 | Au1rxx-base64 | 153.75.250.171 |
| 78.56 | shadowsocks | 302.7 | 786.7 | 20.77 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 37.19.198.236 |
| 77.97 | shadowsocks | 306.4 | 798.6 | 20.68 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 185.196.61.82 |
| 77.75 | hysteria2 | 262.3 | 677.6 | 21.71 | 0.0 | 10.0 | 14.32 | 17.72 | Au1rxx-base64 | 138.124.68.188 |
| 76.85 | shadowsocks | 249.9 | 636.0 | 21.99 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 198.98.53.130 |
| 76.02 | trojan | 284.3 | 655.3 | 21.2 | 0.0 | 10.0 | 13.09 | 17.72 | Au1rxx-base64 | 163.245.196.68 |
| 75.91 | hysteria2 | 262.7 | 681.6 | 21.7 | 0.0 | 8.17 | 14.32 | 17.72 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 74.6 | vless | 286.5 | 698.5 | 21.15 | 0.0 | 10.0 | 6.27 | 17.72 | Au1rxx-base64 | 167.17.69.171 |
| 74.38 | shadowsocks | 310.5 | 719.6 | 20.59 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 108.181.57.93 |
| 74.34 | vless | 320.9 | 861.4 | 20.35 | 0.0 | 10.0 | 6.27 | 17.72 | Au1rxx-base64 | 216.152.147.28 |
| 74.32 | shadowsocks | 306.0 | 643.2 | 20.69 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 149.22.95.183 |
| 73.99 | vless | 292.9 | 737.6 | 21.0 | 0.0 | 10.0 | 6.27 | 17.72 | Au1rxx-base64 | 47.253.226.114 |
| 73.83 | shadowsocks | 289.6 | 538.8 | 21.07 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 108.181.0.177 |
| 73.54 | shadowsocks | 362.2 | 782.8 | 19.39 | 0.0 | 10.0 | 14.07 | 17.72 | Au1rxx-base64 | 172.245.235.84 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.902 | 0.91 | 67 | 92 | prefer |
| Au1rxx-base64 | 0.833 | 0.767 | 597 | 1672 | prefer |
| mheidari-all | 0.413 | 0.325 | 40 | 20242 | observe |
| Surfboard-tg-mixed | 0.366 | 0.28 | 75 | 5211 | observe |
| SoliSpirit-all | 0.335 | 1.0 | 1 | 6811 | observe |
| DeltaKronecker-all | 0.33 | 0.233 | 30 | 5788 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5251 | observe |
| Epodonios-all | 0.255 | None | 0 | 5819 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4191 | observe |
| barry-far-vless | 0.255 | None | 0 | 4536 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5110 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5127 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1672 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 145 |
| speed | TimeoutError | - | 23 |
| geo | ClientOSError | - | 20 |
| 204 | ProxyError | - | 15 |
| speed | ClientOSError | - | 14 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
