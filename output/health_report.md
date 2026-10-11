# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-11 12:39:19 |
| 运行耗时 | 768.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98718 |
| 去重后节点 | 27554 |
| TCP 可达 | 3000 |
| 真实可用 | 479 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27554 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 45.3 |
| probe | 297.1 |
| real_test | 337.3 |
| generate | 78.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57607 |
| vmess | 15774 |
| shadowsocks | 11948 |
| trojan | 10867 |
| hysteria2 | 1601 |
| http | 633 |
| shadowsocksr | 163 |
| socks | 70 |
| anytls | 30 |
| hysteria | 16 |
| tuic | 9 |

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
| 83.72 | hysteria2 | 249.3 | 237.2 | 22.01 | 6.1 | 9.94 | 13.12 | 19.5 | Au1rxx-base64 | 158.101.148.79 |
| 82.14 | hysteria2 | 241.3 | 253.9 | 22.19 | 5.48 | 9.04 | 13.12 | 19.5 | Au1rxx-base64 | open.2ml.bid |
| 82.09 | shadowsocks | 209.1 | 534.3 | 22.94 | 0.0 | 10.0 | 14.15 | 19.5 | Au1rxx-base64 | 5.78.51.123 |
| 81.78 | shadowsocks | 244.1 | 594.9 | 22.13 | 0.0 | 10.0 | 14.15 | 19.5 | Au1rxx-base64 | 149.22.95.183 |
| 81.75 | trojan | 249.7 | 584.4 | 22.0 | 0.0 | 8.23 | 14.52 | 19.5 | Au1rxx-base64 | pro-mako.rooster465.autos |
| 81.2 | shadowsocks | 268.0 | 522.0 | 21.57 | 0.0 | 10.0 | 14.15 | 19.5 | Au1rxx-base64 | 173.244.56.6 |
| 81.12 | trojan | 291.6 | 714.4 | 21.03 | 0.0 | 8.57 | 14.52 | 19.5 | Au1rxx-base64 | alert-titmouse.rooster465.autos |
| 79.47 | vless | 178.4 | 481.1 | 23.65 | 0.0 | 10.0 | 6.32 | 19.5 | Au1rxx-base64 | 137.175.82.40 |
| 78.57 | vless | 217.2 | 526.8 | 22.75 | 0.0 | 10.0 | 6.32 | 19.5 | Au1rxx-base64 | 195.123.240.65 |
| 78.55 | vless | 218.0 | 554.9 | 22.73 | 0.0 | 10.0 | 6.32 | 19.5 | Au1rxx-base64 | 154.12.38.202 |
| 78.54 | trojan | 248.6 | 584.5 | 22.02 | 0.0 | 10.0 | 14.52 | 19.5 | Au1rxx-base64 | 16.144.66.136 |
| 78.22 | vless | 232.4 | 563.8 | 22.4 | 0.0 | 10.0 | 6.32 | 19.5 | Au1rxx-base64 | 15.204.97.216 |
| 78.21 | vless | 232.7 | 572.5 | 22.39 | 0.0 | 10.0 | 6.32 | 19.5 | Au1rxx-base64 | 15.204.97.197 |
| 78.19 | shadowsocks | 274.9 | 283.3 | 21.41 | 4.37 | 9.93 | 14.15 | 19.5 | Au1rxx-base64 | 149.22.87.241 |
| 77.86 | shadowsocks | 268.2 | 583.3 | 21.57 | 0.0 | 10.0 | 14.15 | 19.5 | Au1rxx-base64 | 173.244.56.9 |
| 77.66 | vless | 256.3 | 686.3 | 21.84 | 0.0 | 10.0 | 6.32 | 19.5 | Au1rxx-base64 | 23.95.222.127 |
| 77.47 | hysteria2 | 347.3 | 766.1 | 19.74 | 0.0 | 10.0 | 13.12 | 19.5 | Au1rxx-base64 | 129.213.91.185 |
| 77.03 | vless | 240.4 | 544.1 | 22.21 | 0.0 | 10.0 | 6.32 | 19.5 | Au1rxx-base64 | 154.12.38.159 |
| 76.46 | shadowsocks | 236.4 | 653.1 | 22.31 | 0.0 | 10.0 | 14.15 | 19.5 | Au1rxx-base64 | 64.110.25.2 |
| 76.37 | trojan | 326.5 | 330.1 | 20.22 | 2.62 | 9.93 | 14.52 | 19.5 | Au1rxx-base64 | 45.32.52.173 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | 0.923 | 364 | 1835 | prefer |
| mheidari-all | 0.994 | 0.929 | 56 | 23631 | prefer |
| DeltaKronecker-all | 0.853 | 0.786 | 42 | 5372 | prefer |
| Surfboard-tg-mixed | 0.853 | 0.781 | 64 | 7157 | prefer |
| ermaozi | 0.412 | 0.438 | 16 | 635 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5099 | observe |
| Epodonios-all | 0.255 | None | 0 | 7574 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9584 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5553 | observe |
| barry-far-vless | 0.255 | None | 0 | 5786 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4318 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1835 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 14 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyConnectionError | - | 9 |
| 204 | ProxyError | - | 9 |
| geo | TimeoutError | - | 5 |
| speed | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
