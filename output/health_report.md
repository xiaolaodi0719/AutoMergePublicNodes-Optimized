# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-19 01:41:33 |
| 运行耗时 | 401.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82111 |
| 去重后节点 | 22328 |
| TCP 可达 | 3000 |
| 真实可用 | 1378 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22328 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 0.4 |
| tcp | 34.2 |
| probe | 74.4 |
| real_test | 258.8 |
| generate | 27.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44945 |
| trojan | 17072 |
| shadowsocks | 9903 |
| vmess | 8639 |
| hysteria2 | 1141 |
| http | 179 |
| socks | 117 |
| shadowsocksr | 93 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 7 |

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
| 83.99 | http | 232.2 | 627.2 | 22.4 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.4 |
| 83.98 | http | 232.6 | 623.5 | 22.39 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.27 |
| 83.88 | http | 237.3 | 641.5 | 22.29 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.31 |
| 83.81 | http | 240.1 | 639.4 | 22.22 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.10 |
| 83.79 | http | 240.9 | 643.4 | 22.2 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.5 |
| 83.79 | http | 241.0 | 637.7 | 22.2 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.19 |
| 83.72 | http | 243.9 | 638.7 | 22.13 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.41 |
| 83.64 | http | 247.6 | 671.1 | 22.05 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.34 |
| 83.57 | http | 250.6 | 671.6 | 21.98 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.23 |
| 83.55 | http | 251.3 | 680.3 | 21.96 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.21 |
| 83.52 | http | 252.6 | 685.8 | 21.93 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.25 |
| 83.5 | http | 253.5 | 689.6 | 21.91 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.11 |
| 83.48 | http | 254.2 | 673.9 | 21.89 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.39 |
| 83.45 | http | 255.5 | 680.9 | 21.86 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.9 |
| 83.43 | http | 256.6 | 681.4 | 21.84 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.8 |
| 83.36 | http | 259.5 | 683.8 | 21.77 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.28 |
| 83.34 | http | 260.3 | 703.4 | 21.75 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.33 |
| 82.21 | http | 309.2 | 842.4 | 20.62 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 156.146.59.15 |
| 81.01 | trojan | 243.7 | 611.7 | 22.14 | 0.0 | 10.0 | 14.87 | 20.0 | Au1rxx-base64 | 172.237.131.75 |
| 79.57 | vless | 255.2 | 675.3 | 21.87 | 0.0 | 10.0 | 7.7 | 20.0 | Au1rxx-base64 | 167.17.69.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.99 | 816 | 1745 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.885 | 0.808 | 172 | 6344 | prefer |
| mheidari-all | 0.852 | 0.774 | 371 | 16675 | prefer |
| nscl5-all | 0.519 | 1.0 | 5 | 3330 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5068 | observe |
| Epodonios-all | 0.255 | None | 0 | 6993 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7254 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4847 | observe |
| barry-far-vless | 0.255 | None | 0 | 5142 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4035 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1745 | observe |
| DeltaKronecker-all | 0.24 | 0.152 | 79 | 5725 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 85 |
| speed | TimeoutError | - | 45 |
| geo | ClientOSError | - | 29 |
| speed | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| cn-block | TimeoutError | - | 4 |
| 204 | ProxyError | - | 3 |
| 204 | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
