# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-28 23:13:11 |
| 运行耗时 | 420.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97528 |
| 去重后节点 | 27021 |
| TCP 可达 | 3000 |
| 真实可用 | 373 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27021 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.6 |
| tcp | 44.2 |
| probe | 174.6 |
| real_test | 115.8 |
| generate | 77.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59920 |
| vmess | 14922 |
| shadowsocks | 11416 |
| trojan | 8882 |
| hysteria2 | 1459 |
| http | 635 |
| shadowsocksr | 170 |
| socks | 77 |
| anytls | 24 |
| hysteria | 15 |
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
| 80.79 | vless | 233.7 | 614.9 | 22.37 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 195.123.235.177 |
| 80.65 | vless | 239.7 | 684.7 | 22.23 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 79.141.172.154 |
| 80.32 | vless | 254.0 | 659.1 | 21.9 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 169.40.42.212 |
| 80.25 | vless | 256.8 | 697.7 | 21.83 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 159.89.87.21 |
| 80.18 | vless | 259.8 | 705.1 | 21.76 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 137.184.218.169 |
| 80.03 | vless | 266.6 | 727.5 | 21.61 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 185.95.231.156 |
| 79.92 | vless | 271.2 | 666.3 | 21.5 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 195.211.98.43 |
| 79.6 | vless | 285.1 | 698.0 | 21.18 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 66.70.179.198 |
| 79.5 | vless | 289.2 | 643.8 | 21.08 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 169.40.42.35 |
| 79.0 | vless | 310.9 | 761.8 | 20.58 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 158.69.112.254 |
| 78.82 | vless | 318.8 | 730.1 | 20.4 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 169.40.42.168 |
| 78.73 | vless | 322.4 | 740.3 | 20.31 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 169.40.42.74 |
| 78.61 | vless | 327.9 | 898.4 | 20.19 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 169.40.42.232 |
| 78.48 | shadowsocks | 262.1 | 730.5 | 21.71 | 0.0 | 10.0 | 13.15 | 17.62 | Au1rxx-base64 | 37.19.198.236 |
| 78.45 | vless | 334.8 | 854.9 | 20.03 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 169.40.42.15 |
| 78.31 | vless | 340.9 | 932.0 | 19.89 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 169.40.42.223 |
| 78.11 | vless | 349.6 | 890.8 | 19.69 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 169.40.42.184 |
| 77.94 | vless | 284.7 | 757.6 | 21.19 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 169.40.42.16 |
| 77.71 | shadowsocks | 258.5 | 714.1 | 21.79 | 0.0 | 9.15 | 13.15 | 17.62 | Au1rxx-base64 | 37.19.198.244 |
| 77.67 | vless | 368.4 | 1032.3 | 19.25 | 0.0 | 10.0 | 10.8 | 17.62 | Au1rxx-base64 | 185.95.231.233 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.989 | 0.95 | 20 | 7142 | prefer |
| Au1rxx-base64 | 0.96 | 0.896 | 298 | 1674 | prefer |
| mheidari-all | 0.891 | 0.818 | 88 | 22856 | prefer |
| DeltaKronecker-all | 0.438 | 1.0 | 3 | 5428 | observe |
| ermaozi | 0.358 | 0.333 | 30 | 344 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 121 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5326 | observe |
| Epodonios-all | 0.255 | None | 0 | 7535 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9706 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5799 | observe |
| barry-far-vless | 0.255 | None | 0 | 6027 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4237 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 23 |
| 204 | ProxyError | - | 17 |
| 204 | ProxyConnectionError | - | 13 |
| cn-block | TimeoutError | - | 6 |
| speed | TimeoutError | - | 5 |
| geo | TimeoutError | - | 4 |
| 204 | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
