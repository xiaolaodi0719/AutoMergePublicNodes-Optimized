# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-06 20:19:09 |
| 运行耗时 | 309.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94324 |
| 去重后节点 | 24687 |
| TCP 可达 | 3000 |
| 真实可用 | 549 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24687 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 41.9 |
| probe | 81.1 |
| real_test | 137.0 |
| generate | 42.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58830 |
| vmess | 12738 |
| shadowsocks | 11244 |
| trojan | 9054 |
| hysteria2 | 2061 |
| http | 139 |
| shadowsocksr | 130 |
| socks | 63 |
| anytls | 30 |
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
| 82.86 | vless | 197.7 | 503.5 | 23.2 | 0.0 | 8.6 | 11.74 | 19.32 | Au1rxx-base64 | 172.235.38.85 |
| 82.77 | vless | 200.6 | 518.6 | 23.13 | 0.0 | 8.58 | 11.74 | 19.32 | Au1rxx-base64 | 38.209.125.45 |
| 82.53 | vless | 212.0 | 538.2 | 22.87 | 0.0 | 8.6 | 11.74 | 19.32 | Au1rxx-base64 | 23.94.227.94 |
| 80.69 | hysteria2 | 214.6 | 509.5 | 22.81 | 0.0 | 8.71 | 13.85 | 19.32 | Au1rxx-base64 | 66.94.121.46 |
| 80.65 | vless | 299.8 | 470.8 | 20.84 | 0.0 | 8.75 | 11.74 | 19.32 | Au1rxx-base64 | 38.246.229.58 |
| 80.47 | vless | 306.6 | 812.9 | 20.68 | 0.0 | 8.73 | 11.74 | 19.32 | Au1rxx-base64 | 38.150.33.232 |
| 80.15 | shadowsocks | 237.8 | 542.0 | 22.27 | 0.0 | 8.62 | 13.94 | 19.32 | Au1rxx-base64 | 173.244.56.6 |
| 78.41 | vless | 185.6 | 471.7 | 23.48 | 0.0 | 8.6 | 11.74 | 19.32 | Au1rxx-base64 | 216.167.94.71 |
| 78.28 | vless | 200.6 | 496.0 | 23.13 | 0.0 | 8.59 | 11.74 | 19.32 | Au1rxx-base64 | 162.159.0.53 |
| 77.7 | vless | 233.7 | 449.0 | 22.37 | 0.0 | 8.77 | 11.74 | 19.32 | Au1rxx-base64 | 172.64.32.103 |
| 77.29 | shadowsocks | 243.9 | 612.3 | 22.13 | 0.0 | 8.58 | 13.94 | 19.32 | Au1rxx-base64 | 108.181.0.177 |
| 77.2 | vless | 257.5 | 304.4 | 21.82 | 3.58 | 9.84 | 11.74 | 16.7 | Surfboard-tg-mixed | 31.76.91.72 |
| 76.97 | vless | 195.3 | 506.3 | 23.26 | 0.0 | 8.58 | 11.74 | 19.32 | Au1rxx-base64 | 172.233.139.46 |
| 76.93 | shadowsocks | 262.3 | 677.5 | 21.71 | 0.0 | 10.0 | 13.94 | 15.78 | mheidari-all | 108.181.118.10 |
| 76.88 | shadowsocks | 285.7 | 635.1 | 21.16 | 0.0 | 10.0 | 13.94 | 15.78 | mheidari-all | 173.244.56.9 |
| 75.34 | shadowsocks | 295.2 | 668.0 | 20.94 | 0.0 | 8.72 | 13.94 | 19.32 | Au1rxx-base64 | 156.146.38.168 |
| 74.46 | shadowsocks | 328.3 | 768.5 | 20.18 | 0.0 | 8.54 | 13.94 | 19.32 | Au1rxx-base64 | 156.146.38.167 |
| 74.37 | vless | 336.6 | 343.2 | 19.99 | 2.13 | 8.68 | 11.74 | 19.32 | Au1rxx-base64 | 13.113.195.74 |
| 74.35 | vless | 335.6 | 337.5 | 20.01 | 2.35 | 8.49 | 11.74 | 19.32 | Au1rxx-base64 | 13.193.9.59 |
| 74.34 | vless | 333.8 | 341.0 | 20.05 | 2.21 | 8.48 | 11.74 | 19.32 | Au1rxx-base64 | 57.180.65.248 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | 0.903 | 310 | 1862 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.793 | 0.715 | 186 | 7274 | prefer |
| mheidari-all | 0.675 | 0.596 | 183 | 21188 | observe |
| tg-oneclickvpnkeys | 0.298 | 0.6 | 5 | 134 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4791 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 5856 | observe |
| Epodonios-all | 0.255 | None | 0 | 7817 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8616 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6019 | observe |
| barry-far-vless | 0.255 | None | 0 | 6306 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1862 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 49 |
| geo | ClientOSError | - | 34 |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 19 |
| speed | ClientOSError | - | 8 |
| 204 | ProxyError | - | 7 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 5 |
| geo | TimeoutError | - | 4 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
