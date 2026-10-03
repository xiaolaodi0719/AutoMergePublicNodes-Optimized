# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 11:32:34 |
| 运行耗时 | 540.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98931 |
| 去重后节点 | 27239 |
| TCP 可达 | 3000 |
| 真实可用 | 362 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27239 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.3 |
| tcp | 47.7 |
| probe | 223.2 |
| real_test | 179.4 |
| generate | 82.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60581 |
| vmess | 15500 |
| shadowsocks | 11388 |
| trojan | 9034 |
| hysteria2 | 1611 |
| http | 521 |
| shadowsocksr | 171 |
| socks | 66 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 12 |

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
| 83.97 | hysteria2 | 272.3 | 753.3 | 21.48 | 0.0 | 10.0 | 14.29 | 19.2 | Au1rxx-base64 | 192.255.128.123 |
| 82.31 | hysteria2 | 294.7 | 593.0 | 20.96 | 0.0 | 10.0 | 14.29 | 19.2 | Au1rxx-base64 | 66.94.121.46 |
| 80.79 | hysteria2 | 276.4 | 255.4 | 21.38 | 5.42 | 7.72 | 14.29 | 19.2 | Au1rxx-base64 | open.2ml.bid |
| 80.31 | vless | 195.0 | 513.1 | 23.26 | 0.0 | 10.0 | 7.85 | 19.2 | Au1rxx-base64 | 172.233.139.46 |
| 80.21 | vless | 199.6 | 527.2 | 23.16 | 0.0 | 10.0 | 7.85 | 19.2 | Au1rxx-base64 | 172.235.43.210 |
| 79.98 | shadowsocks | 259.9 | 639.7 | 21.76 | 0.0 | 10.0 | 13.02 | 19.2 | Au1rxx-base64 | 156.146.38.170 |
| 79.62 | shadowsocks | 266.5 | 648.4 | 21.61 | 0.0 | 10.0 | 13.02 | 19.2 | Au1rxx-base64 | 156.146.38.167 |
| 79.09 | shadowsocks | 212.1 | 531.1 | 22.87 | 0.0 | 10.0 | 13.02 | 19.2 | Au1rxx-base64 | 173.244.56.9 |
| 78.95 | shadowsocks | 218.1 | 520.3 | 22.73 | 0.0 | 10.0 | 13.02 | 19.2 | Au1rxx-base64 | 173.244.56.6 |
| 78.9 | vless | 256.1 | 630.0 | 21.85 | 0.0 | 10.0 | 7.85 | 19.2 | Au1rxx-base64 | 137.175.82.40 |
| 78.42 | vless | 233.4 | 590.7 | 22.37 | 0.0 | 10.0 | 7.85 | 19.2 | Au1rxx-base64 | 38.246.229.58 |
| 78.07 | shadowsocks | 256.2 | 622.3 | 21.85 | 0.0 | 10.0 | 13.02 | 19.2 | Au1rxx-base64 | 156.146.38.169 |
| 77.76 | vless | 193.1 | 506.9 | 23.31 | 0.0 | 10.0 | 7.85 | 19.2 | Au1rxx-base64 | 172.235.38.85 |
| 77.41 | shadowsocks | 219.7 | 597.1 | 22.69 | 0.0 | 10.0 | 13.02 | 19.2 | Au1rxx-base64 | 103.214.109.197 |
| 76.97 | http | 202.3 | 523.9 | 23.09 | 0.0 | 10.0 | 11.54 | 15.34 | ermaozi | 138.199.35.216 |
| 76.53 | vless | 272.5 | 607.5 | 21.47 | 0.0 | 10.0 | 7.85 | 19.2 | Au1rxx-base64 | 15.204.97.216 |
| 76.27 | vless | 193.6 | 502.0 | 23.3 | 0.0 | 10.0 | 7.85 | 15.12 | Surfboard-tg-mixed | 2.27.160.4 |
| 75.59 | shadowsocks | 290.5 | 300.0 | 21.05 | 3.75 | 9.83 | 13.02 | 19.2 | Au1rxx-base64 | 149.22.87.241 |
| 75.33 | hysteria2 | 361.2 | 622.4 | 19.42 | 0.0 | 9.27 | 14.29 | 19.2 | Au1rxx-base64 | open.w2m.ink |
| 75.02 | http | 200.5 | 514.7 | 23.14 | 0.0 | 10.0 | 11.54 | 15.34 | ermaozi | 138.199.35.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.938 | 0.871 | 241 | 1754 | prefer |
| Surfboard-tg-mixed | 0.811 | 0.735 | 117 | 7251 | prefer |
| mheidari-all | 0.809 | 0.737 | 57 | 23264 | prefer |
| ermaozi | 0.564 | 0.542 | 24 | 645 | observe |
| DeltaKronecker-all | 0.53 | 0.7 | 10 | 5207 | observe |
| ermaozi-get_subscribe | 0.332 | 1.0 | 2 | 516 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5192 | observe |
| Epodonios-all | 0.255 | None | 0 | 7748 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9363 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5966 | observe |
| barry-far-vless | 0.255 | None | 0 | 6206 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4335 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 20 |
| speed | TimeoutError | - | 12 |
| 204 | ProxyConnectionError | - | 10 |
| geo | TimeoutError | - | 9 |
| 204 | ProxyError | - | 5 |
| speed | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
