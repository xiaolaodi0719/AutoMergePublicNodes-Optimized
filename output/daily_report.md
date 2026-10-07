# AutoNodes 每日报告

生成时间：2026-10-07 13:10:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 98660 |
| 去重后节点数 | 27303 |
| TCP 可达数 | 3000 |
| 真测通过数 | 418 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27303 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 77.8 |
| geo | 1.4 |
| probe | 237.8 |
| real_test | 233.6 |
| tcp | 46.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 1 | 7 | 12.5% |
| http | 38 | 22 | 16 | 57.9% |
| hysteria2 | 26 | 20 | 6 | 76.9% |
| shadowsocks | 156 | 143 | 13 | 91.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 103 | 79 | 24 | 76.7% |
| vless | 205 | 152 | 53 | 74.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 36 |
| 204:ProxyError | 24 |
| cn-block:TimeoutError | 21 |
| speed:ClientOSError | 10 |
| geo:ClientOSError | 8 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6558 |
| ConnectionRefusedError | 1024 |
| gaierror | 397 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 332 | 0.895 | 1830 |
| mheidari-all | 0.862 | prefer | 53 | 0.792 | 23381 |
| Surfboard-tg-mixed | 0.633 | observe | 83 | 0.554 | 7069 |
| ermaozi | 0.631 | observe | 41 | 0.61 | 664 |
| DeltaKronecker-all | 0.449 | observe | 19 | 0.368 | 5344 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7480 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9550 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5616 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.145 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-OutlineReleasedKey | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.125 | 1 | 7 | 8 |
| DeltaKronecker-all | 0.368 | 7 | 12 | 19 |
| Surfboard-tg-mixed | 0.554 | 46 | 37 | 83 |
| ermaozi | 0.61 | 25 | 16 | 41 |
| mheidari-all | 0.792 | 42 | 11 | 53 |
| Au1rxx-base64 | 0.895 | 297 | 35 | 332 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23381 | yes | 3.62 | 0 |
| SoliSpirit-all | 9550 | yes | 1.39 | 0 |
| Epodonios-all | 7480 | yes | 2.01 | 0 |
| Surfboard-tg-mixed | 7069 | yes | 2.21 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.88 | 0 |
| barry-far-vless | 5861 | yes | 1.1 | 0 |
| Surfboard-tg-vless | 5616 | yes | 2.3 | 0 |
| DeltaKronecker-all | 5344 | yes | 3.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 5138 | yes | 0.99 | 0 |
| mahdibland-V2RayAggregator | 4418 | yes | 1.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 64 |
| cn-block | 29 |
| speed | 14 |
| geo | 13 |
