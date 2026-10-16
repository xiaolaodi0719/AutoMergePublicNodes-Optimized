# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 04:10:47 |
| 运行耗时 | 768.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99761 |
| 去重后节点 | 27965 |
| TCP 可达 | 3000 |
| 真实可用 | 538 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27965 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.4 |
| tcp | 48.8 |
| probe | 261.2 |
| real_test | 374.8 |
| generate | 77.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58945 |
| vmess | 16453 |
| shadowsocks | 11836 |
| trojan | 10316 |
| hysteria2 | 1225 |
| http | 713 |
| shadowsocksr | 166 |
| socks | 59 |
| anytls | 25 |
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
| 79.35 | hysteria2 | 273.9 | 706.3 | 21.44 | 0.0 | 10.0 | 12.35 | 17.06 | Au1rxx-base64 | 129.213.91.185 |
| 76.44 | shadowsocks | 253.5 | 629.3 | 21.91 | 0.0 | 8.91 | 13.56 | 17.06 | Au1rxx-base64 | 156.146.38.167 |
| 75.88 | shadowsocks | 304.7 | 741.7 | 20.72 | 0.0 | 8.92 | 13.56 | 17.06 | Au1rxx-base64 | 37.19.198.244 |
| 75.75 | shadowsocks | 306.2 | 754.0 | 20.69 | 0.0 | 8.94 | 13.56 | 17.06 | Au1rxx-base64 | 37.19.198.243 |
| 74.96 | shadowsocks | 298.6 | 744.3 | 20.86 | 0.0 | 8.91 | 13.56 | 17.06 | Au1rxx-base64 | 37.19.198.160 |
| 74.62 | shadowsocks | 336.0 | 900.8 | 20.0 | 0.0 | 10.0 | 13.56 | 17.06 | Au1rxx-base64 | 156.146.38.169 |
| 73.88 | shadowsocks | 371.2 | 950.2 | 19.18 | 0.0 | 10.0 | 13.56 | 17.06 | Au1rxx-base64 | 15.204.233.41 |
| 73.19 | vless | 290.0 | 638.8 | 21.06 | 0.0 | 9.05 | 9.69 | 17.06 | Au1rxx-base64 | 195.123.235.183 |
| 73.15 | shadowsocks | 299.8 | 607.8 | 20.84 | 0.0 | 10.0 | 13.56 | 17.06 | Au1rxx-base64 | 173.244.56.6 |
| 73.15 | vless | 331.3 | 752.1 | 20.11 | 0.0 | 8.96 | 9.69 | 17.06 | Au1rxx-base64 | 137.184.218.169 |
| 72.96 | hysteria2 | 245.2 | 530.2 | 22.1 | 0.0 | 8.93 | 12.35 | 17.06 | Au1rxx-base64 | 179.255.104.98 |
| 72.89 | vless | 350.0 | 765.7 | 19.68 | 0.0 | 9.06 | 9.69 | 17.06 | Au1rxx-base64 | 66.70.179.198 |
| 72.61 | shadowsocks | 246.1 | 635.5 | 22.08 | 0.0 | 8.91 | 13.56 | 17.06 | Au1rxx-base64 | 156.146.38.170 |
| 72.49 | vless | 263.7 | 659.0 | 21.67 | 0.0 | 9.07 | 9.69 | 17.06 | Au1rxx-base64 | 195.211.98.43 |
| 72.04 | vless | 443.5 | 1108.8 | 17.51 | 0.0 | 9.0 | 9.69 | 17.06 | Au1rxx-base64 | 185.95.231.156 |
| 72.02 | vless | 283.5 | 657.9 | 21.21 | 0.0 | 10.0 | 9.69 | 17.06 | Au1rxx-base64 | 69.48.201.136 |
| 71.89 | vless | 381.4 | 930.7 | 18.95 | 0.0 | 8.93 | 9.69 | 17.06 | Au1rxx-base64 | 159.89.87.21 |
| 71.51 | shadowsocks | 356.5 | 866.1 | 19.52 | 0.0 | 10.0 | 13.56 | 17.06 | Au1rxx-base64 | 198.98.53.130 |
| 70.93 | shadowsocks | 328.4 | 649.6 | 20.18 | 0.0 | 9.06 | 13.56 | 17.06 | Au1rxx-base64 | 149.22.95.183 |
| 70.71 | vless | 294.7 | 665.6 | 20.96 | 0.0 | 6.1 | 9.69 | 17.06 | Au1rxx-base64 | freeus.aiage.work |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.88 | 0.802 | 555 | 1991 | prefer |
| ermaozi | 0.728 | 0.711 | 38 | 693 | prefer |
| Surfboard-tg-mixed | 0.688 | 0.611 | 72 | 7135 | observe |
| ermaozi-get_subscribe | 0.381 | 1.0 | 3 | 574 | observe |
| mheidari-all | 0.295 | 0.208 | 77 | 23985 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1991 | observe |
| Epodonios-all | 0.255 | None | 0 | 7647 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9903 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5628 | observe |
| barry-far-vless | 0.255 | None | 0 | 5878 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4235 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 70 |
| speed | TimeoutError | - | 43 |
| speed | ClientOSError | - | 31 |
| geo | ClientOSError | - | 27 |
| 204 | ProxyError | - | 17 |
| 204 | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 10 |
| cn-block | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
