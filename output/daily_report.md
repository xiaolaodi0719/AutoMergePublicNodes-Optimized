# AutoNodes 每日报告

生成时间：2026-09-29 12:40:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96889 |
| 去重后节点数 | 26969 |
| TCP 可达数 | 3000 |
| 真测通过数 | 467 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26969 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 88.6 |
| geo | 1.5 |
| probe | 280.0 |
| real_test | 208.4 |
| tcp | 45.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 31 | 27 | 4 | 87.1% |
| hysteria2 | 23 | 23 | 0 | 100.0% |
| shadowsocks | 178 | 160 | 18 | 89.9% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 34 | 10 | 24 | 29.4% |
| vless | 343 | 243 | 100 | 70.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 41 |
| speed:ClientOSError | 29 |
| cn-block:TimeoutError | 22 |
| geo:TimeoutError | 18 |
| speed:TimeoutError | 10 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 7 |
| geo:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6543 |
| ConnectionRefusedError | 996 |
| gaierror | 316 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | prefer | 54 | 0.87 | 22883 |
| Au1rxx-base64 | 0.913 | prefer | 330 | 0.852 | 1598 |
| ermaozi | 0.822 | prefer | 35 | 0.829 | 291 |
| Surfboard-tg-mixed | 0.668 | observe | 134 | 0.59 | 7053 |
| DeltaKronecker-all | 0.58 | observe | 56 | 0.5 | 5528 |
| ermaozi-get_subscribe | 0.323 | observe | 2 | 1.0 | 293 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5314 |
| Epodonios-all | 0.255 | observe | 0 | None | 7502 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 28 | 28 | 56 |
| Surfboard-tg-mixed | 0.59 | 79 | 55 | 134 |
| ermaozi | 0.829 | 29 | 6 | 35 |
| Au1rxx-base64 | 0.852 | 281 | 49 | 330 |
| mheidari-all | 0.87 | 47 | 7 | 54 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22883 | yes | 4.34 | 0 |
| SoliSpirit-all | 9548 | yes | 2.31 | 0 |
| Epodonios-all | 7502 | yes | 3.35 | 0 |
| Surfboard-tg-mixed | 7053 | yes | 3.2 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.16 | 0 |
| barry-far-vless | 5869 | yes | 1.95 | 0 |
| Surfboard-tg-vless | 5690 | yes | 2.57 | 0 |
| DeltaKronecker-all | 5528 | yes | 4.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5314 | yes | 0.88 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 2.12 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 51 |
| speed | 41 |
| cn-block | 32 |
| geo | 24 |
