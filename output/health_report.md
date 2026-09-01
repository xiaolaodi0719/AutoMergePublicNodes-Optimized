# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-01 04:33:27 |
| 运行耗时 | 331.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 79985 |
| 去重后节点 | 22311 |
| TCP 可达 | 3000 |
| 真实可用 | 666 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22311 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 35.3 |
| probe | 89.6 |
| real_test | 154.2 |
| generate | 45.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50974 |
| vmess | 11048 |
| shadowsocks | 10040 |
| trojan | 6186 |
| hysteria2 | 1381 |
| http | 138 |
| shadowsocksr | 128 |
| socks | 76 |
| hysteria | 7 |
| tuic | 7 |

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
| 84.15 | vless | 218.5 | 594.6 | 22.72 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 195.211.99.45 |
| 84.1 | vless | 220.8 | 606.2 | 22.67 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 195.211.99.49 |
| 83.53 | vless | 245.1 | 629.5 | 22.1 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 172.105.104.54 |
| 82.64 | vless | 277.2 | 672.7 | 21.36 | 0.0 | 9.85 | 12.43 | 19.0 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 82.36 | vless | 295.9 | 718.8 | 20.93 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 169.40.42.184 |
| 82.22 | vless | 301.7 | 698.8 | 20.79 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 169.40.42.89 |
| 82.08 | vless | 286.6 | 683.9 | 21.14 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 204.48.20.223 |
| 81.48 | vless | 278.1 | 670.9 | 21.34 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 169.40.42.74 |
| 81.42 | shadowsocks | 223.2 | 601.2 | 22.61 | 0.0 | 10.0 | 14.31 | 19.0 | Au1rxx-base64 | 84.32.131.61 |
| 81.39 | vless | 301.4 | 673.1 | 20.8 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 169.40.42.15 |
| 81.17 | vless | 325.4 | 685.4 | 20.25 | 0.0 | 10.0 | 12.43 | 18.52 | mheidari-all | 169.40.42.235 |
| 80.92 | vless | 358.1 | 960.4 | 19.49 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 216.152.147.28 |
| 80.66 | shadowsocks | 256.8 | 626.2 | 21.83 | 0.0 | 10.0 | 14.31 | 18.52 | mheidari-all | 156.146.38.169 |
| 80.55 | vless | 305.7 | 699.0 | 20.7 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 169.40.42.225 |
| 80.53 | shadowsocks | 262.5 | 671.9 | 21.7 | 0.0 | 10.0 | 14.31 | 18.52 | mheidari-all | 37.19.198.160 |
| 80.52 | vless | 375.2 | 970.1 | 19.09 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 79.127.243.217 |
| 80.35 | vless | 340.2 | 744.1 | 19.9 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 169.40.42.223 |
| 80.33 | hysteria2 | 271.1 | 568.1 | 21.5 | 0.0 | 10.0 | 13.64 | 19.0 | Au1rxx-base64 | 66.94.121.46 |
| 80.14 | vless | 338.3 | 852.5 | 19.95 | 0.0 | 10.0 | 12.43 | 19.0 | Au1rxx-base64 | 167.17.69.171 |
| 80.08 | shadowsocks | 282.1 | 634.3 | 21.25 | 0.0 | 10.0 | 14.31 | 18.52 | mheidari-all | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | 0.915 | 364 | 1549 | prefer |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.893 | 0.819 | 105 | 6997 | prefer |
| mheidari-all | 0.732 | 0.654 | 133 | 15162 | prefer |
| DeltaKronecker-all | 0.382 | 0.301 | 449 | 5904 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7436 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7837 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5908 | observe |
| barry-far-vless | 0.255 | None | 0 | 6067 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4025 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1549 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| ninja-vless | 0.199 | 0.0 | 1 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 194 |
| geo | ClientOSError | - | 68 |
| speed | ClientOSError | - | 49 |
| speed | TimeoutError | - | 46 |
| cn-block | TimeoutError | - | 24 |
| 204 | ProxyError | - | 13 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
