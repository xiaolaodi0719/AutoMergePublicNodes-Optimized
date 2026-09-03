# AutoNodes 每日报告

生成时间：2026-09-03 20:51:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 82446 |
| 去重后节点数 | 22585 |
| TCP 可达数 | 3000 |
| 真测通过数 | 577 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22585 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| generate | 37.2 |
| geo | 1.4 |
| probe | 67.0 |
| real_test | 111.5 |
| tcp | 38.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 26 | 26 | 0 | 100.0% |
| hysteria2 | 26 | 24 | 2 | 92.3% |
| shadowsocks | 160 | 151 | 9 | 94.4% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 45 | 36 | 9 | 80.0% |
| vless | 391 | 336 | 55 | 85.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 17 |
| geo:ClientOSError | 13 |
| cn-block:ProxyError | 6 |
| speed:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| geo:TimeoutError | 3 |
| 204:ProxyError | 2 |
| geo:ProxyError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5481 |
| ConnectionRefusedError | 909 |
| gaierror | 225 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 365 | 0.951 | 1748 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| mheidari-all | 0.92 | prefer | 98 | 0.847 | 15893 |
| Surfboard-tg-mixed | 0.811 | prefer | 76 | 0.737 | 7177 |
| DeltaKronecker-all | 0.81 | prefer | 87 | 0.736 | 6335 |
| tg-oneclickvpnkeys | 0.405 | observe | 4 | 1.0 | 115 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4671 |
| Epodonios-all | 0.255 | observe | 0 | None | 7695 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8160 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.736 | 64 | 23 | 87 |
| Surfboard-tg-mixed | 0.737 | 56 | 20 | 76 |
| mheidari-all | 0.847 | 83 | 15 | 98 |
| Au1rxx-base64 | 0.951 | 347 | 18 | 365 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15893 | yes | 2.54 | 0 |
| SoliSpirit-all | 8160 | yes | 3.19 | 0 |
| Epodonios-all | 7695 | yes | 0.37 | 0 |
| Surfboard-tg-mixed | 7177 | yes | 2.28 | 0 |
| DeltaKronecker-all | 6335 | yes | 2.72 | 0 |
| barry-far-vless | 6131 | yes | 1.1 | 0 |
| Surfboard-tg-vless | 5920 | yes | 3.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4671 | yes | 1.22 | 0 |
| mahdibland-V2RayAggregator | 4133 | yes | 1.74 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.96 | 0 |

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
| cn-block | 28 |
| 204 | 21 |
| geo | 18 |
| speed | 10 |
