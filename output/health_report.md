# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-31 13:17:43 |
| 运行耗时 | 272.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 79273 |
| 去重后节点 | 22274 |
| TCP 可达 | 3000 |
| 真实可用 | 534 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22274 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.4 |
| tcp | 35.1 |
| probe | 87.9 |
| real_test | 105.6 |
| generate | 34.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50132 |
| vmess | 10956 |
| shadowsocks | 10130 |
| trojan | 6149 |
| hysteria2 | 1548 |
| http | 140 |
| shadowsocksr | 131 |
| socks | 76 |
| hysteria | 7 |
| tuic | 4 |

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
| 83.68 | hysteria2 | 236.1 | 638.8 | 22.31 | 0.0 | 10.0 | 13.57 | 19.9 | Au1rxx-base64 | 159.223.157.129 |
| 82.8 | shadowsocks | 228.2 | 629.6 | 22.5 | 0.0 | 10.0 | 14.4 | 19.9 | Au1rxx-base64 | 37.19.198.236 |
| 82.73 | shadowsocks | 231.2 | 628.8 | 22.43 | 0.0 | 10.0 | 14.4 | 19.9 | Au1rxx-base64 | 37.19.198.160 |
| 82.68 | shadowsocks | 233.3 | 633.2 | 22.38 | 0.0 | 10.0 | 14.4 | 19.9 | Au1rxx-base64 | 37.19.198.244 |
| 81.62 | vless | 241.9 | 654.6 | 22.18 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 81.08 | vless | 265.0 | 699.2 | 21.64 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 169.40.42.232 |
| 80.97 | vless | 270.1 | 645.9 | 21.53 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 195.211.99.45 |
| 80.89 | vless | 273.5 | 749.3 | 21.45 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 204.48.20.223 |
| 80.62 | shadowsocks | 241.5 | 611.9 | 22.19 | 0.0 | 8.63 | 14.4 | 19.9 | Au1rxx-base64 | 84.32.131.61 |
| 80.42 | shadowsocks | 309.3 | 857.3 | 20.62 | 0.0 | 10.0 | 14.4 | 19.9 | Au1rxx-base64 | 38.180.135.156 |
| 80.31 | vless | 298.3 | 822.8 | 20.87 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 79.127.243.217 |
| 80.0 | vless | 300.9 | 806.8 | 20.81 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 169.40.42.182 |
| 79.86 | vless | 317.8 | 789.9 | 20.42 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 158.69.112.254 |
| 79.53 | vless | 332.1 | 782.1 | 20.09 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 169.40.42.212 |
| 79.38 | vless | 338.7 | 862.6 | 19.94 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 169.40.42.173 |
| 79.27 | shadowsocks | 279.4 | 635.6 | 21.31 | 0.0 | 10.0 | 14.4 | 19.9 | Au1rxx-base64 | 156.146.38.168 |
| 79.22 | vless | 345.4 | 937.3 | 19.78 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 169.40.42.229 |
| 79.17 | shadowsocks | 282.3 | 610.9 | 21.24 | 0.0 | 10.0 | 14.4 | 19.9 | Au1rxx-base64 | 156.146.38.169 |
| 79.01 | shadowsocks | 281.2 | 638.2 | 21.27 | 0.0 | 10.0 | 14.4 | 19.9 | Au1rxx-base64 | 156.146.38.170 |
| 78.99 | vless | 337.6 | 854.7 | 19.96 | 0.0 | 10.0 | 9.54 | 19.9 | Au1rxx-base64 | 216.152.147.28 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.948 | 306 | 1804 | prefer |
| Surfboard-tg-mixed | 0.877 | 0.8 | 175 | 6828 | prefer |
| mheidari-all | 0.851 | 0.779 | 68 | 14620 | prefer |
| DeltaKronecker-all | 0.824 | 0.756 | 41 | 5904 | prefer |
| zhangkai | 0.806 | 0.826 | 23 | 144 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| Epodonios-all | 0.255 | None | 0 | 7174 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7956 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5768 | observe |
| barry-far-vless | 0.255 | None | 0 | 5864 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3987 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 14 |
| geo | ClientOSError | - | 12 |
| 204 | ProxyError | - | 12 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| geo | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| speed | ClientOSError | - | 4 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
