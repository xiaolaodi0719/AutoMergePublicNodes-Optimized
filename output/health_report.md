# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-07 13:18:35 |
| 运行耗时 | 234.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82701 |
| 去重后节点 | 23372 |
| TCP 可达 | 3000 |
| 真实可用 | 406 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23372 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.3 |
| tcp | 35.7 |
| probe | 55.9 |
| real_test | 103.5 |
| generate | 32.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47542 |
| vmess | 12851 |
| trojan | 11180 |
| shadowsocks | 9644 |
| hysteria2 | 1294 |
| shadowsocksr | 69 |
| socks | 63 |
| http | 35 |
| hysteria | 13 |
| tuic | 10 |

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
| 84.3 | trojan | 202.4 | 485.2 | 23.09 | 0.0 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 84.26 | trojan | 204.2 | 482.2 | 23.05 | 0.0 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 44.246.163.102 |
| 83.54 | trojan | 235.3 | 582.6 | 22.33 | 0.0 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 44.242.235.129 |
| 83.36 | trojan | 243.0 | 608.8 | 22.15 | 0.0 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 35.91.251.124 |
| 83.17 | trojan | 251.4 | 627.1 | 21.96 | 0.0 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 35.86.90.51 |
| 81.08 | shadowsocks | 266.0 | 726.5 | 21.62 | 0.0 | 10.0 | 13.74 | 19.72 | Au1rxx-base64 | 149.22.95.183 |
| 80.25 | trojan | 246.8 | 620.4 | 22.06 | 0.0 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 44.244.3.114 |
| 79.32 | shadowsocks | 256.9 | 267.0 | 21.83 | 4.99 | 10.0 | 13.74 | 19.72 | Au1rxx-base64 | 149.22.87.204 |
| 78.52 | hysteria2 | 337.2 | 747.1 | 19.97 | 0.0 | 10.0 | 13.12 | 19.72 | Au1rxx-base64 | 138.124.68.188 |
| 77.89 | trojan | 352.4 | 279.5 | 19.62 | 4.52 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 43.207.155.134 |
| 77.88 | shadowsocks | 263.9 | 557.7 | 21.67 | 0.0 | 10.0 | 13.74 | 19.72 | Au1rxx-base64 | 173.244.56.9 |
| 77.78 | trojan | 354.4 | 281.6 | 19.57 | 4.44 | 9.99 | 13.99 | 19.72 | Au1rxx-base64 | 54.249.34.120 |
| 77.68 | shadowsocks | 262.8 | 555.5 | 21.69 | 0.0 | 10.0 | 13.74 | 19.72 | Au1rxx-base64 | 173.244.56.6 |
| 77.62 | trojan | 334.8 | 297.9 | 20.03 | 3.83 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 52.198.25.180 |
| 77.62 | trojan | 340.1 | 294.9 | 19.91 | 3.94 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 3.112.15.214 |
| 77.62 | trojan | 350.9 | 286.5 | 19.66 | 4.26 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 13.231.232.184 |
| 77.61 | trojan | 345.0 | 291.7 | 19.79 | 4.06 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 52.196.121.8 |
| 77.56 | trojan | 348.1 | 290.1 | 19.72 | 4.12 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 54.199.202.238 |
| 77.44 | trojan | 341.7 | 297.9 | 19.87 | 3.83 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 43.207.89.29 |
| 77.42 | trojan | 335.9 | 303.1 | 20.0 | 3.64 | 10.0 | 13.99 | 19.72 | Au1rxx-base64 | 43.207.140.98 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.968 | 339 | 1509 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| mheidari-all | 0.71 | 0.634 | 71 | 17690 | prefer |
| Surfboard-tg-mixed | 0.389 | 0.385 | 13 | 6364 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| DeltaKronecker-all | 0.258 | 0.163 | 43 | 5326 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5282 | observe |
| Epodonios-all | 0.255 | None | 0 | 6987 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7685 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5147 | observe |
| barry-far-vless | 0.255 | None | 0 | 5471 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5247 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1509 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 18 |
| geo | TimeoutError | - | 16 |
| speed | ClientOSError | - | 11 |
| 204 | TimeoutError | - | 9 |
| 204 | ProxyError | - | 8 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| cn-block | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
