# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 17:04:12 |
| 运行耗时 | 641.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98394 |
| 去重后节点 | 27311 |
| TCP 可达 | 3000 |
| 真实可用 | 315 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27311 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 47.6 |
| probe | 239.9 |
| real_test | 245.0 |
| generate | 99.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58412 |
| vmess | 16290 |
| shadowsocks | 11771 |
| trojan | 9942 |
| hysteria2 | 1289 |
| http | 410 |
| shadowsocksr | 166 |
| socks | 65 |
| anytls | 25 |
| hysteria | 18 |
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
| 79.47 | vless | 278.0 | 704.2 | 21.34 | 0.0 | 10.0 | 10.47 | 17.66 | Au1rxx-base64 | 167.17.69.171 |
| 77.94 | hysteria2 | 429.0 | 1232.7 | 17.85 | 0.0 | 10.0 | 13.93 | 17.66 | Au1rxx-base64 | 129.213.91.185 |
| 77.84 | shadowsocks | 262.4 | 710.2 | 21.7 | 0.0 | 10.0 | 12.48 | 17.66 | Au1rxx-base64 | 37.19.198.243 |
| 77.78 | shadowsocks | 265.2 | 715.5 | 21.64 | 0.0 | 10.0 | 12.48 | 17.66 | Au1rxx-base64 | 37.19.198.236 |
| 77.71 | shadowsocks | 268.1 | 718.1 | 21.57 | 0.0 | 10.0 | 12.48 | 17.66 | Au1rxx-base64 | 37.19.198.160 |
| 77.67 | vless | 280.9 | 653.6 | 21.28 | 0.0 | 10.0 | 10.47 | 16.38 | mheidari-all | 195.211.98.43 |
| 77.23 | vless | 375.0 | 987.5 | 19.1 | 0.0 | 10.0 | 10.47 | 17.66 | Au1rxx-base64 | 185.95.231.156 |
| 77.21 | vless | 261.7 | 716.6 | 21.72 | 0.0 | 10.0 | 10.47 | 17.66 | Au1rxx-base64 | 136.107.170.196 |
| 77.16 | vless | 334.7 | 906.4 | 20.03 | 0.0 | 10.0 | 10.47 | 17.66 | Au1rxx-base64 | 137.184.218.169 |
| 76.07 | shadowsocks | 265.4 | 670.5 | 21.63 | 0.0 | 10.0 | 12.48 | 17.66 | Au1rxx-base64 | 140.82.63.79 |
| 75.92 | vless | 431.5 | 962.4 | 17.79 | 0.0 | 10.0 | 10.47 | 17.66 | Au1rxx-base64 | 169.40.42.224 |
| 75.7 | vless | 378.4 | 688.3 | 19.02 | 0.0 | 10.0 | 10.47 | 17.66 | Au1rxx-base64 | 169.40.42.52 |
| 75.31 | shadowsocks | 282.7 | 642.0 | 21.23 | 0.0 | 10.0 | 12.48 | 17.66 | Au1rxx-base64 | 156.146.38.169 |
| 75.2 | vless | 268.1 | 716.5 | 21.57 | 0.0 | 10.0 | 10.47 | 17.66 | Au1rxx-base64 | 104.243.33.154 |
| 74.68 | shadowsocks | 282.2 | 647.8 | 21.24 | 0.0 | 10.0 | 12.48 | 17.66 | Au1rxx-base64 | 156.146.38.168 |
| 74.49 | shadowsocks | 299.1 | 748.5 | 20.85 | 0.0 | 10.0 | 12.48 | 17.66 | Au1rxx-base64 | 64.74.163.67 |
| 74.12 | vless | 293.4 | 768.5 | 20.99 | 0.0 | 10.0 | 10.47 | 17.66 | Au1rxx-base64 | 195.123.235.183 |
| 73.75 | shadowsocks | 362.4 | 952.4 | 19.39 | 0.0 | 10.0 | 12.48 | 16.38 | mheidari-all | 64.74.163.69 |
| 72.8 | shadowsocks | 282.2 | 659.8 | 21.25 | 0.0 | 10.0 | 12.48 | 16.38 | mheidari-all | 156.146.38.170 |
| 72.75 | vless | 397.2 | 940.3 | 18.58 | 0.0 | 10.0 | 10.47 | 17.66 | Au1rxx-base64 | 209.200.246.148 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.894 | 0.825 | 292 | 1780 | prefer |
| mheidari-all | 0.863 | 0.791 | 67 | 23968 | prefer |
| zhangkai | 0.827 | 1.0 | 16 | 144 | prefer |
| Surfboard-tg-mixed | 0.361 | 0.4 | 10 | 7210 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7543 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9997 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5726 | observe |
| barry-far-vless | 0.255 | None | 0 | 5831 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1780 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyError | - | 12 |
| 204 | TimeoutError | - | 11 |
| speed | ClientOSError | - | 11 |
| geo | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 8 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 4 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
