# AutoNodes 每日报告

生成时间：2026-07-24 08:39:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83120 |
| 去重后节点数 | 22640 |
| TCP 可达数 | 3000 |
| 真测通过数 | 617 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22640 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.8 |
| generate | 24.4 |
| geo | 1.0 |
| probe | 65.4 |
| real_test | 177.3 |
| tcp | 31.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 15 | 11 | 4 | 73.3% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 463 | 419 | 44 | 90.5% |
| vless | 489 | 146 | 343 | 29.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 155 |
| speed:ClientOSError | 76 |
| geo:ClientOSError | 42 |
| cn-block:TimeoutError | 40 |
| speed:TimeoutError | 36 |
| 204:ProxyError | 18 |
| 204:TimeoutError | 13 |
| geo:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4103 |
| ConnectionRefusedError | 679 |
| gaierror | 445 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.719 | prefer | 771 | 0.639 | 19618 |
| Surfboard-tg-mixed | 0.554 | observe | 114 | 0.474 | 5319 |
| DeltaKronecker-all | 0.448 | observe | 85 | 0.365 | 5559 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3847 |
| Au1rxx-base64 | 0.329 | observe | 2 | 1.0 | 432 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4588 |
| Epodonios-all | 0.255 | observe | 0 | None | 6546 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6796 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.365 | 31 | 54 | 85 |
| Surfboard-tg-mixed | 0.474 | 54 | 60 | 114 |
| mheidari-all | 0.639 | 493 | 278 | 771 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19618 | yes | 2.42 | 0 |
| SoliSpirit-all | 6796 | yes | 2.04 | 0 |
| Epodonios-all | 6546 | yes | 1.4 | 0 |
| DeltaKronecker-all | 5559 | yes | 3.16 | 0 |
| Surfboard-tg-mixed | 5319 | yes | 1.73 | 0 |
| mahdibland-V2RayAggregator | 5027 | yes | 0.16 | 0 |
| barry-far-vless | 4836 | yes | 1.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 4588 | yes | 1.37 | 0 |
| Surfboard-tg-vless | 4227 | yes | 1.62 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.24 | 0 |

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
| geo | 201 |
| speed | 113 |
| cn-block | 46 |
| 204 | 34 |
