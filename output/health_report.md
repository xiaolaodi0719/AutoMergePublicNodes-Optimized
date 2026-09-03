# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-03 11:02:14 |
| 运行耗时 | 288.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82568 |
| 去重后节点 | 22928 |
| TCP 可达 | 3000 |
| 真实可用 | 513 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22928 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.6 |
| tcp | 37.7 |
| probe | 82.7 |
| real_test | 115.8 |
| generate | 44.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51712 |
| vmess | 11434 |
| shadowsocks | 9814 |
| trojan | 7653 |
| hysteria2 | 1587 |
| http | 138 |
| shadowsocksr | 125 |
| socks | 84 |
| tuic | 11 |
| hysteria | 10 |

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
| 82.03 | shadowsocks | 235.8 | 641.4 | 22.32 | 0.0 | 10.0 | 14.09 | 19.62 | Au1rxx-base64 | 149.22.95.183 |
| 81.51 | vless | 242.5 | 566.1 | 22.16 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 45.79.103.108 |
| 81.14 | vless | 258.6 | 598.1 | 21.79 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 192.155.87.188 |
| 81.14 | vless | 258.9 | 608.6 | 21.79 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 45.33.107.237 |
| 80.51 | vless | 282.6 | 665.0 | 21.24 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 50.116.9.184 |
| 79.85 | vless | 314.6 | 564.9 | 20.5 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 45.33.62.166 |
| 79.45 | vless | 253.1 | 546.4 | 21.92 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 172.235.38.85 |
| 79.34 | vless | 252.9 | 558.1 | 21.92 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 172.236.252.35 |
| 79.25 | vless | 270.3 | 640.8 | 21.52 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 74.207.245.124 |
| 79.1 | vless | 249.1 | 550.2 | 22.01 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 172.233.139.46 |
| 79.05 | vless | 259.4 | 569.3 | 21.77 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 172.233.156.118 |
| 78.95 | vless | 252.7 | 551.4 | 21.93 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 172.239.67.231 |
| 78.25 | vless | 258.6 | 572.6 | 21.79 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 172.235.43.210 |
| 78.18 | vless | 263.8 | 587.4 | 21.67 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 172.239.67.156 |
| 77.89 | vless | 270.7 | 564.9 | 21.51 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 172.233.156.123 |
| 77.32 | vless | 251.7 | 558.1 | 21.95 | 0.0 | 10.0 | 9.73 | 19.62 | Au1rxx-base64 | 31.58.50.200 |
| 77.32 | shadowsocks | 293.6 | 551.3 | 20.98 | 0.0 | 10.0 | 14.09 | 19.62 | Au1rxx-base64 | 173.244.56.6 |
| 77.27 | shadowsocks | 277.9 | 316.4 | 21.35 | 3.14 | 10.0 | 14.09 | 19.62 | Au1rxx-base64 | 149.22.87.204 |
| 76.99 | vless | 274.7 | 272.4 | 21.42 | 4.78 | 10.0 | 9.73 | 17.34 | Surfboard-tg-mixed | 31.76.91.72 |
| 76.33 | shadowsocks | 341.9 | 747.6 | 19.86 | 0.0 | 10.0 | 14.09 | 19.62 | Au1rxx-base64 | 108.181.118.10 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | 0.907 | 312 | 1751 | prefer |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| mheidari-all | 0.868 | 0.793 | 111 | 16145 | prefer |
| Surfboard-tg-mixed | 0.815 | 0.738 | 160 | 7139 | prefer |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 6335 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 87 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4671 | observe |
| Epodonios-all | 0.255 | None | 0 | 7527 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8132 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6006 | observe |
| barry-far-vless | 0.255 | None | 0 | 6217 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4081 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 23 |
| 204 | TimeoutError | - | 20 |
| geo | ClientOSError | - | 14 |
| geo | TimeoutError | - | 10 |
| 204 | ProxyError | - | 8 |
| speed | TimeoutError | - | 5 |
| speed | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyConnectionError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
