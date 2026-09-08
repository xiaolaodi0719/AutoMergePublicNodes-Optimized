# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 11:02:28 |
| 运行耗时 | 295.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91310 |
| 去重后节点 | 25270 |
| TCP 可达 | 3000 |
| 真实可用 | 556 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25270 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 42.1 |
| probe | 87.9 |
| real_test | 122.3 |
| generate | 35.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57070 |
| vmess | 12444 |
| shadowsocks | 10287 |
| trojan | 8987 |
| hysteria2 | 1800 |
| http | 502 |
| shadowsocksr | 128 |
| socks | 54 |
| hysteria | 16 |
| tuic | 11 |
| anytls | 11 |

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
| 80.09 | hysteria2 | 241.9 | 656.2 | 22.18 | 0.0 | 10.0 | 14.35 | 15.66 | Surfboard-tg-mixed | 159.223.157.129 |
| 79.14 | hysteria2 | 292.0 | 581.9 | 21.02 | 0.0 | 8.83 | 14.35 | 19.7 | Au1rxx-base64 | 66.94.121.46 |
| 78.63 | shadowsocks | 300.4 | 824.6 | 20.82 | 0.0 | 8.84 | 13.77 | 19.7 | Au1rxx-base64 | 38.180.135.156 |
| 78.55 | shadowsocks | 354.2 | 1024.1 | 19.58 | 0.0 | 10.0 | 13.77 | 19.7 | Au1rxx-base64 | 15.204.246.108 |
| 78.03 | vless | 261.9 | 688.4 | 21.71 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.15 |
| 77.58 | vless | 281.5 | 743.9 | 21.26 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.90 |
| 77.52 | vless | 241.0 | 630.7 | 22.2 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 195.123.235.177 |
| 77.5 | shadowsocks | 246.5 | 682.0 | 22.07 | 0.0 | 10.0 | 13.77 | 15.66 | Surfboard-tg-mixed | 37.19.198.236 |
| 77.25 | shadowsocks | 298.8 | 641.9 | 20.86 | 0.0 | 8.81 | 13.77 | 19.7 | Au1rxx-base64 | 156.146.38.169 |
| 77.24 | vless | 296.3 | 668.1 | 20.92 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.89 |
| 76.9 | vless | 311.2 | 826.1 | 20.58 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.104 |
| 76.51 | shadowsocks | 289.4 | 810.4 | 21.08 | 0.0 | 10.0 | 13.77 | 15.66 | Surfboard-tg-mixed | 37.19.198.244 |
| 76.47 | vless | 329.3 | 883.6 | 20.15 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.133 |
| 76.44 | vless | 331.0 | 778.6 | 20.12 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.75 |
| 76.29 | shadowsocks | 299.0 | 784.8 | 20.86 | 0.0 | 10.0 | 13.77 | 15.66 | Surfboard-tg-mixed | 198.98.53.130 |
| 76.26 | vless | 338.4 | 868.3 | 19.94 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.52 |
| 76.07 | vless | 296.3 | 680.3 | 20.92 | 0.0 | 8.83 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.35 |
| 76.06 | vless | 347.2 | 881.1 | 19.74 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.95 |
| 76.04 | vless | 348.1 | 886.1 | 19.72 | 0.0 | 10.0 | 6.62 | 19.7 | Au1rxx-base64 | 169.40.42.16 |
| 75.82 | shadowsocks | 317.9 | 911.9 | 20.42 | 0.0 | 8.74 | 13.77 | 19.7 | Au1rxx-base64 | 15.204.246.189 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.961 | 0.961 | 51 | 450 | prefer |
| Au1rxx-base64 | 0.944 | 0.877 | 317 | 1726 | prefer |
| ermaozi-get_subscribe | 0.907 | 1.0 | 18 | 470 | prefer |
| Surfboard-tg-mixed | 0.818 | 0.741 | 185 | 7431 | prefer |
| mheidari-all | 0.755 | 0.679 | 78 | 22334 | prefer |
| DeltaKronecker-all | 0.636 | 0.559 | 34 | 6097 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| Epodonios-all | 0.255 | None | 0 | 7885 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8811 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6201 | observe |
| barry-far-vless | 0.255 | None | 0 | 6423 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4209 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 25 |
| cn-block | ClientOSError | - | 23 |
| speed | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 20 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 9 |
| speed | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
