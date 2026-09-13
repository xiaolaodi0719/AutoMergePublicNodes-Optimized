# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 11:39:48 |
| 运行耗时 | 737.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 94200 |
| 去重后节点 | 25204 |
| TCP 可达 | 3000 |
| 真实可用 | 446 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25204 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.5 |
| tcp | 43.0 |
| probe | 344.0 |
| real_test | 259.1 |
| generate | 82.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57892 |
| vmess | 13479 |
| shadowsocks | 10870 |
| trojan | 8886 |
| hysteria2 | 2203 |
| http | 640 |
| shadowsocksr | 129 |
| socks | 60 |
| hysteria | 15 |
| anytls | 14 |
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
| 78.05 | hysteria2 | 373.9 | 901.2 | 19.12 | 0.0 | 10.0 | 13.64 | 18.48 | Au1rxx-base64 | 66.94.121.46 |
| 76.11 | shadowsocks | 360.6 | 868.2 | 19.43 | 0.0 | 10.0 | 13.89 | 18.48 | Au1rxx-base64 | 15.204.247.175 |
| 75.46 | shadowsocks | 250.6 | 579.0 | 21.98 | 0.0 | 10.0 | 13.89 | 14.02 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.78 | vless | 278.9 | 636.2 | 21.32 | 0.0 | 10.0 | 5.98 | 18.48 | Au1rxx-base64 | 198.251.78.29 |
| 73.62 | vless | 309.9 | 727.4 | 20.6 | 0.0 | 10.0 | 5.98 | 18.48 | Au1rxx-base64 | 47.253.226.114 |
| 73.52 | shadowsocks | 251.8 | 618.8 | 21.95 | 0.0 | 10.0 | 13.89 | 14.02 | Surfboard-tg-mixed | 23.150.248.20 |
| 72.27 | hysteria2 | 242.8 | 562.7 | 22.16 | 0.0 | 10.0 | 13.64 | 18.48 | Au1rxx-base64 | 108.59.244.158 |
| 71.52 | shadowsocks | 458.9 | 892.5 | 17.15 | 0.0 | 10.0 | 13.89 | 18.48 | Au1rxx-base64 | 51.222.200.165 |
| 71.49 | shadowsocks | 278.4 | 601.0 | 21.33 | 0.0 | 10.0 | 13.89 | 14.02 | Surfboard-tg-mixed | 5.78.51.123 |
| 71.49 | vless | 320.5 | 700.2 | 20.36 | 0.0 | 10.0 | 5.98 | 18.48 | Au1rxx-base64 | 137.184.218.169 |
| 71.34 | hysteria2 | 445.6 | 757.1 | 17.46 | 0.0 | 9.55 | 13.64 | 18.48 | Au1rxx-base64 | 144.31.148.87 |
| 71.31 | vless | 312.5 | 677.3 | 20.54 | 0.0 | 10.0 | 5.98 | 18.48 | Au1rxx-base64 | 195.123.235.177 |
| 71.23 | hysteria2 | 465.0 | 848.8 | 17.01 | 0.0 | 9.7 | 13.64 | 18.48 | Au1rxx-base64 | 45.192.12.93 |
| 70.92 | hysteria2 | 508.6 | 1011.6 | 16.01 | 0.0 | 9.95 | 13.64 | 18.48 | Au1rxx-base64 | 5.129.235.85 |
| 70.75 | vless | 379.1 | 774.7 | 19.0 | 0.0 | 10.0 | 5.98 | 18.48 | Au1rxx-base64 | 169.40.42.16 |
| 70.63 | shadowsocks | 399.2 | 960.4 | 18.54 | 0.0 | 10.0 | 13.89 | 18.48 | Au1rxx-base64 | 15.204.246.132 |
| 70.48 | vless | 301.3 | 593.6 | 20.8 | 0.0 | 10.0 | 5.98 | 18.48 | Au1rxx-base64 | 144.172.104.26 |
| 70.32 | vless | 428.3 | 1065.3 | 17.86 | 0.0 | 10.0 | 5.98 | 18.48 | Au1rxx-base64 | 185.95.231.156 |
| 70.28 | shadowsocks | 321.4 | 727.6 | 20.34 | 0.0 | 10.0 | 13.89 | 14.02 | Surfboard-tg-mixed | 198.98.53.130 |
| 70.0 | vless | 346.0 | 730.9 | 19.77 | 0.0 | 10.0 | 5.98 | 18.48 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | 0.822 | 259 | 1633 | prefer |
| Surfboard-tg-mixed | 0.757 | 0.68 | 153 | 7439 | prefer |
| ermaozi | 0.751 | 0.744 | 43 | 436 | prefer |
| mheidari-all | 0.653 | 0.574 | 141 | 20485 | observe |
| DeltaKronecker-all | 0.489 | 0.667 | 9 | 5892 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5301 | observe |
| ermaozi-get_subscribe | 0.328 | 0.385 | 13 | 464 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 102 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7887 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8920 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6075 | observe |
| barry-far-vless | 0.255 | None | 0 | 6291 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 41 |
| 204 | TimeoutError | - | 36 |
| 204 | ProxyError | - | 30 |
| speed | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 17 |
| geo | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 9 |
| speed | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
