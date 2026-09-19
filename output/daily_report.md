# AutoNodes 每日报告

生成时间：2026-09-19 15:51:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 88522 |
| 去重后节点数 | 25250 |
| TCP 可达数 | 3000 |
| 真测通过数 | 526 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25250 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 79.0 |
| geo | 1.4 |
| probe | 218.1 |
| real_test | 224.2 |
| tcp | 41.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 26 | 23 | 3 | 88.5% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 123 | 114 | 9 | 92.7% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 15 | 9 | 6 | 60.0% |
| vless | 497 | 363 | 134 | 73.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 34 |
| geo:TimeoutError | 31 |
| speed:ClientOSError | 23 |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 17 |
| cn-block:ClientOSError | 12 |
| 204:ProxyError | 9 |
| speed:TimeoutError | 3 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5760 |
| ConnectionRefusedError | 890 |
| gaierror | 452 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.941 | prefer | 319 | 0.878 | 1651 |
| ermaozi | 0.895 | prefer | 24 | 0.917 | 250 |
| DeltaKronecker-all | 0.785 | prefer | 147 | 0.707 | 6421 |
| Surfboard-tg-mixed | 0.703 | prefer | 173 | 0.624 | 7296 |
| mheidari-all | 0.684 | observe | 14 | 0.786 | 19364 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5174 |
| Epodonios-all | 0.255 | observe | 0 | None | 7933 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9336 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.624 | 108 | 65 | 173 |
| DeltaKronecker-all | 0.707 | 104 | 43 | 147 |
| mheidari-all | 0.786 | 11 | 3 | 14 |
| Au1rxx-base64 | 0.878 | 280 | 39 | 319 |
| ermaozi | 0.917 | 22 | 2 | 24 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19364 | yes | 5.06 | 0 |
| SoliSpirit-all | 9336 | yes | 4.65 | 0 |
| Epodonios-all | 7933 | yes | 3.33 | 0 |
| Surfboard-tg-mixed | 7296 | yes | 3.7 | 0 |
| DeltaKronecker-all | 6421 | yes | 5.73 | 0 |
| barry-far-vless | 6222 | yes | 3.74 | 0 |
| Surfboard-tg-vless | 5900 | yes | 4.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 3.31 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 0.15 | 0 |
| MatinGhanbari-all-sub | 3995 | yes | 3.04 | 0 |

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
| geo | 66 |
| cn-block | 32 |
| 204 | 30 |
| speed | 27 |
