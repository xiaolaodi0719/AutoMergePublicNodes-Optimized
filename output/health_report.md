# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 16:48:50 |
| 运行耗时 | 581.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 91321 |
| 去重后节点 | 25727 |
| TCP 可达 | 3000 |
| 真实可用 | 418 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25727 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.5 |
| tcp | 42.1 |
| probe | 226.5 |
| real_test | 219.8 |
| generate | 84.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56339 |
| vmess | 13498 |
| shadowsocks | 10067 |
| trojan | 8806 |
| hysteria2 | 1774 |
| http | 624 |
| shadowsocksr | 131 |
| socks | 54 |
| hysteria | 14 |
| anytls | 8 |
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
| 81.89 | hysteria2 | 260.7 | 512.7 | 21.74 | 0.0 | 10.0 | 13.64 | 18.48 | Au1rxx-base64 | 66.94.121.46 |
| 79.73 | vless | 305.3 | 756.7 | 20.71 | 0.0 | 10.0 | 10.54 | 18.48 | Au1rxx-base64 | 38.180.242.205 |
| 77.31 | vless | 277.0 | 594.8 | 21.36 | 0.0 | 10.0 | 10.54 | 18.48 | Au1rxx-base64 | 192.3.247.109 |
| 77.11 | vless | 320.8 | 745.9 | 20.35 | 0.0 | 10.0 | 10.54 | 18.48 | Au1rxx-base64 | 79.141.172.154 |
| 76.88 | hysteria2 | 336.0 | 707.3 | 20.0 | 0.0 | 10.0 | 13.64 | 18.48 | Au1rxx-base64 | 107.175.219.48 |
| 76.74 | vless | 319.8 | 712.2 | 20.37 | 0.0 | 10.0 | 10.54 | 18.48 | Au1rxx-base64 | 150.241.102.181 |
| 76.61 | shadowsocks | 269.6 | 566.0 | 21.54 | 0.0 | 10.0 | 13.75 | 18.48 | Au1rxx-base64 | 108.181.0.177 |
| 76.61 | vless | 275.0 | 590.0 | 21.41 | 0.0 | 10.0 | 10.54 | 18.48 | Au1rxx-base64 | 172.235.43.210 |
| 75.59 | hysteria2 | 305.1 | 693.2 | 20.71 | 0.0 | 10.0 | 13.64 | 14.84 | mheidari-all | 159.223.157.129 |
| 75.46 | vless | 354.1 | 854.2 | 19.58 | 0.0 | 8.64 | 10.54 | 18.48 | Au1rxx-base64 | 15.204.97.216 |
| 74.85 | shadowsocks | 296.3 | 677.8 | 20.92 | 0.0 | 8.87 | 13.75 | 18.48 | Au1rxx-base64 | 173.244.56.9 |
| 74.74 | shadowsocks | 297.5 | 694.2 | 20.89 | 0.0 | 8.89 | 13.75 | 18.48 | Au1rxx-base64 | 173.244.56.6 |
| 73.84 | vless | 344.7 | 709.4 | 19.8 | 0.0 | 10.0 | 10.54 | 18.48 | Au1rxx-base64 | 45.149.172.80 |
| 73.2 | vless | 355.0 | 725.8 | 19.56 | 0.0 | 8.64 | 10.54 | 18.48 | Au1rxx-base64 | 144.172.104.26 |
| 73.11 | shadowsocks | 296.4 | 585.9 | 20.92 | 0.0 | 8.77 | 13.75 | 18.48 | Au1rxx-base64 | 149.22.95.183 |
| 73.05 | vless | 358.3 | 779.8 | 19.48 | 0.0 | 8.91 | 10.54 | 18.48 | Au1rxx-base64 | 47.253.226.114 |
| 72.94 | shadowsocks | 345.8 | 832.3 | 19.77 | 0.0 | 10.0 | 13.75 | 13.92 | Surfboard-tg-mixed | 23.150.248.20 |
| 72.93 | shadowsocks | 272.9 | 524.2 | 21.46 | 0.0 | 10.0 | 13.75 | 13.92 | Surfboard-tg-mixed | 5.78.51.123 |
| 72.91 | vless | 365.0 | 747.1 | 19.33 | 0.0 | 10.0 | 10.54 | 18.48 | Au1rxx-base64 | 137.184.218.169 |
| 72.75 | shadowsocks | 244.2 | 606.2 | 22.12 | 0.0 | 10.0 | 13.75 | 18.48 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | 0.874 | 309 | 1553 | prefer |
| Surfboard-tg-mixed | 0.68 | 0.602 | 88 | 7516 | observe |
| mheidari-all | 0.517 | 0.436 | 188 | 21913 | observe |
| ermaozi | 0.416 | 0.391 | 23 | 406 | observe |
| DeltaKronecker-all | 0.349 | 0.667 | 3 | 5932 | observe |
| ermaozi-get_subscribe | 0.272 | 1.0 | 1 | 422 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 8076 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9411 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6065 | observe |
| barry-far-vless | 0.255 | None | 0 | 6401 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1553 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 55 |
| geo | ClientOSError | - | 40 |
| 204 | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 24 |
| 204 | ProxyError | - | 11 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyConnectionError | - | 10 |
| speed | TimeoutError | - | 9 |
| geo | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
