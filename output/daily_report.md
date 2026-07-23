# AutoNodes 每日报告

生成时间：2026-07-23 14:17:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83515 |
| 去重后节点数 | 22816 |
| TCP 可达数 | 3000 |
| 真测通过数 | 712 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22816 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 33.5 |
| geo | 1.2 |
| probe | 58.7 |
| real_test | 171.3 |
| tcp | 32.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 140 | 118 | 22 | 84.3% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 490 | 438 | 52 | 89.4% |
| vless | 355 | 115 | 240 | 32.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 132 |
| speed:ClientOSError | 58 |
| cn-block:TimeoutError | 54 |
| geo:ClientOSError | 17 |
| 204:ProxyError | 14 |
| 204:TimeoutError | 13 |
| speed:TimeoutError | 13 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 5 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4370 |
| ConnectionRefusedError | 677 |
| gaierror | 286 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.818 | prefer | 199 | 0.804 | 432 |
| mheidari-all | 0.764 | prefer | 498 | 0.685 | 19424 |
| DeltaKronecker-all | 0.683 | observe | 56 | 0.607 | 5572 |
| Surfboard-tg-mixed | 0.668 | observe | 236 | 0.589 | 5390 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 4399 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4757 |
| Epodonios-all | 0.255 | observe | 0 | None | 6487 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7332 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.589 | 139 | 97 | 236 |
| DeltaKronecker-all | 0.607 | 34 | 22 | 56 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| mheidari-all | 0.685 | 341 | 157 | 498 |
| Au1rxx-base64 | 0.804 | 160 | 39 | 199 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19424 | yes | 3.5 | 0 |
| SoliSpirit-all | 7332 | yes | 2.54 | 0 |
| Epodonios-all | 6487 | yes | 1.78 | 0 |
| DeltaKronecker-all | 5572 | yes | 3.63 | 0 |
| Surfboard-tg-mixed | 5390 | yes | 2.11 | 0 |
| mahdibland-V2RayAggregator | 4954 | yes | 1.49 | 0 |
| barry-far-vless | 4823 | yes | 2.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 4757 | yes | 1.63 | 0 |
| xiaoji235-airport-v2ray-all | 4399 | yes | 1.16 | 0 |
| Surfboard-tg-vless | 4196 | yes | 1.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 149 |
| speed | 72 |
| cn-block | 66 |
| 204 | 30 |
