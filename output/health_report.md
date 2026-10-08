# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-08 13:18:47 |
| 运行耗时 | 659.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98622 |
| 去重后节点 | 27533 |
| TCP 可达 | 3000 |
| 真实可用 | 439 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27533 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| geo | 1.5 |
| tcp | 46.5 |
| probe | 297.0 |
| real_test | 212.8 |
| generate | 93.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58404 |
| vmess | 15760 |
| shadowsocks | 11945 |
| trojan | 10310 |
| hysteria2 | 1467 |
| http | 421 |
| shadowsocksr | 169 |
| socks | 87 |
| anytls | 34 |
| hysteria | 16 |
| tuic | 9 |

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
| 80.79 | shadowsocks | 249.6 | 605.9 | 22.0 | 0.0 | 10.0 | 13.49 | 19.3 | Au1rxx-base64 | 149.22.95.183 |
| 80.35 | shadowsocks | 247.0 | 483.4 | 22.06 | 0.0 | 10.0 | 13.49 | 19.3 | Au1rxx-base64 | 5.78.51.123 |
| 80.15 | shadowsocks | 255.6 | 491.8 | 21.86 | 0.0 | 10.0 | 13.49 | 19.3 | Au1rxx-base64 | 108.181.118.10 |
| 79.87 | vless | 172.5 | 469.2 | 23.79 | 0.0 | 10.0 | 6.78 | 19.3 | Au1rxx-base64 | 47.251.108.158 |
| 79.16 | vless | 202.8 | 528.3 | 23.08 | 0.0 | 10.0 | 6.78 | 19.3 | Au1rxx-base64 | 107.173.237.146 |
| 78.96 | vless | 211.6 | 589.3 | 22.88 | 0.0 | 10.0 | 6.78 | 19.3 | Au1rxx-base64 | 137.175.82.40 |
| 78.46 | vless | 233.3 | 575.7 | 22.38 | 0.0 | 10.0 | 6.78 | 19.3 | Au1rxx-base64 | 15.204.97.197 |
| 78.41 | vless | 235.5 | 576.3 | 22.33 | 0.0 | 10.0 | 6.78 | 19.3 | Au1rxx-base64 | 15.204.97.216 |
| 78.32 | vless | 195.9 | 505.3 | 23.24 | 0.0 | 10.0 | 6.78 | 19.3 | Au1rxx-base64 | 144.202.126.147 |
| 77.98 | hysteria2 | 348.4 | 757.4 | 19.71 | 0.0 | 10.0 | 14.35 | 19.3 | Au1rxx-base64 | 129.213.91.185 |
| 77.61 | shadowsocks | 214.1 | 528.6 | 22.82 | 0.0 | 10.0 | 13.49 | 19.3 | Au1rxx-base64 | 108.181.0.177 |
| 77.35 | shadowsocks | 273.1 | 281.7 | 21.46 | 4.43 | 9.95 | 13.49 | 19.3 | Au1rxx-base64 | 149.22.87.204 |
| 77.01 | hysteria2 | 330.1 | 378.7 | 20.14 | 0.8 | 9.94 | 14.35 | 19.3 | Au1rxx-base64 | 158.101.148.79 |
| 76.94 | vless | 282.2 | 596.2 | 21.25 | 0.0 | 10.0 | 6.78 | 19.3 | Au1rxx-base64 | 195.123.240.65 |
| 76.7 | shadowsocks | 188.9 | 496.5 | 23.41 | 0.0 | 10.0 | 13.49 | 19.3 | Au1rxx-base64 | 216.105.168.158 |
| 76.07 | shadowsocks | 308.3 | 711.3 | 20.64 | 0.0 | 10.0 | 13.49 | 19.3 | Au1rxx-base64 | 156.146.38.168 |
| 74.88 | shadowsocks | 292.8 | 338.1 | 21.0 | 2.32 | 9.92 | 13.49 | 19.3 | Au1rxx-base64 | 149.22.87.240 |
| 74.82 | shadowsocks | 296.8 | 654.0 | 20.91 | 0.0 | 10.0 | 13.49 | 19.3 | Au1rxx-base64 | 173.244.56.9 |
| 74.63 | vless | 212.2 | 480.2 | 22.87 | 0.0 | 10.0 | 6.78 | 19.3 | Au1rxx-base64 | 104.17.98.5 |
| 73.94 | vless | 212.5 | 531.6 | 22.86 | 0.0 | 10.0 | 6.78 | 19.3 | Au1rxx-base64 | 156.229.162.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.963 | 0.892 | 344 | 1824 | prefer |
| mheidari-all | 0.902 | 0.837 | 43 | 23417 | prefer |
| Surfboard-tg-mixed | 0.747 | 0.669 | 118 | 7320 | prefer |
| zhangkai | 0.527 | 0.524 | 21 | 144 | observe |
| DeltaKronecker-all | 0.298 | 0.273 | 11 | 5197 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5081 | observe |
| Epodonios-all | 0.255 | None | 0 | 7669 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9654 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5776 | observe |
| barry-far-vless | 0.255 | None | 0 | 5968 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4431 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyConnectionError | - | 16 |
| 204 | ProxyError | - | 14 |
| speed | ClientOSError | - | 12 |
| geo | ClientOSError | - | 11 |
| geo | TimeoutError | - | 7 |
| speed | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
