# AutoNodes 每日报告

生成时间：2026-10-07 05:31:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97105 |
| 去重后节点数 | 27062 |
| TCP 可达数 | 3000 |
| 真测通过数 | 478 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27062 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 75.3 |
| geo | 1.5 |
| probe | 324.1 |
| real_test | 437.1 |
| tcp | 46.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 48 | 24 | 24 | 50.0% |
| hysteria2 | 21 | 18 | 3 | 85.7% |
| shadowsocks | 166 | 153 | 13 | 92.2% |
| socks | 9 | 5 | 4 | 55.6% |
| trojan | 108 | 93 | 15 | 86.1% |
| vless | 459 | 185 | 274 | 40.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 151 |
| speed:TimeoutError | 60 |
| geo:ClientOSError | 30 |
| 204:TimeoutError | 24 |
| 204:ProxyError | 23 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 12 |
| 204:ProxyConnectionError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6734 |
| ConnectionRefusedError | 977 |
| gaierror | 368 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | prefer | 300 | 0.897 | 1797 |
| Surfboard-tg-mixed | 0.765 | prefer | 71 | 0.69 | 7006 |
| ermaozi | 0.529 | observe | 48 | 0.5 | 726 |
| mheidari-all | 0.432 | observe | 379 | 0.351 | 22990 |
| DeltaKronecker-all | 0.305 | observe | 10 | 0.3 | 4889 |
| Epodonios-all | 0.255 | observe | 0 | None | 7476 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9204 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5583 |
| barry-far-vless | 0.255 | observe | 0 | None | 5829 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.3 | 3 | 7 | 10 |
| mheidari-all | 0.351 | 133 | 246 | 379 |
| ermaozi | 0.5 | 24 | 24 | 48 |
| Surfboard-tg-mixed | 0.69 | 49 | 22 | 71 |
| Au1rxx-base64 | 0.897 | 269 | 31 | 300 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22990 | yes | 6.31 | 0 |
| SoliSpirit-all | 9204 | yes | 4.22 | 0 |
| Epodonios-all | 7476 | yes | 4.37 | 0 |
| Surfboard-tg-mixed | 7006 | yes | 4.59 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.84 | 0 |
| barry-far-vless | 5829 | yes | 5.28 | 0 |
| Surfboard-tg-vless | 5583 | yes | 6.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 2.59 | 0 |
| DeltaKronecker-all | 4889 | yes | 6.79 | 0 |
| mahdibland-V2RayAggregator | 4373 | yes | 2.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 183 |
| speed | 72 |
| 204 | 56 |
| cn-block | 22 |
