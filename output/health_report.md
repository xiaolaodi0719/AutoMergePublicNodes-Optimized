# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-02 03:57:43 |
| 运行耗时 | 383.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82051 |
| 去重后节点 | 23604 |
| TCP 可达 | 3000 |
| 真实可用 | 759 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23604 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.6 |
| tcp | 39.7 |
| probe | 88.6 |
| real_test | 205.1 |
| generate | 41.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51178 |
| vmess | 11353 |
| shadowsocks | 9914 |
| trojan | 7698 |
| hysteria2 | 1536 |
| http | 143 |
| shadowsocksr | 130 |
| socks | 81 |
| tuic | 11 |
| hysteria | 7 |

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
| 82.08 | vless | 237.7 | 522.9 | 22.28 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 64.23.229.123 |
| 81.39 | shadowsocks | 240.5 | 614.3 | 22.21 | 0.0 | 10.0 | 13.86 | 19.32 | Au1rxx-base64 | 156.146.38.168 |
| 81.34 | shadowsocks | 242.7 | 616.4 | 22.16 | 0.0 | 10.0 | 13.86 | 19.32 | Au1rxx-base64 | 156.146.38.169 |
| 81.32 | hysteria2 | 356.3 | 924.0 | 19.53 | 0.0 | 10.0 | 13.57 | 19.32 | Au1rxx-base64 | 66.94.121.46 |
| 81.29 | vless | 356.2 | 498.5 | 19.53 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 38.180.242.205 |
| 81.13 | shadowsocks | 251.6 | 613.1 | 21.95 | 0.0 | 10.0 | 13.86 | 19.32 | Au1rxx-base64 | 156.146.38.170 |
| 81.11 | shadowsocks | 252.4 | 612.8 | 21.93 | 0.0 | 10.0 | 13.86 | 19.32 | Au1rxx-base64 | 156.146.38.167 |
| 80.12 | vless | 266.5 | 574.8 | 21.61 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 172.233.156.123 |
| 79.81 | trojan | 279.8 | 697.2 | 21.3 | 0.0 | 10.0 | 12.19 | 19.32 | Au1rxx-base64 | 64.94.95.117 |
| 79.76 | vless | 282.6 | 593.8 | 21.24 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 172.233.156.118 |
| 79.69 | vless | 270.4 | 568.0 | 21.52 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 172.239.67.156 |
| 79.53 | vless | 342.8 | 827.0 | 19.84 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 15.204.97.197 |
| 79.45 | vless | 286.6 | 590.8 | 21.14 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 172.239.67.231 |
| 79.35 | vless | 267.6 | 555.2 | 21.58 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 172.235.43.210 |
| 79.16 | vless | 280.9 | 570.5 | 21.28 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 74.207.245.124 |
| 79.05 | vless | 269.4 | 571.3 | 21.54 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 172.233.139.46 |
| 78.97 | vless | 274.4 | 578.9 | 21.43 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 172.236.252.35 |
| 78.95 | vless | 286.4 | 581.9 | 21.15 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 45.33.62.166 |
| 78.79 | vless | 286.8 | 575.6 | 21.14 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 173.255.242.235 |
| 78.78 | vless | 283.1 | 569.0 | 21.22 | 0.0 | 10.0 | 12.44 | 19.32 | Au1rxx-base64 | 192.155.87.188 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.97 | 0.902 | 429 | 1736 | prefer |
| Surfboard-tg-mixed | 0.935 | 0.865 | 74 | 6990 | prefer |
| zhangkai | 0.922 | 0.955 | 22 | 144 | prefer |
| mheidari-all | 0.742 | 0.664 | 238 | 15712 | prefer |
| DeltaKronecker-all | 0.364 | 0.284 | 455 | 7294 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4708 | observe |
| Epodonios-all | 0.255 | None | 0 | 7407 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7631 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5850 | observe |
| barry-far-vless | 0.255 | None | 0 | 6027 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4159 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1736 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 208 |
| geo | ClientOSError | - | 72 |
| speed | ClientOSError | - | 69 |
| speed | TimeoutError | - | 58 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
