# AutoNodes 每日报告

生成时间：2026-10-01 22:40:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 98426 |
| 去重后节点数 | 27512 |
| TCP 可达数 | 3000 |
| 真测通过数 | 391 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27512 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 85.0 |
| geo | 1.5 |
| probe | 253.5 |
| real_test | 161.7 |
| tcp | 46.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 19 | 3 | 86.4% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 164 | 148 | 16 | 90.2% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 18 | 15 | 3 | 83.3% |
| vless | 227 | 188 | 39 | 82.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 12 |
| speed:TimeoutError | 11 |
| 204:TimeoutError | 10 |
| 204:ProxyConnectionError | 7 |
| cn-block:ClientOSError | 6 |
| speed:ClientOSError | 4 |
| 204:ProxyError | 4 |
| geo:TimeoutError | 4 |
| geo:ClientOSError | 2 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6223 |
| ConnectionRefusedError | 1045 |
| gaierror | 387 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.955 | prefer | 94 | 0.883 | 22987 |
| Au1rxx-base64 | 0.954 | prefer | 276 | 0.884 | 1818 |
| zhangkai | 0.839 | prefer | 22 | 0.864 | 144 |
| Surfboard-tg-mixed | 0.821 | prefer | 52 | 0.75 | 7183 |
| DeltaKronecker-all | 0.352 | observe | 6 | 0.5 | 5603 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| ermaozi-get_subscribe | 0.275 | observe | 1 | 1.0 | 512 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5324 |
| Epodonios-all | 0.255 | observe | 0 | None | 7711 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 3 | 3 | 6 |
| Surfboard-tg-mixed | 0.75 | 39 | 13 | 52 |
| zhangkai | 0.864 | 19 | 3 | 22 |
| mheidari-all | 0.883 | 83 | 11 | 94 |
| Au1rxx-base64 | 0.884 | 244 | 32 | 276 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22987 | yes | 7.58 | 0 |
| SoliSpirit-all | 9539 | yes | 2.08 | 0 |
| Epodonios-all | 7711 | yes | 3.93 | 0 |
| Surfboard-tg-mixed | 7183 | yes | 5.1 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.77 | 0 |
| barry-far-vless | 6097 | yes | 0.87 | 0 |
| Surfboard-tg-vless | 5811 | yes | 4.7 | 0 |
| DeltaKronecker-all | 5603 | yes | 6.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 1.12 | 0 |
| mahdibland-V2RayAggregator | 4310 | yes | 3.45 | 0 |

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
| 204 | 22 |
| cn-block | 18 |
| speed | 17 |
| geo | 6 |
