# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-05 14:59:10 |
| 运行耗时 | 298.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83843 |
| 去重后节点 | 22680 |
| TCP 可达 | 3000 |
| 真实可用 | 609 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22680 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.6 |
| tcp | 37.6 |
| probe | 89.4 |
| real_test | 127.0 |
| generate | 36.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53144 |
| vmess | 11412 |
| shadowsocks | 9707 |
| trojan | 8017 |
| hysteria2 | 1217 |
| http | 146 |
| shadowsocksr | 130 |
| socks | 50 |
| hysteria | 10 |
| tuic | 10 |

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
| 84.25 | vless | 189.1 | 487.2 | 23.4 | 0.0 | 10.0 | 11.67 | 19.18 | Au1rxx-base64 | 172.235.43.210 |
| 83.61 | vless | 216.8 | 562.0 | 22.76 | 0.0 | 10.0 | 11.67 | 19.18 | Au1rxx-base64 | 172.233.139.46 |
| 82.48 | vless | 222.4 | 573.5 | 22.63 | 0.0 | 10.0 | 11.67 | 19.18 | Au1rxx-base64 | 38.209.125.45 |
| 81.88 | vless | 205.0 | 522.2 | 23.03 | 0.0 | 10.0 | 11.67 | 19.18 | Au1rxx-base64 | 23.94.227.94 |
| 81.84 | http | 203.7 | 515.6 | 23.06 | 0.0 | 10.0 | 14.5 | 19.28 | zhangkai | 138.199.35.198 |
| 81.53 | vless | 306.5 | 804.6 | 20.68 | 0.0 | 10.0 | 11.67 | 19.18 | Au1rxx-base64 | 15.204.97.216 |
| 81.32 | shadowsocks | 222.2 | 550.3 | 22.63 | 0.0 | 10.0 | 14.01 | 19.18 | Au1rxx-base64 | 108.181.0.177 |
| 81.24 | shadowsocks | 226.0 | 564.9 | 22.55 | 0.0 | 10.0 | 14.01 | 19.18 | Au1rxx-base64 | 108.181.118.10 |
| 80.98 | hysteria2 | 390.6 | 1073.9 | 18.74 | 0.0 | 10.0 | 14.06 | 19.18 | Au1rxx-base64 | 66.94.121.46 |
| 80.66 | shadowsocks | 272.5 | 631.1 | 21.47 | 0.0 | 10.0 | 14.01 | 19.18 | Au1rxx-base64 | 173.244.56.6 |
| 80.26 | vless | 361.6 | 997.4 | 19.41 | 0.0 | 10.0 | 11.67 | 19.18 | Au1rxx-base64 | 172.235.38.85 |
| 79.95 | shadowsocks | 219.5 | 508.7 | 22.7 | 0.0 | 10.0 | 14.01 | 17.24 | mheidari-all | 149.22.95.183 |
| 79.57 | vless | 245.9 | 264.8 | 22.09 | 5.07 | 9.91 | 11.67 | 17.32 | Surfboard-tg-mixed | 31.76.91.72 |
| 79.53 | vless | 198.6 | 532.2 | 23.18 | 0.0 | 10.0 | 11.67 | 19.18 | Au1rxx-base64 | 204.44.127.222 |
| 79.32 | shadowsocks | 246.6 | 566.7 | 22.07 | 0.0 | 10.0 | 14.01 | 17.24 | mheidari-all | 173.244.56.9 |
| 79.25 | vless | 216.2 | 549.6 | 22.77 | 0.0 | 10.0 | 11.67 | 19.18 | Au1rxx-base64 | 38.127.121.44 |
| 76.85 | vless | 306.1 | 237.0 | 20.69 | 6.11 | 8.56 | 11.67 | 19.18 | Au1rxx-base64 | hk2-r.link-t7.com |
| 76.76 | vless | 235.4 | 528.0 | 22.33 | 0.0 | 10.0 | 11.67 | 17.32 | Surfboard-tg-mixed | 162.159.39.218 |
| 76.14 | trojan | 267.5 | 714.5 | 21.59 | 0.0 | 10.0 | 9.81 | 17.24 | mheidari-all | 34.94.125.227 |
| 76.1 | vless | 541.0 | 1487.8 | 15.25 | 0.0 | 10.0 | 11.67 | 19.18 | Au1rxx-base64 | 51.81.203.63 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | 0.915 | 399 | 1685 | prefer |
| zhangkai | 0.96 | 1.0 | 20 | 144 | prefer |
| Surfboard-tg-mixed | 0.833 | 0.757 | 148 | 7365 | prefer |
| mheidari-all | 0.828 | 0.752 | 129 | 16245 | prefer |
| DeltaKronecker-all | 0.593 | 1.0 | 7 | 6212 | observe |
| tg-oneclickvpnkeys | 0.518 | 1.0 | 7 | 118 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| Epodonios-all | 0.255 | None | 0 | 7776 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8453 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6206 | observe |
| barry-far-vless | 0.255 | None | 0 | 6414 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4095 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1685 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 22 |
| geo | ClientOSError | - | 21 |
| 204 | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 12 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyError | - | 7 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | TimeoutError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
