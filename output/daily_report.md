# AutoNodes 每日报告

生成时间：2026-08-14 19:05:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78247 |
| 去重后节点数 | 22448 |
| TCP 可达数 | 3000 |
| 真测通过数 | 852 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22448 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 33.8 |
| geo | 1.4 |
| probe | 64.2 |
| real_test | 162.3 |
| tcp | 35.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 147 | 131 | 16 | 89.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 392 | 371 | 21 | 94.6% |
| vless | 263 | 204 | 59 | 77.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 32 |
| cn-block:TimeoutError | 19 |
| geo:TimeoutError | 13 |
| speed:TimeoutError | 9 |
| geo:ClientOSError | 7 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 5 |
| speed:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4709 |
| ConnectionRefusedError | 801 |
| gaierror | 298 |
| OSError | 24 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Au1rxx-base64 | 0.993 | prefer | 676 | 0.926 | 1715 |
| mheidari-all | 0.827 | prefer | 81 | 0.753 | 15859 |
| Surfboard-tg-mixed | 0.695 | observe | 24 | 0.625 | 5725 |
| DeltaKronecker-all | 0.628 | observe | 40 | 0.55 | 5969 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 160 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5157 |
| Epodonios-all | 0.255 | observe | 0 | None | 6388 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7685 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.55 | 22 | 18 | 40 |
| Surfboard-tg-mixed | 0.625 | 15 | 9 | 24 |
| mheidari-all | 0.753 | 61 | 20 | 81 |
| Au1rxx-base64 | 0.926 | 626 | 50 | 676 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15859 | yes | 4.21 | 0 |
| SoliSpirit-all | 7685 | yes | 1.46 | 0 |
| Epodonios-all | 6388 | yes | 5.21 | 0 |
| DeltaKronecker-all | 5969 | yes | 4.12 | 0 |
| Surfboard-tg-mixed | 5725 | yes | 3.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 5157 | yes | 1.03 | 0 |
| barry-far-vless | 4814 | yes | 0.83 | 0 |
| Surfboard-tg-vless | 4488 | yes | 2.87 | 0 |
| MatinGhanbari-all-sub | 3995 | yes | 1.1 | 0 |
| mahdibland-V2RayAggregator | 3992 | yes | 2.6 | 0 |

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
| 204 | 42 |
| cn-block | 23 |
| geo | 20 |
| speed | 14 |
