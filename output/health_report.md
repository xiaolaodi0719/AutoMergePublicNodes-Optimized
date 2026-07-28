# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-28 14:26:25 |
| 运行耗时 | 295.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 82917 |
| 去重后节点 | 23077 |
| TCP 可达 | 3000 |
| 真实可用 | 507 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23077 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 31.7 |
| geo | 1.4 |
| tcp | 31.9 |
| probe | 57.2 |
| real_test | 136.1 |
| generate | 37.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46906 |
| trojan | 15049 |
| shadowsocks | 10136 |
| vmess | 10117 |
| hysteria2 | 495 |
| shadowsocksr | 75 |
| http | 73 |
| socks | 55 |
| hysteria | 8 |
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
| 82.13 | shadowsocks | 220.8 | 508.1 | 22.67 | 0.0 | 10.0 | 13.68 | 19.78 | Au1rxx-base64 | 149.22.95.183 |
| 82.12 | shadowsocks | 199.3 | 492.8 | 23.16 | 0.0 | 10.0 | 13.68 | 19.78 | Au1rxx-base64 | 108.181.0.177 |
| 82.05 | shadowsocks | 202.5 | 492.8 | 23.09 | 0.0 | 10.0 | 13.68 | 19.78 | Au1rxx-base64 | 108.181.118.10 |
| 81.43 | shadowsocks | 250.9 | 658.5 | 21.97 | 0.0 | 10.0 | 13.68 | 19.78 | Au1rxx-base64 | 173.244.56.6 |
| 80.48 | shadowsocks | 291.9 | 770.5 | 21.02 | 0.0 | 10.0 | 13.68 | 19.78 | Au1rxx-base64 | 173.244.56.9 |
| 78.45 | vless | 177.4 | 480.1 | 23.67 | 0.0 | 10.0 | 8.0 | 19.78 | Au1rxx-base64 | 172.67.187.219 |
| 78.25 | shadowsocks | 299.6 | 258.7 | 20.84 | 5.3 | 9.95 | 13.68 | 19.78 | Au1rxx-base64 | 149.22.87.241 |
| 77.1 | hysteria2 | 346.9 | 720.5 | 19.75 | 0.0 | 10.0 | 12.86 | 19.78 | Au1rxx-base64 | 159.223.157.129 |
| 76.77 | shadowsocks | 286.9 | 645.9 | 21.14 | 0.0 | 10.0 | 13.68 | 19.78 | Au1rxx-base64 | 156.146.38.167 |
| 76.2 | shadowsocks | 193.4 | 501.0 | 23.3 | 0.0 | 10.0 | 13.68 | 14.22 | Surfboard-tg-mixed | 216.105.168.18 |
| 75.84 | shadowsocks | 325.6 | 758.5 | 20.24 | 0.0 | 10.0 | 13.68 | 19.78 | Au1rxx-base64 | 156.146.38.169 |
| 75.54 | vless | 173.4 | 464.9 | 23.76 | 0.0 | 10.0 | 8.0 | 19.78 | Au1rxx-base64 | skk.moe |
| 75.54 | vless | 173.7 | 475.1 | 23.76 | 0.0 | 10.0 | 8.0 | 19.78 | Au1rxx-base64 | 172.66.132.196 |
| 75.43 | vless | 178.5 | 484.0 | 23.65 | 0.0 | 10.0 | 8.0 | 19.78 | Au1rxx-base64 | 104.21.55.229 |
| 75.43 | trojan | 354.5 | 811.3 | 19.57 | 0.0 | 10.0 | 12.88 | 19.78 | Au1rxx-base64 | 64.94.95.118 |
| 74.97 | shadowsocks | 285.7 | 647.0 | 21.17 | 0.0 | 10.0 | 13.68 | 19.78 | Au1rxx-base64 | 156.146.38.168 |
| 74.74 | vless | 234.4 | 528.3 | 22.35 | 0.0 | 10.0 | 8.0 | 19.78 | Au1rxx-base64 | 52.43.158.158 |
| 74.2 | shadowsocks | 301.9 | 365.4 | 20.79 | 1.3 | 9.94 | 13.68 | 19.78 | Au1rxx-base64 | 149.22.87.204 |
| 73.91 | vless | 174.9 | 452.5 | 23.73 | 0.0 | 10.0 | 8.0 | 13.18 | DeltaKronecker-all | 104.16.9.20 |
| 73.63 | trojan | 409.7 | 972.3 | 18.29 | 0.0 | 10.0 | 12.88 | 19.78 | Au1rxx-base64 | 64.94.95.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 69 | 81 | prefer |
| Au1rxx-base64 | 0.931 | 0.879 | 198 | 1391 | prefer |
| DeltaKronecker-all | 0.917 | 0.843 | 127 | 5965 | prefer |
| mheidari-all | 0.764 | 0.688 | 77 | 18775 | prefer |
| Surfboard-tg-mixed | 0.639 | 0.56 | 184 | 5928 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4972 | observe |
| Epodonios-all | 0.255 | None | 0 | 6785 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6846 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4700 | observe |
| barry-far-vless | 0.255 | None | 0 | 5220 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4991 | observe |
| nscl5-all | 0.255 | None | 0 | 3331 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.231 | None | 0 | 1391 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 36 |
| 204 | TimeoutError | - | 28 |
| 204 | ProxyError | - | 24 |
| cn-block | TimeoutError | - | 18 |
| geo | ClientOSError | - | 13 |
| speed | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| speed | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
