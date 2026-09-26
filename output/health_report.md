# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 04:40:22 |
| 运行耗时 | 1024.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96567 |
| 去重后节点 | 26483 |
| TCP 可达 | 3000 |
| 真实可用 | 477 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26483 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.4 |
| tcp | 44.0 |
| probe | 370.1 |
| real_test | 530.5 |
| generate | 74.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58814 |
| vmess | 15089 |
| shadowsocks | 11210 |
| trojan | 8928 |
| hysteria2 | 1558 |
| http | 638 |
| shadowsocksr | 168 |
| socks | 101 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 14 |

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
| 82.32 | vless | 292.2 | 726.0 | 21.01 | 0.0 | 9.63 | 12.58 | 19.1 | Au1rxx-base64 | 79.141.172.154 |
| 82.22 | vless | 282.1 | 664.6 | 21.25 | 0.0 | 9.64 | 12.58 | 19.1 | Au1rxx-base64 | 198.251.78.29 |
| 81.39 | vless | 272.4 | 729.5 | 21.47 | 0.0 | 10.0 | 12.58 | 19.34 | mheidari-all | 67.220.73.204 |
| 80.91 | hysteria2 | 296.8 | 628.6 | 20.91 | 0.0 | 9.79 | 14.21 | 19.1 | Au1rxx-base64 | 66.94.121.46 |
| 80.47 | shadowsocks | 247.1 | 626.1 | 22.06 | 0.0 | 10.0 | 13.07 | 19.34 | mheidari-all | 156.146.38.170 |
| 79.55 | shadowsocks | 251.3 | 629.0 | 21.96 | 0.0 | 10.0 | 13.07 | 19.34 | mheidari-all | 156.146.38.168 |
| 79.47 | vless | 321.4 | 771.8 | 20.34 | 0.0 | 9.78 | 12.58 | 19.1 | Au1rxx-base64 | 47.253.226.114 |
| 79.2 | vless | 277.2 | 555.9 | 21.36 | 0.0 | 10.0 | 12.58 | 19.34 | mheidari-all | 47.251.108.158 |
| 78.76 | vless | 321.4 | 871.0 | 20.34 | 0.0 | 10.0 | 12.58 | 17.84 | DeltaKronecker-all | 198.46.215.223 |
| 78.65 | shadowsocks | 296.6 | 739.2 | 20.91 | 0.0 | 9.66 | 13.07 | 19.1 | Au1rxx-base64 | 37.19.198.244 |
| 78.09 | shadowsocks | 303.4 | 748.6 | 20.75 | 0.0 | 9.65 | 13.07 | 19.1 | Au1rxx-base64 | 37.19.198.160 |
| 77.98 | vless | 298.7 | 608.4 | 20.86 | 0.0 | 10.0 | 12.58 | 19.34 | mheidari-all | 172.233.139.46 |
| 77.47 | vless | 299.0 | 597.8 | 20.86 | 0.0 | 9.67 | 12.58 | 19.1 | Au1rxx-base64 | 162.159.24.131 |
| 77.39 | vless | 410.6 | 888.4 | 18.27 | 0.0 | 9.8 | 12.58 | 19.1 | Au1rxx-base64 | 169.40.42.74 |
| 77.26 | vless | 343.7 | 801.1 | 19.82 | 0.0 | 9.65 | 12.58 | 19.1 | Au1rxx-base64 | 169.40.42.224 |
| 77.21 | vless | 370.6 | 730.8 | 19.2 | 0.0 | 9.67 | 12.58 | 19.1 | Au1rxx-base64 | 192.255.193.161 |
| 77.04 | vless | 419.8 | 1043.0 | 18.06 | 0.0 | 9.67 | 12.58 | 19.1 | Au1rxx-base64 | 185.95.231.233 |
| 76.95 | vless | 353.9 | 833.0 | 19.59 | 0.0 | 9.77 | 12.58 | 19.1 | Au1rxx-base64 | 195.123.235.177 |
| 76.88 | vless | 318.1 | 721.1 | 20.41 | 0.0 | 9.65 | 12.58 | 19.1 | Au1rxx-base64 | 169.40.42.212 |
| 76.86 | vless | 320.8 | 668.9 | 20.35 | 0.0 | 10.0 | 12.58 | 19.34 | mheidari-all | 104.21.14.116 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.952 | 0.891 | 266 | 1594 | prefer |
| Surfboard-tg-mixed | 0.489 | 0.667 | 9 | 7217 | observe |
| ermaozi | 0.414 | 0.394 | 33 | 352 | observe |
| mheidari-all | 0.412 | 0.331 | 619 | 22526 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| DeltaKronecker-all | 0.32 | 0.229 | 48 | 5452 | observe |
| ermaozi-get_subscribe | 0.267 | 0.286 | 14 | 375 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7682 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8923 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5837 | observe |
| barry-far-vless | 0.255 | None | 0 | 6063 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4304 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1594 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 213 |
| speed | TimeoutError | - | 109 |
| geo | ClientOSError | - | 53 |
| 204 | ProxyError | - | 42 |
| cn-block | ClientOSError | - | 32 |
| speed | ClientOSError | - | 26 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
