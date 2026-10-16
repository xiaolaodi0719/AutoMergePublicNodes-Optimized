# AutoNodes 每日报告

生成时间：2026-10-16 16:36:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 99087 |
| 去重后节点数 | 27705 |
| TCP 可达数 | 3000 |
| 真测通过数 | 374 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27705 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| generate | 148.6 |
| geo | 1.5 |
| probe | 279.1 |
| real_test | 265.5 |
| tcp | 47.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 3 | 2 | 60.0% |
| http | 30 | 4 | 26 | 13.3% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 147 | 133 | 14 | 90.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 39 | 34 | 5 | 87.2% |
| vless | 290 | 182 | 108 | 62.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 34 |
| 204:ProxyError | 28 |
| cn-block:TimeoutError | 22 |
| speed:ClientOSError | 16 |
| speed:TimeoutError | 12 |
| geo:ClientOSError | 11 |
| 204:ProxyConnectionError | 9 |
| geo:TimeoutError | 9 |
| 204:ClientOSError | 7 |
| cn-block:ClientOSError | 7 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6368 |
| ConnectionRefusedError | 1069 |
| gaierror | 279 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.847 | prefer | 450 | 0.769 | 1991 |
| Surfboard-tg-mixed | 0.509 | observe | 26 | 0.423 | 7090 |
| mheidari-all | 0.432 | observe | 14 | 0.429 | 23974 |
| ermaozi-get_subscribe | 0.377 | observe | 3 | 1.0 | 484 |
| DeltaKronecker-all | 0.284 | observe | 6 | 0.333 | 4946 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| peasoft-NoMoreWalls | 0.261 | observe | 1 | 1.0 | 143 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 79 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1991 |

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
| downweight | ermaozi | 0.154 | 29 | 0.103 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.103 | 3 | 26 | 29 |
| DeltaKronecker-all | 0.333 | 2 | 4 | 6 |
| Surfboard-tg-mixed | 0.423 | 11 | 15 | 26 |
| mheidari-all | 0.429 | 6 | 8 | 14 |
| Au1rxx-base64 | 0.769 | 346 | 104 | 450 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| peasoft-NoMoreWalls | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23974 | yes | 6.8 | 0 |
| SoliSpirit-all | 9917 | yes | 4.32 | 0 |
| Epodonios-all | 7602 | yes | 7.1 | 0 |
| Surfboard-tg-mixed | 7090 | yes | 4.37 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.96 | 0 |
| barry-far-vless | 5822 | yes | 3.04 | 0 |
| Surfboard-tg-vless | 5572 | yes | 5.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 2.83 | 0 |
| DeltaKronecker-all | 4946 | yes | 7.33 | 0 |
| mahdibland-V2RayAggregator | 4265 | yes | 0.28 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 78 |
| cn-block | 30 |
| speed | 30 |
| geo | 20 |
