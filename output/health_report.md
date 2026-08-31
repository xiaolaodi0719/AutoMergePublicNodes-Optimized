# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-31 22:45:48 |
| 运行耗时 | 295.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 78460 |
| 去重后节点 | 22374 |
| TCP 可达 | 3000 |
| 真实可用 | 637 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22374 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.5 |
| tcp | 35.4 |
| probe | 83.7 |
| real_test | 127.7 |
| generate | 42.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49181 |
| vmess | 11016 |
| shadowsocks | 10016 |
| trojan | 6180 |
| hysteria2 | 1715 |
| http | 142 |
| shadowsocksr | 121 |
| socks | 75 |
| hysteria | 7 |
| tuic | 7 |

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
| 85.99 | vless | 193.4 | 499.0 | 23.3 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 172.235.43.210 |
| 85.86 | vless | 199.1 | 510.5 | 23.17 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 172.233.156.118 |
| 85.83 | vless | 200.2 | 513.0 | 23.14 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 172.236.252.35 |
| 85.83 | vless | 200.6 | 524.5 | 23.14 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 172.239.67.231 |
| 85.58 | vless | 211.2 | 525.1 | 22.89 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 172.233.156.42 |
| 85.5 | hysteria2 | 237.2 | 551.8 | 22.29 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 85.32 | vless | 222.5 | 532.1 | 22.63 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 74.207.245.124 |
| 85.28 | vless | 224.2 | 516.0 | 22.59 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 192.155.87.188 |
| 85.18 | vless | 228.3 | 541.6 | 22.49 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 50.116.9.184 |
| 85.17 | vless | 226.0 | 526.0 | 22.55 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 173.230.155.55 |
| 85.14 | vless | 230.2 | 547.0 | 22.45 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 192.81.131.225 |
| 84.33 | vless | 212.5 | 493.0 | 22.86 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 45.33.62.226 |
| 84.09 | vless | 235.0 | 621.7 | 22.34 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 83.1 | vless | 238.2 | 542.4 | 22.26 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 173.255.242.56 |
| 83.08 | vless | 221.3 | 520.4 | 22.65 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 45.79.103.108 |
| 82.95 | vless | 218.7 | 514.8 | 22.72 | 0.0 | 10.0 | 12.69 | 17.54 | Surfboard-tg-mixed | 173.255.242.235 |
| 82.93 | vless | 197.0 | 494.6 | 23.22 | 0.0 | 10.0 | 12.69 | 17.02 | mheidari-all | 172.239.67.156 |
| 82.91 | vless | 220.2 | 522.5 | 22.68 | 0.0 | 10.0 | 12.69 | 17.54 | Surfboard-tg-mixed | 45.33.107.237 |
| 82.84 | vless | 200.8 | 495.5 | 23.13 | 0.0 | 10.0 | 12.69 | 17.02 | mheidari-all | 172.233.156.123 |
| 82.35 | vless | 233.8 | 541.6 | 22.37 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 45.33.62.166 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.955 | 0.895 | 38 | 5904 | prefer |
| Au1rxx-base64 | 0.95 | 0.905 | 285 | 1182 | prefer |
| mheidari-all | 0.926 | 0.85 | 180 | 14929 | prefer |
| Surfboard-tg-mixed | 0.913 | 0.836 | 214 | 7016 | prefer |
| zhangkai | 0.544 | 0.542 | 24 | 144 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| Epodonios-all | 0.255 | None | 0 | 7323 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7470 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5879 | observe |
| barry-far-vless | 0.255 | None | 0 | 6031 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4025 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.222 | None | 0 | 1182 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 13 |
| 204 | ProxyConnectionError | - | 12 |
| geo | ClientOSError | - | 10 |
| speed | TimeoutError | - | 10 |
| 204 | ProxyError | - | 9 |
| speed | ClientOSError | - | 8 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
