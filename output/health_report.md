# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 17:02:47 |
| 运行耗时 | 445.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96380 |
| 去重后节点 | 26691 |
| TCP 可达 | 3000 |
| 真实可用 | 193 |
| Verified 输出 | 193 |
| Global 输出 | 207 |
| All 输出 | 26691 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.5 |
| tcp | 44.5 |
| probe | 178.9 |
| real_test | 118.8 |
| generate | 94.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57054 |
| vmess | 17168 |
| shadowsocks | 12399 |
| trojan | 7904 |
| hysteria2 | 1347 |
| http | 239 |
| shadowsocksr | 166 |
| socks | 58 |
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
| 78.04 | vless | 245.2 | 662.1 | 22.1 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 159.89.87.21 |
| 77.37 | shadowsocks | 246.0 | 680.3 | 22.08 | 0.0 | 10.0 | 12.73 | 16.56 | Au1rxx-base64 | 37.19.198.160 |
| 77.05 | shadowsocks | 282.6 | 778.9 | 21.24 | 0.0 | 10.0 | 12.73 | 17.08 | mheidari-all | 37.19.198.244 |
| 76.6 | vless | 307.4 | 744.2 | 20.66 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 169.40.42.225 |
| 74.7 | vless | 389.6 | 1069.8 | 18.76 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 185.95.231.156 |
| 74.63 | vless | 392.6 | 948.0 | 18.69 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 169.40.42.229 |
| 74.62 | vless | 392.9 | 1069.2 | 18.68 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 169.40.42.163 |
| 74.01 | vless | 419.2 | 1145.0 | 18.07 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 169.40.42.104 |
| 73.89 | vless | 357.9 | 970.7 | 19.49 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 169.40.42.231 |
| 73.85 | trojan | 364.9 | 998.9 | 19.33 | 0.0 | 8.71 | 12.25 | 16.56 | Au1rxx-base64 | 69.164.240.85 |
| 73.03 | vless | 461.8 | 796.4 | 17.09 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 169.40.42.35 |
| 72.44 | vless | 370.0 | 969.3 | 19.21 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 2.24.124.64 |
| 72.37 | vless | 341.3 | 721.5 | 19.88 | 0.0 | 8.67 | 9.38 | 16.56 | Au1rxx-base64 | 5.34.178.120 |
| 71.92 | vless | 315.0 | 669.8 | 20.49 | 0.0 | 10.0 | 9.38 | 17.08 | mheidari-all | 216.227.161.95 |
| 71.62 | vless | 403.5 | 1051.5 | 18.44 | 0.0 | 10.0 | 9.38 | 16.56 | Au1rxx-base64 | 169.40.42.90 |
| 71.17 | shadowsocks | 321.5 | 763.7 | 20.33 | 0.0 | 10.0 | 12.73 | 15.18 | Surfboard-tg-mixed | 156.146.38.169 |
| 70.8 | vless | 364.6 | 1025.8 | 19.34 | 0.0 | 10.0 | 9.38 | 17.08 | mheidari-all | 147.182.212.232 |
| 70.8 | hysteria2 | 451.7 | 904.7 | 17.32 | 0.0 | 9.87 | 13.64 | 16.56 | Au1rxx-base64 | 64.188.98.171 |
| 70.28 | hysteria2 | 476.2 | 1018.0 | 16.76 | 0.0 | 10.0 | 13.64 | 17.08 | mheidari-all | 62.210.124.146 |
| 69.17 | hysteria2 | 408.4 | 734.6 | 18.32 | 0.0 | 10.0 | 13.64 | 15.18 | Surfboard-tg-mixed | 130.49.161.70 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.898 | 0.83 | 53 | 7066 | prefer |
| mheidari-all | 0.895 | 0.827 | 52 | 24062 | prefer |
| Au1rxx-base64 | 0.803 | 0.746 | 114 | 1529 | prefer |
| ermaozi | 0.451 | 0.425 | 40 | 573 | observe |
| DeltaKronecker-all | 0.337 | 0.429 | 7 | 3641 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7538 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10202 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5426 | observe |
| barry-far-vless | 0.255 | None | 0 | 5601 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 26 |
| cn-block | TimeoutError | - | 17 |
| speed | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 8 |
| geo | ClientOSError | - | 3 |
| speed | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 292 | 193 | - |
| global | False | 300 | 207 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
