# AutoNodes 每日报告

生成时间：2026-08-18 06:58:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 91021 |
| 去重后节点数 | 23861 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1200 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23861 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 35.8 |
| geo | 1.0 |
| probe | 77.8 |
| real_test | 259.6 |
| tcp | 36.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 21 | 16 | 5 | 76.2% |
| shadowsocks | 167 | 158 | 9 | 94.6% |
| socks | 9 | 7 | 2 | 77.8% |
| trojan | 760 | 745 | 15 | 98.0% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 489 | 146 | 343 | 29.9% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 127 |
| speed:TimeoutError | 96 |
| geo:ClientOSError | 72 |
| speed:ClientOSError | 32 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 7 |
| cn-block:ClientOSError | 6 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4581 |
| ConnectionRefusedError | 886 |
| gaierror | 384 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | prefer | 172 | 0.93 | 6138 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Au1rxx-base64 | 0.901 | prefer | 816 | 0.846 | 1408 |
| mheidari-all | 0.568 | observe | 439 | 0.487 | 21284 |
| nscl5-all | 0.438 | observe | 3 | 1.0 | 2992 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 6329 |
| DeltaKronecker-all | 0.332 | observe | 14 | 0.286 | 5725 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5068 |
| Epodonios-all | 0.255 | observe | 0 | None | 6730 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3986 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.286 | 4 | 10 | 14 |
| mheidari-all | 0.487 | 214 | 225 | 439 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.846 | 690 | 126 | 816 |
| Surfboard-tg-mixed | 0.93 | 160 | 12 | 172 |
| nscl5-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21284 | yes | 4.54 | 0 |
| SoliSpirit-all | 6856 | yes | 3.04 | 0 |
| Epodonios-all | 6730 | yes | 2.48 | 0 |
| xiaoji235-airport-v2ray-all | 6329 | yes | 1.81 | 0 |
| Surfboard-tg-mixed | 6138 | yes | 2.32 | 0 |
| DeltaKronecker-all | 5725 | yes | 4.55 | 0 |
| barry-far-vless | 5074 | yes | 0.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 5068 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 4777 | yes | 3.68 | 0 |
| mahdibland-V2RayAggregator | 4045 | yes | 2.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| tuic | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 199 |
| speed | 128 |
| 204 | 27 |
| cn-block | 22 |
