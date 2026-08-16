# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-16 01:46:31 |
| 运行耗时 | 397.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 79337 |
| 去重后节点 | 22383 |
| TCP 可达 | 3000 |
| 真实可用 | 1139 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22383 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 0.9 |
| tcp | 34.3 |
| probe | 70.4 |
| real_test | 249.2 |
| generate | 36.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43312 |
| trojan | 14077 |
| vmess | 10719 |
| shadowsocks | 9827 |
| hysteria2 | 1032 |
| http | 182 |
| socks | 89 |
| shadowsocksr | 80 |
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
| 83.21 | hysteria2 | 299.1 | 713.4 | 20.85 | 0.0 | 10.0 | 13.5 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 82.65 | hysteria2 | 300.1 | 734.3 | 20.83 | 0.0 | 10.0 | 13.5 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 81.51 | vless | 258.6 | 606.8 | 21.79 | 0.0 | 9.8 | 11.31 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 81.37 | shadowsocks | 250.8 | 633.2 | 21.97 | 0.0 | 10.0 | 13.4 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.36 | shadowsocks | 251.2 | 622.3 | 21.96 | 0.0 | 10.0 | 13.4 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 81.26 | vless | 286.3 | 679.6 | 21.15 | 0.0 | 9.8 | 11.31 | 20.0 | Au1rxx-base64 | 198.251.78.29 |
| 81.25 | shadowsocks | 248.4 | 645.8 | 22.03 | 0.0 | 9.82 | 13.4 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.53 | shadowsocks | 279.3 | 675.8 | 21.31 | 0.0 | 9.82 | 13.4 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 80.41 | shadowsocks | 249.1 | 640.3 | 22.01 | 0.0 | 10.0 | 13.4 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 79.99 | http | 301.9 | 682.8 | 20.79 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 79.87 | http | 311.2 | 705.0 | 20.57 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 79.46 | vless | 329.9 | 736.0 | 20.14 | 0.0 | 9.8 | 11.31 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 79.44 | http | 344.0 | 793.5 | 19.81 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 79.39 | http | 353.5 | 829.0 | 19.6 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 79.21 | http | 350.7 | 800.2 | 19.66 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 79.07 | http | 312.5 | 691.4 | 20.54 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 78.97 | http | 280.2 | 566.4 | 21.29 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 78.89 | http | 282.4 | 567.9 | 21.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 78.89 | http | 326.4 | 730.0 | 20.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 78.8 | http | 279.8 | 560.5 | 21.3 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.977 | 784 | 1995 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.789 | 0.712 | 139 | 5707 | prefer |
| mheidari-all | 0.575 | 0.495 | 277 | 16315 | observe |
| nscl5-all | 0.391 | 1.0 | 2 | 2601 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 145 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1995 | observe |
| Epodonios-all | 0.255 | None | 0 | 6340 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3984 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7329 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4387 | observe |
| barry-far-vless | 0.255 | None | 0 | 4782 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3935 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 101 |
| speed | TimeoutError | - | 71 |
| cn-block | TimeoutError | - | 33 |
| geo | ClientOSError | - | 32 |
| speed | ClientOSError | - | 20 |
| 204 | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
