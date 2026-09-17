# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 16:48:44 |
| 运行耗时 | 643.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 86881 |
| 去重后节点 | 24278 |
| TCP 可达 | 3000 |
| 真实可用 | 404 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24278 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.4 |
| tcp | 41.0 |
| probe | 277.9 |
| real_test | 229.0 |
| generate | 86.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51574 |
| vmess | 13922 |
| shadowsocks | 10638 |
| trojan | 8555 |
| hysteria2 | 1435 |
| http | 545 |
| shadowsocksr | 126 |
| socks | 74 |
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
| 79.86 | vless | 244.8 | 647.1 | 22.11 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 137.184.218.169 |
| 79.6 | vless | 256.1 | 620.0 | 21.85 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.179 |
| 79.39 | vless | 265.3 | 673.2 | 21.64 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 167.17.69.171 |
| 79.13 | vless | 276.6 | 680.1 | 21.38 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.231 |
| 78.59 | vless | 285.4 | 753.5 | 21.17 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.229 |
| 78.54 | shadowsocks | 232.7 | 631.0 | 22.39 | 0.0 | 10.0 | 13.47 | 16.68 | mheidari-all | 37.19.198.243 |
| 78.09 | vless | 321.1 | 812.0 | 20.34 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 66.70.179.198 |
| 77.92 | hysteria2 | 228.7 | 625.6 | 22.48 | 0.0 | 10.0 | 12.86 | 16.68 | mheidari-all | 159.223.157.129 |
| 77.84 | vless | 332.3 | 885.2 | 20.09 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 185.95.231.156 |
| 77.83 | vless | 313.2 | 754.7 | 20.53 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.90 |
| 77.52 | vless | 346.0 | 890.4 | 19.77 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.184 |
| 77.28 | vless | 356.5 | 903.1 | 19.53 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.95 |
| 77.22 | vless | 272.5 | 707.3 | 21.47 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.232 |
| 77.05 | shadowsocks | 330.0 | 850.0 | 20.14 | 0.0 | 10.0 | 13.47 | 17.94 | Au1rxx-base64 | 38.180.135.156 |
| 76.94 | vless | 370.9 | 886.6 | 19.19 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.52 |
| 76.45 | vless | 392.2 | 974.6 | 18.7 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.74 |
| 76.32 | vless | 294.7 | 772.7 | 20.96 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.223 |
| 76.32 | vless | 397.8 | 960.8 | 18.57 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.202 |
| 76.29 | vless | 399.1 | 956.8 | 18.54 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.212 |
| 76.1 | vless | 276.9 | 735.0 | 21.37 | 0.0 | 10.0 | 9.81 | 17.94 | Au1rxx-base64 | 169.40.42.89 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.921 | 0.859 | 263 | 1619 | prefer |
| DeltaKronecker-all | 0.757 | 0.69 | 29 | 5931 | prefer |
| mheidari-all | 0.755 | 0.68 | 75 | 16008 | prefer |
| ermaozi | 0.742 | 0.742 | 31 | 357 | prefer |
| Surfboard-tg-mixed | 0.681 | 0.603 | 136 | 7430 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 119 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5093 | observe |
| Epodonios-all | 0.255 | None | 0 | 7888 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9066 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5904 | observe |
| barry-far-vless | 0.255 | None | 0 | 6129 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4179 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 28 |
| geo | ClientOSError | - | 26 |
| 204 | TimeoutError | - | 19 |
| geo | TimeoutError | - | 16 |
| cn-block | TimeoutError | - | 15 |
| speed | TimeoutError | - | 13 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 4 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
