# AutoNodes 每日报告

生成时间：2026-09-12 20:31:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 83799 |
| 去重后节点数 | 23044 |
| TCP 可达数 | 3000 |
| 真测通过数 | 382 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23044 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 72.1 |
| geo | 1.4 |
| probe | 179.6 |
| real_test | 212.7 |
| tcp | 38.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 23 | 5 | 18 | 21.7% |
| hysteria2 | 28 | 20 | 8 | 71.4% |
| shadowsocks | 140 | 123 | 17 | 87.9% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 31 | 18 | 13 | 58.1% |
| vless | 283 | 213 | 70 | 75.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyConnectionError | 23 |
| geo:ClientOSError | 23 |
| 204:TimeoutError | 21 |
| speed:ClientOSError | 16 |
| 204:ProxyError | 12 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 10 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5087 |
| ConnectionRefusedError | 918 |
| gaierror | 529 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.916 | prefer | 312 | 0.853 | 1650 |
| mheidari-all | 0.821 | prefer | 56 | 0.75 | 15722 |
| Surfboard-tg-mixed | 0.678 | observe | 100 | 0.6 | 7382 |
| DeltaKronecker-all | 0.482 | observe | 14 | 0.5 | 5970 |
| ermaozi | 0.292 | observe | 19 | 0.263 | 393 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 161 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7802 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.09 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 5 | 5 |
| ermaozi | 0.263 | 5 | 14 | 19 |
| DeltaKronecker-all | 0.5 | 7 | 7 | 14 |
| Surfboard-tg-mixed | 0.6 | 60 | 40 | 100 |
| mheidari-all | 0.75 | 42 | 14 | 56 |
| Au1rxx-base64 | 0.853 | 266 | 46 | 312 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15722 | yes | 4.81 | 0 |
| SoliSpirit-all | 8908 | yes | 2.79 | 0 |
| Epodonios-all | 7802 | yes | 3.3 | 0 |
| Surfboard-tg-mixed | 7382 | yes | 5.37 | 0 |
| barry-far-vless | 6127 | yes | 1.97 | 0 |
| Surfboard-tg-vless | 5991 | yes | 4.15 | 0 |
| DeltaKronecker-all | 5970 | yes | 4.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 2.16 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 0.62 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 58 |
| geo | 28 |
| cn-block | 23 |
| speed | 18 |
