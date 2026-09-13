# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 16:07:00 |
| 运行耗时 | 650.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 95131 |
| 去重后节点 | 25342 |
| TCP 可达 | 3000 |
| 真实可用 | 419 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25342 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.4 |
| geo | 1.4 |
| tcp | 42.3 |
| probe | 276.6 |
| real_test | 243.8 |
| generate | 78.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58652 |
| vmess | 13652 |
| shadowsocks | 10958 |
| trojan | 8804 |
| hysteria2 | 2252 |
| http | 584 |
| shadowsocksr | 126 |
| socks | 60 |
| hysteria | 17 |
| anytls | 14 |
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
| 81.88 | hysteria2 | 210.4 | 513.4 | 22.91 | 0.0 | 9.15 | 13.12 | 17.7 | Au1rxx-base64 | 66.94.121.46 |
| 78.54 | hysteria2 | 265.1 | 744.2 | 21.64 | 0.0 | 9.08 | 13.12 | 17.7 | Au1rxx-base64 | 107.175.219.48 |
| 78.38 | shadowsocks | 253.4 | 600.0 | 21.91 | 0.0 | 10.0 | 13.01 | 17.7 | Au1rxx-base64 | 149.22.95.183 |
| 78.28 | vless | 289.2 | 739.3 | 21.08 | 0.0 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 172.233.139.46 |
| 78.11 | vless | 296.7 | 693.0 | 20.91 | 0.0 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 150.241.102.181 |
| 75.53 | shadowsocks | 243.2 | 610.5 | 22.15 | 0.0 | 9.17 | 13.01 | 17.7 | Au1rxx-base64 | 108.181.118.10 |
| 75.12 | shadowsocks | 272.6 | 722.4 | 21.47 | 0.0 | 10.0 | 13.01 | 15.14 | Surfboard-tg-mixed | 5.78.51.123 |
| 74.65 | vless | 286.4 | 557.2 | 21.15 | 0.0 | 9.14 | 9.5 | 17.7 | Au1rxx-base64 | 144.172.104.26 |
| 74.21 | shadowsocks | 290.6 | 642.7 | 21.05 | 0.0 | 10.0 | 13.01 | 17.7 | Au1rxx-base64 | 156.146.38.170 |
| 73.83 | vless | 200.8 | 494.5 | 23.13 | 0.0 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 104.18.34.14 |
| 73.55 | shadowsocks | 289.7 | 642.5 | 21.07 | 0.0 | 9.17 | 13.01 | 17.7 | Au1rxx-base64 | 156.146.38.169 |
| 73.2 | vless | 271.2 | 465.0 | 21.5 | 0.0 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 162.159.39.218 |
| 72.84 | vless | 348.3 | 759.5 | 19.72 | 0.0 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 79.141.172.154 |
| 72.72 | hysteria2 | 372.1 | 782.6 | 19.16 | 0.0 | 10.0 | 13.12 | 17.7 | Au1rxx-base64 | 159.223.157.129 |
| 72.6 | vless | 293.3 | 395.1 | 20.99 | 0.18 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 188.114.97.6 |
| 72.55 | vless | 296.0 | 730.5 | 20.93 | 0.0 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 45.149.172.80 |
| 72.35 | vless | 318.7 | 491.9 | 20.4 | 0.0 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 162.159.0.53 |
| 71.69 | vless | 444.3 | 1013.3 | 17.49 | 0.0 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 64.49.38.3 |
| 71.63 | shadowsocks | 299.4 | 663.7 | 20.85 | 0.0 | 10.0 | 13.01 | 15.14 | Surfboard-tg-mixed | 156.146.38.167 |
| 70.5 | vless | 391.7 | 740.3 | 18.71 | 0.0 | 10.0 | 9.5 | 17.7 | Au1rxx-base64 | 198.251.78.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.911 | 0.847 | 300 | 1678 | prefer |
| Surfboard-tg-mixed | 0.8 | 0.724 | 98 | 7605 | prefer |
| ermaozi | 0.682 | 0.676 | 34 | 382 | observe |
| mheidari-all | 0.53 | 0.449 | 147 | 20611 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5301 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7899 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9265 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6236 | observe |
| barry-far-vless | 0.255 | None | 0 | 6452 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4221 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1678 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 51 |
| cn-block | ClientOSError | - | 39 |
| speed | ClientOSError | - | 28 |
| 204 | ProxyError | - | 18 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| speed | TimeoutError | - | 5 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
