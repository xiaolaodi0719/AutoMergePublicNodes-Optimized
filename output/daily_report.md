# AutoNodes 每日报告

生成时间：2026-08-29 06:37:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 76907 |
| 去重后节点数 | 20895 |
| TCP 可达数 | 3000 |
| 真测通过数 | 622 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 20895 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 42.8 |
| geo | 1.4 |
| probe | 57.5 |
| real_test | 130.3 |
| tcp | 34.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 179 | 163 | 16 | 91.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 39 | 33 | 6 | 84.6% |
| vless | 490 | 376 | 114 | 76.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 27 |
| speed:TimeoutError | 24 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 19 |
| geo:TimeoutError | 16 |
| 204:ProxyError | 11 |
| cn-block:ClientOSError | 9 |
| speed:ClientOSError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4465 |
| ConnectionRefusedError | 889 |
| gaierror | 487 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | prefer | 378 | 0.889 | 1789 |
| zhangkai | 0.922 | prefer | 22 | 0.955 | 144 |
| mheidari-all | 0.83 | prefer | 102 | 0.755 | 14598 |
| Surfboard-tg-mixed | 0.827 | prefer | 93 | 0.753 | 6733 |
| DeltaKronecker-all | 0.819 | prefer | 155 | 0.742 | 4065 |
| tg-oneclickvpnkeys | 0.364 | observe | 3 | 1.0 | 139 |
| Epodonios-all | 0.255 | observe | 0 | None | 7084 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7191 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5530 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| Pawdroid | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.742 | 115 | 40 | 155 |
| Surfboard-tg-mixed | 0.753 | 70 | 23 | 93 |
| mheidari-all | 0.755 | 77 | 25 | 102 |
| Au1rxx-base64 | 0.889 | 336 | 42 | 378 |
| zhangkai | 0.955 | 21 | 1 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14598 | yes | 5.34 | 0 |
| SoliSpirit-all | 7191 | yes | 2.74 | 0 |
| Epodonios-all | 7084 | yes | 1.83 | 0 |
| Surfboard-tg-mixed | 6733 | yes | 3.83 | 0 |
| barry-far-vless | 5694 | yes | 2.06 | 0 |
| Surfboard-tg-vless | 5530 | yes | 3.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 4725 | yes | 1.95 | 0 |
| mahdibland-V2RayAggregator | 4093 | yes | 1.54 | 0 |
| DeltaKronecker-all | 4065 | yes | 4.38 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.75 | 0 |

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
| geo | 44 |
| 204 | 35 |
| cn-block | 30 |
| speed | 30 |
