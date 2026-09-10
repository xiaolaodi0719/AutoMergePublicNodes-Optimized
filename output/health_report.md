# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 04:12:13 |
| 运行耗时 | 715.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 87394 |
| 去重后节点 | 23410 |
| TCP 可达 | 3000 |
| 真实可用 | 562 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23410 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 40.9 |
| probe | 241.6 |
| real_test | 348.4 |
| generate | 76.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53238 |
| vmess | 12569 |
| shadowsocks | 10684 |
| trojan | 8373 |
| hysteria2 | 1682 |
| http | 641 |
| shadowsocksr | 124 |
| socks | 56 |
| hysteria | 12 |
| tuic | 9 |
| anytls | 6 |

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
| 81.66 | vless | 283.0 | 769.0 | 21.23 | 0.0 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 15.204.97.216 |
| 81.52 | shadowsocks | 213.3 | 571.6 | 22.84 | 0.0 | 10.0 | 13.6 | 19.08 | Au1rxx-base64 | 149.22.95.183 |
| 81.43 | vless | 292.9 | 790.0 | 21.0 | 0.0 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 51.81.203.63 |
| 80.25 | vless | 258.9 | 548.2 | 21.79 | 0.0 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 172.233.139.46 |
| 77.48 | vless | 306.4 | 631.4 | 20.69 | 0.0 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 38.246.229.58 |
| 77.07 | vless | 305.4 | 653.3 | 20.71 | 0.0 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 38.209.125.45 |
| 76.51 | shadowsocks | 277.1 | 593.4 | 21.36 | 0.0 | 10.0 | 13.6 | 19.08 | Au1rxx-base64 | 173.244.56.9 |
| 76.31 | vless | 315.3 | 325.1 | 20.48 | 2.81 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 18.183.215.124 |
| 76.29 | vless | 317.8 | 325.7 | 20.42 | 2.79 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 3.112.47.207 |
| 76.2 | vless | 318.5 | 325.7 | 20.4 | 2.79 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 18.177.61.231 |
| 76.13 | shadowsocks | 288.9 | 623.3 | 21.09 | 0.0 | 10.0 | 13.6 | 19.08 | Au1rxx-base64 | 108.181.118.10 |
| 76.06 | vless | 321.2 | 329.8 | 20.34 | 2.63 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 13.231.7.104 |
| 76.01 | vless | 320.7 | 332.3 | 20.35 | 2.54 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 52.199.9.165 |
| 75.84 | vless | 317.4 | 331.8 | 20.43 | 2.56 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 13.231.19.51 |
| 75.66 | vless | 322.7 | 335.9 | 20.31 | 2.4 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 3.112.131.211 |
| 74.51 | vless | 361.3 | 326.2 | 19.42 | 2.77 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 43.207.162.145 |
| 74.02 | shadowsocks | 323.8 | 652.1 | 20.28 | 0.0 | 10.0 | 13.6 | 19.08 | Au1rxx-base64 | 23.150.248.20 |
| 73.93 | vless | 380.8 | 762.2 | 18.96 | 0.0 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 216.152.147.28 |
| 73.77 | vless | 292.1 | 637.0 | 21.02 | 0.0 | 10.0 | 11.35 | 19.08 | Au1rxx-base64 | 38.244.21.139 |
| 73.18 | shadowsocks | 278.6 | 583.0 | 21.33 | 0.0 | 10.0 | 13.6 | 19.08 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | 0.902 | 297 | 1598 | prefer |
| Surfboard-tg-mixed | 0.886 | 0.81 | 153 | 7448 | prefer |
| ermaozi | 0.763 | 0.755 | 53 | 449 | prefer |
| mheidari-all | 0.667 | 0.589 | 90 | 16259 | observe |
| ermaozi-get_subscribe | 0.494 | 0.529 | 17 | 469 | observe |
| DeltaKronecker-all | 0.484 | 0.403 | 139 | 5187 | observe |
| xiaoji235-airport-v2ray-all | 0.471 | 0.381 | 21 | 3508 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 147 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| Epodonios-all | 0.255 | None | 0 | 7910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8706 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6108 | observe |
| barry-far-vless | 0.255 | None | 0 | 6333 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 42 |
| speed | TimeoutError | - | 37 |
| geo | TimeoutError | - | 34 |
| 204 | ProxyError | - | 26 |
| speed | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 14 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
