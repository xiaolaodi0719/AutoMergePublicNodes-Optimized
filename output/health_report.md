# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 04:19:34 |
| 运行耗时 | 982.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84088 |
| 去重后节点 | 23179 |
| TCP 可达 | 3000 |
| 真实可用 | 657 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23179 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 38.4 |
| probe | 357.1 |
| real_test | 553.1 |
| generate | 26.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50378 |
| vmess | 13169 |
| shadowsocks | 10189 |
| trojan | 8181 |
| hysteria2 | 1294 |
| http | 662 |
| shadowsocksr | 130 |
| socks | 71 |
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
| 83.02 | vless | 229.7 | 613.0 | 22.46 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 195.123.235.177 |
| 82.79 | vless | 239.6 | 674.1 | 22.23 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 47.253.226.114 |
| 82.51 | vless | 251.8 | 648.4 | 21.95 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.163 |
| 82.21 | vless | 264.9 | 701.4 | 21.65 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.15 |
| 81.7 | vless | 286.7 | 766.9 | 21.14 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.35 |
| 81.69 | vless | 287.0 | 693.6 | 21.13 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.184 |
| 81.55 | shadowsocks | 232.4 | 645.6 | 22.4 | 0.0 | 10.0 | 13.93 | 19.22 | Au1rxx-base64 | 37.19.198.243 |
| 81.32 | vless | 303.0 | 747.7 | 20.76 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.74 |
| 81.27 | vless | 305.5 | 773.0 | 20.71 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 66.70.179.198 |
| 80.67 | vless | 331.1 | 744.0 | 20.11 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.223 |
| 80.46 | vless | 340.2 | 858.2 | 19.9 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.95 |
| 80.27 | vless | 348.5 | 890.2 | 19.71 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.179 |
| 80.27 | vless | 348.7 | 840.8 | 19.71 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.235 |
| 80.21 | vless | 297.7 | 672.4 | 20.89 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 198.251.78.29 |
| 80.19 | vless | 352.0 | 836.7 | 19.63 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.173 |
| 80.14 | vless | 354.1 | 683.0 | 19.58 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.231 |
| 80.11 | vless | 355.6 | 844.3 | 19.55 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.90 |
| 80.0 | vless | 360.3 | 859.5 | 19.44 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.89 |
| 79.66 | vless | 374.7 | 976.6 | 19.1 | 0.0 | 10.0 | 11.34 | 19.22 | Au1rxx-base64 | 169.40.42.232 |
| 79.63 | shadowsocks | 228.7 | 637.8 | 22.48 | 0.0 | 10.0 | 13.93 | 19.22 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.931 | 0.869 | 289 | 1618 | prefer |
| mheidari-all | 0.801 | 0.732 | 41 | 15863 | prefer |
| Surfboard-tg-mixed | 0.731 | 0.652 | 250 | 7282 | prefer |
| ermaozi | 0.636 | 0.63 | 27 | 378 | observe |
| DeltaKronecker-all | 0.451 | 0.371 | 518 | 5931 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4261 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ermaozi-get_subscribe | 0.256 | 0.5 | 4 | 402 | observe |
| Epodonios-all | 0.255 | None | 0 | 7966 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9011 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5769 | observe |
| barry-far-vless | 0.255 | None | 0 | 6180 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1618 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 221 |
| speed | ClientOSError | - | 81 |
| geo | ClientOSError | - | 73 |
| speed | TimeoutError | - | 39 |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyError | - | 15 |
| cn-block | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
