# AutoNodes 每日报告

生成时间：2026-08-13 13:27:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79794 |
| 去重后节点数 | 22452 |
| TCP 可达数 | 3000 |
| 真测通过数 | 781 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22452 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.3 |
| generate | 25.9 |
| geo | 1.1 |
| probe | 59.6 |
| real_test | 188.6 |
| tcp | 32.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 170 | 151 | 19 | 88.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 333 | 327 | 6 | 98.2% |
| vless | 221 | 154 | 67 | 69.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 17 |
| geo:TimeoutError | 15 |
| speed:TimeoutError | 10 |
| geo:ClientOSError | 9 |
| 204:ProxyError | 9 |
| speed:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4049 |
| ConnectionRefusedError | 760 |
| gaierror | 353 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 541 | 0.957 | 1591 |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.815 | prefer | 115 | 0.739 | 5967 |
| mheidari-all | 0.655 | observe | 78 | 0.577 | 17032 |
| DeltaKronecker-all | 0.291 | observe | 12 | 0.25 | 4878 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5203 |
| Epodonios-all | 0.255 | observe | 0 | None | 6610 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.25 | 3 | 9 | 12 |
| mheidari-all | 0.577 | 45 | 33 | 78 |
| Surfboard-tg-mixed | 0.739 | 85 | 30 | 115 |
| Au1rxx-base64 | 0.957 | 518 | 23 | 541 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17032 | yes | 4.31 | 0 |
| SoliSpirit-all | 7410 | yes | 3.51 | 0 |
| Epodonios-all | 6610 | yes | 2.73 | 0 |
| Surfboard-tg-mixed | 5967 | yes | 3.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 5203 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 5197 | yes | 2.55 | 0 |
| barry-far-vless | 5031 | yes | 1.07 | 0 |
| DeltaKronecker-all | 4878 | yes | 4.89 | 0 |
| Surfboard-tg-vless | 4695 | yes | 3.11 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.39 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 31 |
| cn-block | 25 |
| geo | 24 |
| speed | 16 |
