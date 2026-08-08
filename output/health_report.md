# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-08 18:48:03 |
| 运行耗时 | 227.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83469 |
| 去重后节点 | 23605 |
| TCP 可达 | 3000 |
| 真实可用 | 408 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23605 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.0 |
| tcp | 35.1 |
| probe | 51.1 |
| real_test | 90.4 |
| generate | 44.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49002 |
| vmess | 13041 |
| trojan | 10099 |
| shadowsocks | 9795 |
| hysteria2 | 1330 |
| shadowsocksr | 74 |
| socks | 70 |
| http | 36 |
| hysteria | 13 |
| tuic | 8 |
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
| 84.41 | hysteria2 | 262.2 | 662.5 | 21.71 | 0.0 | 10.0 | 13.8 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 84.27 | hysteria2 | 272.4 | 708.4 | 21.47 | 0.0 | 10.0 | 13.8 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 84.14 | hysteria2 | 278.3 | 723.8 | 21.34 | 0.0 | 10.0 | 13.8 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.54 | shadowsocks | 256.3 | 640.8 | 21.84 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.5 | shadowsocks | 258.1 | 633.9 | 21.8 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 81.5 | shadowsocks | 258.3 | 632.8 | 21.8 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.3 | shadowsocks | 267.0 | 676.8 | 21.6 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 80.75 | trojan | 268.3 | 624.3 | 21.57 | 0.0 | 10.0 | 13.66 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 80.56 | shadowsocks | 253.4 | 614.6 | 21.91 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 80.23 | trojan | 331.4 | 804.4 | 20.11 | 0.0 | 10.0 | 13.66 | 20.0 | Au1rxx-base64 | 64.94.95.114 |
| 78.81 | trojan | 363.1 | 902.9 | 19.37 | 0.0 | 10.0 | 13.66 | 20.0 | Au1rxx-base64 | 64.94.95.115 |
| 78.53 | trojan | 384.5 | 969.6 | 18.88 | 0.0 | 10.0 | 13.66 | 20.0 | Au1rxx-base64 | 64.94.95.117 |
| 78.24 | shadowsocks | 377.5 | 924.7 | 19.04 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 68.168.222.210 |
| 77.74 | vless | 374.6 | 1012.7 | 19.11 | 0.0 | 10.0 | 9.73 | 20.0 | Au1rxx-base64 | 45.138.100.226 |
| 76.64 | shadowsocks | 288.2 | 576.0 | 21.11 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 75.96 | shadowsocks | 313.0 | 659.4 | 20.53 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 75.94 | shadowsocks | 282.4 | 724.9 | 21.24 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 75.57 | shadowsocks | 307.5 | 716.5 | 20.66 | 0.0 | 10.0 | 13.7 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 75.05 | http | 329.0 | 620.8 | 20.16 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 75.01 | http | 330.5 | 617.2 | 20.13 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.985 | 0.926 | 338 | 1540 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| mheidari-all | 0.875 | 0.889 | 18 | 17642 | prefer |
| Surfboard-tg-mixed | 0.71 | 0.633 | 90 | 6620 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5450 | observe |
| Epodonios-all | 0.255 | None | 0 | 7201 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7604 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5385 | observe |
| barry-far-vless | 0.255 | None | 0 | 5666 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5127 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.241 | None | 0 | 1643 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1540 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 29 |
| cn-block | TimeoutError | - | 19 |
| 204 | ClientOSError | - | 6 |
| 204 | ProxyError | - | 6 |
| speed | TimeoutError | - | 5 |
| geo | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| speed | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
