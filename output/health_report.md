# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-02 13:44:01 |
| 运行耗时 | 319.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78289 |
| 去重后节点 | 22870 |
| TCP 可达 | 3000 |
| 真实可用 | 699 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22870 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.6 |
| tcp | 34.4 |
| probe | 62.8 |
| real_test | 174.2 |
| generate | 39.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46855 |
| vmess | 12698 |
| shadowsocks | 10108 |
| trojan | 7653 |
| hysteria2 | 627 |
| http | 165 |
| shadowsocksr | 77 |
| socks | 64 |
| anytls | 26 |
| hysteria | 12 |
| tuic | 4 |

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
| 79.34 | http | 414.2 | 1084.1 | 18.19 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 156.146.59.25 |
| 79.24 | http | 418.6 | 1099.3 | 18.09 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 156.146.59.8 |
| 79.1 | http | 424.7 | 1115.5 | 17.95 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 156.146.59.20 |
| 78.92 | http | 431.2 | 1119.2 | 17.8 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 156.146.59.23 |
| 78.74 | hysteria2 | 266.3 | 686.8 | 21.61 | 0.0 | 10.0 | 12.39 | 15.74 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 78.7 | hysteria2 | 263.8 | 670.9 | 21.67 | 0.0 | 10.0 | 12.39 | 15.74 | Au1rxx-base64 | 159.223.157.129 |
| 78.7 | hysteria2 | 268.0 | 696.9 | 21.57 | 0.0 | 10.0 | 12.39 | 15.74 | Au1rxx-base64 | 138.124.68.188 |
| 78.5 | http | 421.3 | 1089.6 | 18.03 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 156.146.59.5 |
| 78.33 | http | 428.2 | 1120.5 | 17.86 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 156.146.59.7 |
| 78.18 | http | 429.2 | 1107.4 | 17.84 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 156.146.59.21 |
| 77.41 | vless | 254.3 | 655.7 | 21.89 | 0.0 | 10.0 | 9.78 | 15.74 | Au1rxx-base64 | 216.152.147.28 |
| 76.55 | vless | 291.4 | 697.2 | 21.03 | 0.0 | 10.0 | 9.78 | 15.74 | Au1rxx-base64 | 159.89.87.21 |
| 75.84 | http | 329.3 | 617.9 | 20.16 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 138.199.35.213 |
| 75.82 | http | 328.9 | 621.8 | 20.17 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 138.199.35.218 |
| 75.71 | http | 332.1 | 631.4 | 20.09 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 138.199.35.197 |
| 75.71 | http | 332.4 | 634.1 | 20.08 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 138.199.35.210 |
| 75.71 | http | 332.8 | 625.8 | 20.07 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 138.199.35.195 |
| 75.68 | shadowsocks | 254.5 | 626.7 | 21.89 | 0.0 | 10.0 | 12.1 | 15.74 | Au1rxx-base64 | 156.146.38.167 |
| 75.66 | shadowsocks | 257.2 | 635.6 | 21.82 | 0.0 | 10.0 | 12.1 | 15.74 | Au1rxx-base64 | 156.146.38.169 |
| 75.61 | http | 330.9 | 630.8 | 20.12 | 0.0 | 10.0 | 14.59 | 19.56 | zhangkai | 138.199.35.208 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 143 | 344 | prefer |
| Au1rxx-base64 | 0.787 | 0.721 | 555 | 1667 | prefer |
| Surfboard-tg-mixed | 0.691 | 0.613 | 124 | 5249 | observe |
| DeltaKronecker-all | 0.64 | 0.561 | 132 | 4549 | observe |
| mheidari-all | 0.446 | 0.625 | 8 | 16891 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5486 | observe |
| Epodonios-all | 0.255 | None | 0 | 5857 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6807 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4140 | observe |
| barry-far-vless | 0.255 | None | 0 | 4517 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5071 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1667 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 116 |
| speed | TimeoutError | - | 36 |
| cn-block | TimeoutError | - | 29 |
| 204 | TimeoutError | - | 25 |
| geo | ClientOSError | - | 18 |
| speed | ClientOSError | - | 18 |
| cn-block | ClientOSError | - | 8 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46587: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
