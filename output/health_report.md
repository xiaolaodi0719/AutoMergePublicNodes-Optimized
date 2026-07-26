# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-26 03:33:23 |
| 运行耗时 | 317.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80527 |
| 去重后节点 | 22462 |
| TCP 可达 | 3000 |
| 真实可用 | 904 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22462 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.5 |
| tcp | 31.3 |
| probe | 66.0 |
| real_test | 191.7 |
| generate | 21.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45073 |
| trojan | 14617 |
| vmess | 10121 |
| shadowsocks | 9979 |
| hysteria2 | 475 |
| http | 81 |
| shadowsocksr | 79 |
| socks | 77 |
| hysteria | 13 |
| tuic | 11 |
| anytls | 1 |

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
| 70.03 | vless | 284.2 | 672.1 | 21.2 | 0.0 | 10.0 | 5.3 | 14.84 | mheidari-all | 45.206.5.122 |
| 66.73 | trojan | 480.6 | 1306.3 | 16.65 | 0.0 | 10.0 | 13.34 | 9.74 | Au1rxx-base64 | 148.72.168.35 |
| 66.63 | trojan | 439.1 | 1147.0 | 17.61 | 0.0 | 10.0 | 13.34 | 9.74 | Au1rxx-base64 | 153.75.250.171 |
| 66.36 | shadowsocks | 265.9 | 658.0 | 21.62 | 0.0 | 10.0 | 9.0 | 9.74 | Au1rxx-base64 | 198.98.53.130 |
| 66.32 | shadowsocks | 267.6 | 656.8 | 21.58 | 0.0 | 10.0 | 9.0 | 9.74 | Au1rxx-base64 | 156.146.38.169 |
| 66.31 | shadowsocks | 268.2 | 654.4 | 21.57 | 0.0 | 10.0 | 9.0 | 9.74 | Au1rxx-base64 | 156.146.38.167 |
| 66.28 | shadowsocks | 269.5 | 655.7 | 21.54 | 0.0 | 10.0 | 9.0 | 9.74 | Au1rxx-base64 | 156.146.38.168 |
| 66.01 | shadowsocks | 281.1 | 697.4 | 21.27 | 0.0 | 10.0 | 9.0 | 9.74 | Au1rxx-base64 | 37.19.198.243 |
| 65.99 | trojan | 497.0 | 841.1 | 16.27 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 104.19.64.105 |
| 65.93 | trojan | 492.2 | 808.1 | 16.38 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 45.130.125.160 |
| 65.92 | shadowsocks | 284.8 | 716.1 | 21.18 | 0.0 | 10.0 | 9.0 | 9.74 | Au1rxx-base64 | 37.19.198.160 |
| 65.9 | trojan | 501.7 | 846.7 | 16.16 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 172.64.147.227 |
| 65.88 | trojan | 497.4 | 837.6 | 16.26 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 172.64.147.24 |
| 65.87 | trojan | 505.0 | 809.0 | 16.09 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 104.16.174.71 |
| 65.76 | trojan | 501.0 | 817.1 | 16.18 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 104.16.174.44 |
| 65.64 | trojan | 507.6 | 820.4 | 16.03 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 104.16.174.6 |
| 65.62 | trojan | 501.0 | 813.6 | 16.18 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 104.17.121.9 |
| 65.5 | trojan | 507.4 | 829.4 | 16.03 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 172.64.155.209 |
| 65.5 | trojan | 510.6 | 851.2 | 15.96 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 104.18.7.147 |
| 65.47 | trojan | 509.4 | 812.1 | 15.99 | 0.0 | 10.0 | 13.34 | 14.84 | mheidari-all | 212.183.88.136 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 76 | 119 | prefer |
| Au1rxx-base64 | 0.975 | 0.923 | 430 | 1341 | prefer |
| Surfboard-tg-mixed | 0.961 | 0.892 | 65 | 5462 | prefer |
| DeltaKronecker-all | 0.699 | 0.62 | 216 | 5838 | observe |
| mheidari-all | 0.655 | 0.575 | 412 | 17224 | observe |
| xiaoji235-airport-v2ray-all | 0.32 | 1.0 | 1 | 1624 | observe |
| tg-ConfigV2rayNG | 0.263 | 1.0 | 1 | 200 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4879 | observe |
| Epodonios-all | 0.255 | None | 0 | 6569 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6505 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4196 | observe |
| barry-far-vless | 0.255 | None | 0 | 4852 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4980 | observe |
| nscl5-all | 0.255 | None | 0 | 2896 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 100 |
| speed | ClientOSError | - | 92 |
| speed | TimeoutError | - | 38 |
| geo | ClientOSError | - | 27 |
| cn-block | TimeoutError | - | 23 |
| 204 | ProxyError | - | 7 |
| 204 | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
