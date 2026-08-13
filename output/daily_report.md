# AutoNodes 每日报告

生成时间：2026-08-13 07:47:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79301 |
| 去重后节点数 | 22373 |
| TCP 可达数 | 3000 |
| 真测通过数 | 733 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22373 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 12.3 |
| generate | 35.3 |
| geo | 1.2 |
| probe | 60.2 |
| real_test | 181.7 |
| tcp | 33.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 161 | 148 | 13 | 91.9% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 233 | 224 | 9 | 96.1% |
| vless | 338 | 212 | 126 | 62.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 45 |
| speed:TimeoutError | 26 |
| geo:ClientOSError | 17 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 17 |
| 204:ProxyError | 9 |
| 204:ClientOSError | 7 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4291 |
| ConnectionRefusedError | 781 |
| gaierror | 339 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 461 | 0.954 | 1501 |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.792 | prefer | 137 | 0.715 | 5801 |
| mheidari-all | 0.55 | observe | 113 | 0.469 | 16910 |
| DeltaKronecker-all | 0.405 | observe | 38 | 0.316 | 4975 |
| nscl5-all | 0.377 | observe | 2 | 1.0 | 1654 |
| Epodonios-all | 0.255 | observe | 0 | None | 6457 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7624 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4621 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.316 | 12 | 26 | 38 |
| mheidari-all | 0.469 | 53 | 60 | 113 |
| Surfboard-tg-mixed | 0.715 | 98 | 39 | 137 |
| Au1rxx-base64 | 0.954 | 440 | 21 | 461 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16910 | yes | 2.79 | 0 |
| SoliSpirit-all | 7624 | yes | 2.18 | 0 |
| Epodonios-all | 6457 | yes | 2.91 | 0 |
| Surfboard-tg-mixed | 5801 | yes | 2.16 | 0 |
| 10ium-ScrapeCategorize-Vless | 5203 | yes | 1.12 | 0 |
| mahdibland-V2RayAggregator | 5197 | yes | 2.26 | 0 |
| barry-far-vless | 4989 | yes | 1.52 | 0 |
| DeltaKronecker-all | 4975 | yes | 3.18 | 0 |
| Surfboard-tg-vless | 4621 | yes | 3.26 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.38 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 62 |
| 204 | 33 |
| speed | 33 |
| cn-block | 24 |
