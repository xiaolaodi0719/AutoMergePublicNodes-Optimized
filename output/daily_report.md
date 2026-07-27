# AutoNodes 每日报告

生成时间：2026-07-27 03:43:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 83507 |
| 去重后节点数 | 22089 |
| TCP 可达数 | 3000 |
| 真测通过数 | 978 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22089 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 33.3 |
| geo | 0.9 |
| probe | 75.5 |
| real_test | 232.5 |
| tcp | 31.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 6 | 0 | 100.0% |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 154 | 140 | 14 | 90.9% |
| socks | 29 | 24 | 5 | 82.8% |
| trojan | 465 | 448 | 17 | 96.3% |
| vless | 756 | 272 | 484 | 36.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 193 |
| speed:ClientOSError | 179 |
| speed:TimeoutError | 50 |
| geo:ClientOSError | 42 |
| cn-block:TimeoutError | 24 |
| 204:TimeoutError | 12 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4335 |
| ConnectionRefusedError | 713 |
| gaierror | 256 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 76 | 1.0 | 86 |
| Au1rxx-base64 | 0.987 | prefer | 554 | 0.93 | 1476 |
| Surfboard-tg-mixed | 0.554 | observe | 114 | 0.474 | 5483 |
| DeltaKronecker-all | 0.529 | observe | 67 | 0.448 | 4320 |
| mheidari-all | 0.519 | observe | 668 | 0.439 | 19312 |
| tg-oneclickvpnkeys | 0.483 | observe | 6 | 1.0 | 149 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3959 |
| tg-Farah_VPN | 0.263 | observe | 1 | 1.0 | 200 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6493 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.14 | downweight | 6 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.14 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 6 | 6 |
| mheidari-all | 0.439 | 293 | 375 | 668 |
| DeltaKronecker-all | 0.448 | 30 | 37 | 67 |
| Surfboard-tg-mixed | 0.474 | 54 | 60 | 114 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.93 | 515 | 39 | 554 |
| tg-Farah_VPN | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19312 | yes | 5.07 | 0 |
| Epodonios-all | 6493 | yes | 2.39 | 0 |
| SoliSpirit-all | 6284 | yes | 3.57 | 0 |
| Surfboard-tg-mixed | 5483 | yes | 3.53 | 0 |
| mahdibland-V2RayAggregator | 5003 | yes | 2.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 2.26 | 0 |
| barry-far-vless | 4841 | yes | 1.05 | 0 |
| DeltaKronecker-all | 4320 | yes | 4.87 | 0 |
| Surfboard-tg-vless | 4173 | yes | 4.57 | 0 |
| MatinGhanbari-all-sub | 3963 | yes | 1.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 237 |
| speed | 229 |
| cn-block | 32 |
| 204 | 24 |
