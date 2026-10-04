# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-04 12:13:05 |
| 运行耗时 | 526.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99561 |
| 去重后节点 | 27370 |
| TCP 可达 | 3000 |
| 真实可用 | 420 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27370 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 46.5 |
| probe | 217.4 |
| real_test | 180.1 |
| generate | 74.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59732 |
| vmess | 15756 |
| shadowsocks | 11571 |
| trojan | 10123 |
| hysteria2 | 1566 |
| http | 521 |
| shadowsocksr | 172 |
| socks | 70 |
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
| 79.94 | shadowsocks | 252.9 | 626.4 | 21.92 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 156.146.38.168 |
| 79.82 | shadowsocks | 258.3 | 633.9 | 21.8 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 156.146.38.170 |
| 79.62 | shadowsocks | 258.0 | 644.8 | 21.81 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 156.146.38.167 |
| 79.28 | shadowsocks | 281.5 | 729.8 | 21.26 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 37.19.198.236 |
| 79.28 | hysteria2 | 283.1 | 619.8 | 21.22 | 0.0 | 10.0 | 14.12 | 18.8 | Au1rxx-base64 | 66.94.121.46 |
| 79.2 | shadowsocks | 284.9 | 738.2 | 21.18 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 37.19.198.244 |
| 79.2 | shadowsocks | 285.1 | 740.3 | 21.18 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 37.19.198.160 |
| 77.55 | hysteria2 | 389.3 | 1088.8 | 18.77 | 0.0 | 10.0 | 14.12 | 16.16 | Surfboard-tg-mixed | 129.213.91.185 |
| 77.24 | shadowsocks | 255.8 | 629.2 | 21.86 | 0.0 | 10.0 | 13.22 | 16.16 | Surfboard-tg-mixed | 156.146.38.169 |
| 77.01 | shadowsocks | 344.0 | 861.2 | 19.81 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 140.82.63.79 |
| 76.7 | vless | 299.6 | 731.8 | 20.84 | 0.0 | 10.0 | 7.76 | 18.8 | Au1rxx-base64 | 159.89.87.21 |
| 76.28 | hysteria2 | 369.5 | 290.1 | 19.23 | 4.12 | 8.39 | 14.12 | 18.8 | Au1rxx-base64 | open.2ml.bid |
| 75.53 | vless | 380.7 | 994.4 | 18.97 | 0.0 | 10.0 | 7.76 | 18.8 | Au1rxx-base64 | 185.95.231.156 |
| 75.04 | vless | 369.5 | 916.1 | 19.23 | 0.0 | 10.0 | 7.76 | 18.8 | Au1rxx-base64 | 169.40.42.133 |
| 74.28 | shadowsocks | 313.6 | 660.9 | 20.52 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 149.22.95.183 |
| 74.12 | hysteria2 | 398.3 | 716.3 | 18.56 | 0.0 | 9.93 | 14.12 | 18.8 | Au1rxx-base64 | 62.210.124.146 |
| 74.08 | shadowsocks | 268.5 | 769.3 | 21.56 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 66.23.204.210 |
| 74.07 | shadowsocks | 324.5 | 732.2 | 20.27 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 108.181.57.93 |
| 74.02 | vless | 251.4 | 632.0 | 21.96 | 0.0 | 10.0 | 7.76 | 18.8 | Au1rxx-base64 | 69.48.201.136 |
| 73.97 | shadowsocks | 489.3 | 1382.2 | 16.45 | 0.0 | 10.0 | 13.22 | 18.8 | Au1rxx-base64 | 138.199.48.82 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.96 | 0.89 | 300 | 1816 | prefer |
| ermaozi | 0.946 | 0.957 | 23 | 646 | prefer |
| Surfboard-tg-mixed | 0.883 | 0.809 | 115 | 7269 | prefer |
| mheidari-all | 0.835 | 0.766 | 47 | 23332 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5173 | observe |
| Epodonios-all | 0.255 | None | 0 | 7796 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9804 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5821 | observe |
| barry-far-vless | 0.255 | None | 0 | 6148 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1816 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyError | - | 10 |
| speed | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| speed | ClientOSError | - | 3 |
| geo | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
