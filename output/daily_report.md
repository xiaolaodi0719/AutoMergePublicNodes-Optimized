# AutoNodes 每日报告

生成时间：2026-09-25 17:04:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 97420 |
| 去重后节点数 | 26475 |
| TCP 可达数 | 3000 |
| 真测通过数 | 379 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26475 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 82.7 |
| geo | 1.4 |
| probe | 231.3 |
| real_test | 168.6 |
| tcp | 43.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 10 | 14 | 41.7% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 151 | 132 | 19 | 87.4% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 1 | 0 | 1 | 0.0% |
| vless | 314 | 219 | 95 | 69.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 42 |
| 204:TimeoutError | 29 |
| 204:ProxyError | 24 |
| cn-block:TimeoutError | 16 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6248 |
| ConnectionRefusedError | 957 |
| gaierror | 353 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.959 | prefer | 263 | 0.894 | 1699 |
| Surfboard-tg-mixed | 0.784 | prefer | 52 | 0.712 | 7258 |
| DeltaKronecker-all | 0.629 | observe | 8 | 1.0 | 5452 |
| mheidari-all | 0.623 | observe | 160 | 0.544 | 22782 |
| ermaozi | 0.473 | observe | 19 | 0.474 | 304 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 67 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7757 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| downweight | ermaozi-get_subscribe | 0.149 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.167 | 1 | 5 | 6 |
| ermaozi | 0.474 | 9 | 10 | 19 |
| mheidari-all | 0.544 | 87 | 73 | 160 |
| Surfboard-tg-mixed | 0.712 | 37 | 15 | 52 |
| Au1rxx-base64 | 0.894 | 235 | 28 | 263 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22782 | yes | 4.19 | 0 |
| SoliSpirit-all | 9237 | yes | 2.94 | 0 |
| Epodonios-all | 7757 | yes | 2.01 | 0 |
| Surfboard-tg-mixed | 7258 | yes | 3.31 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.87 | 0 |
| barry-far-vless | 6083 | yes | 2.25 | 0 |
| Surfboard-tg-vless | 5857 | yes | 2.31 | 0 |
| DeltaKronecker-all | 5452 | yes | 2.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 1.29 | 0 |
| mahdibland-V2RayAggregator | 4324 | yes | 1.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| trojan | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 59 |
| 204 | 58 |
| speed | 9 |
| geo | 7 |
