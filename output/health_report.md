# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-12 15:10:21 |
| 运行耗时 | 795.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 100392 |
| 去重后节点 | 27824 |
| TCP 可达 | 3000 |
| 真实可用 | 407 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27824 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.7 |
| tcp | 47.2 |
| probe | 291.1 |
| real_test | 361.2 |
| generate | 86.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58914 |
| vmess | 16072 |
| shadowsocks | 11789 |
| trojan | 11208 |
| hysteria2 | 1468 |
| http | 651 |
| shadowsocksr | 171 |
| socks | 70 |
| anytls | 26 |
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
| 86.41 | hysteria2 | 224.9 | 217.8 | 22.57 | 6.83 | 9.94 | 14.0 | 19.74 | Au1rxx-base64 | 45.32.10.7 |
| 85.31 | hysteria2 | 222.5 | 228.2 | 22.63 | 6.44 | 9.36 | 14.0 | 19.74 | Au1rxx-base64 | vp3.yysyy.online |
| 80.09 | vless | 177.0 | 460.3 | 23.68 | 0.0 | 10.0 | 6.67 | 19.74 | Au1rxx-base64 | 47.251.108.158 |
| 79.35 | vless | 209.0 | 526.9 | 22.94 | 0.0 | 10.0 | 6.67 | 19.74 | Au1rxx-base64 | 154.9.241.170 |
| 78.51 | shadowsocks | 273.9 | 284.3 | 21.44 | 4.34 | 9.94 | 14.2 | 19.74 | Au1rxx-base64 | 149.22.87.240 |
| 78.18 | shadowsocks | 286.8 | 645.7 | 21.14 | 0.0 | 10.0 | 14.2 | 19.74 | Au1rxx-base64 | 156.146.38.168 |
| 78.17 | shadowsocks | 289.6 | 656.4 | 21.07 | 0.0 | 10.0 | 14.2 | 19.74 | Au1rxx-base64 | 156.146.38.170 |
| 77.9 | shadowsocks | 297.0 | 668.1 | 20.9 | 0.0 | 10.0 | 14.2 | 19.74 | Au1rxx-base64 | 156.146.38.169 |
| 77.52 | shadowsocks | 312.2 | 710.3 | 20.55 | 0.0 | 10.0 | 14.2 | 19.74 | Au1rxx-base64 | 156.146.38.167 |
| 77.43 | shadowsocks | 252.2 | 548.5 | 21.94 | 0.0 | 10.0 | 14.2 | 19.74 | Au1rxx-base64 | 173.244.56.6 |
| 77.1 | vless | 306.2 | 825.7 | 20.69 | 0.0 | 10.0 | 6.67 | 19.74 | Au1rxx-base64 | 154.29.145.196 |
| 76.37 | trojan | 330.9 | 337.7 | 20.12 | 2.34 | 9.93 | 14.33 | 19.74 | Au1rxx-base64 | 52.194.251.232 |
| 76.26 | trojan | 326.5 | 334.5 | 20.22 | 2.46 | 9.94 | 14.33 | 19.74 | Au1rxx-base64 | 45.32.52.173 |
| 75.8 | trojan | 338.1 | 333.4 | 19.95 | 2.5 | 9.39 | 14.33 | 19.74 | Au1rxx-base64 | legible-ram.rooster465.autos |
| 75.7 | trojan | 335.0 | 336.8 | 20.02 | 2.37 | 9.4 | 14.33 | 19.74 | Au1rxx-base64 | warm-krill.rooster465.autos |
| 75.43 | vless | 272.0 | 635.5 | 21.48 | 0.0 | 9.5 | 6.67 | 19.74 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 75.37 | trojan | 336.6 | 343.9 | 19.99 | 2.1 | 9.38 | 14.33 | 19.74 | Au1rxx-base64 | stable-python.rooster465.autos |
| 75.28 | trojan | 333.9 | 346.7 | 20.05 | 2.0 | 9.38 | 14.33 | 19.74 | Au1rxx-base64 | live-stallion.rooster465.autos |
| 74.35 | trojan | 335.2 | 347.5 | 20.02 | 1.97 | 9.38 | 14.33 | 19.74 | Au1rxx-base64 | allowed-poodle.rooster465.autos |
| 74.23 | trojan | 442.2 | 281.3 | 17.54 | 4.45 | 9.05 | 14.33 | 19.74 | Au1rxx-base64 | prime-corgi.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | 0.912 | 318 | 1816 | prefer |
| mheidari-all | 0.788 | 0.727 | 22 | 24027 | prefer |
| Surfboard-tg-mixed | 0.747 | 0.671 | 70 | 7166 | prefer |
| DeltaKronecker-all | 0.571 | 0.49 | 51 | 5701 | observe |
| ermaozi | 0.518 | 0.49 | 51 | 675 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4314 | observe |
| ermaozi-get_subscribe | 0.333 | 1.0 | 2 | 532 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5028 | observe |
| Epodonios-all | 0.255 | None | 0 | 7671 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9940 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5781 | observe |
| barry-far-vless | 0.255 | None | 0 | 6031 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 26 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 16 |
| speed | TimeoutError | - | 12 |
| 204 | ProxyConnectionError | - | 7 |
| geo | ClientOSError | - | 7 |
| geo | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| speed | ClientOSError | - | 6 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:38306: bind: address already in use | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
