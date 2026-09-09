# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 20:53:57 |
| 运行耗时 | 531.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83567 |
| 去重后节点 | 22107 |
| TCP 可达 | 3000 |
| 真实可用 | 378 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22107 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 37.5 |
| probe | 196.6 |
| real_test | 200.2 |
| generate | 88.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50895 |
| vmess | 12152 |
| shadowsocks | 10142 |
| trojan | 7989 |
| hysteria2 | 1638 |
| http | 554 |
| shadowsocksr | 126 |
| socks | 53 |
| hysteria | 8 |
| tuic | 8 |
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
| 82.11 | shadowsocks | 209.1 | 555.2 | 22.94 | 0.0 | 10.0 | 13.61 | 19.56 | Au1rxx-base64 | 149.22.95.183 |
| 81.78 | vless | 286.7 | 782.3 | 21.14 | 0.0 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 15.204.97.216 |
| 80.34 | vless | 254.6 | 527.0 | 21.88 | 0.0 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 172.233.139.46 |
| 79.79 | vless | 372.8 | 1023.4 | 19.15 | 0.0 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 51.81.203.63 |
| 79.53 | vless | 258.9 | 543.8 | 21.78 | 0.0 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 172.235.38.85 |
| 78.63 | shadowsocks | 251.7 | 521.0 | 21.95 | 0.0 | 10.0 | 13.61 | 19.56 | Au1rxx-base64 | 108.181.0.177 |
| 78.05 | vless | 302.4 | 609.1 | 20.78 | 0.0 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 38.246.229.58 |
| 77.51 | vless | 290.2 | 302.7 | 21.06 | 3.65 | 9.15 | 11.08 | 19.56 | Au1rxx-base64 | freshjuniper.download |
| 77.49 | vless | 285.3 | 629.1 | 21.17 | 0.0 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 38.209.125.45 |
| 77.11 | shadowsocks | 284.6 | 563.0 | 21.19 | 0.0 | 10.0 | 13.61 | 19.56 | Au1rxx-base64 | 173.244.56.9 |
| 76.56 | vless | 316.7 | 326.0 | 20.45 | 2.78 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 18.177.61.231 |
| 76.5 | vless | 317.5 | 326.1 | 20.43 | 2.77 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 13.231.19.51 |
| 76.33 | vless | 317.6 | 330.5 | 20.43 | 2.61 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 13.114.89.187 |
| 76.3 | vless | 323.6 | 329.3 | 20.29 | 2.65 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 3.112.131.211 |
| 76.21 | vless | 318.1 | 332.8 | 20.41 | 2.52 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 18.183.215.124 |
| 76.03 | vless | 318.3 | 336.4 | 20.41 | 2.38 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 3.112.47.207 |
| 75.93 | vless | 323.4 | 336.3 | 20.29 | 2.39 | 9.96 | 11.08 | 19.56 | Au1rxx-base64 | 13.231.7.104 |
| 75.57 | vless | 325.4 | 345.8 | 20.24 | 2.03 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 52.199.9.165 |
| 75.51 | vless | 316.6 | 332.2 | 20.45 | 2.54 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 13.230.66.70 |
| 75.2 | vless | 269.5 | 543.6 | 21.54 | 0.0 | 10.0 | 11.08 | 19.56 | Au1rxx-base64 | 31.58.50.200 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | 0.895 | 305 | 1527 | prefer |
| Surfboard-tg-mixed | 0.786 | 0.712 | 66 | 7393 | prefer |
| DeltaKronecker-all | 0.723 | 0.648 | 54 | 5187 | prefer |
| ermaozi | 0.555 | 0.542 | 24 | 410 | observe |
| mheidari-all | 0.474 | 0.467 | 15 | 16196 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 147 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4795 | observe |
| Epodonios-all | 0.255 | None | 0 | 7839 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8955 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6033 | observe |
| barry-far-vless | 0.255 | None | 0 | 6253 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4247 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 12 |
| 204 | ProxyError | - | 9 |
| 204 | ProxyConnectionError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 5 |
| speed | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
