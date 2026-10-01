# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 12:57:51 |
| 运行耗时 | 527.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98134 |
| 去重后节点 | 27405 |
| TCP 可达 | 3000 |
| 真实可用 | 406 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27405 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 45.5 |
| probe | 222.2 |
| real_test | 170.7 |
| generate | 80.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60363 |
| vmess | 15497 |
| shadowsocks | 11364 |
| trojan | 8880 |
| hysteria2 | 1317 |
| http | 400 |
| shadowsocksr | 174 |
| socks | 64 |
| anytls | 51 |
| hysteria | 16 |
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
| 81.02 | shadowsocks | 250.1 | 697.2 | 21.99 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 37.19.198.160 |
| 80.97 | shadowsocks | 252.3 | 699.2 | 21.94 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 37.19.198.243 |
| 79.32 | hysteria2 | 297.3 | 598.9 | 20.9 | 0.0 | 10.0 | 13.27 | 19.64 | Au1rxx-base64 | 192.255.128.123 |
| 78.78 | shadowsocks | 325.1 | 875.3 | 20.25 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 140.82.63.79 |
| 77.97 | shadowsocks | 280.7 | 644.8 | 21.28 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 156.146.38.169 |
| 77.61 | shadowsocks | 282.9 | 654.3 | 21.23 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 156.146.38.168 |
| 77.16 | shadowsocks | 287.0 | 650.5 | 21.13 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 156.146.38.167 |
| 76.51 | shadowsocks | 285.1 | 648.6 | 21.18 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 156.146.38.170 |
| 76.09 | vless | 232.7 | 617.4 | 22.39 | 0.0 | 10.0 | 4.06 | 19.64 | Au1rxx-base64 | 195.123.235.177 |
| 75.8 | shadowsocks | 259.5 | 710.5 | 21.77 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 37.19.198.236 |
| 75.53 | vless | 257.0 | 686.4 | 21.83 | 0.0 | 10.0 | 4.06 | 19.64 | Au1rxx-base64 | 137.184.218.169 |
| 75.38 | vless | 263.4 | 678.8 | 21.68 | 0.0 | 10.0 | 4.06 | 19.64 | Au1rxx-base64 | 169.40.42.133 |
| 75.32 | shadowsocks | 288.6 | 595.1 | 21.1 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 173.244.56.6 |
| 75.2 | shadowsocks | 318.4 | 814.6 | 20.41 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 199.60.101.12 |
| 75.16 | vless | 235.7 | 670.7 | 22.32 | 0.0 | 10.0 | 4.06 | 19.64 | Au1rxx-base64 | 79.141.172.154 |
| 75.08 | shadowsocks | 483.0 | 1323.4 | 16.6 | 0.0 | 9.95 | 13.39 | 19.64 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 74.86 | vless | 286.1 | 756.9 | 21.16 | 0.0 | 10.0 | 4.06 | 19.64 | Au1rxx-base64 | 185.95.231.233 |
| 74.7 | hysteria2 | 329.3 | 674.6 | 20.16 | 0.0 | 10.0 | 13.27 | 19.64 | Au1rxx-base64 | 66.94.121.46 |
| 74.38 | shadowsocks | 515.4 | 1371.7 | 15.85 | 0.0 | 10.0 | 13.39 | 19.64 | Au1rxx-base64 | 15.235.75.71 |
| 74.37 | hysteria2 | 424.3 | 1186.7 | 17.96 | 0.0 | 10.0 | 13.27 | 19.64 | Au1rxx-base64 | 129.213.91.185 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | 0.797 | 305 | 1787 | prefer |
| mheidari-all | 0.853 | 0.781 | 64 | 23162 | prefer |
| Surfboard-tg-mixed | 0.755 | 0.677 | 124 | 7144 | prefer |
| DeltaKronecker-all | 0.58 | 0.5 | 24 | 5603 | observe |
| zhangkai | 0.551 | 0.55 | 20 | 144 | observe |
| ermaozi | 0.442 | 1.0 | 5 | 56 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5324 | observe |
| Epodonios-all | 0.255 | None | 0 | 7625 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9489 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5788 | observe |
| barry-far-vless | 0.255 | None | 0 | 6032 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4241 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 58 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyConnectionError | - | 12 |
| geo | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| geo | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 4 |
| speed | TimeoutError | - | 4 |
| 204 | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
