# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-28 02:58:34 |
| 运行耗时 | 345.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 84821 |
| 去重后节点 | 23210 |
| TCP 可达 | 3000 |
| 真实可用 | 1018 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23210 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.3 |
| tcp | 32.4 |
| probe | 68.6 |
| real_test | 219.9 |
| generate | 18.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47922 |
| trojan | 15675 |
| vmess | 10413 |
| shadowsocks | 10004 |
| hysteria2 | 549 |
| shadowsocksr | 96 |
| socks | 68 |
| http | 63 |
| hysteria | 15 |
| anytls | 10 |
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
| 80.0 | shadowsocks | 230.4 | 630.2 | 22.44 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 173.244.56.6 |
| 78.45 | trojan | 296.9 | 682.0 | 20.91 | 0.0 | 10.0 | 13.47 | 19.52 | Au1rxx-base64 | 64.94.95.117 |
| 78.37 | shadowsocks | 279.6 | 718.5 | 21.31 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 108.181.0.177 |
| 78.02 | hysteria2 | 314.6 | 694.1 | 20.49 | 0.0 | 10.0 | 12.69 | 19.52 | Au1rxx-base64 | 159.223.157.129 |
| 77.73 | trojan | 297.1 | 628.3 | 20.9 | 0.0 | 10.0 | 13.47 | 19.52 | Au1rxx-base64 | 163.245.196.68 |
| 77.68 | trojan | 334.1 | 784.1 | 20.04 | 0.0 | 10.0 | 13.47 | 19.52 | Au1rxx-base64 | 64.94.95.118 |
| 77.67 | shadowsocks | 201.7 | 525.8 | 23.11 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 216.105.168.18 |
| 76.82 | shadowsocks | 189.0 | 507.1 | 23.4 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 173.244.56.9 |
| 76.64 | trojan | 364.4 | 871.6 | 19.34 | 0.0 | 10.0 | 13.47 | 19.52 | Au1rxx-base64 | 64.94.95.114 |
| 76.48 | shadowsocks | 361.1 | 763.9 | 19.42 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 108.181.118.10 |
| 76.28 | shadowsocks | 327.2 | 838.0 | 20.2 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 156.146.38.167 |
| 75.89 | shadowsocks | 284.5 | 622.2 | 21.19 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 149.22.95.183 |
| 75.77 | trojan | 396.4 | 971.4 | 18.6 | 0.0 | 10.0 | 13.47 | 19.52 | Au1rxx-base64 | 64.94.95.115 |
| 74.96 | shadowsocks | 307.9 | 780.7 | 20.65 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 156.146.38.169 |
| 74.48 | shadowsocks | 252.9 | 617.2 | 21.92 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 156.146.38.168 |
| 72.74 | shadowsocks | 351.4 | 727.2 | 19.64 | 0.0 | 10.0 | 12.04 | 19.9 | mheidari-all | 37.19.198.243 |
| 72.72 | vless | 241.5 | 500.6 | 22.19 | 0.0 | 10.0 | 6.63 | 19.9 | mheidari-all | 162.159.49.145 |
| 72.23 | shadowsocks | 345.2 | 714.5 | 19.79 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 37.19.198.244 |
| 72.21 | shadowsocks | 353.9 | 732.6 | 19.59 | 0.0 | 10.0 | 12.04 | 19.52 | Au1rxx-base64 | 37.19.198.160 |
| 72.02 | vless | 250.9 | 516.1 | 21.97 | 0.0 | 10.0 | 6.63 | 19.52 | Au1rxx-base64 | 172.64.152.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.96 | 477 | 1387 | prefer |
| zhangkai | 0.987 | 1.0 | 59 | 74 | prefer |
| Surfboard-tg-mixed | 0.782 | 0.709 | 55 | 5636 | prefer |
| mheidari-all | 0.64 | 0.56 | 650 | 18500 | observe |
| DeltaKronecker-all | 0.635 | 0.556 | 171 | 5643 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3959 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4831 | observe |
| Epodonios-all | 0.255 | None | 0 | 6592 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6500 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5025 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4997 | observe |
| Au1rxx-clash | 0.23 | None | 0 | 1387 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 162 |
| speed | ClientOSError | - | 109 |
| speed | TimeoutError | - | 48 |
| cn-block | TimeoutError | - | 37 |
| geo | ClientOSError | - | 30 |
| 204 | ProxyError | - | 7 |
| 204 | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
