# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 15:50:41 |
| 运行耗时 | 570.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 88522 |
| 去重后节点 | 25250 |
| TCP 可达 | 3000 |
| 真实可用 | 526 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25250 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 41.3 |
| probe | 218.1 |
| real_test | 224.2 |
| generate | 79.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53553 |
| vmess | 13973 |
| shadowsocks | 10471 |
| trojan | 8544 |
| hysteria2 | 1197 |
| http | 575 |
| shadowsocksr | 128 |
| socks | 64 |
| hysteria | 9 |
| tuic | 4 |
| anytls | 4 |

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
| 78.61 | shadowsocks | 268.6 | 768.0 | 21.56 | 0.0 | 10.0 | 13.47 | 18.08 | Au1rxx-base64 | 15.204.247.206 |
| 78.5 | vless | 288.3 | 763.5 | 21.1 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.35 |
| 78.48 | vless | 289.3 | 712.5 | 21.08 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 216.152.147.28 |
| 78.31 | vless | 296.9 | 741.9 | 20.91 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.231 |
| 77.84 | vless | 317.0 | 817.7 | 20.44 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 66.70.179.198 |
| 77.36 | vless | 337.7 | 786.4 | 19.96 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.95 |
| 77.15 | vless | 346.7 | 905.5 | 19.75 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.104 |
| 77.06 | vless | 350.6 | 905.4 | 19.66 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.223 |
| 77.03 | vless | 351.8 | 903.2 | 19.63 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.75 |
| 76.98 | vless | 354.2 | 971.9 | 19.58 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 185.95.231.156 |
| 76.95 | hysteria2 | 300.6 | 592.9 | 20.82 | 0.0 | 10.0 | 13.33 | 18.08 | Au1rxx-base64 | 66.94.121.46 |
| 76.4 | vless | 379.4 | 988.5 | 19.0 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.163 |
| 76.3 | vless | 305.6 | 819.0 | 20.7 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.168 |
| 76.05 | vless | 327.0 | 744.4 | 20.21 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.184 |
| 75.92 | shadowsocks | 276.8 | 764.3 | 21.37 | 0.0 | 10.0 | 13.47 | 18.08 | Au1rxx-base64 | 198.98.53.130 |
| 75.73 | hysteria2 | 243.6 | 671.2 | 22.14 | 0.0 | 10.0 | 13.33 | 11.36 | mheidari-all | 159.223.157.129 |
| 75.71 | vless | 315.9 | 804.5 | 20.46 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.16 |
| 75.56 | vless | 415.6 | 1021.8 | 18.16 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.90 |
| 75.42 | shadowsocks | 233.4 | 645.7 | 22.37 | 0.0 | 10.0 | 13.47 | 18.08 | Au1rxx-base64 | 37.19.198.160 |
| 75.21 | vless | 345.3 | 831.1 | 19.78 | 0.0 | 10.0 | 9.32 | 18.08 | Au1rxx-base64 | 169.40.42.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.941 | 0.878 | 319 | 1651 | prefer |
| ermaozi | 0.895 | 0.917 | 24 | 250 | prefer |
| DeltaKronecker-all | 0.785 | 0.707 | 147 | 6421 | prefer |
| Surfboard-tg-mixed | 0.703 | 0.624 | 173 | 7296 | prefer |
| mheidari-all | 0.684 | 0.786 | 14 | 19364 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5174 | observe |
| Epodonios-all | 0.255 | None | 0 | 7933 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9336 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5900 | observe |
| barry-far-vless | 0.255 | None | 0 | 6222 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1652 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 34 |
| geo | TimeoutError | - | 31 |
| speed | ClientOSError | - | 23 |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 12 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
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
