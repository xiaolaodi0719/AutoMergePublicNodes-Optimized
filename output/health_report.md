# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 11:22:32 |
| 运行耗时 | 609.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 87785 |
| 去重后节点 | 24305 |
| TCP 可达 | 3000 |
| 真实可用 | 440 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24305 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.4 |
| tcp | 40.9 |
| probe | 228.5 |
| real_test | 240.3 |
| generate | 91.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52933 |
| vmess | 13613 |
| shadowsocks | 10040 |
| trojan | 8791 |
| hysteria2 | 1549 |
| http | 653 |
| shadowsocksr | 129 |
| socks | 62 |
| hysteria | 8 |
| tuic | 5 |
| anytls | 2 |

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
| 82.97 | hysteria2 | 246.2 | 631.3 | 22.08 | 0.0 | 10.0 | 12.95 | 18.94 | Au1rxx-base64 | 107.175.219.48 |
| 82.53 | hysteria2 | 193.5 | 463.3 | 23.3 | 0.0 | 10.0 | 12.95 | 17.28 | Surfboard-tg-mixed | 45.149.172.74 |
| 82.51 | hysteria2 | 194.4 | 462.7 | 23.28 | 0.0 | 10.0 | 12.95 | 17.28 | Surfboard-tg-mixed | 45.149.172.80 |
| 81.09 | shadowsocks | 234.4 | 559.3 | 22.35 | 0.0 | 10.0 | 13.8 | 18.94 | Au1rxx-base64 | 173.244.56.9 |
| 80.65 | shadowsocks | 231.7 | 585.0 | 22.41 | 0.0 | 10.0 | 13.8 | 18.94 | Au1rxx-base64 | 108.181.0.177 |
| 80.47 | shadowsocks | 239.5 | 614.9 | 22.23 | 0.0 | 10.0 | 13.8 | 18.94 | Au1rxx-base64 | 108.181.118.10 |
| 80.36 | http | 200.4 | 497.2 | 23.14 | 0.0 | 10.0 | 12.86 | 17.36 | ermaozi | 138.199.35.198 |
| 80.23 | http | 206.0 | 501.9 | 23.01 | 0.0 | 10.0 | 12.86 | 17.36 | ermaozi | 138.199.35.212 |
| 80.07 | shadowsocks | 256.8 | 676.7 | 21.83 | 0.0 | 10.0 | 13.8 | 18.94 | Au1rxx-base64 | 5.78.51.123 |
| 80.05 | http | 213.7 | 508.5 | 22.83 | 0.0 | 10.0 | 12.86 | 17.36 | ermaozi | 138.199.35.201 |
| 80.0 | http | 215.8 | 514.1 | 22.78 | 0.0 | 10.0 | 12.86 | 17.36 | ermaozi | 138.199.35.210 |
| 79.42 | http | 240.8 | 485.6 | 22.2 | 0.0 | 10.0 | 12.86 | 17.36 | ermaozi | 138.199.35.205 |
| 79.28 | vless | 193.2 | 486.1 | 23.3 | 0.0 | 10.0 | 7.04 | 18.94 | Au1rxx-base64 | 45.149.172.80 |
| 79.16 | vless | 198.8 | 500.9 | 23.18 | 0.0 | 10.0 | 7.04 | 18.94 | Au1rxx-base64 | 172.235.43.210 |
| 78.53 | trojan | 215.2 | 541.2 | 22.8 | 0.0 | 10.0 | 9.29 | 18.94 | Au1rxx-base64 | 100.42.228.109 |
| 78.4 | vless | 231.5 | 538.6 | 22.42 | 0.0 | 10.0 | 7.04 | 18.94 | Au1rxx-base64 | 150.241.102.181 |
| 75.64 | shadowsocks | 224.7 | 541.3 | 22.58 | 0.0 | 10.0 | 13.8 | 13.26 | mheidari-all | 173.244.56.6 |
| 75.58 | shadowsocks | 227.2 | 540.6 | 22.52 | 0.0 | 10.0 | 13.8 | 13.26 | mheidari-all | 149.22.95.183 |
| 75.53 | http | 239.3 | 589.4 | 22.24 | 0.0 | 10.0 | 12.86 | 17.36 | ermaozi | 138.199.35.206 |
| 75.46 | shadowsocks | 294.9 | 670.3 | 20.95 | 0.0 | 9.27 | 13.8 | 18.94 | Au1rxx-base64 | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.943 | 0.878 | 49 | 16003 | prefer |
| Au1rxx-base64 | 0.926 | 0.86 | 301 | 1687 | prefer |
| ermaozi | 0.736 | 0.727 | 55 | 407 | prefer |
| DeltaKronecker-all | 0.708 | 0.75 | 16 | 6081 | prefer |
| Surfboard-tg-mixed | 0.704 | 0.626 | 123 | 7446 | prefer |
| ermaozi-get_subscribe | 0.445 | 0.471 | 17 | 438 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5115 | observe |
| Epodonios-all | 0.255 | None | 0 | 8003 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9052 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6044 | observe |
| barry-far-vless | 0.255 | None | 0 | 6340 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4206 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 24 |
| 204 | ProxyError | - | 22 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 17 |
| speed | ClientOSError | - | 12 |
| geo | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:43353: bind: address already in use | - | 1 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
