# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-29 14:25:28 |
| 运行耗时 | 261.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 78926 |
| 去重后节点 | 22704 |
| TCP 可达 | 3000 |
| 真实可用 | 516 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22704 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 32.0 |
| probe | 54.9 |
| real_test | 140.3 |
| generate | 25.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46372 |
| vmess | 10770 |
| trojan | 10592 |
| shadowsocks | 10402 |
| hysteria2 | 548 |
| http | 73 |
| shadowsocksr | 72 |
| socks | 56 |
| anytls | 26 |
| hysteria | 12 |
| tuic | 3 |

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
| 79.9 | shadowsocks | 217.1 | 519.4 | 22.75 | 0.0 | 10.0 | 13.05 | 18.1 | Au1rxx-base64 | 173.244.56.6 |
| 79.65 | shadowsocks | 227.9 | 509.0 | 22.5 | 0.0 | 10.0 | 13.05 | 18.1 | Au1rxx-base64 | 173.244.56.9 |
| 79.25 | shadowsocks | 245.3 | 588.6 | 22.1 | 0.0 | 10.0 | 13.05 | 18.1 | Au1rxx-base64 | 149.22.95.183 |
| 78.13 | shadowsocks | 271.9 | 712.5 | 21.48 | 0.0 | 10.0 | 13.05 | 18.1 | Au1rxx-base64 | 108.181.118.10 |
| 78.07 | shadowsocks | 274.7 | 711.7 | 21.42 | 0.0 | 10.0 | 13.05 | 18.1 | Au1rxx-base64 | 108.181.0.177 |
| 75.85 | shadowsocks | 272.8 | 277.2 | 21.46 | 4.6 | 9.82 | 13.05 | 18.1 | Au1rxx-base64 | 149.22.87.241 |
| 75.0 | shadowsocks | 286.0 | 646.1 | 21.16 | 0.0 | 10.0 | 13.05 | 18.1 | Au1rxx-base64 | 156.146.38.169 |
| 74.78 | shadowsocks | 288.9 | 650.4 | 21.09 | 0.0 | 10.0 | 13.05 | 18.1 | Au1rxx-base64 | 156.146.38.167 |
| 74.46 | shadowsocks | 338.4 | 789.8 | 19.94 | 0.0 | 10.0 | 13.05 | 18.1 | Au1rxx-base64 | 156.146.38.168 |
| 74.05 | trojan | 300.8 | 652.6 | 20.81 | 0.0 | 10.0 | 11.64 | 18.1 | Au1rxx-base64 | 64.94.95.115 |
| 74.03 | vless | 304.9 | 513.4 | 20.72 | 0.0 | 10.0 | 5.9 | 18.1 | Au1rxx-base64 | 185.164.111.48 |
| 73.55 | trojan | 329.5 | 737.8 | 20.15 | 0.0 | 10.0 | 11.64 | 18.1 | Au1rxx-base64 | 64.94.95.118 |
| 73.54 | trojan | 332.2 | 735.8 | 20.09 | 0.0 | 10.0 | 11.64 | 18.1 | Au1rxx-base64 | 64.94.95.114 |
| 73.24 | trojan | 326.1 | 726.9 | 20.23 | 0.0 | 10.0 | 11.64 | 18.1 | Au1rxx-base64 | 64.94.95.117 |
| 73.24 | hysteria2 | 343.4 | 710.4 | 19.83 | 0.0 | 10.0 | 10.71 | 18.1 | Au1rxx-base64 | 159.223.157.129 |
| 73.12 | shadowsocks | 272.6 | 628.2 | 21.47 | 0.0 | 10.0 | 13.05 | 18.1 | Au1rxx-base64 | 193.42.38.209 |
| 72.85 | vless | 169.8 | 467.7 | 23.85 | 0.0 | 10.0 | 5.9 | 18.1 | Au1rxx-base64 | 47.251.25.74 |
| 72.76 | vless | 195.3 | 506.2 | 23.26 | 0.0 | 10.0 | 5.9 | 18.1 | Au1rxx-base64 | 154.19.184.40 |
| 72.63 | vless | 292.6 | 606.6 | 21.0 | 0.0 | 10.0 | 5.9 | 18.1 | Au1rxx-base64 | 216.227.161.95 |
| 71.91 | shadowsocks | 300.9 | 366.5 | 20.81 | 1.26 | 9.82 | 13.05 | 18.1 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 70 | 84 | prefer |
| Au1rxx-base64 | 0.863 | 0.812 | 276 | 1352 | prefer |
| Surfboard-tg-mixed | 0.726 | 0.648 | 142 | 5803 | prefer |
| DeltaKronecker-all | 0.653 | 0.574 | 216 | 5519 | observe |
| mheidari-all | 0.385 | 0.5 | 8 | 16071 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5118 | observe |
| Epodonios-all | 0.255 | None | 0 | 6469 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6373 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4538 | observe |
| barry-far-vless | 0.255 | None | 0 | 4964 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5089 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 80 |
| speed | TimeoutError | - | 29 |
| cn-block | TimeoutError | - | 26 |
| geo | ClientOSError | - | 19 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyError | - | 10 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
