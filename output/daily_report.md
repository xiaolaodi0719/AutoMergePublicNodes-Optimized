# AutoNodes 每日报告

生成时间：2026-10-10 21:37:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98061 |
| 去重后节点数 | 27327 |
| TCP 可达数 | 3000 |
| 真测通过数 | 437 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27327 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| generate | 90.6 |
| geo | 1.2 |
| probe | 304.6 |
| real_test | 314.8 |
| tcp | 47.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 1 | 4 | 20.0% |
| http | 33 | 17 | 16 | 51.5% |
| hysteria2 | 16 | 13 | 3 | 81.2% |
| shadowsocks | 121 | 112 | 9 | 92.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 98 | 96 | 2 | 98.0% |
| vless | 283 | 196 | 87 | 69.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 27 |
| 204:TimeoutError | 18 |
| speed:ClientOSError | 13 |
| 204:ProxyConnectionError | 11 |
| 204:ProxyError | 11 |
| geo:ClientOSError | 11 |
| cn-block:ClientOSError | 11 |
| geo:TimeoutError | 7 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6336 |
| ConnectionRefusedError | 1041 |
| gaierror | 422 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.961 | prefer | 351 | 0.889 | 1850 |
| mheidari-all | 0.88 | prefer | 53 | 0.811 | 23925 |
| zhangkai | 0.726 | prefer | 23 | 0.739 | 144 |
| DeltaKronecker-all | 0.619 | observe | 113 | 0.54 | 5009 |
| Surfboard-tg-mixed | 0.438 | observe | 3 | 1.0 | 7118 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7597 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9340 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5677 |

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
| downweight | ermaozi-get_subscribe | 0.122 | 15 | 0.067 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.067 | 1 | 14 | 15 |
| DeltaKronecker-all | 0.54 | 61 | 52 | 113 |
| zhangkai | 0.739 | 17 | 6 | 23 |
| mheidari-all | 0.811 | 43 | 10 | 53 |
| Au1rxx-base64 | 0.889 | 312 | 39 | 351 |
| Surfboard-tg-mixed | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23925 | yes | 7.1 | 0 |
| SoliSpirit-all | 9340 | yes | 3.9 | 0 |
| Epodonios-all | 7597 | yes | 4.27 | 0 |
| Surfboard-tg-mixed | 7118 | yes | 6.42 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.18 | 0 |
| barry-far-vless | 5914 | yes | 2.64 | 0 |
| Surfboard-tg-vless | 5677 | yes | 5.39 | 0 |
| DeltaKronecker-all | 5009 | yes | 7.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4999 | yes | 4.14 | 0 |
| mahdibland-V2RayAggregator | 4347 | yes | 1.96 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 43 |
| cn-block | 38 |
| geo | 21 |
| speed | 20 |
