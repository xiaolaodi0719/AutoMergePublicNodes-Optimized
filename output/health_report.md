# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 21:08:49 |
| 运行耗时 | 706.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84956 |
| 去重后节点 | 22773 |
| TCP 可达 | 3000 |
| 真实可用 | 533 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22773 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.5 |
| tcp | 38.9 |
| probe | 298.7 |
| real_test | 281.6 |
| generate | 79.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52475 |
| vmess | 12061 |
| shadowsocks | 9736 |
| trojan | 8295 |
| hysteria2 | 1614 |
| http | 570 |
| shadowsocksr | 128 |
| socks | 54 |
| hysteria | 11 |
| tuic | 8 |
| anytls | 4 |

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
| 80.82 | shadowsocks | 265.5 | 655.8 | 21.63 | 0.0 | 10.0 | 13.51 | 19.68 | Au1rxx-base64 | 37.19.198.243 |
| 80.3 | shadowsocks | 251.0 | 615.5 | 21.97 | 0.0 | 10.0 | 13.51 | 19.68 | Au1rxx-base64 | 156.146.38.168 |
| 79.88 | shadowsocks | 306.3 | 782.9 | 20.69 | 0.0 | 10.0 | 13.51 | 19.68 | Au1rxx-base64 | 198.98.53.130 |
| 79.62 | shadowsocks | 283.3 | 691.9 | 21.22 | 0.0 | 10.0 | 13.51 | 19.68 | Au1rxx-base64 | 37.19.198.244 |
| 79.6 | shadowsocks | 261.8 | 640.4 | 21.72 | 0.0 | 10.0 | 13.51 | 19.68 | Au1rxx-base64 | 156.146.38.170 |
| 79.39 | shadowsocks | 274.2 | 616.6 | 21.43 | 0.0 | 10.0 | 13.51 | 19.68 | Au1rxx-base64 | 23.150.248.20 |
| 79.37 | hysteria2 | 266.1 | 575.4 | 21.62 | 0.0 | 10.0 | 12.27 | 19.68 | Au1rxx-base64 | 66.94.121.46 |
| 78.57 | shadowsocks | 341.2 | 896.1 | 19.88 | 0.0 | 10.0 | 13.51 | 19.68 | Au1rxx-base64 | 15.204.246.189 |
| 77.99 | vless | 360.6 | 834.6 | 19.43 | 0.0 | 10.0 | 9.85 | 19.68 | Au1rxx-base64 | 169.40.42.52 |
| 77.86 | hysteria2 | 270.7 | 665.0 | 21.51 | 0.0 | 10.0 | 12.27 | 15.18 | Surfboard-tg-mixed | 159.223.157.129 |
| 77.79 | vless | 350.7 | 860.7 | 19.66 | 0.0 | 10.0 | 9.85 | 19.68 | Au1rxx-base64 | 169.40.42.90 |
| 77.64 | vless | 365.5 | 853.5 | 19.32 | 0.0 | 10.0 | 9.85 | 19.68 | Au1rxx-base64 | 66.70.179.198 |
| 77.5 | vless | 294.3 | 729.2 | 20.97 | 0.0 | 10.0 | 9.85 | 19.68 | Au1rxx-base64 | 47.253.226.114 |
| 77.41 | trojan | 264.0 | 613.3 | 21.67 | 0.0 | 10.0 | 11.25 | 19.68 | Au1rxx-base64 | 64.94.95.114 |
| 77.27 | vless | 315.6 | 714.2 | 20.47 | 0.0 | 10.0 | 9.85 | 19.68 | Au1rxx-base64 | 169.40.42.184 |
| 76.89 | vless | 272.9 | 704.8 | 21.46 | 0.0 | 10.0 | 9.85 | 19.68 | Au1rxx-base64 | 130.94.115.231 |
| 76.72 | vless | 402.3 | 914.0 | 18.47 | 0.0 | 10.0 | 9.85 | 19.68 | Au1rxx-base64 | 169.40.42.182 |
| 76.38 | vless | 371.2 | 869.1 | 19.18 | 0.0 | 10.0 | 9.85 | 19.68 | Au1rxx-base64 | 169.40.42.224 |
| 76.33 | vless | 365.4 | 859.6 | 19.32 | 0.0 | 10.0 | 9.85 | 19.68 | Au1rxx-base64 | 169.40.42.179 |
| 76.3 | trojan | 268.1 | 614.4 | 21.57 | 0.0 | 10.0 | 11.25 | 19.68 | Au1rxx-base64 | 64.94.95.115 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | 0.901 | 303 | 1700 | prefer |
| DeltaKronecker-all | 0.913 | 0.864 | 22 | 6097 | prefer |
| Surfboard-tg-mixed | 0.827 | 0.75 | 172 | 7370 | prefer |
| mheidari-all | 0.826 | 0.75 | 116 | 16416 | prefer |
| ermaozi | 0.711 | 0.706 | 34 | 409 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7999 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8578 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6089 | observe |
| barry-far-vless | 0.255 | None | 0 | 6497 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1700 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 24 |
| geo | ClientOSError | - | 23 |
| 204 | ProxyError | - | 18 |
| cn-block | ClientOSError | - | 9 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| speed | TimeoutError | - | 4 |
| geo | ProxyError | - | 2 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
