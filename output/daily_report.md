# AutoNodes 每日报告

生成时间：2026-08-18 18:50:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 93067 |
| 去重后节点数 | 24081 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1075 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24081 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 27.7 |
| geo | 0.8 |
| probe | 76.8 |
| real_test | 237.0 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 126 | 1 | 99.2% |
| hysteria2 | 20 | 17 | 3 | 85.0% |
| shadowsocks | 93 | 84 | 9 | 90.3% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 776 | 770 | 6 | 99.2% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 148 | 76 | 72 | 51.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 36 |
| speed:TimeoutError | 18 |
| cn-block:TimeoutError | 11 |
| 204:TimeoutError | 8 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 5 |
| speed:ClientOSError | 3 |
| 204:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4709 |
| ConnectionRefusedError | 921 |
| gaierror | 343 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 639 | 0.987 | 1643 |
| zhangkai | 0.991 | prefer | 127 | 0.992 | 159 |
| mheidari-all | 0.872 | prefer | 378 | 0.794 | 22150 |
| Surfboard-tg-mixed | 0.828 | prefer | 18 | 0.833 | 6301 |
| nscl5-all | 0.349 | observe | 3 | 0.667 | 2992 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 5725 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5068 |
| Epodonios-all | 0.255 | observe | 0 | None | 6927 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7150 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| nscl5-all | 0.667 | 2 | 1 | 3 |
| mheidari-all | 0.794 | 300 | 78 | 378 |
| Surfboard-tg-mixed | 0.833 | 15 | 3 | 18 |
| Au1rxx-base64 | 0.987 | 631 | 8 | 639 |
| zhangkai | 0.992 | 126 | 1 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22150 | yes | 5.44 | 0 |
| SoliSpirit-all | 7150 | yes | 3.72 | 0 |
| Epodonios-all | 6927 | yes | 0.34 | 0 |
| xiaoji235-airport-v2ray-all | 6329 | yes | 1.63 | 0 |
| Surfboard-tg-mixed | 6301 | yes | 4.18 | 0 |
| DeltaKronecker-all | 5725 | yes | 5.49 | 0 |
| barry-far-vless | 5149 | yes | 2.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 5068 | yes | 2.6 | 0 |
| Surfboard-tg-vless | 4855 | yes | 3.45 | 0 |
| mahdibland-V2RayAggregator | 4035 | yes | 0.42 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| tuic | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 42 |
| speed | 21 |
| cn-block | 16 |
| 204 | 16 |
