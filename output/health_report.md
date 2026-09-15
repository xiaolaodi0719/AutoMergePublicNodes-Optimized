# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 21:14:16 |
| 运行耗时 | 600.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84752 |
| 去重后节点 | 23104 |
| TCP 可达 | 3000 |
| 真实可用 | 447 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23104 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 38.2 |
| probe | 268.5 |
| real_test | 206.1 |
| generate | 81.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51851 |
| vmess | 12962 |
| shadowsocks | 9497 |
| trojan | 8299 |
| hysteria2 | 1320 |
| http | 625 |
| shadowsocksr | 125 |
| socks | 55 |
| hysteria | 11 |
| tuic | 5 |
| anytls | 2 |

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
| 84.11 | hysteria2 | 205.1 | 469.3 | 23.03 | 0.0 | 10.0 | 14.29 | 18.68 | Au1rxx-base64 | 107.175.219.48 |
| 80.87 | vless | 192.5 | 491.1 | 23.32 | 0.0 | 10.0 | 8.87 | 18.68 | Au1rxx-base64 | 45.149.172.80 |
| 80.67 | shadowsocks | 226.3 | 575.8 | 22.54 | 0.0 | 10.0 | 13.45 | 18.68 | Au1rxx-base64 | 173.244.56.9 |
| 80.55 | shadowsocks | 209.7 | 488.5 | 22.92 | 0.0 | 10.0 | 13.45 | 18.68 | Au1rxx-base64 | 108.181.0.177 |
| 80.09 | vless | 226.1 | 476.4 | 22.54 | 0.0 | 10.0 | 8.87 | 18.68 | Au1rxx-base64 | 172.235.43.210 |
| 79.15 | vless | 267.0 | 704.4 | 21.6 | 0.0 | 10.0 | 8.87 | 18.68 | Au1rxx-base64 | 45.149.172.74 |
| 79.05 | shadowsocks | 256.5 | 617.6 | 21.84 | 0.0 | 10.0 | 13.45 | 18.68 | Au1rxx-base64 | 156.146.38.170 |
| 78.99 | hysteria2 | 201.9 | 525.4 | 23.1 | 0.0 | 10.0 | 14.29 | 13.6 | Surfboard-tg-mixed | 45.149.172.80 |
| 78.34 | hysteria2 | 331.1 | 723.3 | 20.11 | 0.0 | 10.0 | 14.29 | 18.68 | Au1rxx-base64 | 159.223.157.129 |
| 78.24 | shadowsocks | 267.9 | 653.1 | 21.58 | 0.0 | 10.0 | 13.45 | 18.68 | Au1rxx-base64 | 156.146.38.169 |
| 76.99 | shadowsocks | 277.5 | 636.1 | 21.35 | 0.0 | 10.0 | 13.45 | 18.68 | Au1rxx-base64 | 23.150.248.20 |
| 75.92 | vless | 222.7 | 486.1 | 22.62 | 0.0 | 10.0 | 8.87 | 18.68 | Au1rxx-base64 | 172.64.32.103 |
| 75.69 | vless | 200.4 | 526.5 | 23.14 | 0.0 | 10.0 | 8.87 | 18.68 | Au1rxx-base64 | 192.3.247.109 |
| 75.69 | vless | 259.8 | 522.3 | 21.76 | 0.0 | 10.0 | 8.87 | 18.68 | Au1rxx-base64 | 144.172.104.26 |
| 75.65 | vless | 345.4 | 834.6 | 19.78 | 0.0 | 10.0 | 8.87 | 18.68 | Au1rxx-base64 | 15.204.97.216 |
| 75.59 | vless | 226.5 | 514.6 | 22.54 | 0.0 | 10.0 | 8.87 | 18.68 | Au1rxx-base64 | 172.64.154.8 |
| 75.38 | shadowsocks | 290.5 | 621.7 | 21.05 | 0.0 | 10.0 | 13.45 | 18.68 | Au1rxx-base64 | 149.22.95.183 |
| 75.32 | vless | 237.9 | 515.2 | 22.27 | 0.0 | 10.0 | 8.87 | 18.68 | Au1rxx-base64 | 162.159.48.32 |
| 74.72 | shadowsocks | 483.4 | 1340.1 | 16.59 | 0.0 | 10.0 | 13.45 | 18.68 | Au1rxx-base64 | 173.244.56.6 |
| 74.54 | shadowsocks | 252.0 | 602.0 | 21.94 | 0.0 | 10.0 | 13.45 | 13.6 | Surfboard-tg-mixed | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | 0.906 | 308 | 1553 | prefer |
| DeltaKronecker-all | 0.908 | 0.852 | 27 | 5932 | prefer |
| mheidari-all | 0.8 | 0.729 | 48 | 15952 | prefer |
| Surfboard-tg-mixed | 0.702 | 0.624 | 141 | 7516 | prefer |
| ermaozi | 0.695 | 0.692 | 26 | 406 | observe |
| ermaozi-get_subscribe | 0.272 | 1.0 | 1 | 422 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 148 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7982 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8946 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6065 | observe |
| barry-far-vless | 0.255 | None | 0 | 6289 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 25 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 16 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 7 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
