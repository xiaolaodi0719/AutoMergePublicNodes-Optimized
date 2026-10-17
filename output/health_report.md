# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 15:29:15 |
| 运行耗时 | 701.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99271 |
| 去重后节点 | 27588 |
| TCP 可达 | 3000 |
| 真实可用 | 426 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27588 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| geo | 1.5 |
| tcp | 48.4 |
| probe | 280.5 |
| real_test | 267.4 |
| generate | 95.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58321 |
| vmess | 16614 |
| shadowsocks | 12002 |
| trojan | 10147 |
| hysteria2 | 1341 |
| http | 571 |
| shadowsocksr | 169 |
| socks | 57 |
| anytls | 26 |
| hysteria | 17 |
| tuic | 6 |

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
| 82.87 | vless | 170.7 | 459.7 | 23.83 | 0.0 | 10.0 | 10.58 | 18.46 | Au1rxx-base64 | 47.251.108.158 |
| 81.32 | vless | 207.0 | 527.9 | 22.98 | 0.0 | 9.3 | 10.58 | 18.46 | Au1rxx-base64 | 154.9.241.170 |
| 79.56 | shadowsocks | 229.1 | 536.0 | 22.47 | 0.0 | 9.03 | 13.6 | 18.46 | Au1rxx-base64 | 173.244.56.9 |
| 79.22 | vless | 241.7 | 578.9 | 22.18 | 0.0 | 9.09 | 10.58 | 18.46 | Au1rxx-base64 | 154.40.55.185 |
| 78.59 | vless | 314.9 | 740.9 | 20.49 | 0.0 | 9.06 | 10.58 | 18.46 | Au1rxx-base64 | 95.111.212.241 |
| 78.32 | vless | 301.2 | 717.5 | 20.81 | 0.0 | 8.47 | 10.58 | 18.46 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 78.31 | hysteria2 | 307.0 | 689.7 | 20.67 | 0.0 | 10.0 | 12.19 | 18.46 | Au1rxx-base64 | 66.94.121.46 |
| 78.3 | vless | 199.9 | 515.3 | 23.15 | 0.0 | 9.11 | 10.58 | 18.46 | Au1rxx-base64 | 45.63.53.81 |
| 77.4 | vless | 194.5 | 503.8 | 23.27 | 0.0 | 9.05 | 10.58 | 18.46 | Au1rxx-base64 | 176.122.183.26 |
| 77.38 | shadowsocks | 231.8 | 549.2 | 22.41 | 0.0 | 8.91 | 13.6 | 18.46 | Au1rxx-base64 | 173.244.56.6 |
| 76.59 | shadowsocks | 336.0 | 565.2 | 20.0 | 0.0 | 9.03 | 13.6 | 18.46 | Au1rxx-base64 | 103.11.76.248 |
| 76.47 | vless | 191.2 | 497.8 | 23.35 | 0.0 | 9.08 | 10.58 | 18.46 | Au1rxx-base64 | 67.209.184.133 |
| 76.28 | vless | 411.3 | 1102.3 | 18.26 | 0.0 | 8.98 | 10.58 | 18.46 | Au1rxx-base64 | 51.81.203.63 |
| 76.15 | shadowsocks | 246.4 | 600.4 | 22.07 | 0.0 | 8.9 | 13.6 | 18.46 | Au1rxx-base64 | 149.22.95.183 |
| 75.95 | shadowsocks | 274.0 | 271.5 | 21.43 | 4.82 | 8.84 | 13.6 | 18.46 | Au1rxx-base64 | 149.22.87.240 |
| 75.54 | shadowsocks | 313.5 | 633.2 | 20.52 | 0.0 | 10.0 | 13.6 | 18.46 | Au1rxx-base64 | 156.146.38.170 |
| 75.3 | vless | 313.7 | 700.3 | 20.52 | 0.0 | 8.88 | 10.58 | 18.46 | Au1rxx-base64 | 147.45.60.160 |
| 75.19 | shadowsocks | 290.1 | 656.6 | 21.06 | 0.0 | 8.92 | 13.6 | 18.46 | Au1rxx-base64 | 156.146.38.168 |
| 75.0 | shadowsocks | 287.9 | 649.3 | 21.11 | 0.0 | 8.9 | 13.6 | 18.46 | Au1rxx-base64 | 156.146.38.169 |
| 74.91 | shadowsocks | 300.0 | 676.7 | 20.83 | 0.0 | 8.9 | 13.6 | 18.46 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.882 | 0.803 | 478 | 1993 | prefer |
| ermaozi | 0.813 | 0.806 | 31 | 623 | prefer |
| ermaozi-get_subscribe | 0.378 | 1.0 | 3 | 510 | observe |
| mheidari-all | 0.372 | 0.444 | 9 | 23770 | observe |
| Surfboard-tg-mixed | 0.366 | 0.273 | 33 | 7171 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1993 | observe |
| Epodonios-all | 0.255 | None | 0 | 7678 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10049 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5617 | observe |
| barry-far-vless | 0.255 | None | 0 | 5865 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 41 |
| 204 | ProxyError | - | 19 |
| speed | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 15 |
| geo | ClientOSError | - | 11 |
| speed | TimeoutError | - | 11 |
| 204 | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 5 |
| geo | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
