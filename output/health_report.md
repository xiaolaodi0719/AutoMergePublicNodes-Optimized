# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 21:38:10 |
| 运行耗时 | 645.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98750 |
| 去重后节点 | 27376 |
| TCP 可达 | 3000 |
| 真实可用 | 381 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27376 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.5 |
| tcp | 47.8 |
| probe | 286.8 |
| real_test | 228.9 |
| generate | 73.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58836 |
| vmess | 16341 |
| shadowsocks | 11639 |
| trojan | 9975 |
| hysteria2 | 1282 |
| http | 398 |
| shadowsocksr | 171 |
| socks | 59 |
| anytls | 25 |
| hysteria | 18 |
| tuic | 6 |

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
| 80.74 | vless | 222.2 | 607.9 | 22.63 | 0.0 | 10.0 | 10.85 | 17.26 | mheidari-all | 195.211.98.43 |
| 80.69 | vless | 251.5 | 656.6 | 21.96 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 147.45.60.160 |
| 79.72 | hysteria2 | 264.0 | 703.0 | 21.67 | 0.0 | 10.0 | 11.67 | 17.88 | Au1rxx-base64 | 129.213.91.185 |
| 79.47 | vless | 300.3 | 728.4 | 20.83 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 167.17.69.171 |
| 79.38 | shadowsocks | 255.6 | 624.1 | 21.86 | 0.0 | 10.0 | 13.78 | 17.88 | Au1rxx-base64 | 156.146.38.168 |
| 78.78 | shadowsocks | 287.8 | 731.4 | 21.12 | 0.0 | 10.0 | 13.78 | 17.88 | Au1rxx-base64 | 37.19.198.236 |
| 78.72 | shadowsocks | 290.1 | 740.9 | 21.06 | 0.0 | 10.0 | 13.78 | 17.88 | Au1rxx-base64 | 37.19.198.243 |
| 78.31 | vless | 337.0 | 733.7 | 19.98 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 169.40.42.232 |
| 78.21 | vless | 288.8 | 641.3 | 21.09 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 193.233.202.250 |
| 78.2 | shadowsocks | 256.8 | 630.0 | 21.83 | 0.0 | 10.0 | 13.78 | 17.88 | Au1rxx-base64 | 156.146.38.169 |
| 78.17 | shadowsocks | 314.1 | 821.0 | 20.51 | 0.0 | 10.0 | 13.78 | 17.88 | Au1rxx-base64 | 37.19.198.244 |
| 78.08 | shadowsocks | 260.3 | 636.3 | 21.75 | 0.0 | 10.0 | 13.78 | 17.88 | Au1rxx-base64 | 156.146.38.170 |
| 77.68 | vless | 284.6 | 653.0 | 21.19 | 0.0 | 10.0 | 10.85 | 17.26 | mheidari-all | 216.227.161.95 |
| 77.35 | vless | 358.0 | 906.8 | 19.49 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 169.40.42.89 |
| 77.34 | shadowsocks | 326.4 | 852.0 | 20.22 | 0.0 | 10.0 | 13.78 | 17.88 | Au1rxx-base64 | 37.19.198.160 |
| 77.04 | vless | 372.7 | 931.8 | 19.15 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 169.40.42.235 |
| 76.99 | vless | 375.3 | 831.6 | 19.09 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 169.40.42.90 |
| 76.92 | vless | 296.4 | 661.2 | 20.92 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 213.165.50.45 |
| 76.63 | vless | 347.5 | 750.6 | 19.73 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 169.40.42.16 |
| 76.08 | vless | 255.9 | 643.4 | 21.85 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 69.48.201.136 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.933 | 0.875 | 32 | 7197 | prefer |
| mheidari-all | 0.926 | 0.854 | 89 | 23828 | prefer |
| Au1rxx-base64 | 0.916 | 0.848 | 303 | 1761 | prefer |
| zhangkai | 0.846 | 0.87 | 23 | 144 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7716 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10189 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5754 | observe |
| barry-far-vless | 0.255 | None | 0 | 5978 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4271 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1761 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyConnectionError | - | 13 |
| speed | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 9 |
| speed | TimeoutError | - | 9 |
| geo | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
