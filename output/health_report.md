# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 21:21:21 |
| 运行耗时 | 746.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99754 |
| 去重后节点 | 27713 |
| TCP 可达 | 3000 |
| 真实可用 | 420 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27713 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.5 |
| tcp | 47.9 |
| probe | 302.6 |
| real_test | 301.8 |
| generate | 87.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58733 |
| vmess | 16542 |
| shadowsocks | 11941 |
| trojan | 10415 |
| hysteria2 | 1206 |
| http | 649 |
| shadowsocksr | 161 |
| socks | 57 |
| anytls | 27 |
| hysteria | 17 |
| tuic | 6 |

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
| 77.47 | hysteria2 | 296.3 | 724.2 | 20.92 | 0.0 | 10.0 | 12.19 | 15.86 | Au1rxx-base64 | 129.213.91.185 |
| 76.14 | vless | 265.5 | 658.8 | 21.63 | 0.0 | 10.0 | 8.65 | 15.86 | Au1rxx-base64 | 147.45.60.160 |
| 73.51 | shadowsocks | 251.4 | 636.2 | 21.96 | 0.0 | 10.0 | 11.69 | 15.86 | Au1rxx-base64 | 156.146.38.167 |
| 73.02 | shadowsocks | 304.8 | 740.1 | 20.72 | 0.0 | 10.0 | 11.69 | 15.86 | Au1rxx-base64 | 37.19.198.236 |
| 72.64 | shadowsocks | 307.6 | 750.1 | 20.66 | 0.0 | 10.0 | 11.69 | 15.86 | Au1rxx-base64 | 37.19.198.160 |
| 72.42 | shadowsocks | 311.7 | 752.5 | 20.56 | 0.0 | 10.0 | 11.69 | 15.86 | Au1rxx-base64 | 37.19.198.244 |
| 72.23 | shadowsocks | 303.8 | 742.5 | 20.75 | 0.0 | 10.0 | 11.69 | 15.86 | Au1rxx-base64 | 37.19.198.243 |
| 71.44 | shadowsocks | 290.5 | 749.5 | 21.05 | 0.0 | 10.0 | 11.69 | 15.86 | Au1rxx-base64 | 156.146.38.168 |
| 71.36 | vless | 433.1 | 1072.8 | 17.75 | 0.0 | 10.0 | 8.65 | 15.86 | Au1rxx-base64 | 185.95.231.156 |
| 71.34 | vless | 278.4 | 649.7 | 21.33 | 0.0 | 10.0 | 8.65 | 15.86 | Au1rxx-base64 | 69.48.201.136 |
| 71.16 | vless | 306.1 | 674.8 | 20.69 | 0.0 | 10.0 | 8.65 | 15.86 | Au1rxx-base64 | 195.123.235.183 |
| 70.95 | hysteria2 | 279.9 | 272.2 | 21.3 | 4.79 | 9.58 | 12.19 | 15.86 | Au1rxx-base64 | 8.209.247.109 |
| 70.71 | vless | 342.1 | 790.0 | 19.86 | 0.0 | 10.0 | 8.65 | 15.86 | Au1rxx-base64 | 66.70.179.198 |
| 70.58 | shadowsocks | 248.3 | 630.4 | 22.03 | 0.0 | 10.0 | 11.69 | 15.86 | Au1rxx-base64 | 156.146.38.170 |
| 70.53 | vless | 334.9 | 724.0 | 20.03 | 0.0 | 10.0 | 8.65 | 15.86 | Au1rxx-base64 | 167.17.69.171 |
| 69.32 | vless | 298.3 | 657.2 | 20.87 | 0.0 | 7.1 | 8.65 | 15.86 | Au1rxx-base64 | freeus.aiage.work |
| 69.3 | vless | 273.4 | 640.6 | 21.45 | 0.0 | 10.0 | 8.65 | 15.86 | Au1rxx-base64 | 195.211.98.43 |
| 69.0 | shadowsocks | 306.5 | 625.3 | 20.68 | 0.0 | 10.0 | 11.69 | 15.86 | Au1rxx-base64 | 149.22.95.183 |
| 68.87 | vless | 356.5 | 898.1 | 19.53 | 0.0 | 9.33 | 8.65 | 15.86 | Au1rxx-base64 | uspanel.unixzone.us |
| 68.5 | vless | 430.0 | 1048.9 | 17.82 | 0.0 | 10.0 | 8.65 | 15.86 | Au1rxx-base64 | 159.89.87.21 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.853 | 0.781 | 461 | 1827 | prefer |
| Surfboard-tg-mixed | 0.572 | 0.491 | 57 | 7166 | observe |
| mheidari-all | 0.465 | 0.714 | 7 | 24072 | observe |
| ermaozi | 0.371 | 0.339 | 59 | 659 | observe |
| DeltaKronecker-all | 0.337 | 0.308 | 13 | 5147 | observe |
| ermaozi-get_subscribe | 0.332 | 1.0 | 2 | 519 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 89 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| Epodonios-all | 0.255 | None | 0 | 7793 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9885 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5707 | observe |
| barry-far-vless | 0.255 | None | 0 | 5957 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4235 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 52 |
| 204 | TimeoutError | - | 41 |
| cn-block | TimeoutError | - | 19 |
| speed | ClientOSError | - | 17 |
| geo | ClientOSError | - | 15 |
| cn-block | ClientOSError | - | 11 |
| geo | TimeoutError | - | 7 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 6 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| cn-block | status | 530 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
