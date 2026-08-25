# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-25 12:59:38 |
| 运行耗时 | 266.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 78389 |
| 去重后节点 | 22412 |
| TCP 可达 | 3000 |
| 真实可用 | 571 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22412 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 37.0 |
| probe | 54.5 |
| real_test | 125.4 |
| generate | 43.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48617 |
| shadowsocks | 10762 |
| vmess | 10462 |
| trojan | 6680 |
| hysteria2 | 1494 |
| http | 164 |
| shadowsocksr | 133 |
| socks | 67 |
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
| 79.69 | vless | 264.9 | 595.3 | 21.65 | 0.0 | 10.0 | 10.85 | 18.86 | Au1rxx-base64 | 15.204.97.209 |
| 79.67 | vless | 264.3 | 593.7 | 21.66 | 0.0 | 10.0 | 10.85 | 18.86 | Au1rxx-base64 | 15.204.97.197 |
| 78.67 | shadowsocks | 241.5 | 619.4 | 22.19 | 0.0 | 10.0 | 13.7 | 16.78 | mheidari-all | 156.146.38.170 |
| 77.75 | shadowsocks | 259.7 | 615.6 | 21.77 | 0.0 | 10.0 | 13.7 | 16.78 | mheidari-all | 23.150.248.20 |
| 77.61 | shadowsocks | 243.1 | 619.7 | 22.15 | 0.0 | 10.0 | 13.7 | 15.76 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.55 | trojan | 272.3 | 540.1 | 21.47 | 0.0 | 10.0 | 12.44 | 18.86 | Au1rxx-base64 | 35.91.251.124 |
| 76.28 | http | 458.8 | 1194.4 | 17.16 | 0.0 | 10.0 | 14.4 | 19.34 | zhangkai | 138.199.35.216 |
| 76.1 | vless | 330.9 | 708.2 | 20.12 | 0.0 | 10.0 | 10.85 | 18.86 | Au1rxx-base64 | 198.251.78.29 |
| 75.95 | http | 453.1 | 1172.2 | 17.29 | 0.0 | 10.0 | 14.4 | 19.34 | zhangkai | 138.199.35.198 |
| 75.88 | trojan | 275.4 | 594.3 | 21.4 | 0.0 | 10.0 | 12.44 | 18.86 | Au1rxx-base64 | 107.150.105.84 |
| 75.81 | shadowsocks | 290.5 | 599.3 | 21.05 | 0.0 | 10.0 | 13.7 | 18.86 | Au1rxx-base64 | 173.244.56.9 |
| 75.64 | shadowsocks | 246.2 | 636.0 | 22.08 | 0.0 | 10.0 | 13.7 | 18.86 | Au1rxx-base64 | 156.146.38.168 |
| 75.43 | shadowsocks | 300.5 | 705.4 | 20.82 | 0.0 | 10.0 | 13.7 | 15.76 | Surfboard-tg-mixed | 94.72.127.55 |
| 75.03 | shadowsocks | 271.3 | 530.9 | 21.5 | 0.0 | 10.0 | 13.7 | 18.86 | Au1rxx-base64 | 108.181.118.10 |
| 75.0 | hysteria2 | 328.8 | 741.3 | 20.17 | 0.0 | 10.0 | 13.64 | 16.78 | mheidari-all | 159.223.157.129 |
| 74.94 | shadowsocks | 310.1 | 306.9 | 20.6 | 3.49 | 9.77 | 13.7 | 18.86 | Au1rxx-base64 | 149.22.87.204 |
| 74.67 | shadowsocks | 322.6 | 706.5 | 20.31 | 0.0 | 10.0 | 13.7 | 18.86 | Au1rxx-base64 | 37.19.198.236 |
| 74.66 | vless | 269.1 | 606.8 | 21.55 | 0.0 | 10.0 | 10.85 | 18.86 | Au1rxx-base64 | 15.204.97.219 |
| 74.57 | shadowsocks | 301.0 | 734.5 | 20.81 | 0.0 | 10.0 | 13.7 | 15.76 | Surfboard-tg-mixed | 154.53.60.212 |
| 74.3 | shadowsocks | 307.4 | 638.5 | 20.66 | 0.0 | 10.0 | 13.7 | 18.86 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| mheidari-all | 0.955 | 0.886 | 70 | 14402 | prefer |
| Au1rxx-base64 | 0.925 | 0.863 | 388 | 1581 | prefer |
| Surfboard-tg-mixed | 0.82 | 0.743 | 152 | 6520 | prefer |
| DeltaKronecker-all | 0.784 | 0.712 | 52 | 6340 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 7010 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7084 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5377 | observe |
| barry-far-vless | 0.255 | None | 0 | 5577 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4119 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1589 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 18 |
| speed | TimeoutError | - | 12 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 9 |
| 204 | ClientOSError | - | 6 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
