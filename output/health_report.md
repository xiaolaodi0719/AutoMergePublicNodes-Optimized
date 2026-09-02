# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-02 16:24:04 |
| 运行耗时 | 290.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82564 |
| 去重后节点 | 23518 |
| TCP 可达 | 3000 |
| 真实可用 | 573 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23518 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.5 |
| tcp | 38.1 |
| probe | 87.7 |
| real_test | 120.7 |
| generate | 36.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51773 |
| vmess | 11154 |
| shadowsocks | 9978 |
| trojan | 7701 |
| hysteria2 | 1587 |
| http | 143 |
| shadowsocksr | 130 |
| socks | 80 |
| tuic | 11 |
| hysteria | 7 |

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
| 84.43 | vless | 172.1 | 472.8 | 23.79 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 74.207.245.124 |
| 84.33 | vless | 176.7 | 488.9 | 23.69 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 50.116.9.184 |
| 84.32 | vless | 177.1 | 491.5 | 23.68 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 45.33.107.237 |
| 84.28 | vless | 178.7 | 489.3 | 23.64 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 173.230.155.55 |
| 84.22 | vless | 181.2 | 493.2 | 23.58 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 45.33.62.166 |
| 84.18 | vless | 183.1 | 502.3 | 23.54 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 192.155.87.188 |
| 84.09 | vless | 187.2 | 490.3 | 23.45 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 173.255.242.56 |
| 84.08 | vless | 187.3 | 525.5 | 23.44 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 45.79.103.108 |
| 84.01 | vless | 190.6 | 505.2 | 23.37 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 45.33.107.60 |
| 83.86 | vless | 196.9 | 504.5 | 23.22 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 172.236.252.35 |
| 83.77 | vless | 201.0 | 519.4 | 23.13 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 172.233.156.118 |
| 83.7 | http | 202.9 | 521.4 | 23.08 | 0.0 | 10.0 | 14.38 | 19.24 | zhangkai | 138.199.35.216 |
| 83.65 | http | 205.3 | 482.4 | 23.03 | 0.0 | 10.0 | 14.38 | 19.24 | zhangkai | 138.199.35.198 |
| 83.32 | vless | 220.0 | 580.0 | 22.68 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 172.239.67.156 |
| 83.19 | vless | 226.0 | 597.3 | 22.55 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 172.235.38.85 |
| 83.04 | vless | 232.3 | 591.2 | 22.4 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 172.239.67.231 |
| 82.39 | vless | 260.4 | 494.4 | 21.75 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 172.233.156.123 |
| 81.83 | vless | 241.2 | 621.1 | 22.19 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 104.223.73.149 |
| 81.72 | vless | 289.2 | 506.2 | 21.08 | 0.0 | 10.0 | 11.6 | 19.04 | Au1rxx-base64 | 172.235.43.210 |
| 81.5 | hysteria2 | 343.6 | 906.9 | 19.82 | 0.0 | 10.0 | 13.64 | 19.04 | Au1rxx-base64 | 66.94.121.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.97 | 0.903 | 349 | 1741 | prefer |
| mheidari-all | 0.949 | 0.875 | 120 | 15532 | prefer |
| zhangkai | 0.886 | 0.913 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.808 | 0.731 | 156 | 7112 | prefer |
| DeltaKronecker-all | 0.776 | 0.714 | 21 | 7295 | prefer |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 103 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4765 | observe |
| Epodonios-all | 0.255 | None | 0 | 7553 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7794 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5992 | observe |
| barry-far-vless | 0.255 | None | 0 | 6200 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4066 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 19 |
| geo | ClientOSError | - | 16 |
| cn-block | ClientOSError | - | 14 |
| 204 | ProxyError | - | 11 |
| 204 | TimeoutError | - | 10 |
| speed | TimeoutError | - | 8 |
| speed | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| geo | TimeoutError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
