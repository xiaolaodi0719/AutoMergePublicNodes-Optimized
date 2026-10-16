# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 11:17:31 |
| 运行耗时 | 821.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99257 |
| 去重后节点 | 27610 |
| TCP 可达 | 3000 |
| 真实可用 | 422 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27610 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 47.7 |
| probe | 386.9 |
| real_test | 291.1 |
| generate | 86.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58394 |
| vmess | 16397 |
| shadowsocks | 11898 |
| trojan | 10296 |
| hysteria2 | 1260 |
| http | 740 |
| shadowsocksr | 165 |
| socks | 59 |
| anytls | 25 |
| hysteria | 17 |
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
| 81.46 | hysteria2 | 252.1 | 692.9 | 21.94 | 0.0 | 10.0 | 13.42 | 17.6 | Au1rxx-base64 | 129.213.91.185 |
| 78.21 | shadowsocks | 253.2 | 699.4 | 21.92 | 0.0 | 8.81 | 13.88 | 17.6 | Au1rxx-base64 | 37.19.198.236 |
| 78.19 | shadowsocks | 254.0 | 708.9 | 21.9 | 0.0 | 8.81 | 13.88 | 17.6 | Au1rxx-base64 | 37.19.198.160 |
| 78.13 | shadowsocks | 256.3 | 713.9 | 21.84 | 0.0 | 8.81 | 13.88 | 17.6 | Au1rxx-base64 | 37.19.198.243 |
| 78.12 | shadowsocks | 255.5 | 717.8 | 21.86 | 0.0 | 8.78 | 13.88 | 17.6 | Au1rxx-base64 | 37.19.198.244 |
| 77.5 | shadowsocks | 262.2 | 744.1 | 21.71 | 0.0 | 8.81 | 13.88 | 17.6 | Au1rxx-base64 | 15.204.233.41 |
| 76.59 | vless | 297.2 | 763.2 | 20.9 | 0.0 | 9.23 | 8.86 | 17.6 | Au1rxx-base64 | 66.70.179.198 |
| 75.72 | hysteria2 | 365.4 | 674.0 | 19.32 | 0.0 | 10.0 | 13.42 | 17.6 | Au1rxx-base64 | 66.94.121.46 |
| 75.61 | shadowsocks | 280.7 | 650.8 | 21.28 | 0.0 | 8.8 | 13.88 | 17.6 | Au1rxx-base64 | 156.146.38.167 |
| 75.43 | vless | 336.9 | 911.1 | 19.98 | 0.0 | 8.99 | 8.86 | 17.6 | Au1rxx-base64 | 167.17.69.171 |
| 75.41 | shadowsocks | 274.4 | 719.5 | 21.43 | 0.0 | 10.0 | 13.88 | 17.6 | Au1rxx-base64 | 64.74.163.67 |
| 75.22 | vless | 354.6 | 986.6 | 19.57 | 0.0 | 9.19 | 8.86 | 17.6 | Au1rxx-base64 | 195.123.235.183 |
| 75.12 | vless | 352.1 | 964.7 | 19.63 | 0.0 | 9.03 | 8.86 | 17.6 | Au1rxx-base64 | 185.95.231.156 |
| 75.07 | shadowsocks | 288.8 | 758.9 | 21.09 | 0.0 | 10.0 | 13.88 | 17.6 | Au1rxx-base64 | 64.74.163.69 |
| 74.85 | shadowsocks | 277.6 | 638.6 | 21.35 | 0.0 | 8.8 | 13.88 | 17.6 | Au1rxx-base64 | 156.146.38.169 |
| 74.21 | shadowsocks | 278.8 | 642.4 | 21.32 | 0.0 | 8.8 | 13.88 | 17.6 | Au1rxx-base64 | 156.146.38.168 |
| 74.04 | vless | 264.7 | 644.1 | 21.65 | 0.0 | 8.93 | 8.86 | 17.6 | Au1rxx-base64 | 195.211.98.43 |
| 73.78 | hysteria2 | 356.0 | 689.0 | 19.54 | 0.0 | 10.0 | 13.42 | 17.6 | Au1rxx-base64 | 62.210.124.146 |
| 73.26 | vless | 323.9 | 761.4 | 20.28 | 0.0 | 9.23 | 8.86 | 17.6 | Au1rxx-base64 | 5.34.178.120 |
| 72.71 | vless | 257.2 | 704.4 | 21.82 | 0.0 | 8.93 | 8.86 | 17.6 | Au1rxx-base64 | 104.243.33.154 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.849 | 0.77 | 457 | 1990 | prefer |
| ermaozi | 0.49 | 0.462 | 91 | 693 | observe |
| Surfboard-tg-mixed | 0.485 | 0.4 | 35 | 7090 | observe |
| mheidari-all | 0.474 | 0.467 | 15 | 23871 | observe |
| DeltaKronecker-all | 0.33 | 0.231 | 26 | 4946 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1990 | observe |
| Epodonios-all | 0.255 | None | 0 | 7568 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10065 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5572 | observe |
| barry-far-vless | 0.255 | None | 0 | 5827 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4265 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 50 |
| 204 | ProxyError | - | 41 |
| cn-block | TimeoutError | - | 27 |
| speed | TimeoutError | - | 16 |
| 204 | ProxyConnectionError | - | 15 |
| speed | ClientOSError | - | 14 |
| geo | ClientOSError | - | 11 |
| geo | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 6 |
| 204 | ClientOSError | - | 5 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
