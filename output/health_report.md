# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-08 07:05:18 |
| 运行耗时 | 260.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82085 |
| 去重后节点 | 23444 |
| TCP 可达 | 3000 |
| 真实可用 | 481 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23444 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.5 |
| tcp | 34.9 |
| probe | 58.0 |
| real_test | 125.0 |
| generate | 36.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47747 |
| vmess | 12906 |
| trojan | 10237 |
| shadowsocks | 9722 |
| hysteria2 | 1280 |
| shadowsocksr | 69 |
| socks | 65 |
| http | 36 |
| hysteria | 13 |
| tuic | 9 |
| anytls | 1 |

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
| 83.82 | http | 189.8 | 487.1 | 23.38 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 83.81 | http | 190.3 | 492.1 | 23.37 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 83.8 | http | 190.7 | 494.3 | 23.36 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 83.74 | http | 193.6 | 501.7 | 23.3 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 83.38 | trojan | 222.6 | 503.9 | 22.62 | 0.0 | 10.0 | 13.45 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 82.58 | trojan | 265.5 | 631.6 | 21.63 | 0.0 | 10.0 | 13.45 | 20.0 | Au1rxx-base64 | 44.242.235.129 |
| 82.31 | shadowsocks | 244.9 | 563.7 | 22.11 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 82.04 | trojan | 288.8 | 698.4 | 21.09 | 0.0 | 10.0 | 13.45 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 81.85 | shadowsocks | 243.0 | 605.7 | 22.15 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 81.64 | shadowsocks | 252.4 | 655.6 | 21.94 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 81.43 | shadowsocks | 283.0 | 710.7 | 21.23 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 81.33 | trojan | 316.0 | 783.7 | 20.46 | 0.0 | 10.0 | 13.45 | 20.0 | Au1rxx-base64 | 35.86.90.51 |
| 79.94 | hysteria2 | 348.3 | 774.6 | 19.72 | 0.0 | 10.0 | 14.42 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 79.21 | hysteria2 | 337.7 | 710.8 | 19.96 | 0.0 | 10.0 | 14.42 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 79.04 | shadowsocks | 272.0 | 277.0 | 21.48 | 4.61 | 9.94 | 14.2 | 20.0 | Au1rxx-base64 | 149.22.87.240 |
| 78.33 | shadowsocks | 292.0 | 653.6 | 21.02 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 78.33 | shadowsocks | 292.0 | 660.4 | 21.02 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 78.12 | shadowsocks | 291.2 | 659.8 | 21.04 | 0.0 | 10.0 | 14.2 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 77.97 | trojan | 300.9 | 641.1 | 20.81 | 0.0 | 10.0 | 13.45 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 77.76 | trojan | 299.7 | 648.4 | 20.84 | 0.0 | 10.0 | 13.45 | 20.0 | Au1rxx-base64 | 64.94.95.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.949 | 350 | 1368 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.567 | 0.486 | 111 | 6419 | observe |
| mheidari-all | 0.535 | 0.455 | 121 | 17696 | observe |
| DeltaKronecker-all | 0.42 | 0.333 | 51 | 5347 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 169 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5450 | observe |
| Epodonios-all | 0.255 | None | 0 | 6914 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7402 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5218 | observe |
| barry-far-vless | 0.255 | None | 0 | 5409 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5162 | observe |
| ninja-vless | 0.251 | 0.333 | 3 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 59 |
| geo | ClientOSError | - | 32 |
| cn-block | TimeoutError | - | 20 |
| speed | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 13 |
| speed | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
