# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-25 07:00:45 |
| 运行耗时 | 282.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 78337 |
| 去重后节点 | 22287 |
| TCP 可达 | 3000 |
| 真实可用 | 678 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22287 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 35.6 |
| probe | 63.8 |
| real_test | 149.7 |
| generate | 26.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49153 |
| shadowsocks | 10807 |
| vmess | 10380 |
| trojan | 6618 |
| hysteria2 | 1003 |
| http | 164 |
| shadowsocksr | 132 |
| socks | 70 |
| hysteria | 7 |
| tuic | 3 |

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
| 83.6 | shadowsocks | 180.9 | 478.7 | 23.59 | 0.0 | 10.0 | 14.27 | 19.74 | Au1rxx-base64 | 154.12.240.141 |
| 82.72 | shadowsocks | 208.3 | 553.6 | 22.96 | 0.0 | 10.0 | 14.27 | 19.74 | Au1rxx-base64 | 94.72.127.58 |
| 81.95 | shadowsocks | 208.9 | 547.6 | 22.94 | 0.0 | 10.0 | 14.27 | 19.74 | Au1rxx-base64 | 154.53.60.212 |
| 80.21 | vless | 206.1 | 547.1 | 23.01 | 0.0 | 10.0 | 7.46 | 19.74 | Au1rxx-base64 | 15.204.97.197 |
| 79.26 | shadowsocks | 368.4 | 892.9 | 19.25 | 0.0 | 10.0 | 14.27 | 19.74 | Au1rxx-base64 | 154.12.242.150 |
| 78.97 | http | 267.4 | 569.3 | 21.59 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.216 |
| 78.77 | http | 265.6 | 559.1 | 21.63 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.198 |
| 78.76 | trojan | 320.1 | 672.6 | 20.37 | 0.0 | 9.39 | 11.76 | 19.74 | Au1rxx-base64 | 35.92.245.6 |
| 78.62 | shadowsocks | 197.8 | 507.8 | 23.2 | 0.0 | 9.25 | 14.27 | 19.74 | Au1rxx-base64 | 94.72.127.55 |
| 78.45 | trojan | 359.6 | 953.2 | 19.45 | 0.0 | 10.0 | 11.76 | 19.74 | Au1rxx-base64 | 35.91.251.124 |
| 78.22 | shadowsocks | 257.5 | 264.5 | 21.82 | 5.08 | 10.0 | 14.27 | 18.0 | Surfboard-tg-mixed | 149.22.87.204 |
| 77.3 | shadowsocks | 294.3 | 630.0 | 20.96 | 0.0 | 9.28 | 14.27 | 19.74 | Au1rxx-base64 | 108.181.0.177 |
| 76.93 | shadowsocks | 221.1 | 549.7 | 22.66 | 0.0 | 9.26 | 14.27 | 19.74 | Au1rxx-base64 | 149.22.95.183 |
| 76.31 | shadowsocks | 313.9 | 672.9 | 20.51 | 0.0 | 10.0 | 14.27 | 19.74 | Au1rxx-base64 | 156.146.38.167 |
| 76.12 | shadowsocks | 277.2 | 665.8 | 21.36 | 0.0 | 10.0 | 14.27 | 19.74 | Au1rxx-base64 | 154.53.63.33 |
| 75.2 | trojan | 270.0 | 596.9 | 21.53 | 0.0 | 9.34 | 11.76 | 19.74 | Au1rxx-base64 | 107.150.105.84 |
| 74.76 | shadowsocks | 258.1 | 529.7 | 21.8 | 0.0 | 10.0 | 14.27 | 19.74 | Au1rxx-base64 | 129.146.76.178 |
| 74.7 | vless | 260.4 | 549.6 | 21.75 | 0.0 | 9.3 | 7.46 | 19.74 | Au1rxx-base64 | 23.172.40.60 |
| 74.57 | vless | 306.9 | 292.9 | 20.67 | 4.02 | 10.0 | 7.46 | 19.74 | Au1rxx-base64 | 31.76.91.138 |
| 74.27 | shadowsocks | 342.1 | 701.3 | 19.86 | 0.0 | 9.34 | 14.27 | 19.74 | Au1rxx-base64 | 155.138.136.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Au1rxx-base64 | 0.943 | 0.877 | 503 | 1700 | prefer |
| mheidari-all | 0.839 | 0.769 | 52 | 14480 | prefer |
| Surfboard-tg-mixed | 0.788 | 0.711 | 152 | 6465 | prefer |
| DeltaKronecker-all | 0.635 | 0.556 | 117 | 6340 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 6925 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3989 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6957 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5306 | observe |
| barry-far-vless | 0.255 | None | 0 | 5525 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4119 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1705 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 52 |
| 204 | TimeoutError | - | 26 |
| speed | TimeoutError | - | 20 |
| speed | ClientOSError | - | 19 |
| geo | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 10 |
| 204 | ProxyError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
