# AutoNodes 每日报告

生成时间：2026-07-31 14:24:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 79052 |
| 去重后节点数 | 22809 |
| TCP 可达数 | 3000 |
| 真测通过数 | 480 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22809 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.6 |
| generate | 43.0 |
| geo | 1.7 |
| probe | 54.5 |
| real_test | 126.8 |
| tcp | 33.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 80 | 80 | 0 | 100.0% |
| hysteria2 | 16 | 13 | 3 | 81.2% |
| shadowsocks | 139 | 123 | 16 | 88.5% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 24 | 18 | 6 | 75.0% |
| vless | 356 | 244 | 112 | 68.5% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 41 |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 24 |
| speed:TimeoutError | 18 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4558 |
| ConnectionRefusedError | 763 |
| gaierror | 230 |
| OSError | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 80 | 1.0 | 110 |
| Au1rxx-base64 | 0.889 | prefer | 392 | 0.829 | 1533 |
| DeltaKronecker-all | 0.589 | observe | 51 | 0.51 | 5144 |
| Surfboard-tg-mixed | 0.575 | observe | 89 | 0.494 | 5429 |
| mheidari-all | 0.421 | observe | 6 | 0.667 | 16815 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 48 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5507 |
| Epodonios-all | 0.255 | observe | 0 | None | 5989 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3966 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7049 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.494 | 44 | 45 | 89 |
| DeltaKronecker-all | 0.51 | 26 | 25 | 51 |
| mheidari-all | 0.667 | 4 | 2 | 6 |
| Au1rxx-base64 | 0.829 | 325 | 67 | 392 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 80 | 0 | 80 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16815 | yes | 4.47 | 0 |
| SoliSpirit-all | 7049 | yes | 2.07 | 0 |
| Epodonios-all | 5989 | yes | 2.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5507 | yes | 1.11 | 0 |
| Surfboard-tg-mixed | 5429 | yes | 3.82 | 0 |
| DeltaKronecker-all | 5144 | yes | 4.59 | 0 |
| mahdibland-V2RayAggregator | 5074 | yes | 2.06 | 0 |
| barry-far-vless | 4528 | yes | 0.87 | 0 |
| Surfboard-tg-vless | 4260 | yes | 2.69 | 0 |
| MatinGhanbari-all-sub | 3966 | yes | 1.18 | 0 |

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
| geo | 55 |
| 204 | 32 |
| cn-block | 30 |
| speed | 22 |
