# AutoNodes 每日报告

生成时间：2026-09-07 03:59:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 94333 |
| 去重后节点数 | 24798 |
| TCP 可达数 | 3000 |
| 真测通过数 | 579 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24798 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 43.6 |
| geo | 1.4 |
| probe | 89.7 |
| real_test | 145.9 |
| tcp | 42.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 2 | 2 | 50.0% |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 22 | 19 | 3 | 86.4% |
| shadowsocks | 181 | 171 | 10 | 94.5% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 75 | 47 | 28 | 62.7% |
| vless | 603 | 314 | 289 | 52.1% |
| vmess | 3 | 1 | 2 | 33.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 96 |
| cn-block:TimeoutError | 69 |
| geo:ClientOSError | 49 |
| speed:TimeoutError | 36 |
| cn-block:ClientOSError | 29 |
| 204:TimeoutError | 17 |
| speed:ClientOSError | 15 |
| 204:ProxyConnectionError | 13 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5426 |
| ConnectionRefusedError | 1007 |
| gaierror | 352 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 331 | 0.94 | 1835 |
| zhangkai | 0.926 | prefer | 23 | 0.957 | 144 |
| Surfboard-tg-mixed | 0.802 | prefer | 214 | 0.724 | 7284 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 5750 |
| mheidari-all | 0.344 | observe | 324 | 0.262 | 21249 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4791 |
| Epodonios-all | 0.255 | observe | 0 | None | 7766 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8622 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6082 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.231 | 14 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.143 | 2 | 12 | 14 |
| mheidari-all | 0.262 | 85 | 239 | 324 |
| tg-LonUp_M | 0.5 | 1 | 1 | 2 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.724 | 155 | 59 | 214 |
| Au1rxx-base64 | 0.94 | 311 | 20 | 331 |
| zhangkai | 0.957 | 22 | 1 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21249 | yes | 5.15 | 0 |
| SoliSpirit-all | 8622 | yes | 3.28 | 0 |
| Epodonios-all | 7766 | yes | 2.94 | 0 |
| Surfboard-tg-mixed | 7284 | yes | 3.82 | 0 |
| barry-far-vless | 6301 | yes | 2.77 | 0 |
| Surfboard-tg-vless | 6082 | yes | 4.21 | 0 |
| DeltaKronecker-all | 5856 | yes | 5.21 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 2.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4791 | yes | 2.0 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 2.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 147 |
| cn-block | 101 |
| speed | 51 |
| 204 | 37 |
