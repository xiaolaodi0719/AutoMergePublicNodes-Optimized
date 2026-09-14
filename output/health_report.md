# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 04:29:33 |
| 运行耗时 | 763.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84465 |
| 去重后节点 | 23126 |
| TCP 可达 | 3000 |
| 真实可用 | 494 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23126 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 38.7 |
| probe | 281.5 |
| real_test | 354.9 |
| generate | 82.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51689 |
| vmess | 12739 |
| shadowsocks | 9741 |
| trojan | 7895 |
| hysteria2 | 1517 |
| http | 670 |
| shadowsocksr | 131 |
| socks | 53 |
| tuic | 16 |
| hysteria | 11 |
| anytls | 3 |

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
| 83.16 | vless | 225.1 | 595.5 | 22.57 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 195.123.235.177 |
| 82.86 | vless | 237.8 | 675.1 | 22.27 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 79.141.172.154 |
| 82.8 | vless | 240.7 | 684.3 | 22.21 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 47.253.226.114 |
| 82.29 | vless | 262.6 | 695.1 | 21.7 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.133 |
| 82.14 | vless | 268.9 | 706.3 | 21.55 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 167.17.69.171 |
| 82.12 | vless | 269.8 | 687.4 | 21.53 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.35 |
| 81.91 | vless | 278.9 | 738.5 | 21.32 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.173 |
| 81.87 | vless | 280.9 | 629.7 | 21.28 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.179 |
| 81.56 | vless | 294.0 | 676.2 | 20.97 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.184 |
| 81.52 | vless | 296.0 | 676.3 | 20.93 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.232 |
| 81.19 | vless | 310.1 | 718.8 | 20.6 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.90 |
| 80.91 | vless | 322.3 | 831.0 | 20.32 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 66.70.179.198 |
| 80.69 | shadowsocks | 277.9 | 765.2 | 21.35 | 0.0 | 10.0 | 13.8 | 19.54 | Au1rxx-base64 | 198.98.53.130 |
| 80.61 | vless | 335.1 | 856.2 | 20.02 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.212 |
| 80.6 | vless | 291.6 | 656.6 | 21.03 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 198.251.78.29 |
| 80.54 | vless | 338.3 | 945.7 | 19.95 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 185.95.231.156 |
| 80.39 | vless | 344.8 | 819.8 | 19.8 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.104 |
| 80.31 | vless | 347.9 | 826.7 | 19.72 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.15 |
| 80.1 | vless | 357.1 | 973.1 | 19.51 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.168 |
| 79.85 | vless | 367.9 | 798.8 | 19.26 | 0.0 | 10.0 | 11.05 | 19.54 | Au1rxx-base64 | 169.40.42.229 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.846 | 0.781 | 319 | 1684 | prefer |
| Surfboard-tg-mixed | 0.72 | 0.642 | 201 | 7482 | prefer |
| ermaozi | 0.709 | 0.7 | 50 | 417 | prefer |
| mheidari-all | 0.565 | 0.485 | 132 | 15963 | observe |
| roosterkid-openproxylist-v2ray | 0.406 | 1.0 | 4 | 150 | observe |
| ermaozi-get_subscribe | 0.384 | 0.625 | 8 | 444 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7945 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8786 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6107 | observe |
| barry-far-vless | 0.255 | None | 0 | 6350 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4222 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1684 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 48 |
| speed | TimeoutError | - | 48 |
| speed | ClientOSError | - | 42 |
| geo | ClientOSError | - | 41 |
| cn-block | TimeoutError | - | 29 |
| cn-block | ClientOSError | - | 25 |
| 204 | ProxyError | - | 19 |
| 204 | TimeoutError | - | 14 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
