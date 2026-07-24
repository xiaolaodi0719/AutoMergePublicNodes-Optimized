# AutoNodes 每日报告

生成时间：2026-07-24 19:41:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83183 |
| 去重后节点数 | 22837 |
| TCP 可达数 | 3000 |
| 真测通过数 | 529 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22837 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 29.7 |
| geo | 1.4 |
| probe | 69.1 |
| real_test | 161.4 |
| tcp | 33.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 16 | 12 | 4 | 75.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 396 | 337 | 59 | 85.1% |
| vless | 452 | 137 | 315 | 30.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 161 |
| geo:TimeoutError | 74 |
| 204:ProxyError | 37 |
| cn-block:TimeoutError | 36 |
| geo:ClientOSError | 26 |
| 204:TimeoutError | 21 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| geo:ProxyError | 5 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4669 |
| ConnectionRefusedError | 691 |
| gaierror | 242 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.935 | prefer | 280 | 0.857 | 19355 |
| Surfboard-tg-mixed | 0.888 | prefer | 97 | 0.814 | 5475 |
| DeltaKronecker-all | 0.426 | observe | 489 | 0.346 | 5559 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 3847 |
| Au1rxx-base64 | 0.329 | observe | 2 | 1.0 | 432 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4588 |
| Epodonios-all | 0.255 | observe | 0 | None | 6668 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3967 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.346 | 169 | 320 | 489 |
| Surfboard-tg-mixed | 0.814 | 79 | 18 | 97 |
| mheidari-all | 0.857 | 240 | 40 | 280 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19355 | yes | 2.78 | 0 |
| SoliSpirit-all | 6766 | yes | 2.92 | 0 |
| Epodonios-all | 6668 | yes | 2.92 | 0 |
| DeltaKronecker-all | 5559 | yes | 2.95 | 0 |
| Surfboard-tg-mixed | 5475 | yes | 1.82 | 0 |
| mahdibland-V2RayAggregator | 5027 | yes | 1.42 | 0 |
| barry-far-vless | 4905 | yes | 0.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 4588 | yes | 1.05 | 0 |
| Surfboard-tg-vless | 4271 | yes | 2.13 | 0 |
| MatinGhanbari-all-sub | 3967 | yes | 1.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 169 |
| geo | 105 |
| 204 | 60 |
| cn-block | 45 |
