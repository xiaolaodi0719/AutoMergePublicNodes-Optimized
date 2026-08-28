# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-28 22:05:04 |
| 运行耗时 | 272.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 77028 |
| 去重后节点 | 20891 |
| TCP 可达 | 3000 |
| 真实可用 | 631 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 20891 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 34.8 |
| probe | 57.1 |
| real_test | 126.2 |
| generate | 47.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47110 |
| vmess | 10729 |
| shadowsocks | 10518 |
| trojan | 6586 |
| hysteria2 | 1721 |
| http | 176 |
| shadowsocksr | 124 |
| socks | 54 |
| hysteria | 7 |
| tuic | 3 |

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
| 80.66 | shadowsocks | 243.6 | 608.7 | 22.14 | 0.0 | 10.0 | 13.36 | 19.16 | Au1rxx-base64 | 156.146.38.170 |
| 80.39 | shadowsocks | 233.7 | 574.6 | 22.37 | 0.0 | 9.5 | 13.36 | 19.16 | Au1rxx-base64 | 156.146.38.169 |
| 80.39 | shadowsocks | 236.3 | 600.5 | 22.31 | 0.0 | 9.56 | 13.36 | 19.16 | Au1rxx-base64 | 156.146.38.168 |
| 80.34 | vless | 275.6 | 629.6 | 21.4 | 0.0 | 9.47 | 10.31 | 19.16 | Au1rxx-base64 | 198.251.78.29 |
| 79.56 | shadowsocks | 291.2 | 745.3 | 21.04 | 0.0 | 10.0 | 13.36 | 19.16 | Au1rxx-base64 | 156.146.38.167 |
| 79.0 | vless | 283.0 | 653.6 | 21.23 | 0.0 | 10.0 | 10.31 | 19.16 | Au1rxx-base64 | 195.211.98.214 |
| 78.0 | vless | 317.6 | 750.3 | 20.43 | 0.0 | 10.0 | 10.31 | 19.16 | Au1rxx-base64 | 47.89.186.170 |
| 77.59 | shadowsocks | 294.0 | 689.4 | 20.97 | 0.0 | 10.0 | 13.36 | 19.16 | Au1rxx-base64 | 37.19.198.160 |
| 77.27 | shadowsocks | 291.4 | 693.2 | 21.03 | 0.0 | 10.0 | 13.36 | 19.16 | Au1rxx-base64 | 37.19.198.243 |
| 77.25 | vless | 384.6 | 987.9 | 18.88 | 0.0 | 10.0 | 10.31 | 19.16 | Au1rxx-base64 | 45.138.100.226 |
| 77.24 | trojan | 300.7 | 712.8 | 20.82 | 0.0 | 10.0 | 10.26 | 19.16 | Au1rxx-base64 | 64.94.95.114 |
| 77.04 | vless | 300.2 | 687.8 | 20.83 | 0.0 | 9.52 | 10.31 | 19.16 | Au1rxx-base64 | 137.184.218.169 |
| 76.49 | hysteria2 | 323.4 | 691.0 | 20.29 | 0.0 | 10.0 | 13.8 | 16.08 | mheidari-all | 159.223.157.129 |
| 76.47 | trojan | 284.8 | 661.9 | 21.18 | 0.0 | 10.0 | 10.26 | 19.16 | Au1rxx-base64 | 64.94.95.115 |
| 76.46 | vless | 382.1 | 882.8 | 18.93 | 0.0 | 10.0 | 10.31 | 19.16 | Au1rxx-base64 | 204.48.20.223 |
| 76.02 | vless | 357.5 | 831.0 | 19.5 | 0.0 | 9.53 | 10.31 | 19.16 | Au1rxx-base64 | 169.40.42.15 |
| 75.82 | shadowsocks | 300.8 | 587.9 | 20.82 | 0.0 | 10.0 | 13.36 | 19.16 | Au1rxx-base64 | 173.244.56.9 |
| 75.71 | vless | 305.4 | 687.2 | 20.71 | 0.0 | 8.7 | 10.31 | 19.16 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 75.56 | vless | 255.0 | 608.2 | 21.87 | 0.0 | 9.5 | 10.31 | 19.16 | Au1rxx-base64 | 216.227.161.95 |
| 75.49 | trojan | 371.5 | 949.6 | 19.18 | 0.0 | 10.0 | 10.26 | 19.16 | Au1rxx-base64 | 64.94.95.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.945 | 344 | 1776 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| mheidari-all | 0.95 | 0.88 | 75 | 14493 | prefer |
| DeltaKronecker-all | 0.839 | 0.764 | 110 | 4065 | prefer |
| Surfboard-tg-mixed | 0.803 | 0.726 | 175 | 6713 | prefer |
| tg-oneclickvpnkeys | 0.445 | 1.0 | 5 | 140 | observe |
| nscl5-all | 0.279 | 1.0 | 1 | 594 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4725 | observe |
| Epodonios-all | 0.255 | None | 0 | 6861 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7878 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5540 | observe |
| barry-far-vless | 0.255 | None | 0 | 5468 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4081 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 27 |
| geo | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 13 |
| geo | TimeoutError | - | 8 |
| speed | TimeoutError | - | 8 |
| cn-block | ProxyError | - | 7 |
| speed | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:49910: bind: address already in use | - | 1 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
