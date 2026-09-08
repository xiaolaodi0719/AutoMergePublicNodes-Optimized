# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 04:02:37 |
| 运行耗时 | 382.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91631 |
| 去重后节点 | 25396 |
| TCP 可达 | 3000 |
| 真实可用 | 646 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25396 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.5 |
| tcp | 42.2 |
| probe | 91.8 |
| real_test | 189.2 |
| generate | 50.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57483 |
| vmess | 12274 |
| shadowsocks | 10306 |
| trojan | 9059 |
| hysteria2 | 1780 |
| http | 503 |
| shadowsocksr | 127 |
| socks | 50 |
| anytls | 20 |
| hysteria | 16 |
| tuic | 13 |

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
| 85.19 | vless | 207.6 | 521.6 | 22.97 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 85.14 | vless | 209.7 | 533.1 | 22.92 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 23.94.227.94 |
| 83.95 | vless | 217.9 | 500.2 | 22.73 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 172.236.233.59 |
| 82.77 | vless | 226.0 | 564.4 | 22.55 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 38.244.20.160 |
| 82.31 | shadowsocks | 230.8 | 514.8 | 22.43 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 82.23 | vless | 222.9 | 533.6 | 22.62 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 38.246.229.58 |
| 81.81 | vless | 197.2 | 501.5 | 23.21 | 0.0 | 10.0 | 12.22 | 16.38 | mheidari-all | 38.209.125.45 |
| 80.57 | vless | 205.0 | 477.4 | 23.03 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 79.84 | vless | 351.4 | 849.5 | 19.64 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 15.204.97.216 |
| 79.74 | vless | 370.2 | 855.7 | 19.21 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 51.81.203.63 |
| 79.56 | vless | 234.7 | 570.6 | 22.34 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 104.194.74.14 |
| 78.79 | shadowsocks | 226.7 | 515.1 | 22.53 | 0.0 | 10.0 | 13.88 | 16.38 | mheidari-all | 173.244.56.6 |
| 78.49 | hysteria2 | 326.1 | 718.5 | 20.23 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 78.41 | vless | 248.4 | 488.2 | 22.03 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 104.18.34.14 |
| 78.12 | vless | 249.7 | 287.1 | 22.0 | 4.23 | 9.92 | 12.22 | 16.04 | Surfboard-tg-mixed | 31.76.91.72 |
| 77.81 | vless | 293.7 | 463.9 | 20.98 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 162.159.0.169 |
| 77.71 | shadowsocks | 258.5 | 631.4 | 21.79 | 0.0 | 10.0 | 13.88 | 16.04 | Surfboard-tg-mixed | 156.146.38.170 |
| 77.5 | shadowsocks | 247.5 | 598.2 | 22.05 | 0.0 | 10.0 | 13.88 | 16.04 | Surfboard-tg-mixed | 156.146.38.167 |
| 77.28 | shadowsocks | 262.5 | 601.2 | 21.7 | 0.0 | 10.0 | 13.88 | 16.38 | mheidari-all | 156.146.38.169 |
| 76.97 | vless | 378.5 | 308.3 | 19.02 | 3.44 | 9.89 | 12.22 | 20.0 | Au1rxx-base64 | 52.194.245.53 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.985 | 0.914 | 349 | 1833 | prefer |
| ermaozi-get_subscribe | 0.894 | 0.947 | 19 | 470 | prefer |
| ermaozi | 0.851 | 0.85 | 40 | 450 | prefer |
| Surfboard-tg-mixed | 0.783 | 0.706 | 126 | 7392 | prefer |
| DeltaKronecker-all | 0.487 | 0.404 | 57 | 6417 | observe |
| tg-oneclickvpnkeys | 0.408 | 1.0 | 4 | 196 | observe |
| mheidari-all | 0.36 | 0.279 | 570 | 22287 | observe |
| Epodonios-all | 0.255 | None | 0 | 7885 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8682 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6186 | observe |
| barry-far-vless | 0.255 | None | 0 | 6444 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4218 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1833 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 173 |
| speed | TimeoutError | - | 91 |
| geo | ClientOSError | - | 78 |
| cn-block | ClientOSError | - | 65 |
| speed | ClientOSError | - | 52 |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyConnectionError | - | 11 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
