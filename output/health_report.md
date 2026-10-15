# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 16:54:30 |
| 运行耗时 | 840.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 100051 |
| 去重后节点 | 27884 |
| TCP 可达 | 3000 |
| 真实可用 | 377 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27884 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 48.7 |
| probe | 365.4 |
| real_test | 328.8 |
| generate | 88.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59032 |
| vmess | 16500 |
| shadowsocks | 12001 |
| trojan | 10372 |
| hysteria2 | 1209 |
| http | 660 |
| shadowsocksr | 170 |
| socks | 57 |
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
| 78.02 | shadowsocks | 259.3 | 608.0 | 21.78 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 173.244.56.9 |
| 77.03 | shadowsocks | 257.5 | 519.7 | 21.82 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 173.244.56.6 |
| 76.33 | vless | 321.4 | 628.8 | 20.34 | 0.0 | 10.0 | 10.07 | 16.96 | Au1rxx-base64 | 95.111.212.241 |
| 75.34 | vless | 291.7 | 641.9 | 21.03 | 0.0 | 10.0 | 10.07 | 16.96 | Au1rxx-base64 | 216.227.161.95 |
| 75.03 | vless | 206.4 | 523.1 | 23.0 | 0.0 | 10.0 | 10.07 | 16.96 | Au1rxx-base64 | 154.29.159.211 |
| 74.96 | shadowsocks | 261.9 | 637.4 | 21.72 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 156.146.38.167 |
| 74.93 | vless | 210.5 | 495.3 | 22.9 | 0.0 | 10.0 | 10.07 | 16.96 | Au1rxx-base64 | 47.251.25.74 |
| 74.75 | vless | 295.5 | 614.7 | 20.94 | 0.0 | 10.0 | 10.07 | 16.96 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 74.49 | hysteria2 | 343.9 | 720.3 | 19.82 | 0.0 | 10.0 | 11.54 | 16.96 | Au1rxx-base64 | 129.213.91.185 |
| 74.44 | shadowsocks | 280.3 | 283.9 | 21.29 | 4.35 | 9.91 | 13.28 | 16.96 | Au1rxx-base64 | 149.22.87.241 |
| 74.44 | vless | 296.1 | 614.5 | 20.92 | 0.0 | 10.0 | 10.07 | 16.96 | Au1rxx-base64 | 44.248.233.99 |
| 74.19 | vless | 296.2 | 685.1 | 20.92 | 0.0 | 10.0 | 10.07 | 16.96 | Au1rxx-base64 | 23.95.222.127 |
| 73.57 | shadowsocks | 292.1 | 631.9 | 21.02 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 149.22.95.183 |
| 72.79 | shadowsocks | 263.8 | 631.2 | 21.67 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 156.146.38.168 |
| 71.31 | shadowsocks | 303.0 | 356.2 | 20.76 | 1.64 | 9.91 | 13.28 | 16.96 | Au1rxx-base64 | 149.22.87.204 |
| 71.17 | shadowsocks | 317.4 | 883.9 | 20.43 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 64.110.25.6 |
| 71.06 | shadowsocks | 343.6 | 868.5 | 19.82 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 156.146.38.169 |
| 70.87 | shadowsocks | 289.1 | 438.6 | 21.09 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 103.11.76.248 |
| 70.73 | shadowsocks | 366.0 | 795.6 | 19.3 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 37.19.198.243 |
| 70.7 | shadowsocks | 367.5 | 794.2 | 19.27 | 0.0 | 10.0 | 13.28 | 16.96 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.793 | 0.723 | 441 | 1767 | prefer |
| Surfboard-tg-mixed | 0.462 | 0.377 | 53 | 7281 | observe |
| DeltaKronecker-all | 0.413 | 0.329 | 79 | 5147 | observe |
| mheidari-all | 0.4 | 0.75 | 4 | 24080 | observe |
| ermaozi-get_subscribe | 0.332 | 1.0 | 2 | 519 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| Epodonios-all | 0.255 | None | 0 | 7794 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10074 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5707 | observe |
| barry-far-vless | 0.255 | None | 0 | 5961 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 73 |
| 204 | ProxyError | - | 33 |
| geo | ClientOSError | - | 32 |
| cn-block | TimeoutError | - | 29 |
| speed | ClientOSError | - | 15 |
| geo | TimeoutError | - | 14 |
| 204 | ProxyConnectionError | - | 13 |
| speed | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 5 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
