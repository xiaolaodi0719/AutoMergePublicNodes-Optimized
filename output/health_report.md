# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 16:20:55 |
| 运行耗时 | 724.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91095 |
| 去重后节点 | 24432 |
| TCP 可达 | 3000 |
| 真实可用 | 455 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24432 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 41.5 |
| probe | 318.1 |
| real_test | 277.2 |
| generate | 80.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55141 |
| vmess | 13254 |
| shadowsocks | 11137 |
| trojan | 8830 |
| hysteria2 | 1907 |
| http | 608 |
| shadowsocksr | 127 |
| socks | 58 |
| hysteria | 15 |
| tuic | 10 |
| anytls | 8 |

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
| 80.89 | vless | 200.5 | 506.5 | 23.14 | 0.0 | 9.28 | 9.51 | 18.96 | Au1rxx-base64 | 172.235.43.210 |
| 80.7 | vless | 204.8 | 507.4 | 23.04 | 0.0 | 9.19 | 9.51 | 18.96 | Au1rxx-base64 | 172.233.139.46 |
| 80.41 | vless | 222.3 | 567.6 | 22.63 | 0.0 | 9.31 | 9.51 | 18.96 | Au1rxx-base64 | 38.209.125.45 |
| 78.01 | vless | 320.8 | 839.7 | 20.35 | 0.0 | 9.19 | 9.51 | 18.96 | Au1rxx-base64 | 15.204.97.216 |
| 77.69 | shadowsocks | 225.5 | 551.5 | 22.56 | 0.0 | 10.0 | 13.33 | 16.3 | Surfboard-tg-mixed | 108.181.118.10 |
| 77.07 | shadowsocks | 273.8 | 678.2 | 21.44 | 0.0 | 10.0 | 13.33 | 16.3 | Surfboard-tg-mixed | 173.244.56.9 |
| 75.85 | shadowsocks | 283.5 | 709.8 | 21.22 | 0.0 | 10.0 | 13.33 | 16.3 | Surfboard-tg-mixed | 173.244.56.6 |
| 75.49 | shadowsocks | 294.9 | 671.6 | 20.95 | 0.0 | 9.2 | 13.33 | 18.96 | Au1rxx-base64 | 156.146.38.170 |
| 75.41 | shadowsocks | 291.8 | 660.5 | 21.02 | 0.0 | 9.2 | 13.33 | 18.96 | Au1rxx-base64 | 156.146.38.169 |
| 74.89 | shadowsocks | 297.7 | 783.2 | 20.89 | 0.0 | 9.16 | 13.33 | 18.96 | Au1rxx-base64 | 108.181.0.177 |
| 74.56 | hysteria2 | 359.0 | 735.4 | 19.47 | 0.0 | 9.42 | 12.5 | 18.96 | Au1rxx-base64 | 159.223.157.129 |
| 74.37 | shadowsocks | 294.7 | 661.4 | 20.96 | 0.0 | 9.2 | 13.33 | 18.96 | Au1rxx-base64 | 156.146.38.168 |
| 73.22 | vless | 344.7 | 754.7 | 19.8 | 0.0 | 9.21 | 9.51 | 18.96 | Au1rxx-base64 | 79.141.172.154 |
| 72.85 | vless | 288.4 | 309.9 | 21.1 | 3.38 | 9.77 | 9.51 | 16.3 | Surfboard-tg-mixed | 31.76.91.72 |
| 71.44 | vless | 416.8 | 316.6 | 18.13 | 3.13 | 9.19 | 9.51 | 18.96 | Au1rxx-base64 | 130.12.102.125 |
| 71.22 | shadowsocks | 319.0 | 648.3 | 20.39 | 0.0 | 10.0 | 13.33 | 16.3 | Surfboard-tg-mixed | 23.150.248.20 |
| 70.83 | vless | 505.2 | 1290.9 | 16.08 | 0.0 | 9.19 | 9.51 | 18.96 | Au1rxx-base64 | 51.81.203.63 |
| 70.65 | vless | 346.6 | 387.4 | 19.75 | 0.47 | 9.39 | 9.51 | 18.96 | Au1rxx-base64 | 130.12.102.62 |
| 70.41 | shadowsocks | 388.2 | 791.8 | 18.79 | 0.0 | 9.17 | 13.33 | 18.96 | Au1rxx-base64 | 37.19.198.160 |
| 70.4 | vless | 346.2 | 386.3 | 19.76 | 0.51 | 9.19 | 9.51 | 18.96 | Au1rxx-base64 | 130.12.102.26 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.931 | 0.865 | 275 | 1693 | prefer |
| ermaozi | 0.85 | 0.864 | 22 | 405 | prefer |
| Surfboard-tg-mixed | 0.78 | 0.703 | 158 | 7191 | prefer |
| mheidari-all | 0.62 | 0.541 | 159 | 19266 | observe |
| tg-oneclickvpnkeys | 0.264 | 1.0 | 1 | 214 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7902 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8955 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5790 | observe |
| barry-far-vless | 0.255 | None | 0 | 6248 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3508 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1693 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 50 |
| 204 | TimeoutError | - | 31 |
| cn-block | ClientOSError | - | 20 |
| 204 | ProxyError | - | 19 |
| cn-block | TimeoutError | - | 17 |
| speed | ClientOSError | - | 11 |
| geo | TimeoutError | - | 8 |
| speed | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
