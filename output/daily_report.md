# AutoNodes 每日报告

生成时间：2026-10-10 12:26:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 97803 |
| 去重后节点数 | 27173 |
| TCP 可达数 | 3000 |
| 真测通过数 | 499 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27173 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 77.0 |
| geo | 1.0 |
| probe | 315.1 |
| real_test | 368.5 |
| tcp | 46.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 161 | 139 | 22 | 86.3% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 150 | 140 | 10 | 93.3% |
| vless | 244 | 175 | 69 | 71.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 24 |
| speed:TimeoutError | 11 |
| geo:ClientOSError | 10 |
| speed:ClientOSError | 8 |
| 204:ClientOSError | 7 |
| geo:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6483 |
| ConnectionRefusedError | 1022 |
| gaierror | 420 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.958 | prefer | 365 | 0.888 | 1820 |
| DeltaKronecker-all | 0.847 | prefer | 28 | 0.786 | 5009 |
| mheidari-all | 0.846 | prefer | 45 | 0.778 | 23754 |
| Surfboard-tg-mixed | 0.744 | prefer | 135 | 0.667 | 7103 |
| ermaozi-get_subscribe | 0.426 | observe | 4 | 1.0 | 653 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7579 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| Surfboard-tg-mixed | 0.667 | 90 | 45 | 135 |
| mheidari-all | 0.778 | 35 | 10 | 45 |
| DeltaKronecker-all | 0.786 | 22 | 6 | 28 |
| Au1rxx-base64 | 0.888 | 324 | 41 | 365 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23754 | yes | 4.79 | 0 |
| SoliSpirit-all | 9335 | yes | 1.75 | 0 |
| Epodonios-all | 7579 | yes | 2.86 | 0 |
| Surfboard-tg-mixed | 7103 | yes | 4.05 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.36 | 0 |
| barry-far-vless | 5861 | yes | 0.7 | 0 |
| Surfboard-tg-vless | 5620 | yes | 3.37 | 0 |
| DeltaKronecker-all | 5009 | yes | 4.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 4999 | yes | 0.55 | 0 |
| mahdibland-V2RayAggregator | 4347 | yes | 2.61 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 35 |
| cn-block | 31 |
| speed | 20 |
| geo | 17 |
