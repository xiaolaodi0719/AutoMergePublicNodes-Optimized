# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-30 08:39:55 |
| 运行耗时 | 271.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78173 |
| 去重后节点 | 22773 |
| TCP 可达 | 3000 |
| 真实可用 | 541 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22773 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.3 |
| tcp | 31.6 |
| probe | 57.8 |
| real_test | 130.9 |
| generate | 45.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45723 |
| vmess | 11317 |
| shadowsocks | 10454 |
| trojan | 9828 |
| hysteria2 | 535 |
| http | 121 |
| shadowsocksr | 75 |
| socks | 61 |
| anytls | 26 |
| tuic | 19 |
| hysteria | 14 |

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
| 83.5 | hysteria2 | 236.2 | 638.1 | 22.31 | 0.0 | 10.0 | 13.33 | 18.96 | Au1rxx-base64 | 159.223.157.129 |
| 81.04 | shadowsocks | 226.3 | 597.5 | 22.54 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 198.98.53.130 |
| 80.84 | shadowsocks | 234.9 | 630.8 | 22.34 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 37.19.198.243 |
| 80.71 | shadowsocks | 240.4 | 650.3 | 22.21 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 37.19.198.160 |
| 80.67 | shadowsocks | 242.2 | 652.1 | 22.17 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 37.19.198.244 |
| 80.49 | shadowsocks | 249.8 | 669.3 | 21.99 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 37.19.198.236 |
| 79.66 | shadowsocks | 264.3 | 693.4 | 21.66 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 68.168.222.210 |
| 78.6 | shadowsocks | 310.1 | 826.5 | 20.6 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 185.247.68.94 |
| 78.59 | http | 248.7 | 639.8 | 22.02 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.50 |
| 78.58 | http | 249.1 | 647.0 | 22.01 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.5 |
| 78.57 | http | 249.7 | 645.2 | 22.0 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.7 |
| 78.53 | http | 251.3 | 653.2 | 21.96 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.21 |
| 78.51 | shadowsocks | 313.9 | 834.2 | 20.51 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 185.232.22.28 |
| 78.43 | http | 255.4 | 658.9 | 21.86 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.25 |
| 78.31 | http | 260.9 | 682.6 | 21.74 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.23 |
| 77.65 | shadowsocks | 351.1 | 950.7 | 19.65 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 146.70.34.226 |
| 77.31 | shadowsocks | 346.0 | 872.8 | 19.77 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 185.196.61.82 |
| 77.08 | http | 313.9 | 829.0 | 20.51 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.20 |
| 76.86 | shadowsocks | 286.1 | 659.1 | 21.16 | 0.0 | 10.0 | 13.54 | 18.96 | Au1rxx-base64 | 156.146.38.168 |
| 76.78 | http | 327.1 | 884.9 | 20.21 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.8 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.998 | 1.0 | 118 | 157 | prefer |
| Au1rxx-base64 | 0.892 | 0.847 | 261 | 1201 | prefer |
| Surfboard-tg-mixed | 0.667 | 0.588 | 165 | 5473 | observe |
| mheidari-all | 0.543 | 0.615 | 13 | 16105 | observe |
| DeltaKronecker-all | 0.446 | 0.365 | 260 | 5759 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6219 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6833 | observe |
| barry-far-vless | 0.255 | None | 0 | 4657 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5029 | observe |
| Au1rxx-clash | 0.223 | None | 0 | 1201 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 126 |
| geo | ClientOSError | - | 38 |
| cn-block | TimeoutError | - | 28 |
| speed | ClientOSError | - | 24 |
| speed | TimeoutError | - | 23 |
| 204 | TimeoutError | - | 22 |
| 204 | ProxyError | - | 10 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
