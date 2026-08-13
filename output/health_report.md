# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-13 02:27:11 |
| 运行耗时 | 291.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79753 |
| 去重后节点 | 22382 |
| TCP 可达 | 3000 |
| 真实可用 | 673 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22382 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.4 |
| tcp | 32.6 |
| probe | 55.6 |
| real_test | 157.4 |
| generate | 37.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45221 |
| vmess | 13439 |
| trojan | 9819 |
| shadowsocks | 9741 |
| hysteria2 | 1201 |
| http | 160 |
| socks | 77 |
| shadowsocksr | 74 |
| tuic | 11 |
| hysteria | 7 |
| anytls | 3 |

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
| 84.14 | http | 237.6 | 637.0 | 22.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 84.07 | http | 240.6 | 644.8 | 22.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 84.06 | http | 241.1 | 640.4 | 22.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 84.05 | http | 241.5 | 650.4 | 22.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 84.05 | http | 241.5 | 647.5 | 22.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 84.02 | http | 242.6 | 643.5 | 22.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.99 | http | 244.0 | 650.4 | 22.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 83.93 | http | 246.4 | 659.3 | 22.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.91 | http | 247.3 | 656.3 | 22.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 83.91 | http | 247.6 | 656.3 | 22.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 83.9 | http | 247.8 | 663.3 | 22.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 83.87 | http | 249.0 | 667.4 | 22.01 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 83.83 | http | 251.0 | 678.5 | 21.97 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.72 | http | 255.8 | 692.7 | 21.86 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.7 | http | 256.5 | 693.6 | 21.84 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 82.84 | hysteria2 | 235.8 | 649.2 | 22.32 | 0.0 | 10.0 | 12.86 | 18.76 | Au1rxx-base64 | 159.223.157.129 |
| 82.8 | http | 295.6 | 814.3 | 20.94 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 82.64 | hysteria2 | 248.6 | 672.0 | 22.02 | 0.0 | 10.0 | 12.86 | 18.76 | Au1rxx-base64 | 138.124.68.188 |
| 82.62 | http | 303.1 | 830.4 | 20.76 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 82.59 | http | 304.5 | 837.3 | 20.73 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.947 | 0.889 | 406 | 1489 | prefer |
| Surfboard-tg-mixed | 0.717 | 0.639 | 155 | 5894 | prefer |
| mheidari-all | 0.501 | 0.42 | 162 | 16809 | observe |
| DeltaKronecker-all | 0.33 | 0.243 | 70 | 4975 | observe |
| Epodonios-all | 0.255 | None | 0 | 6571 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7660 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4734 | observe |
| barry-far-vless | 0.255 | None | 0 | 5066 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5209 | observe |
| nscl5-all | 0.241 | None | 0 | 1654 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1489 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 98 |
| speed | TimeoutError | - | 56 |
| geo | ClientOSError | - | 28 |
| speed | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 11 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
