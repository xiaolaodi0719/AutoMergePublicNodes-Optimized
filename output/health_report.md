# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-06 03:00:35 |
| 运行耗时 | 261.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 88972 |
| 去重后节点 | 24629 |
| TCP 可达 | 3000 |
| 真实可用 | 545 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24629 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.5 |
| tcp | 37.2 |
| probe | 57.1 |
| real_test | 131.9 |
| generate | 25.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52808 |
| vmess | 13273 |
| trojan | 11112 |
| shadowsocks | 10127 |
| hysteria2 | 1391 |
| socks | 108 |
| shadowsocksr | 72 |
| http | 24 |
| anytls | 22 |
| hysteria | 21 |
| tuic | 14 |

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
| 83.26 | shadowsocks | 201.3 | 511.3 | 23.12 | 0.0 | 10.0 | 14.14 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 82.86 | shadowsocks | 204.0 | 518.1 | 23.06 | 0.0 | 10.0 | 14.14 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 82.73 | shadowsocks | 202.6 | 492.1 | 23.09 | 0.0 | 10.0 | 14.14 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 81.97 | shadowsocks | 257.1 | 615.6 | 21.83 | 0.0 | 10.0 | 14.14 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.78 | shadowsocks | 265.3 | 645.3 | 21.64 | 0.0 | 10.0 | 14.14 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 80.73 | shadowsocks | 259.9 | 626.7 | 21.76 | 0.0 | 10.0 | 14.14 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.46 | trojan | 261.9 | 523.9 | 21.72 | 0.0 | 10.0 | 14.53 | 20.0 | Au1rxx-base64 | 35.91.251.124 |
| 80.1 | shadowsocks | 303.2 | 760.2 | 20.76 | 0.0 | 10.0 | 14.14 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 79.94 | trojan | 270.8 | 553.8 | 21.51 | 0.0 | 10.0 | 14.53 | 20.0 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |
| 79.82 | trojan | 266.5 | 519.4 | 21.61 | 0.0 | 10.0 | 14.53 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 79.82 | trojan | 267.9 | 541.6 | 21.58 | 0.0 | 10.0 | 14.53 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 79.8 | trojan | 274.1 | 560.4 | 21.43 | 0.0 | 10.0 | 14.53 | 20.0 | Au1rxx-base64 | 44.242.235.129 |
| 78.7 | http | 411.1 | 1152.5 | 18.26 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 78.69 | http | 411.7 | 1160.4 | 18.25 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 78.63 | shadowsocks | 185.2 | 467.0 | 23.49 | 0.0 | 10.0 | 14.14 | 20.0 | Au1rxx-base64 | 216.105.168.18 |
| 78.62 | http | 414.7 | 1169.6 | 18.18 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 78.52 | http | 419.0 | 1172.4 | 18.08 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 77.76 | shadowsocks | 201.1 | 498.1 | 23.12 | 0.0 | 10.0 | 14.14 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 77.39 | trojan | 270.4 | 548.4 | 21.52 | 0.0 | 10.0 | 14.53 | 20.0 | Au1rxx-base64 | natural-collie.rooster465.autos |
| 77.38 | trojan | 342.7 | 795.4 | 19.85 | 0.0 | 10.0 | 14.53 | 20.0 | Au1rxx-base64 | 64.94.95.115 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.963 | 380 | 1395 | prefer |
| zhangkai | 0.789 | 1.0 | 15 | 25 | prefer |
| Surfboard-tg-mixed | 0.649 | 0.57 | 200 | 5908 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 5214 | observe |
| nscl5-all | 0.272 | 0.5 | 2 | 1621 | observe |
| mheidari-all | 0.269 | 0.187 | 241 | 21048 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5260 | observe |
| Epodonios-all | 0.255 | None | 0 | 6515 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7399 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4791 | observe |
| barry-far-vless | 0.255 | None | 0 | 5104 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5206 | observe |
| Au1rxx-clash | 0.231 | None | 0 | 1395 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 151 |
| speed | TimeoutError | - | 50 |
| speed | ClientOSError | - | 45 |
| cn-block | TimeoutError | - | 33 |
| geo | ClientOSError | - | 32 |
| 204 | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | status | 403 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
