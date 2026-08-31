# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-31 04:53:22 |
| 运行耗时 | 309.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 78971 |
| 去重后节点 | 21904 |
| TCP 可达 | 3000 |
| 真实可用 | 657 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21904 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.5 |
| tcp | 34.7 |
| probe | 89.0 |
| real_test | 151.8 |
| generate | 26.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49458 |
| vmess | 10820 |
| shadowsocks | 10176 |
| trojan | 6583 |
| hysteria2 | 1543 |
| http | 168 |
| shadowsocksr | 128 |
| socks | 85 |
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
| 84.53 | vless | 249.4 | 653.0 | 22.0 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 84.21 | vless | 245.5 | 641.1 | 22.1 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 84.09 | vless | 268.4 | 698.3 | 21.56 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 38.77.133.141 |
| 84.06 | vless | 270.0 | 660.3 | 21.53 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 172.105.104.54 |
| 84.02 | vless | 271.8 | 642.3 | 21.49 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 195.211.99.45 |
| 83.6 | vless | 285.7 | 690.3 | 21.16 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 169.40.42.52 |
| 83.36 | vless | 279.3 | 648.4 | 21.31 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 169.40.42.182 |
| 83.27 | vless | 269.9 | 639.0 | 21.53 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 83.27 | vless | 291.8 | 755.9 | 21.02 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 169.40.42.89 |
| 82.63 | hysteria2 | 239.7 | 624.9 | 22.23 | 0.0 | 10.0 | 13.5 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 82.48 | vless | 338.2 | 907.3 | 19.95 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 79.127.243.217 |
| 81.87 | shadowsocks | 236.5 | 639.7 | 22.3 | 0.0 | 10.0 | 13.57 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.8 | shadowsocks | 239.5 | 647.8 | 22.23 | 0.0 | 10.0 | 13.57 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 81.74 | vless | 370.2 | 943.0 | 19.21 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 169.40.42.184 |
| 81.67 | shadowsocks | 245.2 | 660.1 | 22.1 | 0.0 | 10.0 | 13.57 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 81.62 | vless | 352.9 | 819.9 | 19.61 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 169.40.42.15 |
| 81.55 | vless | 343.7 | 916.6 | 19.82 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 169.40.42.229 |
| 81.42 | vless | 356.7 | 949.1 | 19.52 | 0.0 | 10.0 | 12.53 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 81.19 | vless | 297.7 | 818.0 | 20.89 | 0.0 | 8.87 | 12.53 | 20.0 | Au1rxx-base64 | using.neobo-tooth.ru |
| 80.95 | shadowsocks | 276.2 | 758.5 | 21.38 | 0.0 | 10.0 | 13.57 | 20.0 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | 0.925 | 322 | 1804 | prefer |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.787 | 0.709 | 220 | 6765 | prefer |
| mheidari-all | 0.594 | 0.556 | 18 | 14559 | observe |
| DeltaKronecker-all | 0.565 | 0.485 | 342 | 5576 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4762 | observe |
| Epodonios-all | 0.335 | 1.0 | 1 | 7271 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7850 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5673 | observe |
| barry-far-vless | 0.255 | None | 0 | 5858 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4041 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 109 |
| geo | ClientOSError | - | 53 |
| speed | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 22 |
| speed | ClientOSError | - | 21 |
| 204 | TimeoutError | - | 20 |
| 204 | ProxyError | - | 10 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
