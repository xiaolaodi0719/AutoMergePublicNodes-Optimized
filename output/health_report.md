# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-24 08:38:58 |
| 运行耗时 | 303.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83120 |
| 去重后节点 | 22640 |
| TCP 可达 | 3000 |
| 真实可用 | 617 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22640 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.8 |
| geo | 1.0 |
| tcp | 31.7 |
| probe | 65.4 |
| real_test | 177.3 |
| generate | 24.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46948 |
| trojan | 15481 |
| vmess | 10140 |
| shadowsocks | 9929 |
| hysteria2 | 411 |
| shadowsocksr | 79 |
| socks | 58 |
| http | 51 |
| hysteria | 17 |
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
| 75.51 | vless | 171.9 | 452.2 | 23.8 | 0.0 | 10.0 | 4.19 | 18.52 | mheidari-all | 198.41.209.87 |
| 75.43 | vless | 175.4 | 446.1 | 23.72 | 0.0 | 10.0 | 4.19 | 18.52 | mheidari-all | 104.16.9.20 |
| 74.86 | trojan | 329.4 | 335.4 | 20.15 | 2.42 | 9.95 | 13.81 | 18.52 | mheidari-all | 95.85.94.90 |
| 74.84 | trojan | 326.6 | 673.2 | 20.22 | 0.0 | 10.0 | 13.81 | 18.52 | mheidari-all | 163.245.196.68 |
| 73.35 | trojan | 326.5 | 327.3 | 20.22 | 2.73 | 9.95 | 13.81 | 18.52 | mheidari-all | 31.223.184.149 |
| 73.29 | trojan | 325.0 | 327.8 | 20.25 | 2.71 | 9.92 | 13.81 | 18.52 | mheidari-all | 31.223.184.178 |
| 73.17 | trojan | 327.8 | 329.5 | 20.19 | 2.64 | 9.95 | 13.81 | 18.52 | mheidari-all | 31.223.184.43 |
| 72.99 | trojan | 326.2 | 336.7 | 20.23 | 2.37 | 9.94 | 13.81 | 18.52 | mheidari-all | 31.223.184.125 |
| 72.97 | trojan | 327.7 | 331.1 | 20.19 | 2.58 | 9.95 | 13.81 | 18.52 | mheidari-all | 31.223.184.238 |
| 72.02 | trojan | 351.4 | 407.6 | 19.64 | 0.0 | 9.94 | 13.81 | 18.52 | mheidari-all | 95.85.94.148 |
| 71.85 | vless | 289.9 | 718.8 | 21.07 | 0.0 | 10.0 | 4.19 | 18.52 | mheidari-all | 185.164.111.48 |
| 70.88 | trojan | 418.2 | 818.0 | 18.1 | 0.0 | 10.0 | 13.81 | 18.52 | mheidari-all | 153.75.250.171 |
| 70.41 | trojan | 351.3 | 387.1 | 19.65 | 0.48 | 9.93 | 13.81 | 18.52 | mheidari-all | 31.223.184.82 |
| 70.09 | trojan | 348.6 | 400.4 | 19.71 | 0.0 | 9.95 | 13.81 | 18.52 | mheidari-all | 95.85.94.165 |
| 69.84 | trojan | 354.6 | 404.0 | 19.57 | 0.0 | 9.91 | 13.81 | 18.52 | mheidari-all | 31.223.184.164 |
| 69.8 | trojan | 479.6 | 765.3 | 16.68 | 0.0 | 9.24 | 13.81 | 18.52 | mheidari-all | 91.107.145.13 |
| 69.79 | trojan | 329.3 | 336.9 | 20.16 | 2.36 | 9.93 | 13.81 | 18.52 | mheidari-all | 95.85.94.112 |
| 69.68 | trojan | 449.1 | 702.6 | 17.38 | 0.0 | 9.94 | 13.81 | 18.52 | mheidari-all | 95.85.94.199 |
| 69.67 | trojan | 385.2 | 389.4 | 18.86 | 0.4 | 10.0 | 13.81 | 16.4 | Surfboard-tg-mixed | 104.16.72.50 |
| 68.63 | trojan | 426.6 | 354.4 | 17.9 | 1.71 | 9.48 | 13.81 | 16.4 | Surfboard-tg-mixed | 119.246.1.143 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.719 | 0.639 | 771 | 19618 | prefer |
| Surfboard-tg-mixed | 0.554 | 0.474 | 114 | 5319 | observe |
| DeltaKronecker-all | 0.448 | 0.365 | 85 | 5559 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3847 | observe |
| Au1rxx-base64 | 0.329 | 1.0 | 2 | 432 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4588 | observe |
| Epodonios-all | 0.255 | None | 0 | 6546 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6796 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4227 | observe |
| barry-far-vless | 0.255 | None | 0 | 4836 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5027 | observe |
| nscl5-all | 0.255 | None | 0 | 3124 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 155 |
| speed | ClientOSError | - | 76 |
| geo | ClientOSError | - | 42 |
| cn-block | TimeoutError | - | 40 |
| speed | TimeoutError | - | 36 |
| 204 | ProxyError | - | 18 |
| 204 | TimeoutError | - | 13 |
| geo | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
