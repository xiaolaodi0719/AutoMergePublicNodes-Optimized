# AutoNodes 每日报告

生成时间：2026-07-26 19:25:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83998 |
| 去重后节点数 | 22074 |
| TCP 可达数 | 3000 |
| 真测通过数 | 792 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22074 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 40.2 |
| geo | 1.3 |
| probe | 81.1 |
| real_test | 214.7 |
| tcp | 31.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 11 | 10 | 1 | 90.9% |
| http | 78 | 78 | 0 | 100.0% |
| hysteria2 | 12 | 10 | 2 | 83.3% |
| shadowsocks | 120 | 93 | 27 | 77.5% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 501 | 428 | 73 | 85.4% |
| vless | 559 | 172 | 387 | 30.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 139 |
| geo:TimeoutError | 109 |
| 204:ProxyError | 65 |
| 204:TimeoutError | 65 |
| geo:ClientOSError | 41 |
| cn-block:TimeoutError | 34 |
| cn-block:ProxyError | 10 |
| cn-block:ClientOSError | 9 |
| 204:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| geo:ProxyError | 3 |
| speed:ProxyError | 3 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4145 |
| ConnectionRefusedError | 723 |
| gaierror | 326 |
| OSError | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 78 | 1.0 | 86 |
| Au1rxx-base64 | 0.959 | prefer | 453 | 0.901 | 1507 |
| mheidari-all | 0.787 | prefer | 162 | 0.71 | 19379 |
| Surfboard-tg-mixed | 0.654 | observe | 52 | 0.577 | 5487 |
| xiaoji235-airport-v2ray-all | 0.519 | observe | 5 | 1.0 | 3959 |
| tg-oneclickvpnkeys | 0.495 | observe | 8 | 0.875 | 164 |
| DeltaKronecker-all | 0.364 | observe | 522 | 0.284 | 4320 |
| Surfboard-tg-vless | 0.287 | observe | 2 | 0.5 | 4238 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 6631 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 200 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.284 | 148 | 374 | 522 |
| Surfboard-tg-vless | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.577 | 30 | 22 | 52 |
| mheidari-all | 0.71 | 115 | 47 | 162 |
| tg-oneclickvpnkeys | 0.875 | 7 | 1 | 8 |
| Au1rxx-base64 | 0.901 | 408 | 45 | 453 |
| xiaoji235-airport-v2ray-all | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19379 | yes | 3.15 | 0 |
| Epodonios-all | 6631 | yes | 2.02 | 0 |
| SoliSpirit-all | 6557 | yes | 2.35 | 0 |
| Surfboard-tg-mixed | 5487 | yes | 1.9 | 0 |
| mahdibland-V2RayAggregator | 5003 | yes | 1.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 1.89 | 0 |
| barry-far-vless | 4894 | yes | 1.74 | 0 |
| DeltaKronecker-all | 4320 | yes | 3.83 | 0 |
| Surfboard-tg-vless | 4238 | yes | 2.15 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 2.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 153 |
| speed | 150 |
| 204 | 137 |
| cn-block | 53 |
