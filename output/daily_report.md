# AutoNodes 每日报告

生成时间：2026-08-02 19:23:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 81351 |
| 去重后节点数 | 22692 |
| TCP 可达数 | 3000 |
| 真测通过数 | 629 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22692 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 43.0 |
| geo | 1.4 |
| probe | 63.9 |
| real_test | 157.7 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 143 | 143 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 124 | 97 | 27 | 78.2% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 27 | 26 | 1 | 96.3% |
| vless | 617 | 340 | 277 | 55.1% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 108 |
| 204:TimeoutError | 57 |
| 204:ProxyError | 37 |
| speed:TimeoutError | 35 |
| geo:ClientOSError | 19 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 13 |
| cn-block:ProxyError | 9 |
| geo:ProxyError | 9 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4663 |
| ConnectionRefusedError | 778 |
| gaierror | 311 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 143 | 1.0 | 344 |
| Au1rxx-base64 | 0.784 | prefer | 529 | 0.718 | 1651 |
| DeltaKronecker-all | 0.511 | observe | 135 | 0.43 | 3437 |
| Surfboard-tg-mixed | 0.433 | observe | 117 | 0.35 | 5222 |
| mheidari-all | 0.418 | observe | 10 | 0.5 | 18817 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3833 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 56 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5486 |
| Epodonios-all | 0.255 | observe | 0 | None | 5783 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3975 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.35 | 41 | 76 | 117 |
| DeltaKronecker-all | 0.43 | 58 | 77 | 135 |
| mheidari-all | 0.5 | 5 | 5 | 10 |
| Au1rxx-base64 | 0.718 | 380 | 149 | 529 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 143 | 0 | 143 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18817 | yes | 5.41 | 0 |
| SoliSpirit-all | 7117 | yes | 3.46 | 0 |
| Epodonios-all | 5783 | yes | 1.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 5486 | yes | 2.49 | 0 |
| Surfboard-tg-mixed | 5222 | yes | 5.57 | 0 |
| mahdibland-V2RayAggregator | 5208 | yes | 3.43 | 0 |
| barry-far-vless | 4490 | yes | 3.62 | 0 |
| Surfboard-tg-vless | 4122 | yes | 5.73 | 0 |
| MatinGhanbari-all-sub | 3975 | yes | 2.57 | 0 |
| xiaoji235-airport-v2ray-all | 3833 | yes | 3.19 | 0 |

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
| geo | 136 |
| 204 | 97 |
| speed | 48 |
| cn-block | 28 |
