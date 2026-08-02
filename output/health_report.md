# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-02 03:31:58 |
| 运行耗时 | 318.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78379 |
| 去重后节点 | 23363 |
| TCP 可达 | 3000 |
| 真实可用 | 760 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23363 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| geo | 1.5 |
| tcp | 34.5 |
| probe | 59.5 |
| real_test | 185.5 |
| generate | 33.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46914 |
| vmess | 12401 |
| shadowsocks | 10057 |
| trojan | 8038 |
| hysteria2 | 616 |
| http | 157 |
| shadowsocksr | 78 |
| socks | 70 |
| anytls | 26 |
| hysteria | 14 |
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
| 80.4 | hysteria2 | 271.7 | 681.8 | 21.49 | 0.0 | 10.0 | 14.25 | 15.66 | Au1rxx-base64 | 138.124.68.188 |
| 79.81 | hysteria2 | 288.7 | 684.7 | 21.1 | 0.0 | 10.0 | 14.25 | 15.66 | Au1rxx-base64 | 159.223.157.129 |
| 79.53 | http | 328.5 | 735.6 | 20.17 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 156.146.59.7 |
| 78.93 | http | 281.0 | 564.7 | 21.27 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.200 |
| 78.81 | http | 282.2 | 564.4 | 21.25 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.205 |
| 78.81 | http | 290.7 | 594.3 | 21.05 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.208 |
| 78.79 | http | 316.5 | 706.5 | 20.45 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 156.146.59.25 |
| 78.76 | http | 317.7 | 710.6 | 20.42 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 156.146.59.8 |
| 78.68 | http | 282.0 | 565.7 | 21.25 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.213 |
| 78.68 | http | 289.5 | 591.3 | 21.08 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.217 |
| 78.66 | http | 282.6 | 566.4 | 21.24 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.207 |
| 78.53 | http | 287.7 | 584.4 | 21.12 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.212 |
| 78.38 | http | 311.9 | 657.9 | 20.56 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.197 |
| 78.29 | http | 330.4 | 735.6 | 20.13 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 156.146.59.16 |
| 78.26 | http | 291.2 | 589.8 | 21.04 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.195 |
| 78.22 | http | 350.4 | 804.4 | 19.67 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 156.146.59.50 |
| 78.18 | http | 315.3 | 541.0 | 20.48 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.209 |
| 78.16 | http | 286.9 | 584.8 | 21.14 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.216 |
| 78.15 | http | 282.3 | 570.0 | 21.24 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.218 |
| 78.12 | http | 288.4 | 584.6 | 21.1 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.196 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 147 | 194 | prefer |
| Au1rxx-base64 | 0.95 | 0.888 | 536 | 1590 | prefer |
| Surfboard-tg-mixed | 0.659 | 0.58 | 119 | 5146 | observe |
| mheidari-all | 0.272 | 0.286 | 7 | 16695 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5391 | observe |
| Epodonios-all | 0.255 | None | 0 | 5783 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6873 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4069 | observe |
| barry-far-vless | 0.255 | None | 0 | 4431 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5071 | observe |
| xiaoji235-airport-v2ray-all | 0.249 | None | 0 | 1861 | observe |
| DeltaKronecker-all | 0.248 | 0.167 | 384 | 5497 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 240 |
| speed | TimeoutError | - | 57 |
| speed | ClientOSError | - | 55 |
| geo | ClientOSError | - | 49 |
| cn-block | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 9 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
