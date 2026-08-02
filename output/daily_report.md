# AutoNodes 每日报告

生成时间：2026-08-02 08:35:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 77313 |
| 去重后节点数 | 22742 |
| TCP 可达数 | 3000 |
| 真测通过数 | 673 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22742 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 31.6 |
| geo | 1.4 |
| probe | 60.6 |
| real_test | 158.0 |
| tcp | 34.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 143 | 140 | 3 | 97.9% |
| hysteria2 | 21 | 18 | 3 | 85.7% |
| shadowsocks | 153 | 124 | 29 | 81.0% |
| socks | 16 | 11 | 5 | 68.8% |
| trojan | 37 | 29 | 8 | 78.4% |
| vless | 538 | 351 | 187 | 65.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 94 |
| speed:TimeoutError | 44 |
| cn-block:TimeoutError | 20 |
| geo:ClientOSError | 19 |
| 204:TimeoutError | 17 |
| speed:ClientOSError | 14 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| geo:ProxyError | 4 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4681 |
| ConnectionRefusedError | 785 |
| gaierror | 299 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.978 | prefer | 219 | 0.968 | 344 |
| Au1rxx-base64 | 0.787 | prefer | 511 | 0.724 | 1589 |
| Surfboard-tg-mixed | 0.653 | observe | 108 | 0.574 | 5167 |
| DeltaKronecker-all | 0.591 | observe | 45 | 0.511 | 4549 |
| Epodonios-all | 0.335 | observe | 1 | 1.0 | 5764 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| chromego_merge | 0.258 | observe | 1 | 1.0 | 70 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5486 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.145 | downweight | 5 | 0.0 | 0 | 1791 |
| nscl5-all | 0.158 | observe | 2 | 0.0 | 0 | 1354 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.145 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mheidari-all | 0.193 | 10 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Au1rxx-clash | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 5 | 5 |
| mheidari-all | 0.1 | 1 | 9 | 10 |
| DeltaKronecker-all | 0.511 | 23 | 22 | 45 |
| Surfboard-tg-mixed | 0.574 | 62 | 46 | 108 |
| Au1rxx-base64 | 0.724 | 370 | 141 | 511 |
| zhangkai | 0.968 | 212 | 7 | 219 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16553 | yes | 5.58 | 0 |
| SoliSpirit-all | 6688 | yes | 4.58 | 0 |
| Epodonios-all | 5764 | yes | 3.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 5486 | yes | 3.31 | 0 |
| Surfboard-tg-mixed | 5167 | yes | 3.39 | 0 |
| mahdibland-V2RayAggregator | 5071 | yes | 2.9 | 0 |
| DeltaKronecker-all | 4549 | yes | 4.73 | 0 |
| barry-far-vless | 4406 | yes | 2.51 | 0 |
| Surfboard-tg-vless | 3990 | yes | 3.53 | 0 |
| MatinGhanbari-all-sub | 3969 | yes | 3.07 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 117 |
| speed | 60 |
| cn-block | 31 |
| 204 | 27 |
