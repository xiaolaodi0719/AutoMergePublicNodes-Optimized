# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-03 20:51:23 |
| 运行耗时 | 259.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82446 |
| 去重后节点 | 22585 |
| TCP 可达 | 3000 |
| 真实可用 | 577 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22585 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| geo | 1.4 |
| tcp | 38.0 |
| probe | 67.0 |
| real_test | 111.5 |
| generate | 37.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50923 |
| vmess | 11833 |
| shadowsocks | 10016 |
| trojan | 7766 |
| hysteria2 | 1562 |
| http | 139 |
| shadowsocksr | 122 |
| socks | 59 |
| tuic | 15 |
| hysteria | 10 |
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
| 83.79 | hysteria2 | 254.2 | 554.5 | 21.89 | 0.0 | 10.0 | 14.4 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 82.3 | vless | 322.6 | 834.0 | 20.31 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 38.180.242.205 |
| 81.77 | shadowsocks | 245.1 | 637.5 | 22.1 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.51 | shadowsocks | 256.5 | 653.4 | 21.84 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.46 | shadowsocks | 258.5 | 653.1 | 21.79 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 80.17 | vless | 283.4 | 576.4 | 21.22 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 172.239.67.156 |
| 79.89 | shadowsocks | 304.8 | 739.7 | 20.72 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 79.66 | shadowsocks | 295.5 | 683.8 | 20.94 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 79.32 | vless | 284.7 | 591.0 | 21.19 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 172.233.156.123 |
| 79.07 | vless | 320.6 | 555.4 | 20.36 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 172.239.67.231 |
| 79.0 | vless | 285.6 | 578.3 | 21.17 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 78.96 | trojan | 400.3 | 978.0 | 18.51 | 0.0 | 10.0 | 13.45 | 20.0 | Au1rxx-base64 | 64.94.95.117 |
| 78.89 | vless | 280.9 | 565.4 | 21.28 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 78.87 | vless | 292.6 | 594.1 | 21.01 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 172.236.252.35 |
| 78.6 | vless | 298.9 | 554.8 | 20.86 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 45.79.103.108 |
| 78.59 | vless | 299.3 | 580.3 | 20.85 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 192.155.87.188 |
| 78.49 | vless | 298.9 | 579.5 | 20.86 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 173.230.155.55 |
| 78.43 | vless | 359.4 | 676.6 | 19.46 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 78.41 | vless | 299.5 | 571.9 | 20.85 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 45.33.107.237 |
| 78.29 | vless | 294.7 | 542.0 | 20.96 | 0.0 | 10.0 | 12.47 | 20.0 | Au1rxx-base64 | 74.207.245.124 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.951 | 365 | 1748 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| mheidari-all | 0.92 | 0.847 | 98 | 15893 | prefer |
| Surfboard-tg-mixed | 0.811 | 0.737 | 76 | 7177 | prefer |
| DeltaKronecker-all | 0.81 | 0.736 | 87 | 6335 | prefer |
| tg-oneclickvpnkeys | 0.405 | 1.0 | 4 | 115 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4671 | observe |
| Epodonios-all | 0.255 | None | 0 | 7695 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8160 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5920 | observe |
| barry-far-vless | 0.255 | None | 0 | 6131 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4133 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1748 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 17 |
| geo | ClientOSError | - | 13 |
| cn-block | ProxyError | - | 6 |
| speed | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| geo | TimeoutError | - | 3 |
| 204 | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
