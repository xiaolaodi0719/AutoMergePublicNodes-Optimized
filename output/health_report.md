# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-14 19:05:34 |
| 运行耗时 | 302.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78247 |
| 去重后节点 | 22448 |
| TCP 可达 | 3000 |
| 真实可用 | 852 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22448 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.4 |
| tcp | 35.5 |
| probe | 64.2 |
| real_test | 162.3 |
| generate | 33.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44279 |
| trojan | 11678 |
| vmess | 10401 |
| shadowsocks | 10230 |
| hysteria2 | 1320 |
| http | 168 |
| socks | 77 |
| shadowsocksr | 75 |
| tuic | 10 |
| hysteria | 7 |
| anytls | 2 |

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
| 83.58 | hysteria2 | 296.2 | 732.5 | 20.92 | 0.0 | 10.0 | 14.0 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 82.26 | hysteria2 | 292.9 | 693.1 | 21.0 | 0.0 | 10.0 | 14.0 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 82.04 | shadowsocks | 250.3 | 626.1 | 21.98 | 0.0 | 10.0 | 14.06 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.77 | shadowsocks | 251.5 | 637.3 | 21.96 | 0.0 | 10.0 | 14.06 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 79.32 | vless | 300.7 | 675.6 | 20.82 | 0.0 | 10.0 | 11.12 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 78.89 | vless | 318.2 | 713.2 | 20.41 | 0.0 | 10.0 | 11.12 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 78.73 | http | 288.6 | 587.4 | 21.1 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 78.42 | shadowsocks | 296.1 | 704.9 | 20.92 | 0.0 | 10.0 | 14.06 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 78.35 | vless | 302.2 | 655.8 | 20.78 | 0.0 | 10.0 | 11.12 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 78.26 | http | 286.0 | 565.7 | 21.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 78.15 | http | 309.4 | 640.9 | 20.62 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 78.15 | http | 331.6 | 723.3 | 20.1 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 78.11 | hysteria2 | 328.1 | 560.9 | 20.18 | 0.0 | 10.0 | 14.0 | 20.0 | Au1rxx-base64 | 150.241.102.127 |
| 78.01 | http | 331.6 | 775.6 | 20.1 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 77.96 | http | 298.1 | 565.9 | 20.88 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 77.95 | http | 330.6 | 717.0 | 20.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 77.9 | http | 309.6 | 640.7 | 20.61 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 77.88 | shadowsocks | 276.1 | 551.4 | 21.39 | 0.0 | 10.0 | 14.06 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 77.86 | http | 404.4 | 970.0 | 18.42 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 77.84 | http | 341.7 | 740.3 | 19.87 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Au1rxx-base64 | 0.993 | 0.926 | 676 | 1715 | prefer |
| mheidari-all | 0.827 | 0.753 | 81 | 15859 | prefer |
| Surfboard-tg-mixed | 0.695 | 0.625 | 24 | 5725 | observe |
| DeltaKronecker-all | 0.628 | 0.55 | 40 | 5969 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 160 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5157 | observe |
| Epodonios-all | 0.255 | None | 0 | 6388 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7685 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4488 | observe |
| barry-far-vless | 0.255 | None | 0 | 4814 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3992 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.246 | None | 0 | 1768 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 32 |
| cn-block | TimeoutError | - | 19 |
| geo | TimeoutError | - | 13 |
| speed | TimeoutError | - | 9 |
| geo | ClientOSError | - | 7 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 5 |
| speed | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
