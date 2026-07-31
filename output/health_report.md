# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-31 19:46:48 |
| 运行耗时 | 303.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78935 |
| 去重后节点 | 22858 |
| TCP 可达 | 3000 |
| 真实可用 | 555 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22858 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.3 |
| tcp | 34.1 |
| probe | 62.1 |
| real_test | 170.1 |
| generate | 31.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47455 |
| vmess | 11920 |
| shadowsocks | 10228 |
| trojan | 8485 |
| hysteria2 | 572 |
| http | 87 |
| shadowsocksr | 77 |
| socks | 57 |
| anytls | 26 |
| hysteria | 14 |
| tuic | 14 |

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
| 79.21 | shadowsocks | 239.3 | 612.9 | 22.24 | 0.0 | 10.0 | 13.19 | 17.78 | Au1rxx-base64 | 156.146.38.169 |
| 79.05 | shadowsocks | 246.3 | 606.5 | 22.08 | 0.0 | 10.0 | 13.19 | 17.78 | Au1rxx-base64 | 156.146.38.170 |
| 79.0 | shadowsocks | 248.2 | 634.2 | 22.03 | 0.0 | 10.0 | 13.19 | 17.78 | Au1rxx-base64 | 156.146.38.168 |
| 78.27 | vless | 253.6 | 613.7 | 21.91 | 0.0 | 10.0 | 10.27 | 17.78 | Au1rxx-base64 | 216.227.161.95 |
| 78.07 | http | 322.9 | 725.3 | 20.3 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.8 |
| 77.46 | http | 328.1 | 707.3 | 20.18 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.5 |
| 77.38 | http | 342.1 | 762.5 | 19.86 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.7 |
| 77.36 | hysteria2 | 293.6 | 719.7 | 20.98 | 0.0 | 10.0 | 11.67 | 17.78 | Au1rxx-base64 | 138.124.68.188 |
| 77.32 | hysteria2 | 291.6 | 713.4 | 21.03 | 0.0 | 8.75 | 11.67 | 17.78 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 76.71 | shadowsocks | 304.1 | 801.8 | 20.74 | 0.0 | 10.0 | 13.19 | 17.78 | Au1rxx-base64 | 156.146.38.167 |
| 76.33 | hysteria2 | 290.0 | 682.0 | 21.06 | 0.0 | 10.0 | 11.67 | 17.78 | Au1rxx-base64 | 159.223.157.129 |
| 76.28 | shadowsocks | 315.2 | 742.1 | 20.48 | 0.0 | 10.0 | 13.19 | 17.78 | Au1rxx-base64 | 37.19.198.244 |
| 75.88 | shadowsocks | 309.0 | 742.4 | 20.62 | 0.0 | 10.0 | 13.19 | 17.78 | Au1rxx-base64 | 37.19.198.160 |
| 75.67 | shadowsocks | 304.4 | 715.4 | 20.73 | 0.0 | 10.0 | 13.19 | 17.78 | Au1rxx-base64 | 37.19.198.236 |
| 75.52 | shadowsocks | 303.8 | 725.6 | 20.75 | 0.0 | 10.0 | 13.19 | 17.78 | Au1rxx-base64 | 37.19.198.243 |
| 75.23 | vless | 378.0 | 966.4 | 19.03 | 0.0 | 10.0 | 10.27 | 17.78 | Au1rxx-base64 | 45.138.100.226 |
| 75.13 | trojan | 312.1 | 772.7 | 20.55 | 0.0 | 10.0 | 10.96 | 17.78 | Au1rxx-base64 | 163.245.196.68 |
| 73.68 | trojan | 328.7 | 742.8 | 20.17 | 0.0 | 10.0 | 10.96 | 17.78 | Au1rxx-base64 | 153.75.250.171 |
| 73.54 | shadowsocks | 312.6 | 660.6 | 20.54 | 0.0 | 10.0 | 13.19 | 17.78 | Au1rxx-base64 | 149.22.95.183 |
| 73.32 | http | 511.3 | 1253.1 | 15.94 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.199 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 80 | 110 | prefer |
| Au1rxx-base64 | 0.756 | 0.689 | 499 | 1685 | prefer |
| Surfboard-tg-mixed | 0.734 | 0.667 | 24 | 5433 | prefer |
| DeltaKronecker-all | 0.556 | 0.476 | 231 | 5144 | observe |
| mheidari-all | 0.438 | 1.0 | 3 | 16449 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 51 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5507 | observe |
| Epodonios-all | 0.255 | None | 0 | 6115 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3975 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6602 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4317 | observe |
| barry-far-vless | 0.255 | None | 0 | 4677 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5081 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 104 |
| 204 | ProxyError | - | 36 |
| 204 | TimeoutError | - | 34 |
| geo | ClientOSError | - | 30 |
| cn-block | TimeoutError | - | 28 |
| speed | TimeoutError | - | 19 |
| speed | ClientOSError | - | 13 |
| cn-block | ProxyError | - | 7 |
| 204 | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
