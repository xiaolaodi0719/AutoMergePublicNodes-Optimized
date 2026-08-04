# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-04 03:01:44 |
| 运行耗时 | 314.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85783 |
| 去重后节点 | 24686 |
| TCP 可达 | 3000 |
| 真实可用 | 680 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24686 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.5 |
| tcp | 36.7 |
| probe | 59.2 |
| real_test | 166.3 |
| generate | 43.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52129 |
| vmess | 12946 |
| shadowsocks | 10193 |
| trojan | 9250 |
| hysteria2 | 1002 |
| socks | 76 |
| http | 76 |
| shadowsocksr | 73 |
| hysteria | 18 |
| tuic | 10 |
| anytls | 10 |

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
| 77.71 | hysteria2 | 234.1 | 648.9 | 22.36 | 0.0 | 10.0 | 10.31 | 16.14 | Au1rxx-base64 | 159.223.157.129 |
| 77.35 | vless | 243.9 | 634.4 | 22.13 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 167.17.69.171 |
| 77.01 | shadowsocks | 228.9 | 631.7 | 22.48 | 0.0 | 10.0 | 12.39 | 16.14 | Au1rxx-base64 | 37.19.198.243 |
| 76.99 | shadowsocks | 229.9 | 637.7 | 22.46 | 0.0 | 10.0 | 12.39 | 16.14 | Au1rxx-base64 | 37.19.198.160 |
| 76.91 | vless | 263.2 | 694.6 | 21.69 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 169.40.42.121 |
| 76.74 | trojan | 365.1 | 1010.2 | 19.33 | 0.0 | 10.0 | 14.27 | 16.14 | Au1rxx-base64 | 153.75.250.171 |
| 76.7 | shadowsocks | 242.1 | 649.0 | 22.17 | 0.0 | 10.0 | 12.39 | 16.14 | Au1rxx-base64 | 37.19.198.244 |
| 76.67 | shadowsocks | 243.7 | 681.7 | 22.14 | 0.0 | 10.0 | 12.39 | 16.14 | Au1rxx-base64 | 37.19.198.236 |
| 76.27 | vless | 290.6 | 767.8 | 21.05 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 169.40.42.16 |
| 75.43 | shadowsocks | 297.0 | 826.8 | 20.9 | 0.0 | 10.0 | 12.39 | 16.14 | Au1rxx-base64 | 198.98.53.130 |
| 75.35 | vless | 244.0 | 683.5 | 22.13 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 47.253.226.114 |
| 75.34 | vless | 330.9 | 898.5 | 20.12 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 169.40.42.133 |
| 75.26 | vless | 334.4 | 866.4 | 20.04 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 169.40.42.212 |
| 75.12 | vless | 340.5 | 868.7 | 19.9 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 169.40.42.232 |
| 75.04 | vless | 343.9 | 973.6 | 19.82 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 47.89.186.170 |
| 74.91 | vless | 349.5 | 886.2 | 19.69 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 169.40.42.179 |
| 74.74 | vless | 356.6 | 968.0 | 19.52 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 78.111.89.171 |
| 74.57 | vless | 252.7 | 651.9 | 21.93 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 169.40.42.184 |
| 74.06 | trojan | 308.5 | 665.1 | 20.64 | 0.0 | 10.0 | 14.27 | 16.14 | Au1rxx-base64 | 163.245.196.68 |
| 73.99 | vless | 346.1 | 869.8 | 19.77 | 0.0 | 10.0 | 9.08 | 16.14 | Au1rxx-base64 | 169.40.42.52 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 67 | 92 | prefer |
| Au1rxx-base64 | 0.886 | 0.82 | 627 | 1682 | prefer |
| Surfboard-tg-mixed | 0.494 | 0.412 | 131 | 5262 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5285 | observe |
| Epodonios-all | 0.255 | None | 0 | 5848 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6831 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4123 | observe |
| barry-far-vless | 0.255 | None | 0 | 4484 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5152 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5127 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1682 | observe |
| nscl5-all | 0.226 | None | 0 | 1267 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 245 |
| speed | TimeoutError | - | 101 |
| speed | ClientOSError | - | 58 |
| geo | ClientOSError | - | 50 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 10 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
