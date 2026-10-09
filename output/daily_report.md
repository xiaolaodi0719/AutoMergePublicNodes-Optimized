# AutoNodes 每日报告

生成时间：2026-10-09 13:08:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98198 |
| 去重后节点数 | 27457 |
| TCP 可达数 | 3000 |
| 真测通过数 | 407 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27457 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 87.6 |
| geo | 1.7 |
| probe | 305.5 |
| real_test | 360.4 |
| tcp | 47.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 2 | 4 | 33.3% |
| http | 59 | 25 | 34 | 42.4% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 151 | 123 | 28 | 81.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 130 | 97 | 33 | 74.6% |
| vless | 211 | 146 | 65 | 69.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 49 |
| cn-block:TimeoutError | 32 |
| 204:ProxyError | 30 |
| 204:ProxyConnectionError | 10 |
| geo:ClientOSError | 10 |
| speed:TimeoutError | 9 |
| geo:TimeoutError | 9 |
| speed:ClientOSError | 8 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6656 |
| ConnectionRefusedError | 1005 |
| gaierror | 362 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.904 | prefer | 342 | 0.833 | 1810 |
| zhangkai | 0.881 | prefer | 22 | 0.909 | 144 |
| mheidari-all | 0.747 | prefer | 40 | 0.675 | 23165 |
| Surfboard-tg-mixed | 0.649 | observe | 100 | 0.57 | 7139 |
| DeltaKronecker-all | 0.465 | observe | 24 | 0.375 | 5154 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4984 |
| Epodonios-all | 0.255 | observe | 0 | None | 7541 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| downweight | ermaozi-get_subscribe | 0.198 | 44 | 0.159 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.159 | 7 | 37 | 44 |
| DeltaKronecker-all | 0.375 | 9 | 15 | 24 |
| Surfboard-tg-mixed | 0.57 | 57 | 43 | 100 |
| mheidari-all | 0.675 | 27 | 13 | 40 |
| Au1rxx-base64 | 0.833 | 285 | 57 | 342 |
| zhangkai | 0.909 | 20 | 2 | 22 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23165 | yes | 5.84 | 0 |
| SoliSpirit-all | 10038 | yes | 3.24 | 0 |
| Epodonios-all | 7541 | yes | 3.54 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 4.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.3 | 0 |
| barry-far-vless | 5830 | yes | 1.98 | 0 |
| Surfboard-tg-vless | 5578 | yes | 4.71 | 0 |
| DeltaKronecker-all | 5154 | yes | 4.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4984 | yes | 0.71 | 0 |
| mahdibland-V2RayAggregator | 4362 | yes | 3.34 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 90 |
| cn-block | 40 |
| geo | 20 |
| speed | 18 |
