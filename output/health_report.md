# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-30 20:53:44 |
| 运行耗时 | 260.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 79345 |
| 去重后节点 | 21873 |
| TCP 可达 | 3000 |
| 真实可用 | 594 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21873 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.5 |
| tcp | 34.6 |
| probe | 52.3 |
| real_test | 128.9 |
| generate | 36.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49795 |
| vmess | 10742 |
| shadowsocks | 10258 |
| trojan | 6651 |
| hysteria2 | 1516 |
| http | 168 |
| shadowsocksr | 120 |
| socks | 82 |
| hysteria | 7 |
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
| 83.26 | vless | 235.4 | 635.3 | 22.33 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 83.15 | vless | 240.0 | 649.5 | 22.22 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 204.48.20.223 |
| 82.94 | vless | 249.2 | 630.5 | 22.01 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 172.105.104.54 |
| 82.77 | vless | 256.4 | 671.5 | 21.84 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 38.77.133.141 |
| 82.61 | vless | 263.5 | 633.9 | 21.68 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.184 |
| 82.49 | vless | 265.3 | 696.0 | 21.64 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.35 |
| 82.15 | vless | 283.4 | 749.3 | 21.22 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.173 |
| 81.92 | vless | 293.2 | 652.9 | 20.99 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.223 |
| 81.58 | vless | 307.9 | 838.6 | 20.65 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 79.127.243.217 |
| 81.4 | vless | 315.7 | 721.1 | 20.47 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.16 |
| 81.4 | vless | 315.9 | 719.8 | 20.47 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.212 |
| 80.99 | vless | 333.5 | 840.6 | 20.06 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.225 |
| 80.71 | shadowsocks | 233.8 | 630.6 | 22.37 | 0.0 | 10.0 | 13.24 | 19.1 | Au1rxx-base64 | 37.19.198.236 |
| 80.67 | shadowsocks | 235.2 | 644.8 | 22.33 | 0.0 | 10.0 | 13.24 | 19.1 | Au1rxx-base64 | 37.19.198.244 |
| 80.62 | vless | 297.7 | 740.2 | 20.89 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.15 |
| 80.5 | vless | 354.7 | 911.5 | 19.57 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.89 |
| 80.48 | vless | 261.4 | 691.1 | 21.73 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.74 |
| 80.46 | shadowsocks | 244.6 | 677.0 | 22.12 | 0.0 | 10.0 | 13.24 | 19.1 | Au1rxx-base64 | 37.19.198.243 |
| 80.36 | vless | 324.4 | 815.0 | 20.27 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 66.70.179.198 |
| 80.34 | vless | 361.5 | 922.7 | 19.41 | 0.0 | 10.0 | 11.83 | 19.1 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.949 | 335 | 1804 | prefer |
| zhangkai | 0.89 | 0.917 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.864 | 0.787 | 174 | 6963 | prefer |
| DeltaKronecker-all | 0.795 | 0.718 | 149 | 5576 | prefer |
| mheidari-all | 0.699 | 1.0 | 10 | 14482 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4762 | observe |
| Epodonios-all | 0.255 | None | 0 | 7411 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7545 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5857 | observe |
| barry-far-vless | 0.255 | None | 0 | 6057 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4041 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 26 |
| cn-block | TimeoutError | - | 24 |
| geo | ClientOSError | - | 13 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 6 |
| speed | TimeoutError | - | 4 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
