# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 17:00:01 |
| 运行耗时 | 489.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 97092 |
| 去重后节点 | 26416 |
| TCP 可达 | 3000 |
| 真实可用 | 381 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26416 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 43.5 |
| probe | 190.2 |
| real_test | 164.9 |
| generate | 82.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59649 |
| vmess | 14751 |
| shadowsocks | 11245 |
| trojan | 9033 |
| hysteria2 | 1569 |
| http | 551 |
| shadowsocksr | 173 |
| socks | 74 |
| anytls | 22 |
| hysteria | 18 |
| tuic | 7 |

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
| 78.55 | shadowsocks | 241.2 | 613.4 | 22.19 | 0.0 | 9.14 | 13.36 | 17.86 | Au1rxx-base64 | 156.146.38.167 |
| 75.24 | shadowsocks | 276.2 | 722.8 | 21.38 | 0.0 | 10.0 | 13.36 | 14.5 | Surfboard-tg-mixed | 156.146.38.169 |
| 72.59 | shadowsocks | 279.4 | 732.3 | 21.31 | 0.0 | 10.0 | 13.36 | 11.92 | mheidari-all | 156.146.38.170 |
| 72.5 | hysteria2 | 378.3 | 869.7 | 19.02 | 0.0 | 9.12 | 14.25 | 17.86 | Au1rxx-base64 | 159.223.157.129 |
| 71.85 | shadowsocks | 289.6 | 697.5 | 21.07 | 0.0 | 10.0 | 13.36 | 11.92 | mheidari-all | 23.150.248.20 |
| 71.45 | shadowsocks | 268.4 | 564.6 | 21.57 | 0.0 | 10.0 | 13.36 | 14.5 | Surfboard-tg-mixed | 173.244.56.6 |
| 71.21 | shadowsocks | 325.3 | 359.6 | 20.25 | 1.51 | 9.77 | 13.36 | 17.86 | Au1rxx-base64 | 149.22.87.240 |
| 71.12 | vless | 364.2 | 841.4 | 19.35 | 0.0 | 9.05 | 8.29 | 17.86 | Au1rxx-base64 | 195.211.98.43 |
| 70.64 | shadowsocks | 252.1 | 562.1 | 21.94 | 0.0 | 10.0 | 13.36 | 11.92 | mheidari-all | 192.3.247.109 |
| 70.62 | shadowsocks | 278.0 | 718.9 | 21.34 | 0.0 | 10.0 | 13.36 | 11.92 | mheidari-all | 156.146.38.168 |
| 70.57 | vless | 384.3 | 922.9 | 18.88 | 0.0 | 9.01 | 8.29 | 17.86 | Au1rxx-base64 | 172.235.43.210 |
| 70.36 | vless | 400.1 | 917.5 | 18.52 | 0.0 | 9.01 | 8.29 | 17.86 | Au1rxx-base64 | 198.251.78.29 |
| 70.28 | vless | 342.6 | 713.8 | 19.85 | 0.0 | 10.0 | 8.29 | 17.86 | Au1rxx-base64 | 195.123.235.177 |
| 70.07 | vless | 359.3 | 762.6 | 19.46 | 0.0 | 9.07 | 8.29 | 17.86 | Au1rxx-base64 | 23.132.28.51 |
| 70.05 | shadowsocks | 348.0 | 739.8 | 19.72 | 0.0 | 8.97 | 13.36 | 17.86 | Au1rxx-base64 | 108.181.57.93 |
| 69.58 | shadowsocks | 348.6 | 787.4 | 19.71 | 0.0 | 10.0 | 13.36 | 14.5 | Surfboard-tg-mixed | 37.19.198.243 |
| 69.55 | hysteria2 | 491.4 | 891.7 | 16.4 | 0.0 | 9.08 | 14.25 | 17.86 | Au1rxx-base64 | 66.94.121.46 |
| 69.41 | shadowsocks | 343.4 | 755.3 | 19.83 | 0.0 | 10.0 | 13.36 | 14.5 | Surfboard-tg-mixed | 108.181.0.177 |
| 69.31 | vless | 351.2 | 814.7 | 19.65 | 0.0 | 10.0 | 8.29 | 17.86 | Au1rxx-base64 | 192.3.247.109 |
| 68.97 | vless | 378.7 | 804.8 | 19.01 | 0.0 | 9.06 | 8.29 | 17.86 | Au1rxx-base64 | 66.70.179.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | 0.933 | 252 | 1697 | prefer |
| Surfboard-tg-mixed | 0.875 | 0.803 | 76 | 7421 | prefer |
| mheidari-all | 0.8 | 0.726 | 73 | 22258 | prefer |
| ermaozi | 0.669 | 0.667 | 33 | 298 | observe |
| DeltaKronecker-all | 0.519 | 1.0 | 5 | 5845 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 149 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5307 | observe |
| Epodonios-all | 0.255 | None | 0 | 7498 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9120 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5991 | observe |
| barry-far-vless | 0.255 | None | 0 | 5901 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4305 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 16 |
| 204 | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
