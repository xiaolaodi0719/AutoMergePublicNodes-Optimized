# AutoNodes 每日报告

生成时间：2026-10-14 11:42:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98051 |
| 去重后节点数 | 27189 |
| TCP 可达数 | 3000 |
| 真测通过数 | 316 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27189 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 81.7 |
| geo | 1.5 |
| probe | 271.4 |
| real_test | 257.9 |
| tcp | 47.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 39 | 13 | 26 | 33.3% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 111 | 93 | 18 | 83.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 41 | 35 | 6 | 85.4% |
| vless | 230 | 161 | 69 | 70.0% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 24 |
| 204:ProxyError | 22 |
| geo:ClientOSError | 13 |
| speed:ClientOSError | 10 |
| 204:ProxyConnectionError | 8 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6651 |
| ConnectionRefusedError | 1047 |
| gaierror | 358 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.883 | prefer | 258 | 0.814 | 1786 |
| mheidari-all | 0.819 | prefer | 44 | 0.75 | 23983 |
| Surfboard-tg-mixed | 0.724 | prefer | 88 | 0.648 | 7056 |
| ermaozi-get_subscribe | 0.366 | observe | 36 | 0.333 | 598 |
| zhangkai | 0.278 | observe | 6 | 0.5 | 144 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7542 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9834 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5579 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| ermaozi-get_subscribe | 0.333 | 12 | 24 | 36 |
| zhangkai | 0.5 | 3 | 3 | 6 |
| Surfboard-tg-mixed | 0.648 | 57 | 31 | 88 |
| mheidari-all | 0.75 | 33 | 11 | 44 |
| Au1rxx-base64 | 0.814 | 210 | 48 | 258 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23983 | yes | 6.3 | 0 |
| SoliSpirit-all | 9834 | yes | 3.87 | 0 |
| Epodonios-all | 7542 | yes | 6.5 | 0 |
| Surfboard-tg-mixed | 7056 | yes | 4.56 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.91 | 0 |
| barry-far-vless | 5831 | yes | 0.63 | 0 |
| Surfboard-tg-vless | 5579 | yes | 4.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 1.11 | 0 |
| DeltaKronecker-all | 4803 | yes | 5.96 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 1.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 60 |
| cn-block | 31 |
| speed | 17 |
| geo | 14 |
