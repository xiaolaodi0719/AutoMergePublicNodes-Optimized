# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-25 18:50:22 |
| 运行耗时 | 282.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 78004 |
| 去重后节点 | 22568 |
| TCP 可达 | 3000 |
| 真实可用 | 584 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22568 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 35.8 |
| probe | 58.3 |
| real_test | 139.8 |
| generate | 40.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48801 |
| shadowsocks | 10605 |
| vmess | 10458 |
| trojan | 6418 |
| hysteria2 | 1341 |
| http | 164 |
| shadowsocksr | 132 |
| socks | 75 |
| hysteria | 7 |
| tuic | 3 |

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
| 83.99 | http | 194.8 | 497.3 | 23.27 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.198 |
| 83.58 | http | 203.0 | 516.2 | 23.08 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.216 |
| 82.63 | vless | 226.7 | 564.7 | 22.53 | 0.0 | 10.0 | 11.6 | 18.5 | Au1rxx-base64 | 15.204.97.209 |
| 80.83 | shadowsocks | 206.4 | 497.3 | 23.0 | 0.0 | 10.0 | 13.58 | 18.5 | Au1rxx-base64 | 94.72.127.55 |
| 80.74 | trojan | 193.4 | 500.4 | 23.3 | 0.0 | 10.0 | 11.94 | 18.5 | Au1rxx-base64 | 14.1.28.76 |
| 80.58 | shadowsocks | 244.3 | 557.8 | 22.12 | 0.0 | 10.0 | 13.58 | 19.1 | mheidari-all | 173.244.56.6 |
| 80.53 | shadowsocks | 230.3 | 561.1 | 22.45 | 0.0 | 10.0 | 13.58 | 18.5 | Au1rxx-base64 | 154.53.60.212 |
| 80.51 | vless | 318.3 | 843.3 | 20.41 | 0.0 | 10.0 | 11.6 | 18.5 | Au1rxx-base64 | 15.204.97.195 |
| 80.51 | vless | 318.4 | 833.1 | 20.41 | 0.0 | 10.0 | 11.6 | 18.5 | Au1rxx-base64 | 15.204.97.197 |
| 80.26 | vless | 199.4 | 521.4 | 23.16 | 0.0 | 10.0 | 11.6 | 18.5 | Au1rxx-base64 | 166.88.186.151 |
| 80.08 | shadowsocks | 231.1 | 581.1 | 22.43 | 0.0 | 10.0 | 13.58 | 18.5 | Au1rxx-base64 | 94.72.127.58 |
| 79.76 | trojan | 211.0 | 549.7 | 22.89 | 0.0 | 10.0 | 11.94 | 18.5 | Au1rxx-base64 | 107.150.105.84 |
| 79.63 | vless | 253.3 | 602.2 | 21.91 | 0.0 | 10.0 | 11.6 | 18.5 | Au1rxx-base64 | 23.172.40.60 |
| 78.79 | trojan | 292.6 | 710.5 | 21.0 | 0.0 | 10.0 | 11.94 | 18.5 | Au1rxx-base64 | 35.91.251.124 |
| 77.3 | shadowsocks | 266.2 | 602.0 | 21.62 | 0.0 | 10.0 | 13.58 | 19.1 | mheidari-all | 149.22.95.183 |
| 77.11 | shadowsocks | 271.1 | 275.4 | 21.5 | 4.67 | 9.95 | 13.58 | 18.5 | Au1rxx-base64 | 149.22.87.241 |
| 76.15 | http | 345.2 | 617.1 | 19.79 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 38.28.193.188 |
| 76.04 | shadowsocks | 321.9 | 787.0 | 20.33 | 0.0 | 10.0 | 13.58 | 19.1 | mheidari-all | 173.244.56.9 |
| 76.02 | vless | 365.3 | 667.6 | 19.32 | 0.0 | 10.0 | 11.6 | 18.5 | Au1rxx-base64 | 69.63.193.78 |
| 75.89 | trojan | 187.1 | 483.8 | 23.45 | 0.0 | 10.0 | 11.94 | 18.5 | Au1rxx-base64 | kuso153.pacemakere.com |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.915 | 0.856 | 424 | 1502 | prefer |
| DeltaKronecker-all | 0.871 | 0.805 | 41 | 6340 | prefer |
| Surfboard-tg-mixed | 0.781 | 0.704 | 152 | 6487 | prefer |
| mheidari-all | 0.774 | 0.699 | 83 | 14446 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 6936 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7007 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5327 | observe |
| barry-far-vless | 0.255 | None | 0 | 5601 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4119 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1505 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 49 |
| 204 | TimeoutError | - | 23 |
| geo | TimeoutError | - | 20 |
| 204 | ProxyError | - | 12 |
| cn-block | TimeoutError | - | 11 |
| geo | ClientOSError | - | 8 |
| speed | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
