# AutoNodes 每日报告

生成时间：2026-09-23 21:28:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 96813 |
| 去重后节点数 | 26642 |
| TCP 可达数 | 3000 |
| 真测通过数 | 414 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26642 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 71.8 |
| geo | 1.4 |
| probe | 269.1 |
| real_test | 158.9 |
| tcp | 43.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 36 | 25 | 11 | 69.4% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 164 | 150 | 14 | 91.5% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 22 | 19 | 3 | 86.4% |
| vless | 244 | 202 | 42 | 82.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 14 |
| cn-block:ClientOSError | 9 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| speed:ClientOSError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5878 |
| ConnectionRefusedError | 965 |
| gaierror | 410 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.967 | prefer | 252 | 0.905 | 1635 |
| mheidari-all | 0.906 | prefer | 84 | 0.833 | 22531 |
| Surfboard-tg-mixed | 0.854 | prefer | 113 | 0.779 | 7072 |
| ermaozi | 0.793 | prefer | 30 | 0.8 | 291 |
| DeltaKronecker-all | 0.391 | observe | 2 | 1.0 | 6471 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4332 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5131 |
| Epodonios-all | 0.255 | observe | 0 | None | 7534 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8842 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.141 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| Surfboard-tg-mixed | 0.779 | 88 | 25 | 113 |
| ermaozi | 0.8 | 24 | 6 | 30 |
| mheidari-all | 0.833 | 70 | 14 | 84 |
| Au1rxx-base64 | 0.905 | 228 | 24 | 252 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22531 | yes | 4.07 | 0 |
| SoliSpirit-all | 8842 | yes | 1.68 | 0 |
| Epodonios-all | 7534 | yes | 2.36 | 0 |
| Surfboard-tg-mixed | 7072 | yes | 3.12 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.65 | 0 |
| DeltaKronecker-all | 6471 | yes | 4.62 | 0 |
| barry-far-vless | 5930 | yes | 0.76 | 0 |
| Surfboard-tg-vless | 5711 | yes | 3.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 1.0 | 0 |
| mahdibland-V2RayAggregator | 4332 | yes | 2.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 36 |
| cn-block | 27 |
| speed | 9 |
| geo | 5 |
