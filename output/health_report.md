# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-01 03:31:31 |
| 运行耗时 | 304.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78571 |
| 去重后节点 | 22863 |
| TCP 可达 | 3000 |
| 真实可用 | 660 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22863 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 34.1 |
| probe | 56.9 |
| real_test | 166.0 |
| generate | 39.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46766 |
| vmess | 12053 |
| shadowsocks | 10140 |
| trojan | 8777 |
| hysteria2 | 567 |
| http | 87 |
| shadowsocksr | 75 |
| socks | 60 |
| anytls | 26 |
| hysteria | 14 |
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
| 84.99 | http | 192.0 | 488.5 | 23.33 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.218 |
| 84.93 | http | 194.7 | 500.7 | 23.27 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.207 |
| 84.92 | http | 195.0 | 500.3 | 23.26 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.202 |
| 84.89 | http | 196.5 | 500.3 | 23.23 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.196 |
| 84.88 | http | 196.8 | 501.6 | 23.22 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.217 |
| 84.84 | http | 198.4 | 502.1 | 23.18 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.198 |
| 84.8 | http | 200.2 | 506.7 | 23.14 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.220 |
| 84.8 | http | 200.5 | 506.0 | 23.14 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.209 |
| 84.79 | http | 200.9 | 512.4 | 23.13 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.199 |
| 84.78 | http | 201.2 | 504.5 | 23.12 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.197 |
| 84.78 | http | 201.4 | 501.6 | 23.12 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.204 |
| 84.56 | http | 210.6 | 539.4 | 22.9 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.205 |
| 76.07 | vless | 179.1 | 463.9 | 23.63 | 0.0 | 10.0 | 8.32 | 15.12 | Au1rxx-base64 | 70.39.198.183 |
| 75.39 | shadowsocks | 198.7 | 493.7 | 23.18 | 0.0 | 9.57 | 12.02 | 15.12 | Au1rxx-base64 | 108.181.118.10 |
| 75.32 | shadowsocks | 201.6 | 498.1 | 23.11 | 0.0 | 9.57 | 12.02 | 15.12 | Au1rxx-base64 | 108.181.0.177 |
| 74.96 | vless | 226.9 | 595.7 | 22.52 | 0.0 | 10.0 | 8.32 | 15.12 | Au1rxx-base64 | 192.204.50.220 |
| 74.93 | shadowsocks | 236.1 | 556.7 | 22.31 | 0.0 | 9.48 | 12.02 | 15.12 | Au1rxx-base64 | 149.22.95.183 |
| 74.43 | vless | 293.4 | 797.5 | 20.99 | 0.0 | 10.0 | 8.32 | 15.12 | Au1rxx-base64 | 70.39.178.231 |
| 74.24 | vless | 279.9 | 656.8 | 21.3 | 0.0 | 10.0 | 8.32 | 15.12 | Au1rxx-base64 | 52.43.158.158 |
| 73.82 | vless | 189.9 | 495.8 | 23.38 | 0.0 | 10.0 | 8.32 | 15.12 | Au1rxx-base64 | 154.17.239.145 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 80 | 110 | prefer |
| Au1rxx-base64 | 0.923 | 0.857 | 533 | 1664 | prefer |
| Surfboard-tg-mixed | 0.588 | 0.508 | 124 | 5365 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| DeltaKronecker-all | 0.294 | 0.212 | 269 | 5144 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5507 | observe |
| Epodonios-all | 0.255 | None | 0 | 6122 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6657 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4239 | observe |
| barry-far-vless | 0.255 | None | 0 | 4596 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5081 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1664 | observe |
| nscl5-all | 0.225 | None | 0 | 1258 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 170 |
| speed | TimeoutError | - | 55 |
| speed | ClientOSError | - | 52 |
| geo | ClientOSError | - | 36 |
| cn-block | TimeoutError | - | 29 |
| 204 | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 5 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
