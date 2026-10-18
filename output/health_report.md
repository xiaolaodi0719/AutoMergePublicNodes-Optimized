# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 04:08:27 |
| 运行耗时 | 850.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99131 |
| 去重后节点 | 27861 |
| TCP 可达 | 3000 |
| 真实可用 | 524 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27861 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.5 |
| tcp | 47.6 |
| probe | 306.0 |
| real_test | 403.5 |
| generate | 85.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58417 |
| vmess | 16741 |
| shadowsocks | 11813 |
| trojan | 9837 |
| hysteria2 | 1283 |
| http | 757 |
| shadowsocksr | 171 |
| socks | 65 |
| anytls | 24 |
| hysteria | 17 |
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
| 82.0 | vless | 194.4 | 507.2 | 23.28 | 0.0 | 10.0 | 10.98 | 17.74 | Au1rxx-base64 | 45.32.69.110 |
| 81.83 | hysteria2 | 228.5 | 227.7 | 22.49 | 6.46 | 9.91 | 12.0 | 17.74 | Au1rxx-base64 | 45.32.10.7 |
| 81.65 | vless | 209.5 | 520.2 | 22.93 | 0.0 | 10.0 | 10.98 | 17.74 | Au1rxx-base64 | 154.9.241.170 |
| 81.6 | vless | 211.7 | 535.2 | 22.88 | 0.0 | 10.0 | 10.98 | 17.74 | Au1rxx-base64 | 195.123.240.65 |
| 80.92 | vless | 197.6 | 502.6 | 23.2 | 0.0 | 10.0 | 10.98 | 17.74 | Au1rxx-base64 | 176.122.183.26 |
| 80.9 | vless | 198.8 | 508.1 | 23.18 | 0.0 | 10.0 | 10.98 | 17.74 | Au1rxx-base64 | 45.63.53.81 |
| 80.0 | shadowsocks | 213.5 | 525.4 | 22.83 | 0.0 | 10.0 | 13.43 | 17.74 | Au1rxx-base64 | 173.244.56.6 |
| 79.98 | shadowsocks | 214.7 | 531.8 | 22.81 | 0.0 | 10.0 | 13.43 | 17.74 | Au1rxx-base64 | 173.244.56.9 |
| 79.34 | vless | 293.8 | 702.3 | 20.98 | 0.0 | 10.0 | 10.98 | 17.74 | Au1rxx-base64 | 147.45.60.160 |
| 79.32 | hysteria2 | 229.5 | 234.5 | 22.46 | 6.21 | 7.73 | 12.0 | 17.74 | Au1rxx-base64 | vp3.yysyy.online |
| 79.21 | vless | 314.8 | 672.3 | 20.49 | 0.0 | 10.0 | 10.98 | 17.74 | Au1rxx-base64 | 95.111.212.241 |
| 78.94 | hysteria2 | 250.4 | 585.6 | 21.98 | 0.0 | 10.0 | 12.0 | 17.74 | Au1rxx-base64 | 66.94.121.46 |
| 78.8 | shadowsocks | 259.6 | 629.8 | 21.77 | 0.0 | 10.0 | 13.43 | 17.74 | Au1rxx-base64 | 156.146.38.168 |
| 78.63 | vless | 210.3 | 499.0 | 22.91 | 0.0 | 10.0 | 10.98 | 17.74 | Au1rxx-base64 | 47.77.196.79 |
| 78.42 | vless | 300.1 | 721.3 | 20.83 | 0.0 | 10.0 | 10.98 | 17.74 | Au1rxx-base64 | 23.95.222.127 |
| 78.16 | http | 197.4 | 512.8 | 23.21 | 0.0 | 10.0 | 11.57 | 16.38 | ermaozi | 138.199.35.216 |
| 78.14 | http | 198.2 | 516.2 | 23.19 | 0.0 | 10.0 | 11.57 | 16.38 | ermaozi | 138.199.35.203 |
| 78.12 | http | 199.2 | 517.6 | 23.17 | 0.0 | 10.0 | 11.57 | 16.38 | ermaozi | 138.199.35.217 |
| 78.06 | http | 201.5 | 519.0 | 23.11 | 0.0 | 10.0 | 11.57 | 16.38 | ermaozi | 138.199.35.199 |
| 78.04 | http | 202.7 | 519.9 | 23.09 | 0.0 | 10.0 | 11.57 | 16.38 | ermaozi | 138.199.35.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.913 | 0.842 | 482 | 1798 | prefer |
| ermaozi | 0.567 | 0.539 | 102 | 710 | observe |
| Surfboard-tg-mixed | 0.48 | 1.0 | 4 | 7181 | observe |
| mheidari-all | 0.406 | 0.324 | 176 | 23946 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Epodonios-all | 0.255 | None | 0 | 7667 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9901 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5616 | observe |
| barry-far-vless | 0.255 | None | 0 | 5884 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| DeltaKronecker-all | 0.249 | 0.2 | 10 | 4999 | downweight |
| Au1rxx-clash | 0.247 | None | 0 | 1798 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 88 |
| 204 | ProxyError | - | 55 |
| geo | ClientOSError | - | 29 |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 17 |
| speed | ClientOSError | - | 15 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
