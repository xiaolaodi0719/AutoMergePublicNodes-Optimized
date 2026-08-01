# AutoNodes 每日报告

生成时间：2026-08-01 19:21:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78665 |
| 去重后节点数 | 23513 |
| TCP 可达数 | 3000 |
| 真测通过数 | 574 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23513 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 13.8 |
| generate | 46.5 |
| geo | 1.4 |
| probe | 67.1 |
| real_test | 155.4 |
| tcp | 35.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 146 | 146 | 0 | 100.0% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 116 | 93 | 23 | 80.2% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 26 | 24 | 2 | 92.3% |
| vless | 532 | 289 | 243 | 54.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 97 |
| 204:ProxyError | 39 |
| speed:TimeoutError | 34 |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 22 |
| geo:ClientOSError | 19 |
| speed:ClientOSError | 15 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4649 |
| ConnectionRefusedError | 796 |
| gaierror | 317 |
| OSError | 223 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.994 | prefer | 148 | 0.993 | 194 |
| Au1rxx-base64 | 0.783 | prefer | 469 | 0.716 | 1692 |
| Surfboard-tg-mixed | 0.489 | observe | 9 | 0.667 | 5294 |
| DeltaKronecker-all | 0.469 | observe | 214 | 0.388 | 5502 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 16619 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 55 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5391 |
| Epodonios-all | 0.255 | observe | 0 | None | 5909 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3975 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6647 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.388 | 83 | 131 | 214 |
| Surfboard-tg-mixed | 0.667 | 6 | 3 | 9 |
| Au1rxx-base64 | 0.716 | 336 | 133 | 469 |
| zhangkai | 0.993 | 147 | 1 | 148 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16619 | yes | 5.24 | 0 |
| SoliSpirit-all | 6647 | yes | 4.2 | 0 |
| Epodonios-all | 5909 | yes | 4.74 | 0 |
| DeltaKronecker-all | 5502 | yes | 5.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 5391 | yes | 3.04 | 0 |
| Surfboard-tg-mixed | 5294 | yes | 3.95 | 0 |
| mahdibland-V2RayAggregator | 5071 | yes | 4.56 | 0 |
| barry-far-vless | 4547 | yes | 2.01 | 0 |
| Surfboard-tg-vless | 4168 | yes | 4.09 | 0 |
| MatinGhanbari-all-sub | 3975 | yes | 3.12 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 117 |
| 204 | 72 |
| speed | 49 |
| cn-block | 32 |
