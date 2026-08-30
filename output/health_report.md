# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-30 11:41:43 |
| 运行耗时 | 275.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 79168 |
| 去重后节点 | 21765 |
| TCP 可达 | 3000 |
| 真实可用 | 619 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21765 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.5 |
| tcp | 34.5 |
| probe | 58.7 |
| real_test | 137.2 |
| generate | 38.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49358 |
| vmess | 10532 |
| shadowsocks | 10274 |
| trojan | 7159 |
| hysteria2 | 1474 |
| http | 169 |
| shadowsocksr | 134 |
| socks | 53 |
| hysteria | 7 |
| tuic | 7 |
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
| 83.73 | vless | 222.5 | 611.8 | 22.63 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 82.5 | vless | 271.4 | 665.7 | 21.49 | 0.0 | 9.91 | 11.1 | 20.0 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 82.29 | shadowsocks | 248.9 | 604.4 | 22.02 | 0.0 | 10.0 | 14.27 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 82.26 | vless | 277.6 | 686.9 | 21.35 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 38.77.133.141 |
| 82.16 | shadowsocks | 244.5 | 596.4 | 22.12 | 0.0 | 10.0 | 14.27 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 82.12 | shadowsocks | 256.1 | 642.8 | 21.85 | 0.0 | 10.0 | 14.27 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 82.07 | shadowsocks | 258.3 | 651.0 | 21.8 | 0.0 | 10.0 | 14.27 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 82.01 | shadowsocks | 260.9 | 653.0 | 21.74 | 0.0 | 10.0 | 14.27 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.55 | vless | 309.4 | 713.4 | 20.62 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 169.40.42.89 |
| 81.28 | vless | 328.2 | 883.6 | 20.18 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 81.08 | vless | 315.7 | 719.9 | 20.47 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 169.40.42.35 |
| 80.6 | vless | 336.3 | 698.7 | 19.99 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 169.40.42.173 |
| 80.3 | shadowsocks | 270.0 | 776.6 | 21.53 | 0.0 | 10.0 | 14.27 | 20.0 | Au1rxx-base64 | 84.32.131.61 |
| 80.03 | vless | 382.2 | 995.9 | 18.93 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 79.127.243.217 |
| 79.56 | vless | 402.6 | 991.9 | 18.46 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 79.22 | vless | 241.5 | 625.2 | 22.19 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 172.105.104.54 |
| 78.99 | shadowsocks | 264.4 | 679.7 | 21.66 | 0.0 | 10.0 | 14.27 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 78.86 | vless | 397.7 | 965.9 | 18.57 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 78.78 | vless | 395.1 | 1007.3 | 18.63 | 0.0 | 10.0 | 11.1 | 20.0 | Au1rxx-base64 | 169.40.42.95 |
| 78.31 | vless | 421.8 | 1121.0 | 18.01 | 0.0 | 10.0 | 11.1 | 19.2 | Surfboard-tg-mixed | 47.89.186.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.945 | 347 | 1804 | prefer |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.833 | 0.756 | 172 | 6846 | prefer |
| DeltaKronecker-all | 0.813 | 0.736 | 174 | 5576 | prefer |
| mheidari-all | 0.624 | 0.818 | 11 | 15081 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4762 | observe |
| Epodonios-all | 0.255 | None | 0 | 7251 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3991 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7584 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5683 | observe |
| barry-far-vless | 0.255 | None | 0 | 5864 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3949 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 23 |
| geo | ClientOSError | - | 15 |
| 204 | ProxyError | - | 10 |
| speed | ClientOSError | - | 9 |
| geo | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 5 |
| geo | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| speed | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:47024: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
