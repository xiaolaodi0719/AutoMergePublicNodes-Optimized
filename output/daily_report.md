# AutoNodes 每日报告

生成时间：2026-10-18 10:54:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 98645 |
| 去重后节点数 | 27677 |
| TCP 可达数 | 3000 |
| 真测通过数 | 409 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27677 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 76.9 |
| geo | 1.5 |
| probe | 297.5 |
| real_test | 293.6 |
| tcp | 49.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 98 | 51 | 47 | 52.0% |
| hysteria2 | 18 | 14 | 4 | 77.8% |
| shadowsocks | 136 | 125 | 11 | 91.9% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 51 | 31 | 20 | 60.8% |
| vless | 284 | 184 | 100 | 64.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 49 |
| 204:TimeoutError | 37 |
| cn-block:TimeoutError | 26 |
| geo:ClientOSError | 18 |
| 204:ClientOSError | 12 |
| geo:TimeoutError | 11 |
| speed:TimeoutError | 10 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7395 |
| ConnectionRefusedError | 1041 |
| OSError | 235 |
| gaierror | 142 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.882 | prefer | 408 | 0.806 | 1920 |
| ermaozi | 0.558 | observe | 100 | 0.53 | 710 |
| Surfboard-tg-mixed | 0.433 | observe | 66 | 0.348 | 7030 |
| mheidari-all | 0.281 | observe | 14 | 0.214 | 23769 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| Epodonios-all | 0.255 | observe | 0 | None | 7561 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10015 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5615 |
| barry-far-vless | 0.255 | observe | 0 | None | 5830 |

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
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.214 | 3 | 11 | 14 |
| Surfboard-tg-mixed | 0.348 | 23 | 43 | 66 |
| ermaozi | 0.53 | 53 | 47 | 100 |
| Au1rxx-base64 | 0.806 | 329 | 79 | 408 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23769 | yes | 3.55 | 0 |
| SoliSpirit-all | 10015 | yes | 2.88 | 0 |
| Epodonios-all | 7561 | yes | 3.66 | 0 |
| Surfboard-tg-mixed | 7030 | yes | 3.12 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.87 | 0 |
| barry-far-vless | 5830 | yes | 1.42 | 0 |
| Surfboard-tg-vless | 5615 | yes | 2.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 1.31 | 0 |
| DeltaKronecker-all | 4750 | yes | 3.8 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 1.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 98 |
| cn-block | 34 |
| geo | 32 |
| speed | 20 |
