# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 16:15:25 |
| 运行耗时 | 494.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96750 |
| 去重后节点 | 26317 |
| TCP 可达 | 3000 |
| 真实可用 | 367 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26317 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 43.1 |
| probe | 196.4 |
| real_test | 165.7 |
| generate | 80.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58761 |
| vmess | 15337 |
| shadowsocks | 11309 |
| trojan | 8917 |
| hysteria2 | 1515 |
| http | 609 |
| shadowsocksr | 173 |
| socks | 78 |
| anytls | 25 |
| hysteria | 15 |
| tuic | 11 |

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
| 80.02 | vless | 241.4 | 684.1 | 22.19 | 0.0 | 8.81 | 9.94 | 19.08 | Au1rxx-base64 | 79.141.172.154 |
| 79.12 | vless | 279.5 | 627.5 | 21.31 | 0.0 | 8.79 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.173 |
| 78.88 | vless | 288.9 | 648.4 | 21.09 | 0.0 | 8.77 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.35 |
| 78.45 | vless | 307.5 | 795.6 | 20.66 | 0.0 | 8.77 | 9.94 | 19.08 | Au1rxx-base64 | 38.77.133.202 |
| 78.36 | vless | 311.6 | 714.8 | 20.57 | 0.0 | 8.77 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.235 |
| 78.21 | vless | 319.8 | 816.2 | 20.38 | 0.0 | 8.81 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.104 |
| 77.87 | vless | 338.1 | 967.6 | 19.95 | 0.0 | 8.9 | 9.94 | 19.08 | Au1rxx-base64 | 47.253.226.114 |
| 77.51 | vless | 348.2 | 904.2 | 19.72 | 0.0 | 8.77 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.179 |
| 77.16 | vless | 363.9 | 993.8 | 19.36 | 0.0 | 8.78 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.163 |
| 77.12 | shadowsocks | 319.4 | 840.5 | 20.39 | 0.0 | 9.04 | 13.11 | 19.08 | Au1rxx-base64 | 38.180.135.156 |
| 77.04 | vless | 369.1 | 882.7 | 19.23 | 0.0 | 8.79 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.95 |
| 76.98 | vless | 302.9 | 683.7 | 20.77 | 0.0 | 8.71 | 9.94 | 19.08 | Au1rxx-base64 | 198.251.78.29 |
| 76.96 | vless | 373.6 | 902.2 | 19.13 | 0.0 | 8.81 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.202 |
| 76.9 | vless | 385.4 | 939.5 | 18.86 | 0.0 | 9.02 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.231 |
| 76.86 | vless | 378.0 | 922.1 | 19.03 | 0.0 | 8.81 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.225 |
| 76.68 | vless | 284.7 | 716.2 | 21.19 | 0.0 | 8.77 | 9.94 | 19.08 | Au1rxx-base64 | 66.70.179.198 |
| 76.65 | vless | 287.3 | 656.4 | 21.13 | 0.0 | 8.78 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.212 |
| 76.31 | vless | 328.7 | 840.6 | 20.17 | 0.0 | 8.73 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.168 |
| 75.82 | vless | 351.5 | 956.3 | 19.64 | 0.0 | 8.77 | 9.94 | 19.08 | Au1rxx-base64 | 169.40.42.133 |
| 75.72 | vless | 426.1 | 1195.8 | 17.92 | 0.0 | 8.78 | 9.94 | 19.08 | Au1rxx-base64 | 185.95.231.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | 0.87 | 276 | 1642 | prefer |
| Surfboard-tg-mixed | 0.816 | 0.743 | 70 | 7263 | prefer |
| mheidari-all | 0.722 | 0.644 | 104 | 22551 | prefer |
| ermaozi | 0.339 | 0.333 | 18 | 296 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7742 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8947 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5823 | observe |
| barry-far-vless | 0.255 | None | 0 | 6056 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1642 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| ermaozi-get_subscribe | 0.22 | 0.5 | 2 | 302 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 24 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyError | - | 16 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 5 |
| geo | TimeoutError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ClientOSError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
