# AutoNodes 每日报告

生成时间：2026-08-03 03:33:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 81081 |
| 去重后节点数 | 22635 |
| TCP 可达数 | 3000 |
| 真测通过数 | 852 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22635 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 32.7 |
| geo | 1.4 |
| probe | 59.7 |
| real_test | 190.4 |
| tcp | 35.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 143 | 143 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 171 | 159 | 12 | 93.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 40 | 34 | 6 | 85.0% |
| vless | 785 | 495 | 290 | 63.1% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 96 |
| geo:TimeoutError | 92 |
| speed:TimeoutError | 54 |
| speed:ClientOSError | 29 |
| geo:ClientOSError | 15 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4886 |
| ConnectionRefusedError | 756 |
| OSError | 226 |
| gaierror | 214 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 144 | 1.0 | 344 |
| Au1rxx-base64 | 0.894 | prefer | 598 | 0.829 | 1632 |
| Surfboard-tg-mixed | 0.619 | observe | 87 | 0.54 | 5182 |
| DeltaKronecker-all | 0.61 | observe | 283 | 0.53 | 3437 |
| mheidari-all | 0.373 | observe | 39 | 0.282 | 18808 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3833 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 56 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5486 |
| Epodonios-all | 0.255 | observe | 0 | None | 5849 |

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
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| nscl5-all | 0.25 | 1 | 3 | 4 |
| mheidari-all | 0.282 | 11 | 28 | 39 |
| DeltaKronecker-all | 0.53 | 150 | 133 | 283 |
| Surfboard-tg-mixed | 0.54 | 47 | 40 | 87 |
| Au1rxx-base64 | 0.829 | 496 | 102 | 598 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18808 | yes | 3.68 | 0 |
| SoliSpirit-all | 6871 | yes | 2.94 | 0 |
| Epodonios-all | 5849 | yes | 3.81 | 0 |
| 10ium-ScrapeCategorize-Vless | 5486 | yes | 1.46 | 0 |
| mahdibland-V2RayAggregator | 5208 | yes | 2.03 | 0 |
| Surfboard-tg-mixed | 5182 | yes | 3.27 | 0 |
| barry-far-vless | 4560 | yes | 1.18 | 0 |
| Surfboard-tg-vless | 4109 | yes | 2.33 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.04 | 0 |
| xiaoji235-airport-v2ray-all | 3833 | yes | 0.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 107 |
| cn-block | 105 |
| speed | 83 |
| 204 | 16 |
