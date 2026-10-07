# AutoNodes 每日报告

生成时间：2026-10-07 23:03:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 98461 |
| 去重后节点数 | 27482 |
| TCP 可达数 | 3000 |
| 真测通过数 | 448 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27482 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 69.9 |
| geo | 1.4 |
| probe | 188.7 |
| real_test | 160.4 |
| tcp | 46.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 2 | 5 | 28.6% |
| http | 39 | 24 | 15 | 61.5% |
| hysteria2 | 24 | 22 | 2 | 91.7% |
| shadowsocks | 157 | 145 | 12 | 92.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 73 | 71 | 2 | 97.3% |
| vless | 234 | 182 | 52 | 77.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 16 |
| cn-block:TimeoutError | 16 |
| speed:ClientOSError | 11 |
| 204:TimeoutError | 11 |
| speed:TimeoutError | 8 |
| geo:TimeoutError | 8 |
| 204:ClientOSError | 6 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6619 |
| ConnectionRefusedError | 1021 |
| gaierror | 376 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.944 | prefer | 42 | 0.881 | 7189 |
| Au1rxx-base64 | 0.943 | prefer | 345 | 0.872 | 1824 |
| mheidari-all | 0.925 | prefer | 95 | 0.853 | 23169 |
| ermaozi | 0.636 | observe | 39 | 0.615 | 664 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7553 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9262 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.215 | 7 | 0.286 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.216 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.167 | 1 | 5 | 6 |
| ermaozi-get_subscribe | 0.286 | 2 | 5 | 7 |
| ermaozi | 0.615 | 24 | 15 | 39 |
| mheidari-all | 0.853 | 81 | 14 | 95 |
| Au1rxx-base64 | 0.872 | 301 | 44 | 345 |
| Surfboard-tg-mixed | 0.881 | 37 | 5 | 42 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23169 | yes | 3.99 | 0 |
| SoliSpirit-all | 9262 | yes | 2.39 | 0 |
| Epodonios-all | 7553 | yes | 0.58 | 0 |
| Surfboard-tg-mixed | 7189 | yes | 2.33 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.15 | 0 |
| barry-far-vless | 5859 | yes | 1.36 | 0 |
| Surfboard-tg-vless | 5706 | yes | 2.67 | 0 |
| DeltaKronecker-all | 5344 | yes | 3.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 5138 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 4431 | yes | 2.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 33 |
| cn-block | 22 |
| speed | 20 |
| geo | 14 |
