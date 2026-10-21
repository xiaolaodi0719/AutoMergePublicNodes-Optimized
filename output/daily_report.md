# AutoNodes 每日报告

生成时间：2026-10-21 17:06:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 96570 |
| 去重后节点数 | 26902 |
| TCP 可达数 | 3000 |
| 真测通过数 | 228 |
| verified 输出数 | 228 |
| global 输出数 | 242 |
| all 输出数 | 26902 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 78.7 |
| geo | 1.5 |
| probe | 229.8 |
| real_test | 219.0 |
| tcp | 44.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 40 | 12 | 28 | 30.0% |
| hysteria2 | 7 | 7 | 0 | 100.0% |
| shadowsocks | 123 | 103 | 20 | 83.7% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 42 | 25 | 17 | 59.5% |
| vless | 130 | 80 | 50 | 61.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 29 |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 19 |
| geo:ClientOSError | 9 |
| speed:ClientOSError | 9 |
| geo:TimeoutError | 8 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 4 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6359 |
| ConnectionRefusedError | 1052 |
| gaierror | 330 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.834 | prefer | 190 | 0.774 | 1568 |
| Surfboard-tg-mixed | 0.803 | prefer | 45 | 0.733 | 7070 |
| mheidari-all | 0.673 | observe | 57 | 0.596 | 24102 |
| zhangkai | 0.45 | observe | 27 | 0.444 | 31 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| Epodonios-all | 0.255 | observe | 0 | None | 7559 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10165 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5554 |
| barry-far-vless | 0.255 | observe | 0 | None | 5768 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.068 | 12 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.234 | 13 | 0.154 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 12 | 12 |
| DeltaKronecker-all | 0.154 | 2 | 11 | 13 |
| zhangkai | 0.444 | 12 | 15 | 27 |
| mheidari-all | 0.596 | 34 | 23 | 57 |
| Surfboard-tg-mixed | 0.733 | 33 | 12 | 45 |
| Au1rxx-base64 | 0.774 | 147 | 43 | 190 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24102 | yes | 6.24 | 0 |
| SoliSpirit-all | 10165 | yes | 4.1 | 0 |
| Epodonios-all | 7559 | yes | 5.52 | 0 |
| Surfboard-tg-mixed | 7070 | yes | 4.03 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.47 | 0 |
| barry-far-vless | 5768 | yes | 1.14 | 0 |
| Surfboard-tg-vless | 5554 | yes | 4.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 2.71 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 1.07 | 0 |
| DeltaKronecker-all | 4067 | yes | 5.91 | 0 |

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
| 204 | 62 |
| cn-block | 25 |
| geo | 17 |
| speed | 14 |
