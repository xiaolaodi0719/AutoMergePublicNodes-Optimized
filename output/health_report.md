# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 11:16:19 |
| 运行耗时 | 590.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97168 |
| 去重后节点 | 26417 |
| TCP 可达 | 3000 |
| 真实可用 | 354 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26417 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.6 |
| tcp | 43.5 |
| probe | 269.9 |
| real_test | 180.9 |
| generate | 87.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59131 |
| vmess | 15228 |
| shadowsocks | 11254 |
| trojan | 8979 |
| hysteria2 | 1571 |
| http | 672 |
| shadowsocksr | 176 |
| socks | 98 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 12 |

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
| 80.24 | shadowsocks | 284.8 | 737.9 | 21.19 | 0.0 | 10.0 | 14.01 | 19.04 | Au1rxx-base64 | 37.19.198.236 |
| 78.93 | shadowsocks | 284.4 | 734.9 | 21.2 | 0.0 | 8.68 | 14.01 | 19.04 | Au1rxx-base64 | 37.19.198.244 |
| 76.85 | shadowsocks | 321.3 | 883.0 | 20.34 | 0.0 | 7.96 | 14.01 | 19.04 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 76.5 | shadowsocks | 370.7 | 913.3 | 19.2 | 0.0 | 8.75 | 14.01 | 19.04 | Au1rxx-base64 | 15.204.247.206 |
| 76.27 | vless | 218.8 | 605.1 | 22.71 | 0.0 | 8.59 | 5.93 | 19.04 | Au1rxx-base64 | 195.211.98.43 |
| 76.05 | shadowsocks | 338.8 | 822.4 | 19.93 | 0.0 | 8.75 | 14.01 | 19.04 | Au1rxx-base64 | 38.180.135.156 |
| 75.96 | hysteria2 | 306.6 | 296.8 | 20.68 | 3.87 | 6.66 | 13.85 | 19.04 | Au1rxx-base64 | open.w2m.ink |
| 75.63 | shadowsocks | 307.0 | 647.9 | 20.67 | 0.0 | 10.0 | 14.01 | 19.04 | Au1rxx-base64 | 149.22.95.183 |
| 75.29 | vless | 262.5 | 660.2 | 21.7 | 0.0 | 8.62 | 5.93 | 19.04 | Au1rxx-base64 | 198.251.78.29 |
| 75.08 | vless | 271.0 | 702.2 | 21.5 | 0.0 | 8.61 | 5.93 | 19.04 | Au1rxx-base64 | 79.141.172.154 |
| 74.3 | shadowsocks | 380.7 | 892.8 | 18.96 | 0.0 | 10.0 | 14.01 | 19.04 | Au1rxx-base64 | 108.181.57.93 |
| 73.66 | vless | 332.8 | 716.8 | 20.07 | 0.0 | 8.62 | 5.93 | 19.04 | Au1rxx-base64 | 169.40.42.212 |
| 73.19 | vless | 304.4 | 733.5 | 20.73 | 0.0 | 8.7 | 5.93 | 19.04 | Au1rxx-base64 | 66.70.179.198 |
| 72.45 | vless | 384.5 | 923.1 | 18.88 | 0.0 | 8.6 | 5.93 | 19.04 | Au1rxx-base64 | 169.40.42.35 |
| 72.43 | vless | 388.2 | 1010.2 | 18.79 | 0.0 | 8.67 | 5.93 | 19.04 | Au1rxx-base64 | 185.95.231.233 |
| 72.29 | vless | 313.4 | 782.5 | 20.52 | 0.0 | 8.62 | 5.93 | 19.04 | Au1rxx-base64 | 169.40.42.225 |
| 72.04 | vless | 405.0 | 1006.6 | 18.4 | 0.0 | 8.67 | 5.93 | 19.04 | Au1rxx-base64 | 169.40.42.75 |
| 71.89 | vless | 409.6 | 1083.8 | 18.3 | 0.0 | 8.62 | 5.93 | 19.04 | Au1rxx-base64 | 185.95.231.156 |
| 71.77 | vless | 309.6 | 782.3 | 20.61 | 0.0 | 8.67 | 5.93 | 19.04 | Au1rxx-base64 | 38.77.133.202 |
| 71.45 | hysteria2 | 478.3 | 1009.2 | 16.71 | 0.0 | 8.74 | 13.85 | 19.04 | Au1rxx-base64 | 5.129.235.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | 0.891 | 239 | 1660 | prefer |
| mheidari-all | 0.67 | 0.592 | 103 | 22392 | observe |
| Surfboard-tg-mixed | 0.64 | 0.561 | 107 | 7247 | observe |
| ermaozi | 0.424 | 0.405 | 37 | 352 | observe |
| DeltaKronecker-all | 0.337 | 0.429 | 7 | 5512 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7713 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9376 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5840 | observe |
| barry-far-vless | 0.255 | None | 0 | 6071 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1660 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 30 |
| 204 | TimeoutError | - | 29 |
| cn-block | ClientOSError | - | 27 |
| 204 | ProxyError | - | 25 |
| geo | TimeoutError | - | 15 |
| speed | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 3 |
| geo | ClientOSError | - | 3 |
| speed | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
