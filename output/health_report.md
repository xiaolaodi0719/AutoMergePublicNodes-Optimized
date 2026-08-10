# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-10 13:23:04 |
| 运行耗时 | 242.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86587 |
| 去重后节点 | 24769 |
| TCP 可达 | 3000 |
| 真实可用 | 510 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24769 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.0 |
| tcp | 36.8 |
| probe | 50.7 |
| real_test | 110.2 |
| generate | 37.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51750 |
| vmess | 13293 |
| trojan | 10177 |
| shadowsocks | 9770 |
| hysteria2 | 1370 |
| shadowsocksr | 74 |
| socks | 65 |
| http | 40 |
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
| 81.5 | hysteria2 | 266.6 | 666.7 | 21.61 | 0.0 | 10.0 | 13.27 | 17.72 | Au1rxx-base64 | 159.223.157.129 |
| 81.48 | hysteria2 | 271.7 | 677.8 | 21.49 | 0.0 | 10.0 | 13.27 | 17.72 | Au1rxx-base64 | 138.124.68.188 |
| 79.32 | shadowsocks | 260.7 | 640.1 | 21.74 | 0.0 | 10.0 | 13.86 | 17.72 | Au1rxx-base64 | 37.19.198.244 |
| 78.94 | shadowsocks | 277.3 | 695.6 | 21.36 | 0.0 | 10.0 | 13.86 | 17.72 | Au1rxx-base64 | 37.19.198.236 |
| 78.68 | shadowsocks | 288.4 | 739.1 | 21.1 | 0.0 | 10.0 | 13.86 | 17.72 | Au1rxx-base64 | 37.19.198.243 |
| 77.84 | hysteria2 | 281.0 | 713.2 | 21.27 | 0.0 | 6.58 | 13.27 | 17.72 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 77.11 | trojan | 309.2 | 758.6 | 20.62 | 0.0 | 10.0 | 12.78 | 17.72 | Au1rxx-base64 | 64.94.95.114 |
| 75.78 | trojan | 376.7 | 947.9 | 19.06 | 0.0 | 10.0 | 12.78 | 17.72 | Au1rxx-base64 | 64.94.95.118 |
| 75.63 | trojan | 349.0 | 860.6 | 19.7 | 0.0 | 10.0 | 12.78 | 17.72 | Au1rxx-base64 | 64.94.95.115 |
| 74.83 | trojan | 364.2 | 922.0 | 19.35 | 0.0 | 10.0 | 12.78 | 17.72 | Au1rxx-base64 | 64.94.95.117 |
| 74.63 | vless | 251.9 | 565.4 | 21.95 | 0.0 | 9.46 | 7.92 | 17.72 | Au1rxx-base64 | 216.227.161.95 |
| 74.62 | http | 343.2 | 615.5 | 19.83 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 74.47 | http | 344.7 | 629.0 | 19.8 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 74.4 | http | 346.0 | 629.0 | 19.77 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 74.1 | http | 344.1 | 621.9 | 19.81 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 74.06 | shadowsocks | 304.3 | 632.9 | 20.73 | 0.0 | 10.0 | 13.86 | 17.72 | Au1rxx-base64 | 149.22.95.183 |
| 73.88 | shadowsocks | 334.1 | 713.0 | 20.04 | 0.0 | 10.0 | 13.86 | 17.72 | Au1rxx-base64 | 108.181.57.93 |
| 73.62 | shadowsocks | 301.3 | 599.6 | 20.8 | 0.0 | 10.0 | 13.86 | 17.72 | Au1rxx-base64 | 173.244.56.6 |
| 73.59 | vless | 301.7 | 695.2 | 20.79 | 0.0 | 10.0 | 7.92 | 17.72 | Au1rxx-base64 | 169.40.42.15 |
| 73.44 | shadowsocks | 274.2 | 684.3 | 21.43 | 0.0 | 9.43 | 13.86 | 17.72 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.991 | 0.926 | 435 | 1668 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.742 | 0.667 | 69 | 6388 | prefer |
| DeltaKronecker-all | 0.559 | 0.478 | 69 | 5881 | observe |
| mheidari-all | 0.418 | 0.5 | 10 | 20526 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 122 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7165 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7747 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5219 | observe |
| barry-far-vless | 0.255 | None | 0 | 5695 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5191 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 17 |
| speed | TimeoutError | - | 15 |
| geo | ClientOSError | - | 14 |
| speed | ClientOSError | - | 8 |
| geo | TimeoutError | - | 8 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
