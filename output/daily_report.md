# AutoNodes 每日报告

生成时间：2026-08-01 03:31:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 78571 |
| 去重后节点数 | 22863 |
| TCP 可达数 | 3000 |
| 真测通过数 | 660 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22863 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 39.1 |
| geo | 1.4 |
| probe | 56.9 |
| real_test | 166.0 |
| tcp | 34.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 80 | 80 | 0 | 100.0% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 163 | 151 | 12 | 92.6% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 48 | 33 | 15 | 68.8% |
| vless | 712 | 372 | 340 | 52.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 170 |
| speed:TimeoutError | 55 |
| speed:ClientOSError | 52 |
| geo:ClientOSError | 36 |
| cn-block:TimeoutError | 29 |
| 204:TimeoutError | 9 |
| cn-block:ProxyError | 5 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4554 |
| ConnectionRefusedError | 758 |
| gaierror | 261 |
| OSError | 224 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 80 | 1.0 | 110 |
| Au1rxx-base64 | 0.923 | prefer | 533 | 0.857 | 1664 |
| Surfboard-tg-mixed | 0.588 | observe | 124 | 0.508 | 5365 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| DeltaKronecker-all | 0.294 | observe | 269 | 0.212 | 5144 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5507 |
| Epodonios-all | 0.255 | observe | 0 | None | 6122 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6657 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.175 | 17 | 0.059 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.059 | 1 | 16 | 17 |
| DeltaKronecker-all | 0.212 | 57 | 212 | 269 |
| Surfboard-tg-mixed | 0.508 | 63 | 61 | 124 |
| Au1rxx-base64 | 0.857 | 457 | 76 | 533 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 80 | 0 | 80 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16450 | yes | 5.05 | 0 |
| SoliSpirit-all | 6657 | yes | 3.95 | 0 |
| Epodonios-all | 6122 | yes | 0.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 5507 | yes | 2.89 | 0 |
| Surfboard-tg-mixed | 5365 | yes | 3.62 | 0 |
| DeltaKronecker-all | 5144 | yes | 5.26 | 0 |
| mahdibland-V2RayAggregator | 5081 | yes | 1.84 | 0 |
| barry-far-vless | 4596 | yes | 2.61 | 0 |
| Surfboard-tg-vless | 4239 | yes | 3.45 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.97 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 207 |
| speed | 107 |
| cn-block | 38 |
| 204 | 16 |
