# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-24 19:41:22 |
| 运行耗时 | 298.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83183 |
| 去重后节点 | 22837 |
| TCP 可达 | 3000 |
| 真实可用 | 529 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22837 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.4 |
| tcp | 33.2 |
| probe | 69.1 |
| real_test | 161.4 |
| generate | 29.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47164 |
| trojan | 15150 |
| vmess | 10276 |
| shadowsocks | 9965 |
| hysteria2 | 396 |
| socks | 79 |
| shadowsocksr | 76 |
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
| 75.88 | vless | 208.5 | 524.9 | 22.95 | 0.0 | 10.0 | 5.87 | 17.06 | DeltaKronecker-all | 167.17.68.205 |
| 75.02 | vless | 202.6 | 480.8 | 23.09 | 0.0 | 10.0 | 5.87 | 17.06 | DeltaKronecker-all | 172.67.209.126 |
| 73.86 | vless | 252.4 | 612.4 | 21.93 | 0.0 | 10.0 | 5.87 | 17.06 | DeltaKronecker-all | 104.17.90.246 |
| 73.08 | trojan | 306.2 | 657.5 | 20.69 | 0.0 | 10.0 | 13.73 | 16.16 | mheidari-all | 163.245.196.68 |
| 71.99 | trojan | 342.8 | 336.4 | 19.84 | 2.38 | 9.85 | 13.73 | 16.16 | mheidari-all | 31.223.184.125 |
| 71.88 | trojan | 336.4 | 338.2 | 19.99 | 2.32 | 9.79 | 13.73 | 16.16 | mheidari-all | 31.223.184.238 |
| 71.79 | trojan | 339.2 | 341.3 | 19.93 | 2.2 | 9.8 | 13.73 | 16.16 | mheidari-all | 31.223.184.178 |
| 71.74 | trojan | 342.1 | 341.9 | 19.86 | 2.18 | 9.82 | 13.73 | 16.16 | mheidari-all | 95.85.94.148 |
| 71.65 | trojan | 340.3 | 347.1 | 19.9 | 1.99 | 9.83 | 13.73 | 16.16 | mheidari-all | 31.223.184.82 |
| 71.57 | vless | 248.1 | 613.9 | 22.03 | 0.0 | 10.0 | 5.87 | 17.06 | DeltaKronecker-all | 104.25.161.29 |
| 71.3 | trojan | 342.9 | 355.3 | 19.84 | 1.67 | 9.84 | 13.73 | 16.16 | mheidari-all | 31.223.184.149 |
| 70.58 | vless | 398.4 | 1134.6 | 18.55 | 0.0 | 10.0 | 5.87 | 16.16 | mheidari-all | 185.164.111.48 |
| 69.03 | trojan | 366.8 | 437.4 | 19.29 | 0.0 | 9.85 | 13.73 | 16.16 | mheidari-all | 95.85.94.90 |
| 68.92 | trojan | 356.4 | 353.7 | 19.53 | 1.74 | 9.78 | 13.73 | 16.16 | mheidari-all | 31.223.184.109 |
| 68.85 | trojan | 374.5 | 418.8 | 19.11 | 0.0 | 9.84 | 13.73 | 16.16 | mheidari-all | 31.223.184.164 |
| 68.17 | trojan | 349.3 | 379.6 | 19.69 | 0.76 | 9.82 | 13.73 | 16.16 | mheidari-all | 95.85.94.112 |
| 68.06 | trojan | 342.3 | 332.0 | 19.85 | 2.55 | 9.84 | 13.73 | 17.06 | DeltaKronecker-all | 95.85.94.51 |
| 67.95 | trojan | 432.2 | 824.3 | 17.77 | 0.0 | 10.0 | 13.73 | 16.16 | mheidari-all | 153.75.250.171 |
| 67.9 | vless | 189.4 | 458.0 | 23.39 | 0.0 | 10.0 | 5.87 | 17.06 | DeltaKronecker-all | 92.223.71.246 |
| 67.88 | trojan | 340.9 | 335.8 | 19.89 | 2.41 | 9.78 | 13.73 | 17.06 | DeltaKronecker-all | 31.223.184.58 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.935 | 0.857 | 280 | 19355 | prefer |
| Surfboard-tg-mixed | 0.888 | 0.814 | 97 | 5475 | prefer |
| DeltaKronecker-all | 0.426 | 0.346 | 489 | 5559 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 3847 | observe |
| Au1rxx-base64 | 0.329 | 1.0 | 2 | 432 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4588 | observe |
| Epodonios-all | 0.255 | None | 0 | 6668 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3967 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6766 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4271 | observe |
| barry-far-vless | 0.255 | None | 0 | 4905 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5027 | observe |
| nscl5-all | 0.255 | None | 0 | 3124 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 161 |
| geo | TimeoutError | - | 74 |
| 204 | ProxyError | - | 37 |
| cn-block | TimeoutError | - | 36 |
| geo | ClientOSError | - | 26 |
| 204 | TimeoutError | - | 21 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| geo | ProxyError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
