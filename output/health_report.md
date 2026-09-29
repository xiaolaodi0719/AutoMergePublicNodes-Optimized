# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-29 05:23:04 |
| 运行耗时 | 850.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96799 |
| 去重后节点 | 27001 |
| TCP 可达 | 3000 |
| 真实可用 | 543 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27001 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.4 |
| tcp | 44.6 |
| probe | 289.4 |
| real_test | 416.1 |
| generate | 91.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59492 |
| vmess | 14852 |
| shadowsocks | 11297 |
| trojan | 8876 |
| hysteria2 | 1344 |
| http | 643 |
| shadowsocksr | 170 |
| socks | 78 |
| anytls | 24 |
| hysteria | 15 |
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
| 84.0 | vless | 233.2 | 616.6 | 22.38 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 195.123.235.177 |
| 83.52 | vless | 253.9 | 657.1 | 21.9 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 159.89.87.21 |
| 83.3 | vless | 261.2 | 628.0 | 21.73 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.225 |
| 82.8 | vless | 285.1 | 616.3 | 21.18 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.75 |
| 82.47 | vless | 299.3 | 734.8 | 20.85 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 66.70.179.198 |
| 82.08 | vless | 316.1 | 727.2 | 20.46 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.163 |
| 82.07 | vless | 316.6 | 860.3 | 20.45 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.104 |
| 82.03 | shadowsocks | 261.1 | 727.0 | 21.73 | 0.0 | 10.0 | 14.52 | 19.78 | Surfboard-tg-mixed | 37.19.198.244 |
| 81.66 | vless | 334.2 | 906.2 | 20.04 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.182 |
| 81.5 | shadowsocks | 262.6 | 651.0 | 21.7 | 0.0 | 10.0 | 14.52 | 19.78 | Surfboard-tg-mixed | 140.82.63.79 |
| 81.47 | vless | 342.5 | 885.0 | 19.85 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.224 |
| 81.46 | vless | 342.9 | 814.6 | 19.84 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.133 |
| 81.37 | vless | 346.9 | 815.6 | 19.75 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.173 |
| 81.27 | vless | 351.1 | 973.8 | 19.65 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 185.95.231.233 |
| 81.09 | vless | 358.8 | 928.0 | 19.47 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.229 |
| 81.07 | vless | 327.4 | 898.3 | 20.2 | 0.0 | 9.25 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.235 |
| 81.06 | vless | 329.4 | 900.0 | 20.15 | 0.0 | 9.29 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.74 |
| 81.01 | vless | 362.2 | 866.6 | 19.39 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.89 |
| 80.91 | vless | 366.5 | 948.3 | 19.29 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.202 |
| 80.72 | vless | 374.9 | 891.6 | 19.1 | 0.0 | 10.0 | 12.42 | 19.2 | Au1rxx-base64 | 169.40.42.16 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.865 | 0.803 | 350 | 1609 | prefer |
| Surfboard-tg-mixed | 0.769 | 0.691 | 217 | 7005 | prefer |
| ermaozi | 0.724 | 0.724 | 29 | 354 | prefer |
| DeltaKronecker-all | 0.482 | 0.5 | 14 | 5428 | observe |
| mheidari-all | 0.337 | 0.256 | 317 | 22589 | observe |
| ermaozi-get_subscribe | 0.308 | 0.6 | 5 | 367 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5326 | observe |
| Epodonios-all | 0.255 | None | 0 | 7625 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9567 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5633 | observe |
| barry-far-vless | 0.255 | None | 0 | 6028 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4237 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1609 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 129 |
| speed | TimeoutError | - | 85 |
| speed | ClientOSError | - | 70 |
| geo | ClientOSError | - | 39 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyError | - | 17 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| speed | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
