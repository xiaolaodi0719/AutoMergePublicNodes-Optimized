# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 04:14:47 |
| 运行耗时 | 1039.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 87168 |
| 去重后节点 | 24439 |
| TCP 可达 | 3000 |
| 真实可用 | 586 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24439 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.4 |
| tcp | 42.0 |
| probe | 361.1 |
| real_test | 545.9 |
| generate | 84.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52554 |
| vmess | 12924 |
| shadowsocks | 10530 |
| trojan | 8486 |
| hysteria2 | 1836 |
| http | 620 |
| shadowsocksr | 128 |
| socks | 61 |
| tuic | 13 |
| hysteria | 12 |
| anytls | 4 |

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
| 82.46 | vless | 202.4 | 493.6 | 23.09 | 0.0 | 10.0 | 10.81 | 18.56 | Au1rxx-base64 | 172.235.38.85 |
| 82.28 | vless | 210.1 | 511.0 | 22.91 | 0.0 | 10.0 | 10.81 | 18.56 | Au1rxx-base64 | 172.233.139.46 |
| 81.24 | vless | 241.7 | 554.6 | 22.18 | 0.0 | 10.0 | 10.81 | 18.56 | Au1rxx-base64 | 31.58.50.200 |
| 80.85 | vless | 272.0 | 720.0 | 21.48 | 0.0 | 10.0 | 10.81 | 18.56 | Au1rxx-base64 | 107.173.237.146 |
| 80.2 | hysteria2 | 252.5 | 593.5 | 21.93 | 0.0 | 10.0 | 10.71 | 18.56 | Au1rxx-base64 | 66.94.121.46 |
| 80.04 | vless | 263.7 | 491.6 | 21.67 | 0.0 | 10.0 | 10.81 | 18.56 | Au1rxx-base64 | 216.36.124.176 |
| 79.82 | shadowsocks | 250.3 | 656.2 | 21.98 | 0.0 | 10.0 | 13.28 | 18.56 | Au1rxx-base64 | 173.244.56.9 |
| 78.69 | shadowsocks | 255.9 | 627.2 | 21.85 | 0.0 | 10.0 | 13.28 | 18.56 | Au1rxx-base64 | 156.146.38.167 |
| 77.62 | trojan | 206.2 | 524.6 | 23.0 | 0.0 | 9.93 | 9.13 | 18.56 | Au1rxx-base64 | us01.duotg.top |
| 77.15 | shadowsocks | 212.9 | 528.7 | 22.85 | 0.0 | 10.0 | 13.28 | 15.02 | Surfboard-tg-mixed | 173.244.56.6 |
| 77.09 | vless | 350.7 | 841.9 | 19.66 | 0.0 | 10.0 | 10.81 | 18.56 | Au1rxx-base64 | 15.204.97.216 |
| 76.95 | vless | 243.7 | 253.4 | 22.14 | 5.5 | 9.92 | 10.81 | 15.02 | Surfboard-tg-mixed | 31.76.91.72 |
| 76.86 | vless | 327.8 | 739.8 | 20.19 | 0.0 | 10.0 | 10.81 | 18.56 | Au1rxx-base64 | 79.141.172.154 |
| 76.21 | shadowsocks | 231.9 | 541.0 | 22.41 | 0.0 | 10.0 | 13.28 | 15.02 | Surfboard-tg-mixed | 108.181.118.10 |
| 76.03 | shadowsocks | 312.5 | 727.2 | 20.54 | 0.0 | 10.0 | 13.28 | 18.56 | Au1rxx-base64 | 23.150.248.20 |
| 75.76 | hysteria2 | 319.0 | 697.2 | 20.39 | 0.0 | 10.0 | 10.71 | 18.56 | Au1rxx-base64 | 159.223.157.129 |
| 75.16 | shadowsocks | 215.8 | 538.5 | 22.78 | 0.0 | 10.0 | 13.28 | 13.6 | mheidari-all | 108.181.0.177 |
| 74.97 | vless | 355.6 | 867.8 | 19.55 | 0.0 | 10.0 | 10.81 | 18.56 | Au1rxx-base64 | ww13.levikogjgfdd.ir |
| 74.82 | shadowsocks | 252.0 | 619.0 | 21.94 | 0.0 | 10.0 | 13.28 | 13.6 | mheidari-all | 156.146.38.170 |
| 74.73 | shadowsocks | 250.8 | 610.1 | 21.97 | 0.0 | 10.0 | 13.28 | 13.6 | mheidari-all | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 0.963 | 27 | 15718 | prefer |
| Au1rxx-base64 | 0.881 | 0.818 | 335 | 1613 | prefer |
| Surfboard-tg-mixed | 0.787 | 0.709 | 165 | 7301 | prefer |
| ermaozi | 0.684 | 0.68 | 25 | 431 | observe |
| ermaozi-get_subscribe | 0.502 | 0.562 | 16 | 461 | observe |
| xiaoji235-airport-v2ray-all | 0.382 | 0.357 | 14 | 3508 | observe |
| DeltaKronecker-all | 0.381 | 0.3 | 456 | 5853 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 168 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7793 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8799 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5909 | observe |
| barry-far-vless | 0.255 | None | 0 | 6145 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 180 |
| speed | ClientOSError | - | 88 |
| geo | ClientOSError | - | 74 |
| speed | TimeoutError | - | 38 |
| cn-block | TimeoutError | - | 25 |
| 204 | ProxyError | - | 22 |
| 204 | TimeoutError | - | 14 |
| cn-block | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
