# AutoNodes 每日报告

生成时间：2026-09-05 14:59:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83843 |
| 去重后节点数 | 22680 |
| TCP 可达数 | 3000 |
| 真测通过数 | 609 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22680 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 36.3 |
| geo | 1.6 |
| probe | 89.4 |
| real_test | 127.0 |
| tcp | 37.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 27 | 27 | 0 | 100.0% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 165 | 156 | 9 | 94.5% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 50 | 43 | 7 | 86.0% |
| vless | 456 | 370 | 86 | 81.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 22 |
| geo:ClientOSError | 21 |
| 204:TimeoutError | 16 |
| cn-block:ClientOSError | 12 |
| speed:ClientOSError | 10 |
| 204:ProxyError | 7 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| geo:TimeoutError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5011 |
| ConnectionRefusedError | 903 |
| gaierror | 442 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | prefer | 399 | 0.915 | 1685 |
| zhangkai | 0.96 | prefer | 20 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.833 | prefer | 148 | 0.757 | 7365 |
| mheidari-all | 0.828 | prefer | 129 | 0.752 | 16245 |
| DeltaKronecker-all | 0.593 | observe | 7 | 1.0 | 6212 |
| tg-oneclickvpnkeys | 0.518 | observe | 7 | 1.0 | 118 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| Epodonios-all | 0.255 | observe | 0 | None | 7776 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8453 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.752 | 97 | 32 | 129 |
| Surfboard-tg-mixed | 0.757 | 112 | 36 | 148 |
| Au1rxx-base64 | 0.915 | 365 | 34 | 399 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 7 | 0 | 7 |
| DeltaKronecker-all | 1.0 | 7 | 0 | 7 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16245 | yes | 5.18 | 0 |
| SoliSpirit-all | 8453 | yes | 3.05 | 0 |
| Epodonios-all | 7776 | yes | 0.29 | 0 |
| Surfboard-tg-mixed | 7365 | yes | 4.38 | 0 |
| barry-far-vless | 6414 | yes | 2.11 | 0 |
| DeltaKronecker-all | 6212 | yes | 5.37 | 0 |
| Surfboard-tg-vless | 6206 | yes | 3.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 4887 | yes | 2.39 | 0 |
| mahdibland-V2RayAggregator | 4095 | yes | 3.13 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.46 | 0 |

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
| cn-block | 37 |
| 204 | 26 |
| geo | 23 |
| speed | 18 |
