# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 16:40:40 |
| 运行耗时 | 549.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 97200 |
| 去重后节点 | 26542 |
| TCP 可达 | 3000 |
| 真实可用 | 415 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26542 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.5 |
| tcp | 43.2 |
| probe | 230.0 |
| real_test | 186.4 |
| generate | 82.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60136 |
| vmess | 14763 |
| shadowsocks | 11172 |
| trojan | 8774 |
| hysteria2 | 1497 |
| http | 562 |
| shadowsocksr | 171 |
| socks | 74 |
| anytls | 25 |
| hysteria | 18 |
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
| 81.34 | vless | 196.2 | 515.2 | 23.24 | 0.0 | 9.5 | 9.8 | 18.8 | Au1rxx-base64 | 172.235.43.210 |
| 80.43 | shadowsocks | 201.5 | 521.3 | 23.11 | 0.0 | 10.0 | 14.02 | 18.8 | Au1rxx-base64 | 129.146.124.141 |
| 79.8 | shadowsocks | 277.3 | 709.5 | 21.36 | 0.0 | 9.62 | 14.02 | 18.8 | Au1rxx-base64 | 173.244.56.6 |
| 78.84 | shadowsocks | 266.8 | 652.6 | 21.6 | 0.0 | 10.0 | 14.02 | 18.8 | Au1rxx-base64 | 156.146.38.170 |
| 78.8 | shadowsocks | 265.4 | 639.4 | 21.63 | 0.0 | 9.54 | 14.02 | 18.8 | Au1rxx-base64 | 156.146.38.169 |
| 78.24 | shadowsocks | 232.2 | 534.8 | 22.4 | 0.0 | 10.0 | 14.02 | 16.32 | mheidari-all | 108.181.118.10 |
| 77.39 | shadowsocks | 196.7 | 521.6 | 23.22 | 0.0 | 10.0 | 14.02 | 16.32 | mheidari-all | 192.3.247.109 |
| 77.26 | vless | 200.2 | 517.0 | 23.14 | 0.0 | 10.0 | 9.8 | 16.32 | mheidari-all | 172.233.139.46 |
| 77.17 | vless | 290.5 | 717.3 | 21.05 | 0.0 | 10.0 | 9.8 | 16.32 | mheidari-all | 47.251.108.158 |
| 77.04 | shadowsocks | 277.7 | 624.6 | 21.35 | 0.0 | 9.59 | 14.02 | 18.8 | Au1rxx-base64 | 23.150.248.20 |
| 76.38 | shadowsocks | 245.1 | 490.6 | 22.1 | 0.0 | 10.0 | 14.02 | 15.76 | Surfboard-tg-mixed | 108.181.0.177 |
| 76.37 | vless | 198.2 | 518.4 | 23.19 | 0.0 | 9.58 | 9.8 | 18.8 | Au1rxx-base64 | 192.3.247.109 |
| 74.53 | vless | 250.8 | 522.6 | 21.97 | 0.0 | 9.48 | 9.8 | 18.8 | Au1rxx-base64 | 31.58.50.200 |
| 74.21 | shadowsocks | 368.7 | 848.8 | 19.24 | 0.0 | 9.61 | 14.02 | 18.8 | Au1rxx-base64 | 149.22.95.183 |
| 72.96 | hysteria2 | 396.1 | 632.4 | 18.61 | 0.0 | 9.58 | 13.5 | 18.8 | Au1rxx-base64 | 66.94.121.46 |
| 72.53 | http | 239.7 | 541.0 | 22.23 | 0.0 | 10.0 | 10.5 | 15.2 | ermaozi | 138.199.35.216 |
| 72.46 | trojan | 379.4 | 1056.1 | 19.0 | 0.0 | 10.0 | 9.64 | 16.32 | mheidari-all | 34.94.125.227 |
| 72.32 | vless | 355.3 | 713.5 | 19.55 | 0.0 | 9.55 | 9.8 | 18.8 | Au1rxx-base64 | 195.211.98.43 |
| 71.73 | shadowsocks | 365.0 | 794.2 | 19.33 | 0.0 | 9.61 | 14.02 | 18.8 | Au1rxx-base64 | 37.19.198.244 |
| 71.65 | http | 242.4 | 544.8 | 22.17 | 0.0 | 10.0 | 10.5 | 15.2 | ermaozi | 138.199.35.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.96 | 0.896 | 270 | 1665 | prefer |
| ermaozi | 0.793 | 0.8 | 30 | 291 | prefer |
| Surfboard-tg-mixed | 0.708 | 0.634 | 41 | 7138 | prefer |
| mheidari-all | 0.597 | 0.517 | 234 | 22163 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 88 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5131 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 6471 | observe |
| Epodonios-all | 0.255 | None | 0 | 7512 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9407 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5827 | observe |
| barry-far-vless | 0.255 | None | 0 | 6042 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4187 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 42 |
| geo | ClientOSError | - | 31 |
| 204 | TimeoutError | - | 31 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 20 |
| speed | TimeoutError | - | 9 |
| speed | ClientOSError | - | 5 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
