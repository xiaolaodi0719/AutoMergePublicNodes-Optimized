# AutoNodes 每日报告

生成时间：2026-08-27 08:35:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 88922 |
| 去重后节点数 | 24474 |
| TCP 可达数 | 3000 |
| 真测通过数 | 486 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24474 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 36.8 |
| geo | 1.4 |
| probe | 49.2 |
| real_test | 107.4 |
| tcp | 40.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 179 | 171 | 8 | 95.5% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 22 | 20 | 2 | 90.9% |
| vless | 393 | 252 | 141 | 64.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 61 |
| geo:TimeoutError | 30 |
| speed:TimeoutError | 15 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 13 |
| 204:TimeoutError | 9 |
| 204:ProxyError | 5 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 3 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5891 |
| ConnectionRefusedError | 932 |
| OSError | 232 |
| gaierror | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.993 | prefer | 318 | 0.928 | 1712 |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.883 | prefer | 135 | 0.807 | 6600 |
| mheidari-all | 0.454 | observe | 153 | 0.373 | 19260 |
| DeltaKronecker-all | 0.352 | observe | 11 | 0.364 | 6107 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4825 |
| Epodonios-all | 0.255 | observe | 0 | None | 7097 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7132 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5353 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.364 | 4 | 7 | 11 |
| mheidari-all | 0.373 | 57 | 96 | 153 |
| Surfboard-tg-mixed | 0.807 | 109 | 26 | 135 |
| Au1rxx-base64 | 0.928 | 295 | 23 | 318 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19260 | yes | 4.09 | 0 |
| SoliSpirit-all | 7132 | yes | 2.99 | 0 |
| Epodonios-all | 7097 | yes | 2.42 | 0 |
| Surfboard-tg-mixed | 6600 | yes | 3.07 | 0 |
| DeltaKronecker-all | 6107 | yes | 4.1 | 0 |
| barry-far-vless | 5696 | yes | 2.29 | 0 |
| xiaoji235-airport-v2ray-all | 5418 | yes | 3.41 | 0 |
| Surfboard-tg-vless | 5353 | yes | 2.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 4825 | yes | 2.49 | 0 |
| mahdibland-V2RayAggregator | 4011 | yes | 2.18 | 0 |

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
| geo | 91 |
| speed | 31 |
| cn-block | 17 |
| 204 | 16 |
