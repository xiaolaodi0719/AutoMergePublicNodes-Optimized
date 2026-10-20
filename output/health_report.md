# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 16:46:40 |
| 运行耗时 | 554.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 94292 |
| 去重后节点 | 26495 |
| TCP 可达 | 3000 |
| 真实可用 | 293 |
| Verified 输出 | 293 |
| Global 输出 | 300 |
| All 输出 | 26495 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.5 |
| tcp | 45.4 |
| probe | 235.4 |
| real_test | 175.0 |
| generate | 89.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56255 |
| vmess | 16826 |
| shadowsocks | 11209 |
| trojan | 8370 |
| hysteria2 | 1141 |
| http | 211 |
| shadowsocksr | 158 |
| socks | 63 |
| anytls | 36 |
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
| 81.12 | vless | 217.5 | 513.9 | 22.74 | 0.0 | 10.0 | 11.24 | 19.14 | mheidari-all | 47.251.108.158 |
| 80.89 | shadowsocks | 246.9 | 578.4 | 22.06 | 0.0 | 10.0 | 13.69 | 19.14 | mheidari-all | 173.244.56.6 |
| 80.62 | hysteria2 | 175.8 | 466.0 | 23.71 | 0.0 | 9.09 | 13.85 | 18.02 | Au1rxx-base64 | 179.255.104.98 |
| 80.5 | shadowsocks | 263.9 | 635.1 | 21.67 | 0.0 | 10.0 | 13.69 | 19.14 | mheidari-all | 156.146.38.168 |
| 79.75 | shadowsocks | 213.8 | 530.6 | 22.83 | 0.0 | 9.21 | 13.69 | 18.02 | Au1rxx-base64 | 173.244.56.9 |
| 78.07 | shadowsocks | 259.6 | 623.9 | 21.77 | 0.0 | 9.31 | 13.69 | 18.02 | Au1rxx-base64 | 156.146.38.169 |
| 75.56 | shadowsocks | 358.8 | 913.5 | 19.47 | 0.0 | 9.02 | 13.69 | 18.02 | Au1rxx-base64 | 156.146.38.167 |
| 75.47 | vless | 298.3 | 618.9 | 20.87 | 0.0 | 9.07 | 11.24 | 18.02 | Au1rxx-base64 | 44.248.233.99 |
| 75.09 | vless | 273.2 | 687.7 | 21.45 | 0.0 | 9.06 | 11.24 | 18.02 | Au1rxx-base64 | 154.40.55.185 |
| 75.07 | shadowsocks | 386.5 | 586.2 | 18.83 | 0.0 | 9.03 | 13.69 | 18.02 | Au1rxx-base64 | 103.11.76.248 |
| 74.9 | vless | 278.8 | 562.9 | 21.32 | 0.0 | 8.21 | 11.24 | 18.02 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 74.85 | hysteria2 | 325.1 | 711.4 | 20.25 | 0.0 | 10.0 | 13.85 | 14.4 | Surfboard-tg-mixed | 129.213.91.185 |
| 74.71 | shadowsocks | 296.3 | 634.8 | 20.92 | 0.0 | 8.98 | 13.69 | 18.02 | Au1rxx-base64 | 149.22.95.183 |
| 73.82 | shadowsocks | 303.8 | 358.1 | 20.75 | 1.57 | 9.9 | 13.69 | 19.14 | mheidari-all | 149.22.87.241 |
| 73.75 | vless | 442.8 | 1105.5 | 17.53 | 0.0 | 9.06 | 11.24 | 18.02 | Au1rxx-base64 | 51.81.203.63 |
| 73.4 | shadowsocks | 360.6 | 780.6 | 19.43 | 0.0 | 10.0 | 13.69 | 19.14 | mheidari-all | 37.19.198.243 |
| 73.13 | vless | 337.5 | 336.1 | 19.96 | 2.4 | 9.0 | 11.24 | 18.02 | Au1rxx-base64 | 142.91.108.25 |
| 73.13 | shadowsocks | 368.6 | 800.6 | 19.25 | 0.0 | 10.0 | 13.69 | 19.14 | mheidari-all | 37.19.198.236 |
| 72.62 | http | 397.8 | 909.1 | 18.57 | 0.0 | 10.0 | 10.31 | 19.12 | zhangkai | 38.247.141.135 |
| 72.42 | vless | 275.5 | 610.3 | 21.4 | 0.0 | 9.1 | 11.24 | 18.02 | Au1rxx-base64 | 15.204.97.195 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.911 | 0.86 | 250 | 1348 | prefer |
| mheidari-all | 0.88 | 0.814 | 43 | 23236 | prefer |
| Surfboard-tg-mixed | 0.785 | 0.714 | 42 | 6911 | prefer |
| zhangkai | 0.401 | 0.391 | 23 | 31 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 79 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| Epodonios-all | 0.255 | None | 0 | 7384 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10086 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5732 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| DeltaKronecker-all | 0.24 | 0.25 | 4 | 3519 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyConnectionError | - | 17 |
| 204 | TimeoutError | - | 13 |
| speed | TimeoutError | - | 12 |
| speed | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 11 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 3 |
| geo | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 293 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
