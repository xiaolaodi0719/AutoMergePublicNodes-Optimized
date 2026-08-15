# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-15 06:53:37 |
| 运行耗时 | 456.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78120 |
| 去重后节点 | 22201 |
| TCP 可达 | 3000 |
| 真实可用 | 1192 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22201 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.3 |
| tcp | 34.4 |
| probe | 81.2 |
| real_test | 300.7 |
| generate | 34.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44032 |
| trojan | 11940 |
| vmess | 10772 |
| shadowsocks | 10072 |
| hysteria2 | 953 |
| http | 187 |
| socks | 77 |
| shadowsocksr | 72 |
| tuic | 8 |
| hysteria | 7 |

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
| 84.77 | hysteria2 | 256.7 | 566.2 | 21.84 | 0.0 | 9.61 | 14.32 | 20.0 | Au1rxx-base64 | 150.241.102.127 |
| 82.79 | http | 240.7 | 541.2 | 22.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 82.5 | http | 239.1 | 527.6 | 22.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 82.5 | http | 246.3 | 547.0 | 22.08 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 82.39 | http | 235.0 | 523.2 | 22.34 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 82.38 | http | 239.0 | 534.6 | 22.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 82.29 | http | 237.3 | 529.4 | 22.29 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 82.28 | shadowsocks | 239.6 | 604.2 | 22.23 | 0.0 | 10.0 | 14.05 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 82.27 | shadowsocks | 239.9 | 614.5 | 22.22 | 0.0 | 10.0 | 14.05 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 82.21 | http | 239.1 | 532.3 | 22.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 82.18 | hysteria2 | 315.2 | 748.3 | 20.48 | 0.0 | 10.0 | 14.32 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 82.06 | http | 256.8 | 580.7 | 21.83 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 81.62 | http | 235.9 | 522.7 | 22.32 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 81.44 | hysteria2 | 320.9 | 723.9 | 20.35 | 0.0 | 10.0 | 14.32 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 81.38 | http | 245.6 | 555.3 | 22.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 81.2 | http | 245.6 | 556.2 | 22.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 81.03 | http | 241.5 | 541.2 | 22.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 80.83 | http | 238.1 | 532.9 | 22.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 79.94 | trojan | 263.9 | 514.7 | 21.67 | 0.0 | 10.0 | 14.67 | 20.0 | Au1rxx-base64 | 54.244.169.225 |
| 79.51 | trojan | 292.9 | 609.6 | 21.0 | 0.0 | 10.0 | 14.67 | 20.0 | Au1rxx-base64 | 34.221.30.108 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.949 | 811 | 1975 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.593 | 1.0 | 7 | 5665 | observe |
| DeltaKronecker-all | 0.491 | 0.411 | 669 | 5773 | observe |
| mheidari-all | 0.482 | 0.5 | 14 | 15492 | observe |
| nscl5-all | 0.4 | 0.75 | 4 | 2081 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 162 | observe |
| Epodonios-all | 0.255 | None | 0 | 6322 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7671 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4367 | observe |
| barry-far-vless | 0.255 | None | 0 | 4715 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3935 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 205 |
| geo | ClientOSError | - | 77 |
| speed | TimeoutError | - | 54 |
| speed | ClientOSError | - | 43 |
| cn-block | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 21 |
| 204 | ProxyError | - | 14 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
