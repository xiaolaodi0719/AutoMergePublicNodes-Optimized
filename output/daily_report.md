# AutoNodes 每日报告

生成时间：2026-07-28 02:58:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84821 |
| 去重后节点数 | 23210 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1018 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23210 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 18.4 |
| geo | 1.3 |
| probe | 68.6 |
| real_test | 219.9 |
| tcp | 32.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 59 | 59 | 0 | 100.0% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 168 | 161 | 7 | 95.8% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 576 | 547 | 29 | 95.0% |
| vless | 599 | 234 | 365 | 39.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 162 |
| speed:ClientOSError | 109 |
| speed:TimeoutError | 48 |
| cn-block:TimeoutError | 37 |
| geo:ClientOSError | 30 |
| 204:ProxyError | 7 |
| 204:TimeoutError | 6 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4246 |
| ConnectionRefusedError | 751 |
| gaierror | 318 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 477 | 0.96 | 1387 |
| zhangkai | 0.987 | prefer | 59 | 1.0 | 74 |
| Surfboard-tg-mixed | 0.782 | prefer | 55 | 0.709 | 5636 |
| mheidari-all | 0.64 | observe | 650 | 0.56 | 18500 |
| DeltaKronecker-all | 0.635 | observe | 171 | 0.556 | 5643 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3959 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4831 |
| Epodonios-all | 0.255 | observe | 0 | None | 6592 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.556 | 95 | 76 | 171 |
| mheidari-all | 0.56 | 364 | 286 | 650 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.709 | 39 | 16 | 55 |
| Au1rxx-base64 | 0.96 | 458 | 19 | 477 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 59 | 0 | 59 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18500 | yes | 3.73 | 0 |
| Epodonios-all | 6592 | yes | 1.74 | 0 |
| SoliSpirit-all | 6500 | yes | 1.85 | 0 |
| DeltaKronecker-all | 5643 | yes | 4.11 | 0 |
| Surfboard-tg-mixed | 5636 | yes | 1.87 | 0 |
| barry-far-vless | 5025 | yes | 0.47 | 0 |
| mahdibland-V2RayAggregator | 4997 | yes | 1.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4831 | yes | 0.94 | 0 |
| Surfboard-tg-vless | 4515 | yes | 2.1 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 0.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 192 |
| speed | 157 |
| cn-block | 40 |
| 204 | 15 |
