# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-11 13:20:23 |
| 运行耗时 | 244.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 84566 |
| 去重后节点 | 24401 |
| TCP 可达 | 3000 |
| 真实可用 | 527 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24401 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.3 |
| tcp | 35.9 |
| probe | 50.1 |
| real_test | 121.9 |
| generate | 28.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48829 |
| vmess | 13380 |
| trojan | 10675 |
| shadowsocks | 10012 |
| hysteria2 | 1321 |
| http | 159 |
| shadowsocksr | 74 |
| socks | 69 |
| anytls | 26 |
| hysteria | 13 |
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
| 82.74 | trojan | 235.5 | 544.0 | 22.33 | 0.0 | 10.0 | 13.51 | 19.4 | Au1rxx-base64 | 44.246.163.102 |
| 82.35 | trojan | 234.2 | 541.1 | 22.36 | 0.0 | 10.0 | 13.51 | 19.4 | Au1rxx-base64 | 44.242.235.129 |
| 82.08 | vless | 184.6 | 480.6 | 23.51 | 0.0 | 10.0 | 9.17 | 19.4 | Au1rxx-base64 | 179.253.240.24 |
| 82.05 | vless | 185.5 | 476.4 | 23.48 | 0.0 | 10.0 | 9.17 | 19.4 | Au1rxx-base64 | 179.255.148.66 |
| 82.02 | vless | 186.8 | 485.3 | 23.45 | 0.0 | 10.0 | 9.17 | 19.4 | Au1rxx-base64 | 186.241.106.97 |
| 81.88 | shadowsocks | 235.9 | 556.5 | 22.32 | 0.0 | 10.0 | 14.16 | 19.4 | Au1rxx-base64 | 149.22.95.183 |
| 81.86 | trojan | 273.4 | 659.1 | 21.45 | 0.0 | 10.0 | 13.51 | 19.4 | Au1rxx-base64 | 44.244.3.114 |
| 81.69 | vless | 201.0 | 496.4 | 23.12 | 0.0 | 10.0 | 9.17 | 19.4 | Au1rxx-base64 | 167.17.68.205 |
| 81.42 | shadowsocks | 234.0 | 598.5 | 22.36 | 0.0 | 10.0 | 14.16 | 19.4 | Au1rxx-base64 | 108.181.0.177 |
| 81.02 | shadowsocks | 229.8 | 506.0 | 22.46 | 0.0 | 10.0 | 14.16 | 19.4 | Au1rxx-base64 | 173.244.56.9 |
| 81.0 | shadowsocks | 273.7 | 675.5 | 21.44 | 0.0 | 10.0 | 14.16 | 19.4 | Au1rxx-base64 | 173.244.56.6 |
| 80.78 | vless | 240.7 | 620.1 | 22.21 | 0.0 | 10.0 | 9.17 | 19.4 | Au1rxx-base64 | 70.39.198.93 |
| 80.44 | shadowsocks | 276.5 | 751.0 | 21.38 | 0.0 | 10.0 | 14.16 | 19.4 | Au1rxx-base64 | 70.39.178.204 |
| 80.35 | http | 380.1 | 1052.6 | 18.98 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.212 |
| 80.31 | http | 381.8 | 1050.8 | 18.94 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.215 |
| 80.31 | http | 381.9 | 1059.1 | 18.94 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.208 |
| 80.28 | http | 382.9 | 1058.8 | 18.91 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.206 |
| 80.2 | http | 386.4 | 1064.9 | 18.83 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.220 |
| 80.19 | http | 387.1 | 1069.8 | 18.82 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.214 |
| 80.18 | http | 387.3 | 1072.4 | 18.81 | 0.0 | 10.0 | 14.71 | 19.66 | zhangkai | 138.199.35.211 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.903 | 0.844 | 392 | 1501 | prefer |
| Surfboard-tg-mixed | 0.784 | 0.709 | 79 | 6195 | prefer |
| mheidari-all | 0.543 | 0.615 | 13 | 20194 | observe |
| DeltaKronecker-all | 0.324 | 0.375 | 8 | 5522 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5419 | observe |
| Epodonios-all | 0.255 | None | 0 | 6769 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7602 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5048 | observe |
| barry-far-vless | 0.255 | None | 0 | 5245 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5209 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.239 | None | 0 | 1607 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 26 |
| geo | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 16 |
| speed | ClientOSError | - | 13 |
| geo | TimeoutError | - | 6 |
| 204 | ProxyError | - | 6 |
| cn-block | TimeoutError | - | 5 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
