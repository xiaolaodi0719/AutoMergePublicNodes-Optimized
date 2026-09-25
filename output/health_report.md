# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 04:35:57 |
| 运行耗时 | 1030.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97835 |
| 去重后节点 | 26568 |
| TCP 可达 | 3000 |
| 真实可用 | 496 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26568 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.4 |
| tcp | 43.8 |
| probe | 361.6 |
| real_test | 531.8 |
| generate | 86.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59322 |
| vmess | 15099 |
| shadowsocks | 11810 |
| trojan | 9005 |
| hysteria2 | 1654 |
| http | 649 |
| shadowsocksr | 175 |
| socks | 74 |
| anytls | 24 |
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
| 85.29 | vless | 214.7 | 520.9 | 22.81 | 0.0 | 10.0 | 12.6 | 19.88 | Au1rxx-base64 | 195.123.240.65 |
| 82.58 | vless | 301.9 | 422.8 | 20.79 | 0.0 | 9.31 | 12.6 | 19.88 | Au1rxx-base64 | 172.235.43.210 |
| 82.39 | vless | 212.0 | 533.5 | 22.87 | 0.0 | 10.0 | 12.6 | 16.92 | mheidari-all | 172.233.139.46 |
| 82.25 | vless | 218.1 | 506.2 | 22.73 | 0.0 | 10.0 | 12.6 | 16.92 | mheidari-all | 47.251.108.158 |
| 80.95 | vless | 273.8 | 608.5 | 21.44 | 0.0 | 10.0 | 12.6 | 19.88 | Au1rxx-base64 | 15.204.97.216 |
| 80.94 | shadowsocks | 215.3 | 538.1 | 22.79 | 0.0 | 9.35 | 12.92 | 19.88 | Au1rxx-base64 | 173.244.56.6 |
| 79.95 | shadowsocks | 256.3 | 621.8 | 21.85 | 0.0 | 9.3 | 12.92 | 19.88 | Au1rxx-base64 | 156.146.38.167 |
| 79.95 | vless | 329.6 | 779.8 | 20.15 | 0.0 | 9.33 | 12.6 | 19.88 | Au1rxx-base64 | 5.78.159.214 |
| 79.8 | shadowsocks | 262.6 | 648.7 | 21.7 | 0.0 | 9.3 | 12.92 | 19.88 | Au1rxx-base64 | 156.146.38.170 |
| 78.79 | shadowsocks | 215.3 | 539.7 | 22.79 | 0.0 | 9.3 | 12.92 | 19.88 | Au1rxx-base64 | 173.244.56.9 |
| 77.89 | hysteria2 | 236.9 | 241.1 | 22.29 | 5.96 | 9.33 | 12.75 | 19.88 | Au1rxx-base64 | 43.167.208.94 |
| 77.21 | shadowsocks | 255.1 | 686.3 | 21.87 | 0.0 | 10.0 | 12.92 | 16.92 | mheidari-all | 192.3.247.109 |
| 76.98 | shadowsocks | 215.2 | 509.0 | 22.8 | 0.0 | 10.0 | 12.92 | 15.76 | Surfboard-tg-mixed | 108.181.0.177 |
| 76.9 | vless | 279.7 | 460.6 | 21.3 | 0.0 | 10.0 | 12.6 | 19.88 | Au1rxx-base64 | 104.18.34.14 |
| 76.9 | vless | 381.3 | 873.7 | 18.95 | 0.0 | 9.31 | 12.6 | 19.88 | Au1rxx-base64 | 136.117.218.86 |
| 76.81 | hysteria2 | 387.5 | 912.3 | 18.81 | 0.0 | 10.0 | 12.75 | 19.88 | Au1rxx-base64 | 159.223.157.129 |
| 76.66 | vless | 442.7 | 1094.9 | 17.53 | 0.0 | 9.31 | 12.6 | 19.88 | Au1rxx-base64 | 51.81.203.63 |
| 76.65 | trojan | 239.7 | 554.8 | 22.23 | 0.0 | 10.0 | 11.25 | 16.92 | mheidari-all | 100.42.228.109 |
| 76.62 | shadowsocks | 230.5 | 542.1 | 22.44 | 0.0 | 10.0 | 12.92 | 15.76 | Surfboard-tg-mixed | 108.181.118.10 |
| 76.53 | vless | 344.2 | 705.3 | 19.81 | 0.0 | 9.31 | 12.6 | 19.88 | Au1rxx-base64 | 195.211.98.43 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | 0.907 | 270 | 1702 | prefer |
| Surfboard-tg-mixed | 0.859 | 0.787 | 75 | 7399 | prefer |
| ermaozi | 0.621 | 0.615 | 26 | 338 | observe |
| ermaozi-get_subscribe | 0.399 | 0.714 | 7 | 359 | observe |
| mheidari-all | 0.359 | 0.278 | 601 | 22554 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| DeltaKronecker-all | 0.324 | 0.375 | 8 | 5845 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5307 | observe |
| Epodonios-all | 0.255 | None | 0 | 7876 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9018 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5862 | observe |
| barry-far-vless | 0.255 | None | 0 | 6091 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4405 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1702 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 183 |
| speed | TimeoutError | - | 98 |
| geo | ClientOSError | - | 47 |
| speed | ClientOSError | - | 45 |
| cn-block | ClientOSError | - | 42 |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 19 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| speed | ClientPayloadError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48396: bind: address already in use | - | 1 |
| geo | status | 403 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
