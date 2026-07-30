# AutoNodes 每日报告

生成时间：2026-07-30 02:51:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 77441 |
| 去重后节点数 | 22598 |
| TCP 可达数 | 3000 |
| 真测通过数 | 751 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22598 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 41.4 |
| geo | 1.4 |
| probe | 72.5 |
| real_test | 221.9 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 70 | 70 | 0 | 100.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 234 | 212 | 22 | 90.6% |
| socks | 15 | 10 | 5 | 66.7% |
| trojan | 65 | 45 | 20 | 69.2% |
| vless | 1121 | 398 | 723 | 35.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 249 |
| speed:ClientOSError | 114 |
| cn-block:TimeoutError | 104 |
| 204:ProxyError | 88 |
| geo:ClientOSError | 48 |
| geo:ProxyError | 44 |
| cn-block:ProxyError | 41 |
| speed:TimeoutError | 39 |
| speed:ProxyError | 20 |
| 204:TimeoutError | 12 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 6 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4731 |
| ConnectionRefusedError | 725 |
| OSError | 222 |
| gaierror | 94 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 70 | 1.0 | 84 |
| Au1rxx-base64 | 0.948 | prefer | 291 | 0.9 | 1255 |
| Surfboard-tg-mixed | 0.709 | prefer | 33 | 0.636 | 5390 |
| DeltaKronecker-all | 0.435 | observe | 1112 | 0.355 | 5519 |
| mheidari-all | 0.291 | observe | 12 | 0.25 | 16333 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5118 |
| Epodonios-all | 0.255 | observe | 0 | None | 6124 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6420 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4279 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.25 | 3 | 9 | 12 |
| DeltaKronecker-all | 0.355 | 395 | 717 | 1112 |
| Surfboard-tg-mixed | 0.636 | 21 | 12 | 33 |
| Au1rxx-base64 | 0.9 | 262 | 29 | 291 |
| zhangkai | 1.0 | 70 | 0 | 70 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16333 | yes | 2.72 | 0 |
| SoliSpirit-all | 6420 | yes | 1.23 | 0 |
| Epodonios-all | 6124 | yes | 1.36 | 0 |
| DeltaKronecker-all | 5519 | yes | 1.8 | 0 |
| Surfboard-tg-mixed | 5390 | yes | 1.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 5118 | yes | 0.65 | 0 |
| mahdibland-V2RayAggregator | 5076 | yes | 1.25 | 0 |
| barry-far-vless | 4688 | yes | 0.41 | 0 |
| Surfboard-tg-vless | 4279 | yes | 1.68 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 341 |
| speed | 173 |
| cn-block | 151 |
| 204 | 106 |
