# AutoNodes 每日报告

生成时间：2026-07-29 14:25:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78926 |
| 去重后节点数 | 22704 |
| TCP 可达数 | 3000 |
| 真测通过数 | 516 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22704 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 25.7 |
| geo | 1.4 |
| probe | 54.9 |
| real_test | 140.3 |
| tcp | 32.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 70 | 70 | 0 | 100.0% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 182 | 153 | 29 | 84.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 40 | 32 | 8 | 80.0% |
| vless | 407 | 246 | 161 | 60.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 80 |
| speed:TimeoutError | 29 |
| cn-block:TimeoutError | 26 |
| geo:ClientOSError | 19 |
| 204:TimeoutError | 17 |
| 204:ProxyError | 10 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4397 |
| ConnectionRefusedError | 738 |
| gaierror | 309 |
| OSError | 224 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 70 | 1.0 | 84 |
| Au1rxx-base64 | 0.863 | prefer | 276 | 0.812 | 1352 |
| Surfboard-tg-mixed | 0.726 | prefer | 142 | 0.648 | 5803 |
| DeltaKronecker-all | 0.653 | observe | 216 | 0.574 | 5519 |
| mheidari-all | 0.385 | observe | 8 | 0.5 | 16071 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5118 |
| Epodonios-all | 0.255 | observe | 0 | None | 6469 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.5 | 4 | 4 | 8 |
| DeltaKronecker-all | 0.574 | 124 | 92 | 216 |
| Surfboard-tg-mixed | 0.648 | 92 | 50 | 142 |
| Au1rxx-base64 | 0.812 | 224 | 52 | 276 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 70 | 0 | 70 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16071 | yes | 4.81 | 0 |
| Epodonios-all | 6469 | yes | 2.5 | 0 |
| SoliSpirit-all | 6373 | yes | 3.13 | 0 |
| Surfboard-tg-mixed | 5803 | yes | 3.59 | 0 |
| DeltaKronecker-all | 5519 | yes | 4.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 5118 | yes | 2.78 | 0 |
| mahdibland-V2RayAggregator | 5089 | yes | 2.32 | 0 |
| barry-far-vless | 4964 | yes | 2.14 | 0 |
| Surfboard-tg-vless | 4538 | yes | 3.76 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.87 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 99 |
| speed | 35 |
| cn-block | 33 |
| 204 | 32 |
