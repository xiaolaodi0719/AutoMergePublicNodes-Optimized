# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-28 13:35:15 |
| 运行耗时 | 613.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96149 |
| 去重后节点 | 26789 |
| TCP 可达 | 3000 |
| 真实可用 | 430 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26789 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 44.6 |
| probe | 279.3 |
| real_test | 204.1 |
| generate | 75.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58652 |
| vmess | 14819 |
| shadowsocks | 11430 |
| trojan | 8868 |
| hysteria2 | 1473 |
| http | 617 |
| shadowsocksr | 169 |
| socks | 74 |
| anytls | 24 |
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
| 79.24 | shadowsocks | 274.6 | 711.3 | 21.42 | 0.0 | 10.0 | 13.76 | 18.06 | Au1rxx-base64 | 37.19.198.236 |
| 78.8 | shadowsocks | 235.3 | 589.4 | 22.33 | 0.0 | 8.65 | 13.76 | 18.06 | Au1rxx-base64 | 198.98.53.130 |
| 76.72 | hysteria2 | 292.6 | 574.1 | 21.0 | 0.0 | 8.6 | 14.38 | 18.06 | Au1rxx-base64 | 192.255.128.123 |
| 76.59 | shadowsocks | 312.0 | 866.6 | 20.56 | 0.0 | 8.71 | 13.76 | 18.06 | Au1rxx-base64 | 15.204.247.206 |
| 75.44 | shadowsocks | 294.3 | 635.3 | 20.96 | 0.0 | 10.0 | 13.76 | 18.06 | Au1rxx-base64 | 23.150.248.20 |
| 75.22 | shadowsocks | 283.0 | 631.7 | 21.23 | 0.0 | 8.71 | 13.76 | 18.06 | Au1rxx-base64 | 156.146.38.168 |
| 75.07 | vless | 249.2 | 691.6 | 22.01 | 0.0 | 8.69 | 6.31 | 18.06 | Au1rxx-base64 | 79.141.172.154 |
| 74.96 | hysteria2 | 317.2 | 297.5 | 20.44 | 3.84 | 6.37 | 14.38 | 18.06 | Au1rxx-base64 | open.w2m.ink |
| 74.43 | shadowsocks | 309.6 | 772.0 | 20.61 | 0.0 | 8.23 | 13.76 | 18.06 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 74.2 | shadowsocks | 433.9 | 889.8 | 17.73 | 0.0 | 8.65 | 13.76 | 18.06 | Au1rxx-base64 | 142.4.216.225 |
| 74.11 | vless | 274.7 | 710.1 | 21.42 | 0.0 | 8.69 | 6.31 | 18.06 | Au1rxx-base64 | 169.40.42.212 |
| 74.02 | vless | 293.5 | 694.5 | 20.98 | 0.0 | 8.67 | 6.31 | 18.06 | Au1rxx-base64 | 169.40.42.133 |
| 73.9 | vless | 298.8 | 783.2 | 20.86 | 0.0 | 8.67 | 6.31 | 18.06 | Au1rxx-base64 | 169.40.42.232 |
| 73.85 | shadowsocks | 324.6 | 782.3 | 20.26 | 0.0 | 8.75 | 13.76 | 18.06 | Au1rxx-base64 | 156.146.38.169 |
| 73.33 | shadowsocks | 373.4 | 968.5 | 19.13 | 0.0 | 10.0 | 13.76 | 14.94 | Surfboard-tg-mixed | 38.180.135.156 |
| 73.26 | shadowsocks | 259.8 | 707.0 | 21.76 | 0.0 | 8.68 | 13.76 | 18.06 | Au1rxx-base64 | 37.19.198.160 |
| 73.17 | vless | 365.6 | 961.8 | 19.32 | 0.0 | 10.0 | 6.31 | 18.06 | Au1rxx-base64 | 169.40.42.182 |
| 73.16 | hysteria2 | 420.6 | 848.9 | 18.04 | 0.0 | 8.99 | 14.38 | 18.06 | Au1rxx-base64 | paris.nerabotaet.com |
| 73.02 | vless | 394.3 | 1073.3 | 18.65 | 0.0 | 10.0 | 6.31 | 18.06 | Au1rxx-base64 | 159.89.87.21 |
| 72.96 | vless | 339.1 | 830.9 | 19.93 | 0.0 | 8.66 | 6.31 | 18.06 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.927 | 0.86 | 57 | 22474 | prefer |
| Au1rxx-base64 | 0.881 | 0.816 | 304 | 1677 | prefer |
| Surfboard-tg-mixed | 0.801 | 0.724 | 127 | 7046 | prefer |
| ermaozi | 0.569 | 0.558 | 52 | 344 | observe |
| DeltaKronecker-all | 0.543 | 0.615 | 13 | 5428 | observe |
| tg-oneclickvpnkeys | 0.315 | 1.0 | 2 | 94 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5326 | observe |
| Epodonios-all | 0.255 | None | 0 | 7414 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9420 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5638 | observe |
| barry-far-vless | 0.255 | None | 0 | 5752 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4185 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 21 |
| speed | ClientOSError | - | 20 |
| 204 | ProxyError | - | 18 |
| speed | TimeoutError | - | 16 |
| 204 | ProxyConnectionError | - | 12 |
| geo | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 4 |
| geo | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
