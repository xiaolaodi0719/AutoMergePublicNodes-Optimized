# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 20:32:48 |
| 运行耗时 | 621.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 97468 |
| 去重后节点 | 27633 |
| TCP 可达 | 3000 |
| 真实可用 | 314 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27633 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 49.0 |
| probe | 281.0 |
| real_test | 204.3 |
| generate | 80.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57200 |
| vmess | 16831 |
| shadowsocks | 11713 |
| trojan | 9487 |
| hysteria2 | 1346 |
| http | 613 |
| shadowsocksr | 164 |
| socks | 68 |
| anytls | 22 |
| hysteria | 17 |
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
| 80.56 | hysteria2 | 283.9 | 710.1 | 21.21 | 0.0 | 10.0 | 13.85 | 17.0 | Au1rxx-base64 | 129.213.91.185 |
| 78.63 | hysteria2 | 296.0 | 582.1 | 20.93 | 0.0 | 10.0 | 13.85 | 17.0 | Au1rxx-base64 | 66.94.121.46 |
| 76.55 | shadowsocks | 250.4 | 618.7 | 21.98 | 0.0 | 10.0 | 12.53 | 16.04 | mheidari-all | 156.146.38.168 |
| 75.57 | vless | 297.3 | 660.6 | 20.9 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 195.123.235.183 |
| 74.76 | shadowsocks | 241.3 | 611.4 | 22.19 | 0.0 | 10.0 | 12.53 | 16.04 | mheidari-all | 156.146.38.170 |
| 74.16 | shadowsocks | 308.8 | 760.3 | 20.63 | 0.0 | 10.0 | 12.53 | 17.0 | Au1rxx-base64 | 37.19.198.236 |
| 73.93 | vless | 300.2 | 545.0 | 20.83 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 176.122.183.26 |
| 73.92 | vless | 291.7 | 590.1 | 21.02 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 67.209.184.133 |
| 73.59 | vless | 373.0 | 873.2 | 19.14 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 159.89.87.21 |
| 73.51 | vless | 370.6 | 918.1 | 19.2 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 185.95.231.156 |
| 73.27 | vless | 296.1 | 579.6 | 20.92 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 45.63.53.81 |
| 73.11 | vless | 283.4 | 669.1 | 21.22 | 0.0 | 9.58 | 9.81 | 17.0 | Au1rxx-base64 | uspanel.unixzone.us |
| 73.1 | vless | 303.5 | 597.5 | 20.75 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 195.123.240.65 |
| 73.09 | vless | 341.9 | 744.6 | 19.86 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 169.40.42.104 |
| 72.91 | trojan | 455.4 | 1202.2 | 17.24 | 0.0 | 10.0 | 11.67 | 17.0 | Au1rxx-base64 | 66.23.203.21 |
| 72.77 | shadowsocks | 290.9 | 575.4 | 21.04 | 0.0 | 10.0 | 12.53 | 17.0 | Au1rxx-base64 | 173.244.56.9 |
| 72.72 | vless | 296.7 | 750.3 | 20.91 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 162.35.126.130 |
| 72.66 | shadowsocks | 244.1 | 638.2 | 22.13 | 0.0 | 10.0 | 12.53 | 17.0 | Au1rxx-base64 | 156.146.38.167 |
| 72.38 | shadowsocks | 256.1 | 642.3 | 21.85 | 0.0 | 10.0 | 12.53 | 17.0 | Au1rxx-base64 | 156.146.38.169 |
| 72.14 | vless | 352.9 | 782.1 | 19.61 | 0.0 | 10.0 | 9.81 | 17.0 | Au1rxx-base64 | 66.70.179.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.887 | 0.82 | 261 | 1727 | prefer |
| Surfboard-tg-mixed | 0.812 | 0.744 | 39 | 7036 | prefer |
| mheidari-all | 0.793 | 0.718 | 85 | 23629 | prefer |
| ermaozi | 0.541 | 0.692 | 13 | 639 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| Epodonios-all | 0.255 | None | 0 | 7503 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9755 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5553 | observe |
| barry-far-vless | 0.255 | None | 0 | 5766 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1727 | observe |
| DeltaKronecker-all | 0.24 | 0.25 | 4 | 4750 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 20 |
| 204 | ProxyError | - | 13 |
| cn-block | TimeoutError | - | 13 |
| speed | ClientOSError | - | 12 |
| geo | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| geo | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
