# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-17 07:10:52 |
| 运行耗时 | 401.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 82922 |
| 去重后节点 | 23092 |
| TCP 可达 | 3000 |
| 真实可用 | 1377 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23092 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 0.8 |
| tcp | 34.2 |
| probe | 74.9 |
| real_test | 241.4 |
| generate | 43.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45610 |
| trojan | 15281 |
| vmess | 11027 |
| shadowsocks | 9578 |
| hysteria2 | 1080 |
| http | 160 |
| socks | 87 |
| shadowsocksr | 76 |
| tuic | 10 |
| hysteria | 7 |
| anytls | 6 |

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
| 81.96 | hysteria2 | 285.9 | 707.8 | 21.16 | 0.0 | 10.0 | 11.9 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 81.61 | shadowsocks | 256.2 | 621.3 | 21.85 | 0.0 | 10.0 | 14.24 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.51 | shadowsocks | 281.0 | 693.6 | 21.27 | 0.0 | 10.0 | 14.24 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 81.4 | vless | 227.8 | 608.0 | 22.51 | 0.0 | 10.0 | 8.89 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 81.15 | http | 317.8 | 731.2 | 20.42 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 81.02 | shadowsocks | 285.2 | 698.8 | 21.18 | 0.0 | 10.0 | 14.24 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 80.47 | http | 314.7 | 730.6 | 20.49 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 80.45 | http | 310.8 | 711.8 | 20.58 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 80.25 | vless | 277.0 | 760.4 | 21.36 | 0.0 | 10.0 | 8.89 | 20.0 | Au1rxx-base64 | 195.211.99.45 |
| 80.24 | http | 316.8 | 746.4 | 20.44 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 80.03 | http | 315.9 | 727.5 | 20.46 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 80.02 | http | 320.9 | 742.4 | 20.35 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 80.01 | http | 298.5 | 691.3 | 20.87 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 79.96 | http | 290.1 | 666.9 | 21.06 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 79.95 | http | 313.0 | 733.8 | 20.53 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 79.93 | http | 301.7 | 697.6 | 20.79 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 79.9 | http | 314.9 | 736.3 | 20.49 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 79.78 | http | 310.0 | 705.1 | 20.6 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 79.6 | http | 305.5 | 712.1 | 20.71 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 79.59 | http | 313.6 | 720.0 | 20.52 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.952 | 876 | 1991 | prefer |
| mheidari-all | 1.0 | 0.947 | 265 | 17400 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.792 | 0.714 | 217 | 5925 | prefer |
| nscl5-all | 0.335 | 1.0 | 1 | 3043 | observe |
| DeltaKronecker-all | 0.306 | 0.207 | 29 | 6368 | observe |
| ninja-vless | 0.279 | 0.5 | 2 | 1791 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 164 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5085 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1991 | observe |
| Epodonios-all | 0.255 | None | 0 | 6602 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7808 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4592 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 37 |
| cn-block | TimeoutError | - | 21 |
| speed | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 16 |
| 204 | ProxyError | - | 14 |
| geo | ClientOSError | - | 13 |
| speed | ClientOSError | - | 11 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
