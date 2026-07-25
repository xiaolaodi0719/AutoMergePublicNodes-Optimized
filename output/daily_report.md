# AutoNodes 每日报告

生成时间：2026-07-25 13:51:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78947 |
| 去重后节点数 | 22518 |
| TCP 可达数 | 3000 |
| 真测通过数 | 667 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22518 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 39.1 |
| geo | 1.3 |
| probe | 64.9 |
| real_test | 188.0 |
| tcp | 31.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 9 | 7 | 2 | 77.8% |
| shadowsocks | 4 | 4 | 0 | 100.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 398 | 373 | 25 | 93.7% |
| vless | 689 | 205 | 484 | 29.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 188 |
| geo:TimeoutError | 147 |
| 204:ProxyError | 56 |
| geo:ClientOSError | 39 |
| speed:TimeoutError | 31 |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 18 |
| cn-block:ProxyError | 10 |
| geo:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4102 |
| ConnectionRefusedError | 695 |
| gaierror | 320 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 258 | 0.946 | 17158 |
| zhangkai | 0.992 | prefer | 76 | 1.0 | 119 |
| Surfboard-tg-mixed | 0.73 | prefer | 58 | 0.655 | 5379 |
| DeltaKronecker-all | 0.469 | observe | 777 | 0.389 | 5838 |
| Au1rxx-base64 | 0.417 | observe | 7 | 0.714 | 803 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 180 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4879 |
| Epodonios-all | 0.255 | observe | 0 | None | 6540 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3969 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.389 | 302 | 475 | 777 |
| Surfboard-tg-mixed | 0.655 | 38 | 20 | 58 |
| Au1rxx-base64 | 0.714 | 5 | 2 | 7 |
| mheidari-all | 0.946 | 244 | 14 | 258 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 76 | 0 | 76 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17158 | yes | 3.19 | 0 |
| Epodonios-all | 6540 | yes | 3.36 | 0 |
| SoliSpirit-all | 6338 | yes | 2.04 | 0 |
| DeltaKronecker-all | 5838 | yes | 3.81 | 0 |
| Surfboard-tg-mixed | 5379 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 5009 | yes | 1.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 4879 | yes | 1.12 | 0 |
| barry-far-vless | 4746 | yes | 0.94 | 0 |
| Surfboard-tg-vless | 4058 | yes | 2.31 | 0 |
| MatinGhanbari-all-sub | 3969 | yes | 0.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 220 |
| geo | 188 |
| 204 | 76 |
| cn-block | 29 |
