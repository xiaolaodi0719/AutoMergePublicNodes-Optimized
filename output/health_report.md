# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-16 12:54:13 |
| 运行耗时 | 352.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 79021 |
| 去重后节点 | 21934 |
| TCP 可达 | 3000 |
| 真实可用 | 1106 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21934 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 0.7 |
| tcp | 33.5 |
| probe | 64.6 |
| real_test | 209.7 |
| generate | 39.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43551 |
| trojan | 13256 |
| vmess | 10802 |
| shadowsocks | 10022 |
| hysteria2 | 1056 |
| http | 166 |
| socks | 75 |
| shadowsocksr | 74 |
| tuic | 10 |
| hysteria | 7 |
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
| 85.26 | trojan | 184.4 | 481.0 | 23.51 | 0.0 | 10.0 | 14.75 | 20.0 | Au1rxx-base64 | 14.1.28.76 |
| 85.16 | http | 193.5 | 492.7 | 23.3 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 85.14 | http | 194.4 | 505.5 | 23.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 85.12 | http | 195.1 | 499.6 | 23.26 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 85.1 | http | 195.9 | 507.6 | 23.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 85.09 | http | 196.3 | 510.1 | 23.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 85.07 | http | 197.1 | 507.1 | 23.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 85.02 | http | 199.4 | 514.2 | 23.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 85.01 | http | 199.7 | 516.7 | 23.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 85.0 | http | 200.5 | 517.3 | 23.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 84.95 | http | 202.4 | 521.1 | 23.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 84.92 | http | 203.6 | 520.2 | 23.06 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 84.91 | http | 204.4 | 525.6 | 23.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 84.9 | http | 204.7 | 530.3 | 23.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 84.88 | http | 205.6 | 535.9 | 23.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 82.87 | shadowsocks | 221.7 | 506.9 | 22.65 | 0.0 | 10.0 | 14.22 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 82.84 | shadowsocks | 201.2 | 485.1 | 23.12 | 0.0 | 10.0 | 14.22 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 82.51 | shadowsocks | 215.4 | 524.7 | 22.79 | 0.0 | 10.0 | 14.22 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 82.38 | shadowsocks | 242.9 | 604.5 | 22.16 | 0.0 | 10.0 | 14.22 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 82.2 | shadowsocks | 250.5 | 614.6 | 21.98 | 0.0 | 10.0 | 14.22 | 20.0 | Au1rxx-base64 | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.967 | 814 | 1994 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.982 | 0.91 | 100 | 16375 | prefer |
| Surfboard-tg-mixed | 0.762 | 0.685 | 146 | 5800 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1994 | observe |
| Epodonios-all | 0.255 | None | 0 | 6483 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3989 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7383 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4502 | observe |
| barry-far-vless | 0.255 | None | 0 | 4839 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3950 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 18 |
| geo | TimeoutError | - | 16 |
| speed | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 15 |
| geo | ClientOSError | - | 13 |
| speed | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
