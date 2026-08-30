# AutoNodes 每日报告

生成时间：2026-08-30 20:54:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79345 |
| 去重后节点数 | 21873 |
| TCP 可达数 | 3000 |
| 真测通过数 | 594 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21873 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 36.8 |
| geo | 1.5 |
| probe | 52.3 |
| real_test | 128.9 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 145 | 132 | 13 | 91.0% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 24 | 20 | 4 | 83.3% |
| vless | 478 | 400 | 78 | 83.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 26 |
| cn-block:TimeoutError | 24 |
| geo:ClientOSError | 13 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 6 |
| speed:TimeoutError | 4 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4736 |
| ConnectionRefusedError | 881 |
| gaierror | 392 |
| OSError | 25 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 335 | 0.949 | 1804 |
| zhangkai | 0.89 | prefer | 24 | 0.917 | 144 |
| Surfboard-tg-mixed | 0.864 | prefer | 174 | 0.787 | 6963 |
| DeltaKronecker-all | 0.795 | prefer | 149 | 0.718 | 5576 |
| mheidari-all | 0.699 | observe | 10 | 1.0 | 14482 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4762 |
| Epodonios-all | 0.255 | observe | 0 | None | 7411 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7545 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5857 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.718 | 107 | 42 | 149 |
| Surfboard-tg-mixed | 0.787 | 137 | 37 | 174 |
| zhangkai | 0.917 | 22 | 2 | 24 |
| Au1rxx-base64 | 0.949 | 318 | 17 | 335 |
| mheidari-all | 1.0 | 10 | 0 | 10 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14482 | yes | 4.46 | 0 |
| SoliSpirit-all | 7545 | yes | 3.88 | 0 |
| Epodonios-all | 7411 | yes | 4.72 | 0 |
| Surfboard-tg-mixed | 6963 | yes | 3.31 | 0 |
| barry-far-vless | 6057 | yes | 2.34 | 0 |
| Surfboard-tg-vless | 5857 | yes | 4.12 | 0 |
| DeltaKronecker-all | 5576 | yes | 4.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 4762 | yes | 2.14 | 0 |
| mahdibland-V2RayAggregator | 4041 | yes | 0.14 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.45 | 0 |

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
| 204 | 40 |
| cn-block | 30 |
| geo | 18 |
| speed | 12 |
