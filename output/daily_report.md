# AutoNodes 每日报告

生成时间：2026-09-30 12:24:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96400 |
| 去重后节点数 | 26890 |
| TCP 可达数 | 3000 |
| 真测通过数 | 396 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26890 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 89.6 |
| geo | 1.6 |
| probe | 265.6 |
| real_test | 183.7 |
| tcp | 45.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 54 | 43 | 11 | 79.6% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 165 | 146 | 19 | 88.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 32 | 23 | 9 | 71.9% |
| vless | 266 | 166 | 100 | 62.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 52 |
| 204:TimeoutError | 24 |
| 204:ProxyError | 17 |
| cn-block:TimeoutError | 15 |
| geo:TimeoutError | 13 |
| cn-block:ClientOSError | 10 |
| speed:TimeoutError | 6 |
| 204:ProxyConnectionError | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6288 |
| ConnectionRefusedError | 1003 |
| gaierror | 354 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.87 | prefer | 278 | 0.802 | 1752 |
| mheidari-all | 0.807 | prefer | 53 | 0.736 | 22755 |
| ermaozi | 0.795 | prefer | 53 | 0.792 | 335 |
| Surfboard-tg-mixed | 0.683 | observe | 134 | 0.604 | 6952 |
| DeltaKronecker-all | 0.474 | observe | 15 | 0.467 | 5434 |
| tg-oneclickvpnkeys | 0.36 | observe | 3 | 1.0 | 53 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 164 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7458 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.467 | 7 | 8 | 15 |
| Surfboard-tg-mixed | 0.604 | 81 | 53 | 134 |
| mheidari-all | 0.736 | 39 | 14 | 53 |
| ermaozi | 0.792 | 42 | 11 | 53 |
| Au1rxx-base64 | 0.802 | 223 | 55 | 278 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22755 | yes | 5.58 | 0 |
| SoliSpirit-all | 9148 | yes | 3.11 | 0 |
| Epodonios-all | 7458 | yes | 3.23 | 0 |
| Surfboard-tg-mixed | 6952 | yes | 4.1 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.15 | 0 |
| barry-far-vless | 5879 | yes | 2.04 | 0 |
| Surfboard-tg-vless | 5632 | yes | 3.66 | 0 |
| DeltaKronecker-all | 5434 | yes | 5.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.65 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 2.91 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 58 |
| 204 | 44 |
| cn-block | 26 |
| geo | 15 |
