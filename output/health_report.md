# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-30 02:51:09 |
| 运行耗时 | 375.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 77441 |
| 去重后节点 | 22598 |
| TCP 可达 | 3000 |
| 真实可用 | 751 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22598 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 31.8 |
| probe | 72.5 |
| real_test | 221.9 |
| generate | 41.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45294 |
| vmess | 11146 |
| shadowsocks | 10409 |
| trojan | 9796 |
| hysteria2 | 530 |
| shadowsocksr | 78 |
| http | 73 |
| socks | 67 |
| anytls | 26 |
| hysteria | 14 |
| tuic | 8 |

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
| 77.07 | hysteria2 | 271.0 | 662.4 | 21.5 | 0.0 | 10.0 | 10.31 | 16.36 | Au1rxx-base64 | 159.223.157.129 |
| 75.55 | shadowsocks | 241.1 | 602.8 | 22.2 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 156.146.38.168 |
| 75.35 | shadowsocks | 249.7 | 610.5 | 22.0 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 156.146.38.169 |
| 74.82 | trojan | 323.0 | 815.3 | 20.3 | 0.0 | 10.0 | 11.38 | 16.36 | Au1rxx-base64 | 163.245.196.68 |
| 73.2 | shadowsocks | 290.5 | 683.4 | 21.05 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 37.19.198.236 |
| 73.18 | hysteria2 | 292.0 | 718.6 | 21.02 | 0.0 | 7.51 | 10.31 | 16.36 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 73.16 | shadowsocks | 286.1 | 665.1 | 21.15 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 37.19.198.243 |
| 72.65 | shadowsocks | 303.5 | 720.9 | 20.75 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 37.19.198.244 |
| 72.25 | shadowsocks | 380.1 | 966.5 | 18.98 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 37.19.198.160 |
| 72.18 | trojan | 321.2 | 732.3 | 20.34 | 0.0 | 10.0 | 11.38 | 16.36 | Au1rxx-base64 | 153.75.250.171 |
| 71.79 | vless | 303.2 | 695.6 | 20.76 | 0.0 | 10.0 | 9.54 | 13.66 | DeltaKronecker-all | 78.153.155.112 |
| 71.77 | shadowsocks | 353.3 | 908.8 | 19.6 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 156.146.38.195 |
| 71.36 | shadowsocks | 377.5 | 881.3 | 19.04 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 185.196.61.82 |
| 71.19 | vless | 228.4 | 510.0 | 22.49 | 0.0 | 10.0 | 9.54 | 13.66 | DeltaKronecker-all | 92.223.71.246 |
| 70.89 | shadowsocks | 239.4 | 617.5 | 22.24 | 0.0 | 10.0 | 10.99 | 13.66 | DeltaKronecker-all | 104.192.227.164 |
| 70.75 | vless | 368.7 | 925.3 | 19.24 | 0.0 | 10.0 | 9.54 | 13.66 | DeltaKronecker-all | 45.138.100.226 |
| 70.29 | shadowsocks | 252.2 | 621.4 | 21.94 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 156.146.38.167 |
| 69.57 | shadowsocks | 360.4 | 855.5 | 19.44 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 198.98.53.130 |
| 69.57 | shadowsocks | 381.9 | 918.0 | 18.94 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 185.247.68.94 |
| 69.4 | shadowsocks | 281.8 | 558.1 | 21.25 | 0.0 | 10.0 | 10.99 | 16.36 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 70 | 84 | prefer |
| Au1rxx-base64 | 0.948 | 0.9 | 291 | 1255 | prefer |
| Surfboard-tg-mixed | 0.709 | 0.636 | 33 | 5390 | prefer |
| DeltaKronecker-all | 0.435 | 0.355 | 1112 | 5519 | observe |
| mheidari-all | 0.291 | 0.25 | 12 | 16333 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5118 | observe |
| Epodonios-all | 0.255 | None | 0 | 6124 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6420 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4279 | observe |
| barry-far-vless | 0.255 | None | 0 | 4688 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5076 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.225 | None | 0 | 1255 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 249 |
| speed | ClientOSError | - | 114 |
| cn-block | TimeoutError | - | 104 |
| 204 | ProxyError | - | 88 |
| geo | ClientOSError | - | 48 |
| geo | ProxyError | - | 44 |
| cn-block | ProxyError | - | 41 |
| speed | TimeoutError | - | 39 |
| speed | ProxyError | - | 20 |
| 204 | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 6 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
