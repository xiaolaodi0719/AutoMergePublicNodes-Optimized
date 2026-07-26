# AutoNodes 每日报告

生成时间：2026-07-26 03:33:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 80527 |
| 去重后节点数 | 22462 |
| TCP 可达数 | 3000 |
| 真测通过数 | 904 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22462 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 21.9 |
| geo | 1.5 |
| probe | 66.0 |
| real_test | 191.7 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 153 | 138 | 15 | 90.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 624 | 598 | 26 | 95.8% |
| vless | 340 | 80 | 260 | 23.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 100 |
| speed:ClientOSError | 92 |
| speed:TimeoutError | 38 |
| geo:ClientOSError | 27 |
| cn-block:TimeoutError | 23 |
| 204:ProxyError | 7 |
| 204:TimeoutError | 6 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4168 |
| ConnectionRefusedError | 693 |
| gaierror | 297 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 76 | 1.0 | 119 |
| Au1rxx-base64 | 0.975 | prefer | 430 | 0.923 | 1341 |
| Surfboard-tg-mixed | 0.961 | prefer | 65 | 0.892 | 5462 |
| DeltaKronecker-all | 0.699 | observe | 216 | 0.62 | 5838 |
| mheidari-all | 0.655 | observe | 412 | 0.575 | 17224 |
| xiaoji235-airport-v2ray-all | 0.32 | observe | 1 | 1.0 | 1624 |
| tg-ConfigV2rayNG | 0.263 | observe | 1 | 1.0 | 200 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4879 |
| Epodonios-all | 0.255 | observe | 0 | None | 6569 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.145 | downweight | 5 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.145 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 5 | 5 |
| mheidari-all | 0.575 | 237 | 175 | 412 |
| DeltaKronecker-all | 0.62 | 134 | 82 | 216 |
| Surfboard-tg-mixed | 0.892 | 58 | 7 | 65 |
| Au1rxx-base64 | 0.923 | 397 | 33 | 430 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-ConfigV2rayNG | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 76 | 0 | 76 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17224 | yes | 4.43 | 0 |
| Epodonios-all | 6569 | yes | 3.17 | 0 |
| SoliSpirit-all | 6505 | yes | 3.18 | 0 |
| DeltaKronecker-all | 5838 | yes | 4.76 | 0 |
| Surfboard-tg-mixed | 5462 | yes | 3.94 | 0 |
| mahdibland-V2RayAggregator | 4980 | yes | 2.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4879 | yes | 2.35 | 0 |
| barry-far-vless | 4852 | yes | 1.89 | 0 |
| Surfboard-tg-vless | 4196 | yes | 4.74 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 1.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 130 |
| geo | 129 |
| cn-block | 29 |
| 204 | 15 |
