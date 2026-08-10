# AutoNodes 每日报告

生成时间：2026-08-10 02:13:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 86295 |
| 去重后节点数 | 23966 |
| TCP 可达数 | 3000 |
| 真测通过数 | 579 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23966 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 24.1 |
| geo | 1.4 |
| probe | 56.6 |
| real_test | 144.6 |
| tcp | 34.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 22 | 19 | 3 | 86.4% |
| shadowsocks | 162 | 151 | 11 | 93.2% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 147 | 133 | 14 | 90.5% |
| vless | 609 | 247 | 362 | 40.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 154 |
| geo:ClientOSError | 82 |
| speed:TimeoutError | 76 |
| speed:ClientOSError | 30 |
| cn-block:TimeoutError | 27 |
| 204:TimeoutError | 8 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4073 |
| ConnectionRefusedError | 857 |
| gaierror | 433 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Au1rxx-base64 | 0.947 | prefer | 457 | 0.88 | 1716 |
| Surfboard-tg-mixed | 0.738 | prefer | 156 | 0.66 | 6683 |
| tg-oneclickvpnkeys | 0.402 | observe | 4 | 1.0 | 44 |
| nscl5-all | 0.313 | observe | 1 | 1.0 | 1442 |
| Epodonios-all | 0.255 | observe | 0 | None | 7220 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7672 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5494 |
| barry-far-vless | 0.255 | observe | 0 | None | 5808 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.199 | 40 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mheidari-all | 0.238 | 289 | 0.156 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.1 | 4 | 36 | 40 |
| mheidari-all | 0.156 | 45 | 244 | 289 |
| Surfboard-tg-mixed | 0.66 | 103 | 53 | 156 |
| Au1rxx-base64 | 0.88 | 402 | 55 | 457 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20202 | yes | 4.78 | 0 |
| SoliSpirit-all | 7672 | yes | 3.31 | 0 |
| Epodonios-all | 7220 | yes | 3.22 | 0 |
| Surfboard-tg-mixed | 6683 | yes | 3.85 | 0 |
| barry-far-vless | 5808 | yes | 2.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 5505 | yes | 1.86 | 0 |
| Surfboard-tg-vless | 5494 | yes | 1.49 | 0 |
| mahdibland-V2RayAggregator | 5189 | yes | 1.87 | 0 |
| DeltaKronecker-all | 4998 | yes | 5.19 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 237 |
| speed | 106 |
| cn-block | 32 |
| 204 | 17 |
