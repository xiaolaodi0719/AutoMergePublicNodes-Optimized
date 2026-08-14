# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-14 07:44:18 |
| 运行耗时 | 311.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 81257 |
| 去重后节点 | 23189 |
| TCP 可达 | 3000 |
| 真实可用 | 862 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23189 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 35.9 |
| probe | 65.9 |
| real_test | 168.4 |
| generate | 34.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44342 |
| vmess | 13420 |
| trojan | 11669 |
| shadowsocks | 10068 |
| hysteria2 | 1444 |
| http | 149 |
| socks | 79 |
| shadowsocksr | 70 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 1 |

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
| 84.31 | hysteria2 | 288.3 | 726.6 | 21.1 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.9 | trojan | 238.4 | 597.2 | 22.26 | 0.0 | 10.0 | 14.64 | 20.0 | Au1rxx-base64 | 64.94.95.115 |
| 83.7 | trojan | 247.1 | 598.2 | 22.06 | 0.0 | 10.0 | 14.64 | 20.0 | Au1rxx-base64 | 64.94.95.114 |
| 83.51 | trojan | 250.9 | 620.8 | 21.97 | 0.0 | 10.0 | 14.64 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 82.91 | hysteria2 | 301.4 | 714.2 | 20.8 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 82.5 | shadowsocks | 243.6 | 634.3 | 22.14 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 82.47 | shadowsocks | 238.3 | 620.7 | 22.26 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 81.65 | shadowsocks | 258.5 | 593.5 | 21.79 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 81.14 | shadowsocks | 302.4 | 723.6 | 20.78 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 80.46 | shadowsocks | 245.2 | 616.9 | 22.1 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.32 | shadowsocks | 276.6 | 672.3 | 21.37 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 79.7 | http | 322.0 | 749.6 | 20.33 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 79.43 | http | 311.9 | 708.0 | 20.56 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 79.1 | http | 277.3 | 552.8 | 21.36 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 79.09 | http | 323.4 | 714.8 | 20.29 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 78.93 | http | 281.2 | 565.1 | 21.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 78.92 | http | 289.4 | 586.6 | 21.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 78.87 | http | 283.9 | 571.3 | 21.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 78.75 | http | 286.3 | 577.2 | 21.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 78.71 | http | 287.0 | 570.4 | 21.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.935 | 666 | 1671 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.695 | 0.618 | 102 | 5896 | observe |
| mheidari-all | 0.523 | 0.533 | 15 | 16991 | observe |
| DeltaKronecker-all | 0.456 | 0.374 | 107 | 5969 | observe |
| nscl5-all | 0.326 | 1.0 | 1 | 1768 | observe |
| Epodonios-all | 0.255 | None | 0 | 6568 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7698 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4633 | observe |
| barry-far-vless | 0.255 | None | 0 | 4969 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5332 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1671 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 61 |
| geo | ClientOSError | - | 29 |
| speed | ClientOSError | - | 19 |
| speed | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 10 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
