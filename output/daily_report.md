# AutoNodes 每日报告

生成时间：2026-09-24 17:00:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97092 |
| 去重后节点数 | 26416 |
| TCP 可达数 | 3000 |
| 真测通过数 | 381 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26416 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 82.5 |
| geo | 1.5 |
| probe | 190.2 |
| real_test | 164.9 |
| tcp | 43.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 38 | 24 | 14 | 63.2% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 160 | 147 | 13 | 91.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 13 | 12 | 1 | 92.3% |
| vless | 212 | 175 | 37 | 82.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 16 |
| 204:TimeoutError | 15 |
| cn-block:ClientOSError | 11 |
| cn-block:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| speed:ClientOSError | 2 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6048 |
| ConnectionRefusedError | 985 |
| gaierror | 379 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | prefer | 252 | 0.933 | 1697 |
| Surfboard-tg-mixed | 0.875 | prefer | 76 | 0.803 | 7421 |
| mheidari-all | 0.8 | prefer | 73 | 0.726 | 22258 |
| ermaozi | 0.669 | observe | 33 | 0.667 | 298 |
| DeltaKronecker-all | 0.519 | observe | 5 | 1.0 | 5845 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5307 |
| Epodonios-all | 0.255 | observe | 0 | None | 7498 |
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
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| ermaozi-get_subscribe | 0.5 | 2 | 2 | 4 |
| ermaozi | 0.667 | 22 | 11 | 33 |
| mheidari-all | 0.726 | 53 | 20 | 73 |
| Surfboard-tg-mixed | 0.803 | 61 | 15 | 76 |
| Au1rxx-base64 | 0.933 | 235 | 17 | 252 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22258 | yes | 7.26 | 0 |
| SoliSpirit-all | 9120 | yes | 3.52 | 0 |
| Epodonios-all | 7498 | yes | 3.36 | 0 |
| Surfboard-tg-mixed | 7421 | yes | 6.26 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.39 | 0 |
| Surfboard-tg-vless | 5991 | yes | 4.31 | 0 |
| barry-far-vless | 5901 | yes | 0.9 | 0 |
| DeltaKronecker-all | 5845 | yes | 5.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 2.6 | 0 |
| mahdibland-V2RayAggregator | 4305 | yes | 1.21 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 36 |
| cn-block | 21 |
| speed | 6 |
| geo | 4 |
