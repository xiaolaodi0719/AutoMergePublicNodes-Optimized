# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-17 18:53:32 |
| 运行耗时 | 435.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 80814 |
| 去重后节点 | 22843 |
| TCP 可达 | 3000 |
| 真实可用 | 1394 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22843 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 0.9 |
| tcp | 35.1 |
| probe | 79.5 |
| real_test | 288.3 |
| generate | 25.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46734 |
| trojan | 14339 |
| shadowsocks | 9736 |
| vmess | 8327 |
| hysteria2 | 1231 |
| http | 195 |
| socks | 143 |
| shadowsocksr | 80 |
| tuic | 20 |
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
| 83.23 | hysteria2 | 249.4 | 695.4 | 22.01 | 0.0 | 10.0 | 12.22 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 82.74 | http | 298.1 | 819.0 | 20.88 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 82.73 | vless | 246.1 | 665.6 | 22.08 | 0.0 | 10.0 | 10.65 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 82.65 | http | 301.7 | 824.4 | 20.79 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 82.65 | http | 301.7 | 814.1 | 20.79 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 82.56 | http | 305.8 | 821.7 | 20.7 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 82.51 | http | 307.9 | 834.0 | 20.65 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 82.44 | http | 310.8 | 844.6 | 20.58 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 82.37 | http | 313.9 | 847.6 | 20.51 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 82.35 | http | 314.8 | 858.9 | 20.49 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 82.24 | http | 319.5 | 862.2 | 20.38 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 82.23 | http | 319.8 | 863.7 | 20.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 82.22 | http | 320.3 | 867.3 | 20.36 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 82.17 | http | 322.8 | 876.6 | 20.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 82.16 | http | 322.9 | 870.5 | 20.3 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 82.11 | http | 325.4 | 862.1 | 20.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 82.03 | hysteria2 | 251.7 | 675.7 | 21.95 | 0.0 | 10.0 | 12.22 | 18.96 | mheidari-all | 159.223.157.129 |
| 82.01 | http | 329.6 | 886.2 | 20.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 82.0 | http | 330.0 | 895.4 | 20.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 81.99 | http | 330.4 | 882.0 | 20.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 0.942 | 327 | 15619 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Au1rxx-base64 | 0.971 | 0.893 | 962 | 1983 | prefer |
| Surfboard-tg-mixed | 0.93 | 0.856 | 111 | 6228 | prefer |
| DeltaKronecker-all | 0.324 | 0.375 | 8 | 6368 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 192 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5085 | observe |
| Epodonios-all | 0.255 | None | 0 | 6789 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3984 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6707 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4903 | observe |
| barry-far-vless | 0.255 | None | 0 | 5131 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4027 | observe |
| nscl5-all | 0.255 | None | 0 | 3043 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ClientOSError | - | 43 |
| 204 | TimeoutError | - | 33 |
| cn-block | TimeoutError | - | 18 |
| speed | TimeoutError | - | 11 |
| geo | TimeoutError | - | 10 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyError | - | 9 |
| geo | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
