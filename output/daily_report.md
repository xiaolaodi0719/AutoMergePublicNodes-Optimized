# AutoNodes 每日报告

生成时间：2026-07-31 03:33:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 78323 |
| 去重后节点数 | 23087 |
| TCP 可达数 | 3000 |
| 真测通过数 | 672 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23087 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.4 |
| generate | 27.3 |
| geo | 1.3 |
| probe | 74.3 |
| real_test | 225.7 |
| tcp | 33.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 160 | 146 | 14 | 91.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 46 | 44 | 2 | 95.7% |
| vless | 989 | 352 | 637 | 35.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 297 |
| speed:ClientOSError | 105 |
| cn-block:TimeoutError | 70 |
| geo:ClientOSError | 68 |
| speed:TimeoutError | 44 |
| 204:ProxyError | 31 |
| cn-block:ProxyError | 13 |
| 204:TimeoutError | 11 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 5 |
| speed:ProxyError | 4 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4698 |
| ConnectionRefusedError | 745 |
| OSError | 226 |
| gaierror | 214 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | prefer | 113 | 1.0 | 129 |
| Au1rxx-base64 | 0.946 | prefer | 237 | 0.899 | 1272 |
| Surfboard-tg-mixed | 0.734 | prefer | 18 | 0.722 | 5223 |
| DeltaKronecker-all | 0.431 | observe | 937 | 0.351 | 5759 |
| mheidari-all | 0.291 | observe | 12 | 0.25 | 16264 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 43 |
| Epodonios-all | 0.255 | observe | 0 | None | 6141 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7041 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4144 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.136 | downweight | 7 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.136 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 7 | 7 |
| mheidari-all | 0.25 | 3 | 9 | 12 |
| DeltaKronecker-all | 0.351 | 329 | 608 | 937 |
| Surfboard-tg-mixed | 0.722 | 13 | 5 | 18 |
| Au1rxx-base64 | 0.899 | 213 | 24 | 237 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16264 | yes | 2.52 | 0 |
| SoliSpirit-all | 7041 | yes | 1.84 | 0 |
| Epodonios-all | 6141 | yes | 1.33 | 0 |
| DeltaKronecker-all | 5759 | yes | 2.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 5342 | yes | 2.33 | 0 |
| Surfboard-tg-mixed | 5223 | yes | 2.62 | 0 |
| mahdibland-V2RayAggregator | 5047 | yes | 1.38 | 0 |
| barry-far-vless | 4647 | yes | 1.19 | 0 |
| Surfboard-tg-vless | 4144 | yes | 2.06 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 370 |
| speed | 153 |
| cn-block | 88 |
| 204 | 44 |
