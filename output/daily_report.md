# AutoNodes 每日报告

生成时间：2026-09-04 16:09:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84288 |
| 去重后节点数 | 23436 |
| TCP 可达数 | 3000 |
| 真测通过数 | 588 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23436 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 40.9 |
| geo | 1.4 |
| probe | 85.9 |
| real_test | 126.5 |
| tcp | 39.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 28 | 13 | 15 | 46.4% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 161 | 143 | 18 | 88.8% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 27 | 24 | 3 | 88.9% |
| vless | 473 | 391 | 82 | 82.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 26 |
| cn-block:TimeoutError | 23 |
| 204:ProxyConnectionError | 16 |
| geo:ClientOSError | 15 |
| cn-block:ClientOSError | 11 |
| speed:TimeoutError | 9 |
| 204:ProxyError | 7 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:ClientOSError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5605 |
| ConnectionRefusedError | 876 |
| gaierror | 208 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 359 | 0.919 | 1751 |
| Surfboard-tg-mixed | 0.856 | prefer | 159 | 0.78 | 7209 |
| mheidari-all | 0.85 | prefer | 137 | 0.774 | 15927 |
| DeltaKronecker-all | 0.732 | prefer | 21 | 0.667 | 7089 |
| zhangkai | 0.486 | observe | 23 | 0.478 | 144 |
| tg-oneclickvpnkeys | 0.277 | observe | 6 | 0.5 | 104 |
| Epodonios-all | 0.255 | observe | 0 | None | 7667 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8718 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6091 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| zhangkai | 0.478 | 11 | 12 | 23 |
| tg-oneclickvpnkeys | 0.5 | 3 | 3 | 6 |
| DeltaKronecker-all | 0.667 | 14 | 7 | 21 |
| mheidari-all | 0.774 | 106 | 31 | 137 |
| Surfboard-tg-mixed | 0.78 | 124 | 35 | 159 |
| Au1rxx-base64 | 0.919 | 330 | 29 | 359 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15927 | yes | 6.06 | 0 |
| SoliSpirit-all | 8718 | yes | 4.5 | 0 |
| Epodonios-all | 7667 | yes | 3.37 | 0 |
| Surfboard-tg-mixed | 7209 | yes | 4.64 | 0 |
| DeltaKronecker-all | 7089 | yes | 5.99 | 0 |
| barry-far-vless | 6339 | yes | 2.32 | 0 |
| Surfboard-tg-vless | 6091 | yes | 4.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 4810 | yes | 2.55 | 0 |
| mahdibland-V2RayAggregator | 4123 | yes | 3.04 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.93 | 0 |

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
| 204 | 51 |
| cn-block | 37 |
| geo | 20 |
| speed | 12 |
