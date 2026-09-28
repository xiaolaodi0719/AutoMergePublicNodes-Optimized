# AutoNodes 每日报告

生成时间：2026-09-28 04:58:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 95255 |
| 去重后节点数 | 26807 |
| TCP 可达数 | 3000 |
| 真测通过数 | 535 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26807 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 88.6 |
| geo | 1.6 |
| probe | 343.9 |
| real_test | 492.4 |
| tcp | 44.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 34 | 15 | 69.4% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 191 | 176 | 15 | 92.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 23 | 9 | 14 | 39.1% |
| vless | 699 | 294 | 405 | 42.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 187 |
| speed:TimeoutError | 83 |
| geo:ClientOSError | 52 |
| speed:ClientOSError | 45 |
| 204:ProxyError | 33 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6105 |
| ConnectionRefusedError | 954 |
| gaierror | 396 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.903 | prefer | 321 | 0.847 | 1437 |
| Surfboard-tg-mixed | 0.747 | prefer | 76 | 0.671 | 6916 |
| ermaozi | 0.735 | prefer | 41 | 0.732 | 347 |
| mheidari-all | 0.409 | observe | 533 | 0.328 | 22305 |
| DeltaKronecker-all | 0.373 | observe | 5 | 0.6 | 5466 |
| tg-oneclickvpnkeys | 0.313 | observe | 2 | 1.0 | 51 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7506 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9195 |

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
| downweight | ermaozi-get_subscribe | 0.207 | 7 | 0.286 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.286 | 2 | 5 | 7 |
| mheidari-all | 0.328 | 175 | 358 | 533 |
| DeltaKronecker-all | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.671 | 51 | 25 | 76 |
| ermaozi | 0.732 | 30 | 11 | 41 |
| Au1rxx-base64 | 0.847 | 272 | 49 | 321 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22305 | yes | 5.09 | 0 |
| SoliSpirit-all | 9195 | yes | 5.27 | 0 |
| Epodonios-all | 7506 | yes | 1.63 | 0 |
| Surfboard-tg-mixed | 6916 | yes | 3.06 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.47 | 0 |
| barry-far-vless | 5817 | yes | 1.86 | 0 |
| Surfboard-tg-vless | 5591 | yes | 2.86 | 0 |
| DeltaKronecker-all | 5466 | yes | 4.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 2.65 | 0 |
| mahdibland-V2RayAggregator | 4185 | yes | 1.46 | 0 |

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
| geo | 241 |
| speed | 128 |
| 204 | 56 |
| cn-block | 26 |
