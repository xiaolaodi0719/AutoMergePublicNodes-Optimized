# AutoNodes 每日报告

生成时间：2026-08-05 08:47:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 85532 |
| 去重后节点数 | 23905 |
| TCP 可达数 | 3000 |
| 真测通过数 | 511 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23905 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| generate | 29.2 |
| geo | 1.4 |
| probe | 52.7 |
| real_test | 111.3 |
| tcp | 35.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 50 | 0 | 100.0% |
| hysteria2 | 19 | 16 | 3 | 84.2% |
| shadowsocks | 151 | 131 | 20 | 86.8% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 166 | 158 | 8 | 95.2% |
| vless | 249 | 152 | 97 | 61.0% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 41 |
| 204:TimeoutError | 17 |
| speed:TimeoutError | 15 |
| 204:ProxyError | 14 |
| geo:ClientOSError | 12 |
| 204:ClientOSError | 9 |
| speed:ClientOSError | 8 |
| cn-block:TimeoutError | 8 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4779 |
| ConnectionRefusedError | 832 |
| gaierror | 288 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.984 | prefer | 50 | 1.0 | 72 |
| Au1rxx-base64 | 0.969 | prefer | 401 | 0.915 | 1403 |
| Surfboard-tg-mixed | 0.68 | observe | 128 | 0.602 | 5560 |
| DeltaKronecker-all | 0.413 | observe | 22 | 0.318 | 5316 |
| mheidari-all | 0.369 | observe | 36 | 0.278 | 20226 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5260 |
| Epodonios-all | 0.255 | observe | 0 | None | 6163 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6818 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4397 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.278 | 10 | 26 | 36 |
| DeltaKronecker-all | 0.318 | 7 | 15 | 22 |
| Surfboard-tg-mixed | 0.602 | 77 | 51 | 128 |
| Au1rxx-base64 | 0.915 | 367 | 34 | 401 |
| zhangkai | 1.0 | 50 | 0 | 50 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20226 | yes | 5.26 | 0 |
| SoliSpirit-all | 6818 | yes | 2.9 | 0 |
| Epodonios-all | 6163 | yes | 2.61 | 0 |
| Surfboard-tg-mixed | 5560 | yes | 3.48 | 0 |
| DeltaKronecker-all | 5316 | yes | 5.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 5260 | yes | 1.5 | 0 |
| mahdibland-V2RayAggregator | 5147 | yes | 2.79 | 0 |
| barry-far-vless | 4823 | yes | 1.45 | 0 |
| xiaoji235-airport-v2ray-all | 4655 | yes | 2.05 | 0 |
| Surfboard-tg-vless | 4397 | yes | 3.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 54 |
| 204 | 40 |
| speed | 24 |
| cn-block | 14 |
