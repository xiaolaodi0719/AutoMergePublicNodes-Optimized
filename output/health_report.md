# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 16:08:57 |
| 运行耗时 | 518.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99539 |
| 去重后节点 | 27335 |
| TCP 可达 | 3000 |
| 真实可用 | 350 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27335 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 0.9 |
| tcp | 47.7 |
| probe | 211.8 |
| real_test | 148.2 |
| generate | 101.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60961 |
| vmess | 15421 |
| shadowsocks | 11437 |
| trojan | 9371 |
| hysteria2 | 1544 |
| http | 521 |
| shadowsocksr | 170 |
| socks | 65 |
| anytls | 24 |
| hysteria | 17 |
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
| 79.92 | vless | 352.6 | 863.5 | 19.62 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 137.184.218.169 |
| 79.44 | vless | 266.2 | 681.3 | 21.62 | 0.0 | 7.52 | 11.54 | 18.76 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 79.14 | shadowsocks | 265.5 | 722.2 | 21.63 | 0.0 | 10.0 | 12.75 | 18.76 | Au1rxx-base64 | 37.19.198.160 |
| 78.88 | hysteria2 | 251.2 | 677.0 | 21.96 | 0.0 | 10.0 | 11.84 | 16.18 | mheidari-all | 159.223.157.129 |
| 77.78 | vless | 359.7 | 913.0 | 19.45 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 169.40.42.90 |
| 77.04 | hysteria2 | 287.9 | 580.8 | 21.11 | 0.0 | 10.0 | 11.84 | 18.76 | Au1rxx-base64 | 192.255.128.123 |
| 76.13 | shadowsocks | 309.1 | 853.9 | 20.62 | 0.0 | 10.0 | 12.75 | 18.76 | Au1rxx-base64 | 37.19.198.236 |
| 75.68 | vless | 503.3 | 1356.5 | 16.13 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 66.70.179.198 |
| 74.82 | vless | 334.0 | 629.6 | 20.05 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 172.235.43.210 |
| 74.62 | vless | 333.9 | 635.9 | 20.05 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 172.235.38.85 |
| 74.48 | vless | 270.6 | 703.1 | 21.51 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 195.123.235.177 |
| 74.3 | vless | 348.5 | 678.7 | 19.71 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 172.233.139.46 |
| 74.08 | shadowsocks | 351.2 | 920.0 | 19.65 | 0.0 | 10.0 | 12.75 | 16.18 | mheidari-all | 15.204.247.206 |
| 74.03 | vless | 423.8 | 980.1 | 17.97 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 169.40.42.168 |
| 73.95 | vless | 517.4 | 1290.4 | 15.8 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 198.251.78.29 |
| 73.92 | shadowsocks | 278.5 | 647.6 | 21.33 | 0.0 | 10.0 | 12.75 | 16.18 | mheidari-all | 156.146.38.168 |
| 73.72 | vless | 328.9 | 880.6 | 20.16 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 159.89.87.21 |
| 73.39 | vless | 381.1 | 931.5 | 18.96 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 209.200.246.148 |
| 72.76 | vless | 387.7 | 705.1 | 18.8 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 15.204.97.216 |
| 72.5 | vless | 310.7 | 804.1 | 20.58 | 0.0 | 10.0 | 11.54 | 18.76 | Au1rxx-base64 | 169.40.42.231 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | 0.866 | 261 | 1778 | prefer |
| mheidari-all | 0.868 | 0.8 | 50 | 23342 | prefer |
| Surfboard-tg-mixed | 0.781 | 0.705 | 95 | 7404 | prefer |
| ermaozi | 0.706 | 0.696 | 23 | 656 | prefer |
| ermaozi-get_subscribe | 0.274 | 1.0 | 1 | 478 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5192 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 5207 | observe |
| Epodonios-all | 0.255 | None | 0 | 7883 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9374 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6035 | observe |
| barry-far-vless | 0.255 | None | 0 | 6273 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4335 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyConnectionError | - | 11 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| speed | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
