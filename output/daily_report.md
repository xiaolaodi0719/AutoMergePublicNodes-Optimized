# AutoNodes 每日报告

生成时间：2026-10-22 21:30:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96212 |
| 去重后节点数 | 26679 |
| TCP 可达数 | 3000 |
| 真测通过数 | 192 |
| verified 输出数 | 192 |
| global 输出数 | 196 |
| all 输出数 | 26679 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 77.2 |
| geo | 1.7 |
| probe | 233.6 |
| real_test | 106.8 |
| tcp | 44.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 37 | 11 | 26 | 29.7% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 135 | 127 | 8 | 94.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 31 | 27 | 4 | 87.1% |
| vless | 41 | 17 | 24 | 41.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyConnectionError | 16 |
| 204:ProxyError | 12 |
| geo:ClientOSError | 8 |
| cn-block:TimeoutError | 7 |
| 204:TimeoutError | 6 |
| speed:TimeoutError | 5 |
| geo:TimeoutError | 5 |
| speed:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6504 |
| ConnectionRefusedError | 1052 |
| gaierror | 278 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 95 | 0.968 | 1575 |
| mheidari-all | 0.941 | prefer | 34 | 0.882 | 23896 |
| Surfboard-tg-mixed | 0.755 | prefer | 78 | 0.679 | 7066 |
| DeltaKronecker-all | 0.461 | observe | 11 | 0.545 | 3641 |
| ermaozi | 0.331 | observe | 37 | 0.297 | 573 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 7550 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10026 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5426 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.297 | 11 | 26 | 37 |
| DeltaKronecker-all | 0.545 | 6 | 5 | 11 |
| Surfboard-tg-mixed | 0.679 | 53 | 25 | 78 |
| mheidari-all | 0.882 | 30 | 4 | 34 |
| Au1rxx-base64 | 0.968 | 92 | 3 | 95 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23896 | yes | 5.47 | 0 |
| SoliSpirit-all | 10026 | yes | 5.75 | 0 |
| Epodonios-all | 7550 | yes | 5.75 | 0 |
| Surfboard-tg-mixed | 7066 | yes | 3.84 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.8 | 0 |
| barry-far-vless | 5640 | yes | 2.58 | 0 |
| Surfboard-tg-vless | 5426 | yes | 4.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 3.08 | 0 |
| mahdibland-V2RayAggregator | 4176 | yes | 3.16 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.09 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 34 |
| geo | 14 |
| cn-block | 9 |
| speed | 7 |
