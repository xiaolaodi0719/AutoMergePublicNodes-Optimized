# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 15:28:24 |
| 运行耗时 | 556.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83067 |
| 去重后节点 | 22816 |
| TCP 可达 | 3000 |
| 真实可用 | 428 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22816 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.9 |
| geo | 1.4 |
| tcp | 38.3 |
| probe | 201.8 |
| real_test | 228.0 |
| generate | 76.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50552 |
| vmess | 12589 |
| shadowsocks | 9742 |
| trojan | 7933 |
| hysteria2 | 1468 |
| http | 580 |
| shadowsocksr | 129 |
| socks | 56 |
| hysteria | 9 |
| tuic | 8 |
| anytls | 1 |

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
| 81.56 | vless | 216.1 | 536.6 | 22.77 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 172.233.139.46 |
| 81.5 | vless | 219.0 | 521.8 | 22.71 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 172.235.38.85 |
| 80.49 | vless | 254.4 | 526.7 | 21.89 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 31.58.50.200 |
| 80.34 | vless | 269.0 | 633.4 | 21.55 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 216.36.124.176 |
| 80.31 | vless | 270.4 | 693.7 | 21.52 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 172.235.43.210 |
| 79.6 | shadowsocks | 287.7 | 745.6 | 21.12 | 0.0 | 10.0 | 13.94 | 18.54 | Au1rxx-base64 | 173.244.56.6 |
| 78.95 | shadowsocks | 315.6 | 798.3 | 20.47 | 0.0 | 10.0 | 13.94 | 18.54 | Au1rxx-base64 | 156.146.38.169 |
| 76.43 | vless | 258.7 | 535.1 | 21.79 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 144.172.104.26 |
| 75.62 | vless | 278.4 | 524.2 | 21.33 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 162.159.39.218 |
| 75.58 | vless | 388.7 | 954.8 | 18.78 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 15.204.97.216 |
| 75.46 | shadowsocks | 294.9 | 648.2 | 20.95 | 0.0 | 10.0 | 13.94 | 18.54 | Au1rxx-base64 | 149.22.95.183 |
| 74.92 | shadowsocks | 288.5 | 718.4 | 21.1 | 0.0 | 10.0 | 13.94 | 13.88 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.54 | vless | 218.0 | 504.0 | 22.73 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 104.21.70.21 |
| 73.49 | shadowsocks | 511.8 | 1392.6 | 15.93 | 0.0 | 10.0 | 13.94 | 18.54 | Au1rxx-base64 | 156.146.38.170 |
| 73.29 | shadowsocks | 347.0 | 742.9 | 19.74 | 0.0 | 10.0 | 13.94 | 18.54 | Au1rxx-base64 | 37.19.198.243 |
| 73.27 | vless | 344.2 | 335.9 | 19.81 | 2.4 | 9.9 | 10.25 | 18.54 | Au1rxx-base64 | 154.31.114.248 |
| 73.05 | vless | 340.3 | 343.9 | 19.9 | 2.1 | 9.9 | 10.25 | 18.54 | Au1rxx-base64 | 156.231.113.153 |
| 72.58 | vless | 379.0 | 780.1 | 19.0 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 47.89.186.170 |
| 72.16 | vless | 387.8 | 793.9 | 18.8 | 0.0 | 10.0 | 10.25 | 18.54 | Au1rxx-base64 | 137.184.218.169 |
| 72.09 | shadowsocks | 328.3 | 752.1 | 20.18 | 0.0 | 10.0 | 13.94 | 13.88 | Surfboard-tg-mixed | 23.150.248.20 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.928 | 0.872 | 297 | 1455 | prefer |
| Surfboard-tg-mixed | 0.718 | 0.64 | 114 | 7345 | prefer |
| mheidari-all | 0.619 | 0.541 | 74 | 15620 | observe |
| ermaozi | 0.556 | 0.543 | 35 | 393 | observe |
| DeltaKronecker-all | 0.543 | 0.462 | 65 | 5970 | observe |
| ermaozi-get_subscribe | 0.465 | 0.857 | 7 | 408 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4793 | observe |
| Epodonios-all | 0.255 | None | 0 | 7743 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8959 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5912 | observe |
| barry-far-vless | 0.255 | None | 0 | 6112 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4207 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 63 |
| 204 | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 15 |
| speed | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| 204 | ProxyError | - | 13 |
| 204 | ProxyConnectionError | - | 12 |
| 204 | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| geo | TimeoutError | - | 4 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46410: bind: address already in use | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
