# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-04 14:31:34 |
| 运行耗时 | 257.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86444 |
| 去重后节点 | 24261 |
| TCP 可达 | 3000 |
| 真实可用 | 494 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24261 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 20.2 |
| geo | 1.4 |
| tcp | 37.1 |
| probe | 53.5 |
| real_test | 114.8 |
| generate | 30.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52797 |
| vmess | 12971 |
| shadowsocks | 10050 |
| trojan | 9369 |
| hysteria2 | 1008 |
| socks | 79 |
| shadowsocksr | 68 |
| http | 63 |
| hysteria | 19 |
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
| 79.23 | http | 248.3 | 552.1 | 22.03 | 0.0 | 10.0 | 13.48 | 18.04 | zhangkai | 138.199.35.200 |
| 78.96 | http | 243.0 | 541.1 | 22.15 | 0.0 | 10.0 | 13.48 | 18.04 | zhangkai | 138.199.35.214 |
| 78.58 | trojan | 284.7 | 717.5 | 21.19 | 0.0 | 10.0 | 13.73 | 16.66 | Au1rxx-base64 | 64.94.95.114 |
| 78.56 | trojan | 285.5 | 717.5 | 21.17 | 0.0 | 10.0 | 13.73 | 16.66 | Au1rxx-base64 | 64.94.95.115 |
| 78.53 | trojan | 286.8 | 721.4 | 21.14 | 0.0 | 10.0 | 13.73 | 16.66 | Au1rxx-base64 | 64.94.95.117 |
| 78.3 | http | 277.2 | 643.0 | 21.36 | 0.0 | 10.0 | 13.48 | 18.04 | zhangkai | 138.199.35.199 |
| 77.92 | shadowsocks | 242.5 | 616.3 | 22.17 | 0.0 | 10.0 | 13.09 | 16.66 | Au1rxx-base64 | 156.146.38.168 |
| 77.88 | shadowsocks | 243.9 | 621.8 | 22.13 | 0.0 | 10.0 | 13.09 | 16.66 | Au1rxx-base64 | 156.146.38.170 |
| 77.68 | http | 306.6 | 732.6 | 20.68 | 0.0 | 10.0 | 13.48 | 18.04 | zhangkai | 138.199.35.219 |
| 77.63 | http | 286.6 | 671.6 | 21.14 | 0.0 | 10.0 | 13.48 | 18.04 | zhangkai | 138.199.35.217 |
| 77.62 | http | 279.1 | 637.1 | 21.32 | 0.0 | 10.0 | 13.48 | 18.04 | zhangkai | 138.199.35.198 |
| 77.09 | trojan | 288.0 | 727.7 | 21.11 | 0.0 | 10.0 | 13.73 | 16.66 | Au1rxx-base64 | 64.94.95.118 |
| 76.53 | hysteria2 | 272.6 | 318.1 | 21.47 | 3.07 | 9.78 | 13.5 | 16.66 | Au1rxx-base64 | 45.76.202.45 |
| 74.79 | shadowsocks | 247.8 | 640.2 | 22.04 | 0.0 | 10.0 | 13.09 | 16.66 | Au1rxx-base64 | 156.146.38.169 |
| 74.42 | shadowsocks | 253.8 | 529.0 | 21.9 | 0.0 | 10.0 | 13.09 | 16.66 | Au1rxx-base64 | 108.181.0.177 |
| 74.16 | vless | 333.4 | 840.8 | 20.06 | 0.0 | 10.0 | 7.84 | 16.66 | Au1rxx-base64 | 64.49.38.6 |
| 74.1 | shadowsocks | 267.3 | 564.8 | 21.59 | 0.0 | 10.0 | 13.09 | 16.66 | Au1rxx-base64 | 173.244.56.6 |
| 74.1 | hysteria2 | 352.7 | 842.1 | 19.61 | 0.0 | 10.0 | 13.5 | 16.66 | Au1rxx-base64 | 138.124.68.188 |
| 73.18 | shadowsocks | 279.6 | 552.7 | 21.31 | 0.0 | 10.0 | 13.09 | 16.66 | Au1rxx-base64 | 108.181.118.10 |
| 73.1 | http | 513.2 | 1333.9 | 15.9 | 0.0 | 10.0 | 13.48 | 18.04 | zhangkai | 138.199.35.207 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.947 | 0.962 | 52 | 72 | prefer |
| Au1rxx-base64 | 0.903 | 0.837 | 478 | 1684 | prefer |
| mheidari-all | 0.524 | 0.443 | 70 | 20302 | observe |
| Surfboard-tg-mixed | 0.45 | 0.5 | 12 | 5397 | observe |
| DeltaKronecker-all | 0.407 | 0.455 | 11 | 5788 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 58 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5251 | observe |
| Epodonios-all | 0.255 | None | 0 | 5995 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7036 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4315 | observe |
| barry-far-vless | 0.255 | None | 0 | 4658 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5110 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5127 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 23 |
| geo | ClientOSError | - | 22 |
| speed | TimeoutError | - | 17 |
| speed | ClientOSError | - | 14 |
| 204 | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 6 |
| 204 | ProxyError | - | 5 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
