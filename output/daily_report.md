# AutoNodes 每日报告

生成时间：2026-07-31 09:00:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 77153 |
| 去重后节点数 | 22423 |
| TCP 可达数 | 3000 |
| 真测通过数 | 366 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22423 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 36.4 |
| geo | 1.3 |
| probe | 49.6 |
| real_test | 96.9 |
| tcp | 31.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 80 | 80 | 0 | 100.0% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 142 | 120 | 22 | 84.5% |
| socks | 10 | 6 | 4 | 60.0% |
| trojan | 39 | 31 | 8 | 79.5% |
| vless | 239 | 116 | 123 | 48.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 48 |
| 204:ProxyError | 21 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 14 |
| geo:ClientOSError | 13 |
| speed:TimeoutError | 13 |
| speed:ClientOSError | 11 |
| cn-block:ProxyError | 7 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4589 |
| ConnectionRefusedError | 751 |
| OSError | 221 |
| gaierror | 187 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 81 | 1.0 | 110 |
| Au1rxx-base64 | 0.865 | prefer | 190 | 0.816 | 1319 |
| Surfboard-tg-mixed | 0.62 | observe | 148 | 0.541 | 5242 |
| DeltaKronecker-all | 0.557 | observe | 86 | 0.477 | 5144 |
| mheidari-all | 0.474 | observe | 10 | 0.6 | 16339 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 45 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5507 |
| Epodonios-all | 0.255 | observe | 0 | None | 5918 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| nscl5-all | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.477 | 41 | 45 | 86 |
| Surfboard-tg-mixed | 0.541 | 80 | 68 | 148 |
| mheidari-all | 0.6 | 6 | 4 | 10 |
| Au1rxx-base64 | 0.816 | 155 | 35 | 190 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16339 | yes | 3.72 | 0 |
| SoliSpirit-all | 6473 | yes | 2.83 | 0 |
| Epodonios-all | 5918 | yes | 2.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 5507 | yes | 2.15 | 0 |
| Surfboard-tg-mixed | 5242 | yes | 2.57 | 0 |
| DeltaKronecker-all | 5144 | yes | 3.14 | 0 |
| mahdibland-V2RayAggregator | 5074 | yes | 1.63 | 0 |
| barry-far-vless | 4510 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 4146 | yes | 1.81 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 64 |
| 204 | 46 |
| speed | 25 |
| cn-block | 24 |
