# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 11:54:53 |
| 运行耗时 | 586.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 95691 |
| 去重后节点 | 26593 |
| TCP 可达 | 3000 |
| 真实可用 | 416 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26593 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.7 |
| tcp | 44.3 |
| probe | 266.4 |
| real_test | 183.8 |
| generate | 83.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58165 |
| vmess | 14701 |
| shadowsocks | 11300 |
| trojan | 9136 |
| hysteria2 | 1454 |
| http | 641 |
| shadowsocksr | 168 |
| socks | 77 |
| anytls | 26 |
| hysteria | 15 |
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
| 79.62 | shadowsocks | 255.0 | 640.8 | 21.87 | 0.0 | 9.06 | 13.57 | 19.12 | Au1rxx-base64 | 156.146.38.168 |
| 79.52 | shadowsocks | 253.3 | 681.1 | 21.91 | 0.0 | 9.42 | 13.57 | 19.12 | Au1rxx-base64 | 185.156.47.97 |
| 79.12 | shadowsocks | 283.0 | 726.1 | 21.23 | 0.0 | 9.2 | 13.57 | 19.12 | Au1rxx-base64 | 37.19.198.244 |
| 78.52 | shadowsocks | 304.5 | 792.7 | 20.73 | 0.0 | 9.1 | 13.57 | 19.12 | Au1rxx-base64 | 198.98.53.130 |
| 77.77 | shadowsocks | 336.9 | 885.3 | 19.98 | 0.0 | 9.1 | 13.57 | 19.12 | Au1rxx-base64 | 156.146.38.169 |
| 77.18 | shadowsocks | 291.3 | 582.9 | 21.03 | 0.0 | 10.0 | 13.57 | 16.58 | Surfboard-tg-mixed | 156.146.38.170 |
| 76.97 | shadowsocks | 283.4 | 738.3 | 21.22 | 0.0 | 9.06 | 13.57 | 19.12 | Au1rxx-base64 | 37.19.198.243 |
| 76.92 | shadowsocks | 330.3 | 920.6 | 20.13 | 0.0 | 8.6 | 13.57 | 19.12 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 76.83 | shadowsocks | 277.1 | 641.2 | 21.36 | 0.0 | 10.0 | 13.57 | 16.58 | Surfboard-tg-mixed | 23.150.248.20 |
| 76.78 | vless | 262.2 | 657.4 | 21.71 | 0.0 | 9.18 | 6.77 | 19.12 | Au1rxx-base64 | 198.251.78.29 |
| 76.7 | shadowsocks | 253.3 | 632.3 | 21.92 | 0.0 | 9.09 | 13.57 | 19.12 | Au1rxx-base64 | 156.146.38.167 |
| 76.44 | vless | 273.6 | 706.4 | 21.44 | 0.0 | 9.11 | 6.77 | 19.12 | Au1rxx-base64 | 79.141.172.154 |
| 76.22 | shadowsocks | 360.0 | 900.4 | 19.45 | 0.0 | 9.14 | 13.57 | 19.12 | Au1rxx-base64 | 38.180.135.156 |
| 76.08 | vless | 292.4 | 709.6 | 21.01 | 0.0 | 9.18 | 6.77 | 19.12 | Au1rxx-base64 | 169.40.42.16 |
| 75.84 | vless | 295.8 | 727.5 | 20.93 | 0.0 | 9.02 | 6.77 | 19.12 | Au1rxx-base64 | 169.40.42.184 |
| 75.46 | vless | 298.0 | 683.2 | 20.88 | 0.0 | 9.18 | 6.77 | 19.12 | Au1rxx-base64 | 169.40.42.202 |
| 75.31 | shadowsocks | 439.3 | 954.5 | 17.61 | 0.0 | 9.01 | 13.57 | 19.12 | Au1rxx-base64 | 142.4.216.225 |
| 75.18 | hysteria2 | 381.0 | 918.3 | 18.96 | 0.0 | 8.87 | 12.86 | 19.12 | Au1rxx-base64 | 66.94.121.46 |
| 74.87 | vless | 333.5 | 715.0 | 20.06 | 0.0 | 9.18 | 6.77 | 19.12 | Au1rxx-base64 | 169.40.42.225 |
| 74.8 | vless | 335.3 | 794.3 | 20.02 | 0.0 | 9.08 | 6.77 | 19.12 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.939 | 0.878 | 278 | 1589 | prefer |
| mheidari-all | 0.883 | 0.812 | 69 | 22397 | prefer |
| Surfboard-tg-mixed | 0.764 | 0.688 | 93 | 7025 | prefer |
| ermaozi | 0.658 | 0.649 | 57 | 338 | observe |
| DeltaKronecker-all | 0.533 | 0.571 | 14 | 5466 | observe |
| ermaozi-get_subscribe | 0.401 | 0.438 | 16 | 361 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7510 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8971 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5637 | observe |
| barry-far-vless | 0.255 | None | 0 | 5862 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4277 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1589 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 30 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 15 |
| speed | TimeoutError | - | 13 |
| geo | TimeoutError | - | 11 |
| speed | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 4 |
| geo | ClientOSError | - | 4 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
