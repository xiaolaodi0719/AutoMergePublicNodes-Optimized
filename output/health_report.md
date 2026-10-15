# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 11:23:22 |
| 运行耗时 | 851.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99769 |
| 去重后节点 | 27811 |
| TCP 可达 | 3000 |
| 真实可用 | 408 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27811 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 17.9 |
| geo | 1.5 |
| tcp | 48.5 |
| probe | 406.1 |
| real_test | 293.9 |
| generate | 84.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58918 |
| vmess | 16422 |
| shadowsocks | 12082 |
| trojan | 10184 |
| hysteria2 | 1166 |
| http | 706 |
| shadowsocksr | 170 |
| socks | 66 |
| anytls | 32 |
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
| 82.38 | shadowsocks | 214.5 | 532.0 | 22.81 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 173.244.56.9 |
| 82.35 | shadowsocks | 215.9 | 536.4 | 22.78 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 173.244.56.6 |
| 81.24 | shadowsocks | 263.7 | 647.0 | 21.67 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 156.146.38.170 |
| 80.2 | shadowsocks | 287.3 | 439.6 | 21.13 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 103.11.76.248 |
| 78.48 | hysteria2 | 326.7 | 756.3 | 20.21 | 0.0 | 10.0 | 12.27 | 19.9 | Au1rxx-base64 | 129.213.91.185 |
| 77.59 | shadowsocks | 184.0 | 485.6 | 23.52 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 64.110.25.6 |
| 76.8 | shadowsocks | 290.8 | 640.5 | 21.05 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 149.22.95.183 |
| 76.75 | shadowsocks | 220.1 | 599.0 | 22.68 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 103.214.109.45 |
| 76.36 | shadowsocks | 258.6 | 621.9 | 21.79 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 156.146.38.168 |
| 76.32 | shadowsocks | 260.5 | 636.7 | 21.75 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 156.146.38.167 |
| 76.3 | trojan | 340.0 | 860.4 | 19.91 | 0.0 | 10.0 | 12.61 | 19.9 | Au1rxx-base64 | 107.149.159.190 |
| 75.45 | shadowsocks | 298.1 | 745.9 | 20.88 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 156.146.38.169 |
| 75.38 | trojan | 387.3 | 288.9 | 18.81 | 4.17 | 9.91 | 12.61 | 19.9 | Au1rxx-base64 | 108.61.186.37 |
| 75.11 | shadowsocks | 301.3 | 338.5 | 20.8 | 2.31 | 9.9 | 13.67 | 19.9 | Au1rxx-base64 | 149.22.87.241 |
| 74.65 | shadowsocks | 305.4 | 354.4 | 20.71 | 1.71 | 9.9 | 13.67 | 19.9 | Au1rxx-base64 | 149.22.87.204 |
| 74.26 | shadowsocks | 365.4 | 793.4 | 19.32 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 37.19.198.236 |
| 74.14 | shadowsocks | 366.6 | 794.3 | 19.29 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 37.19.198.244 |
| 74.06 | shadowsocks | 366.0 | 801.3 | 19.31 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 37.19.198.160 |
| 73.87 | shadowsocks | 369.5 | 805.4 | 19.22 | 0.0 | 10.0 | 13.67 | 19.9 | Au1rxx-base64 | 37.19.198.243 |
| 72.92 | trojan | 368.6 | 877.1 | 19.25 | 0.0 | 10.0 | 12.61 | 19.9 | Au1rxx-base64 | 66.23.203.21 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.848 | 0.778 | 451 | 1769 | prefer |
| ermaozi | 0.452 | 0.422 | 83 | 703 | observe |
| Surfboard-tg-mixed | 0.418 | 0.5 | 10 | 7139 | observe |
| DeltaKronecker-all | 0.413 | 0.324 | 34 | 5147 | observe |
| ermaozi-get_subscribe | 0.335 | 1.0 | 2 | 595 | observe |
| mheidari-all | 0.324 | 0.375 | 8 | 24005 | observe |
| peasoft-NoMoreWalls | 0.261 | 1.0 | 1 | 147 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| Epodonios-all | 0.255 | None | 0 | 7652 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10113 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5693 | observe |
| barry-far-vless | 0.255 | None | 0 | 5924 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 46 |
| 204 | TimeoutError | - | 45 |
| cn-block | TimeoutError | - | 20 |
| geo | ClientOSError | - | 13 |
| geo | TimeoutError | - | 12 |
| speed | ClientOSError | - | 12 |
| speed | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 10 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 233 | 300 | - |
| global | False | 240 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
