# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 04:14:38 |
| 运行耗时 | 546.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 91 |
| 原始节点 | 96952 |
| 去重后节点 | 27043 |
| TCP 可达 | 3000 |
| 真实可用 | 325 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27043 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.6 |
| tcp | 44.5 |
| probe | 206.9 |
| real_test | 210.4 |
| generate | 75.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57679 |
| vmess | 17005 |
| shadowsocks | 12101 |
| trojan | 8425 |
| hysteria2 | 1282 |
| http | 194 |
| shadowsocksr | 167 |
| socks | 55 |
| anytls | 21 |
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
| 82.08 | hysteria2 | 227.7 | 616.4 | 22.51 | 0.0 | 10.0 | 13.93 | 17.14 | Au1rxx-base64 | 129.213.91.185 |
| 79.42 | vless | 248.4 | 592.7 | 22.03 | 0.0 | 10.0 | 9.79 | 17.6 | mheidari-all | 172.245.253.16 |
| 78.93 | shadowsocks | 237.7 | 660.7 | 22.27 | 0.0 | 10.0 | 13.52 | 17.14 | Au1rxx-base64 | 37.19.198.160 |
| 78.62 | shadowsocks | 251.2 | 697.4 | 21.96 | 0.0 | 10.0 | 13.52 | 17.14 | Au1rxx-base64 | 37.19.198.244 |
| 78.39 | shadowsocks | 239.6 | 660.1 | 22.23 | 0.0 | 10.0 | 13.52 | 17.14 | Au1rxx-base64 | 193.151.163.18 |
| 78.26 | shadowsocks | 244.2 | 665.2 | 22.12 | 0.0 | 10.0 | 13.52 | 17.12 | Surfboard-tg-mixed | 185.230.230.18 |
| 78.23 | shadowsocks | 245.7 | 652.9 | 22.09 | 0.0 | 10.0 | 13.52 | 17.12 | Surfboard-tg-mixed | 185.215.132.9 |
| 78.11 | shadowsocks | 273.6 | 768.3 | 21.45 | 0.0 | 10.0 | 13.52 | 17.14 | Au1rxx-base64 | 37.19.198.243 |
| 77.0 | trojan | 369.8 | 1032.4 | 19.22 | 0.0 | 10.0 | 13.64 | 17.14 | Au1rxx-base64 | 69.164.240.85 |
| 76.99 | hysteria2 | 253.3 | 620.5 | 21.92 | 0.0 | 10.0 | 13.93 | 17.14 | Au1rxx-base64 | clash2.deep-links.com |
| 76.4 | shadowsocks | 324.8 | 884.8 | 20.26 | 0.0 | 10.0 | 13.52 | 17.12 | Surfboard-tg-mixed | 185.215.132.18 |
| 76.35 | shadowsocks | 219.9 | 595.1 | 22.69 | 0.0 | 10.0 | 13.52 | 17.14 | Au1rxx-base64 | 198.98.53.130 |
| 75.94 | shadowsocks | 344.7 | 885.8 | 19.8 | 0.0 | 10.0 | 13.52 | 17.12 | Surfboard-tg-mixed | 45.86.51.18 |
| 75.75 | shadowsocks | 245.7 | 682.7 | 22.09 | 0.0 | 10.0 | 13.52 | 17.14 | Au1rxx-base64 | 37.19.198.236 |
| 75.17 | shadowsocks | 378.9 | 984.8 | 19.01 | 0.0 | 10.0 | 13.52 | 17.14 | Au1rxx-base64 | 193.151.160.18 |
| 75.06 | shadowsocks | 381.6 | 986.3 | 18.94 | 0.0 | 10.0 | 13.52 | 17.12 | Surfboard-tg-mixed | 193.151.160.9 |
| 74.3 | hysteria2 | 359.2 | 701.2 | 19.46 | 0.0 | 10.0 | 13.93 | 17.6 | mheidari-all | 62.210.124.146 |
| 73.58 | trojan | 354.2 | 775.8 | 19.58 | 0.0 | 9.9 | 13.64 | 17.14 | Au1rxx-base64 | us3.dedushka.top |
| 73.09 | vless | 305.7 | 851.8 | 20.7 | 0.0 | 10.0 | 9.79 | 17.6 | mheidari-all | 147.182.212.232 |
| 72.99 | hysteria2 | 383.3 | 710.9 | 18.9 | 0.0 | 10.0 | 13.93 | 17.12 | Surfboard-tg-mixed | 130.49.161.70 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | 0.93 | 142 | 1599 | prefer |
| Surfboard-tg-mixed | 0.85 | 0.778 | 72 | 7097 | prefer |
| mheidari-all | 0.603 | 0.524 | 212 | 24252 | observe |
| zhangkai | 0.547 | 0.55 | 20 | 31 | observe |
| ermaozi-get_subscribe | 0.335 | 0.303 | 33 | 523 | observe |
| DeltaKronecker-all | 0.294 | 0.192 | 26 | 4067 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| Epodonios-all | 0.255 | None | 0 | 7591 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10125 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5559 | observe |
| barry-far-vless | 0.255 | None | 0 | 5773 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 70 |
| 204 | ProxyError | - | 45 |
| geo | ClientOSError | - | 20 |
| speed | ClientOSError | - | 18 |
| 204 | ProxyConnectionError | - | 8 |
| cn-block | TimeoutError | - | 7 |
| speed | TimeoutError | - | 5 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
