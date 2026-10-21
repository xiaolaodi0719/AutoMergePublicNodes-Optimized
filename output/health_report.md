# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 17:05:44 |
| 运行耗时 | 581.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96570 |
| 去重后节点 | 26902 |
| TCP 可达 | 3000 |
| 真实可用 | 228 |
| Verified 输出 | 228 |
| Global 输出 | 242 |
| All 输出 | 26902 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 44.4 |
| probe | 229.8 |
| real_test | 219.0 |
| generate | 78.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57413 |
| vmess | 17058 |
| shadowsocks | 11928 |
| trojan | 8545 |
| hysteria2 | 1255 |
| shadowsocksr | 161 |
| http | 110 |
| socks | 56 |
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
| 79.1 | hysteria2 | 240.9 | 674.0 | 22.2 | 0.0 | 10.0 | 12.0 | 16.4 | Au1rxx-base64 | 129.213.91.185 |
| 77.64 | vless | 262.9 | 667.3 | 21.69 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 159.89.87.21 |
| 77.56 | vless | 266.2 | 668.3 | 21.61 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 169.40.42.163 |
| 77.34 | shadowsocks | 234.3 | 670.4 | 22.35 | 0.0 | 10.0 | 13.09 | 16.4 | Au1rxx-base64 | 185.230.230.18 |
| 77.34 | vless | 276.1 | 720.7 | 21.39 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 169.40.42.35 |
| 77.34 | vless | 276.1 | 731.2 | 21.39 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 195.123.235.183 |
| 76.98 | vless | 291.6 | 714.2 | 21.03 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 66.70.179.198 |
| 76.97 | shadowsocks | 272.2 | 763.3 | 21.48 | 0.0 | 10.0 | 13.09 | 16.4 | Au1rxx-base64 | 37.19.198.243 |
| 76.85 | shadowsocks | 277.1 | 778.0 | 21.36 | 0.0 | 10.0 | 13.09 | 16.4 | Au1rxx-base64 | 37.19.198.244 |
| 76.42 | vless | 299.4 | 691.9 | 20.85 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 167.17.69.171 |
| 76.1 | shadowsocks | 244.7 | 671.1 | 22.11 | 0.0 | 10.0 | 13.09 | 16.4 | Au1rxx-base64 | 193.151.163.18 |
| 75.89 | vless | 338.5 | 865.2 | 19.94 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 169.40.42.229 |
| 75.79 | vless | 342.7 | 920.9 | 19.84 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 169.40.42.235 |
| 75.51 | shadowsocks | 285.2 | 626.7 | 21.17 | 0.0 | 10.0 | 13.09 | 18.12 | mheidari-all | 156.146.38.168 |
| 75.36 | vless | 361.7 | 990.8 | 19.41 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 169.40.42.202 |
| 75.23 | vless | 367.0 | 991.2 | 19.28 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 169.40.42.168 |
| 75.13 | vless | 371.3 | 910.2 | 19.18 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 169.40.42.231 |
| 74.75 | shadowsocks | 346.5 | 951.5 | 19.76 | 0.0 | 10.0 | 13.09 | 16.4 | Au1rxx-base64 | 185.215.132.9 |
| 74.7 | shadowsocks | 305.2 | 884.9 | 20.71 | 0.0 | 10.0 | 13.09 | 16.4 | Au1rxx-base64 | 45.86.51.18 |
| 74.52 | vless | 341.9 | 833.1 | 19.86 | 0.0 | 10.0 | 9.55 | 16.4 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.834 | 0.774 | 190 | 1568 | prefer |
| Surfboard-tg-mixed | 0.803 | 0.733 | 45 | 7070 | prefer |
| mheidari-all | 0.673 | 0.596 | 57 | 24102 | observe |
| zhangkai | 0.45 | 0.444 | 27 | 31 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| Epodonios-all | 0.255 | None | 0 | 7559 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10165 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5554 | observe |
| barry-far-vless | 0.255 | None | 0 | 5768 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1568 | observe |
| DeltaKronecker-all | 0.234 | 0.154 | 13 | 4067 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 29 |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 19 |
| geo | ClientOSError | - | 9 |
| speed | ClientOSError | - | 9 |
| geo | TimeoutError | - | 8 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 228 | - |
| global | False | 300 | 242 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
