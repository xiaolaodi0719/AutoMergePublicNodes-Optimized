# AutoNodes 每日报告

生成时间：2026-09-22 21:12:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 88556 |
| 去重后节点数 | 25499 |
| TCP 可达数 | 3000 |
| 真测通过数 | 371 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25499 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 36.7 |
| geo | 1.4 |
| probe | 161.4 |
| real_test | 158.3 |
| tcp | 42.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 19 | 13 | 6 | 68.4% |
| hysteria2 | 23 | 22 | 1 | 95.7% |
| shadowsocks | 113 | 107 | 6 | 94.7% |
| socks | 7 | 3 | 4 | 42.9% |
| trojan | 34 | 23 | 11 | 67.6% |
| vless | 285 | 198 | 87 | 69.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 40 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 15 |
| geo:TimeoutError | 13 |
| geo:ClientOSError | 11 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5463 |
| ConnectionRefusedError | 940 |
| gaierror | 308 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.877 | prefer | 305 | 0.81 | 1718 |
| mheidari-all | 0.833 | prefer | 83 | 0.759 | 15951 |
| DeltaKronecker-all | 0.774 | prefer | 47 | 0.702 | 6324 |
| ermaozi | 0.653 | observe | 15 | 0.8 | 325 |
| Surfboard-tg-mixed | 0.515 | observe | 11 | 0.636 | 7279 |
| xiaoji235-airport-v2ray-all | 0.441 | observe | 13 | 0.462 | 4242 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 116 |
| Epodonios-all | 0.255 | observe | 0 | None | 7749 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9217 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-ScrapeCategorize-Vless | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.2 | 1 | 4 | 5 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| xiaoji235-airport-v2ray-all | 0.462 | 6 | 7 | 13 |
| Surfboard-tg-mixed | 0.636 | 7 | 4 | 11 |
| DeltaKronecker-all | 0.702 | 33 | 14 | 47 |
| mheidari-all | 0.759 | 63 | 20 | 83 |
| ermaozi | 0.8 | 12 | 3 | 15 |
| Au1rxx-base64 | 0.81 | 247 | 58 | 305 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15951 | yes | 5.02 | 0 |
| SoliSpirit-all | 9217 | yes | 4.6 | 0 |
| Epodonios-all | 7749 | yes | 3.32 | 0 |
| Surfboard-tg-mixed | 7279 | yes | 4.47 | 0 |
| DeltaKronecker-all | 6324 | yes | 6.15 | 0 |
| Surfboard-tg-vless | 5930 | yes | 3.72 | 0 |
| barry-far-vless | 5928 | yes | 0.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 1.12 | 0 |
| mahdibland-V2RayAggregator | 4252 | yes | 0.8 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 3.02 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 43 |
| 204 | 26 |
| geo | 24 |
| cn-block | 22 |
