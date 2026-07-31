# AutoNodes 每日报告

生成时间：2026-07-31 19:47:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78935 |
| 去重后节点数 | 22858 |
| TCP 可达数 | 3000 |
| 真测通过数 | 555 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22858 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| generate | 31.8 |
| geo | 1.3 |
| probe | 62.1 |
| real_test | 170.1 |
| tcp | 34.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 80 | 80 | 0 | 100.0% |
| hysteria2 | 18 | 13 | 5 | 72.2% |
| shadowsocks | 119 | 96 | 23 | 80.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 57 | 52 | 5 | 91.2% |
| vless | 562 | 312 | 250 | 55.5% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 104 |
| 204:ProxyError | 36 |
| 204:TimeoutError | 34 |
| geo:ClientOSError | 30 |
| cn-block:TimeoutError | 28 |
| speed:TimeoutError | 19 |
| speed:ClientOSError | 13 |
| cn-block:ProxyError | 7 |
| 204:ClientOSError | 7 |
| cn-block:ClientOSError | 4 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4654 |
| ConnectionRefusedError | 770 |
| gaierror | 243 |
| OSError | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 80 | 1.0 | 110 |
| Au1rxx-base64 | 0.756 | prefer | 499 | 0.689 | 1685 |
| Surfboard-tg-mixed | 0.734 | prefer | 24 | 0.667 | 5433 |
| DeltaKronecker-all | 0.556 | observe | 231 | 0.476 | 5144 |
| mheidari-all | 0.438 | observe | 3 | 1.0 | 16449 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 51 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5507 |
| Epodonios-all | 0.255 | observe | 0 | None | 6115 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3975 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.476 | 110 | 121 | 231 |
| Surfboard-tg-mixed | 0.667 | 16 | 8 | 24 |
| Au1rxx-base64 | 0.689 | 344 | 155 | 499 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 80 | 0 | 80 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16449 | yes | 3.23 | 0 |
| SoliSpirit-all | 6602 | yes | 2.48 | 0 |
| Epodonios-all | 6115 | yes | 2.95 | 0 |
| 10ium-ScrapeCategorize-Vless | 5507 | yes | 1.81 | 0 |
| Surfboard-tg-mixed | 5433 | yes | 2.3 | 0 |
| DeltaKronecker-all | 5144 | yes | 3.35 | 0 |
| mahdibland-V2RayAggregator | 5081 | yes | 1.84 | 0 |
| barry-far-vless | 4677 | yes | 1.42 | 0 |
| Surfboard-tg-vless | 4317 | yes | 1.98 | 0 |
| MatinGhanbari-all-sub | 3975 | yes | 1.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 136 |
| 204 | 77 |
| cn-block | 39 |
| speed | 33 |
