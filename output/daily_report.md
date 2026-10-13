# AutoNodes 每日报告

生成时间：2026-10-13 00:45:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 100924 |
| 去重后节点数 | 27887 |
| TCP 可达数 | 3000 |
| 真测通过数 | 483 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27887 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 92.0 |
| geo | 1.5 |
| probe | 413.2 |
| real_test | 693.8 |
| tcp | 47.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 28 | 12 | 16 | 42.9% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 119 | 116 | 3 | 97.5% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 124 | 115 | 9 | 92.7% |
| vless | 627 | 219 | 408 | 34.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 213 |
| speed:TimeoutError | 107 |
| geo:ClientOSError | 38 |
| speed:ClientOSError | 32 |
| 204:ProxyError | 17 |
| cn-block:TimeoutError | 15 |
| cn-block:ClientOSError | 7 |
| 204:ProxyConnectionError | 4 |
| 204:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6351 |
| ConnectionRefusedError | 1058 |
| gaierror | 417 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 336 | 0.935 | 1847 |
| Surfboard-tg-mixed | 0.48 | observe | 4 | 1.0 | 7208 |
| ermaozi | 0.479 | observe | 29 | 0.448 | 675 |
| mheidari-all | 0.355 | observe | 536 | 0.274 | 23897 |
| ermaozi-get_subscribe | 0.29 | observe | 3 | 0.667 | 532 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| Epodonios-all | 0.255 | observe | 0 | None | 7736 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10536 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5678 |

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
| downweight | DeltaKronecker-all | 0.243 | 11 | 0.182 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.182 | 2 | 9 | 11 |
| mheidari-all | 0.274 | 147 | 389 | 536 |
| ermaozi | 0.448 | 13 | 16 | 29 |
| ermaozi-get_subscribe | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.935 | 314 | 22 | 336 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23897 | yes | 7.95 | 0 |
| SoliSpirit-all | 10536 | yes | 4.7 | 0 |
| Epodonios-all | 7736 | yes | 7.28 | 0 |
| Surfboard-tg-mixed | 7208 | yes | 4.21 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.26 | 0 |
| barry-far-vless | 6023 | yes | 2.05 | 0 |
| DeltaKronecker-all | 5701 | yes | 5.87 | 0 |
| Surfboard-tg-vless | 5678 | yes | 5.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 5028 | yes | 3.05 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 3.76 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 251 |
| speed | 139 |
| 204 | 26 |
| cn-block | 25 |
