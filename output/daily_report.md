# AutoNodes 每日报告

生成时间：2026-07-25 19:20:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 80536 |
| 去重后节点数 | 22511 |
| TCP 可达数 | 3000 |
| 真测通过数 | 356 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22511 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 39.4 |
| geo | 1.4 |
| probe | 64.1 |
| real_test | 112.5 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 74 | 74 | 0 | 100.0% |
| hysteria2 | 7 | 7 | 0 | 100.0% |
| shadowsocks | 3 | 2 | 1 | 66.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 188 | 168 | 20 | 89.4% |
| vless | 295 | 104 | 191 | 35.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 81 |
| speed:ClientOSError | 56 |
| 204:ProxyError | 22 |
| 204:TimeoutError | 20 |
| geo:ClientOSError | 13 |
| speed:TimeoutError | 8 |
| cn-block:TimeoutError | 7 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |
| cn-block:ClientOSError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4336 |
| ConnectionRefusedError | 694 |
| gaierror | 245 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 74 | 1.0 | 119 |
| mheidari-all | 0.742 | prefer | 223 | 0.664 | 17275 |
| Surfboard-tg-mixed | 0.575 | observe | 184 | 0.495 | 5515 |
| DeltaKronecker-all | 0.538 | observe | 81 | 0.457 | 5838 |
| Au1rxx-base64 | 0.487 | observe | 5 | 1.0 | 1199 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4879 |
| Epodonios-all | 0.255 | observe | 0 | None | 6622 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6305 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 183 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.457 | 37 | 44 | 81 |
| Surfboard-tg-mixed | 0.495 | 91 | 93 | 184 |
| mheidari-all | 0.664 | 148 | 75 | 223 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 74 | 0 | 74 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17275 | yes | 4.58 | 0 |
| Epodonios-all | 6622 | yes | 3.41 | 0 |
| SoliSpirit-all | 6305 | yes | 3.06 | 0 |
| DeltaKronecker-all | 5838 | yes | 4.42 | 0 |
| Surfboard-tg-mixed | 5515 | yes | 3.6 | 0 |
| mahdibland-V2RayAggregator | 4980 | yes | 2.92 | 0 |
| barry-far-vless | 4959 | yes | 1.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4879 | yes | 1.74 | 0 |
| Surfboard-tg-vless | 4371 | yes | 3.1 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 2.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 96 |
| speed | 64 |
| 204 | 43 |
| cn-block | 11 |
