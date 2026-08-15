# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-15 12:52:06 |
| 运行耗时 | 339.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 77456 |
| 去重后节点 | 22401 |
| TCP 可达 | 3000 |
| 真实可用 | 1030 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22401 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.1 |
| geo | 0.6 |
| tcp | 33.8 |
| probe | 68.4 |
| real_test | 187.5 |
| generate | 34.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42725 |
| trojan | 12248 |
| vmess | 10507 |
| shadowsocks | 10221 |
| hysteria2 | 1403 |
| http | 188 |
| socks | 75 |
| shadowsocksr | 74 |
| tuic | 8 |
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
| 83.8 | hysteria2 | 276.4 | 722.2 | 21.38 | 0.0 | 10.0 | 13.42 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.68 | hysteria2 | 277.2 | 688.9 | 21.36 | 0.0 | 10.0 | 13.42 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 82.75 | http | 297.4 | 722.6 | 20.89 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 82.75 | http | 297.7 | 705.9 | 20.89 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 82.74 | http | 298.1 | 704.1 | 20.88 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 82.45 | http | 286.5 | 681.7 | 21.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 82.29 | http | 282.0 | 669.9 | 21.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 82.1 | http | 297.5 | 705.9 | 20.89 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 82.03 | http | 295.7 | 718.5 | 20.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 81.84 | http | 284.8 | 687.0 | 21.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 81.49 | http | 312.5 | 763.8 | 20.55 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 81.4 | shadowsocks | 278.6 | 703.5 | 21.33 | 0.0 | 10.0 | 14.07 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 81.36 | http | 313.8 | 751.1 | 20.51 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 81.31 | http | 299.3 | 722.5 | 20.85 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 81.26 | http | 291.9 | 696.9 | 21.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 81.17 | http | 307.4 | 745.7 | 20.66 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 80.68 | shadowsocks | 273.7 | 692.5 | 21.44 | 0.0 | 10.0 | 14.07 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 80.65 | http | 331.8 | 621.5 | 20.1 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 80.56 | shadowsocks | 271.7 | 675.6 | 21.49 | 0.0 | 10.0 | 14.07 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 79.67 | http | 349.9 | 890.3 | 19.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.954 | 738 | 1659 | prefer |
| mheidari-all | 1.0 | 0.968 | 93 | 15977 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.89 | 0.821 | 56 | 5656 | prefer |
| DeltaKronecker-all | 0.778 | 0.702 | 84 | 5773 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 2081 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 160 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5113 | observe |
| Epodonios-all | 0.255 | None | 0 | 6303 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7258 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4372 | observe |
| barry-far-vless | 0.255 | None | 0 | 4711 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3935 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 13 |
| geo | ClientOSError | - | 12 |
| geo | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 6 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
