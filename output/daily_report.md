# AutoNodes 每日报告

生成时间：2026-09-18 04:19:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84088 |
| 去重后节点数 | 23179 |
| TCP 可达数 | 3000 |
| 真测通过数 | 657 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23179 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 26.0 |
| geo | 1.4 |
| probe | 357.1 |
| real_test | 553.1 |
| tcp | 38.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 29 | 18 | 11 | 62.1% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 182 | 177 | 5 | 97.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 74 | 52 | 22 | 70.3% |
| vless | 828 | 388 | 440 | 46.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 221 |
| speed:ClientOSError | 81 |
| geo:ClientOSError | 73 |
| speed:TimeoutError | 39 |
| cn-block:TimeoutError | 18 |
| 204:ProxyError | 15 |
| cn-block:ClientOSError | 13 |
| 204:TimeoutError | 11 |
| 204:ProxyConnectionError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5235 |
| ConnectionRefusedError | 839 |
| gaierror | 381 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.931 | prefer | 289 | 0.869 | 1618 |
| mheidari-all | 0.801 | prefer | 41 | 0.732 | 15863 |
| Surfboard-tg-mixed | 0.731 | prefer | 250 | 0.652 | 7282 |
| ermaozi | 0.636 | observe | 27 | 0.63 | 378 |
| DeltaKronecker-all | 0.451 | observe | 518 | 0.371 | 5931 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4261 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| ermaozi-get_subscribe | 0.256 | observe | 4 | 0.5 | 402 |
| Epodonios-all | 0.255 | observe | 0 | None | 7966 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| Pawdroid | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.371 | 192 | 326 | 518 |
| ermaozi-get_subscribe | 0.5 | 2 | 2 | 4 |
| ermaozi | 0.63 | 17 | 10 | 27 |
| Surfboard-tg-mixed | 0.652 | 163 | 87 | 250 |
| mheidari-all | 0.732 | 30 | 11 | 41 |
| Au1rxx-base64 | 0.869 | 251 | 38 | 289 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15863 | yes | 5.82 | 0 |
| SoliSpirit-all | 9011 | yes | 2.67 | 0 |
| Epodonios-all | 7966 | yes | 2.56 | 0 |
| Surfboard-tg-mixed | 7282 | yes | 3.75 | 0 |
| barry-far-vless | 6180 | yes | 1.68 | 0 |
| DeltaKronecker-all | 5931 | yes | 5.03 | 0 |
| Surfboard-tg-vless | 5769 | yes | 4.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 2.02 | 0 |
| mahdibland-V2RayAggregator | 4261 | yes | 0.32 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.77 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 294 |
| speed | 120 |
| 204 | 34 |
| cn-block | 32 |
