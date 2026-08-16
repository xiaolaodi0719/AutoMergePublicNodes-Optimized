# AutoNodes 每日报告

生成时间：2026-08-16 18:41:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 79898 |
| 去重后节点数 | 21944 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1032 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21944 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 34.5 |
| geo | 0.6 |
| probe | 69.5 |
| real_test | 231.4 |
| tcp | 33.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 22 | 18 | 4 | 81.8% |
| shadowsocks | 133 | 115 | 18 | 86.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 587 | 582 | 5 | 99.1% |
| vless | 255 | 186 | 69 | 72.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 17 |
| speed:TimeoutError | 16 |
| geo:TimeoutError | 13 |
| 204:ProxyError | 9 |
| geo:ClientOSError | 8 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4186 |
| ConnectionRefusedError | 815 |
| gaierror | 326 |
| OSError | 14 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 754 | 0.958 | 1994 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.873 | prefer | 138 | 0.797 | 17005 |
| Surfboard-tg-mixed | 0.809 | prefer | 94 | 0.734 | 5798 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 2601 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 174 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1994 |
| Epodonios-all | 0.255 | observe | 0 | None | 6468 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3982 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| DeltaKronecker-all | 0.134 | downweight | 11 | 0.0 | 0 | 5092 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.134 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 11 | 11 |
| Surfboard-tg-mixed | 0.734 | 69 | 25 | 94 |
| mheidari-all | 0.797 | 110 | 28 | 138 |
| Au1rxx-base64 | 0.958 | 722 | 32 | 754 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17005 | yes | 3.81 | 0 |
| SoliSpirit-all | 7449 | yes | 3.33 | 0 |
| Epodonios-all | 6468 | yes | 4.24 | 0 |
| Surfboard-tg-mixed | 5798 | yes | 3.16 | 0 |
| DeltaKronecker-all | 5092 | yes | 4.14 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 3.76 | 0 |
| barry-far-vless | 4856 | yes | 2.68 | 0 |
| Surfboard-tg-vless | 4549 | yes | 2.93 | 0 |
| mahdibland-V2RayAggregator | 4025 | yes | 0.75 | 0 |
| MatinGhanbari-all-sub | 3982 | yes | 2.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 30 |
| geo | 23 |
| cn-block | 23 |
| speed | 21 |
