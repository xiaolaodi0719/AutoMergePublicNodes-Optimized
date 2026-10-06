# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-06 05:58:59 |
| 运行耗时 | 842.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98384 |
| 去重后节点 | 27442 |
| TCP 可达 | 3000 |
| 真实可用 | 513 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27442 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.5 |
| tcp | 46.8 |
| probe | 289.2 |
| real_test | 421.6 |
| generate | 75.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58266 |
| vmess | 15912 |
| shadowsocks | 11660 |
| trojan | 10223 |
| hysteria2 | 1380 |
| http | 614 |
| shadowsocksr | 165 |
| socks | 107 |
| anytls | 28 |
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
| 84.61 | vless | 248.4 | 676.5 | 22.03 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 84.6 | hysteria2 | 244.1 | 658.4 | 22.13 | 0.0 | 10.0 | 13.57 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 83.9 | vless | 279.1 | 705.4 | 21.32 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 66.70.179.198 |
| 83.46 | vless | 298.0 | 737.7 | 20.88 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.224 |
| 83.45 | vless | 298.3 | 741.5 | 20.87 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.74 |
| 83.19 | vless | 309.6 | 706.4 | 20.61 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 82.99 | vless | 318.3 | 883.6 | 20.41 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 159.89.87.21 |
| 82.92 | vless | 321.3 | 888.2 | 20.34 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 185.95.231.156 |
| 82.84 | vless | 324.7 | 810.1 | 20.26 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.235 |
| 82.32 | vless | 275.3 | 721.7 | 21.4 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 82.19 | vless | 353.0 | 691.6 | 19.61 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.184 |
| 82.04 | shadowsocks | 258.4 | 718.5 | 21.8 | 0.0 | 10.0 | 14.24 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 81.38 | vless | 388.0 | 943.3 | 18.8 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.168 |
| 81.05 | vless | 401.9 | 764.5 | 18.47 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.179 |
| 80.76 | vless | 340.7 | 872.5 | 19.89 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 80.55 | vless | 270.6 | 644.2 | 21.51 | 0.0 | 10.0 | 12.58 | 18.2 | mheidari-all | 216.227.161.95 |
| 80.55 | vless | 330.8 | 889.6 | 20.12 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.229 |
| 80.53 | vless | 256.1 | 669.8 | 21.85 | 0.0 | 10.0 | 12.58 | 20.0 | Au1rxx-base64 | 169.40.42.89 |
| 80.52 | shadowsocks | 302.3 | 865.6 | 20.78 | 0.0 | 10.0 | 14.24 | 20.0 | Au1rxx-base64 | 15.204.246.132 |
| 80.49 | shadowsocks | 303.7 | 868.7 | 20.75 | 0.0 | 10.0 | 14.24 | 20.0 | Au1rxx-base64 | 15.204.247.206 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.996 | 0.926 | 351 | 1801 | prefer |
| DeltaKronecker-all | 0.727 | 0.656 | 32 | 5300 | prefer |
| ermaozi | 0.601 | 0.576 | 59 | 691 | observe |
| Surfboard-tg-mixed | 0.53 | 0.7 | 10 | 7083 | observe |
| mheidari-all | 0.409 | 0.328 | 378 | 23039 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7631 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9601 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5600 | observe |
| barry-far-vless | 0.255 | None | 0 | 5876 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4375 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1801 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 151 |
| speed | TimeoutError | - | 56 |
| geo | ClientOSError | - | 40 |
| 204 | ProxyError | - | 32 |
| 204 | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 12 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyConnectionError | - | 5 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
