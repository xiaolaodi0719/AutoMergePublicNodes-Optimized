# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-25 01:40:25 |
| 运行耗时 | 307.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 83410 |
| 去重后节点 | 23892 |
| TCP 可达 | 3000 |
| 真实可用 | 732 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23892 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.5 |
| tcp | 38.2 |
| probe | 60.3 |
| real_test | 168.3 |
| generate | 33.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52265 |
| shadowsocks | 11137 |
| vmess | 10512 |
| trojan | 7603 |
| hysteria2 | 1509 |
| http | 164 |
| shadowsocksr | 132 |
| socks | 68 |
| hysteria | 13 |
| tuic | 5 |
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
| 80.9 | shadowsocks | 249.7 | 604.1 | 22.0 | 0.0 | 10.0 | 13.68 | 19.22 | Au1rxx-base64 | 156.146.38.169 |
| 80.59 | http | 244.1 | 536.2 | 22.13 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.198 |
| 80.12 | shadowsocks | 283.1 | 740.6 | 21.22 | 0.0 | 10.0 | 13.68 | 19.22 | Au1rxx-base64 | 156.146.38.170 |
| 80.09 | http | 244.9 | 540.8 | 22.11 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.216 |
| 80.07 | vless | 274.8 | 615.3 | 21.42 | 0.0 | 10.0 | 11.09 | 19.22 | Au1rxx-base64 | 15.204.97.195 |
| 79.72 | trojan | 304.5 | 771.2 | 20.73 | 0.0 | 10.0 | 12.77 | 19.22 | Au1rxx-base64 | 64.94.95.117 |
| 79.49 | shadowsocks | 254.3 | 607.1 | 21.89 | 0.0 | 10.0 | 13.68 | 19.22 | Au1rxx-base64 | 23.150.248.20 |
| 79.45 | trojan | 281.1 | 703.8 | 21.27 | 0.0 | 10.0 | 12.77 | 19.22 | Au1rxx-base64 | 64.94.95.115 |
| 79.34 | vless | 271.2 | 586.9 | 21.5 | 0.0 | 10.0 | 11.09 | 19.22 | Au1rxx-base64 | 15.204.97.197 |
| 78.5 | trojan | 354.3 | 917.8 | 19.58 | 0.0 | 10.0 | 12.77 | 19.22 | Au1rxx-base64 | 64.94.95.118 |
| 78.13 | shadowsocks | 245.1 | 623.2 | 22.1 | 0.0 | 10.0 | 13.68 | 19.22 | Au1rxx-base64 | 156.146.38.167 |
| 77.94 | vless | 279.7 | 563.6 | 21.3 | 0.0 | 10.0 | 11.09 | 19.22 | Au1rxx-base64 | 23.172.40.60 |
| 77.56 | vless | 355.9 | 843.6 | 19.54 | 0.0 | 10.0 | 11.09 | 19.22 | Au1rxx-base64 | 15.204.97.209 |
| 77.43 | shadowsocks | 267.3 | 564.2 | 21.59 | 0.0 | 10.0 | 13.68 | 19.22 | Au1rxx-base64 | 154.12.240.141 |
| 77.34 | shadowsocks | 253.8 | 568.4 | 21.9 | 0.0 | 10.0 | 13.68 | 19.22 | Au1rxx-base64 | 154.53.60.212 |
| 76.98 | vless | 329.5 | 706.3 | 20.15 | 0.0 | 10.0 | 11.09 | 19.22 | Au1rxx-base64 | 198.251.78.29 |
| 76.51 | hysteria2 | 333.9 | 744.7 | 20.05 | 0.0 | 10.0 | 13.85 | 16.1 | mheidari-all | 159.223.157.129 |
| 76.05 | trojan | 285.8 | 568.5 | 21.16 | 0.0 | 10.0 | 12.77 | 19.22 | Au1rxx-base64 | 35.91.251.124 |
| 75.99 | shadowsocks | 294.0 | 647.4 | 20.97 | 0.0 | 10.0 | 13.68 | 19.22 | Au1rxx-base64 | 94.72.127.58 |
| 75.98 | trojan | 287.2 | 587.3 | 21.13 | 0.0 | 10.0 | 12.77 | 18.84 | Surfboard-tg-mixed | 44.246.163.102 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | 0.92 | 476 | 1713 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.9 | 0.824 | 176 | 6540 | prefer |
| mheidari-all | 0.329 | 0.248 | 467 | 19487 | observe |
| DeltaKronecker-all | 0.28 | 0.188 | 48 | 5914 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4899 | observe |
| Epodonios-all | 0.255 | None | 0 | 7074 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3989 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7047 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5352 | observe |
| barry-far-vless | 0.255 | None | 0 | 5640 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4132 | observe |
| ninja-vless | 0.251 | 0.333 | 3 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1714 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 195 |
| geo | ClientOSError | - | 108 |
| speed | TimeoutError | - | 83 |
| speed | ClientOSError | - | 40 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 8 |
| 204 | ProxyError | - | 6 |
| 204 | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
