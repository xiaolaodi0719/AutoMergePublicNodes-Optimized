# AutoNodes 每日报告

生成时间：2026-08-16 06:53:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 78586 |
| 去重后节点数 | 21818 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1146 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21818 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 31.6 |
| geo | 0.7 |
| probe | 69.7 |
| real_test | 224.5 |
| tcp | 31.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 23 | 21 | 2 | 91.3% |
| shadowsocks | 151 | 144 | 7 | 95.4% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 654 | 644 | 10 | 98.5% |
| vless | 354 | 209 | 145 | 59.0% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 59 |
| speed:TimeoutError | 38 |
| geo:ClientOSError | 16 |
| cn-block:TimeoutError | 12 |
| speed:ClientOSError | 12 |
| 204:TimeoutError | 11 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 3867 |
| ConnectionRefusedError | 802 |
| gaierror | 436 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 800 | 0.966 | 1997 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.789 | prefer | 204 | 0.711 | 5641 |
| mheidari-all | 0.768 | prefer | 136 | 0.691 | 16464 |
| nscl5-all | 0.287 | observe | 2 | 0.5 | 2601 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1997 |
| Epodonios-all | 0.255 | observe | 0 | None | 6328 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3986 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7355 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.243 | 41 | 0.146 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.146 | 6 | 35 | 41 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.691 | 94 | 42 | 136 |
| Surfboard-tg-mixed | 0.711 | 145 | 59 | 204 |
| Au1rxx-base64 | 0.966 | 773 | 27 | 800 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16464 | yes | 4.56 | 0 |
| SoliSpirit-all | 7355 | yes | 2.21 | 0 |
| Epodonios-all | 6328 | yes | 4.81 | 0 |
| Surfboard-tg-mixed | 5641 | yes | 3.63 | 0 |
| DeltaKronecker-all | 5092 | yes | 4.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 1.06 | 0 |
| barry-far-vless | 4736 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 4360 | yes | 3.41 | 0 |
| MatinGhanbari-all-sub | 3986 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 3950 | yes | 2.98 | 0 |

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
| geo | 75 |
| speed | 51 |
| 204 | 23 |
| cn-block | 18 |
