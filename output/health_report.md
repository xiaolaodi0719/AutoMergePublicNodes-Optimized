# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-01 19:21:33 |
| 运行耗时 | 319.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78665 |
| 去重后节点 | 23513 |
| TCP 可达 | 3000 |
| 真实可用 | 574 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23513 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 13.8 |
| geo | 1.4 |
| tcp | 35.0 |
| probe | 67.1 |
| real_test | 155.4 |
| generate | 46.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47018 |
| vmess | 12254 |
| shadowsocks | 10197 |
| trojan | 8223 |
| hysteria2 | 633 |
| http | 157 |
| shadowsocksr | 70 |
| socks | 65 |
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
| 79.91 | http | 417.0 | 1150.7 | 18.13 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.197 |
| 79.89 | http | 417.5 | 1149.1 | 18.11 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.212 |
| 79.83 | http | 420.2 | 1161.5 | 18.05 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.220 |
| 79.83 | http | 420.4 | 1156.2 | 18.05 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.209 |
| 79.81 | http | 421.1 | 1168.1 | 18.03 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.196 |
| 79.77 | http | 422.9 | 1162.1 | 17.99 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.205 |
| 79.76 | http | 423.4 | 1161.2 | 17.98 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.202 |
| 79.75 | http | 423.5 | 1158.1 | 17.97 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.199 |
| 79.69 | http | 426.4 | 1166.3 | 17.91 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.210 |
| 79.65 | http | 427.8 | 1161.2 | 17.87 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.214 |
| 79.65 | http | 428.1 | 1168.4 | 17.87 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.198 |
| 79.62 | http | 429.3 | 1165.6 | 17.84 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.213 |
| 79.61 | http | 429.5 | 1168.6 | 17.83 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.207 |
| 79.6 | http | 430.2 | 1173.0 | 17.82 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.211 |
| 79.58 | http | 431.0 | 1168.8 | 17.8 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.217 |
| 79.58 | http | 431.2 | 1170.2 | 17.8 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.195 |
| 79.58 | http | 431.2 | 1171.2 | 17.8 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.206 |
| 79.55 | vless | 176.7 | 471.7 | 23.69 | 0.0 | 10.0 | 9.66 | 16.2 | Au1rxx-base64 | 64.23.143.23 |
| 79.55 | http | 432.2 | 1175.7 | 17.77 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.218 |
| 79.43 | http | 437.6 | 1178.1 | 17.65 | 0.0 | 10.0 | 14.9 | 19.88 | zhangkai | 138.199.35.215 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.994 | 0.993 | 148 | 194 | prefer |
| Au1rxx-base64 | 0.783 | 0.716 | 469 | 1692 | prefer |
| Surfboard-tg-mixed | 0.489 | 0.667 | 9 | 5294 | observe |
| DeltaKronecker-all | 0.469 | 0.388 | 214 | 5502 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 16619 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 55 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5391 | observe |
| Epodonios-all | 0.255 | None | 0 | 5909 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3975 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6647 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4168 | observe |
| barry-far-vless | 0.255 | None | 0 | 4547 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5071 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1692 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 97 |
| 204 | ProxyError | - | 39 |
| speed | TimeoutError | - | 34 |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 22 |
| geo | ClientOSError | - | 19 |
| speed | ClientOSError | - | 15 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
