# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 11:40:27 |
| 运行耗时 | 510.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96970 |
| 去重后节点 | 26321 |
| TCP 可达 | 3000 |
| 真实可用 | 316 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26321 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 43.3 |
| probe | 297.4 |
| real_test | 126.6 |
| generate | 34.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58827 |
| vmess | 15168 |
| shadowsocks | 11416 |
| trojan | 8990 |
| hysteria2 | 1643 |
| http | 635 |
| shadowsocksr | 172 |
| socks | 73 |
| anytls | 24 |
| hysteria | 15 |
| tuic | 7 |

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
| 84.24 | hysteria2 | 228.5 | 590.9 | 22.49 | 0.0 | 9.02 | 14.29 | 19.44 | Au1rxx-base64 | 66.94.121.46 |
| 79.42 | shadowsocks | 236.0 | 553.8 | 22.32 | 0.0 | 10.0 | 14.03 | 17.18 | Surfboard-tg-mixed | 173.244.56.9 |
| 78.82 | shadowsocks | 244.7 | 629.7 | 22.11 | 0.0 | 10.0 | 14.03 | 17.18 | Surfboard-tg-mixed | 108.181.0.177 |
| 77.23 | vless | 196.5 | 512.6 | 23.23 | 0.0 | 8.97 | 5.59 | 19.44 | Au1rxx-base64 | 172.235.43.210 |
| 76.85 | vless | 214.7 | 537.6 | 22.81 | 0.0 | 9.01 | 5.59 | 19.44 | Au1rxx-base64 | 195.123.240.65 |
| 76.33 | vless | 241.4 | 587.5 | 22.19 | 0.0 | 9.11 | 5.59 | 19.44 | Au1rxx-base64 | 15.204.97.216 |
| 76.31 | vless | 199.2 | 522.6 | 23.17 | 0.0 | 9.11 | 5.59 | 19.44 | Au1rxx-base64 | 192.3.247.109 |
| 75.33 | hysteria2 | 301.4 | 455.6 | 20.8 | 0.0 | 7.84 | 14.29 | 19.44 | Au1rxx-base64 | open.w2m.ink |
| 74.91 | hysteria2 | 401.4 | 880.8 | 18.49 | 0.0 | 8.97 | 14.29 | 19.44 | Au1rxx-base64 | 159.223.157.129 |
| 72.79 | vless | 195.5 | 486.0 | 23.25 | 0.0 | 9.01 | 5.59 | 19.44 | Au1rxx-base64 | 172.64.32.108 |
| 72.77 | vless | 174.9 | 478.9 | 23.73 | 0.0 | 9.01 | 5.59 | 19.44 | Au1rxx-base64 | 137.175.82.40 |
| 72.48 | vless | 221.5 | 491.7 | 22.65 | 0.0 | 9.05 | 5.59 | 19.44 | Au1rxx-base64 | 172.64.158.146 |
| 72.46 | vless | 401.0 | 962.6 | 18.49 | 0.0 | 8.94 | 5.59 | 19.44 | Au1rxx-base64 | 51.81.203.63 |
| 72.33 | shadowsocks | 314.8 | 352.1 | 20.49 | 1.79 | 8.93 | 14.03 | 19.44 | Au1rxx-base64 | 84.247.155.196 |
| 71.97 | vless | 377.1 | 956.5 | 19.05 | 0.0 | 8.94 | 5.59 | 19.44 | Au1rxx-base64 | 136.117.218.86 |
| 71.65 | http | 200.4 | 513.7 | 23.14 | 0.0 | 10.0 | 9.09 | 12.42 | ermaozi | 138.199.35.201 |
| 71.63 | http | 201.1 | 513.7 | 23.12 | 0.0 | 10.0 | 9.09 | 12.42 | ermaozi | 138.199.35.203 |
| 71.57 | http | 203.7 | 516.3 | 23.06 | 0.0 | 10.0 | 9.09 | 12.42 | ermaozi | 138.199.35.210 |
| 71.54 | http | 205.3 | 522.8 | 23.03 | 0.0 | 10.0 | 9.09 | 12.42 | ermaozi | 138.199.35.209 |
| 71.54 | http | 205.3 | 535.7 | 23.03 | 0.0 | 10.0 | 9.09 | 12.42 | ermaozi | 138.199.35.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | 0.916 | 202 | 1624 | prefer |
| mheidari-all | 0.901 | 0.831 | 65 | 22444 | prefer |
| Surfboard-tg-mixed | 0.774 | 0.7 | 60 | 7280 | prefer |
| ermaozi | 0.666 | 0.659 | 44 | 338 | observe |
| DeltaKronecker-all | 0.446 | 0.625 | 8 | 5452 | observe |
| ermaozi-get_subscribe | 0.269 | 1.0 | 1 | 359 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7869 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9069 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5801 | observe |
| barry-far-vless | 0.255 | None | 0 | 6140 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4324 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1624 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 19 |
| 204 | ProxyError | - | 17 |
| cn-block | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| speed | TimeoutError | - | 3 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
