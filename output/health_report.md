# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 11:31:12 |
| 运行耗时 | 646.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 86889 |
| 去重后节点 | 24176 |
| TCP 可达 | 3000 |
| 真实可用 | 440 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24176 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 41.3 |
| probe | 275.4 |
| real_test | 246.5 |
| generate | 77.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51540 |
| vmess | 14007 |
| shadowsocks | 10463 |
| trojan | 8663 |
| hysteria2 | 1383 |
| http | 627 |
| shadowsocksr | 120 |
| socks | 74 |
| hysteria | 8 |
| tuic | 2 |
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
| 80.33 | shadowsocks | 249.6 | 628.9 | 22.0 | 0.0 | 10.0 | 13.55 | 18.78 | Au1rxx-base64 | 156.146.38.169 |
| 79.29 | hysteria2 | 269.8 | 600.9 | 21.53 | 0.0 | 10.0 | 12.69 | 18.78 | Au1rxx-base64 | 66.94.121.46 |
| 78.25 | vless | 286.1 | 718.5 | 21.15 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 79.141.172.154 |
| 76.52 | vless | 251.7 | 638.6 | 21.95 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 38.180.242.205 |
| 75.37 | hysteria2 | 292.3 | 696.4 | 21.01 | 0.0 | 10.0 | 12.69 | 18.78 | Au1rxx-base64 | 159.223.157.129 |
| 75.22 | shadowsocks | 265.9 | 569.8 | 21.62 | 0.0 | 10.0 | 13.55 | 18.78 | Au1rxx-base64 | 5.78.51.123 |
| 75.22 | shadowsocks | 383.3 | 964.4 | 18.91 | 0.0 | 10.0 | 13.55 | 18.78 | Au1rxx-base64 | 37.19.198.244 |
| 74.88 | shadowsocks | 282.9 | 755.2 | 21.23 | 0.0 | 10.0 | 13.55 | 14.26 | Surfboard-tg-mixed | 156.146.38.168 |
| 73.74 | shadowsocks | 327.6 | 772.8 | 20.2 | 0.0 | 10.0 | 13.55 | 18.78 | Au1rxx-base64 | 38.180.135.156 |
| 73.68 | hysteria2 | 265.3 | 592.8 | 21.64 | 0.0 | 10.0 | 12.69 | 18.78 | Au1rxx-base64 | 108.59.244.158 |
| 73.21 | vless | 379.4 | 873.9 | 19.0 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 137.184.218.169 |
| 73.13 | vless | 378.7 | 889.4 | 19.01 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 169.40.42.184 |
| 72.98 | vless | 312.8 | 753.1 | 20.54 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 47.253.226.114 |
| 72.82 | vless | 395.6 | 917.5 | 18.62 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 66.70.179.198 |
| 72.48 | shadowsocks | 259.8 | 654.0 | 21.76 | 0.0 | 10.0 | 13.55 | 14.26 | Surfboard-tg-mixed | 156.146.38.167 |
| 72.2 | vless | 430.7 | 901.7 | 17.81 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 169.40.42.35 |
| 72.07 | vless | 411.8 | 936.3 | 18.25 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 169.40.42.235 |
| 71.81 | hysteria2 | 427.7 | 777.0 | 17.88 | 0.0 | 9.76 | 12.69 | 18.78 | Au1rxx-base64 | 173.212.201.85 |
| 71.77 | vless | 435.7 | 948.2 | 17.69 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 169.40.42.104 |
| 71.63 | vless | 444.5 | 935.9 | 17.49 | 0.0 | 10.0 | 8.32 | 18.78 | Au1rxx-base64 | 169.40.42.224 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.897 | 0.833 | 275 | 1663 | prefer |
| mheidari-all | 0.834 | 0.762 | 63 | 16008 | prefer |
| ermaozi | 0.748 | 0.741 | 54 | 396 | prefer |
| Surfboard-tg-mixed | 0.68 | 0.601 | 143 | 7408 | observe |
| DeltaKronecker-all | 0.668 | 0.592 | 49 | 5931 | observe |
| ermaozi-get_subscribe | 0.365 | 0.333 | 21 | 431 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 129 | observe |
| Epodonios-all | 0.255 | None | 0 | 7867 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8871 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5925 | observe |
| barry-far-vless | 0.255 | None | 0 | 6149 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4179 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 40 |
| geo | ClientOSError | - | 27 |
| 204 | TimeoutError | - | 23 |
| speed | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 13 |
| geo | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:30782: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
