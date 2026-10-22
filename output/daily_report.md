# AutoNodes 每日报告

生成时间：2026-10-22 11:38:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 4/101 |
| 原始节点数 | 95605 |
| 去重后节点数 | 26650 |
| TCP 可达数 | 3000 |
| 真测通过数 | 292 |
| verified 输出数 | 292 |
| global 输出数 | 300 |
| all 输出数 | 26650 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 82.6 |
| geo | 1.6 |
| probe | 171.5 |
| real_test | 219.3 |
| tcp | 44.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 37 | 18 | 19 | 48.6% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 117 | 100 | 17 | 85.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 58 | 48 | 10 | 82.8% |
| vless | 182 | 114 | 68 | 62.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 23 |
| 204:ProxyError | 21 |
| 204:TimeoutError | 21 |
| speed:TimeoutError | 11 |
| speed:ClientOSError | 11 |
| geo:ClientOSError | 7 |
| geo:TimeoutError | 7 |
| 204:ProxyConnectionError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6555 |
| ConnectionRefusedError | 1023 |
| gaierror | 246 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.854 | prefer | 29 | 0.793 | 23951 |
| Au1rxx-base64 | 0.828 | prefer | 251 | 0.769 | 1526 |
| zhangkai | 0.82 | prefer | 20 | 0.85 | 45 |
| Surfboard-tg-mixed | 0.759 | prefer | 82 | 0.683 | 7043 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 7460 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10067 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5382 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.114 | 18 | 0.056 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.216 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.056 | 1 | 17 | 18 |
| DeltaKronecker-all | 0.167 | 1 | 5 | 6 |
| Surfboard-tg-mixed | 0.683 | 56 | 26 | 82 |
| Au1rxx-base64 | 0.769 | 193 | 58 | 251 |
| mheidari-all | 0.793 | 23 | 6 | 29 |
| zhangkai | 0.85 | 17 | 3 | 20 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23951 | yes | 6.12 | 0 |
| SoliSpirit-all | 10067 | yes | 3.09 | 0 |
| Epodonios-all | 7460 | yes | 4.56 | 0 |
| Surfboard-tg-mixed | 7043 | yes | 1.55 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.94 | 0 |
| barry-far-vless | 5666 | yes | 0.94 | 0 |
| Surfboard-tg-vless | 5382 | yes | 3.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 0.73 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 3.47 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.03 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 51 |
| cn-block | 28 |
| speed | 22 |
| geo | 15 |
