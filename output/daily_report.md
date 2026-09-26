# AutoNodes 每日报告

生成时间：2026-09-26 04:40:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 96567 |
| 去重后节点数 | 26483 |
| TCP 可达数 | 3000 |
| 真测通过数 | 477 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26483 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 74.2 |
| geo | 1.4 |
| probe | 370.1 |
| real_test | 530.5 |
| tcp | 44.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 43 | 14 | 29 | 32.6% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 134 | 126 | 8 | 94.0% |
| socks | 10 | 7 | 3 | 70.0% |
| trojan | 21 | 11 | 10 | 52.4% |
| vless | 770 | 304 | 466 | 39.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 213 |
| speed:TimeoutError | 109 |
| geo:ClientOSError | 53 |
| 204:ProxyError | 42 |
| cn-block:ClientOSError | 32 |
| speed:ClientOSError | 26 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 9 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 2 |
| speed:ClientPayloadError | 2 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6326 |
| ConnectionRefusedError | 932 |
| gaierror | 309 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.952 | prefer | 266 | 0.891 | 1594 |
| Surfboard-tg-mixed | 0.489 | observe | 9 | 0.667 | 7217 |
| ermaozi | 0.414 | observe | 33 | 0.394 | 352 |
| mheidari-all | 0.412 | observe | 619 | 0.331 | 22526 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| DeltaKronecker-all | 0.32 | observe | 48 | 0.229 | 5452 |
| ermaozi-get_subscribe | 0.267 | observe | 14 | 0.286 | 375 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7682 |
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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.229 | 11 | 37 | 48 |
| ermaozi-get_subscribe | 0.286 | 4 | 10 | 14 |
| mheidari-all | 0.331 | 205 | 414 | 619 |
| ermaozi | 0.394 | 13 | 20 | 33 |
| Surfboard-tg-mixed | 0.667 | 6 | 3 | 9 |
| Au1rxx-base64 | 0.891 | 237 | 29 | 266 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22526 | yes | 4.13 | 0 |
| SoliSpirit-all | 8923 | yes | 2.08 | 0 |
| Epodonios-all | 7682 | yes | 3.38 | 0 |
| Surfboard-tg-mixed | 7217 | yes | 2.91 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.61 | 0 |
| barry-far-vless | 6063 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 5837 | yes | 2.27 | 0 |
| DeltaKronecker-all | 5452 | yes | 3.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 0.86 | 0 |
| mahdibland-V2RayAggregator | 4304 | yes | 1.23 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 266 |
| speed | 137 |
| 204 | 70 |
| cn-block | 43 |
