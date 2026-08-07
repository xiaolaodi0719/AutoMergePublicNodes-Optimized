# AutoNodes 每日报告

生成时间：2026-08-07 00:10:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 88824 |
| 去重后节点数 | 24624 |
| TCP 可达数 | 3000 |
| 真测通过数 | 464 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24624 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 33.6 |
| geo | 1.4 |
| probe | 54.0 |
| real_test | 118.4 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 162 | 148 | 14 | 91.4% |
| socks | 8 | 5 | 3 | 62.5% |
| trojan | 179 | 159 | 20 | 88.8% |
| vless | 315 | 111 | 204 | 35.2% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 108 |
| geo:ClientOSError | 36 |
| speed:TimeoutError | 27 |
| speed:ClientOSError | 25 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 8 |
| 204:ProxyError | 7 |
| cn-block:ProxyError | 6 |
| geo:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4877 |
| ConnectionRefusedError | 832 |
| gaierror | 351 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 331 | 0.937 | 1327 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.563 | observe | 199 | 0.482 | 5904 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 5184 |
| DeltaKronecker-all | 0.334 | observe | 65 | 0.246 | 5897 |
| mheidari-all | 0.312 | observe | 80 | 0.225 | 20787 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5219 |
| Epodonios-all | 0.255 | observe | 0 | None | 6481 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| nscl5-all | 0.154 | observe | 3 | 0.0 | 0 | 1621 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.145 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 3 | 3 |
| ninja-vless | 0.0 | 0 | 5 | 5 |
| mheidari-all | 0.225 | 18 | 62 | 80 |
| DeltaKronecker-all | 0.246 | 16 | 49 | 65 |
| Surfboard-tg-mixed | 0.482 | 96 | 103 | 199 |
| Au1rxx-base64 | 0.937 | 310 | 21 | 331 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20787 | yes | 4.11 | 0 |
| SoliSpirit-all | 7217 | yes | 3.57 | 0 |
| Epodonios-all | 6481 | yes | 5.07 | 0 |
| Surfboard-tg-mixed | 5904 | yes | 3.01 | 0 |
| DeltaKronecker-all | 5897 | yes | 4.5 | 0 |
| mahdibland-V2RayAggregator | 5225 | yes | 1.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 5219 | yes | 1.81 | 0 |
| xiaoji235-airport-v2ray-all | 5184 | yes | 2.0 | 0 |
| barry-far-vless | 5041 | yes | 1.63 | 0 |
| Surfboard-tg-vless | 4729 | yes | 2.84 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 148 |
| speed | 54 |
| cn-block | 25 |
| 204 | 17 |
