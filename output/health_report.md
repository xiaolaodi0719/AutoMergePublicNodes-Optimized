# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 21:28:12 |
| 运行耗时 | 473.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97258 |
| 去重后节点 | 26464 |
| TCP 可达 | 3000 |
| 真实可用 | 381 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26464 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.4 |
| tcp | 43.3 |
| probe | 189.6 |
| real_test | 151.7 |
| generate | 79.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59655 |
| vmess | 15074 |
| shadowsocks | 11210 |
| trojan | 8873 |
| hysteria2 | 1552 |
| http | 576 |
| shadowsocksr | 169 |
| socks | 96 |
| anytls | 27 |
| hysteria | 15 |
| tuic | 11 |

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
| 81.6 | vless | 219.4 | 583.2 | 22.7 | 0.0 | 9.28 | 10.44 | 19.18 | Au1rxx-base64 | 5.78.159.214 |
| 81.44 | vless | 222.2 | 577.6 | 22.64 | 0.0 | 9.18 | 10.44 | 19.18 | Au1rxx-base64 | 15.204.97.216 |
| 78.35 | vless | 238.0 | 533.7 | 22.27 | 0.0 | 9.14 | 10.44 | 19.18 | Au1rxx-base64 | 137.175.82.40 |
| 78.0 | vless | 264.2 | 587.9 | 21.66 | 0.0 | 9.14 | 10.44 | 19.18 | Au1rxx-base64 | 172.235.43.210 |
| 77.21 | vless | 312.4 | 740.5 | 20.55 | 0.0 | 9.18 | 10.44 | 19.18 | Au1rxx-base64 | 192.3.247.109 |
| 76.91 | vless | 220.5 | 573.1 | 22.67 | 0.0 | 7.62 | 10.44 | 19.18 | Au1rxx-base64 | ww13.levikogjgfdd.ir |
| 75.99 | vless | 277.8 | 603.0 | 21.35 | 0.0 | 9.17 | 10.44 | 19.18 | Au1rxx-base64 | 195.123.240.65 |
| 75.67 | shadowsocks | 274.5 | 319.7 | 21.42 | 3.01 | 10.0 | 13.04 | 19.18 | Au1rxx-base64 | 149.22.87.241 |
| 74.94 | vless | 351.3 | 301.0 | 19.65 | 3.71 | 9.25 | 10.44 | 19.18 | Au1rxx-base64 | 18.183.215.124 |
| 74.5 | hysteria2 | 307.4 | 489.5 | 20.66 | 0.0 | 8.12 | 13.24 | 19.18 | Au1rxx-base64 | open.w2m.ink |
| 74.25 | shadowsocks | 217.3 | 587.5 | 22.75 | 0.0 | 10.0 | 13.04 | 12.46 | mheidari-all | 149.22.95.183 |
| 73.45 | vless | 363.3 | 693.5 | 19.37 | 0.0 | 9.14 | 10.44 | 19.18 | Au1rxx-base64 | 195.211.98.43 |
| 73.16 | shadowsocks | 319.0 | 681.4 | 20.39 | 0.0 | 9.3 | 13.04 | 19.18 | Au1rxx-base64 | 156.146.38.168 |
| 72.74 | vless | 277.1 | 416.2 | 21.36 | 0.0 | 9.26 | 10.44 | 19.18 | Au1rxx-base64 | 162.159.48.32 |
| 72.73 | shadowsocks | 332.3 | 684.0 | 20.09 | 0.0 | 9.13 | 13.04 | 19.18 | Au1rxx-base64 | 23.150.248.20 |
| 72.66 | vless | 229.3 | 518.8 | 22.47 | 0.0 | 9.29 | 10.44 | 19.18 | Au1rxx-base64 | 173.249.207.28 |
| 72.38 | vless | 345.7 | 374.4 | 19.78 | 0.96 | 9.2 | 10.44 | 19.18 | Au1rxx-base64 | 46.250.250.149 |
| 72.27 | shadowsocks | 234.1 | 530.6 | 22.36 | 0.0 | 10.0 | 13.04 | 12.46 | mheidari-all | 192.3.247.109 |
| 72.21 | vless | 377.4 | 738.0 | 19.04 | 0.0 | 9.12 | 10.44 | 19.18 | Au1rxx-base64 | 198.251.78.29 |
| 72.09 | shadowsocks | 288.3 | 574.3 | 21.1 | 0.0 | 10.0 | 13.04 | 15.68 | Surfboard-tg-mixed | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.967 | 0.899 | 69 | 22345 | prefer |
| Au1rxx-base64 | 0.955 | 0.89 | 237 | 1701 | prefer |
| DeltaKronecker-all | 0.892 | 0.826 | 46 | 5452 | prefer |
| Surfboard-tg-mixed | 0.809 | 0.735 | 68 | 7370 | prefer |
| ermaozi | 0.593 | 0.586 | 29 | 304 | observe |
| ermaozi-get_subscribe | 0.324 | 1.0 | 2 | 314 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 69 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7740 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9253 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5959 | observe |
| barry-far-vless | 0.255 | None | 0 | 6190 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4304 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 14 |
| 204 | TimeoutError | - | 12 |
| 204 | ProxyConnectionError | - | 6 |
| speed | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
