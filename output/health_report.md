# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-05 02:57:17 |
| 运行耗时 | 279.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86570 |
| 去重后节点 | 24355 |
| TCP 可达 | 3000 |
| 真实可用 | 593 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24355 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 35.9 |
| probe | 55.8 |
| real_test | 150.5 |
| generate | 28.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50885 |
| vmess | 13092 |
| trojan | 10779 |
| shadowsocks | 10242 |
| hysteria2 | 1288 |
| socks | 79 |
| http | 77 |
| shadowsocksr | 74 |
| anytls | 21 |
| hysteria | 19 |
| tuic | 14 |

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
| 81.87 | vless | 192.4 | 472.0 | 23.32 | 0.0 | 10.0 | 10.29 | 18.98 | Au1rxx-base64 | 70.39.178.231 |
| 80.29 | http | 383.9 | 1071.5 | 18.89 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.207 |
| 80.22 | http | 387.2 | 1078.0 | 18.82 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.214 |
| 80.21 | shadowsocks | 226.4 | 506.5 | 22.54 | 0.0 | 10.0 | 12.69 | 18.98 | Au1rxx-base64 | 173.244.56.6 |
| 80.1 | http | 392.0 | 1086.8 | 18.7 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.199 |
| 80.09 | http | 392.5 | 1085.4 | 18.69 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.217 |
| 80.09 | http | 392.6 | 1087.8 | 18.69 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.219 |
| 80.0 | http | 396.4 | 1104.9 | 18.6 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.213 |
| 79.99 | http | 397.0 | 1109.4 | 18.59 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.198 |
| 79.94 | http | 399.0 | 1108.8 | 18.54 | 0.0 | 10.0 | 14.72 | 19.68 | zhangkai | 138.199.35.200 |
| 79.81 | shadowsocks | 243.5 | 559.1 | 22.14 | 0.0 | 10.0 | 12.69 | 18.98 | Au1rxx-base64 | 149.22.95.183 |
| 79.4 | vless | 244.0 | 490.4 | 22.13 | 0.0 | 10.0 | 10.29 | 18.98 | Au1rxx-base64 | 176.122.164.194 |
| 79.33 | vless | 201.9 | 517.9 | 23.1 | 0.0 | 6.96 | 10.29 | 18.98 | Au1rxx-base64 | jyvlryz.cvewfjg.shop |
| 79.32 | shadowsocks | 243.0 | 607.3 | 22.15 | 0.0 | 10.0 | 12.69 | 18.98 | Au1rxx-base64 | 108.181.0.177 |
| 79.08 | vless | 192.3 | 526.0 | 23.33 | 0.0 | 6.48 | 10.29 | 18.98 | Au1rxx-base64 | t18.qifei.app |
| 79.04 | shadowsocks | 223.8 | 540.6 | 22.6 | 0.0 | 10.0 | 12.69 | 18.98 | Au1rxx-base64 | 108.181.118.10 |
| 78.19 | vless | 245.9 | 585.6 | 22.09 | 0.0 | 10.0 | 10.29 | 18.98 | Au1rxx-base64 | 185.164.111.48 |
| 78.15 | vless | 254.8 | 617.6 | 21.88 | 0.0 | 10.0 | 10.29 | 18.98 | Au1rxx-base64 | 167.17.68.205 |
| 77.98 | vless | 224.6 | 573.8 | 22.58 | 0.0 | 6.13 | 10.29 | 18.98 | Au1rxx-base64 | us3.levikogjgfdd.ir |
| 77.89 | vless | 283.9 | 625.4 | 21.21 | 0.0 | 10.0 | 10.29 | 18.98 | Au1rxx-base64 | 216.227.161.95 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.949 | 408 | 1440 | prefer |
| zhangkai | 0.984 | 1.0 | 51 | 72 | prefer |
| Surfboard-tg-mixed | 0.675 | 0.596 | 183 | 5655 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5251 | observe |
| Epodonios-all | 0.255 | None | 0 | 6252 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7076 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4478 | observe |
| barry-far-vless | 0.255 | None | 0 | 4815 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5141 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.233 | None | 0 | 1440 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| DeltaKronecker-all | 0.22 | 0.122 | 41 | 5788 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 161 |
| speed | TimeoutError | - | 72 |
| speed | ClientOSError | - | 66 |
| geo | ClientOSError | - | 46 |
| cn-block | TimeoutError | - | 23 |
| 204 | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 5 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
