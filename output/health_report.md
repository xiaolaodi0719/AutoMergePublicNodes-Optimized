# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 04:33:44 |
| 运行耗时 | 863.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89183 |
| 去重后节点 | 24536 |
| TCP 可达 | 3000 |
| 真实可用 | 530 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24536 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 41.2 |
| probe | 359.4 |
| real_test | 376.5 |
| generate | 79.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52802 |
| vmess | 14151 |
| shadowsocks | 10863 |
| trojan | 9055 |
| hysteria2 | 1422 |
| http | 676 |
| shadowsocksr | 125 |
| socks | 77 |
| hysteria | 8 |
| tuic | 2 |
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
| 83.56 | vless | 194.0 | 507.8 | 23.29 | 0.0 | 10.0 | 11.69 | 18.58 | Au1rxx-base64 | 172.235.43.210 |
| 81.48 | vless | 283.9 | 725.2 | 21.21 | 0.0 | 10.0 | 11.69 | 18.58 | Au1rxx-base64 | 45.149.172.74 |
| 81.09 | hysteria2 | 250.4 | 551.0 | 21.98 | 0.0 | 10.0 | 13.27 | 18.58 | Au1rxx-base64 | 66.94.121.46 |
| 81.04 | shadowsocks | 211.1 | 524.9 | 22.89 | 0.0 | 10.0 | 13.57 | 18.58 | Au1rxx-base64 | 173.244.56.9 |
| 80.02 | vless | 199.5 | 496.6 | 23.16 | 0.0 | 10.0 | 11.69 | 18.58 | Au1rxx-base64 | 45.149.172.80 |
| 79.31 | http | 193.8 | 498.2 | 23.29 | 0.0 | 10.0 | 12.08 | 16.94 | ermaozi | 138.199.35.205 |
| 79.28 | vless | 250.3 | 522.9 | 21.98 | 0.0 | 10.0 | 11.69 | 18.58 | Au1rxx-base64 | 144.172.104.26 |
| 79.23 | http | 197.3 | 500.5 | 23.21 | 0.0 | 10.0 | 12.08 | 16.94 | ermaozi | 138.199.35.198 |
| 79.22 | http | 197.9 | 514.7 | 23.2 | 0.0 | 10.0 | 12.08 | 16.94 | ermaozi | 138.199.35.210 |
| 79.19 | http | 199.0 | 512.2 | 23.17 | 0.0 | 10.0 | 12.08 | 16.94 | ermaozi | 138.199.35.216 |
| 79.16 | shadowsocks | 217.1 | 535.4 | 22.75 | 0.0 | 10.0 | 13.57 | 17.34 | Surfboard-tg-mixed | 108.181.118.10 |
| 78.97 | http | 208.6 | 526.4 | 22.95 | 0.0 | 10.0 | 12.08 | 16.94 | ermaozi | 138.199.35.212 |
| 78.69 | vless | 209.7 | 517.8 | 22.92 | 0.0 | 10.0 | 11.69 | 18.58 | Au1rxx-base64 | 172.64.32.108 |
| 78.6 | shadowsocks | 263.0 | 642.4 | 21.69 | 0.0 | 10.0 | 13.57 | 17.34 | Surfboard-tg-mixed | 156.146.38.169 |
| 78.56 | shadowsocks | 243.0 | 611.0 | 22.15 | 0.0 | 10.0 | 13.57 | 17.34 | Surfboard-tg-mixed | 108.181.0.177 |
| 78.42 | shadowsocks | 257.5 | 621.2 | 21.82 | 0.0 | 10.0 | 13.57 | 18.58 | Au1rxx-base64 | 156.146.38.168 |
| 78.34 | vless | 225.2 | 476.3 | 22.57 | 0.0 | 10.0 | 11.69 | 18.58 | Au1rxx-base64 | 172.64.53.55 |
| 78.24 | vless | 229.1 | 498.5 | 22.47 | 0.0 | 10.0 | 11.69 | 18.58 | Au1rxx-base64 | 104.18.39.218 |
| 78.1 | shadowsocks | 284.6 | 663.8 | 21.19 | 0.0 | 10.0 | 13.57 | 17.34 | mheidari-all | 173.244.56.6 |
| 78.1 | vless | 338.0 | 729.5 | 19.95 | 0.0 | 10.0 | 11.69 | 18.58 | Au1rxx-base64 | 79.141.172.154 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.939 | 0.878 | 278 | 1590 | prefer |
| ermaozi | 0.785 | 0.792 | 24 | 396 | prefer |
| Surfboard-tg-mixed | 0.713 | 0.634 | 257 | 7408 | prefer |
| mheidari-all | 0.547 | 0.467 | 165 | 17792 | observe |
| DeltaKronecker-all | 0.438 | 0.353 | 51 | 6081 | observe |
| ermaozi-get_subscribe | 0.411 | 0.6 | 10 | 431 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4234 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 130 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5115 | observe |
| Epodonios-all | 0.255 | None | 0 | 7930 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9115 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5925 | observe |
| barry-far-vless | 0.255 | None | 0 | 6194 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 69 |
| speed | TimeoutError | - | 46 |
| geo | ClientOSError | - | 44 |
| speed | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 19 |
| cn-block | ClientOSError | - | 18 |
| 204 | TimeoutError | - | 15 |
| cn-block | ProxyError | - | 1 |
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
