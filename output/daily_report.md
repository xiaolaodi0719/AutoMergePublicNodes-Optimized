# AutoNodes 每日报告

生成时间：2026-08-26 13:05:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78650 |
| 去重后节点数 | 22225 |
| TCP 可达数 | 3000 |
| 真测通过数 | 487 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22225 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.8 |
| generate | 42.0 |
| geo | 1.5 |
| probe | 54.5 |
| real_test | 102.7 |
| tcp | 35.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 28 | 23 | 5 | 82.1% |
| shadowsocks | 169 | 153 | 16 | 90.5% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 34 | 28 | 6 | 82.4% |
| vless | 337 | 256 | 81 | 76.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 26 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 20 |
| speed:ClientOSError | 9 |
| geo:ClientOSError | 8 |
| geo:TimeoutError | 6 |
| 204:ClientOSError | 6 |
| 204:ProxyError | 5 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4685 |
| ConnectionRefusedError | 862 |
| gaierror | 417 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 38 | 0.947 | 14222 |
| Au1rxx-base64 | 0.948 | prefer | 325 | 0.871 | 1988 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| DeltaKronecker-all | 0.778 | prefer | 41 | 0.707 | 6107 |
| Surfboard-tg-mixed | 0.755 | prefer | 161 | 0.677 | 6535 |
| nscl5-all | 0.444 | observe | 6 | 0.833 | 887 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 206 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4825 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1992 |
| Epodonios-all | 0.255 | observe | 0 | None | 7011 |

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
| Surfboard-tg-mixed | 0.677 | 109 | 52 | 161 |
| DeltaKronecker-all | 0.707 | 29 | 12 | 41 |
| nscl5-all | 0.833 | 5 | 1 | 6 |
| Au1rxx-base64 | 0.871 | 283 | 42 | 325 |
| mheidari-all | 0.947 | 36 | 2 | 38 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14222 | yes | 5.33 | 0 |
| SoliSpirit-all | 7145 | yes | 3.53 | 0 |
| Epodonios-all | 7011 | yes | 1.66 | 0 |
| Surfboard-tg-mixed | 6535 | yes | 3.76 | 0 |
| DeltaKronecker-all | 6107 | yes | 5.11 | 0 |
| barry-far-vless | 5628 | yes | 2.84 | 0 |
| Surfboard-tg-vless | 5395 | yes | 4.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 4825 | yes | 3.18 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.92 | 0 |
| mahdibland-V2RayAggregator | 3981 | yes | 3.82 | 0 |

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
| speed | 36 |
| 204 | 33 |
| cn-block | 26 |
| geo | 16 |
