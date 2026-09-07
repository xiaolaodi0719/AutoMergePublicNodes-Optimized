# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 03:58:59 |
| 运行耗时 | 329.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94333 |
| 去重后节点 | 24798 |
| TCP 可达 | 3000 |
| 真实可用 | 579 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24798 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.4 |
| tcp | 42.1 |
| probe | 89.7 |
| real_test | 145.9 |
| generate | 43.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58831 |
| vmess | 12749 |
| shadowsocks | 11273 |
| trojan | 9045 |
| hysteria2 | 2051 |
| http | 137 |
| shadowsocksr | 123 |
| socks | 60 |
| anytls | 29 |
| hysteria | 19 |
| tuic | 16 |

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
| 79.92 | shadowsocks | 264.7 | 639.1 | 21.65 | 0.0 | 10.0 | 12.77 | 19.5 | Au1rxx-base64 | 156.146.38.169 |
| 78.24 | trojan | 249.6 | 581.6 | 22.0 | 0.0 | 10.0 | 11.82 | 19.5 | Au1rxx-base64 | 64.94.95.117 |
| 77.6 | trojan | 269.3 | 690.2 | 21.54 | 0.0 | 10.0 | 11.82 | 19.5 | Au1rxx-base64 | 64.94.95.115 |
| 77.0 | vless | 290.7 | 574.6 | 21.05 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 172.233.139.46 |
| 76.97 | vless | 294.8 | 706.0 | 20.95 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 130.94.115.231 |
| 76.67 | vless | 405.4 | 1003.2 | 18.39 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 185.95.231.156 |
| 76.53 | vless | 312.9 | 651.3 | 20.54 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 172.235.38.85 |
| 76.09 | vless | 300.7 | 523.2 | 20.82 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 216.167.94.71 |
| 76.01 | shadowsocks | 268.1 | 622.8 | 21.57 | 0.0 | 10.0 | 12.77 | 15.86 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.86 | vless | 350.2 | 648.7 | 19.67 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 38.246.229.58 |
| 75.81 | vless | 351.7 | 801.5 | 19.64 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 169.40.42.104 |
| 75.69 | vless | 326.4 | 741.3 | 20.22 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 137.184.218.169 |
| 75.56 | vless | 292.0 | 576.0 | 21.02 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 172.235.43.210 |
| 75.4 | http | 294.8 | 593.3 | 20.95 | 0.0 | 10.0 | 14.44 | 19.32 | zhangkai | 138.199.35.198 |
| 75.24 | vless | 408.4 | 800.1 | 18.33 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 169.40.42.231 |
| 74.91 | vless | 368.1 | 864.2 | 19.26 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 169.40.42.179 |
| 74.75 | vless | 442.3 | 1037.2 | 17.54 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 169.40.42.15 |
| 74.69 | vless | 366.6 | 797.3 | 19.29 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 66.70.179.198 |
| 74.61 | hysteria2 | 250.8 | 549.3 | 21.97 | 0.0 | 9.79 | 13.04 | 19.5 | Au1rxx-base64 | 66.94.121.46 |
| 74.4 | vless | 392.3 | 514.9 | 18.7 | 0.0 | 10.0 | 10.85 | 19.5 | Au1rxx-base64 | 38.150.33.232 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.94 | 331 | 1835 | prefer |
| zhangkai | 0.926 | 0.957 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.802 | 0.724 | 214 | 7284 | prefer |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 5750 | observe |
| mheidari-all | 0.344 | 0.262 | 324 | 21249 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4791 | observe |
| Epodonios-all | 0.255 | None | 0 | 7766 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8622 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6082 | observe |
| barry-far-vless | 0.255 | None | 0 | 6301 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1835 | observe |
| DeltaKronecker-all | 0.231 | 0.143 | 14 | 5856 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 96 |
| cn-block | TimeoutError | - | 69 |
| geo | ClientOSError | - | 49 |
| speed | TimeoutError | - | 36 |
| cn-block | ClientOSError | - | 29 |
| 204 | TimeoutError | - | 17 |
| speed | ClientOSError | - | 15 |
| 204 | ProxyConnectionError | - | 13 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
