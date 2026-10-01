# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 22:40:15 |
| 运行耗时 | 555.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98426 |
| 去重后节点 | 27512 |
| TCP 可达 | 3000 |
| 真实可用 | 391 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27512 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 46.0 |
| probe | 253.5 |
| real_test | 161.7 |
| generate | 85.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60553 |
| vmess | 15307 |
| shadowsocks | 11569 |
| trojan | 9016 |
| hysteria2 | 1304 |
| http | 377 |
| shadowsocksr | 165 |
| socks | 60 |
| anytls | 52 |
| hysteria | 16 |
| tuic | 7 |

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
| 82.91 | hysteria2 | 205.4 | 532.5 | 23.02 | 0.0 | 10.0 | 13.57 | 17.32 | Au1rxx-base64 | 66.94.121.46 |
| 82.4 | hysteria2 | 227.6 | 533.3 | 22.51 | 0.0 | 10.0 | 13.57 | 17.32 | Au1rxx-base64 | 192.255.128.123 |
| 80.52 | vless | 213.6 | 551.0 | 22.83 | 0.0 | 10.0 | 10.37 | 17.32 | Au1rxx-base64 | 15.204.97.216 |
| 78.79 | shadowsocks | 206.9 | 552.4 | 22.99 | 0.0 | 10.0 | 12.48 | 17.32 | Au1rxx-base64 | 149.22.95.183 |
| 78.75 | hysteria2 | 270.9 | 292.5 | 21.51 | 4.03 | 9.39 | 13.57 | 17.32 | Au1rxx-base64 | open.2ml.bid |
| 78.51 | vless | 232.7 | 518.9 | 22.39 | 0.0 | 10.0 | 10.37 | 17.06 | mheidari-all | 47.251.108.158 |
| 77.67 | vless | 255.2 | 558.1 | 21.87 | 0.0 | 10.0 | 10.37 | 17.32 | Au1rxx-base64 | 172.233.139.46 |
| 77.66 | vless | 256.0 | 569.3 | 21.85 | 0.0 | 10.0 | 10.37 | 17.32 | Au1rxx-base64 | 23.95.222.127 |
| 77.14 | vless | 258.8 | 567.4 | 21.79 | 0.0 | 10.0 | 10.37 | 17.32 | Au1rxx-base64 | 172.235.43.210 |
| 76.58 | vless | 272.3 | 583.9 | 21.47 | 0.0 | 10.0 | 10.37 | 17.32 | Au1rxx-base64 | 195.123.240.65 |
| 76.28 | shadowsocks | 198.0 | 518.1 | 23.2 | 0.0 | 10.0 | 12.48 | 15.1 | Surfboard-tg-mixed | 5.78.51.123 |
| 75.49 | vless | 215.0 | 558.2 | 22.8 | 0.0 | 10.0 | 10.37 | 17.32 | Au1rxx-base64 | 15.204.97.195 |
| 74.99 | shadowsocks | 246.2 | 523.8 | 22.08 | 0.0 | 10.0 | 12.48 | 17.32 | Au1rxx-base64 | 108.181.0.177 |
| 74.72 | hysteria2 | 296.8 | 472.8 | 20.91 | 0.0 | 9.4 | 13.57 | 17.32 | Au1rxx-base64 | open.w2m.ink |
| 74.59 | hysteria2 | 348.8 | 736.2 | 19.7 | 0.0 | 10.0 | 13.57 | 17.06 | mheidari-all | 159.223.157.129 |
| 74.41 | shadowsocks | 290.7 | 695.1 | 21.05 | 0.0 | 10.0 | 12.48 | 17.32 | Au1rxx-base64 | 173.234.25.90 |
| 73.93 | vless | 313.1 | 318.7 | 20.53 | 3.05 | 9.97 | 10.37 | 17.32 | Au1rxx-base64 | 43.133.11.187 |
| 73.93 | vless | 346.2 | 766.8 | 19.76 | 0.0 | 10.0 | 10.37 | 17.32 | Au1rxx-base64 | 79.141.172.154 |
| 73.52 | vless | 336.3 | 318.3 | 19.99 | 3.06 | 10.0 | 10.37 | 17.32 | Au1rxx-base64 | 46.250.250.149 |
| 73.38 | vless | 522.2 | 1361.0 | 15.69 | 0.0 | 10.0 | 10.37 | 17.32 | Au1rxx-base64 | 51.81.203.63 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.955 | 0.883 | 94 | 22987 | prefer |
| Au1rxx-base64 | 0.954 | 0.884 | 276 | 1818 | prefer |
| zhangkai | 0.839 | 0.864 | 22 | 144 | prefer |
| Surfboard-tg-mixed | 0.821 | 0.75 | 52 | 7183 | prefer |
| DeltaKronecker-all | 0.352 | 0.5 | 6 | 5603 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ermaozi-get_subscribe | 0.275 | 1.0 | 1 | 512 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 149 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5324 | observe |
| Epodonios-all | 0.255 | None | 0 | 7711 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9539 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5811 | observe |
| barry-far-vless | 0.255 | None | 0 | 6097 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4310 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 12 |
| speed | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 10 |
| 204 | ProxyConnectionError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| speed | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| geo | TimeoutError | - | 4 |
| geo | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
