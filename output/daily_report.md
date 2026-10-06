# AutoNodes 每日报告

生成时间：2026-10-06 00:02:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 98529 |
| 去重后节点数 | 27355 |
| TCP 可达数 | 3000 |
| 真测通过数 | 409 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27355 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 31.5 |
| geo | 1.5 |
| probe | 200.2 |
| real_test | 158.8 |
| tcp | 45.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 1 | 2 | 33.3% |
| http | 59 | 36 | 23 | 61.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 97 | 93 | 4 | 95.9% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 86 | 83 | 3 | 96.5% |
| vless | 209 | 176 | 33 | 84.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 26 |
| cn-block:TimeoutError | 13 |
| 204:TimeoutError | 7 |
| geo:ClientOSError | 6 |
| speed:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| cn-block:ClientOSError | 2 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6226 |
| ConnectionRefusedError | 1054 |
| gaierror | 474 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 295 | 0.929 | 1862 |
| mheidari-all | 0.91 | prefer | 104 | 0.837 | 23213 |
| ermaozi | 0.635 | observe | 59 | 0.61 | 701 |
| DeltaKronecker-all | 0.529 | observe | 7 | 0.857 | 5300 |
| Surfboard-tg-mixed | 0.4 | observe | 4 | 0.75 | 7145 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 177 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5111 |
| Epodonios-all | 0.255 | observe | 0 | None | 7624 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| tg-OutlineReleasedKey | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| ermaozi | 0.61 | 36 | 23 | 59 |
| Surfboard-tg-mixed | 0.75 | 3 | 1 | 4 |
| mheidari-all | 0.837 | 87 | 17 | 104 |
| DeltaKronecker-all | 0.857 | 6 | 1 | 7 |
| Au1rxx-base64 | 0.929 | 274 | 21 | 295 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23213 | yes | 7.01 | 0 |
| SoliSpirit-all | 9352 | yes | 1.83 | 0 |
| Epodonios-all | 7624 | yes | 3.98 | 0 |
| Surfboard-tg-mixed | 7145 | yes | 4.48 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.55 | 0 |
| barry-far-vless | 5871 | yes | 1.43 | 0 |
| Surfboard-tg-vless | 5642 | yes | 4.26 | 0 |
| DeltaKronecker-all | 5300 | yes | 5.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 5111 | yes | 1.16 | 0 |
| mahdibland-V2RayAggregator | 4375 | yes | 3.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 34 |
| cn-block | 16 |
| speed | 9 |
| geo | 8 |
