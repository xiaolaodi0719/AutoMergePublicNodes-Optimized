# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-01 11:29:21 |
| 运行耗时 | 291.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 83205 |
| 去重后节点 | 24567 |
| TCP 可达 | 3000 |
| 真实可用 | 589 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24567 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.5 |
| tcp | 39.4 |
| probe | 87.6 |
| real_test | 121.7 |
| generate | 34.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52165 |
| vmess | 11425 |
| shadowsocks | 10156 |
| trojan | 7667 |
| hysteria2 | 1413 |
| http | 146 |
| shadowsocksr | 131 |
| socks | 81 |
| hysteria | 9 |
| tuic | 7 |
| anytls | 5 |

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
| 81.68 | shadowsocks | 233.8 | 649.0 | 22.36 | 0.0 | 10.0 | 13.82 | 19.5 | Au1rxx-base64 | 37.19.198.160 |
| 80.78 | shadowsocks | 273.0 | 766.4 | 21.46 | 0.0 | 10.0 | 13.82 | 19.5 | Au1rxx-base64 | 37.19.198.243 |
| 79.81 | vless | 239.4 | 649.5 | 22.23 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 79.127.243.217 |
| 79.81 | vless | 239.6 | 650.7 | 22.23 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 79.74 | vless | 242.7 | 649.7 | 22.16 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 204.48.20.223 |
| 79.6 | vless | 248.9 | 628.7 | 22.02 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 172.105.104.54 |
| 79.25 | vless | 264.0 | 644.7 | 21.67 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 195.211.99.45 |
| 79.14 | vless | 263.6 | 635.2 | 21.68 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 195.211.99.49 |
| 79.1 | vless | 270.5 | 714.2 | 21.52 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 169.40.42.104 |
| 78.76 | vless | 285.0 | 717.6 | 21.18 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 2.24.124.64 |
| 78.35 | shadowsocks | 285.4 | 820.3 | 21.17 | 0.0 | 10.0 | 13.82 | 17.86 | Surfboard-tg-mixed | 15.204.247.124 |
| 78.04 | vless | 316.0 | 729.0 | 20.46 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 169.40.42.225 |
| 78.01 | hysteria2 | 362.5 | 800.5 | 19.39 | 0.0 | 10.0 | 14.25 | 19.5 | Au1rxx-base64 | 66.94.121.46 |
| 77.94 | vless | 320.6 | 674.9 | 20.36 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 216.152.147.28 |
| 77.88 | shadowsocks | 274.5 | 634.9 | 21.42 | 0.0 | 10.0 | 13.82 | 19.5 | Au1rxx-base64 | 156.146.38.170 |
| 77.88 | vless | 323.2 | 815.7 | 20.3 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 66.70.179.198 |
| 77.48 | vless | 340.4 | 944.9 | 19.9 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 185.95.231.156 |
| 77.36 | vless | 345.5 | 936.9 | 19.78 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 137.184.218.169 |
| 77.32 | vless | 347.2 | 943.0 | 19.74 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 169.40.42.202 |
| 77.28 | vless | 252.0 | 648.1 | 21.94 | 0.0 | 10.0 | 8.08 | 19.5 | Au1rxx-base64 | 169.40.42.16 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| Au1rxx-base64 | 0.923 | 0.857 | 329 | 1711 | prefer |
| mheidari-all | 0.839 | 0.762 | 193 | 17148 | prefer |
| Surfboard-tg-mixed | 0.83 | 0.753 | 182 | 6921 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4708 | observe |
| Epodonios-all | 0.255 | None | 0 | 7334 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7625 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5831 | observe |
| barry-far-vless | 0.255 | None | 0 | 6092 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4013 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1711 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 35 |
| 204 | TimeoutError | - | 27 |
| speed | TimeoutError | - | 23 |
| geo | ClientOSError | - | 17 |
| geo | TimeoutError | - | 14 |
| 204 | ProxyError | - | 13 |
| cn-block | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 3 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
