# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 21:30:02 |
| 运行耗时 | 470.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96212 |
| 去重后节点 | 26679 |
| TCP 可达 | 3000 |
| 真实可用 | 192 |
| Verified 输出 | 192 |
| Global 输出 | 196 |
| All 输出 | 26679 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.7 |
| tcp | 44.4 |
| probe | 233.6 |
| real_test | 106.8 |
| generate | 77.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57019 |
| vmess | 17135 |
| shadowsocks | 12368 |
| trojan | 7872 |
| hysteria2 | 1361 |
| http | 298 |
| socks | 59 |
| shadowsocksr | 55 |
| anytls | 22 |
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
| 80.54 | hysteria2 | 267.3 | 592.7 | 21.59 | 0.0 | 9.96 | 13.93 | 16.06 | Au1rxx-base64 | 66.94.121.46 |
| 77.03 | shadowsocks | 270.8 | 579.9 | 21.51 | 0.0 | 10.0 | 13.46 | 16.06 | Au1rxx-base64 | 156.146.38.167 |
| 76.86 | shadowsocks | 278.3 | 607.6 | 21.34 | 0.0 | 10.0 | 13.46 | 16.06 | Au1rxx-base64 | 156.146.38.169 |
| 74.96 | hysteria2 | 315.8 | 709.7 | 20.47 | 0.0 | 9.38 | 13.93 | 16.06 | Au1rxx-base64 | clash2.deep-links.com |
| 74.89 | hysteria2 | 441.6 | 1085.9 | 17.56 | 0.0 | 10.0 | 13.93 | 16.06 | Au1rxx-base64 | 129.213.91.185 |
| 73.69 | shadowsocks | 278.6 | 600.8 | 21.33 | 0.0 | 10.0 | 13.46 | 17.9 | mheidari-all | 156.146.38.168 |
| 73.4 | shadowsocks | 351.3 | 869.9 | 19.65 | 0.0 | 9.96 | 13.46 | 16.06 | Au1rxx-base64 | 185.215.132.18 |
| 72.56 | shadowsocks | 326.9 | 754.1 | 20.21 | 0.0 | 9.95 | 13.46 | 16.06 | Au1rxx-base64 | 37.19.198.160 |
| 72.49 | shadowsocks | 321.6 | 714.3 | 20.33 | 0.0 | 10.0 | 13.46 | 16.06 | Au1rxx-base64 | 37.19.198.243 |
| 72.34 | shadowsocks | 303.2 | 300.3 | 20.76 | 3.74 | 9.79 | 13.46 | 16.06 | Au1rxx-base64 | 149.22.87.240 |
| 71.67 | shadowsocks | 343.1 | 796.3 | 19.84 | 0.0 | 10.0 | 13.46 | 16.06 | Au1rxx-base64 | 95.215.201.18 |
| 71.57 | shadowsocks | 318.6 | 737.1 | 20.4 | 0.0 | 10.0 | 13.46 | 16.06 | Au1rxx-base64 | 193.151.163.18 |
| 71.47 | shadowsocks | 325.4 | 738.0 | 20.25 | 0.0 | 9.96 | 13.46 | 16.06 | Au1rxx-base64 | 185.230.230.18 |
| 71.19 | shadowsocks | 343.5 | 779.6 | 19.83 | 0.0 | 10.0 | 13.46 | 16.06 | Au1rxx-base64 | 37.19.198.244 |
| 70.89 | shadowsocks | 350.5 | 811.0 | 19.67 | 0.0 | 10.0 | 13.46 | 16.06 | Au1rxx-base64 | 37.19.198.236 |
| 70.56 | shadowsocks | 353.1 | 511.1 | 19.6 | 0.0 | 10.0 | 13.46 | 16.06 | Au1rxx-base64 | 103.11.76.248 |
| 70.17 | hysteria2 | 479.7 | 823.1 | 16.67 | 0.0 | 9.59 | 13.93 | 17.96 | Surfboard-tg-mixed | 130.49.161.70 |
| 69.93 | hysteria2 | 482.7 | 903.3 | 16.6 | 0.0 | 9.67 | 13.93 | 17.9 | mheidari-all | 62.210.124.146 |
| 69.85 | hysteria2 | 459.1 | 690.3 | 17.15 | 0.0 | 9.26 | 13.93 | 17.9 | mheidari-all | 152.67.115.203 |
| 69.5 | shadowsocks | 382.5 | 915.7 | 18.92 | 0.0 | 10.0 | 13.46 | 16.06 | Au1rxx-base64 | 45.86.51.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.968 | 95 | 1575 | prefer |
| mheidari-all | 0.941 | 0.882 | 34 | 23896 | prefer |
| Surfboard-tg-mixed | 0.755 | 0.679 | 78 | 7066 | prefer |
| DeltaKronecker-all | 0.461 | 0.545 | 11 | 3641 | observe |
| ermaozi | 0.331 | 0.297 | 37 | 573 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7550 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10026 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5426 | observe |
| barry-far-vless | 0.255 | None | 0 | 5640 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4176 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1601 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyConnectionError | - | 16 |
| 204 | ProxyError | - | 12 |
| geo | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 7 |
| 204 | TimeoutError | - | 6 |
| speed | TimeoutError | - | 5 |
| geo | TimeoutError | - | 5 |
| speed | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 193 | 192 | - |
| global | False | 207 | 196 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
