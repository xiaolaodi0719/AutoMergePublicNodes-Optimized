# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 20:56:59 |
| 运行耗时 | 681.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99400 |
| 去重后节点 | 27657 |
| TCP 可达 | 3000 |
| 真实可用 | 445 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27657 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.5 |
| tcp | 48.9 |
| probe | 254.1 |
| real_test | 291.0 |
| generate | 79.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58371 |
| vmess | 16698 |
| shadowsocks | 12080 |
| trojan | 10034 |
| hysteria2 | 1310 |
| http | 631 |
| shadowsocksr | 166 |
| socks | 58 |
| anytls | 29 |
| hysteria | 17 |
| tuic | 6 |

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
| 78.41 | hysteria2 | 300.4 | 627.9 | 20.82 | 0.0 | 10.0 | 12.63 | 16.94 | Au1rxx-base64 | 66.94.121.46 |
| 77.68 | hysteria2 | 288.4 | 715.9 | 21.1 | 0.0 | 8.51 | 12.63 | 16.94 | Au1rxx-base64 | 129.213.91.185 |
| 76.84 | shadowsocks | 240.6 | 589.7 | 22.21 | 0.0 | 8.2 | 13.49 | 16.94 | Au1rxx-base64 | 156.146.38.168 |
| 76.78 | shadowsocks | 242.6 | 613.5 | 22.16 | 0.0 | 8.19 | 13.49 | 16.94 | Au1rxx-base64 | 156.146.38.169 |
| 76.65 | shadowsocks | 247.8 | 600.0 | 22.04 | 0.0 | 8.18 | 13.49 | 16.94 | Au1rxx-base64 | 156.146.38.167 |
| 75.63 | shadowsocks | 249.4 | 652.7 | 22.0 | 0.0 | 8.2 | 13.49 | 16.94 | Au1rxx-base64 | 156.146.38.170 |
| 74.96 | shadowsocks | 316.2 | 754.2 | 20.46 | 0.0 | 8.2 | 13.49 | 16.94 | Au1rxx-base64 | 37.19.198.236 |
| 74.77 | vless | 326.0 | 832.8 | 20.23 | 0.0 | 8.2 | 9.4 | 16.94 | Au1rxx-base64 | 147.45.60.160 |
| 74.64 | trojan | 340.1 | 856.4 | 19.9 | 0.0 | 10.0 | 12.8 | 16.94 | Au1rxx-base64 | 66.23.203.21 |
| 73.58 | vless | 264.2 | 611.3 | 21.66 | 0.0 | 8.27 | 9.4 | 16.94 | Au1rxx-base64 | 195.211.98.43 |
| 73.47 | shadowsocks | 315.1 | 771.2 | 20.48 | 0.0 | 8.19 | 13.49 | 16.94 | Au1rxx-base64 | 37.19.198.243 |
| 72.86 | vless | 284.0 | 570.7 | 21.2 | 0.0 | 10.0 | 9.4 | 16.94 | Au1rxx-base64 | 47.251.108.158 |
| 72.47 | shadowsocks | 322.8 | 738.6 | 20.31 | 0.0 | 8.19 | 13.49 | 16.94 | Au1rxx-base64 | 37.19.198.160 |
| 72.35 | shadowsocks | 326.1 | 769.0 | 20.23 | 0.0 | 8.45 | 13.49 | 16.94 | Au1rxx-base64 | 64.74.163.67 |
| 71.58 | vless | 328.3 | 742.0 | 20.18 | 0.0 | 8.44 | 9.4 | 16.94 | Au1rxx-base64 | 66.70.179.198 |
| 71.56 | shadowsocks | 294.0 | 616.0 | 20.97 | 0.0 | 8.25 | 13.49 | 16.94 | Au1rxx-base64 | 173.244.56.9 |
| 71.47 | vless | 297.0 | 671.1 | 20.9 | 0.0 | 7.48 | 9.4 | 16.94 | Au1rxx-base64 | freeus.aiage.work |
| 71.17 | vless | 280.9 | 674.1 | 21.28 | 0.0 | 8.23 | 9.4 | 16.94 | Au1rxx-base64 | 69.48.201.136 |
| 71.0 | shadowsocks | 322.0 | 656.2 | 20.32 | 0.0 | 8.19 | 13.49 | 16.94 | Au1rxx-base64 | 149.22.95.183 |
| 70.95 | shadowsocks | 411.7 | 910.2 | 18.25 | 0.0 | 10.0 | 13.49 | 16.94 | Au1rxx-base64 | 15.204.247.206 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.867 | 0.788 | 501 | 1995 | prefer |
| Surfboard-tg-mixed | 0.515 | 0.432 | 44 | 7222 | observe |
| ermaozi | 0.418 | 0.39 | 59 | 618 | observe |
| mheidari-all | 0.389 | 0.385 | 13 | 23910 | observe |
| tg-oneclickvpnkeys | 0.315 | 1.0 | 2 | 88 | observe |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 4946 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7598 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10077 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5648 | observe |
| barry-far-vless | 0.255 | None | 0 | 5818 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 48 |
| 204 | TimeoutError | - | 37 |
| cn-block | TimeoutError | - | 16 |
| geo | ClientOSError | - | 14 |
| speed | ClientOSError | - | 14 |
| geo | TimeoutError | - | 14 |
| cn-block | ClientOSError | - | 12 |
| speed | TimeoutError | - | 11 |
| 204 | ClientOSError | - | 9 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:44687: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
