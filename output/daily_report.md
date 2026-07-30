# AutoNodes 每日报告

生成时间：2026-07-30 08:40:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78173 |
| 去重后节点数 | 22773 |
| TCP 可达数 | 3000 |
| 真测通过数 | 541 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22773 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 45.0 |
| geo | 1.3 |
| probe | 57.8 |
| real_test | 130.9 |
| tcp | 31.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 118 | 118 | 0 | 100.0% |
| hysteria2 | 16 | 11 | 5 | 68.8% |
| shadowsocks | 214 | 179 | 35 | 83.6% |
| socks | 8 | 5 | 3 | 62.5% |
| trojan | 63 | 58 | 5 | 92.1% |
| vless | 406 | 169 | 237 | 41.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 126 |
| geo:ClientOSError | 38 |
| cn-block:TimeoutError | 28 |
| speed:ClientOSError | 24 |
| speed:TimeoutError | 23 |
| 204:TimeoutError | 22 |
| 204:ProxyError | 10 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4385 |
| ConnectionRefusedError | 717 |
| gaierror | 281 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.998 | prefer | 118 | 1.0 | 157 |
| Au1rxx-base64 | 0.892 | prefer | 261 | 0.847 | 1201 |
| Surfboard-tg-mixed | 0.667 | observe | 165 | 0.588 | 5473 |
| mheidari-all | 0.543 | observe | 13 | 0.615 | 16105 |
| DeltaKronecker-all | 0.446 | observe | 260 | 0.365 | 5759 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6219 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6833 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.365 | 95 | 165 | 260 |
| Surfboard-tg-mixed | 0.588 | 97 | 68 | 165 |
| mheidari-all | 0.615 | 8 | 5 | 13 |
| Au1rxx-base64 | 0.847 | 221 | 40 | 261 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16105 | yes | 4.53 | 0 |
| SoliSpirit-all | 6833 | yes | 2.0 | 0 |
| Epodonios-all | 6219 | yes | 2.26 | 0 |
| DeltaKronecker-all | 5759 | yes | 3.72 | 0 |
| Surfboard-tg-mixed | 5473 | yes | 2.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 5342 | yes | 0.97 | 0 |
| mahdibland-V2RayAggregator | 5029 | yes | 2.33 | 0 |
| barry-far-vless | 4657 | yes | 1.75 | 0 |
| Surfboard-tg-vless | 4282 | yes | 2.46 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 165 |
| speed | 49 |
| 204 | 37 |
| cn-block | 34 |
