# AutoNodes 每日报告

生成时间：2026-08-02 03:32:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 78379 |
| 去重后节点数 | 23363 |
| TCP 可达数 | 3000 |
| 真测通过数 | 760 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23363 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| generate | 33.1 |
| geo | 1.5 |
| probe | 59.5 |
| real_test | 185.5 |
| tcp | 34.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 146 | 146 | 0 | 100.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 164 | 150 | 14 | 91.5% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 54 | 35 | 19 | 64.8% |
| vless | 812 | 405 | 407 | 49.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 240 |
| speed:TimeoutError | 57 |
| speed:ClientOSError | 55 |
| geo:ClientOSError | 49 |
| cn-block:TimeoutError | 21 |
| 204:TimeoutError | 9 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4728 |
| ConnectionRefusedError | 792 |
| gaierror | 282 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 147 | 1.0 | 194 |
| Au1rxx-base64 | 0.95 | prefer | 536 | 0.888 | 1590 |
| Surfboard-tg-mixed | 0.659 | observe | 119 | 0.58 | 5146 |
| mheidari-all | 0.272 | observe | 7 | 0.286 | 16695 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5391 |
| Epodonios-all | 0.255 | observe | 0 | None | 5783 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6873 |

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
| ninja-vless | 0.136 | downweight | 7 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.136 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.248 | 384 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 7 | 7 |
| DeltaKronecker-all | 0.167 | 64 | 320 | 384 |
| mheidari-all | 0.286 | 2 | 5 | 7 |
| Surfboard-tg-mixed | 0.58 | 69 | 50 | 119 |
| Au1rxx-base64 | 0.888 | 476 | 60 | 536 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 147 | 0 | 147 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16695 | yes | 2.82 | 0 |
| SoliSpirit-all | 6873 | yes | 1.66 | 0 |
| Epodonios-all | 5783 | yes | 2.58 | 0 |
| DeltaKronecker-all | 5497 | yes | 3.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 5391 | yes | 0.7 | 0 |
| Surfboard-tg-mixed | 5146 | yes | 1.86 | 0 |
| mahdibland-V2RayAggregator | 5071 | yes | 1.76 | 0 |
| barry-far-vless | 4431 | yes | 0.32 | 0 |
| Surfboard-tg-vless | 4069 | yes | 1.94 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 0.76 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 290 |
| speed | 112 |
| cn-block | 25 |
| 204 | 17 |
