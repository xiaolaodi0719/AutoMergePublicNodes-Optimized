# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 20:52:02 |
| 运行耗时 | 645.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 87619 |
| 去重后节点 | 25094 |
| TCP 可达 | 3000 |
| 真实可用 | 458 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25094 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 42.2 |
| probe | 289.5 |
| real_test | 228.3 |
| generate | 77.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52439 |
| vmess | 13862 |
| shadowsocks | 10579 |
| trojan | 8620 |
| hysteria2 | 1317 |
| http | 586 |
| shadowsocksr | 120 |
| socks | 72 |
| anytls | 11 |
| hysteria | 10 |
| tuic | 3 |

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
| 81.37 | hysteria2 | 310.0 | 848.1 | 20.6 | 0.0 | 10.0 | 13.33 | 18.54 | Au1rxx-base64 | 159.223.157.129 |
| 80.41 | vless | 257.4 | 695.2 | 21.82 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 79.141.172.154 |
| 80.0 | vless | 275.1 | 705.2 | 21.41 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.74 |
| 79.94 | vless | 272.0 | 701.6 | 21.48 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.235 |
| 79.11 | vless | 313.4 | 754.4 | 20.52 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.179 |
| 79.01 | vless | 318.0 | 796.7 | 20.42 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 66.70.179.198 |
| 78.74 | shadowsocks | 281.1 | 768.1 | 21.27 | 0.0 | 10.0 | 12.93 | 18.54 | Au1rxx-base64 | 37.19.198.160 |
| 78.42 | vless | 263.8 | 668.0 | 21.67 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.225 |
| 78.22 | vless | 351.8 | 956.1 | 19.63 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 185.95.231.156 |
| 78.2 | vless | 352.7 | 933.3 | 19.61 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.95 |
| 78.17 | vless | 354.3 | 878.9 | 19.58 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.173 |
| 78.11 | vless | 356.5 | 874.8 | 19.52 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.202 |
| 78.07 | vless | 358.5 | 947.1 | 19.48 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.16 |
| 78.05 | vless | 351.2 | 926.5 | 19.65 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.212 |
| 77.58 | hysteria2 | 303.9 | 597.9 | 20.74 | 0.0 | 10.0 | 13.33 | 18.54 | Au1rxx-base64 | 66.94.121.46 |
| 77.43 | vless | 353.7 | 880.8 | 19.59 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.52 |
| 77.39 | vless | 255.2 | 698.9 | 21.87 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 47.253.226.114 |
| 77.31 | vless | 233.1 | 591.5 | 22.38 | 0.0 | 10.0 | 10.05 | 14.88 | Surfboard-tg-mixed | 88.216.57.128 |
| 77.03 | vless | 277.6 | 708.6 | 21.35 | 0.0 | 10.0 | 10.05 | 18.54 | Au1rxx-base64 | 169.40.42.232 |
| 76.86 | shadowsocks | 279.3 | 647.4 | 21.31 | 0.0 | 10.0 | 12.93 | 18.54 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.928 | 0.866 | 277 | 1615 | prefer |
| ermaozi | 0.828 | 0.84 | 25 | 325 | prefer |
| Surfboard-tg-mixed | 0.756 | 0.678 | 146 | 7333 | prefer |
| mheidari-all | 0.638 | 0.559 | 170 | 19747 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5076 | observe |
| Epodonios-all | 0.255 | None | 0 | 7771 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8922 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5838 | observe |
| barry-far-vless | 0.255 | None | 0 | 6051 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1615 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 40 |
| geo | ClientOSError | - | 38 |
| 204 | ProxyError | - | 24 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 19 |
| speed | ClientOSError | - | 12 |
| geo | TimeoutError | - | 12 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
