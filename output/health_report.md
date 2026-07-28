# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-28 08:48:29 |
| 运行耗时 | 326.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86095 |
| 去重后节点 | 23310 |
| TCP 可达 | 3000 |
| 真实可用 | 731 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23310 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.3 |
| tcp | 32.3 |
| probe | 63.1 |
| real_test | 180.5 |
| generate | 42.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48732 |
| trojan | 16054 |
| vmess | 10314 |
| shadowsocks | 10165 |
| hysteria2 | 560 |
| shadowsocksr | 95 |
| http | 73 |
| socks | 72 |
| hysteria | 15 |
| anytls | 10 |
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
| 83.18 | shadowsocks | 211.1 | 567.9 | 22.89 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 80.02 | shadowsocks | 257.8 | 269.3 | 21.81 | 4.9 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 149.22.87.240 |
| 79.15 | shadowsocks | 252.0 | 557.8 | 21.94 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 78.99 | shadowsocks | 255.4 | 565.9 | 21.86 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 78.71 | shadowsocks | 281.5 | 604.7 | 21.26 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 78.32 | shadowsocks | 291.5 | 638.7 | 21.03 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 77.95 | hysteria2 | 340.8 | 706.8 | 19.89 | 0.0 | 10.0 | 13.12 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 77.03 | shadowsocks | 281.0 | 335.3 | 21.27 | 2.43 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 149.22.87.241 |
| 76.76 | shadowsocks | 316.7 | 661.4 | 20.45 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 76.23 | shadowsocks | 325.2 | 691.5 | 20.25 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 74.34 | shadowsocks | 354.6 | 718.9 | 19.57 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 74.18 | shadowsocks | 363.2 | 742.1 | 19.37 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 73.99 | shadowsocks | 372.2 | 771.5 | 19.16 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 73.43 | trojan | 410.9 | 345.1 | 18.27 | 2.06 | 9.49 | 14.22 | 20.0 | Au1rxx-base64 | 119.246.1.143 |
| 73.15 | shadowsocks | 343.0 | 525.2 | 19.84 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 149.22.87.204 |
| 73.02 | shadowsocks | 414.3 | 898.0 | 18.19 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 72.67 | shadowsocks | 323.4 | 691.3 | 20.29 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 72.67 | shadowsocks | 409.5 | 881.6 | 18.3 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 185.196.61.82 |
| 72.66 | shadowsocks | 244.3 | 501.1 | 22.12 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 216.105.168.18 |
| 72.55 | shadowsocks | 390.4 | 758.9 | 18.74 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 108.181.57.93 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.989 | 0.937 | 412 | 1345 | prefer |
| zhangkai | 0.989 | 1.0 | 69 | 81 | prefer |
| Surfboard-tg-mixed | 0.711 | 0.633 | 166 | 5743 | prefer |
| mheidari-all | 0.707 | 0.629 | 140 | 18776 | prefer |
| DeltaKronecker-all | 0.659 | 0.58 | 138 | 5965 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4972 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| xiaoji235-airport-v2ray-all | 0.259 | 0.333 | 3 | 3959 | observe |
| Epodonios-all | 0.255 | None | 0 | 6749 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6579 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4586 | observe |
| barry-far-vless | 0.255 | None | 0 | 5112 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4991 | observe |
| Au1rxx-clash | 0.229 | None | 0 | 1345 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 62 |
| cn-block | TimeoutError | - | 32 |
| geo | ClientOSError | - | 29 |
| 204 | TimeoutError | - | 21 |
| speed | ClientOSError | - | 17 |
| speed | TimeoutError | - | 16 |
| 204 | ProxyError | - | 14 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
