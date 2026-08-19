# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-19 06:58:54 |
| 运行耗时 | 415.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82903 |
| 去重后节点 | 22465 |
| TCP 可达 | 3000 |
| 真实可用 | 1411 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22465 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 0.8 |
| tcp | 35.0 |
| probe | 81.9 |
| real_test | 256.5 |
| generate | 34.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44348 |
| trojan | 18415 |
| shadowsocks | 10123 |
| vmess | 8472 |
| hysteria2 | 1129 |
| http | 178 |
| socks | 117 |
| shadowsocksr | 97 |
| tuic | 10 |
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
| 85.28 | hysteria2 | 214.8 | 498.3 | 22.81 | 0.0 | 10.0 | 13.75 | 20.0 | Au1rxx-base64 | 150.241.102.127 |
| 82.99 | trojan | 196.4 | 516.4 | 23.23 | 0.0 | 10.0 | 14.76 | 20.0 | Au1rxx-base64 | 128.14.181.220 |
| 82.82 | trojan | 203.8 | 496.5 | 23.06 | 0.0 | 10.0 | 14.76 | 20.0 | Au1rxx-base64 | 147.182.198.83 |
| 82.82 | shadowsocks | 204.9 | 511.7 | 23.04 | 0.0 | 9.63 | 14.15 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 82.78 | shadowsocks | 222.2 | 524.3 | 22.63 | 0.0 | 10.0 | 14.15 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 82.55 | http | 195.2 | 508.3 | 23.26 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 82.15 | shadowsocks | 249.6 | 609.3 | 22.0 | 0.0 | 10.0 | 14.15 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.92 | shadowsocks | 259.4 | 643.2 | 21.77 | 0.0 | 10.0 | 14.15 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 81.66 | shadowsocks | 254.8 | 628.7 | 21.88 | 0.0 | 9.63 | 14.15 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 81.54 | vless | 191.9 | 490.1 | 23.33 | 0.0 | 10.0 | 8.21 | 20.0 | Au1rxx-base64 | 70.39.197.13 |
| 81.14 | http | 367.1 | 1020.7 | 19.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 80.38 | vless | 242.3 | 633.2 | 22.17 | 0.0 | 10.0 | 8.21 | 20.0 | Au1rxx-base64 | 70.39.198.93 |
| 80.31 | trojan | 277.8 | 584.0 | 21.35 | 0.0 | 10.0 | 14.76 | 20.0 | Au1rxx-base64 | 34.220.224.252 |
| 80.3 | trojan | 272.8 | 563.7 | 21.46 | 0.0 | 10.0 | 14.76 | 20.0 | Au1rxx-base64 | 35.88.120.18 |
| 80.03 | trojan | 196.5 | 509.9 | 23.23 | 0.0 | 10.0 | 14.76 | 17.04 | mheidari-all | 128.14.180.210 |
| 80.0 | trojan | 205.5 | 493.0 | 23.02 | 0.0 | 10.0 | 14.76 | 17.7 | Surfboard-tg-mixed | 173.255.247.228 |
| 79.83 | trojan | 203.4 | 491.6 | 23.07 | 0.0 | 10.0 | 14.76 | 20.0 | Au1rxx-base64 | 154.21.92.100 |
| 79.8 | shadowsocks | 251.6 | 615.1 | 21.95 | 0.0 | 10.0 | 14.15 | 17.7 | Surfboard-tg-mixed | 156.146.38.167 |
| 79.62 | shadowsocks | 209.6 | 479.8 | 22.93 | 0.0 | 10.0 | 14.15 | 17.04 | mheidari-all | 108.181.118.10 |
| 79.56 | shadowsocks | 212.2 | 479.9 | 22.87 | 0.0 | 10.0 | 14.15 | 17.04 | mheidari-all | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.989 | 803 | 1924 | prefer |
| mheidari-all | 1.0 | 0.926 | 257 | 16809 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.87 | 0.792 | 307 | 6315 | prefer |
| nscl5-all | 0.373 | 0.6 | 5 | 3330 | observe |
| DeltaKronecker-all | 0.299 | 0.2 | 30 | 6390 | observe |
| Epodonios-all | 0.255 | None | 0 | 7030 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7119 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4850 | observe |
| barry-far-vless | 0.255 | None | 0 | 5173 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3995 | observe |
| Au1rxx-clash | 0.252 | None | 0 | 1924 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 30 |
| speed | TimeoutError | - | 28 |
| geo | ClientOSError | - | 15 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyError | - | 8 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:34673: bind: address already in use | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
