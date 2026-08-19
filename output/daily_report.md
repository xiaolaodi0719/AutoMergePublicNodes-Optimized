# AutoNodes 每日报告

生成时间：2026-08-19 13:01:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82413 |
| 去重后节点数 | 22576 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1136 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22576 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 20.1 |
| generate | 26.0 |
| geo | 0.8 |
| probe | 63.5 |
| real_test | 201.0 |
| tcp | 35.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 110 | 109 | 1 | 99.1% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 140 | 127 | 13 | 90.7% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 710 | 705 | 5 | 99.3% |
| vless | 228 | 175 | 53 | 76.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 12 |
| 204:ProxyError | 9 |
| speed:TimeoutError | 8 |
| geo:TimeoutError | 7 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 5 |
| geo:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4626 |
| ConnectionRefusedError | 877 |
| gaierror | 487 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 614 | 0.976 | 1765 |
| mheidari-all | 0.989 | prefer | 315 | 0.911 | 16605 |
| zhangkai | 0.979 | prefer | 111 | 0.982 | 144 |
| Surfboard-tg-mixed | 0.917 | prefer | 158 | 0.842 | 6304 |
| DeltaKronecker-all | 0.418 | observe | 10 | 0.5 | 6390 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3330 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5067 |
| Epodonios-all | 0.255 | observe | 0 | None | 7081 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 5 | 5 | 10 |
| Surfboard-tg-mixed | 0.842 | 133 | 25 | 158 |
| mheidari-all | 0.911 | 287 | 28 | 315 |
| Au1rxx-base64 | 0.976 | 599 | 15 | 614 |
| zhangkai | 0.982 | 109 | 2 | 111 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16605 | yes | 3.41 | 0 |
| Epodonios-all | 7081 | yes | 1.92 | 0 |
| SoliSpirit-all | 7049 | yes | 2.8 | 0 |
| DeltaKronecker-all | 6390 | yes | 3.33 | 0 |
| Surfboard-tg-mixed | 6304 | yes | 2.37 | 0 |
| barry-far-vless | 5240 | yes | 1.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 5067 | yes | 2.58 | 0 |
| Surfboard-tg-vless | 4858 | yes | 2.63 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.52 | 0 |
| mahdibland-V2RayAggregator | 3995 | yes | 1.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 28 |
| cn-block | 21 |
| speed | 14 |
| geo | 13 |
