# AutoNodes 每日报告

生成时间：2026-10-11 05:23:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 97520 |
| 去重后节点数 | 27407 |
| TCP 可达数 | 3000 |
| 真测通过数 | 496 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27407 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 81.6 |
| geo | 1.5 |
| probe | 409.4 |
| real_test | 583.7 |
| tcp | 46.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 9 | 2 | 7 | 22.2% |
| http | 21 | 17 | 4 | 81.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 122 | 116 | 6 | 95.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 122 | 119 | 3 | 97.5% |
| vless | 518 | 218 | 300 | 42.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 141 |
| speed:TimeoutError | 60 |
| geo:ClientOSError | 37 |
| speed:ClientOSError | 31 |
| 204:ProxyError | 16 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 10 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 3 |
| speed:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6462 |
| ConnectionRefusedError | 1053 |
| gaierror | 414 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | prefer | 379 | 0.905 | 1799 |
| ermaozi-get_subscribe | 0.58 | observe | 25 | 0.56 | 610 |
| Surfboard-tg-mixed | 0.529 | observe | 7 | 0.857 | 7087 |
| zhangkai | 0.483 | observe | 6 | 1.0 | 144 |
| mheidari-all | 0.397 | observe | 392 | 0.316 | 23694 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4347 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 5009 |
| Epodonios-all | 0.255 | observe | 0 | None | 7576 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9365 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.316 | 124 | 268 | 392 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| ermaozi-get_subscribe | 0.56 | 14 | 11 | 25 |
| Surfboard-tg-mixed | 0.857 | 6 | 1 | 7 |
| Au1rxx-base64 | 0.905 | 343 | 36 | 379 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 6 | 0 | 6 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23694 | yes | 4.39 | 0 |
| SoliSpirit-all | 9365 | yes | 3.55 | 0 |
| Epodonios-all | 7576 | yes | 3.92 | 0 |
| Surfboard-tg-mixed | 7087 | yes | 2.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.03 | 0 |
| barry-far-vless | 5790 | yes | 3.12 | 0 |
| Surfboard-tg-vless | 5545 | yes | 3.73 | 0 |
| DeltaKronecker-all | 5009 | yes | 4.54 | 0 |
| 10ium-ScrapeCategorize-Vless | 4999 | yes | 1.66 | 0 |
| mahdibland-V2RayAggregator | 4347 | yes | 1.47 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 178 |
| speed | 93 |
| 204 | 32 |
| cn-block | 20 |
