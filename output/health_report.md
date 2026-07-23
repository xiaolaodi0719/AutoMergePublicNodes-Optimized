# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-23 08:44:10 |
| 运行耗时 | 384.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83067 |
| 去重后节点 | 22726 |
| TCP 可达 | 3000 |
| 真实可用 | 861 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22726 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.5 |
| tcp | 32.0 |
| probe | 75.6 |
| real_test | 227.9 |
| generate | 42.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47778 |
| trojan | 14017 |
| shadowsocks | 10471 |
| vmess | 10181 |
| hysteria2 | 421 |
| shadowsocksr | 72 |
| http | 50 |
| socks | 43 |
| tuic | 17 |
| hysteria | 14 |
| anytls | 3 |

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
| 78.85 | shadowsocks | 250.3 | 625.2 | 21.98 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 198.98.53.130 |
| 78.75 | shadowsocks | 254.9 | 637.2 | 21.88 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 156.146.38.168 |
| 78.42 | shadowsocks | 269.2 | 678.8 | 21.55 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 37.19.198.160 |
| 78.33 | shadowsocks | 259.9 | 638.7 | 21.76 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 156.146.38.169 |
| 78.19 | shadowsocks | 279.0 | 699.7 | 21.32 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 37.19.198.243 |
| 77.9 | shadowsocks | 248.1 | 608.0 | 22.03 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 156.146.38.167 |
| 77.9 | shadowsocks | 271.1 | 675.1 | 21.5 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 37.19.198.236 |
| 76.89 | shadowsocks | 313.4 | 803.0 | 20.52 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 185.196.61.82 |
| 74.91 | shadowsocks | 398.9 | 1043.0 | 18.54 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 68.168.222.210 |
| 74.57 | trojan | 433.0 | 1106.0 | 17.75 | 0.0 | 10.0 | 13.75 | 17.16 | Au1rxx-base64 | 64.94.95.118 |
| 73.09 | shadowsocks | 293.2 | 560.5 | 20.99 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 173.244.56.6 |
| 73.0 | shadowsocks | 327.3 | 710.1 | 20.2 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 108.181.57.93 |
| 72.96 | shadowsocks | 289.0 | 716.4 | 21.09 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 37.19.198.244 |
| 72.67 | shadowsocks | 303.7 | 584.8 | 20.75 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 108.181.0.177 |
| 72.05 | trojan | 278.1 | 633.1 | 21.34 | 0.0 | 10.0 | 13.75 | 12.76 | mheidari-all | 163.245.196.68 |
| 71.96 | shadowsocks | 299.6 | 585.4 | 20.84 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 108.181.118.10 |
| 71.52 | trojan | 429.7 | 1097.2 | 17.83 | 0.0 | 10.0 | 13.75 | 13.54 | DeltaKronecker-all | 64.74.163.118 |
| 71.3 | shadowsocks | 328.9 | 708.6 | 20.16 | 0.0 | 10.0 | 13.71 | 17.16 | Au1rxx-base64 | 149.22.95.183 |
| 70.61 | trojan | 360.8 | 623.7 | 19.43 | 0.0 | 10.0 | 13.75 | 17.16 | Au1rxx-base64 | 35.90.87.253 |
| 70.46 | hysteria2 | 406.6 | 764.8 | 18.37 | 0.0 | 9.9 | 12.5 | 17.16 | Au1rxx-base64 | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.917 | 0.845 | 84 | 5330 | prefer |
| mheidari-all | 0.877 | 0.799 | 398 | 19639 | prefer |
| Au1rxx-base64 | 0.654 | 0.638 | 188 | 432 | observe |
| DeltaKronecker-all | 0.515 | 0.435 | 717 | 5572 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 4399 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4757 | observe |
| Epodonios-all | 0.255 | None | 0 | 6489 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3968 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6912 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4154 | observe |
| barry-far-vless | 0.255 | None | 0 | 4690 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4954 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 215 |
| speed | ClientOSError | - | 124 |
| cn-block | TimeoutError | - | 85 |
| geo | ClientOSError | - | 50 |
| 204 | ProxyError | - | 24 |
| 204 | TimeoutError | - | 23 |
| speed | TimeoutError | - | 22 |
| cn-block | ClientOSError | - | 6 |
| speed | ProxyError | - | 6 |
| geo | ProxyError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
