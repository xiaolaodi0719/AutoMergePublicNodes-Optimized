# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 16:22:54 |
| 运行耗时 | 627.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83892 |
| 去重后节点 | 23232 |
| TCP 可达 | 3000 |
| 真实可用 | 420 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23232 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.5 |
| tcp | 40.1 |
| probe | 255.3 |
| real_test | 239.9 |
| generate | 84.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50697 |
| vmess | 12815 |
| shadowsocks | 9896 |
| trojan | 8027 |
| hysteria2 | 1659 |
| http | 599 |
| shadowsocksr | 125 |
| socks | 51 |
| tuic | 12 |
| hysteria | 9 |
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
| 80.57 | vless | 287.3 | 740.3 | 21.13 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 172.233.139.46 |
| 80.01 | vless | 311.2 | 795.7 | 20.57 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 15.204.97.216 |
| 77.41 | hysteria2 | 254.5 | 554.5 | 21.89 | 0.0 | 10.0 | 12.27 | 18.66 | Au1rxx-base64 | 66.94.121.46 |
| 76.83 | vless | 217.9 | 519.7 | 22.73 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 172.235.38.85 |
| 76.63 | vless | 207.5 | 529.2 | 22.97 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 172.235.43.210 |
| 76.03 | shadowsocks | 286.6 | 723.6 | 21.14 | 0.0 | 10.0 | 13.77 | 15.12 | Surfboard-tg-mixed | 173.244.56.6 |
| 75.4 | shadowsocks | 264.6 | 663.9 | 21.65 | 0.0 | 10.0 | 13.77 | 14.48 | mheidari-all | 108.181.0.177 |
| 75.12 | vless | 522.5 | 1392.7 | 15.68 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 51.81.203.63 |
| 74.97 | hysteria2 | 360.8 | 719.7 | 19.43 | 0.0 | 10.0 | 12.27 | 18.66 | Au1rxx-base64 | 159.223.157.129 |
| 74.84 | shadowsocks | 267.4 | 649.8 | 21.59 | 0.0 | 10.0 | 13.77 | 14.48 | mheidari-all | 149.22.95.183 |
| 74.36 | vless | 355.0 | 761.6 | 19.56 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 79.141.172.154 |
| 74.05 | http | 235.7 | 600.8 | 22.32 | 0.0 | 10.0 | 11.93 | 15.8 | ermaozi | 138.199.35.198 |
| 74.05 | vless | 339.4 | 338.5 | 19.92 | 2.3 | 9.91 | 10.78 | 18.66 | Au1rxx-base64 | 13.231.19.51 |
| 73.75 | vless | 238.7 | 483.5 | 22.25 | 0.0 | 10.0 | 10.78 | 16.46 | DeltaKronecker-all | 162.159.39.218 |
| 73.56 | vless | 395.8 | 624.7 | 18.62 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 108.162.198.178 |
| 73.36 | vless | 342.1 | 354.7 | 19.86 | 1.7 | 9.94 | 10.78 | 18.66 | Au1rxx-base64 | 13.231.7.104 |
| 73.34 | vless | 213.7 | 531.3 | 22.83 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 172.236.233.59 |
| 73.31 | vless | 354.2 | 757.8 | 19.58 | 0.0 | 10.0 | 10.78 | 18.66 | Au1rxx-base64 | 188.137.243.243 |
| 73.08 | vless | 298.3 | 616.2 | 20.87 | 0.0 | 10.0 | 10.78 | 16.46 | DeltaKronecker-all | 162.159.0.169 |
| 72.85 | shadowsocks | 230.3 | 579.4 | 22.45 | 0.0 | 10.0 | 13.77 | 15.12 | Surfboard-tg-mixed | 5.78.51.123 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.941 | 0.882 | 34 | 15708 | prefer |
| Au1rxx-base64 | 0.895 | 0.827 | 255 | 1758 | prefer |
| Surfboard-tg-mixed | 0.816 | 0.742 | 89 | 7370 | prefer |
| ermaozi | 0.748 | 0.75 | 28 | 377 | prefer |
| DeltaKronecker-all | 0.732 | 0.654 | 136 | 6070 | prefer |
| tg-oneclickvpnkeys | 0.32 | 1.0 | 2 | 228 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7833 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8514 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5979 | observe |
| barry-far-vless | 0.255 | None | 0 | 6192 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1758 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 42 |
| 204 | ProxyError | - | 19 |
| cn-block | TimeoutError | - | 19 |
| speed | ClientOSError | - | 11 |
| 204 | TimeoutError | - | 11 |
| geo | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 5 |
| geo | ProxyError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
