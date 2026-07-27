# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-27 14:52:25 |
| 运行耗时 | 324.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 85526 |
| 去重后节点 | 22983 |
| TCP 可达 | 3000 |
| 真实可用 | 795 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22983 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.6 |
| tcp | 32.3 |
| probe | 68.1 |
| real_test | 189.9 |
| generate | 27.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48277 |
| trojan | 15967 |
| vmess | 10401 |
| shadowsocks | 9890 |
| hysteria2 | 704 |
| shadowsocksr | 109 |
| socks | 69 |
| http | 64 |
| anytls | 22 |
| hysteria | 15 |
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
| 80.24 | trojan | 312.5 | 777.5 | 20.54 | 0.0 | 10.0 | 13.22 | 19.48 | Au1rxx-base64 | 163.245.196.68 |
| 79.74 | shadowsocks | 249.3 | 613.7 | 22.01 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 156.146.38.167 |
| 79.7 | shadowsocks | 250.9 | 637.4 | 21.97 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 156.146.38.170 |
| 78.64 | shadowsocks | 253.3 | 642.0 | 21.91 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 156.146.38.169 |
| 77.14 | hysteria2 | 287.7 | 673.3 | 21.12 | 0.0 | 10.0 | 12.0 | 19.48 | Au1rxx-base64 | 159.223.157.129 |
| 76.71 | shadowsocks | 283.9 | 658.9 | 21.21 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 37.19.198.160 |
| 76.64 | shadowsocks | 290.6 | 688.1 | 21.05 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 37.19.198.244 |
| 76.39 | trojan | 351.9 | 770.2 | 19.63 | 0.0 | 10.0 | 13.22 | 19.48 | Au1rxx-base64 | 153.75.250.171 |
| 75.67 | shadowsocks | 332.5 | 821.0 | 20.08 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 37.19.198.243 |
| 74.68 | vless | 238.6 | 598.4 | 22.26 | 0.0 | 10.0 | 4.46 | 18.12 | mheidari-all | 154.193.55.183 |
| 74.43 | shadowsocks | 309.3 | 654.1 | 20.62 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 149.22.95.183 |
| 74.28 | shadowsocks | 296.8 | 549.4 | 20.91 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 173.244.56.6 |
| 74.06 | shadowsocks | 356.2 | 828.4 | 19.53 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 185.196.61.82 |
| 73.7 | shadowsocks | 275.2 | 543.8 | 21.41 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 173.244.56.9 |
| 73.69 | shadowsocks | 295.8 | 688.0 | 20.93 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 37.19.198.236 |
| 73.3 | trojan | 569.2 | 1565.6 | 14.6 | 0.0 | 10.0 | 13.22 | 19.48 | Au1rxx-base64 | 64.94.95.115 |
| 73.29 | shadowsocks | 335.1 | 690.9 | 20.02 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 108.181.0.177 |
| 72.83 | shadowsocks | 326.6 | 726.6 | 20.22 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 108.181.57.93 |
| 72.42 | trojan | 611.4 | 1720.4 | 13.62 | 0.0 | 10.0 | 13.22 | 19.48 | Au1rxx-base64 | 64.94.95.118 |
| 71.93 | vless | 281.8 | 533.4 | 21.26 | 0.0 | 10.0 | 4.46 | 18.12 | mheidari-all | 198.41.209.87 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | 0.938 | 390 | 1507 | prefer |
| zhangkai | 0.987 | 1.0 | 59 | 74 | prefer |
| DeltaKronecker-all | 0.744 | 0.667 | 129 | 5643 | prefer |
| Surfboard-tg-mixed | 0.728 | 0.654 | 52 | 5641 | prefer |
| mheidari-all | 0.624 | 0.545 | 448 | 19227 | observe |
| tg-oneclickvpnkeys | 0.346 | 0.667 | 6 | 131 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 3959 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4831 | observe |
| Epodonios-all | 0.255 | None | 0 | 6520 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6628 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4484 | observe |
| barry-far-vless | 0.255 | None | 0 | 4866 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5017 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 112 |
| speed | ClientOSError | - | 75 |
| geo | ClientOSError | - | 27 |
| cn-block | TimeoutError | - | 18 |
| speed | TimeoutError | - | 14 |
| 204 | ProxyError | - | 13 |
| cn-block | ProxyError | - | 10 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46187: bind: address already in use | - | 1 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
