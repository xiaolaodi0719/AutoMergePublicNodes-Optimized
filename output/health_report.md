# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 11:36:19 |
| 运行耗时 | 597.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96310 |
| 去重后节点 | 26222 |
| TCP 可达 | 3000 |
| 真实可用 | 367 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26222 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 42.7 |
| probe | 246.9 |
| real_test | 215.8 |
| generate | 83.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58606 |
| vmess | 14916 |
| shadowsocks | 11191 |
| trojan | 9059 |
| hysteria2 | 1611 |
| http | 622 |
| shadowsocksr | 168 |
| socks | 86 |
| anytls | 24 |
| hysteria | 19 |
| tuic | 8 |

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
| 79.97 | shadowsocks | 236.0 | 565.4 | 22.31 | 0.0 | 9.01 | 13.95 | 18.74 | Au1rxx-base64 | 173.244.56.6 |
| 77.88 | shadowsocks | 326.0 | 846.8 | 20.23 | 0.0 | 8.96 | 13.95 | 18.74 | Au1rxx-base64 | 149.22.95.183 |
| 77.12 | shadowsocks | 292.4 | 655.4 | 21.01 | 0.0 | 10.0 | 13.95 | 18.74 | Au1rxx-base64 | 156.146.38.169 |
| 76.96 | shadowsocks | 309.7 | 818.3 | 20.61 | 0.0 | 10.0 | 13.95 | 16.9 | Surfboard-tg-mixed | 108.181.0.177 |
| 76.61 | vless | 197.8 | 514.1 | 23.2 | 0.0 | 8.99 | 5.68 | 18.74 | Au1rxx-base64 | 172.235.43.210 |
| 75.83 | vless | 236.2 | 578.7 | 22.31 | 0.0 | 9.1 | 5.68 | 18.74 | Au1rxx-base64 | 15.204.97.216 |
| 75.74 | shadowsocks | 295.9 | 671.6 | 20.93 | 0.0 | 9.12 | 13.95 | 18.74 | Au1rxx-base64 | 156.146.38.170 |
| 75.4 | vless | 214.2 | 538.2 | 22.82 | 0.0 | 10.0 | 5.68 | 16.9 | Surfboard-tg-mixed | 172.235.38.85 |
| 74.78 | shadowsocks | 290.2 | 651.1 | 21.06 | 0.0 | 9.21 | 13.95 | 18.74 | Au1rxx-base64 | 156.146.38.167 |
| 74.57 | shadowsocks | 318.4 | 635.4 | 20.41 | 0.0 | 10.0 | 13.95 | 18.74 | Au1rxx-base64 | 23.150.248.20 |
| 72.3 | vless | 195.5 | 456.3 | 23.25 | 0.0 | 9.13 | 5.68 | 18.74 | Au1rxx-base64 | 172.64.158.146 |
| 71.95 | shadowsocks | 298.5 | 671.6 | 20.87 | 0.0 | 9.07 | 13.95 | 18.74 | Au1rxx-base64 | 156.146.38.168 |
| 71.5 | shadowsocks | 238.2 | 560.4 | 22.26 | 0.0 | 10.0 | 13.95 | 16.9 | Surfboard-tg-mixed | 173.244.56.9 |
| 71.08 | shadowsocks | 391.3 | 807.9 | 18.72 | 0.0 | 9.2 | 13.95 | 18.74 | Au1rxx-base64 | 37.19.198.243 |
| 70.94 | shadowsocks | 190.5 | 512.8 | 23.37 | 0.0 | 10.0 | 13.95 | 8.12 | mheidari-all | 192.3.247.109 |
| 70.87 | shadowsocks | 392.8 | 828.1 | 18.69 | 0.0 | 9.19 | 13.95 | 18.74 | Au1rxx-base64 | 37.19.198.236 |
| 70.81 | vless | 404.0 | 1040.1 | 18.43 | 0.0 | 9.05 | 5.68 | 18.74 | Au1rxx-base64 | 136.117.218.86 |
| 70.55 | shadowsocks | 207.3 | 522.2 | 22.98 | 0.0 | 10.0 | 13.95 | 8.12 | mheidari-all | 108.181.118.10 |
| 70.41 | shadowsocks | 394.0 | 818.9 | 18.66 | 0.0 | 9.12 | 13.95 | 18.74 | Au1rxx-base64 | 37.19.198.160 |
| 70.4 | shadowsocks | 390.9 | 809.5 | 18.73 | 0.0 | 9.07 | 13.95 | 18.74 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.893 | 0.829 | 217 | 1658 | prefer |
| Surfboard-tg-mixed | 0.725 | 0.648 | 122 | 7027 | prefer |
| ermaozi | 0.632 | 0.623 | 53 | 339 | observe |
| mheidari-all | 0.596 | 0.517 | 120 | 22399 | observe |
| ermaozi-get_subscribe | 0.49 | 0.529 | 17 | 373 | observe |
| DeltaKronecker-all | 0.4 | 0.75 | 4 | 5845 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7495 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8857 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5676 | observe |
| barry-far-vless | 0.255 | None | 0 | 5899 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4305 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1658 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 33 |
| 204 | TimeoutError | - | 32 |
| cn-block | ClientOSError | - | 26 |
| geo | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 22 |
| speed | TimeoutError | - | 15 |
| geo | ClientOSError | - | 11 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
