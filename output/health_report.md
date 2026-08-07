# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-07 00:10:38 |
| 运行耗时 | 249.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 88824 |
| 去重后节点 | 24624 |
| TCP 可达 | 3000 |
| 真实可用 | 464 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24624 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 36.6 |
| probe | 54.0 |
| real_test | 118.4 |
| generate | 33.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51652 |
| vmess | 13326 |
| trojan | 11852 |
| shadowsocks | 10225 |
| hysteria2 | 1478 |
| socks | 129 |
| shadowsocksr | 72 |
| anytls | 30 |
| http | 25 |
| hysteria | 21 |
| tuic | 14 |

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
| 84.12 | hysteria2 | 237.1 | 633.4 | 22.29 | 0.0 | 10.0 | 12.95 | 19.98 | Au1rxx-base64 | 159.223.157.129 |
| 83.37 | trojan | 260.1 | 709.8 | 21.76 | 0.0 | 10.0 | 14.63 | 19.98 | Au1rxx-base64 | 153.75.250.171 |
| 82.97 | hysteria2 | 291.0 | 804.9 | 21.04 | 0.0 | 10.0 | 12.95 | 19.98 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 82.92 | hysteria2 | 293.3 | 811.0 | 20.99 | 0.0 | 10.0 | 12.95 | 19.98 | Au1rxx-base64 | 138.124.68.188 |
| 82.11 | shadowsocks | 224.1 | 593.8 | 22.59 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 198.98.53.130 |
| 82.01 | shadowsocks | 228.2 | 627.8 | 22.49 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 37.19.198.160 |
| 81.79 | shadowsocks | 237.8 | 660.3 | 22.27 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 37.19.198.244 |
| 81.64 | shadowsocks | 244.3 | 677.5 | 22.12 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 37.19.198.236 |
| 78.27 | shadowsocks | 286.6 | 648.8 | 21.14 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 156.146.38.168 |
| 77.97 | trojan | 302.1 | 642.3 | 20.78 | 0.0 | 10.0 | 14.63 | 19.98 | Au1rxx-base64 | 163.245.196.68 |
| 77.89 | shadowsocks | 384.6 | 1072.5 | 18.87 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 68.168.222.210 |
| 77.82 | shadowsocks | 286.2 | 648.5 | 21.15 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 156.146.38.169 |
| 76.88 | shadowsocks | 282.3 | 646.1 | 21.24 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 156.146.38.170 |
| 76.74 | shadowsocks | 240.3 | 660.8 | 22.22 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 37.19.198.243 |
| 76.1 | hysteria2 | 349.1 | 678.4 | 19.7 | 0.0 | 10.0 | 12.95 | 19.98 | Au1rxx-base64 | 62.210.124.146 |
| 76.02 | trojan | 418.2 | 1009.9 | 18.1 | 0.0 | 10.0 | 14.63 | 19.98 | Au1rxx-base64 | 64.94.95.115 |
| 75.58 | trojan | 418.5 | 1010.3 | 18.09 | 0.0 | 10.0 | 14.63 | 19.98 | Au1rxx-base64 | 64.94.95.118 |
| 75.5 | trojan | 417.2 | 995.6 | 18.12 | 0.0 | 10.0 | 14.63 | 19.98 | Au1rxx-base64 | 64.94.95.117 |
| 75.14 | shadowsocks | 287.8 | 782.7 | 21.12 | 0.0 | 10.0 | 13.54 | 19.98 | Au1rxx-base64 | 38.180.135.39 |
| 74.93 | trojan | 458.3 | 1132.6 | 17.17 | 0.0 | 10.0 | 14.63 | 19.98 | Au1rxx-base64 | 64.94.95.114 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | 0.937 | 331 | 1327 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.563 | 0.482 | 199 | 5904 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 5184 | observe |
| DeltaKronecker-all | 0.334 | 0.246 | 65 | 5897 | observe |
| mheidari-all | 0.312 | 0.225 | 80 | 20787 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5219 | observe |
| Epodonios-all | 0.255 | None | 0 | 6481 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7217 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4729 | observe |
| barry-far-vless | 0.255 | None | 0 | 5041 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5225 | observe |
| Au1rxx-clash | 0.228 | None | 0 | 1327 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 108 |
| geo | ClientOSError | - | 36 |
| speed | TimeoutError | - | 27 |
| speed | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 8 |
| 204 | ProxyError | - | 7 |
| cn-block | ProxyError | - | 6 |
| geo | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
