# AutoNodes 每日报告

生成时间：2026-10-15 04:10:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 1/104 |
| 原始节点数 | 98808 |
| 去重后节点数 | 27486 |
| TCP 可达数 | 3000 |
| 真测通过数 | 233 |
| verified 输出数 | 233 |
| global 输出数 | 240 |
| all 输出数 | 27486 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 23.8 |
| geo | 1.6 |
| probe | 237.2 |
| real_test | 236.8 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 53 | 22 | 31 | 41.5% |
| hysteria2 | 9 | 8 | 1 | 88.9% |
| shadowsocks | 156 | 143 | 13 | 91.7% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 42 | 36 | 6 | 85.7% |
| vless | 135 | 16 | 119 | 11.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 83 |
| 204:ProxyError | 31 |
| geo:ClientOSError | 22 |
| speed:TimeoutError | 10 |
| 204:TimeoutError | 9 |
| 204:ClientOSError | 6 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6793 |
| ConnectionRefusedError | 1040 |
| OSError | 237 |
| gaierror | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | prefer | 190 | 0.937 | 1576 |
| ermaozi | 0.467 | observe | 55 | 0.436 | 703 |
| Surfboard-tg-mixed | 0.43 | observe | 38 | 0.342 | 7169 |
| ermaozi-get_subscribe | 0.382 | observe | 3 | 1.0 | 595 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7681 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9917 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5728 |
| barry-far-vless | 0.255 | observe | 0 | None | 5978 |

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
| downweight | mheidari-all | 0.206 | 109 | 0.119 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.249 | 10 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.119 | 13 | 96 | 109 |
| DeltaKronecker-all | 0.2 | 2 | 8 | 10 |
| Surfboard-tg-mixed | 0.342 | 13 | 25 | 38 |
| ermaozi | 0.436 | 24 | 31 | 55 |
| Au1rxx-base64 | 0.937 | 178 | 12 | 190 |
| ermaozi-get_subscribe | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23886 | yes | 7.59 | 0 |
| SoliSpirit-all | 9917 | yes | 2.32 | 0 |
| Epodonios-all | 7681 | yes | 5.08 | 0 |
| Surfboard-tg-mixed | 7169 | yes | 4.76 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.07 | 0 |
| barry-far-vless | 5978 | yes | 0.63 | 0 |
| Surfboard-tg-vless | 5728 | yes | 4.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 0.87 | 0 |
| DeltaKronecker-all | 4803 | yes | 5.06 | 0 |
| mahdibland-V2RayAggregator | 4271 | yes | 3.51 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 105 |
| 204 | 50 |
| speed | 10 |
| cn-block | 8 |
