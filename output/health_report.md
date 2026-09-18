# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 16:20:20 |
| 运行耗时 | 670.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83896 |
| 去重后节点 | 23095 |
| TCP 可达 | 3000 |
| 真实可用 | 397 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23095 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 38.5 |
| probe | 271.6 |
| real_test | 275.6 |
| generate | 76.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50405 |
| vmess | 13226 |
| shadowsocks | 10067 |
| trojan | 8141 |
| hysteria2 | 1259 |
| http | 588 |
| shadowsocksr | 128 |
| socks | 65 |
| hysteria | 8 |
| anytls | 7 |
| tuic | 2 |

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
| 80.2 | hysteria2 | 308.5 | 847.4 | 20.64 | 0.0 | 10.0 | 12.5 | 18.16 | Au1rxx-base64 | 159.223.157.129 |
| 80.18 | vless | 227.7 | 600.0 | 22.51 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 195.123.235.177 |
| 80.01 | shadowsocks | 247.2 | 676.3 | 22.05 | 0.0 | 10.0 | 13.8 | 18.16 | Au1rxx-base64 | 37.19.198.160 |
| 79.5 | vless | 256.9 | 671.6 | 21.83 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.173 |
| 79.26 | vless | 267.1 | 675.8 | 21.59 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 137.184.218.169 |
| 78.47 | vless | 301.4 | 807.5 | 20.8 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.212 |
| 78.17 | vless | 314.4 | 791.5 | 20.5 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.133 |
| 77.59 | vless | 339.4 | 943.7 | 19.92 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 185.95.231.156 |
| 77.52 | vless | 342.6 | 871.7 | 19.85 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.89 |
| 77.4 | vless | 289.3 | 714.9 | 21.08 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.223 |
| 77.27 | vless | 300.9 | 681.1 | 20.81 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 198.251.78.29 |
| 77.27 | vless | 353.4 | 964.0 | 19.6 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.182 |
| 77.22 | vless | 355.5 | 752.2 | 19.55 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.74 |
| 77.17 | vless | 357.6 | 858.0 | 19.5 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.75 |
| 76.88 | vless | 276.1 | 683.2 | 21.39 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.35 |
| 76.7 | vless | 363.4 | 776.8 | 19.37 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.163 |
| 76.4 | vless | 390.9 | 1008.8 | 18.73 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.104 |
| 76.36 | vless | 283.5 | 730.5 | 21.22 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.231 |
| 76.18 | vless | 384.3 | 986.0 | 18.88 | 0.0 | 10.0 | 9.51 | 18.16 | Au1rxx-base64 | 169.40.42.95 |
| 76.11 | shadowsocks | 284.7 | 642.8 | 21.19 | 0.0 | 10.0 | 13.8 | 18.16 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.927 | 0.866 | 254 | 1596 | prefer |
| ermaozi | 0.813 | 0.826 | 23 | 325 | prefer |
| mheidari-all | 0.752 | 0.678 | 59 | 15758 | prefer |
| Surfboard-tg-mixed | 0.744 | 0.667 | 147 | 7397 | prefer |
| DeltaKronecker-all | 0.499 | 0.415 | 41 | 6040 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| Epodonios-all | 0.255 | None | 0 | 7860 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8960 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5909 | observe |
| barry-far-vless | 0.255 | None | 0 | 6127 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1596 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| roosterkid-openproxylist-v2ray | 0.213 | 0.5 | 2 | 150 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 34 |
| 204 | TimeoutError | - | 20 |
| geo | TimeoutError | - | 17 |
| 204 | ProxyError | - | 16 |
| cn-block | TimeoutError | - | 16 |
| speed | ClientOSError | - | 15 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 4 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
