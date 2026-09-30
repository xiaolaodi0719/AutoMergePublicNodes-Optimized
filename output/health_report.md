# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-30 22:11:04 |
| 运行耗时 | 455.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97982 |
| 去重后节点 | 27241 |
| TCP 可达 | 3000 |
| 真实可用 | 341 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27241 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.7 |
| tcp | 45.9 |
| probe | 191.7 |
| real_test | 130.1 |
| generate | 79.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60180 |
| vmess | 15249 |
| shadowsocks | 11357 |
| trojan | 9114 |
| hysteria2 | 1348 |
| http | 440 |
| shadowsocksr | 171 |
| socks | 68 |
| anytls | 32 |
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
| 78.56 | shadowsocks | 251.2 | 620.8 | 21.96 | 0.0 | 10.0 | 13.2 | 17.4 | Au1rxx-base64 | 156.146.38.167 |
| 78.56 | vless | 257.9 | 644.1 | 21.81 | 0.0 | 10.0 | 9.35 | 17.4 | Au1rxx-base64 | 198.251.78.29 |
| 78.26 | shadowsocks | 264.5 | 613.1 | 21.66 | 0.0 | 10.0 | 13.2 | 17.4 | Au1rxx-base64 | 156.146.38.170 |
| 78.25 | hysteria2 | 283.6 | 717.5 | 21.21 | 0.0 | 10.0 | 12.0 | 16.14 | mheidari-all | 159.223.157.129 |
| 77.83 | shadowsocks | 283.1 | 730.5 | 21.23 | 0.0 | 10.0 | 13.2 | 17.4 | Au1rxx-base64 | 37.19.198.236 |
| 77.77 | shadowsocks | 285.5 | 733.1 | 21.17 | 0.0 | 10.0 | 13.2 | 17.4 | Au1rxx-base64 | 37.19.198.243 |
| 77.72 | shadowsocks | 287.6 | 740.8 | 21.12 | 0.0 | 10.0 | 13.2 | 17.4 | Au1rxx-base64 | 37.19.198.160 |
| 77.05 | vless | 266.3 | 623.8 | 21.61 | 0.0 | 10.0 | 9.35 | 17.4 | Au1rxx-base64 | 195.123.235.177 |
| 77.04 | vless | 307.3 | 727.2 | 20.66 | 0.0 | 10.0 | 9.35 | 17.4 | Au1rxx-base64 | 66.70.179.198 |
| 76.87 | hysteria2 | 264.4 | 562.7 | 21.66 | 0.0 | 10.0 | 12.0 | 17.4 | Au1rxx-base64 | 192.255.128.123 |
| 76.55 | shadowsocks | 283.6 | 721.1 | 21.21 | 0.0 | 10.0 | 13.2 | 16.14 | mheidari-all | 37.19.198.244 |
| 76.51 | shadowsocks | 296.6 | 764.3 | 20.91 | 0.0 | 10.0 | 13.2 | 17.4 | Au1rxx-base64 | 198.98.53.130 |
| 76.33 | vless | 339.6 | 721.5 | 19.92 | 0.0 | 10.0 | 9.35 | 17.4 | Au1rxx-base64 | 169.40.42.35 |
| 76.26 | vless | 301.9 | 741.2 | 20.79 | 0.0 | 10.0 | 9.35 | 17.4 | Au1rxx-base64 | 169.40.42.133 |
| 76.19 | shadowsocks | 329.9 | 620.9 | 20.14 | 0.0 | 10.0 | 13.2 | 17.4 | Au1rxx-base64 | 140.82.63.79 |
| 75.57 | shadowsocks | 272.4 | 790.9 | 21.47 | 0.0 | 10.0 | 13.2 | 17.4 | Au1rxx-base64 | 66.23.204.219 |
| 75.56 | shadowsocks | 335.2 | 820.9 | 20.02 | 0.0 | 10.0 | 13.2 | 17.4 | Au1rxx-base64 | 15.204.246.132 |
| 75.15 | vless | 371.3 | 894.4 | 19.18 | 0.0 | 10.0 | 9.35 | 17.4 | Au1rxx-base64 | 137.184.218.169 |
| 75.14 | vless | 356.3 | 902.3 | 19.53 | 0.0 | 10.0 | 9.35 | 17.4 | Au1rxx-base64 | 169.40.42.95 |
| 74.92 | vless | 313.1 | 669.9 | 20.53 | 0.0 | 10.0 | 9.35 | 17.4 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.903 | 0.831 | 77 | 22901 | prefer |
| Surfboard-tg-mixed | 0.895 | 0.84 | 25 | 7200 | prefer |
| Au1rxx-base64 | 0.873 | 0.803 | 289 | 1803 | prefer |
| zhangkai | 0.745 | 0.933 | 15 | 144 | prefer |
| DeltaKronecker-all | 0.503 | 0.583 | 12 | 5434 | observe |
| tg-oneclickvpnkeys | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7696 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9724 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5833 | observe |
| barry-far-vless | 0.255 | None | 0 | 6072 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4183 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1803 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 43 |
| cn-block | TimeoutError | - | 11 |
| 204 | ProxyError | - | 7 |
| 204 | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
