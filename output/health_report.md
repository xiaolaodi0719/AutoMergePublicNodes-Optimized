# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-26 08:38:59 |
| 运行耗时 | 325.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80985 |
| 去重后节点 | 22458 |
| TCP 可达 | 3000 |
| 真实可用 | 890 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22458 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.3 |
| tcp | 31.3 |
| probe | 66.5 |
| real_test | 196.6 |
| generate | 24.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45251 |
| trojan | 14731 |
| vmess | 10155 |
| shadowsocks | 10121 |
| hysteria2 | 474 |
| http | 84 |
| shadowsocksr | 76 |
| socks | 70 |
| hysteria | 13 |
| tuic | 9 |
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
| 81.51 | shadowsocks | 203.6 | 506.8 | 23.06 | 0.0 | 10.0 | 13.45 | 19.5 | Au1rxx-base64 | 108.181.0.177 |
| 80.61 | shadowsocks | 242.7 | 604.5 | 22.16 | 0.0 | 10.0 | 13.45 | 19.5 | Au1rxx-base64 | 108.181.118.10 |
| 78.61 | trojan | 295.2 | 641.1 | 20.95 | 0.0 | 10.0 | 14.35 | 19.5 | Au1rxx-base64 | 163.245.196.68 |
| 77.83 | shadowsocks | 283.0 | 656.4 | 21.23 | 0.0 | 10.0 | 13.45 | 19.5 | Au1rxx-base64 | 156.146.38.168 |
| 77.22 | shadowsocks | 194.6 | 520.1 | 23.27 | 0.0 | 10.0 | 13.45 | 19.5 | Au1rxx-base64 | 173.244.56.6 |
| 77.16 | shadowsocks | 275.9 | 628.8 | 21.39 | 0.0 | 10.0 | 13.45 | 19.5 | Au1rxx-base64 | 156.146.38.170 |
| 77.01 | shadowsocks | 324.0 | 778.4 | 20.28 | 0.0 | 10.0 | 13.45 | 19.5 | Au1rxx-base64 | 156.146.38.167 |
| 76.69 | shadowsocks | 281.1 | 595.4 | 21.27 | 0.0 | 10.0 | 13.45 | 19.5 | Au1rxx-base64 | 149.22.95.183 |
| 76.09 | trojan | 335.1 | 337.7 | 20.02 | 2.34 | 9.91 | 14.35 | 19.5 | Au1rxx-base64 | 95.85.94.165 |
| 75.94 | trojan | 336.5 | 339.7 | 19.99 | 2.26 | 9.91 | 14.35 | 19.5 | Au1rxx-base64 | 31.223.184.109 |
| 75.45 | trojan | 342.2 | 349.9 | 19.86 | 1.88 | 9.91 | 14.35 | 19.5 | Au1rxx-base64 | 95.85.94.90 |
| 75.36 | trojan | 338.4 | 344.6 | 19.94 | 2.08 | 9.5 | 14.35 | 19.5 | Au1rxx-base64 | moved-osprey.rooster465.autos |
| 74.07 | trojan | 336.8 | 335.6 | 19.98 | 2.42 | 9.91 | 14.35 | 19.5 | Au1rxx-base64 | 31.223.184.172 |
| 73.71 | shadowsocks | 345.7 | 703.1 | 19.78 | 0.0 | 10.0 | 13.45 | 19.5 | Au1rxx-base64 | 198.98.53.130 |
| 73.69 | trojan | 351.9 | 390.5 | 19.63 | 0.36 | 9.91 | 14.35 | 19.5 | Au1rxx-base64 | 95.85.94.148 |
| 73.63 | shadowsocks | 305.8 | 360.0 | 20.7 | 1.5 | 9.77 | 13.45 | 19.5 | Au1rxx-base64 | 149.22.87.240 |
| 73.53 | shadowsocks | 308.7 | 360.8 | 20.63 | 1.47 | 9.75 | 13.45 | 19.5 | Au1rxx-base64 | 149.22.87.204 |
| 73.38 | trojan | 400.5 | 795.0 | 18.51 | 0.0 | 10.0 | 14.35 | 19.5 | Au1rxx-base64 | 153.75.250.171 |
| 73.18 | shadowsocks | 352.8 | 740.9 | 19.61 | 0.0 | 10.0 | 13.45 | 19.5 | Au1rxx-base64 | 37.19.198.160 |
| 73.15 | trojan | 361.2 | 410.0 | 19.42 | 0.0 | 9.89 | 14.35 | 19.5 | Au1rxx-base64 | 95.85.94.199 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 1.0 | 76 | 86 | prefer |
| Au1rxx-base64 | 0.931 | 0.875 | 457 | 1442 | prefer |
| mheidari-all | 0.927 | 0.851 | 188 | 17285 | prefer |
| Surfboard-tg-mixed | 0.697 | 0.619 | 147 | 5458 | observe |
| DeltaKronecker-all | 0.556 | 0.476 | 338 | 5950 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| Pawdroid | 0.255 | 1.0 | 1 | 10 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6596 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4178 | observe |
| barry-far-vless | 0.255 | None | 0 | 4874 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4980 | observe |
| nscl5-all | 0.255 | None | 0 | 2896 | observe |
| xiaoji235-airport-v2ray-all | 0.24 | None | 0 | 1624 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 114 |
| 204 | ProxyError | - | 50 |
| geo | ClientOSError | - | 37 |
| speed | ClientOSError | - | 37 |
| cn-block | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 22 |
| speed | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 8 |
| speed | ProxyError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
