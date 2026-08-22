# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-22 06:53:08 |
| 运行耗时 | 304.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 91263 |
| 去重后节点 | 23609 |
| TCP 可达 | 3000 |
| 真实可用 | 777 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23609 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 39.2 |
| probe | 58.7 |
| real_test | 161.6 |
| generate | 37.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51782 |
| trojan | 15874 |
| shadowsocks | 10916 |
| vmess | 10589 |
| hysteria2 | 1549 |
| shadowsocksr | 203 |
| http | 167 |
| socks | 123 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 13 |

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
| 83.05 | shadowsocks | 225.9 | 609.1 | 22.55 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 82.85 | trojan | 222.9 | 582.3 | 22.62 | 0.0 | 9.45 | 13.78 | 20.0 | Au1rxx-base64 | 64.94.95.115 |
| 82.84 | trojan | 221.7 | 578.7 | 22.65 | 0.0 | 9.41 | 13.78 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 82.78 | trojan | 226.0 | 585.6 | 22.55 | 0.0 | 9.45 | 13.78 | 20.0 | Au1rxx-base64 | 64.94.95.114 |
| 82.73 | trojan | 225.6 | 588.2 | 22.56 | 0.0 | 9.39 | 13.78 | 20.0 | Au1rxx-base64 | 64.94.95.117 |
| 82.69 | shadowsocks | 213.4 | 578.4 | 22.84 | 0.0 | 9.35 | 14.5 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 82.43 | shadowsocks | 224.5 | 611.2 | 22.58 | 0.0 | 9.35 | 14.5 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 82.05 | http | 248.6 | 552.8 | 22.02 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 81.51 | shadowsocks | 247.8 | 593.5 | 22.04 | 0.0 | 9.47 | 14.5 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 81.28 | shadowsocks | 275.7 | 768.2 | 21.4 | 0.0 | 9.38 | 14.5 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.89 | http | 250.6 | 555.4 | 21.98 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |
| 80.09 | shadowsocks | 259.4 | 556.7 | 21.77 | 0.0 | 9.46 | 14.5 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 78.62 | shadowsocks | 306.8 | 653.0 | 20.68 | 0.0 | 9.37 | 14.5 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 77.95 | shadowsocks | 314.7 | 734.1 | 20.49 | 0.0 | 9.53 | 14.5 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 77.9 | shadowsocks | 233.4 | 521.7 | 22.38 | 0.0 | 9.4 | 14.5 | 20.0 | Au1rxx-base64 | 129.153.203.166 |
| 77.87 | shadowsocks | 274.0 | 563.9 | 21.43 | 0.0 | 9.37 | 14.5 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 77.85 | shadowsocks | 313.7 | 729.6 | 20.52 | 0.0 | 9.49 | 14.5 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 77.82 | shadowsocks | 311.9 | 730.6 | 20.56 | 0.0 | 9.39 | 14.5 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 77.55 | shadowsocks | 253.0 | 505.9 | 21.92 | 0.0 | 9.34 | 14.5 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 76.79 | shadowsocks | 310.1 | 680.7 | 20.6 | 0.0 | 9.63 | 14.5 | 20.0 | Au1rxx-base64 | 155.138.136.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.988 | 0.991 | 112 | 144 | prefer |
| Au1rxx-base64 | 0.97 | 0.919 | 447 | 1299 | prefer |
| Surfboard-tg-mixed | 0.881 | 0.805 | 174 | 6140 | prefer |
| mheidari-all | 0.69 | 0.612 | 152 | 21732 | observe |
| DeltaKronecker-all | 0.43 | 0.345 | 58 | 5015 | observe |
| nscl5-all | 0.335 | 1.0 | 1 | 3321 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 151 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5096 | observe |
| Epodonios-all | 0.255 | None | 0 | 6729 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3992 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7142 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4954 | observe |
| barry-far-vless | 0.255 | None | 0 | 5261 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4074 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 66 |
| geo | ClientOSError | - | 26 |
| speed | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 5 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48458: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
