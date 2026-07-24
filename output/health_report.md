# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-24 03:23:03 |
| 运行耗时 | 410.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83695 |
| 去重后节点 | 23126 |
| TCP 可达 | 3000 |
| 真实可用 | 893 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23126 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.3 |
| tcp | 32.1 |
| probe | 81.2 |
| real_test | 258.5 |
| generate | 31.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47330 |
| trojan | 15490 |
| shadowsocks | 10141 |
| vmess | 10126 |
| hysteria2 | 401 |
| shadowsocksr | 77 |
| socks | 58 |
| http | 51 |
| hysteria | 15 |
| tuic | 4 |
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
| 75.09 | vless | 174.1 | 464.5 | 23.75 | 0.0 | 10.0 | 4.32 | 18.02 | DeltaKronecker-all | 172.67.209.126 |
| 75.07 | vless | 174.7 | 462.7 | 23.73 | 0.0 | 10.0 | 4.32 | 18.02 | DeltaKronecker-all | 104.25.161.29 |
| 74.08 | vless | 217.4 | 596.5 | 22.74 | 0.0 | 10.0 | 4.32 | 18.02 | DeltaKronecker-all | 104.17.90.246 |
| 72.06 | trojan | 550.9 | 1463.6 | 15.02 | 0.0 | 10.0 | 12.52 | 18.02 | DeltaKronecker-all | 16.147.206.1 |
| 71.97 | trojan | 326.4 | 660.0 | 20.22 | 0.0 | 10.0 | 12.52 | 17.16 | Surfboard-tg-mixed | 163.245.196.68 |
| 71.75 | trojan | 233.7 | 510.2 | 22.37 | 0.0 | 10.0 | 12.52 | 15.12 | mheidari-all | 44.246.190.9 |
| 71.68 | trojan | 234.4 | 530.2 | 22.35 | 0.0 | 10.0 | 12.52 | 15.12 | mheidari-all | 44.255.209.248 |
| 71.32 | trojan | 281.4 | 660.2 | 21.27 | 0.0 | 10.0 | 12.52 | 15.12 | mheidari-all | 44.255.92.71 |
| 69.41 | vless | 225.1 | 546.7 | 22.57 | 0.0 | 10.0 | 4.32 | 18.02 | DeltaKronecker-all | 172.67.69.63 |
| 68.19 | trojan | 365.1 | 374.7 | 19.33 | 0.95 | 10.0 | 12.52 | 18.02 | DeltaKronecker-all | 45.85.118.16 |
| 67.97 | trojan | 332.4 | 337.8 | 20.08 | 2.33 | 9.94 | 12.52 | 18.02 | DeltaKronecker-all | 161.34.39.108 |
| 67.85 | trojan | 480.6 | 982.6 | 16.65 | 0.0 | 10.0 | 12.52 | 18.02 | DeltaKronecker-all | 64.74.163.118 |
| 67.79 | trojan | 426.9 | 361.5 | 17.89 | 1.44 | 9.48 | 12.52 | 17.16 | Surfboard-tg-mixed | 119.246.1.143 |
| 67.55 | trojan | 325.0 | 331.5 | 20.26 | 2.57 | 9.95 | 12.52 | 15.12 | mheidari-all | 31.223.184.43 |
| 67.49 | trojan | 328.3 | 330.8 | 20.18 | 2.59 | 9.95 | 12.52 | 15.12 | mheidari-all | 31.223.184.164 |
| 67.34 | trojan | 325.9 | 334.7 | 20.23 | 2.45 | 9.95 | 12.52 | 15.12 | mheidari-all | 95.85.94.165 |
| 67.29 | trojan | 329.5 | 333.5 | 20.15 | 2.49 | 9.95 | 12.52 | 15.12 | mheidari-all | 31.223.184.82 |
| 66.97 | trojan | 366.7 | 452.3 | 19.29 | 0.0 | 9.95 | 12.52 | 15.12 | mheidari-all | 95.85.94.199 |
| 66.84 | vless | 163.2 | 460.0 | 24.0 | 0.0 | 10.0 | 4.32 | 18.02 | DeltaKronecker-all | 92.223.71.246 |
| 66.45 | trojan | 334.1 | 354.0 | 20.04 | 1.73 | 9.95 | 12.52 | 15.12 | mheidari-all | 31.223.184.125 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.926 | 0.848 | 486 | 20024 | prefer |
| Surfboard-tg-mixed | 0.82 | 0.745 | 98 | 5375 | prefer |
| DeltaKronecker-all | 0.444 | 0.364 | 1011 | 5572 | observe |
| Au1rxx-base64 | 0.329 | 1.0 | 2 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 3843 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4757 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6957 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4163 | observe |
| barry-far-vless | 0.255 | None | 0 | 4750 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4971 | observe |
| nscl5-all | 0.255 | None | 0 | 3124 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 261 |
| speed | ClientOSError | - | 208 |
| cn-block | TimeoutError | - | 95 |
| geo | ClientOSError | - | 66 |
| 204 | ProxyError | - | 49 |
| speed | TimeoutError | - | 38 |
| cn-block | ProxyError | - | 12 |
| geo | ProxyError | - | 6 |
| speed | ProxyError | - | 4 |
| 204 | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
