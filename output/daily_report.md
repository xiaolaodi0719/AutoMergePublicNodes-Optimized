# AutoNodes 每日报告

生成时间：2026-07-26 08:39:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 80985 |
| 去重后节点数 | 22458 |
| TCP 可达数 | 3000 |
| 真测通过数 | 890 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22458 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 24.9 |
| geo | 1.3 |
| probe | 66.5 |
| real_test | 196.6 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 9 | 6 | 3 | 66.7% |
| shadowsocks | 143 | 116 | 27 | 81.1% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 611 | 533 | 78 | 87.2% |
| vless | 374 | 157 | 217 | 42.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 114 |
| 204:ProxyError | 50 |
| geo:ClientOSError | 37 |
| speed:ClientOSError | 37 |
| cn-block:TimeoutError | 27 |
| 204:TimeoutError | 22 |
| speed:TimeoutError | 13 |
| cn-block:ClientOSError | 8 |
| speed:ProxyError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4112 |
| ConnectionRefusedError | 689 |
| gaierror | 308 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 76 | 1.0 | 86 |
| Au1rxx-base64 | 0.931 | prefer | 457 | 0.875 | 1442 |
| mheidari-all | 0.927 | prefer | 188 | 0.851 | 17285 |
| Surfboard-tg-mixed | 0.697 | observe | 147 | 0.619 | 5458 |
| DeltaKronecker-all | 0.556 | observe | 338 | 0.476 | 5950 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Pawdroid | 0.255 | observe | 1 | 1.0 | 10 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6596 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 200 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.14 | downweight | 6 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.14 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Epodonios-all | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 6 | 6 |
| DeltaKronecker-all | 0.476 | 161 | 177 | 338 |
| Surfboard-tg-mixed | 0.619 | 91 | 56 | 147 |
| mheidari-all | 0.851 | 160 | 28 | 188 |
| Au1rxx-base64 | 0.875 | 400 | 57 | 457 |
| Pawdroid | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17285 | yes | 3.72 | 0 |
| SoliSpirit-all | 6596 | yes | 2.85 | 0 |
| Epodonios-all | 6589 | yes | 1.5 | 0 |
| DeltaKronecker-all | 5950 | yes | 3.81 | 0 |
| Surfboard-tg-mixed | 5458 | yes | 2.55 | 0 |
| mahdibland-V2RayAggregator | 4980 | yes | 1.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 1.95 | 0 |
| barry-far-vless | 4874 | yes | 2.1 | 0 |
| Surfboard-tg-vless | 4178 | yes | 2.68 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 2.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 155 |
| 204 | 77 |
| speed | 56 |
| cn-block | 39 |
