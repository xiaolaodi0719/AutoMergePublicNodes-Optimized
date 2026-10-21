# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 21:37:09 |
| 运行耗时 | 603.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96052 |
| 去重后节点 | 26993 |
| TCP 可达 | 3000 |
| 真实可用 | 360 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26993 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.5 |
| tcp | 44.9 |
| probe | 261.4 |
| real_test | 211.1 |
| generate | 78.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57052 |
| vmess | 16954 |
| shadowsocks | 11970 |
| trojan | 8422 |
| hysteria2 | 1270 |
| shadowsocksr | 164 |
| http | 121 |
| socks | 55 |
| anytls | 21 |
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
| 78.07 | vless | 241.2 | 615.9 | 22.19 | 0.0 | 10.0 | 9.2 | 16.68 | Au1rxx-base64 | 154.12.38.202 |
| 77.78 | vless | 253.8 | 638.7 | 21.9 | 0.0 | 10.0 | 9.2 | 16.68 | Au1rxx-base64 | 154.12.38.159 |
| 77.72 | vless | 211.0 | 514.8 | 22.89 | 0.0 | 8.95 | 9.2 | 16.68 | Au1rxx-base64 | 195.123.240.65 |
| 76.18 | vless | 193.3 | 497.0 | 23.3 | 0.0 | 10.0 | 9.2 | 16.68 | Au1rxx-base64 | 45.76.172.197 |
| 75.63 | shadowsocks | 262.8 | 637.1 | 21.69 | 0.0 | 10.0 | 12.48 | 16.06 | Surfboard-tg-mixed | 156.146.38.168 |
| 75.46 | shadowsocks | 263.2 | 633.0 | 21.68 | 0.0 | 8.92 | 12.48 | 16.68 | Au1rxx-base64 | 156.146.38.167 |
| 75.1 | hysteria2 | 345.4 | 807.5 | 19.78 | 0.0 | 8.98 | 13.33 | 16.68 | Au1rxx-base64 | 129.213.91.185 |
| 74.83 | vless | 207.2 | 513.3 | 22.98 | 0.0 | 8.97 | 9.2 | 16.68 | Au1rxx-base64 | 156.229.164.4 |
| 73.92 | vless | 313.9 | 754.6 | 20.51 | 0.0 | 10.0 | 9.2 | 16.68 | Au1rxx-base64 | 23.95.222.127 |
| 73.91 | shadowsocks | 321.0 | 893.4 | 20.35 | 0.0 | 8.9 | 12.48 | 16.68 | Au1rxx-base64 | 95.215.201.18 |
| 73.84 | vless | 208.1 | 521.1 | 22.96 | 0.0 | 10.0 | 9.2 | 16.68 | Au1rxx-base64 | 45.78.7.153 |
| 73.23 | shadowsocks | 181.6 | 485.3 | 23.57 | 0.0 | 10.0 | 12.48 | 16.68 | Au1rxx-base64 | 167.160.90.50 |
| 72.86 | vless | 205.7 | 514.1 | 23.02 | 0.0 | 8.96 | 9.2 | 16.68 | Au1rxx-base64 | 172.236.227.60 |
| 72.06 | shadowsocks | 292.5 | 631.6 | 21.01 | 0.0 | 8.9 | 12.48 | 16.68 | Au1rxx-base64 | 149.22.95.183 |
| 71.47 | vless | 331.6 | 713.5 | 20.1 | 0.0 | 8.94 | 9.2 | 16.68 | Au1rxx-base64 | 44.248.233.99 |
| 70.89 | shadowsocks | 238.4 | 652.8 | 22.26 | 0.0 | 8.97 | 12.48 | 16.68 | Au1rxx-base64 | 167.160.90.54 |
| 70.83 | vless | 329.6 | 708.9 | 20.15 | 0.0 | 8.59 | 9.2 | 16.68 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 70.21 | vless | 368.6 | 779.3 | 19.25 | 0.0 | 10.0 | 9.2 | 16.68 | Au1rxx-base64 | 5.34.178.120 |
| 70.03 | shadowsocks | 352.7 | 754.3 | 19.61 | 0.0 | 10.0 | 12.48 | 16.68 | Au1rxx-base64 | 37.19.198.244 |
| 69.86 | shadowsocks | 264.9 | 634.9 | 21.65 | 0.0 | 8.92 | 12.48 | 16.68 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.88 | 0.81 | 58 | 23903 | prefer |
| Au1rxx-base64 | 0.857 | 0.796 | 250 | 1596 | prefer |
| Surfboard-tg-mixed | 0.856 | 0.78 | 123 | 7033 | prefer |
| zhangkai | 0.518 | 0.519 | 27 | 31 | observe |
| DeltaKronecker-all | 0.352 | 0.5 | 6 | 4067 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| Epodonios-all | 0.255 | None | 0 | 7500 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10005 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5488 | observe |
| barry-far-vless | 0.255 | None | 0 | 5734 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1596 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 22 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 16 |
| speed | ClientOSError | - | 13 |
| geo | ClientOSError | - | 10 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| geo | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 228 | 300 | - |
| global | False | 242 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
