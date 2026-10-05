# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-05 14:17:58 |
| 运行耗时 | 592.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98609 |
| 去重后节点 | 27263 |
| TCP 可达 | 3000 |
| 真实可用 | 413 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27263 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.4 |
| tcp | 46.4 |
| probe | 224.6 |
| real_test | 165.7 |
| generate | 146.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58353 |
| vmess | 15941 |
| shadowsocks | 11579 |
| trojan | 10369 |
| hysteria2 | 1422 |
| http | 636 |
| shadowsocksr | 171 |
| socks | 74 |
| anytls | 27 |
| tuic | 20 |
| hysteria | 17 |

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
| 81.66 | shadowsocks | 255.2 | 705.1 | 21.87 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 37.19.198.244 |
| 81.61 | shadowsocks | 257.6 | 712.6 | 21.82 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 37.19.198.160 |
| 81.55 | shadowsocks | 260.0 | 723.6 | 21.76 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 37.19.198.243 |
| 81.53 | shadowsocks | 260.9 | 721.2 | 21.74 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 37.19.198.236 |
| 81.2 | shadowsocks | 253.5 | 645.7 | 21.91 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 140.82.63.79 |
| 79.8 | hysteria2 | 385.4 | 1121.0 | 18.86 | 0.0 | 10.0 | 13.12 | 19.32 | Au1rxx-base64 | 129.213.91.185 |
| 79.48 | shadowsocks | 327.9 | 784.8 | 20.19 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 15.204.247.206 |
| 78.89 | shadowsocks | 353.3 | 908.5 | 19.6 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 185.156.47.97 |
| 78.82 | shadowsocks | 280.0 | 648.7 | 21.3 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 156.146.38.167 |
| 78.71 | shadowsocks | 287.4 | 657.7 | 21.13 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 156.146.38.170 |
| 78.19 | vless | 257.2 | 688.6 | 21.82 | 0.0 | 10.0 | 7.05 | 19.32 | Au1rxx-base64 | 159.89.87.21 |
| 78.15 | shadowsocks | 287.7 | 666.7 | 21.12 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 156.146.38.169 |
| 77.57 | vless | 284.2 | 722.7 | 21.2 | 0.0 | 10.0 | 7.05 | 19.32 | Au1rxx-base64 | 66.70.179.198 |
| 77.02 | shadowsocks | 283.1 | 645.2 | 21.22 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 156.146.38.168 |
| 76.57 | vless | 327.4 | 913.2 | 20.2 | 0.0 | 10.0 | 7.05 | 19.32 | Au1rxx-base64 | 137.184.218.169 |
| 75.49 | vless | 374.1 | 1038.6 | 19.12 | 0.0 | 10.0 | 7.05 | 19.32 | Au1rxx-base64 | 185.95.231.156 |
| 75.43 | shadowsocks | 311.6 | 622.7 | 20.57 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 173.244.56.9 |
| 75.05 | vless | 340.0 | 869.1 | 19.91 | 0.0 | 10.0 | 7.05 | 19.32 | Au1rxx-base64 | 169.40.42.212 |
| 74.34 | shadowsocks | 317.6 | 841.2 | 20.42 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 51.222.200.165 |
| 74.03 | shadowsocks | 334.9 | 615.2 | 20.03 | 0.0 | 10.0 | 14.47 | 19.32 | Au1rxx-base64 | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | 0.909 | 275 | 1816 | prefer |
| mheidari-all | 0.955 | 0.889 | 54 | 23423 | prefer |
| Surfboard-tg-mixed | 0.818 | 0.743 | 105 | 7151 | prefer |
| ermaozi | 0.535 | 0.507 | 69 | 701 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 172 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5111 | observe |
| Epodonios-all | 0.255 | None | 0 | 7645 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9203 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5695 | observe |
| barry-far-vless | 0.255 | None | 0 | 5930 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4375 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1816 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 32 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyConnectionError | - | 8 |
| speed | ClientOSError | - | 7 |
| geo | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| speed | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:41949: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
