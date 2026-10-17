# AutoNodes 每日报告

生成时间：2026-10-17 15:29:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99271 |
| 去重后节点数 | 27588 |
| TCP 可达数 | 3000 |
| 真测通过数 | 426 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27588 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| generate | 95.8 |
| geo | 1.5 |
| probe | 280.5 |
| real_test | 267.4 |
| tcp | 48.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 34 | 26 | 8 | 76.5% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 146 | 128 | 18 | 87.7% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 37 | 32 | 5 | 86.5% |
| vless | 324 | 222 | 102 | 68.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 41 |
| 204:ProxyError | 19 |
| speed:ClientOSError | 16 |
| cn-block:TimeoutError | 15 |
| geo:ClientOSError | 11 |
| speed:TimeoutError | 11 |
| 204:ClientOSError | 7 |
| cn-block:ProxyError | 5 |
| geo:TimeoutError | 5 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6794 |
| ConnectionRefusedError | 1046 |
| gaierror | 290 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.882 | prefer | 478 | 0.803 | 1993 |
| ermaozi | 0.813 | prefer | 31 | 0.806 | 623 |
| ermaozi-get_subscribe | 0.378 | observe | 3 | 1.0 | 510 |
| mheidari-all | 0.372 | observe | 9 | 0.444 | 23770 |
| Surfboard-tg-mixed | 0.366 | observe | 33 | 0.273 | 7171 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1993 |
| Epodonios-all | 0.255 | observe | 0 | None | 7678 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10049 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| Surfboard-tg-mixed | 0.273 | 9 | 24 | 33 |
| tg-oneclickvpnkeys | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.444 | 4 | 5 | 9 |
| Au1rxx-base64 | 0.803 | 384 | 94 | 478 |
| ermaozi | 0.806 | 25 | 6 | 31 |
| ermaozi-get_subscribe | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23770 | yes | 6.61 | 0 |
| SoliSpirit-all | 10049 | yes | 6.01 | 0 |
| Epodonios-all | 7678 | yes | 5.93 | 0 |
| Surfboard-tg-mixed | 7171 | yes | 5.71 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.88 | 0 |
| barry-far-vless | 5865 | yes | 3.22 | 0 |
| Surfboard-tg-vless | 5617 | yes | 5.47 | 0 |
| DeltaKronecker-all | 4999 | yes | 7.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 3.09 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 1.3 | 0 |

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
| 204 | 67 |
| speed | 28 |
| cn-block | 23 |
| geo | 18 |
