# AutoNodes 每日报告

生成时间：2026-07-26 13:45:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 81669 |
| 去重后节点数 | 22638 |
| TCP 可达数 | 3000 |
| 真测通过数 | 726 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22638 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 44.5 |
| geo | 1.3 |
| probe | 67.6 |
| real_test | 160.9 |
| tcp | 32.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 7 | 0 | 100.0% |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 11 | 9 | 2 | 81.8% |
| shadowsocks | 134 | 115 | 19 | 85.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 464 | 422 | 42 | 90.9% |
| vless | 267 | 96 | 171 | 36.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 80 |
| speed:ClientOSError | 41 |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 23 |
| cn-block:ClientOSError | 18 |
| geo:ClientOSError | 17 |
| speed:TimeoutError | 10 |
| 204:ProxyError | 8 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| speed:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4362 |
| ConnectionRefusedError | 688 |
| gaierror | 267 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | prefer | 458 | 0.939 | 1458 |
| zhangkai | 0.991 | prefer | 76 | 1.0 | 86 |
| DeltaKronecker-all | 0.717 | prefer | 144 | 0.639 | 5950 |
| mheidari-all | 0.549 | observe | 209 | 0.469 | 17236 |
| tg-oneclickvpnkeys | 0.519 | observe | 7 | 1.0 | 149 |
| Surfboard-tg-mixed | 0.434 | observe | 63 | 0.349 | 5591 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 6731 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 200 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.349 | 22 | 41 | 63 |
| mheidari-all | 0.469 | 98 | 111 | 209 |
| DeltaKronecker-all | 0.639 | 92 | 52 | 144 |
| Au1rxx-base64 | 0.939 | 430 | 28 | 458 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 7 | 0 | 7 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17236 | yes | 4.41 | 0 |
| Epodonios-all | 6731 | yes | 2.48 | 0 |
| SoliSpirit-all | 6620 | yes | 2.6 | 0 |
| DeltaKronecker-all | 5950 | yes | 4.84 | 0 |
| Surfboard-tg-mixed | 5591 | yes | 3.85 | 0 |
| barry-far-vless | 5039 | yes | 0.97 | 0 |
| mahdibland-V2RayAggregator | 4980 | yes | 2.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 1.42 | 0 |
| Surfboard-tg-vless | 4351 | yes | 3.67 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 98 |
| speed | 54 |
| cn-block | 46 |
| 204 | 38 |
