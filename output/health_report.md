# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 11:05:57 |
| 运行耗时 | 669.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83513 |
| 去重后节点 | 22979 |
| TCP 可达 | 3000 |
| 真实可用 | 395 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22979 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.6 |
| tcp | 38.1 |
| probe | 284.6 |
| real_test | 256.0 |
| generate | 83.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49723 |
| vmess | 13256 |
| shadowsocks | 10074 |
| trojan | 8223 |
| hysteria2 | 1378 |
| http | 649 |
| shadowsocksr | 127 |
| socks | 69 |
| hysteria | 8 |
| anytls | 4 |
| tuic | 2 |

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
| 81.14 | hysteria2 | 249.1 | 663.6 | 22.01 | 0.0 | 10.0 | 14.21 | 16.02 | mheidari-all | 159.223.157.129 |
| 80.6 | shadowsocks | 250.8 | 624.5 | 21.97 | 0.0 | 10.0 | 14.51 | 18.62 | Au1rxx-base64 | 38.180.135.156 |
| 78.45 | shadowsocks | 343.6 | 970.9 | 19.82 | 0.0 | 10.0 | 14.51 | 18.62 | Au1rxx-base64 | 15.204.247.206 |
| 78.12 | shadowsocks | 267.4 | 721.3 | 21.59 | 0.0 | 10.0 | 14.51 | 16.02 | mheidari-all | 37.19.198.236 |
| 77.78 | shadowsocks | 289.7 | 666.6 | 21.07 | 0.0 | 10.0 | 14.51 | 18.62 | Au1rxx-base64 | 156.146.38.169 |
| 77.76 | shadowsocks | 282.5 | 643.0 | 21.24 | 0.0 | 10.0 | 14.51 | 18.62 | Au1rxx-base64 | 156.146.38.167 |
| 77.48 | shadowsocks | 234.7 | 619.4 | 22.35 | 0.0 | 10.0 | 14.51 | 14.62 | Surfboard-tg-mixed | 198.98.53.130 |
| 76.79 | vless | 286.8 | 625.0 | 21.14 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 169.40.42.133 |
| 76.76 | vless | 286.6 | 740.5 | 21.14 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 169.40.42.74 |
| 76.74 | shadowsocks | 417.4 | 1025.9 | 18.11 | 0.0 | 10.0 | 14.51 | 18.62 | Au1rxx-base64 | 15.204.247.175 |
| 76.61 | shadowsocks | 289.4 | 794.4 | 21.08 | 0.0 | 10.0 | 14.51 | 16.02 | mheidari-all | 37.19.198.160 |
| 76.51 | vless | 299.0 | 728.6 | 20.86 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 169.40.42.15 |
| 76.41 | vless | 303.2 | 738.9 | 20.76 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 169.40.42.173 |
| 76.3 | vless | 308.1 | 744.9 | 20.65 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 169.40.42.229 |
| 76.2 | vless | 312.1 | 815.7 | 20.55 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 169.40.42.163 |
| 76.13 | hysteria2 | 330.3 | 595.1 | 20.13 | 0.0 | 10.0 | 14.21 | 18.62 | Au1rxx-base64 | 66.94.121.46 |
| 76.12 | vless | 315.5 | 852.8 | 20.47 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 137.184.218.169 |
| 76.07 | vless | 318.0 | 841.0 | 20.42 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 169.40.42.223 |
| 75.96 | vless | 322.4 | 846.7 | 20.31 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 169.40.42.179 |
| 75.56 | vless | 339.8 | 865.1 | 19.91 | 0.0 | 10.0 | 7.03 | 18.62 | Au1rxx-base64 | 169.40.42.232 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.908 | 0.846 | 246 | 1622 | prefer |
| ermaozi | 0.748 | 0.744 | 43 | 378 | prefer |
| mheidari-all | 0.712 | 0.636 | 66 | 15778 | prefer |
| Surfboard-tg-mixed | 0.706 | 0.628 | 145 | 7294 | prefer |
| DeltaKronecker-all | 0.509 | 0.426 | 47 | 6040 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7751 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8957 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5763 | observe |
| barry-far-vless | 0.255 | None | 0 | 5979 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1622 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 29 |
| geo | TimeoutError | - | 26 |
| geo | ClientOSError | - | 23 |
| 204 | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 17 |
| speed | TimeoutError | - | 16 |
| speed | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
