# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-24 13:59:41 |
| 运行耗时 | 287.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 82875 |
| 去重后节点 | 22678 |
| TCP 可达 | 3000 |
| 真实可用 | 666 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22678 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.3 |
| tcp | 32.3 |
| probe | 60.0 |
| real_test | 148.8 |
| generate | 40.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46945 |
| trojan | 15334 |
| vmess | 10140 |
| shadowsocks | 9847 |
| hysteria2 | 404 |
| shadowsocksr | 69 |
| socks | 59 |
| http | 51 |
| hysteria | 15 |
| tuic | 9 |
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
| 72.78 | trojan | 428.9 | 1218.6 | 17.85 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 153.75.250.171 |
| 71.81 | trojan | 308.0 | 670.2 | 20.65 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 163.245.196.68 |
| 69.38 | trojan | 341.6 | 871.6 | 19.87 | 0.0 | 10.0 | 13.55 | 8.96 | DeltaKronecker-all | 64.74.163.118 |
| 68.25 | vless | 324.0 | 633.9 | 20.28 | 0.0 | 10.0 | 4.49 | 14.38 | mheidari-all | 45.206.5.122 |
| 67.94 | trojan | 383.0 | 705.8 | 18.91 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 91.107.145.13 |
| 67.79 | trojan | 435.2 | 767.6 | 17.7 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 45.130.125.75 |
| 67.76 | trojan | 433.9 | 771.6 | 17.73 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 104.19.64.105 |
| 67.75 | trojan | 433.8 | 766.3 | 17.74 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 45.130.125.160 |
| 67.74 | trojan | 436.0 | 787.7 | 17.69 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 104.16.174.6 |
| 67.69 | trojan | 436.9 | 778.8 | 17.66 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 212.183.88.136 |
| 67.67 | trojan | 435.5 | 767.9 | 17.7 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 185.18.250.245 |
| 67.66 | trojan | 436.5 | 763.1 | 17.67 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 104.17.121.71 |
| 67.62 | trojan | 442.5 | 785.4 | 17.53 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 45.130.125.76 |
| 67.18 | trojan | 451.0 | 833.5 | 17.34 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 104.16.174.121 |
| 66.74 | trojan | 434.0 | 776.8 | 17.73 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 8.6.112.6 |
| 66.19 | vless | 235.9 | 651.4 | 22.32 | 0.0 | 10.0 | 4.49 | 14.38 | mheidari-all | 47.89.186.170 |
| 65.87 | trojan | 448.0 | 803.6 | 17.41 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 79.133.126.237 |
| 65.85 | trojan | 447.8 | 810.8 | 17.41 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 85.234.65.26 |
| 65.71 | shadowsocks | 226.4 | 625.6 | 22.54 | 0.0 | 10.0 | 10.59 | 6.58 | Au1rxx-base64 | 37.19.198.236 |
| 65.68 | trojan | 455.0 | 822.8 | 17.25 | 0.0 | 10.0 | 13.55 | 14.38 | mheidari-all | 89.39.70.49 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.95 | 0.972 | 36 | 61 | prefer |
| DeltaKronecker-all | 0.853 | 0.777 | 148 | 5559 | prefer |
| mheidari-all | 0.808 | 0.728 | 655 | 19570 | prefer |
| Surfboard-tg-mixed | 0.703 | 0.627 | 51 | 5218 | prefer |
| Au1rxx-base64 | 0.457 | 1.0 | 5 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3847 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4588 | observe |
| Epodonios-all | 0.255 | None | 0 | 6424 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3975 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6965 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4143 | observe |
| barry-far-vless | 0.255 | None | 0 | 4809 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5027 | observe |
| nscl5-all | 0.255 | None | 0 | 3124 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 72 |
| speed | ClientOSError | - | 42 |
| 204 | ProxyError | - | 26 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 19 |
| geo | ClientOSError | - | 16 |
| cn-block | ProxyError | - | 10 |
| speed | TimeoutError | - | 10 |
| geo | ProxyError | - | 7 |
| speed | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
