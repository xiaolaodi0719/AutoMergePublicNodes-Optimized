# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-11 21:53:51 |
| 运行耗时 | 732.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99284 |
| 去重后节点 | 27441 |
| TCP 可达 | 3000 |
| 真实可用 | 478 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27441 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 46.8 |
| probe | 294.4 |
| real_test | 304.2 |
| generate | 77.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58285 |
| vmess | 15938 |
| shadowsocks | 11720 |
| trojan | 11000 |
| hysteria2 | 1485 |
| http | 568 |
| shadowsocksr | 166 |
| socks | 66 |
| anytls | 30 |
| hysteria | 16 |
| tuic | 10 |

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
| 84.98 | hysteria2 | 242.9 | 698.3 | 22.16 | 0.0 | 10.0 | 14.44 | 19.88 | Au1rxx-base64 | 129.213.91.185 |
| 84.13 | vless | 262.7 | 643.3 | 21.7 | 0.0 | 10.0 | 12.55 | 19.88 | mheidari-all | 195.211.98.43 |
| 83.96 | vless | 269.8 | 646.0 | 21.53 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.232 |
| 83.85 | vless | 274.8 | 656.4 | 21.42 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.182 |
| 83.63 | vless | 284.2 | 716.6 | 21.2 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 66.70.179.198 |
| 83.25 | vless | 300.7 | 676.3 | 20.82 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.184 |
| 83.16 | vless | 289.9 | 630.5 | 21.07 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 172.245.253.16 |
| 83.09 | vless | 307.6 | 748.6 | 20.66 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.231 |
| 82.97 | vless | 312.8 | 840.1 | 20.54 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.235 |
| 82.77 | vless | 280.6 | 637.0 | 21.28 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.212 |
| 82.74 | vless | 276.0 | 677.1 | 21.39 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.224 |
| 82.44 | vless | 335.7 | 909.8 | 20.01 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.16 |
| 82.26 | vless | 343.4 | 887.8 | 19.83 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.74 |
| 82.23 | vless | 344.7 | 935.9 | 19.8 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.52 |
| 81.96 | vless | 282.2 | 741.2 | 21.24 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.104 |
| 81.91 | vless | 287.9 | 756.2 | 21.11 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.90 |
| 81.85 | vless | 360.9 | 1014.3 | 19.42 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 185.95.231.156 |
| 81.74 | vless | 340.8 | 920.6 | 19.89 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.179 |
| 81.71 | vless | 309.2 | 715.3 | 20.62 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 169.40.42.35 |
| 81.71 | vless | 367.3 | 1057.4 | 19.28 | 0.0 | 10.0 | 12.55 | 19.88 | Au1rxx-base64 | 136.107.170.196 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.992 | 0.92 | 374 | 1858 | prefer |
| mheidari-all | 0.915 | 0.84 | 119 | 23882 | prefer |
| ermaozi | 0.611 | 0.59 | 39 | 635 | observe |
| Surfboard-tg-mixed | 0.474 | 0.6 | 10 | 7031 | observe |
| DeltaKronecker-all | 0.391 | 1.0 | 2 | 5372 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 104 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5099 | observe |
| Epodonios-all | 0.255 | None | 0 | 7711 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9704 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5590 | observe |
| barry-far-vless | 0.255 | None | 0 | 5966 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4284 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyError | - | 16 |
| 204 | TimeoutError | - | 8 |
| speed | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 6 |
| geo | ClientOSError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40536: bind: address already in use | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
