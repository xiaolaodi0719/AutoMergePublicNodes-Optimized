# AutoNodes 每日报告

生成时间：2026-08-08 07:05:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 82085 |
| 去重后节点数 | 23444 |
| TCP 可达数 | 3000 |
| 真测通过数 | 481 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23444 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 36.0 |
| geo | 1.5 |
| probe | 58.0 |
| real_test | 125.0 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 148 | 134 | 14 | 90.5% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 136 | 128 | 8 | 94.1% |
| vless | 323 | 170 | 153 | 52.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 59 |
| geo:ClientOSError | 32 |
| cn-block:TimeoutError | 20 |
| speed:ClientOSError | 16 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 13 |
| speed:TimeoutError | 12 |
| 204:ClientOSError | 10 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4724 |
| ConnectionRefusedError | 807 |
| gaierror | 344 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 350 | 0.949 | 1368 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.567 | observe | 111 | 0.486 | 6419 |
| mheidari-all | 0.535 | observe | 121 | 0.455 | 17696 |
| DeltaKronecker-all | 0.42 | observe | 51 | 0.333 | 5347 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 169 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5450 |
| Epodonios-all | 0.255 | observe | 0 | None | 6914 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.333 | 17 | 34 | 51 |
| mheidari-all | 0.455 | 55 | 66 | 121 |
| Surfboard-tg-mixed | 0.486 | 54 | 57 | 111 |
| Au1rxx-base64 | 0.949 | 332 | 18 | 350 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17696 | yes | 4.2 | 0 |
| SoliSpirit-all | 7402 | yes | 4.05 | 0 |
| Epodonios-all | 6914 | yes | 3.71 | 0 |
| Surfboard-tg-mixed | 6419 | yes | 3.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 5450 | yes | 2.57 | 0 |
| barry-far-vless | 5409 | yes | 2.34 | 0 |
| DeltaKronecker-all | 5347 | yes | 4.68 | 0 |
| Surfboard-tg-vless | 5218 | yes | 3.43 | 0 |
| mahdibland-V2RayAggregator | 5162 | yes | 0.2 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 91 |
| 204 | 36 |
| speed | 29 |
| cn-block | 22 |
