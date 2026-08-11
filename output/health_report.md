# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-11 02:07:26 |
| 运行耗时 | 218.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85365 |
| 去重后节点 | 24751 |
| TCP 可达 | 3000 |
| 真实可用 | 541 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24751 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.2 |
| tcp | 36.6 |
| probe | 47.5 |
| real_test | 100.8 |
| generate | 27.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50214 |
| vmess | 13252 |
| trojan | 10598 |
| shadowsocks | 9737 |
| hysteria2 | 1295 |
| socks | 76 |
| shadowsocksr | 73 |
| http | 72 |
| anytls | 26 |
| hysteria | 13 |
| tuic | 9 |

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
| 84.53 | hysteria2 | 241.9 | 665.1 | 22.18 | 0.0 | 10.0 | 14.21 | 19.14 | Au1rxx-base64 | 138.124.68.188 |
| 84.32 | hysteria2 | 246.6 | 657.2 | 22.07 | 0.0 | 10.0 | 14.21 | 19.14 | Au1rxx-base64 | 159.223.157.129 |
| 83.25 | hysteria2 | 247.4 | 682.9 | 22.05 | 0.0 | 8.85 | 14.21 | 19.14 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.64 | shadowsocks | 222.7 | 603.7 | 22.62 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 198.98.53.130 |
| 81.09 | shadowsocks | 246.7 | 680.7 | 22.07 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 37.19.198.243 |
| 79.94 | shadowsocks | 296.2 | 827.6 | 20.92 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 37.19.198.236 |
| 79.78 | shadowsocks | 303.0 | 845.5 | 20.76 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 37.19.198.244 |
| 78.48 | shadowsocks | 337.7 | 876.0 | 19.96 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 185.196.61.82 |
| 78.07 | shadowsocks | 247.2 | 682.9 | 22.05 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 37.19.198.160 |
| 78.07 | trojan | 296.7 | 640.3 | 20.91 | 0.0 | 10.0 | 14.16 | 19.14 | Au1rxx-base64 | 64.94.95.115 |
| 77.98 | trojan | 295.7 | 640.3 | 20.93 | 0.0 | 10.0 | 14.16 | 19.14 | Au1rxx-base64 | 64.94.95.117 |
| 77.54 | shadowsocks | 284.6 | 657.1 | 21.19 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 156.146.38.169 |
| 77.25 | shadowsocks | 289.2 | 651.2 | 21.08 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 156.146.38.167 |
| 76.75 | shadowsocks | 325.7 | 785.1 | 20.24 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 156.146.38.168 |
| 76.03 | vless | 308.9 | 645.1 | 20.63 | 0.0 | 10.0 | 9.26 | 19.14 | Au1rxx-base64 | 104.17.139.37 |
| 76.0 | hysteria2 | 371.0 | 735.3 | 19.19 | 0.0 | 10.0 | 14.21 | 19.14 | Au1rxx-base64 | 62.210.124.146 |
| 75.87 | shadowsocks | 297.5 | 648.1 | 20.89 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 156.146.38.170 |
| 75.44 | trojan | 376.9 | 876.5 | 19.05 | 0.0 | 10.0 | 14.16 | 19.14 | Au1rxx-base64 | 64.94.95.118 |
| 75.01 | shadowsocks | 487.6 | 1401.9 | 16.49 | 0.0 | 10.0 | 13.88 | 19.14 | Au1rxx-base64 | 68.168.222.210 |
| 74.75 | hysteria2 | 382.0 | 738.3 | 18.94 | 0.0 | 10.0 | 14.21 | 19.14 | Au1rxx-base64 | 144.31.207.60 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | 1.0 | 49 | 67 | prefer |
| Au1rxx-base64 | 0.94 | 0.883 | 402 | 1463 | prefer |
| Surfboard-tg-mixed | 0.812 | 0.735 | 136 | 6329 | prefer |
| DeltaKronecker-all | 0.374 | 0.289 | 83 | 5881 | observe |
| mheidari-all | 0.316 | 0.226 | 53 | 20211 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 6946 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7525 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5163 | observe |
| barry-far-vless | 0.255 | None | 0 | 5506 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5191 | observe |
| nscl5-all | 0.239 | None | 0 | 1607 | observe |
| Au1rxx-clash | 0.234 | None | 0 | 1463 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 62 |
| speed | TimeoutError | - | 37 |
| geo | ClientOSError | - | 33 |
| speed | ClientOSError | - | 24 |
| 204 | ProxyError | - | 7 |
| cn-block | TimeoutError | - | 7 |
| 204 | TimeoutError | - | 6 |
| speed | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
