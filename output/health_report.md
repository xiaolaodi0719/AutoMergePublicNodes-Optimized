# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-16 18:40:54 |
| 运行耗时 | 374.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 79898 |
| 去重后节点 | 21944 |
| TCP 可达 | 3000 |
| 真实可用 | 1032 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21944 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 0.6 |
| tcp | 33.2 |
| probe | 69.5 |
| real_test | 231.4 |
| generate | 34.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43751 |
| trojan | 14315 |
| vmess | 10867 |
| shadowsocks | 9553 |
| hysteria2 | 1085 |
| http | 159 |
| socks | 77 |
| shadowsocksr | 72 |
| tuic | 10 |
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
| 84.84 | hysteria2 | 262.8 | 720.9 | 21.69 | 0.0 | 10.0 | 14.25 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 84.02 | hysteria2 | 287.4 | 704.3 | 21.13 | 0.0 | 10.0 | 14.25 | 19.64 | mheidari-all | 138.124.68.188 |
| 83.98 | http | 244.6 | 651.5 | 22.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 83.94 | http | 246.3 | 661.6 | 22.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.87 | http | 249.1 | 668.0 | 22.01 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 83.87 | http | 249.3 | 673.3 | 22.01 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 83.72 | http | 255.5 | 668.4 | 21.86 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 83.45 | http | 267.1 | 722.2 | 21.59 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 82.57 | vless | 247.7 | 675.5 | 22.04 | 0.0 | 9.54 | 10.99 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 82.48 | shadowsocks | 228.1 | 623.0 | 22.5 | 0.0 | 10.0 | 13.98 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 82.44 | vless | 253.5 | 671.0 | 21.91 | 0.0 | 9.54 | 10.99 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 82.13 | http | 324.2 | 820.8 | 20.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 82.12 | shadowsocks | 228.0 | 619.1 | 22.5 | 0.0 | 10.0 | 13.98 | 19.64 | mheidari-all | 37.19.198.243 |
| 82.12 | vless | 266.8 | 643.1 | 21.6 | 0.0 | 9.53 | 10.99 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 82.12 | http | 324.8 | 783.1 | 20.26 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 82.1 | http | 325.7 | 821.2 | 20.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 82.02 | http | 329.1 | 823.3 | 20.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 81.95 | http | 332.3 | 837.3 | 20.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 81.93 | http | 333.0 | 829.1 | 20.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 81.79 | http | 338.9 | 849.2 | 19.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.958 | 754 | 1994 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.873 | 0.797 | 138 | 17005 | prefer |
| Surfboard-tg-mixed | 0.809 | 0.734 | 94 | 5798 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 2601 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 174 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1994 | observe |
| Epodonios-all | 0.255 | None | 0 | 6468 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3982 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7449 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4549 | observe |
| barry-far-vless | 0.255 | None | 0 | 4856 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4025 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 17 |
| speed | TimeoutError | - | 16 |
| geo | TimeoutError | - | 13 |
| 204 | ProxyError | - | 9 |
| geo | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
