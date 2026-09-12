# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 04:18:31 |
| 运行耗时 | 1147.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83274 |
| 去重后节点 | 23407 |
| TCP 可达 | 3000 |
| 真实可用 | 600 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23407 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 40.9 |
| probe | 351.9 |
| real_test | 590.6 |
| generate | 156.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50324 |
| vmess | 12500 |
| shadowsocks | 9778 |
| trojan | 8120 |
| hysteria2 | 1692 |
| http | 661 |
| shadowsocksr | 120 |
| socks | 54 |
| tuic | 12 |
| hysteria | 11 |
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
| 83.96 | hysteria2 | 185.6 | 504.4 | 23.48 | 0.0 | 10.0 | 12.86 | 18.62 | Au1rxx-base64 | 66.94.121.46 |
| 79.37 | vless | 304.4 | 832.6 | 20.73 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 15.204.97.216 |
| 78.18 | vless | 260.0 | 539.2 | 21.76 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 172.233.139.46 |
| 77.94 | vless | 264.6 | 534.7 | 21.65 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 172.235.43.210 |
| 77.84 | shadowsocks | 215.7 | 574.5 | 22.78 | 0.0 | 10.0 | 13.46 | 15.6 | mheidari-all | 149.22.95.183 |
| 77.7 | vless | 258.9 | 538.3 | 21.78 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 172.235.38.85 |
| 75.71 | vless | 304.7 | 593.9 | 20.72 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 31.58.50.200 |
| 75.54 | shadowsocks | 241.0 | 505.8 | 22.2 | 0.0 | 10.0 | 13.46 | 15.6 | mheidari-all | 108.181.0.177 |
| 75.26 | vless | 481.9 | 1349.6 | 16.62 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 51.81.203.63 |
| 75.02 | vless | 211.5 | 482.3 | 22.88 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 172.64.53.55 |
| 74.99 | vless | 291.9 | 641.3 | 21.02 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 38.209.125.45 |
| 74.81 | vless | 310.9 | 324.7 | 20.58 | 2.83 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 154.31.114.248 |
| 74.74 | shadowsocks | 193.3 | 516.6 | 23.3 | 0.0 | 10.0 | 13.46 | 13.48 | Surfboard-tg-mixed | 5.78.51.123 |
| 74.64 | vless | 292.8 | 796.0 | 21.0 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 15.204.97.214 |
| 74.39 | vless | 318.6 | 329.5 | 20.4 | 2.64 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 13.231.19.51 |
| 74.35 | shadowsocks | 341.1 | 787.0 | 19.88 | 0.0 | 10.0 | 13.46 | 18.62 | Au1rxx-base64 | 173.244.56.6 |
| 74.32 | vless | 306.5 | 843.5 | 20.68 | 0.0 | 10.0 | 10.02 | 18.62 | Au1rxx-base64 | 15.204.97.195 |
| 73.79 | shadowsocks | 252.9 | 516.5 | 21.92 | 0.0 | 10.0 | 13.46 | 15.6 | mheidari-all | 108.181.118.10 |
| 73.75 | shadowsocks | 322.5 | 689.6 | 20.31 | 0.0 | 10.0 | 13.46 | 18.62 | Au1rxx-base64 | 156.146.38.170 |
| 73.71 | shadowsocks | 304.4 | 354.2 | 20.73 | 1.72 | 10.0 | 13.46 | 18.62 | Au1rxx-base64 | 84.247.155.196 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.95 | 0.885 | 321 | 1681 | prefer |
| ermaozi | 0.776 | 0.778 | 27 | 434 | prefer |
| Surfboard-tg-mixed | 0.738 | 0.661 | 118 | 7263 | prefer |
| mheidari-all | 0.584 | 0.504 | 115 | 15597 | observe |
| DeltaKronecker-all | 0.391 | 0.31 | 497 | 6070 | observe |
| ermaozi-get_subscribe | 0.311 | 0.6 | 5 | 459 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 194 | observe |
| Epodonios-all | 0.255 | None | 0 | 7719 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8500 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5889 | observe |
| barry-far-vless | 0.255 | None | 0 | 6106 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.251 | 0.333 | 3 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1681 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 220 |
| geo | ClientOSError | - | 92 |
| speed | ClientOSError | - | 48 |
| speed | TimeoutError | - | 47 |
| 204 | ProxyError | - | 24 |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 20 |
| cn-block | ClientOSError | - | 12 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
