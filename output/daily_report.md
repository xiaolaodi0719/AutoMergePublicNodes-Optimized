# AutoNodes 每日报告

生成时间：2026-09-10 11:11:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 91201 |
| 去重后节点数 | 24193 |
| TCP 可达数 | 3000 |
| 真测通过数 | 467 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24193 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 86.0 |
| geo | 1.7 |
| probe | 336.1 |
| real_test | 295.1 |
| tcp | 41.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 54 | 40 | 14 | 74.1% |
| hysteria2 | 22 | 19 | 3 | 86.4% |
| shadowsocks | 151 | 135 | 16 | 89.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 33 | 21 | 12 | 63.6% |
| vless | 389 | 247 | 142 | 63.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 57 |
| 204:TimeoutError | 38 |
| 204:ProxyError | 23 |
| cn-block:ClientOSError | 23 |
| cn-block:TimeoutError | 14 |
| geo:TimeoutError | 12 |
| 204:ClientOSError | 7 |
| speed:ClientOSError | 6 |
| speed:TimeoutError | 5 |
| cn-block:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5769 |
| ConnectionRefusedError | 932 |
| gaierror | 365 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.948 | prefer | 263 | 0.886 | 1628 |
| Surfboard-tg-mixed | 0.815 | prefer | 164 | 0.738 | 7439 |
| ermaozi | 0.75 | prefer | 54 | 0.741 | 449 |
| mheidari-all | 0.522 | observe | 161 | 0.441 | 19290 |
| ermaozi-get_subscribe | 0.274 | observe | 1 | 1.0 | 469 |
| tg-oneclickvpnkeys | 0.264 | observe | 1 | 1.0 | 214 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7808 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8703 |

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
| downweight | DeltaKronecker-all | 0.134 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 11 | 11 |
| mheidari-all | 0.441 | 71 | 90 | 161 |
| Surfboard-tg-mixed | 0.738 | 121 | 43 | 164 |
| ermaozi | 0.741 | 40 | 14 | 54 |
| Au1rxx-base64 | 0.886 | 233 | 30 | 263 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19290 | yes | 6.01 | 0 |
| SoliSpirit-all | 8703 | yes | 2.16 | 0 |
| Epodonios-all | 7808 | yes | 3.65 | 0 |
| Surfboard-tg-mixed | 7439 | yes | 4.73 | 0 |
| barry-far-vless | 6215 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 6025 | yes | 4.48 | 0 |
| DeltaKronecker-all | 5853 | yes | 6.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 1.74 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 0.49 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.82 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 69 |
| geo | 69 |
| cn-block | 39 |
| speed | 12 |
