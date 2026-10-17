# AutoNodes 每日报告

生成时间：2026-10-17 04:01:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99741 |
| 去重后节点数 | 27742 |
| TCP 可达数 | 3000 |
| 真测通过数 | 550 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27742 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 84.9 |
| geo | 1.5 |
| probe | 284.6 |
| real_test | 345.9 |
| tcp | 49.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 51 | 20 | 31 | 39.2% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 173 | 164 | 9 | 94.8% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 58 | 50 | 8 | 86.2% |
| vless | 453 | 292 | 161 | 64.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 64 |
| 204:ProxyError | 44 |
| geo:ClientOSError | 27 |
| speed:ClientOSError | 23 |
| speed:TimeoutError | 21 |
| cn-block:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| 204:TimeoutError | 5 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7046 |
| ConnectionRefusedError | 1041 |
| gaierror | 242 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | prefer | 524 | 0.876 | 1993 |
| Surfboard-tg-mixed | 0.689 | observe | 67 | 0.612 | 7128 |
| ermaozi | 0.439 | observe | 54 | 0.407 | 702 |
| DeltaKronecker-all | 0.384 | observe | 21 | 0.286 | 4946 |
| ermaozi-get_subscribe | 0.335 | observe | 2 | 1.0 | 601 |
| mheidari-all | 0.306 | observe | 91 | 0.22 | 24092 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1993 |
| Epodonios-all | 0.255 | observe | 0 | None | 7692 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.22 | 20 | 71 | 91 |
| DeltaKronecker-all | 0.286 | 6 | 15 | 21 |
| ermaozi | 0.407 | 22 | 32 | 54 |
| Surfboard-tg-mixed | 0.612 | 41 | 26 | 67 |
| Au1rxx-base64 | 0.876 | 459 | 65 | 524 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24092 | yes | 7.31 | 0 |
| SoliSpirit-all | 10039 | yes | 3.97 | 0 |
| Epodonios-all | 7692 | yes | 6.54 | 0 |
| Surfboard-tg-mixed | 7128 | yes | 5.77 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.78 | 0 |
| barry-far-vless | 5847 | yes | 3.3 | 0 |
| Surfboard-tg-vless | 5602 | yes | 5.22 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 2.13 | 0 |
| DeltaKronecker-all | 4946 | yes | 7.2 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 3.91 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 92 |
| 204 | 57 |
| speed | 45 |
| cn-block | 17 |
