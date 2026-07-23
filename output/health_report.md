# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-23 19:30:42 |
| 运行耗时 | 309.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83072 |
| 去重后节点 | 22757 |
| TCP 可达 | 3000 |
| 真实可用 | 667 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22757 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.3 |
| tcp | 32.1 |
| probe | 61.4 |
| real_test | 156.3 |
| generate | 52.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48036 |
| trojan | 14354 |
| vmess | 10056 |
| shadowsocks | 10000 |
| hysteria2 | 421 |
| shadowsocksr | 75 |
| socks | 54 |
| http | 50 |
| hysteria | 14 |
| tuic | 9 |
| anytls | 3 |

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
| 77.72 | shadowsocks | 215.7 | 585.9 | 22.79 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 198.98.53.130 |
| 77.45 | shadowsocks | 227.0 | 631.2 | 22.52 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 37.19.198.160 |
| 77.33 | shadowsocks | 232.2 | 638.5 | 22.4 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 37.19.198.236 |
| 76.52 | shadowsocks | 267.5 | 749.4 | 21.59 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 37.19.198.243 |
| 76.09 | trojan | 247.5 | 676.4 | 22.05 | 0.0 | 10.0 | 13.38 | 13.66 | DeltaKronecker-all | 153.75.250.171 |
| 74.46 | shadowsocks | 330.7 | 841.3 | 20.12 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 185.196.61.82 |
| 74.27 | shadowsocks | 234.8 | 651.5 | 22.34 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 37.19.198.244 |
| 73.79 | shadowsocks | 293.6 | 684.6 | 20.98 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 156.146.38.167 |
| 73.7 | shadowsocks | 283.9 | 657.2 | 21.21 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 156.146.38.168 |
| 72.71 | trojan | 342.9 | 853.8 | 19.84 | 0.0 | 10.0 | 13.38 | 13.66 | DeltaKronecker-all | 64.74.163.118 |
| 72.7 | shadowsocks | 286.4 | 653.0 | 21.15 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 156.146.38.169 |
| 72.41 | vless | 238.3 | 663.0 | 22.26 | 0.0 | 10.0 | 4.87 | 15.28 | mheidari-all | 47.89.186.170 |
| 72.1 | vless | 251.9 | 620.0 | 21.95 | 0.0 | 10.0 | 4.87 | 15.28 | mheidari-all | 154.193.55.183 |
| 71.53 | shadowsocks | 461.3 | 1276.2 | 17.1 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 68.168.222.210 |
| 71.16 | hysteria2 | 359.8 | 693.7 | 19.45 | 0.0 | 10.0 | 12.0 | 16.36 | Au1rxx-base64 | 62.210.124.146 |
| 70.13 | vmess | 363.9 | 1051.9 | 19.35 | 0.0 | 10.0 | 10.0 | 15.28 | mheidari-all | 67.220.95.3 |
| 69.69 | shadowsocks | 317.6 | 691.6 | 20.43 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 108.181.57.93 |
| 69.38 | shadowsocks | 338.5 | 617.5 | 19.94 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 108.181.118.10 |
| 69.32 | shadowsocks | 340.4 | 666.1 | 19.9 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 149.22.95.183 |
| 69.13 | shadowsocks | 326.3 | 607.0 | 20.22 | 0.0 | 10.0 | 12.57 | 16.36 | Au1rxx-base64 | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| DeltaKronecker-all | 0.901 | 0.825 | 171 | 5572 | prefer |
| Surfboard-tg-mixed | 0.858 | 0.786 | 70 | 5429 | prefer |
| mheidari-all | 0.756 | 0.676 | 476 | 19362 | prefer |
| Au1rxx-base64 | 0.646 | 0.631 | 176 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 4399 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4757 | observe |
| Epodonios-all | 0.255 | None | 0 | 6563 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3966 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6800 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4227 | observe |
| barry-far-vless | 0.255 | None | 0 | 4890 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4971 | observe |
| nscl5-all | 0.255 | None | 0 | 2435 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 87 |
| cn-block | TimeoutError | - | 78 |
| speed | ClientOSError | - | 42 |
| 204 | TimeoutError | - | 29 |
| geo | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
