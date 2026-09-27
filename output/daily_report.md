# AutoNodes 每日报告

生成时间：2026-09-27 04:55:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 95804 |
| 去重后节点数 | 26625 |
| TCP 可达数 | 3000 |
| 真测通过数 | 518 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26625 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 78.3 |
| geo | 1.5 |
| probe | 300.5 |
| real_test | 447.8 |
| tcp | 43.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 37 | 26 | 11 | 70.3% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 176 | 160 | 16 | 90.9% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 29 | 26 | 3 | 89.7% |
| vless | 647 | 292 | 355 | 45.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 173 |
| speed:TimeoutError | 71 |
| geo:ClientOSError | 52 |
| 204:TimeoutError | 22 |
| speed:ClientOSError | 21 |
| cn-block:ClientOSError | 20 |
| cn-block:TimeoutError | 11 |
| 204:ProxyError | 10 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6423 |
| ConnectionRefusedError | 946 |
| gaierror | 295 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.956 | prefer | 273 | 0.897 | 1536 |
| Surfboard-tg-mixed | 0.829 | prefer | 197 | 0.751 | 7113 |
| ermaozi | 0.69 | observe | 32 | 0.688 | 338 |
| ermaozi-get_subscribe | 0.423 | observe | 6 | 0.833 | 361 |
| DeltaKronecker-all | 0.407 | observe | 11 | 0.455 | 5512 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| mheidari-all | 0.321 | observe | 384 | 0.24 | 22408 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7583 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.24 | 92 | 292 | 384 |
| DeltaKronecker-all | 0.455 | 5 | 6 | 11 |
| ermaozi | 0.688 | 22 | 10 | 32 |
| Surfboard-tg-mixed | 0.751 | 148 | 49 | 197 |
| ermaozi-get_subscribe | 0.833 | 5 | 1 | 6 |
| Au1rxx-base64 | 0.897 | 245 | 28 | 273 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22408 | yes | 5.65 | 0 |
| SoliSpirit-all | 8902 | yes | 1.47 | 0 |
| Epodonios-all | 7583 | yes | 3.28 | 0 |
| Surfboard-tg-mixed | 7113 | yes | 6.14 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.1 | 0 |
| barry-far-vless | 5907 | yes | 1.16 | 0 |
| Surfboard-tg-vless | 5686 | yes | 3.8 | 0 |
| DeltaKronecker-all | 5512 | yes | 6.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 0.73 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 2.96 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 225 |
| speed | 92 |
| 204 | 37 |
| cn-block | 34 |
