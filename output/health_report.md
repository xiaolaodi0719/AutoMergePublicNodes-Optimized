# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-17 01:44:09 |
| 运行耗时 | 381.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 80829 |
| 去重后节点 | 22248 |
| TCP 可达 | 3000 |
| 真实可用 | 1313 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22248 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.3 |
| tcp | 33.8 |
| probe | 70.6 |
| real_test | 240.9 |
| generate | 28.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44376 |
| trojan | 14790 |
| vmess | 10738 |
| shadowsocks | 9515 |
| hysteria2 | 1073 |
| http | 159 |
| socks | 84 |
| shadowsocksr | 75 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 4 |

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
| 83.38 | vless | 229.2 | 591.2 | 22.47 | 0.0 | 10.0 | 10.91 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 83.19 | http | 275.1 | 656.0 | 21.41 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 83.07 | http | 283.9 | 691.2 | 21.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 82.98 | http | 278.6 | 669.3 | 21.33 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 82.9 | http | 291.1 | 707.3 | 21.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 82.88 | http | 291.9 | 718.0 | 21.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 82.83 | http | 272.3 | 665.6 | 21.48 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 82.79 | http | 295.6 | 711.5 | 20.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 82.71 | http | 293.7 | 711.8 | 20.98 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 82.6 | http | 304.0 | 748.1 | 20.74 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 82.49 | http | 277.6 | 674.4 | 21.35 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 82.3 | http | 307.1 | 745.4 | 20.67 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 82.28 | http | 293.0 | 715.2 | 20.99 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 82.25 | http | 276.6 | 674.1 | 21.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 81.99 | vless | 288.1 | 694.2 | 21.11 | 0.0 | 10.0 | 10.91 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 81.99 | vless | 289.3 | 710.5 | 21.08 | 0.0 | 10.0 | 10.91 | 20.0 | Au1rxx-base64 | 47.89.186.170 |
| 81.76 | http | 332.8 | 841.2 | 20.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 81.54 | vless | 292.5 | 710.1 | 21.01 | 0.0 | 10.0 | 10.91 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 80.91 | http | 349.5 | 892.2 | 19.69 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 80.72 | vless | 344.2 | 919.0 | 19.81 | 0.0 | 10.0 | 10.91 | 20.0 | Au1rxx-base64 | 216.152.147.28 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.962 | 913 | 1994 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.837 | 0.76 | 150 | 5916 | prefer |
| mheidari-all | 0.671 | 0.592 | 311 | 17074 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 129 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1994 | observe |
| Epodonios-all | 0.255 | None | 0 | 6595 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7537 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4572 | observe |
| barry-far-vless | 0.255 | None | 0 | 4905 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4025 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 103 |
| speed | TimeoutError | - | 44 |
| cn-block | TimeoutError | - | 37 |
| geo | ClientOSError | - | 31 |
| speed | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
