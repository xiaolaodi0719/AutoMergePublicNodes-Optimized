# AutoNodes 每日报告

生成时间：2026-08-04 08:50:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 85567 |
| 去重后节点数 | 24255 |
| TCP 可达数 | 3000 |
| 真测通过数 | 562 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24255 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 29.9 |
| geo | 1.3 |
| probe | 62.2 |
| real_test | 129.8 |
| tcp | 36.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 61 | 6 | 91.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 139 | 122 | 17 | 87.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 128 | 118 | 10 | 92.2% |
| vless | 461 | 241 | 220 | 52.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 145 |
| speed:TimeoutError | 23 |
| geo:ClientOSError | 20 |
| 204:ProxyError | 15 |
| speed:ClientOSError | 14 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4966 |
| ConnectionRefusedError | 797 |
| gaierror | 319 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.902 | prefer | 67 | 0.91 | 92 |
| Au1rxx-base64 | 0.833 | prefer | 597 | 0.767 | 1672 |
| mheidari-all | 0.413 | observe | 40 | 0.325 | 20242 |
| Surfboard-tg-mixed | 0.366 | observe | 75 | 0.28 | 5211 |
| SoliSpirit-all | 0.335 | observe | 1 | 1.0 | 6811 |
| DeltaKronecker-all | 0.33 | observe | 30 | 0.233 | 5788 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5251 |
| Epodonios-all | 0.255 | observe | 0 | None | 5819 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.135 | observe | 1 | 0.0 | 0 | 178 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| 10ium-HighSpeed | 0.161 | observe | 1 | 0.0 | 0 | 839 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.233 | 7 | 23 | 30 |
| Surfboard-tg-mixed | 0.28 | 21 | 54 | 75 |
| mheidari-all | 0.325 | 13 | 27 | 40 |
| Au1rxx-base64 | 0.767 | 458 | 139 | 597 |
| zhangkai | 0.91 | 61 | 6 | 67 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20242 | yes | 4.38 | 0 |
| SoliSpirit-all | 6811 | yes | 4.67 | 0 |
| Epodonios-all | 5819 | yes | 4.6 | 0 |
| DeltaKronecker-all | 5788 | yes | 5.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 5251 | yes | 2.84 | 0 |
| Surfboard-tg-mixed | 5211 | yes | 2.58 | 0 |
| xiaoji235-airport-v2ray-all | 5127 | yes | 1.48 | 0 |
| mahdibland-V2RayAggregator | 5110 | yes | 0.24 | 0 |
| barry-far-vless | 4536 | yes | 2.55 | 0 |
| Surfboard-tg-vless | 4191 | yes | 3.4 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 165 |
| speed | 37 |
| 204 | 34 |
| cn-block | 19 |
