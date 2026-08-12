# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-12 19:10:41 |
| 运行耗时 | 231.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79820 |
| 去重后节点 | 22379 |
| TCP 可达 | 3000 |
| 真实可用 | 584 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22379 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 33.7 |
| probe | 49.0 |
| real_test | 113.5 |
| generate | 28.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45462 |
| vmess | 13287 |
| shadowsocks | 9736 |
| trojan | 9669 |
| hysteria2 | 1344 |
| http | 159 |
| shadowsocksr | 73 |
| socks | 72 |
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
| 83.72 | http | 255.4 | 659.6 | 21.86 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 83.68 | http | 257.3 | 637.6 | 21.82 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 83.49 | http | 265.4 | 686.0 | 21.63 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 83.37 | http | 270.8 | 700.7 | 21.51 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 83.02 | http | 285.7 | 730.4 | 21.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 82.99 | http | 287.3 | 733.0 | 21.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 82.27 | http | 318.2 | 848.8 | 20.41 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 82.07 | http | 326.9 | 860.5 | 20.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 82.03 | http | 328.9 | 888.8 | 20.17 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 81.94 | http | 332.6 | 882.7 | 20.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 81.87 | http | 335.7 | 899.8 | 20.01 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 81.82 | http | 337.9 | 906.9 | 19.96 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 81.69 | http | 343.4 | 904.1 | 19.83 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 81.02 | hysteria2 | 251.4 | 669.8 | 21.96 | 0.0 | 10.0 | 11.84 | 18.22 | Au1rxx-base64 | 138.124.68.188 |
| 80.99 | hysteria2 | 248.4 | 673.4 | 22.03 | 0.0 | 10.0 | 11.84 | 18.22 | Au1rxx-base64 | 159.223.157.129 |
| 80.17 | http | 408.9 | 1109.6 | 18.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 80.15 | http | 410.0 | 1100.2 | 18.29 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 79.93 | http | 419.3 | 1146.0 | 18.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 79.9 | http | 420.8 | 1144.0 | 18.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 79.01 | http | 422.8 | 1142.9 | 17.99 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.938 | 0.872 | 452 | 1703 | prefer |
| Surfboard-tg-mixed | 0.767 | 0.692 | 65 | 5991 | prefer |
| mheidari-all | 0.749 | 0.923 | 13 | 16743 | prefer |
| DeltaKronecker-all | 0.389 | 0.385 | 13 | 4975 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5328 | observe |
| Epodonios-all | 0.255 | None | 0 | 6597 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7349 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4839 | observe |
| barry-far-vless | 0.255 | None | 0 | 5121 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5209 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1703 | observe |
| nscl5-all | 0.234 | None | 0 | 1481 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 14 |
| geo | ClientOSError | - | 12 |
| speed | TimeoutError | - | 11 |
| geo | TimeoutError | - | 11 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyError | - | 7 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
