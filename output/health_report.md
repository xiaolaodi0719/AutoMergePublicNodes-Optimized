# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-13 19:13:03 |
| 运行耗时 | 312.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 80094 |
| 去重后节点 | 22489 |
| TCP 可达 | 3000 |
| 真实可用 | 850 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22489 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.1 |
| tcp | 32.9 |
| probe | 63.2 |
| real_test | 177.6 |
| generate | 31.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44900 |
| vmess | 13324 |
| trojan | 10241 |
| shadowsocks | 9967 |
| hysteria2 | 1339 |
| http | 152 |
| socks | 78 |
| shadowsocksr | 76 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 2 |

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
| 84.04 | hysteria2 | 237.7 | 651.2 | 22.28 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 83.99 | http | 244.1 | 648.0 | 22.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 83.89 | http | 248.4 | 660.5 | 22.03 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 83.82 | http | 251.4 | 662.5 | 21.96 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.74 | http | 254.9 | 673.5 | 21.88 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.74 | http | 255.0 | 679.7 | 21.88 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.7 | hysteria2 | 256.5 | 691.0 | 21.84 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.56 | http | 262.6 | 713.6 | 21.7 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 82.81 | http | 295.2 | 798.2 | 20.95 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 82.75 | http | 297.6 | 801.4 | 20.89 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 82.67 | http | 300.9 | 812.8 | 20.81 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 82.66 | http | 301.3 | 813.9 | 20.8 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 82.61 | http | 303.8 | 819.5 | 20.75 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 82.51 | http | 308.0 | 843.6 | 20.65 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 82.41 | http | 312.3 | 857.4 | 20.55 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 82.39 | http | 313.0 | 856.2 | 20.53 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 82.38 | http | 313.5 | 861.1 | 20.52 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 82.35 | http | 315.0 | 843.2 | 20.49 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 82.09 | http | 326.2 | 866.6 | 20.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 82.0 | http | 329.7 | 899.8 | 20.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.998 | 0.933 | 616 | 1639 | prefer |
| mheidari-all | 0.88 | 0.805 | 113 | 16814 | prefer |
| Surfboard-tg-mixed | 0.756 | 0.682 | 66 | 6036 | prefer |
| DeltaKronecker-all | 0.684 | 0.786 | 14 | 4878 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5203 | observe |
| Epodonios-all | 0.255 | None | 0 | 6692 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7502 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4739 | observe |
| barry-far-vless | 0.255 | None | 0 | 5103 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5197 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1639 | observe |
| nscl5-all | 0.241 | None | 0 | 1654 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 16 |
| geo | TimeoutError | - | 14 |
| 204 | ProxyError | - | 9 |
| 204 | ClientOSError | - | 8 |
| geo | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| speed | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
