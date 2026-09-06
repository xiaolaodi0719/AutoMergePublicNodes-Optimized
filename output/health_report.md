# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-06 10:42:37 |
| 运行耗时 | 283.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96057 |
| 去重后节点 | 25365 |
| TCP 可达 | 3000 |
| 真实可用 | 490 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25365 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.4 |
| tcp | 41.9 |
| probe | 85.0 |
| real_test | 115.7 |
| generate | 33.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60558 |
| vmess | 12579 |
| shadowsocks | 11219 |
| trojan | 9270 |
| hysteria2 | 2030 |
| http | 138 |
| shadowsocksr | 125 |
| socks | 61 |
| anytls | 47 |
| hysteria | 18 |
| tuic | 12 |

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
| 78.74 | shadowsocks | 278.5 | 644.6 | 21.33 | 0.0 | 10.0 | 14.34 | 18.78 | Au1rxx-base64 | 156.146.38.168 |
| 78.18 | shadowsocks | 311.1 | 803.4 | 20.58 | 0.0 | 8.98 | 14.34 | 18.78 | Au1rxx-base64 | 38.180.135.156 |
| 76.8 | shadowsocks | 338.6 | 948.9 | 19.94 | 0.0 | 10.0 | 14.34 | 17.02 | Surfboard-tg-mixed | 15.204.246.108 |
| 76.42 | shadowsocks | 328.5 | 758.8 | 20.17 | 0.0 | 9.17 | 14.34 | 18.78 | Au1rxx-base64 | 156.146.38.169 |
| 76.36 | vless | 262.5 | 652.7 | 21.7 | 0.0 | 9.14 | 6.74 | 18.78 | Au1rxx-base64 | 169.40.42.104 |
| 76.03 | vless | 268.8 | 687.7 | 21.55 | 0.0 | 8.96 | 6.74 | 18.78 | Au1rxx-base64 | 167.17.69.171 |
| 75.99 | vless | 273.0 | 629.9 | 21.46 | 0.0 | 9.01 | 6.74 | 18.78 | Au1rxx-base64 | 169.40.42.231 |
| 75.74 | vless | 289.0 | 708.4 | 21.09 | 0.0 | 9.14 | 6.74 | 18.78 | Au1rxx-base64 | 66.70.179.198 |
| 75.66 | shadowsocks | 279.7 | 750.0 | 21.3 | 0.0 | 10.0 | 14.34 | 17.02 | Surfboard-tg-mixed | 198.98.53.130 |
| 75.5 | vless | 290.6 | 684.9 | 21.05 | 0.0 | 8.93 | 6.74 | 18.78 | Au1rxx-base64 | 169.40.42.232 |
| 75.4 | shadowsocks | 297.8 | 630.1 | 20.88 | 0.0 | 10.0 | 14.34 | 17.02 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.04 | shadowsocks | 350.5 | 765.9 | 19.66 | 0.0 | 10.0 | 14.34 | 17.02 | Surfboard-tg-mixed | 156.146.38.170 |
| 75.0 | vless | 315.7 | 823.4 | 20.47 | 0.0 | 9.01 | 6.74 | 18.78 | Au1rxx-base64 | 169.40.42.223 |
| 74.81 | vless | 310.0 | 761.1 | 20.6 | 0.0 | 8.96 | 6.74 | 18.78 | Au1rxx-base64 | 169.40.42.163 |
| 74.75 | http | 347.1 | 605.8 | 19.74 | 0.0 | 10.0 | 14.5 | 19.28 | zhangkai | 138.199.35.198 |
| 74.56 | vless | 332.6 | 900.5 | 20.08 | 0.0 | 8.96 | 6.74 | 18.78 | Au1rxx-base64 | 185.95.231.156 |
| 73.9 | vless | 406.1 | 966.3 | 18.38 | 0.0 | 10.0 | 6.74 | 18.78 | Au1rxx-base64 | 169.40.42.229 |
| 73.64 | shadowsocks | 280.9 | 764.8 | 21.28 | 0.0 | 10.0 | 14.34 | 17.02 | Surfboard-tg-mixed | 37.19.198.243 |
| 73.33 | vless | 265.7 | 676.1 | 21.63 | 0.0 | 8.97 | 6.74 | 18.78 | Au1rxx-base64 | 169.40.42.182 |
| 73.09 | vless | 390.0 | 989.6 | 18.75 | 0.0 | 9.01 | 6.74 | 18.78 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.915 | 0.845 | 343 | 1781 | prefer |
| Surfboard-tg-mixed | 0.85 | 0.773 | 150 | 7318 | prefer |
| zhangkai | 0.839 | 0.864 | 22 | 144 | prefer |
| DeltaKronecker-all | 0.593 | 1.0 | 7 | 5856 | observe |
| mheidari-all | 0.558 | 0.478 | 113 | 22388 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6965 | observe |
| tg-oneclickvpnkeys | 0.274 | 0.667 | 3 | 133 | observe |
| peasoft-NoMoreWalls | 0.256 | 1.0 | 1 | 30 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4791 | observe |
| Epodonios-all | 0.255 | None | 0 | 7771 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8223 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6005 | observe |
| barry-far-vless | 0.255 | None | 0 | 6223 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4111 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 40 |
| geo | ClientOSError | - | 23 |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 20 |
| speed | TimeoutError | - | 17 |
| geo | TimeoutError | - | 11 |
| 204 | ProxyError | - | 8 |
| speed | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
