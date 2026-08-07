# AutoNodes 每日报告

生成时间：2026-08-07 19:07:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82709 |
| 去重后节点数 | 23525 |
| TCP 可达数 | 3000 |
| 真测通过数 | 408 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23525 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 32.0 |
| geo | 1.4 |
| probe | 52.7 |
| real_test | 92.6 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 158 | 131 | 27 | 82.9% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 142 | 140 | 2 | 98.6% |
| vless | 138 | 93 | 45 | 67.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 13 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 9 |
| geo:ClientOSError | 8 |
| geo:TimeoutError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4781 |
| ConnectionRefusedError | 834 |
| gaierror | 340 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.963 | prefer | 362 | 0.903 | 1543 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| mheidari-all | 0.738 | prefer | 71 | 0.662 | 17684 |
| Surfboard-tg-mixed | 0.441 | observe | 13 | 0.462 | 6368 |
| DeltaKronecker-all | 0.432 | observe | 14 | 0.429 | 5326 |
| Epodonios-all | 0.287 | observe | 2 | 0.5 | 7096 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5282 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7593 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 9 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.429 | 6 | 8 | 14 |
| Surfboard-tg-mixed | 0.462 | 6 | 7 | 13 |
| Epodonios-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.662 | 47 | 24 | 71 |
| Au1rxx-base64 | 0.903 | 327 | 35 | 362 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17684 | yes | 3.66 | 0 |
| SoliSpirit-all | 7593 | yes | 2.21 | 0 |
| Epodonios-all | 7096 | yes | 4.33 | 0 |
| Surfboard-tg-mixed | 6368 | yes | 2.72 | 0 |
| barry-far-vless | 5504 | yes | 1.32 | 0 |
| DeltaKronecker-all | 5326 | yes | 3.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 5282 | yes | 1.51 | 0 |
| mahdibland-V2RayAggregator | 5175 | yes | 1.78 | 0 |
| Surfboard-tg-vless | 5103 | yes | 2.55 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 28 |
| cn-block | 20 |
| geo | 15 |
| speed | 14 |
