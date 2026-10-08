# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-08 05:38:45 |
| 运行耗时 | 762.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99165 |
| 去重后节点 | 27686 |
| TCP 可达 | 3000 |
| 真实可用 | 477 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27686 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 46.1 |
| probe | 277.7 |
| real_test | 346.6 |
| generate | 82.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57994 |
| vmess | 15811 |
| shadowsocks | 11970 |
| trojan | 10834 |
| hysteria2 | 1571 |
| http | 676 |
| shadowsocksr | 167 |
| socks | 88 |
| anytls | 29 |
| hysteria | 16 |
| tuic | 9 |

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
| 84.28 | vless | 172.3 | 459.9 | 23.79 | 0.0 | 10.0 | 11.63 | 18.86 | Au1rxx-base64 | 137.175.82.40 |
| 84.14 | vless | 178.2 | 478.7 | 23.65 | 0.0 | 10.0 | 11.63 | 18.86 | Au1rxx-base64 | 47.251.108.158 |
| 83.27 | vless | 215.9 | 537.3 | 22.78 | 0.0 | 10.0 | 11.63 | 18.86 | Au1rxx-base64 | 195.123.240.65 |
| 82.93 | vless | 230.8 | 565.2 | 22.44 | 0.0 | 10.0 | 11.63 | 18.86 | Au1rxx-base64 | 15.204.97.216 |
| 82.91 | vless | 231.6 | 564.1 | 22.42 | 0.0 | 10.0 | 11.63 | 18.86 | Au1rxx-base64 | 15.204.97.197 |
| 82.71 | vless | 239.9 | 623.6 | 22.22 | 0.0 | 10.0 | 11.63 | 18.86 | Au1rxx-base64 | 107.173.237.146 |
| 81.88 | hysteria2 | 249.6 | 570.5 | 22.0 | 0.0 | 10.0 | 13.27 | 18.86 | Au1rxx-base64 | 66.94.121.46 |
| 81.72 | shadowsocks | 203.2 | 520.0 | 23.07 | 0.0 | 10.0 | 13.77 | 18.88 | Surfboard-tg-mixed | 216.105.168.18 |
| 81.47 | hysteria2 | 221.9 | 222.9 | 22.64 | 6.64 | 9.94 | 13.27 | 18.86 | Au1rxx-base64 | 45.32.10.7 |
| 81.44 | shadowsocks | 193.1 | 498.3 | 23.31 | 0.0 | 10.0 | 13.77 | 18.86 | Au1rxx-base64 | 108.181.0.177 |
| 80.94 | hysteria2 | 257.2 | 298.7 | 21.82 | 3.8 | 9.94 | 13.27 | 18.86 | Au1rxx-base64 | 158.101.148.79 |
| 80.63 | shadowsocks | 249.6 | 616.9 | 22.0 | 0.0 | 10.0 | 13.77 | 18.86 | Au1rxx-base64 | 149.22.95.183 |
| 80.62 | vless | 200.9 | 497.3 | 23.13 | 0.0 | 10.0 | 11.63 | 18.86 | Au1rxx-base64 | 154.9.241.170 |
| 80.26 | shadowsocks | 243.8 | 605.7 | 22.13 | 0.0 | 10.0 | 13.77 | 18.86 | Au1rxx-base64 | 108.181.118.10 |
| 79.72 | trojan | 365.3 | 1021.0 | 19.32 | 0.0 | 10.0 | 14.4 | 18.5 | mheidari-all | 34.94.125.227 |
| 79.02 | hysteria2 | 219.8 | 222.3 | 22.69 | 6.66 | 9.3 | 13.27 | 18.86 | Au1rxx-base64 | vp3.yysyy.online |
| 78.72 | shadowsocks | 267.4 | 540.8 | 21.59 | 0.0 | 10.0 | 13.77 | 18.86 | Au1rxx-base64 | 173.244.56.6 |
| 77.02 | shadowsocks | 293.8 | 668.9 | 20.98 | 0.0 | 10.0 | 13.77 | 18.86 | Au1rxx-base64 | 156.146.38.169 |
| 76.85 | hysteria2 | 348.1 | 769.3 | 19.72 | 0.0 | 10.0 | 13.27 | 18.86 | Au1rxx-base64 | 129.213.91.185 |
| 76.62 | shadowsocks | 185.3 | 491.1 | 23.49 | 0.0 | 10.0 | 13.77 | 18.86 | Au1rxx-base64 | 216.105.168.158 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | 0.897 | 330 | 1772 | prefer |
| Surfboard-tg-mixed | 0.708 | 0.629 | 143 | 7193 | prefer |
| ermaozi-get_subscribe | 0.575 | 0.556 | 27 | 592 | observe |
| ermaozi | 0.457 | 0.425 | 40 | 715 | observe |
| mheidari-all | 0.343 | 0.261 | 211 | 23407 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7663 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9552 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5725 | observe |
| barry-far-vless | 0.255 | None | 0 | 5963 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4431 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 122 |
| 204 | ProxyError | - | 40 |
| speed | TimeoutError | - | 30 |
| geo | ClientOSError | - | 27 |
| 204 | TimeoutError | - | 22 |
| speed | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
