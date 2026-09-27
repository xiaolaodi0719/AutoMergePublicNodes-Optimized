# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 04:55:08 |
| 运行耗时 | 879.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 95804 |
| 去重后节点 | 26625 |
| TCP 可达 | 3000 |
| 真实可用 | 518 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26625 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 43.9 |
| probe | 300.5 |
| real_test | 447.8 |
| generate | 78.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58211 |
| vmess | 14886 |
| shadowsocks | 11304 |
| trojan | 8999 |
| hysteria2 | 1433 |
| http | 677 |
| shadowsocksr | 167 |
| socks | 79 |
| anytls | 26 |
| hysteria | 15 |
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
| 80.75 | vless | 283.1 | 719.7 | 21.23 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 79.141.172.154 |
| 80.74 | vless | 278.7 | 667.9 | 21.33 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 198.251.78.29 |
| 77.74 | vless | 299.4 | 673.5 | 20.85 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 195.123.235.177 |
| 77.54 | hysteria2 | 262.4 | 560.9 | 21.7 | 0.0 | 10.0 | 14.46 | 19.0 | Au1rxx-base64 | 192.255.128.123 |
| 77.47 | shadowsocks | 339.2 | 911.3 | 19.93 | 0.0 | 10.0 | 13.04 | 19.0 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 77.38 | shadowsocks | 343.0 | 902.0 | 19.84 | 0.0 | 10.0 | 13.04 | 19.0 | Au1rxx-base64 | 185.156.47.97 |
| 77.12 | vless | 350.2 | 848.4 | 19.67 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 185.95.231.233 |
| 76.92 | vless | 350.1 | 828.4 | 19.67 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 169.40.42.179 |
| 76.85 | vless | 335.7 | 759.9 | 20.01 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 66.70.179.198 |
| 76.76 | vless | 370.2 | 760.4 | 19.21 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 169.40.42.74 |
| 76.64 | shadowsocks | 253.2 | 630.3 | 21.92 | 0.0 | 10.0 | 13.04 | 15.68 | Surfboard-tg-mixed | 156.146.38.169 |
| 76.42 | vless | 350.0 | 704.3 | 19.68 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 169.40.42.223 |
| 76.38 | vless | 326.3 | 686.9 | 20.22 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 169.40.42.35 |
| 76.25 | vless | 282.7 | 597.0 | 21.23 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 104.18.47.113 |
| 76.1 | vless | 343.1 | 690.4 | 19.84 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 169.40.42.75 |
| 76.03 | shadowsocks | 279.6 | 665.0 | 21.31 | 0.0 | 10.0 | 13.04 | 15.68 | Surfboard-tg-mixed | 198.98.53.130 |
| 75.83 | vless | 420.2 | 1056.2 | 18.05 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 185.95.231.156 |
| 75.59 | vless | 388.9 | 932.9 | 18.78 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 38.77.133.202 |
| 75.51 | vless | 302.1 | 606.8 | 20.78 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 172.235.43.210 |
| 75.33 | vless | 349.7 | 812.3 | 19.68 | 0.0 | 10.0 | 10.52 | 19.0 | Au1rxx-base64 | 169.40.42.163 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.956 | 0.897 | 273 | 1536 | prefer |
| Surfboard-tg-mixed | 0.829 | 0.751 | 197 | 7113 | prefer |
| ermaozi | 0.69 | 0.688 | 32 | 338 | observe |
| ermaozi-get_subscribe | 0.423 | 0.833 | 6 | 361 | observe |
| DeltaKronecker-all | 0.407 | 0.455 | 11 | 5512 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| mheidari-all | 0.321 | 0.24 | 384 | 22408 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7583 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8902 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5686 | observe |
| barry-far-vless | 0.255 | None | 0 | 5907 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4355 | observe |
| Au1rxx-clash | 0.236 | None | 0 | 1536 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 173 |
| speed | TimeoutError | - | 71 |
| geo | ClientOSError | - | 52 |
| 204 | TimeoutError | - | 22 |
| speed | ClientOSError | - | 21 |
| cn-block | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 11 |
| 204 | ProxyError | - | 10 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
