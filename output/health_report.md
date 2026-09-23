# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 04:30:19 |
| 运行耗时 | 1223.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96642 |
| 去重后节点 | 26618 |
| TCP 可达 | 3000 |
| 真实可用 | 604 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26618 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.6 |
| tcp | 42.7 |
| probe | 399.5 |
| real_test | 697.5 |
| generate | 74.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59154 |
| vmess | 14890 |
| shadowsocks | 11265 |
| trojan | 8755 |
| hysteria2 | 1586 |
| http | 681 |
| shadowsocksr | 171 |
| socks | 89 |
| anytls | 24 |
| hysteria | 19 |
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
| 79.33 | shadowsocks | 262.7 | 716.4 | 21.7 | 0.0 | 10.0 | 14.09 | 17.54 | Au1rxx-base64 | 37.19.198.160 |
| 78.93 | vless | 293.3 | 729.1 | 20.99 | 0.0 | 10.0 | 10.4 | 17.54 | Au1rxx-base64 | 66.70.179.198 |
| 78.38 | shadowsocks | 265.7 | 726.4 | 21.63 | 0.0 | 10.0 | 14.09 | 16.66 | mheidari-all | 37.19.198.236 |
| 78.26 | vless | 271.2 | 702.8 | 21.5 | 0.0 | 8.82 | 10.4 | 17.54 | Au1rxx-base64 | 169.40.42.212 |
| 78.12 | vless | 288.6 | 691.5 | 21.1 | 0.0 | 9.08 | 10.4 | 17.54 | Au1rxx-base64 | 138.124.60.146 |
| 78.06 | shadowsocks | 267.5 | 727.4 | 21.59 | 0.0 | 8.84 | 14.09 | 17.54 | Au1rxx-base64 | 37.19.198.244 |
| 77.96 | vless | 281.2 | 679.5 | 21.27 | 0.0 | 8.75 | 10.4 | 17.54 | Au1rxx-base64 | 169.40.42.235 |
| 77.62 | vless | 269.0 | 639.8 | 21.55 | 0.0 | 8.81 | 10.4 | 17.54 | Au1rxx-base64 | 195.211.98.43 |
| 77.35 | vless | 288.1 | 744.0 | 21.11 | 0.0 | 8.75 | 10.4 | 17.54 | Au1rxx-base64 | 169.40.42.225 |
| 76.32 | vless | 365.7 | 919.8 | 19.31 | 0.0 | 9.07 | 10.4 | 17.54 | Au1rxx-base64 | 169.40.42.179 |
| 76.31 | shadowsocks | 333.2 | 941.7 | 20.06 | 0.0 | 10.0 | 14.09 | 16.66 | mheidari-all | 15.204.247.206 |
| 76.24 | vless | 356.1 | 973.9 | 19.53 | 0.0 | 8.77 | 10.4 | 17.54 | Au1rxx-base64 | 185.95.231.156 |
| 75.95 | shadowsocks | 278.6 | 652.5 | 21.33 | 0.0 | 9.03 | 14.09 | 17.54 | Au1rxx-base64 | 156.146.38.169 |
| 75.9 | vless | 351.4 | 932.0 | 19.64 | 0.0 | 8.88 | 10.4 | 17.54 | Au1rxx-base64 | 169.40.42.74 |
| 75.85 | vless | 386.7 | 1054.5 | 18.83 | 0.0 | 9.08 | 10.4 | 17.54 | Au1rxx-base64 | 185.95.231.233 |
| 75.83 | vless | 374.1 | 877.8 | 19.12 | 0.0 | 8.82 | 10.4 | 17.54 | Au1rxx-base64 | 169.40.42.173 |
| 75.75 | vless | 375.1 | 936.4 | 19.1 | 0.0 | 8.71 | 10.4 | 17.54 | Au1rxx-base64 | 169.40.42.182 |
| 75.68 | vless | 356.4 | 897.3 | 19.53 | 0.0 | 8.82 | 10.4 | 17.54 | Au1rxx-base64 | 169.40.42.202 |
| 75.38 | vless | 395.4 | 1017.4 | 18.62 | 0.0 | 8.82 | 10.4 | 17.54 | Au1rxx-base64 | 169.40.42.104 |
| 75.37 | shadowsocks | 294.7 | 641.9 | 20.96 | 0.0 | 10.0 | 14.09 | 17.54 | Au1rxx-base64 | 23.150.248.20 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.882 | 0.821 | 329 | 1585 | prefer |
| Surfboard-tg-mixed | 0.8 | 0.739 | 23 | 7168 | prefer |
| ermaozi | 0.701 | 0.7 | 30 | 346 | prefer |
| DeltaKronecker-all | 0.514 | 0.433 | 141 | 6324 | observe |
| mheidari-all | 0.371 | 0.291 | 802 | 22274 | observe |
| ermaozi-get_subscribe | 0.283 | 0.667 | 3 | 372 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4915 | observe |
| Epodonios-all | 0.255 | None | 0 | 7633 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8890 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5836 | observe |
| barry-far-vless | 0.255 | None | 0 | 6054 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4252 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1585 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 283 |
| speed | ClientOSError | - | 118 |
| speed | TimeoutError | - | 112 |
| geo | ClientOSError | - | 88 |
| cn-block | ClientOSError | - | 41 |
| 204 | TimeoutError | - | 36 |
| 204 | ProxyError | - | 22 |
| cn-block | TimeoutError | - | 18 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
