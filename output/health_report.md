# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 21:51:38 |
| 运行耗时 | 647.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 89958 |
| 去重后节点 | 25660 |
| TCP 可达 | 3000 |
| 真实可用 | 450 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25660 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.5 |
| tcp | 39.8 |
| probe | 297.4 |
| real_test | 222.7 |
| generate | 78.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55643 |
| vmess | 13045 |
| shadowsocks | 10188 |
| trojan | 8360 |
| hysteria2 | 1892 |
| http | 604 |
| shadowsocksr | 125 |
| socks | 55 |
| anytls | 22 |
| hysteria | 14 |
| tuic | 10 |

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
| 84.47 | hysteria2 | 205.7 | 520.4 | 23.02 | 0.0 | 9.38 | 14.21 | 18.86 | Au1rxx-base64 | 66.94.121.46 |
| 82.77 | hysteria2 | 271.7 | 772.7 | 21.49 | 0.0 | 9.21 | 14.21 | 18.86 | Au1rxx-base64 | 107.175.219.48 |
| 82.76 | vless | 214.7 | 526.9 | 22.81 | 0.0 | 10.0 | 11.09 | 18.86 | Au1rxx-base64 | 172.235.43.210 |
| 82.17 | trojan | 186.4 | 462.7 | 23.46 | 0.0 | 10.0 | 12.35 | 18.86 | Au1rxx-base64 | 100.42.228.109 |
| 82.07 | vless | 244.6 | 523.2 | 22.12 | 0.0 | 10.0 | 11.09 | 18.86 | Au1rxx-base64 | 150.241.102.181 |
| 81.41 | vless | 273.0 | 560.3 | 21.46 | 0.0 | 10.0 | 11.09 | 18.86 | Au1rxx-base64 | 172.233.139.46 |
| 81.27 | vless | 248.7 | 667.1 | 22.02 | 0.0 | 9.3 | 11.09 | 18.86 | Au1rxx-base64 | 45.149.172.80 |
| 80.73 | shadowsocks | 240.9 | 566.1 | 22.2 | 0.0 | 9.24 | 14.43 | 18.86 | Au1rxx-base64 | 149.22.95.183 |
| 80.29 | shadowsocks | 245.6 | 544.6 | 22.09 | 0.0 | 9.24 | 14.43 | 18.86 | Au1rxx-base64 | 173.244.56.9 |
| 80.25 | vless | 323.1 | 843.8 | 20.3 | 0.0 | 10.0 | 11.09 | 18.86 | Au1rxx-base64 | 15.204.97.216 |
| 79.68 | shadowsocks | 286.4 | 721.8 | 21.15 | 0.0 | 9.24 | 14.43 | 18.86 | Au1rxx-base64 | 173.244.56.6 |
| 79.56 | vless | 191.1 | 494.6 | 23.35 | 0.0 | 9.26 | 11.09 | 18.86 | Au1rxx-base64 | 45.149.172.74 |
| 78.81 | shadowsocks | 199.5 | 486.8 | 23.16 | 0.0 | 10.0 | 14.43 | 15.72 | Surfboard-tg-mixed | 108.181.0.177 |
| 78.47 | vless | 184.1 | 490.1 | 23.52 | 0.0 | 10.0 | 11.09 | 18.86 | Au1rxx-base64 | 31.58.50.200 |
| 78.02 | vless | 224.9 | 538.4 | 22.57 | 0.0 | 10.0 | 11.09 | 18.86 | Au1rxx-base64 | 172.64.229.2 |
| 77.56 | vless | 223.5 | 558.3 | 22.61 | 0.0 | 10.0 | 11.09 | 18.86 | Au1rxx-base64 | 38.244.20.41 |
| 77.55 | vless | 191.6 | 539.7 | 23.34 | 0.0 | 9.26 | 11.09 | 18.86 | Au1rxx-base64 | 198.200.42.129 |
| 77.42 | vless | 260.1 | 511.3 | 21.76 | 0.0 | 9.3 | 11.09 | 18.86 | Au1rxx-base64 | 144.172.104.26 |
| 77.14 | hysteria2 | 197.5 | 522.1 | 23.21 | 0.0 | 10.0 | 14.21 | 15.72 | Surfboard-tg-mixed | 45.149.172.80 |
| 77.13 | vless | 202.5 | 445.2 | 23.09 | 0.0 | 10.0 | 11.09 | 18.86 | Au1rxx-base64 | 162.159.48.32 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | 0.911 | 303 | 1752 | prefer |
| Surfboard-tg-mixed | 0.913 | 0.844 | 64 | 7602 | prefer |
| mheidari-all | 0.904 | 0.833 | 72 | 21195 | prefer |
| DeltaKronecker-all | 0.752 | 0.678 | 59 | 5972 | prefer |
| ermaozi | 0.575 | 0.562 | 32 | 393 | observe |
| ermaozi-get_subscribe | 0.272 | 1.0 | 1 | 427 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 135 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4914 | observe |
| Epodonios-all | 0.255 | None | 0 | 7941 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8691 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6098 | observe |
| barry-far-vless | 0.255 | None | 0 | 6284 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4099 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 11 |
| geo | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 6 |
| speed | ClientOSError | - | 6 |
| 204 | ProxyConnectionError | - | 4 |
| geo | ClientOSError | - | 4 |
| speed | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
