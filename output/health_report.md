# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-26 13:44:47 |
| 运行耗时 | 312.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81669 |
| 去重后节点 | 22638 |
| TCP 可达 | 3000 |
| 真实可用 | 726 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22638 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.3 |
| tcp | 32.0 |
| probe | 67.6 |
| real_test | 160.9 |
| generate | 44.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46079 |
| trojan | 14771 |
| vmess | 10094 |
| shadowsocks | 9962 |
| hysteria2 | 498 |
| http | 84 |
| shadowsocksr | 77 |
| socks | 69 |
| hysteria | 15 |
| anytls | 12 |
| tuic | 8 |

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
| 79.81 | shadowsocks | 202.6 | 538.2 | 23.09 | 0.0 | 10.0 | 12.1 | 18.62 | Au1rxx-base64 | 149.22.95.183 |
| 77.25 | shadowsocks | 256.7 | 530.0 | 21.84 | 0.0 | 10.0 | 12.1 | 18.62 | Au1rxx-base64 | 108.181.118.10 |
| 75.96 | shadowsocks | 237.8 | 507.5 | 22.27 | 0.0 | 10.0 | 12.1 | 18.62 | Au1rxx-base64 | 108.181.0.177 |
| 75.82 | trojan | 306.8 | 315.9 | 20.68 | 3.15 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 95.85.94.148 |
| 75.81 | trojan | 308.4 | 314.9 | 20.64 | 3.19 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 95.85.94.165 |
| 75.8 | trojan | 308.4 | 315.9 | 20.64 | 3.15 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 95.85.94.112 |
| 75.77 | trojan | 305.9 | 317.5 | 20.7 | 3.1 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 31.223.184.43 |
| 75.4 | trojan | 309.0 | 321.2 | 20.63 | 2.96 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 31.223.184.149 |
| 75.27 | trojan | 311.1 | 319.3 | 20.58 | 3.03 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 95.85.94.51 |
| 74.92 | trojan | 320.1 | 321.7 | 20.37 | 2.93 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 95.85.94.17 |
| 73.88 | trojan | 331.0 | 680.1 | 20.12 | 0.0 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 64.94.95.118 |
| 73.86 | shadowsocks | 278.9 | 325.9 | 21.32 | 2.78 | 10.0 | 12.1 | 18.62 | Au1rxx-base64 | 149.22.87.240 |
| 73.79 | trojan | 307.5 | 315.9 | 20.66 | 3.15 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 31.223.184.218 |
| 73.79 | trojan | 332.2 | 670.8 | 20.09 | 0.0 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 163.245.196.68 |
| 73.03 | trojan | 320.8 | 351.7 | 20.35 | 1.81 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 95.85.94.185 |
| 72.83 | trojan | 328.9 | 379.7 | 20.16 | 0.76 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 31.223.184.164 |
| 72.69 | trojan | 307.1 | 318.3 | 20.67 | 3.07 | 10.0 | 13.07 | 18.62 | Au1rxx-base64 | 31.223.184.249 |
| 72.52 | trojan | 310.3 | 317.9 | 20.59 | 3.08 | 9.88 | 13.07 | 18.62 | Au1rxx-base64 | 31.223.184.58 |
| 72.42 | vless | 220.2 | 502.2 | 22.68 | 0.0 | 10.0 | 6.3 | 18.62 | Au1rxx-base64 | 173.249.200.68 |
| 72.37 | shadowsocks | 319.2 | 683.6 | 20.39 | 0.0 | 10.0 | 12.1 | 18.62 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | 0.939 | 458 | 1458 | prefer |
| zhangkai | 0.991 | 1.0 | 76 | 86 | prefer |
| DeltaKronecker-all | 0.717 | 0.639 | 144 | 5950 | prefer |
| mheidari-all | 0.549 | 0.469 | 209 | 17236 | observe |
| tg-oneclickvpnkeys | 0.519 | 1.0 | 7 | 149 | observe |
| Surfboard-tg-mixed | 0.434 | 0.349 | 63 | 5591 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 6731 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6620 | observe |
| barry-far-vless | 0.255 | None | 0 | 5039 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4980 | observe |
| nscl5-all | 0.255 | None | 0 | 2896 | observe |
| xiaoji235-airport-v2ray-all | 0.24 | None | 0 | 1624 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 80 |
| speed | ClientOSError | - | 41 |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 23 |
| cn-block | ClientOSError | - | 18 |
| geo | ClientOSError | - | 17 |
| speed | TimeoutError | - | 10 |
| 204 | ProxyError | - | 8 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 5 |
| speed | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
