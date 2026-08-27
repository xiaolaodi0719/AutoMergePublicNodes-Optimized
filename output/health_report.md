# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-27 08:35:24 |
| 运行耗时 | 240.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 88922 |
| 去重后节点 | 24474 |
| TCP 可达 | 3000 |
| 真实可用 | 486 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24474 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 40.6 |
| probe | 49.2 |
| real_test | 107.4 |
| generate | 36.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55367 |
| shadowsocks | 11857 |
| vmess | 11483 |
| trojan | 7704 |
| hysteria2 | 2100 |
| http | 164 |
| shadowsocksr | 127 |
| socks | 79 |
| anytls | 20 |
| hysteria | 16 |
| tuic | 5 |

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
| 79.36 | hysteria2 | 330.4 | 728.8 | 20.13 | 0.0 | 10.0 | 14.46 | 19.2 | Au1rxx-base64 | 159.223.157.129 |
| 78.42 | shadowsocks | 279.3 | 654.6 | 21.31 | 0.0 | 10.0 | 13.68 | 19.16 | Surfboard-tg-mixed | 156.146.38.170 |
| 78.01 | shadowsocks | 283.7 | 671.3 | 21.21 | 0.0 | 10.0 | 13.68 | 19.16 | Surfboard-tg-mixed | 156.146.38.167 |
| 77.68 | shadowsocks | 298.6 | 686.0 | 20.87 | 0.0 | 10.0 | 13.68 | 19.2 | Au1rxx-base64 | 156.146.38.168 |
| 76.6 | shadowsocks | 344.8 | 863.0 | 19.8 | 0.0 | 10.0 | 13.68 | 19.2 | Au1rxx-base64 | 156.146.38.169 |
| 76.02 | vless | 317.1 | 621.4 | 20.44 | 0.0 | 10.0 | 11.09 | 19.2 | Au1rxx-base64 | 166.88.186.151 |
| 75.11 | trojan | 304.9 | 589.4 | 20.72 | 0.0 | 10.0 | 13.27 | 19.2 | Au1rxx-base64 | 14.1.28.76 |
| 75.08 | shadowsocks | 308.3 | 594.0 | 20.64 | 0.0 | 10.0 | 13.68 | 19.2 | Au1rxx-base64 | 173.244.56.9 |
| 74.33 | http | 303.2 | 597.2 | 20.76 | 0.0 | 10.0 | 13.75 | 17.5 | zhangkai | 138.199.35.216 |
| 74.3 | vless | 359.8 | 711.9 | 19.45 | 0.0 | 10.0 | 11.09 | 19.2 | Au1rxx-base64 | 195.211.99.45 |
| 74.27 | vless | 479.9 | 973.8 | 16.67 | 0.0 | 10.0 | 11.09 | 19.2 | Au1rxx-base64 | 38.180.242.205 |
| 73.98 | http | 301.7 | 593.9 | 20.79 | 0.0 | 10.0 | 13.75 | 17.5 | zhangkai | 138.199.35.198 |
| 73.78 | shadowsocks | 348.8 | 743.1 | 19.7 | 0.0 | 10.0 | 13.68 | 19.2 | Au1rxx-base64 | 37.19.198.236 |
| 73.61 | shadowsocks | 298.2 | 568.3 | 20.88 | 0.0 | 10.0 | 13.68 | 19.2 | Au1rxx-base64 | 108.181.118.10 |
| 73.58 | vless | 347.0 | 363.2 | 19.75 | 1.38 | 9.47 | 11.09 | 19.16 | Surfboard-tg-mixed | 31.76.91.72 |
| 73.56 | shadowsocks | 384.6 | 783.4 | 18.88 | 0.0 | 10.0 | 13.68 | 19.16 | Surfboard-tg-mixed | 173.244.56.6 |
| 73.31 | vless | 357.7 | 703.2 | 19.5 | 0.0 | 10.0 | 11.09 | 19.2 | Au1rxx-base64 | 195.211.99.49 |
| 73.29 | vless | 430.7 | 1025.4 | 17.81 | 0.0 | 10.0 | 11.09 | 19.2 | Au1rxx-base64 | 45.138.100.226 |
| 73.18 | shadowsocks | 338.5 | 634.2 | 19.94 | 0.0 | 10.0 | 13.68 | 19.2 | Au1rxx-base64 | 108.181.0.177 |
| 73.13 | vless | 404.5 | 833.4 | 18.41 | 0.0 | 10.0 | 11.09 | 19.2 | Au1rxx-base64 | 47.89.186.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.993 | 0.928 | 318 | 1712 | prefer |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| Surfboard-tg-mixed | 0.883 | 0.807 | 135 | 6600 | prefer |
| mheidari-all | 0.454 | 0.373 | 153 | 19260 | observe |
| DeltaKronecker-all | 0.352 | 0.364 | 11 | 6107 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4825 | observe |
| Epodonios-all | 0.255 | None | 0 | 7097 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7132 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5353 | observe |
| barry-far-vless | 0.255 | None | 0 | 5696 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4011 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1712 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 61 |
| geo | TimeoutError | - | 30 |
| speed | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 9 |
| 204 | ProxyError | - | 5 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
