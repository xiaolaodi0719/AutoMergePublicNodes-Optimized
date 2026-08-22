# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-22 18:42:01 |
| 运行耗时 | 309.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 86103 |
| 去重后节点 | 23834 |
| TCP 可达 | 3000 |
| 真实可用 | 700 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23834 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.5 |
| tcp | 40.6 |
| probe | 62.4 |
| real_test | 154.4 |
| generate | 44.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50371 |
| trojan | 12973 |
| shadowsocks | 10484 |
| vmess | 10281 |
| hysteria2 | 1511 |
| http | 168 |
| shadowsocksr | 163 |
| socks | 117 |
| anytls | 16 |
| hysteria | 11 |
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
| 83.11 | trojan | 248.3 | 605.1 | 22.03 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 64.94.95.114 |
| 81.57 | trojan | 246.3 | 598.2 | 22.08 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 64.94.95.115 |
| 81.55 | shadowsocks | 236.9 | 604.6 | 22.29 | 0.0 | 10.0 | 13.4 | 19.86 | Au1rxx-base64 | 156.146.38.170 |
| 81.52 | shadowsocks | 238.3 | 613.5 | 22.26 | 0.0 | 10.0 | 13.4 | 19.86 | Au1rxx-base64 | 156.146.38.169 |
| 81.15 | trojan | 344.0 | 820.2 | 19.81 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 64.94.95.117 |
| 80.91 | shadowsocks | 251.4 | 599.7 | 21.96 | 0.0 | 10.0 | 13.4 | 19.86 | Au1rxx-base64 | 94.72.127.55 |
| 80.59 | trojan | 327.9 | 781.7 | 20.19 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 34.94.125.227 |
| 80.4 | shadowsocks | 255.0 | 598.9 | 21.88 | 0.0 | 10.0 | 13.4 | 19.86 | Au1rxx-base64 | 94.72.127.58 |
| 79.78 | shadowsocks | 264.6 | 625.8 | 21.65 | 0.0 | 10.0 | 13.4 | 19.86 | Au1rxx-base64 | 23.150.248.20 |
| 79.66 | trojan | 266.0 | 529.5 | 21.62 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 35.88.120.18 |
| 79.45 | trojan | 277.3 | 563.4 | 21.36 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 35.160.249.189 |
| 79.44 | trojan | 277.1 | 555.3 | 21.36 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 35.92.245.6 |
| 79.44 | trojan | 280.6 | 574.6 | 21.28 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 44.255.190.116 |
| 79.41 | trojan | 272.0 | 540.6 | 21.48 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 34.210.213.17 |
| 79.37 | trojan | 281.2 | 566.4 | 21.27 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 44.246.163.102 |
| 79.35 | trojan | 284.7 | 572.3 | 21.19 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 35.91.251.124 |
| 79.34 | trojan | 268.7 | 524.1 | 21.56 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 34.223.2.163 |
| 79.28 | trojan | 286.5 | 589.6 | 21.15 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 54.188.176.255 |
| 79.04 | trojan | 289.4 | 586.8 | 21.08 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 35.90.27.143 |
| 78.99 | trojan | 296.2 | 612.2 | 20.92 | 0.0 | 10.0 | 14.48 | 19.86 | Au1rxx-base64 | 54.213.46.211 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | 1.0 | 111 | 144 | prefer |
| Au1rxx-base64 | 0.988 | 0.915 | 485 | 1853 | prefer |
| mheidari-all | 0.853 | 0.781 | 73 | 14443 | prefer |
| Surfboard-tg-mixed | 0.747 | 0.669 | 124 | 6394 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5974 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 176 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5096 | observe |
| DeltaKronecker-all | 0.255 | 0.222 | 9 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 6972 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7145 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5216 | observe |
| barry-far-vless | 0.255 | None | 0 | 5527 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4074 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 30 |
| 204 | TimeoutError | - | 21 |
| geo | TimeoutError | - | 20 |
| speed | TimeoutError | - | 10 |
| speed | ClientOSError | - | 7 |
| geo | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
