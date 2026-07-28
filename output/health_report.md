# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-28 19:43:44 |
| 运行耗时 | 245.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 80840 |
| 去重后节点 | 22955 |
| TCP 可达 | 3000 |
| 真实可用 | 396 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22955 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 32.3 |
| probe | 52.7 |
| real_test | 119.0 |
| generate | 33.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46334 |
| trojan | 13086 |
| vmess | 10417 |
| shadowsocks | 10345 |
| hysteria2 | 516 |
| shadowsocksr | 76 |
| socks | 52 |
| hysteria | 8 |
| tuic | 3 |
| http | 3 |

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
| 80.21 | shadowsocks | 218.0 | 516.9 | 22.73 | 0.0 | 10.0 | 12.86 | 18.62 | Au1rxx-base64 | 173.244.56.9 |
| 79.63 | shadowsocks | 242.1 | 563.0 | 22.17 | 0.0 | 10.0 | 12.86 | 18.62 | Au1rxx-base64 | 149.22.95.183 |
| 79.19 | vless | 176.5 | 451.1 | 23.69 | 0.0 | 10.0 | 8.16 | 18.34 | DeltaKronecker-all | 104.16.9.20 |
| 79.16 | vless | 177.7 | 460.1 | 23.66 | 0.0 | 10.0 | 8.16 | 18.34 | DeltaKronecker-all | 104.25.161.29 |
| 79.15 | vless | 178.1 | 463.9 | 23.65 | 0.0 | 10.0 | 8.16 | 18.34 | DeltaKronecker-all | 104.17.90.246 |
| 78.39 | vless | 179.8 | 475.8 | 23.61 | 0.0 | 10.0 | 8.16 | 18.62 | Au1rxx-base64 | 172.67.187.219 |
| 77.83 | vless | 235.5 | 634.7 | 22.33 | 0.0 | 10.0 | 8.16 | 18.34 | DeltaKronecker-all | 172.67.209.126 |
| 77.31 | vless | 183.6 | 483.0 | 23.53 | 0.0 | 10.0 | 8.16 | 18.62 | Au1rxx-base64 | 154.17.238.183 |
| 77.31 | vless | 300.9 | 811.5 | 20.81 | 0.0 | 10.0 | 8.16 | 18.34 | DeltaKronecker-all | 167.17.68.205 |
| 77.1 | shadowsocks | 219.1 | 527.9 | 22.71 | 0.0 | 10.0 | 12.86 | 18.62 | Au1rxx-base64 | 173.244.56.6 |
| 77.09 | vless | 299.3 | 741.0 | 20.85 | 0.0 | 10.0 | 8.16 | 18.62 | Au1rxx-base64 | 185.164.111.48 |
| 76.56 | vless | 172.6 | 456.2 | 23.78 | 0.0 | 10.0 | 8.16 | 18.62 | Au1rxx-base64 | 172.67.174.37 |
| 76.17 | shadowsocks | 273.1 | 280.1 | 21.46 | 4.5 | 9.84 | 12.86 | 18.62 | Au1rxx-base64 | 149.22.87.240 |
| 75.89 | vless | 168.1 | 453.6 | 23.89 | 0.0 | 10.0 | 8.16 | 18.34 | DeltaKronecker-all | 92.223.71.246 |
| 75.79 | hysteria2 | 353.6 | 727.3 | 19.59 | 0.0 | 10.0 | 13.93 | 18.62 | Au1rxx-base64 | 159.223.157.129 |
| 75.76 | vless | 185.6 | 480.4 | 23.48 | 0.0 | 10.0 | 8.16 | 18.62 | Au1rxx-base64 | 154.19.184.40 |
| 75.53 | shadowsocks | 182.7 | 474.0 | 23.55 | 0.0 | 10.0 | 12.86 | 18.62 | Au1rxx-base64 | 185.236.200.210 |
| 75.51 | shadowsocks | 286.5 | 642.5 | 21.15 | 0.0 | 10.0 | 12.86 | 18.62 | Au1rxx-base64 | 156.146.38.167 |
| 75.45 | vless | 177.5 | 488.4 | 23.67 | 0.0 | 10.0 | 8.16 | 18.62 | Au1rxx-base64 | 64.23.143.23 |
| 74.62 | vless | 170.2 | 461.2 | 23.84 | 0.0 | 10.0 | 8.16 | 18.62 | Au1rxx-base64 | 172.66.132.196 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | 0.815 | 271 | 1312 | prefer |
| DeltaKronecker-all | 0.588 | 0.508 | 329 | 5965 | observe |
| Surfboard-tg-mixed | 0.373 | 0.6 | 5 | 5820 | observe |
| mheidari-all | 0.352 | 0.5 | 6 | 17378 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4972 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6834 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6507 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4597 | observe |
| barry-far-vless | 0.255 | None | 0 | 5117 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5059 | observe |
| nscl5-all | 0.255 | None | 0 | 3331 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.227 | None | 0 | 1312 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 49 |
| geo | TimeoutError | - | 39 |
| cn-block | TimeoutError | - | 37 |
| 204 | TimeoutError | - | 25 |
| geo | ClientOSError | - | 23 |
| speed | ClientOSError | - | 15 |
| cn-block | ProxyError | - | 11 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
