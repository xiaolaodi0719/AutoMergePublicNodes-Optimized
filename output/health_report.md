# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-21 13:02:11 |
| 运行耗时 | 340.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 95230 |
| 去重后节点 | 24848 |
| TCP 可达 | 3000 |
| 真实可用 | 1143 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24848 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.1 |
| tcp | 40.0 |
| probe | 61.2 |
| real_test | 195.7 |
| generate | 36.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52462 |
| trojan | 18914 |
| vmess | 10873 |
| shadowsocks | 10791 |
| hysteria2 | 1641 |
| shadowsocksr | 196 |
| http | 166 |
| socks | 129 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 11 |

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
| 81.95 | shadowsocks | 245.0 | 621.4 | 22.11 | 0.0 | 10.0 | 13.84 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 81.71 | shadowsocks | 255.2 | 637.9 | 21.87 | 0.0 | 10.0 | 13.84 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.07 | shadowsocks | 253.1 | 652.1 | 21.92 | 0.0 | 10.0 | 13.84 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.86 | trojan | 294.2 | 757.9 | 20.97 | 0.0 | 10.0 | 14.72 | 18.44 | mheidari-all | 64.94.95.118 |
| 80.3 | shadowsocks | 272.2 | 631.7 | 21.48 | 0.0 | 10.0 | 13.84 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 79.88 | shadowsocks | 323.6 | 818.4 | 20.29 | 0.0 | 10.0 | 13.84 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 79.6 | trojan | 360.3 | 924.8 | 19.44 | 0.0 | 10.0 | 14.72 | 18.44 | mheidari-all | 64.94.95.114 |
| 79.58 | trojan | 293.9 | 725.2 | 20.98 | 0.0 | 10.0 | 14.72 | 18.44 | mheidari-all | 64.94.95.117 |
| 79.43 | vless | 270.7 | 602.1 | 21.51 | 0.0 | 10.0 | 9.81 | 18.44 | mheidari-all | 216.227.161.95 |
| 79.23 | vless | 280.9 | 633.4 | 21.27 | 0.0 | 10.0 | 9.81 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 78.87 | trojan | 320.2 | 798.5 | 20.37 | 0.0 | 10.0 | 14.72 | 18.44 | mheidari-all | 64.94.95.115 |
| 78.85 | shadowsocks | 299.4 | 719.7 | 20.85 | 0.0 | 10.0 | 13.84 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 78.67 | vless | 273.8 | 654.6 | 21.44 | 0.0 | 10.0 | 9.81 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 78.63 | trojan | 266.8 | 559.7 | 21.6 | 0.0 | 10.0 | 14.72 | 18.44 | mheidari-all | 128.14.181.220 |
| 78.63 | http | 283.6 | 573.8 | 21.21 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |
| 78.41 | shadowsocks | 248.2 | 515.4 | 22.03 | 0.0 | 10.0 | 13.84 | 20.0 | Au1rxx-base64 | 209.38.142.23 |
| 78.39 | http | 298.5 | 616.7 | 20.87 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 78.12 | hysteria2 | 289.9 | 566.4 | 21.07 | 0.0 | 10.0 | 13.12 | 18.44 | mheidari-all | 150.241.102.127 |
| 77.95 | shadowsocks | 287.9 | 691.7 | 21.11 | 0.0 | 10.0 | 13.84 | 20.0 | Au1rxx-base64 | 159.89.112.218 |
| 77.68 | vless | 309.6 | 690.5 | 20.61 | 0.0 | 10.0 | 9.81 | 20.0 | Au1rxx-base64 | 216.152.147.28 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.966 | 713 | 1897 | prefer |
| zhangkai | 0.997 | 1.0 | 110 | 144 | prefer |
| mheidari-all | 0.845 | 0.766 | 338 | 22031 | prefer |
| Surfboard-tg-mixed | 0.835 | 0.76 | 104 | 6419 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 3031 | observe |
| DeltaKronecker-all | 0.324 | 0.375 | 8 | 6250 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 192 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5148 | observe |
| Epodonios-all | 0.255 | None | 0 | 7104 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3985 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7205 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5125 | observe |
| barry-far-vless | 0.255 | None | 0 | 5444 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4647 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 45 |
| geo | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 13 |
| speed | TimeoutError | - | 12 |
| speed | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 8 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
