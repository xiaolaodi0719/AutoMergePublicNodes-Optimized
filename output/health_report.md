# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-10 19:07:30 |
| 运行耗时 | 235.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 84993 |
| 去重后节点 | 24663 |
| TCP 可达 | 3000 |
| 真实可用 | 469 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24663 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.5 |
| tcp | 37.1 |
| probe | 56.5 |
| real_test | 100.6 |
| generate | 33.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50407 |
| vmess | 13222 |
| trojan | 10283 |
| shadowsocks | 9500 |
| hysteria2 | 1325 |
| shadowsocksr | 73 |
| http | 72 |
| socks | 64 |
| anytls | 26 |
| hysteria | 13 |
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
| 82.26 | vless | 272.0 | 642.4 | 21.48 | 0.0 | 10.0 | 11.3 | 19.82 | Au1rxx-base64 | 216.227.161.95 |
| 82.03 | hysteria2 | 256.0 | 695.4 | 21.85 | 0.0 | 8.5 | 12.86 | 19.82 | Au1rxx-base64 | 138.124.68.188 |
| 82.0 | hysteria2 | 252.4 | 672.8 | 21.94 | 0.0 | 8.48 | 12.86 | 19.82 | Au1rxx-base64 | 159.223.157.129 |
| 80.15 | shadowsocks | 250.7 | 666.9 | 21.98 | 0.0 | 8.53 | 13.82 | 19.82 | Au1rxx-base64 | 37.19.198.243 |
| 79.08 | shadowsocks | 296.9 | 814.8 | 20.91 | 0.0 | 8.53 | 13.82 | 19.82 | Au1rxx-base64 | 37.19.198.244 |
| 78.92 | shadowsocks | 303.4 | 835.3 | 20.75 | 0.0 | 8.53 | 13.82 | 19.82 | Au1rxx-base64 | 37.19.198.236 |
| 78.38 | hysteria2 | 262.7 | 715.8 | 21.7 | 0.0 | 5.0 | 12.86 | 19.82 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 75.91 | vless | 337.6 | 769.6 | 19.96 | 0.0 | 8.39 | 11.3 | 19.82 | Au1rxx-base64 | 152.53.82.202 |
| 75.51 | vless | 319.1 | 663.5 | 20.39 | 0.0 | 10.0 | 11.3 | 19.82 | Au1rxx-base64 | 162.159.137.204 |
| 74.99 | shadowsocks | 257.3 | 697.4 | 21.82 | 0.0 | 8.53 | 13.82 | 19.82 | Au1rxx-base64 | 37.19.198.160 |
| 74.97 | shadowsocks | 456.9 | 1274.8 | 17.2 | 0.0 | 8.63 | 13.82 | 19.82 | Au1rxx-base64 | 68.168.222.210 |
| 74.88 | vless | 337.8 | 605.0 | 19.96 | 0.0 | 10.0 | 11.3 | 19.82 | Au1rxx-base64 | 167.17.68.205 |
| 74.55 | vless | 358.1 | 628.4 | 19.49 | 0.0 | 10.0 | 11.3 | 19.82 | Au1rxx-base64 | 64.23.143.23 |
| 74.17 | vless | 332.2 | 564.8 | 20.09 | 0.0 | 10.0 | 11.3 | 19.82 | Au1rxx-base64 | 70.39.178.231 |
| 73.99 | shadowsocks | 248.8 | 645.7 | 22.02 | 0.0 | 8.67 | 13.82 | 19.82 | Au1rxx-base64 | 198.98.53.130 |
| 73.8 | vless | 323.6 | 587.8 | 20.29 | 0.0 | 8.35 | 11.3 | 19.82 | Au1rxx-base64 | 179.253.240.24 |
| 73.38 | hysteria2 | 383.3 | 669.9 | 18.91 | 0.0 | 8.5 | 12.86 | 19.82 | Au1rxx-base64 | 62.210.124.146 |
| 72.89 | shadowsocks | 314.1 | 538.2 | 20.51 | 0.0 | 8.52 | 13.82 | 19.82 | Au1rxx-base64 | 108.181.0.177 |
| 72.87 | trojan | 373.4 | 598.1 | 19.13 | 0.0 | 10.0 | 13.33 | 19.82 | Au1rxx-base64 | 44.246.163.102 |
| 72.87 | shadowsocks | 384.7 | 917.5 | 18.87 | 0.0 | 8.64 | 13.82 | 19.82 | Au1rxx-base64 | 108.181.57.93 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | 1.0 | 49 | 67 | prefer |
| Au1rxx-base64 | 0.957 | 0.894 | 398 | 1614 | prefer |
| Surfboard-tg-mixed | 0.687 | 0.61 | 59 | 6152 | observe |
| DeltaKronecker-all | 0.47 | 0.386 | 57 | 5881 | observe |
| mheidari-all | 0.361 | 0.4 | 10 | 20189 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 6803 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7537 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5085 | observe |
| barry-far-vless | 0.255 | None | 0 | 5417 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5191 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 29 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 15 |
| geo | ClientOSError | - | 13 |
| geo | TimeoutError | - | 10 |
| speed | TimeoutError | - | 10 |
| speed | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
