# AutoNodes 每日报告

生成时间：2026-09-28 23:13:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97528 |
| 去重后节点数 | 27021 |
| TCP 可达数 | 3000 |
| 真测通过数 | 373 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27021 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 77.5 |
| geo | 1.6 |
| probe | 174.6 |
| real_test | 115.8 |
| tcp | 44.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 36 | 11 | 25 | 30.6% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 124 | 121 | 3 | 97.6% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 21 | 18 | 3 | 85.7% |
| vless | 236 | 196 | 40 | 83.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 23 |
| 204:ProxyError | 17 |
| 204:ProxyConnectionError | 13 |
| cn-block:TimeoutError | 6 |
| speed:TimeoutError | 5 |
| geo:TimeoutError | 4 |
| 204:TimeoutError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5989 |
| ConnectionRefusedError | 1004 |
| gaierror | 417 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.989 | prefer | 20 | 0.95 | 7142 |
| Au1rxx-base64 | 0.96 | prefer | 298 | 0.896 | 1674 |
| mheidari-all | 0.891 | prefer | 88 | 0.818 | 22856 |
| DeltaKronecker-all | 0.438 | observe | 3 | 1.0 | 5428 |
| ermaozi | 0.358 | observe | 30 | 0.333 | 344 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 121 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5326 |
| Epodonios-all | 0.255 | observe | 0 | None | 7535 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9706 |

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
| downweight | ermaozi-get_subscribe | 0.151 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.167 | 1 | 5 | 6 |
| ermaozi | 0.333 | 10 | 20 | 30 |
| mheidari-all | 0.818 | 72 | 16 | 88 |
| Au1rxx-base64 | 0.896 | 267 | 31 | 298 |
| Surfboard-tg-mixed | 0.95 | 19 | 1 | 20 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22856 | yes | 6.21 | 0 |
| SoliSpirit-all | 9706 | yes | 2.78 | 0 |
| Epodonios-all | 7535 | yes | 3.36 | 0 |
| Surfboard-tg-mixed | 7142 | yes | 3.72 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.4 | 0 |
| barry-far-vless | 6027 | yes | 1.76 | 0 |
| Surfboard-tg-vless | 5799 | yes | 3.96 | 0 |
| DeltaKronecker-all | 5428 | yes | 6.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 5326 | yes | 3.05 | 0 |
| mahdibland-V2RayAggregator | 4237 | yes | 1.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 32 |
| speed | 29 |
| cn-block | 8 |
| geo | 5 |
