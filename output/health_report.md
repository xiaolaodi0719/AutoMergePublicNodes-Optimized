# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 21:15:33 |
| 运行耗时 | 565.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89335 |
| 去重后节点 | 24603 |
| TCP 可达 | 3000 |
| 真实可用 | 396 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24603 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.5 |
| tcp | 41.3 |
| probe | 244.5 |
| real_test | 191.9 |
| generate | 80.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52838 |
| vmess | 14367 |
| shadowsocks | 10782 |
| trojan | 9065 |
| hysteria2 | 1477 |
| http | 592 |
| shadowsocksr | 129 |
| socks | 73 |
| hysteria | 8 |
| tuic | 2 |
| anytls | 2 |

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
| 78.29 | shadowsocks | 255.4 | 632.4 | 21.87 | 0.0 | 10.0 | 13.26 | 17.5 | Au1rxx-base64 | 156.146.38.168 |
| 78.15 | vless | 304.0 | 771.1 | 20.74 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 198.251.78.29 |
| 77.98 | shadowsocks | 275.6 | 683.9 | 21.4 | 0.0 | 10.0 | 13.26 | 17.32 | mheidari-all | 37.19.198.244 |
| 77.58 | shadowsocks | 256.1 | 623.7 | 21.85 | 0.0 | 10.0 | 13.26 | 17.5 | Au1rxx-base64 | 156.146.38.169 |
| 77.14 | vless | 320.9 | 776.6 | 20.35 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.74 |
| 76.96 | vless | 321.8 | 654.2 | 20.33 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.202 |
| 76.68 | vless | 302.7 | 688.5 | 20.77 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.133 |
| 76.48 | vless | 273.2 | 625.5 | 21.45 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 195.123.235.177 |
| 76.23 | vless | 312.7 | 701.0 | 20.54 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.16 |
| 76.2 | shadowsocks | 265.8 | 665.2 | 21.62 | 0.0 | 10.0 | 13.26 | 17.32 | mheidari-all | 37.19.198.160 |
| 76.09 | vless | 341.4 | 733.6 | 19.87 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.163 |
| 76.08 | vless | 289.9 | 680.5 | 21.07 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.184 |
| 76.03 | vless | 361.1 | 866.0 | 19.42 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.231 |
| 75.55 | vless | 312.1 | 764.3 | 20.55 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.225 |
| 75.48 | vless | 332.0 | 788.0 | 20.09 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 66.70.179.198 |
| 75.46 | shadowsocks | 252.0 | 621.5 | 21.94 | 0.0 | 10.0 | 13.26 | 17.5 | Au1rxx-base64 | 156.146.38.170 |
| 75.1 | shadowsocks | 277.6 | 681.8 | 21.35 | 0.0 | 10.0 | 13.26 | 17.32 | mheidari-all | 37.19.198.236 |
| 75.1 | vless | 300.5 | 728.9 | 20.82 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.35 |
| 75.08 | vless | 315.0 | 777.7 | 20.49 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 169.40.42.173 |
| 75.02 | vless | 430.8 | 1098.6 | 17.81 | 0.0 | 10.0 | 9.91 | 17.5 | Au1rxx-base64 | 130.107.73.148 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.929 | 0.866 | 268 | 1651 | prefer |
| Surfboard-tg-mixed | 0.867 | 0.797 | 59 | 7483 | prefer |
| mheidari-all | 0.867 | 0.795 | 78 | 17985 | prefer |
| ermaozi | 0.847 | 0.857 | 28 | 353 | prefer |
| DeltaKronecker-all | 0.823 | 0.758 | 33 | 6081 | prefer |
| tg-oneclickvpnkeys | 0.364 | 1.0 | 3 | 140 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4234 | observe |
| Pawdroid | 0.256 | 1.0 | 1 | 20 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5115 | observe |
| Epodonios-all | 0.255 | None | 0 | 7934 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8999 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5919 | observe |
| barry-far-vless | 0.255 | None | 0 | 6197 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 17 |
| geo | ClientOSError | - | 15 |
| speed | ClientOSError | - | 11 |
| 204 | TimeoutError | - | 10 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
