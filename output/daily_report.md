# AutoNodes 每日报告

生成时间：2026-10-14 17:04:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 98394 |
| 去重后节点数 | 27311 |
| TCP 可达数 | 3000 |
| 真测通过数 | 315 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27311 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 99.2 |
| geo | 1.5 |
| probe | 239.9 |
| real_test | 245.0 |
| tcp | 47.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 25 | 16 | 9 | 64.0% |
| hysteria2 | 7 | 6 | 1 | 85.7% |
| shadowsocks | 96 | 89 | 7 | 92.7% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 40 | 33 | 7 | 82.5% |
| vless | 233 | 169 | 64 | 72.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 20 |
| 204:ProxyError | 12 |
| 204:TimeoutError | 11 |
| speed:ClientOSError | 11 |
| geo:TimeoutError | 9 |
| 204:ProxyConnectionError | 8 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 4 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6775 |
| ConnectionRefusedError | 1045 |
| gaierror | 358 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.894 | prefer | 292 | 0.825 | 1780 |
| mheidari-all | 0.863 | prefer | 67 | 0.791 | 23968 |
| zhangkai | 0.827 | prefer | 16 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.361 | observe | 10 | 0.4 | 7210 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7543 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9997 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5726 |
| barry-far-vless | 0.255 | observe | 0 | None | 5831 |

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
| downweight | ermaozi-get_subscribe | 0.133 | 10 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.138 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 9 | 9 |
| ermaozi-get_subscribe | 0.1 | 1 | 9 | 10 |
| Surfboard-tg-mixed | 0.4 | 4 | 6 | 10 |
| mheidari-all | 0.791 | 53 | 14 | 67 |
| Au1rxx-base64 | 0.825 | 241 | 51 | 292 |
| zhangkai | 1.0 | 16 | 0 | 16 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23968 | yes | 6.88 | 0 |
| SoliSpirit-all | 9997 | yes | 4.95 | 0 |
| Epodonios-all | 7543 | yes | 7.65 | 0 |
| Surfboard-tg-mixed | 7210 | yes | 4.8 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.74 | 0 |
| barry-far-vless | 5831 | yes | 4.59 | 0 |
| Surfboard-tg-vless | 5726 | yes | 4.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 2.64 | 0 |
| DeltaKronecker-all | 4803 | yes | 7.22 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 1.48 | 0 |

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
| 204 | 35 |
| cn-block | 23 |
| speed | 18 |
| geo | 14 |
