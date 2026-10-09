# AutoNodes 每日报告

生成时间：2026-10-09 22:39:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 4/101 |
| 原始节点数 | 97854 |
| 去重后节点数 | 27601 |
| TCP 可达数 | 3000 |
| 真测通过数 | 444 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27601 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 79.8 |
| geo | 1.7 |
| probe | 250.2 |
| real_test | 274.8 |
| tcp | 47.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 2 | 4 | 33.3% |
| http | 23 | 15 | 8 | 65.2% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 126 | 119 | 7 | 94.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 99 | 99 | 0 | 100.0% |
| vless | 225 | 187 | 38 | 83.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 12 |
| 204:ProxyError | 9 |
| speed:ClientOSError | 9 |
| 204:ProxyConnectionError | 6 |
| geo:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| 204:TimeoutError | 5 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6757 |
| ConnectionRefusedError | 1017 |
| gaierror | 354 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | prefer | 27 | 0.963 | 7025 |
| Au1rxx-base64 | 0.99 | prefer | 373 | 0.92 | 1805 |
| mheidari-all | 0.916 | prefer | 65 | 0.846 | 23076 |
| zhangkai | 0.779 | prefer | 16 | 0.938 | 144 |
| tg-V2RAYProxy | 0.264 | observe | 1 | 1.0 | 217 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4984 |
| Epodonios-all | 0.255 | observe | 0 | None | 7582 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9986 |

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
| downweight | ermaozi-get_subscribe | 0.175 | 14 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.143 | 2 | 12 | 14 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.846 | 55 | 10 | 65 |
| Au1rxx-base64 | 0.92 | 343 | 30 | 373 |
| zhangkai | 0.938 | 15 | 1 | 16 |
| Surfboard-tg-mixed | 0.963 | 26 | 1 | 27 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-V2RAYProxy | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23076 | yes | 6.37 | 0 |
| SoliSpirit-all | 9986 | yes | 1.92 | 0 |
| Epodonios-all | 7582 | yes | 4.09 | 0 |
| Surfboard-tg-mixed | 7025 | yes | 4.42 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 4.03 | 0 |
| barry-far-vless | 5812 | yes | 0.93 | 0 |
| Surfboard-tg-vless | 5553 | yes | 4.86 | 0 |
| DeltaKronecker-all | 5154 | yes | 6.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 4984 | yes | 1.41 | 0 |
| mahdibland-V2RayAggregator | 4346 | yes | 3.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 22 |
| cn-block | 17 |
| speed | 13 |
| geo | 6 |
