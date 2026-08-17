# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-17 12:59:30 |
| 运行耗时 | 401.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83030 |
| 去重后节点 | 23200 |
| TCP 可达 | 3000 |
| 真实可用 | 1260 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23200 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.0 |
| tcp | 35.0 |
| probe | 83.5 |
| real_test | 237.4 |
| generate | 38.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45326 |
| trojan | 15199 |
| vmess | 11071 |
| shadowsocks | 9744 |
| hysteria2 | 1214 |
| socks | 192 |
| http | 190 |
| shadowsocksr | 73 |
| tuic | 10 |
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
| 82.88 | hysteria2 | 293.5 | 735.2 | 20.98 | 0.0 | 10.0 | 13.93 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 82.32 | vless | 276.4 | 644.6 | 21.38 | 0.0 | 10.0 | 10.94 | 20.0 | Au1rxx-base64 | 198.251.78.29 |
| 81.71 | shadowsocks | 231.1 | 593.2 | 22.43 | 0.0 | 10.0 | 13.28 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.45 | shadowsocks | 242.4 | 615.8 | 22.17 | 0.0 | 10.0 | 13.28 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 80.88 | vless | 290.4 | 645.5 | 21.05 | 0.0 | 10.0 | 10.94 | 20.0 | Au1rxx-base64 | 195.211.99.45 |
| 80.46 | vless | 290.0 | 644.6 | 21.06 | 0.0 | 10.0 | 10.94 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 80.34 | shadowsocks | 290.2 | 749.7 | 21.06 | 0.0 | 10.0 | 13.28 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 79.38 | http | 330.8 | 713.7 | 20.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 78.93 | http | 324.5 | 725.7 | 20.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 78.83 | http | 337.2 | 760.2 | 19.97 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 78.78 | http | 314.9 | 697.0 | 20.49 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 78.77 | http | 325.6 | 726.1 | 20.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 78.76 | shadowsocks | 298.8 | 716.7 | 20.86 | 0.0 | 10.0 | 13.28 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 78.72 | http | 287.5 | 584.1 | 21.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 78.72 | http | 332.9 | 747.8 | 20.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 78.71 | http | 285.6 | 568.8 | 21.17 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 78.68 | http | 289.8 | 578.5 | 21.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 78.66 | http | 292.7 | 596.1 | 21.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 78.66 | vless | 319.5 | 733.3 | 20.38 | 0.0 | 10.0 | 10.94 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 78.57 | http | 334.0 | 729.4 | 20.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.942 | 883 | 1983 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.948 | 0.871 | 279 | 17057 | prefer |
| Surfboard-tg-mixed | 0.874 | 0.803 | 66 | 6086 | prefer |
| DeltaKronecker-all | 0.337 | 0.308 | 13 | 6368 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 194 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5085 | observe |
| Epodonios-all | 0.255 | None | 0 | 6645 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3989 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7827 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4669 | observe |
| barry-far-vless | 0.255 | None | 0 | 4992 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4046 | observe |
| nscl5-all | 0.255 | None | 0 | 3043 | observe |
| Au1rxx-clash | 0.254 | None | 0 | 1983 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 21 |
| speed | TimeoutError | - | 16 |
| geo | TimeoutError | - | 13 |
| geo | ClientOSError | - | 10 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
