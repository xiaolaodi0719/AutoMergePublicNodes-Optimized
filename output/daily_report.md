# AutoNodes 每日报告

生成时间：2026-08-15 06:53:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78120 |
| 去重后节点数 | 22201 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1192 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22201 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 34.5 |
| geo | 1.3 |
| probe | 81.2 |
| real_test | 300.7 |
| tcp | 34.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 95 | 90 | 5 | 94.7% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 552 | 534 | 18 | 96.7% |
| vless | 843 | 420 | 423 | 49.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 205 |
| geo:ClientOSError | 77 |
| speed:TimeoutError | 54 |
| speed:ClientOSError | 43 |
| cn-block:TimeoutError | 21 |
| 204:TimeoutError | 21 |
| 204:ProxyError | 14 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4692 |
| ConnectionRefusedError | 755 |
| gaierror | 252 |
| OSError | 15 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 811 | 0.949 | 1975 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.593 | observe | 7 | 1.0 | 5665 |
| DeltaKronecker-all | 0.491 | observe | 669 | 0.411 | 5773 |
| mheidari-all | 0.482 | observe | 14 | 0.5 | 15492 |
| nscl5-all | 0.4 | observe | 4 | 0.75 | 2081 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 162 |
| Epodonios-all | 0.255 | observe | 0 | None | 6322 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.411 | 275 | 394 | 669 |
| mheidari-all | 0.5 | 7 | 7 | 14 |
| nscl5-all | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.949 | 770 | 41 | 811 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15492 | yes | 4.18 | 0 |
| SoliSpirit-all | 7671 | yes | 2.34 | 0 |
| Epodonios-all | 6322 | yes | 2.88 | 0 |
| DeltaKronecker-all | 5773 | yes | 3.47 | 0 |
| Surfboard-tg-mixed | 5665 | yes | 3.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 5113 | yes | 1.86 | 0 |
| barry-far-vless | 4715 | yes | 1.71 | 0 |
| Surfboard-tg-vless | 4367 | yes | 3.31 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.92 | 0 |
| mahdibland-V2RayAggregator | 3935 | yes | 1.81 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 285 |
| speed | 97 |
| 204 | 39 |
| cn-block | 27 |
