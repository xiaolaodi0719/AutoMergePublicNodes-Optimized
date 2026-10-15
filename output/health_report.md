# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 04:09:57 |
| 运行耗时 | 554.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98808 |
| 去重后节点 | 27486 |
| TCP 可达 | 3000 |
| 真实可用 | 233 |
| Verified 输出 | 233 |
| Global 输出 | 240 |
| All 输出 | 27486 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.6 |
| tcp | 47.7 |
| probe | 237.2 |
| real_test | 236.8 |
| generate | 23.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58478 |
| vmess | 16366 |
| shadowsocks | 11783 |
| trojan | 10087 |
| hysteria2 | 1149 |
| http | 657 |
| shadowsocksr | 165 |
| socks | 68 |
| anytls | 32 |
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
| 81.58 | hysteria2 | 274.3 | 708.5 | 21.43 | 0.0 | 10.0 | 13.33 | 18.32 | Au1rxx-base64 | 129.213.91.185 |
| 79.17 | shadowsocks | 280.4 | 721.9 | 21.29 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 156.146.38.170 |
| 77.88 | shadowsocks | 314.6 | 714.8 | 20.5 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 140.82.63.79 |
| 77.81 | shadowsocks | 304.5 | 751.2 | 20.73 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 37.19.198.243 |
| 77.67 | shadowsocks | 302.2 | 737.1 | 20.78 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 37.19.198.236 |
| 77.54 | vless | 272.3 | 545.7 | 21.47 | 0.0 | 10.0 | 11.72 | 18.52 | mheidari-all | 47.251.108.158 |
| 77.3 | shadowsocks | 307.1 | 755.4 | 20.67 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 37.19.198.244 |
| 77.28 | shadowsocks | 303.7 | 747.6 | 20.75 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 37.19.198.160 |
| 75.05 | shadowsocks | 321.1 | 769.9 | 20.34 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 64.74.163.69 |
| 74.48 | shadowsocks | 302.3 | 628.4 | 20.78 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 149.22.95.183 |
| 74.07 | shadowsocks | 292.5 | 587.4 | 21.01 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 173.244.56.6 |
| 73.94 | shadowsocks | 295.5 | 592.3 | 20.94 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 173.244.56.9 |
| 72.77 | shadowsocks | 319.0 | 769.2 | 20.39 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 64.74.163.67 |
| 72.53 | trojan | 359.8 | 721.1 | 19.45 | 0.0 | 10.0 | 13.95 | 18.32 | Au1rxx-base64 | 107.149.159.190 |
| 72.51 | hysteria2 | 401.9 | 719.9 | 18.47 | 0.0 | 9.85 | 13.33 | 18.32 | Au1rxx-base64 | 62.210.124.146 |
| 72.4 | shadowsocks | 404.2 | 969.3 | 18.42 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 15.204.233.41 |
| 72.37 | shadowsocks | 279.2 | 738.8 | 21.32 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 156.146.38.167 |
| 72.1 | shadowsocks | 337.8 | 333.4 | 19.96 | 2.5 | 9.62 | 13.56 | 18.32 | Au1rxx-base64 | 149.22.87.204 |
| 70.43 | shadowsocks | 443.7 | 732.5 | 17.51 | 0.0 | 10.0 | 13.56 | 18.32 | Au1rxx-base64 | 103.11.76.248 |
| 70.3 | hysteria2 | 486.0 | 867.5 | 16.53 | 0.0 | 9.46 | 13.33 | 18.66 | Surfboard-tg-mixed | 162.249.125.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | 0.937 | 190 | 1576 | prefer |
| ermaozi | 0.467 | 0.436 | 55 | 703 | observe |
| Surfboard-tg-mixed | 0.43 | 0.342 | 38 | 7169 | observe |
| ermaozi-get_subscribe | 0.382 | 1.0 | 3 | 595 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7681 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9917 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5728 | observe |
| barry-far-vless | 0.255 | None | 0 | 5978 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4271 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| DeltaKronecker-all | 0.249 | 0.2 | 10 | 4803 | downweight |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1576 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 83 |
| 204 | ProxyError | - | 31 |
| geo | ClientOSError | - | 22 |
| speed | TimeoutError | - | 10 |
| 204 | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 6 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 233 | - |
| global | False | 300 | 240 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
