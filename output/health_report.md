# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-24 13:02:50 |
| 运行耗时 | 243.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 78546 |
| 去重后节点 | 21951 |
| TCP 可达 | 3000 |
| 真实可用 | 558 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21951 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.7 |
| geo | 1.3 |
| tcp | 34.8 |
| probe | 51.4 |
| real_test | 120.3 |
| generate | 31.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49140 |
| shadowsocks | 10295 |
| vmess | 9988 |
| trojan | 7652 |
| hysteria2 | 1098 |
| http | 164 |
| shadowsocksr | 122 |
| socks | 77 |
| hysteria | 7 |
| tuic | 3 |

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
| 82.45 | shadowsocks | 239.2 | 655.9 | 22.24 | 0.0 | 10.0 | 14.21 | 20.0 | mheidari-all | 149.22.95.183 |
| 81.9 | trojan | 215.6 | 518.5 | 22.79 | 0.0 | 10.0 | 12.47 | 19.14 | Au1rxx-base64 | 35.91.251.124 |
| 81.56 | shadowsocks | 227.9 | 628.2 | 22.5 | 0.0 | 9.71 | 14.21 | 19.14 | Au1rxx-base64 | 154.12.240.141 |
| 80.71 | shadowsocks | 252.8 | 545.3 | 21.93 | 0.0 | 9.68 | 14.21 | 19.14 | Au1rxx-base64 | 94.72.127.55 |
| 80.21 | shadowsocks | 284.9 | 599.5 | 21.18 | 0.0 | 9.68 | 14.21 | 19.14 | Au1rxx-base64 | 94.72.127.58 |
| 80.0 | trojan | 194.9 | 460.7 | 23.27 | 0.0 | 7.62 | 12.47 | 19.14 | Au1rxx-base64 | sincere-gelding.rooster465.autos |
| 79.42 | vless | 209.0 | 554.7 | 22.94 | 0.0 | 9.69 | 7.65 | 19.14 | Au1rxx-base64 | 15.204.97.197 |
| 79.04 | shadowsocks | 349.3 | 881.7 | 19.69 | 0.0 | 10.0 | 14.21 | 19.14 | Au1rxx-base64 | 154.12.242.150 |
| 78.44 | hysteria2 | 352.3 | 742.3 | 19.62 | 0.0 | 10.0 | 14.29 | 20.0 | mheidari-all | 159.223.157.129 |
| 77.75 | vless | 294.4 | 810.1 | 20.96 | 0.0 | 10.0 | 7.65 | 19.14 | Au1rxx-base64 | 15.204.97.209 |
| 77.39 | vless | 297.0 | 811.6 | 20.9 | 0.0 | 9.7 | 7.65 | 19.14 | Au1rxx-base64 | 15.204.97.214 |
| 77.35 | vless | 298.6 | 824.0 | 20.87 | 0.0 | 9.69 | 7.65 | 19.14 | Au1rxx-base64 | 15.204.97.216 |
| 77.24 | shadowsocks | 257.3 | 267.6 | 21.82 | 4.96 | 10.0 | 14.21 | 17.5 | Surfboard-tg-mixed | 149.22.87.241 |
| 77.21 | vless | 312.0 | 609.5 | 20.56 | 0.0 | 10.0 | 7.65 | 20.0 | mheidari-all | 104.21.85.220 |
| 76.49 | shadowsocks | 323.0 | 694.6 | 20.3 | 0.0 | 10.0 | 14.21 | 20.0 | mheidari-all | 173.244.56.9 |
| 76.34 | shadowsocks | 282.7 | 320.4 | 21.23 | 2.98 | 9.71 | 14.21 | 19.14 | Au1rxx-base64 | 149.22.87.240 |
| 75.81 | shadowsocks | 280.7 | 334.2 | 21.28 | 2.47 | 9.69 | 14.21 | 19.14 | Au1rxx-base64 | 149.22.87.204 |
| 75.36 | shadowsocks | 327.5 | 690.8 | 20.2 | 0.0 | 10.0 | 14.21 | 20.0 | mheidari-all | 156.146.38.170 |
| 75.32 | shadowsocks | 260.0 | 637.2 | 21.76 | 0.0 | 9.71 | 14.21 | 19.14 | Au1rxx-base64 | 152.67.250.45 |
| 75.23 | shadowsocks | 326.7 | 673.0 | 20.22 | 0.0 | 10.0 | 14.21 | 20.0 | mheidari-all | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | 0.873 | 361 | 1628 | prefer |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| DeltaKronecker-all | 0.843 | 0.772 | 57 | 5914 | prefer |
| mheidari-all | 0.83 | 0.756 | 86 | 14541 | prefer |
| Surfboard-tg-mixed | 0.821 | 0.745 | 145 | 6395 | prefer |
| nscl5-all | 0.352 | 1.0 | 2 | 1008 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4899 | observe |
| Epodonios-all | 0.255 | None | 0 | 6919 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7302 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5345 | observe |
| barry-far-vless | 0.255 | None | 0 | 5633 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4097 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1629 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 16 |
| 204 | ProxyError | - | 15 |
| speed | TimeoutError | - | 13 |
| geo | ClientOSError | - | 11 |
| cn-block | ClientOSError | - | 8 |
| speed | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
