# AutoNodes 每日报告

生成时间：2026-09-29 22:12:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 96969 |
| 去重后节点数 | 27167 |
| TCP 可达数 | 3000 |
| 真测通过数 | 359 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27167 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 43.8 |
| geo | 1.5 |
| probe | 219.6 |
| real_test | 137.1 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 31 | 19 | 12 | 61.3% |
| hysteria2 | 23 | 23 | 0 | 100.0% |
| shadowsocks | 136 | 123 | 13 | 90.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 7 | 4 | 3 | 57.1% |
| vless | 253 | 184 | 69 | 72.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 31 |
| speed:TimeoutError | 15 |
| cn-block:TimeoutError | 15 |
| 204:ProxyConnectionError | 13 |
| 204:TimeoutError | 10 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 3 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5646 |
| ConnectionRefusedError | 1016 |
| gaierror | 396 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.892 | prefer | 288 | 0.823 | 1792 |
| mheidari-all | 0.862 | prefer | 122 | 0.787 | 22763 |
| ermaozi | 0.605 | observe | 30 | 0.6 | 291 |
| tg-oneclickvpnkeys | 0.36 | observe | 3 | 1.0 | 62 |
| ermaozi-get_subscribe | 0.323 | observe | 2 | 1.0 | 293 |
| Surfboard-tg-mixed | 0.32 | observe | 4 | 0.5 | 7082 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5314 |
| Epodonios-all | 0.255 | observe | 0 | None | 7556 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9172 |

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
| downweight | DeltaKronecker-all | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.143 | 1 | 6 | 7 |
| Surfboard-tg-mixed | 0.5 | 2 | 2 | 4 |
| ermaozi | 0.6 | 18 | 12 | 30 |
| mheidari-all | 0.787 | 96 | 26 | 122 |
| Au1rxx-base64 | 0.823 | 237 | 51 | 288 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22763 | yes | 6.4 | 0 |
| SoliSpirit-all | 9172 | yes | 2.55 | 0 |
| Epodonios-all | 7556 | yes | 3.48 | 0 |
| Surfboard-tg-mixed | 7082 | yes | 4.53 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.21 | 0 |
| barry-far-vless | 5942 | yes | 0.91 | 0 |
| Surfboard-tg-vless | 5695 | yes | 3.77 | 0 |
| DeltaKronecker-all | 5528 | yes | 6.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 5314 | yes | 1.16 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 0.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 46 |
| 204 | 29 |
| cn-block | 19 |
| geo | 4 |
