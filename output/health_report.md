# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-06 22:40:16 |
| 运行耗时 | 487.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97769 |
| 去重后节点 | 27067 |
| TCP 可达 | 3000 |
| 真实可用 | 526 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27067 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 45.7 |
| probe | 181.4 |
| real_test | 178.1 |
| generate | 73.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57630 |
| vmess | 15982 |
| shadowsocks | 11597 |
| trojan | 10104 |
| hysteria2 | 1424 |
| http | 704 |
| shadowsocksr | 164 |
| socks | 103 |
| anytls | 36 |
| hysteria | 17 |
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
| 83.37 | hysteria2 | 269.6 | 703.8 | 21.54 | 0.0 | 10.0 | 13.33 | 20.0 | Au1rxx-base64 | 129.213.91.185 |
| 81.49 | shadowsocks | 252.0 | 628.7 | 21.94 | 0.0 | 10.0 | 13.55 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 81.46 | vless | 301.4 | 736.3 | 20.8 | 0.0 | 10.0 | 10.77 | 20.0 | Au1rxx-base64 | 159.89.87.21 |
| 81.36 | shadowsocks | 257.6 | 634.3 | 21.81 | 0.0 | 10.0 | 13.55 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.32 | shadowsocks | 259.4 | 636.4 | 21.77 | 0.0 | 10.0 | 13.55 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.98 | hysteria2 | 305.2 | 754.1 | 20.71 | 0.0 | 10.0 | 13.33 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 80.66 | shadowsocks | 288.2 | 738.4 | 21.11 | 0.0 | 10.0 | 13.55 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 80.45 | shadowsocks | 297.2 | 740.4 | 20.9 | 0.0 | 10.0 | 13.55 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 80.4 | shadowsocks | 251.0 | 626.3 | 21.97 | 0.0 | 10.0 | 13.55 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 80.26 | vless | 341.5 | 844.4 | 19.87 | 0.0 | 10.0 | 10.77 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 80.19 | vless | 305.8 | 734.0 | 20.7 | 0.0 | 10.0 | 10.77 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 79.7 | shadowsocks | 290.5 | 688.8 | 21.05 | 0.0 | 10.0 | 13.55 | 20.0 | Au1rxx-base64 | 140.82.63.79 |
| 79.63 | vless | 367.5 | 952.1 | 19.27 | 0.0 | 10.0 | 10.77 | 20.0 | Au1rxx-base64 | 185.95.231.156 |
| 79.44 | vless | 273.2 | 639.2 | 21.45 | 0.0 | 10.0 | 10.77 | 18.22 | Surfboard-tg-mixed | 198.251.78.29 |
| 79.4 | shadowsocks | 342.4 | 906.6 | 19.85 | 0.0 | 10.0 | 13.55 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 79.13 | shadowsocks | 354.2 | 928.6 | 19.58 | 0.0 | 10.0 | 13.55 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 78.77 | vless | 336.4 | 806.6 | 19.99 | 0.0 | 10.0 | 10.77 | 20.0 | Au1rxx-base64 | 2.24.124.64 |
| 78.72 | vless | 415.9 | 954.6 | 18.15 | 0.0 | 10.0 | 10.77 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 78.71 | shadowsocks | 273.8 | 791.4 | 21.44 | 0.0 | 10.0 | 13.55 | 18.22 | Surfboard-tg-mixed | 66.23.204.210 |
| 78.66 | hysteria2 | 297.9 | 290.5 | 20.88 | 4.1 | 8.27 | 13.33 | 20.0 | Au1rxx-base64 | open.2ml.bid |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.953 | 339 | 1829 | prefer |
| mheidari-all | 1.0 | 0.941 | 51 | 23303 | prefer |
| Surfboard-tg-mixed | 0.879 | 0.802 | 162 | 7055 | prefer |
| ermaozi | 0.487 | 0.457 | 46 | 708 | observe |
| ermaozi-get_subscribe | 0.279 | 1.0 | 1 | 597 | observe |
| DeltaKronecker-all | 0.263 | 0.25 | 8 | 4889 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Epodonios-all | 0.255 | None | 0 | 7604 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9213 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5593 | observe |
| barry-far-vless | 0.255 | None | 0 | 5954 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4373 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 27 |
| cn-block | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 9 |
| geo | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| speed | ClientOSError | - | 6 |
| speed | TimeoutError | - | 5 |
| geo | TimeoutError | - | 4 |
| geo | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
