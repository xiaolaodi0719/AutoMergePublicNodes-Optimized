# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-04 19:47:06 |
| 运行耗时 | 237.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86001 |
| 去重后节点 | 24515 |
| TCP 可达 | 3000 |
| 真实可用 | 490 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24515 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.1 |
| tcp | 37.0 |
| probe | 54.3 |
| real_test | 110.6 |
| generate | 28.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51148 |
| vmess | 13151 |
| shadowsocks | 10261 |
| trojan | 9991 |
| hysteria2 | 1174 |
| socks | 80 |
| shadowsocksr | 76 |
| http | 67 |
| anytls | 21 |
| hysteria | 19 |
| tuic | 13 |

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
| 81.47 | hysteria2 | 274.4 | 661.7 | 21.43 | 0.0 | 8.76 | 14.32 | 18.06 | Au1rxx-base64 | 159.223.157.129 |
| 78.76 | vless | 305.6 | 705.9 | 20.7 | 0.0 | 10.0 | 10.0 | 18.06 | Au1rxx-base64 | 67.220.73.204 |
| 78.64 | hysteria2 | 292.6 | 712.1 | 21.01 | 0.0 | 8.77 | 14.32 | 18.06 | Au1rxx-base64 | 138.124.68.188 |
| 77.35 | hysteria2 | 291.3 | 709.2 | 21.03 | 0.0 | 6.94 | 14.32 | 18.06 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 76.44 | shadowsocks | 246.4 | 612.2 | 22.07 | 0.0 | 8.82 | 11.76 | 18.06 | Au1rxx-base64 | 156.146.38.170 |
| 75.85 | shadowsocks | 246.0 | 621.5 | 22.08 | 0.0 | 8.82 | 11.76 | 18.06 | Au1rxx-base64 | 156.146.38.168 |
| 75.74 | vless | 279.9 | 555.4 | 21.3 | 0.0 | 10.0 | 10.0 | 18.06 | Au1rxx-base64 | 64.23.143.23 |
| 75.12 | vless | 330.8 | 755.1 | 20.12 | 0.0 | 10.0 | 10.0 | 18.06 | Au1rxx-base64 | 159.195.12.98 |
| 74.69 | vless | 408.0 | 653.5 | 18.33 | 0.0 | 10.0 | 10.0 | 18.06 | Au1rxx-base64 | 47.253.226.114 |
| 74.51 | shadowsocks | 255.2 | 632.9 | 21.87 | 0.0 | 8.82 | 11.76 | 18.06 | Au1rxx-base64 | 156.146.38.169 |
| 74.07 | vless | 296.3 | 549.8 | 20.92 | 0.0 | 10.0 | 10.0 | 18.06 | Au1rxx-base64 | 70.39.178.231 |
| 73.69 | trojan | 463.6 | 1177.5 | 17.05 | 0.0 | 10.0 | 14.3 | 18.06 | Au1rxx-base64 | 163.245.196.68 |
| 73.67 | hysteria2 | 322.4 | 396.6 | 20.32 | 0.13 | 8.75 | 14.32 | 18.06 | Au1rxx-base64 | 45.76.202.45 |
| 73.63 | shadowsocks | 282.7 | 662.2 | 21.23 | 0.0 | 8.82 | 11.76 | 18.06 | Au1rxx-base64 | 37.19.198.160 |
| 72.94 | shadowsocks | 338.0 | 824.5 | 19.95 | 0.0 | 10.0 | 11.76 | 18.06 | Au1rxx-base64 | 37.19.198.243 |
| 72.81 | vless | 325.6 | 603.8 | 20.24 | 0.0 | 10.0 | 10.0 | 18.06 | Au1rxx-base64 | 52.43.158.158 |
| 72.34 | vless | 408.5 | 943.0 | 18.32 | 0.0 | 10.0 | 10.0 | 18.06 | Au1rxx-base64 | 158.69.112.254 |
| 72.28 | http | 496.9 | 1207.9 | 16.28 | 0.0 | 10.0 | 14.43 | 18.94 | zhangkai | 138.199.35.217 |
| 72.16 | http | 491.5 | 1187.5 | 16.4 | 0.0 | 10.0 | 14.43 | 18.94 | zhangkai | 138.199.35.214 |
| 72.14 | trojan | 505.2 | 1286.8 | 16.08 | 0.0 | 10.0 | 14.3 | 18.06 | Au1rxx-base64 | 153.75.250.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.984 | 1.0 | 51 | 72 | prefer |
| Au1rxx-base64 | 0.949 | 0.889 | 423 | 1560 | prefer |
| Surfboard-tg-mixed | 0.573 | 0.6 | 15 | 5570 | observe |
| mheidari-all | 0.57 | 0.49 | 98 | 19967 | observe |
| DeltaKronecker-all | 0.446 | 0.8 | 5 | 5788 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 58 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5251 | observe |
| Epodonios-all | 0.255 | None | 0 | 6154 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6965 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4451 | observe |
| barry-far-vless | 0.255 | None | 0 | 4787 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5141 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 4655 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 34 |
| geo | ClientOSError | - | 19 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 11 |
| speed | TimeoutError | - | 11 |
| 204 | ProxyError | - | 7 |
| speed | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
