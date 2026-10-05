# AutoNodes 每日报告

生成时间：2026-10-05 05:11:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 98824 |
| 去重后节点数 | 27507 |
| TCP 可达数 | 3000 |
| 真测通过数 | 535 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27507 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 34.8 |
| geo | 1.4 |
| probe | 287.5 |
| real_test | 445.0 |
| tcp | 47.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 3 | 3 | 50.0% |
| http | 63 | 38 | 25 | 60.3% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 111 | 108 | 3 | 97.3% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 97 | 88 | 9 | 90.7% |
| vless | 587 | 276 | 311 | 47.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 146 |
| speed:TimeoutError | 77 |
| 204:ProxyError | 43 |
| geo:ClientOSError | 40 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 13 |
| speed:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6704 |
| ConnectionRefusedError | 1003 |
| gaierror | 369 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | prefer | 364 | 0.893 | 1883 |
| ermaozi | 0.622 | observe | 62 | 0.597 | 694 |
| Surfboard-tg-mixed | 0.471 | observe | 21 | 0.381 | 7178 |
| mheidari-all | 0.459 | observe | 425 | 0.379 | 23195 |
| 10ium-ScrapeCategorize-Vless | 0.287 | observe | 2 | 0.5 | 5173 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 68 |
| Epodonios-all | 0.255 | observe | 0 | None | 7673 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9258 |

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
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| mheidari-all | 0.379 | 161 | 264 | 425 |
| Surfboard-tg-mixed | 0.381 | 8 | 13 | 21 |
| 10ium-ScrapeCategorize-Vless | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.597 | 37 | 25 | 62 |
| Au1rxx-base64 | 0.893 | 325 | 39 | 364 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23195 | yes | 3.79 | 0 |
| SoliSpirit-all | 9258 | yes | 1.65 | 0 |
| Epodonios-all | 7673 | yes | 1.97 | 0 |
| Surfboard-tg-mixed | 7178 | yes | 2.71 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.19 | 0 |
| barry-far-vless | 6057 | yes | 0.69 | 0 |
| Surfboard-tg-vless | 5736 | yes | 2.6 | 0 |
| DeltaKronecker-all | 5267 | yes | 2.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 5173 | yes | 0.58 | 0 |
| mahdibland-V2RayAggregator | 4365 | yes | 2.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 186 |
| speed | 85 |
| 204 | 61 |
| cn-block | 22 |
