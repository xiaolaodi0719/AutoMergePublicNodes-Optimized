# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 04:23:00 |
| 运行耗时 | 611.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 91704 |
| 去重后节点 | 25163 |
| TCP 可达 | 3000 |
| 真实可用 | 512 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25163 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 42.7 |
| probe | 215.8 |
| real_test | 266.5 |
| generate | 80.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54115 |
| vmess | 14758 |
| shadowsocks | 11177 |
| trojan | 9289 |
| hysteria2 | 1456 |
| http | 651 |
| shadowsocksr | 131 |
| socks | 81 |
| anytls | 21 |
| hysteria | 17 |
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
| 79.65 | shadowsocks | 254.2 | 623.2 | 21.89 | 0.0 | 9.71 | 13.81 | 18.24 | Au1rxx-base64 | 156.146.38.168 |
| 78.99 | hysteria2 | 345.3 | 829.4 | 19.78 | 0.0 | 10.0 | 13.5 | 18.24 | Au1rxx-base64 | 66.94.121.46 |
| 78.34 | vless | 265.9 | 673.8 | 21.62 | 0.0 | 9.8 | 8.68 | 18.24 | Au1rxx-base64 | 195.211.98.43 |
| 77.55 | vless | 298.3 | 718.5 | 20.87 | 0.0 | 9.76 | 8.68 | 18.24 | Au1rxx-base64 | 79.141.172.154 |
| 75.62 | shadowsocks | 270.1 | 667.6 | 21.53 | 0.0 | 10.0 | 13.81 | 14.28 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.49 | shadowsocks | 275.4 | 707.1 | 21.4 | 0.0 | 10.0 | 13.81 | 14.28 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.43 | vless | 319.4 | 758.6 | 20.38 | 0.0 | 10.0 | 8.68 | 18.24 | Au1rxx-base64 | 47.253.226.114 |
| 74.94 | vless | 319.1 | 723.0 | 20.39 | 0.0 | 9.29 | 8.68 | 18.24 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 74.83 | hysteria2 | 315.0 | 778.0 | 20.49 | 0.0 | 10.0 | 13.5 | 12.66 | mheidari-all | 159.223.157.129 |
| 74.54 | vless | 292.6 | 642.3 | 21.01 | 0.0 | 9.76 | 8.68 | 18.24 | Au1rxx-base64 | 195.123.235.177 |
| 74.29 | vless | 317.5 | 687.6 | 20.43 | 0.0 | 10.0 | 8.68 | 18.24 | Au1rxx-base64 | 138.124.60.146 |
| 74.06 | vless | 371.2 | 836.6 | 19.18 | 0.0 | 9.76 | 8.68 | 18.24 | Au1rxx-base64 | 169.40.42.235 |
| 73.33 | shadowsocks | 277.3 | 693.8 | 21.36 | 0.0 | 10.0 | 13.81 | 12.66 | mheidari-all | 23.150.248.20 |
| 73.18 | vless | 297.9 | 611.5 | 20.88 | 0.0 | 9.69 | 8.68 | 18.24 | Au1rxx-base64 | 172.235.43.210 |
| 73.06 | vless | 358.9 | 713.3 | 19.47 | 0.0 | 9.73 | 8.68 | 18.24 | Au1rxx-base64 | 169.40.42.173 |
| 72.88 | shadowsocks | 317.3 | 769.8 | 20.43 | 0.0 | 10.0 | 13.81 | 14.28 | Surfboard-tg-mixed | 37.19.198.243 |
| 72.61 | vless | 442.9 | 1093.9 | 17.52 | 0.0 | 9.76 | 8.68 | 18.24 | Au1rxx-base64 | 137.184.218.169 |
| 72.4 | vless | 426.9 | 1043.8 | 17.9 | 0.0 | 9.73 | 8.68 | 18.24 | Au1rxx-base64 | 185.95.231.156 |
| 72.12 | vless | 365.5 | 914.4 | 19.32 | 0.0 | 9.73 | 8.68 | 18.24 | Au1rxx-base64 | 198.251.78.29 |
| 71.65 | shadowsocks | 315.1 | 765.1 | 20.48 | 0.0 | 10.0 | 13.81 | 12.66 | mheidari-all | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.918 | 0.854 | 302 | 1658 | prefer |
| Surfboard-tg-mixed | 0.657 | 0.578 | 237 | 7121 | observe |
| ermaozi | 0.586 | 0.577 | 26 | 369 | observe |
| mheidari-all | 0.504 | 0.423 | 227 | 19852 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 153 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5290 | observe |
| Epodonios-all | 0.255 | None | 0 | 7572 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8704 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5672 | observe |
| barry-far-vless | 0.255 | None | 0 | 5888 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1660 | observe |
| ermaozi-get_subscribe | 0.235 | 0.4 | 5 | 393 | downweight |
| ninja-vless | 0.232 | 0.25 | 4 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 74 |
| geo | TimeoutError | - | 54 |
| cn-block | ClientOSError | - | 54 |
| speed | TimeoutError | - | 45 |
| speed | ClientOSError | - | 43 |
| cn-block | TimeoutError | - | 25 |
| 204 | ProxyError | - | 18 |
| 204 | TimeoutError | - | 11 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
