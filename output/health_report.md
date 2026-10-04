# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-04 05:25:15 |
| 运行耗时 | 711.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99344 |
| 去重后节点 | 27384 |
| TCP 可达 | 3000 |
| 真实可用 | 462 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27384 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 0.9 |
| tcp | 47.4 |
| probe | 260.9 |
| real_test | 319.3 |
| generate | 75.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60086 |
| vmess | 15659 |
| shadowsocks | 11527 |
| trojan | 9612 |
| hysteria2 | 1656 |
| http | 520 |
| shadowsocksr | 166 |
| socks | 68 |
| anytls | 27 |
| hysteria | 17 |
| tuic | 6 |

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
| 85.13 | vless | 193.7 | 507.8 | 23.29 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 172.235.43.210 |
| 85.08 | vless | 196.1 | 511.8 | 23.24 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 172.235.38.85 |
| 84.98 | vless | 200.4 | 515.4 | 23.14 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 107.173.237.146 |
| 84.25 | vless | 231.9 | 566.8 | 22.41 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 15.204.97.216 |
| 79.85 | shadowsocks | 241.6 | 589.0 | 22.19 | 0.0 | 10.0 | 13.24 | 19.42 | Au1rxx-base64 | 149.22.95.183 |
| 79.8 | hysteria2 | 318.7 | 266.3 | 20.4 | 5.01 | 9.26 | 13.33 | 19.42 | Au1rxx-base64 | open.2ml.bid |
| 78.82 | shadowsocks | 270.4 | 717.7 | 21.52 | 0.0 | 10.0 | 13.24 | 18.56 | Surfboard-tg-mixed | 5.78.51.123 |
| 78.09 | vless | 171.7 | 463.1 | 23.8 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 137.175.82.40 |
| 77.55 | trojan | 244.1 | 567.9 | 22.13 | 0.0 | 10.0 | 13.5 | 19.42 | Au1rxx-base64 | 44.255.123.205 |
| 77.32 | trojan | 349.8 | 972.5 | 19.68 | 0.0 | 10.0 | 13.5 | 16.64 | mheidari-all | 34.94.125.227 |
| 77.01 | vless | 201.1 | 509.2 | 23.12 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 172.233.139.46 |
| 76.94 | trojan | 248.8 | 617.8 | 22.02 | 0.0 | 10.0 | 13.5 | 19.42 | Au1rxx-base64 | 107.149.159.190 |
| 76.9 | vless | 333.2 | 847.5 | 20.06 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 154.29.145.196 |
| 76.8 | vless | 252.1 | 620.6 | 21.94 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 172.64.158.146 |
| 76.7 | shadowsocks | 291.4 | 654.8 | 21.03 | 0.0 | 10.0 | 13.24 | 19.42 | Au1rxx-base64 | 156.146.38.169 |
| 76.62 | shadowsocks | 290.9 | 658.5 | 21.04 | 0.0 | 10.0 | 13.24 | 19.42 | Au1rxx-base64 | 156.146.38.168 |
| 76.56 | vless | 335.0 | 340.0 | 20.02 | 2.25 | 9.93 | 12.42 | 19.42 | Au1rxx-base64 | 43.133.11.187 |
| 76.48 | vless | 213.7 | 534.2 | 22.83 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 195.123.240.65 |
| 76.4 | trojan | 240.3 | 555.2 | 22.22 | 0.0 | 8.76 | 13.5 | 19.42 | Au1rxx-base64 | happy-gibbon.rooster465.autos |
| 76.4 | vless | 387.4 | 745.9 | 18.81 | 0.0 | 10.0 | 12.42 | 19.42 | Au1rxx-base64 | 172.64.32.103 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.94 | 0.87 | 293 | 1797 | prefer |
| Surfboard-tg-mixed | 0.808 | 0.731 | 171 | 7318 | prefer |
| ermaozi | 0.718 | 0.708 | 24 | 646 | prefer |
| mheidari-all | 0.393 | 0.312 | 199 | 23371 | observe |
| Epodonios-all | 0.255 | None | 0 | 7797 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9571 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5909 | observe |
| barry-far-vless | 0.255 | None | 0 | 6122 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4285 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| DeltaKronecker-all | 0.249 | 0.2 | 10 | 5207 | downweight |
| Au1rxx-clash | 0.247 | None | 0 | 1797 | observe |
| ermaozi-get_subscribe | 0.228 | 0.5 | 2 | 505 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 97 |
| speed | TimeoutError | - | 43 |
| cn-block | TimeoutError | - | 24 |
| geo | ClientOSError | - | 20 |
| 204 | ProxyError | - | 14 |
| 204 | TimeoutError | - | 14 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyConnectionError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
