# AutoNodes 每日报告

生成时间：2026-10-11 12:39:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 98718 |
| 去重后节点数 | 27554 |
| TCP 可达数 | 3000 |
| 真测通过数 | 479 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27554 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 78.8 |
| geo | 1.5 |
| probe | 297.1 |
| real_test | 337.3 |
| tcp | 45.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 0 | 8 | 0.0% |
| http | 15 | 6 | 9 | 40.0% |
| hysteria2 | 25 | 25 | 0 | 100.0% |
| shadowsocks | 154 | 136 | 18 | 88.3% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 186 | 175 | 11 | 94.1% |
| vless | 163 | 137 | 26 | 84.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 14 |
| 204:TimeoutError | 14 |
| speed:ClientOSError | 11 |
| 204:ProxyConnectionError | 9 |
| 204:ProxyError | 9 |
| geo:TimeoutError | 5 |
| speed:TimeoutError | 4 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5820 |
| ConnectionRefusedError | 1043 |
| gaierror | 496 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | prefer | 364 | 0.923 | 1835 |
| mheidari-all | 0.994 | prefer | 56 | 0.929 | 23631 |
| Surfboard-tg-mixed | 0.853 | prefer | 64 | 0.781 | 7157 |
| DeltaKronecker-all | 0.853 | prefer | 42 | 0.786 | 5372 |
| ermaozi | 0.412 | observe | 16 | 0.438 | 635 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5099 |
| Epodonios-all | 0.255 | observe | 0 | None | 7574 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9584 |

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
| downweight | ermaozi-get_subscribe | 0.081 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 8 | 8 |
| ermaozi | 0.438 | 7 | 9 | 16 |
| Surfboard-tg-mixed | 0.781 | 50 | 14 | 64 |
| DeltaKronecker-all | 0.786 | 33 | 9 | 42 |
| Au1rxx-base64 | 0.923 | 336 | 28 | 364 |
| mheidari-all | 0.929 | 52 | 4 | 56 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23631 | yes | 6.3 | 0 |
| SoliSpirit-all | 9584 | yes | 4.96 | 0 |
| Epodonios-all | 7574 | yes | 6.5 | 0 |
| Surfboard-tg-mixed | 7157 | yes | 4.19 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.14 | 0 |
| barry-far-vless | 5786 | yes | 2.41 | 0 |
| Surfboard-tg-vless | 5553 | yes | 4.64 | 0 |
| DeltaKronecker-all | 5372 | yes | 6.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 5099 | yes | 1.99 | 0 |
| mahdibland-V2RayAggregator | 4318 | yes | 2.56 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 35 |
| cn-block | 19 |
| speed | 15 |
| geo | 5 |
