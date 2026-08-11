# AutoNodes 每日报告

生成时间：2026-08-11 07:19:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84663 |
| 去重后节点数 | 24209 |
| TCP 可达数 | 3000 |
| 真测通过数 | 506 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24209 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 32.2 |
| geo | 1.4 |
| probe | 52.8 |
| real_test | 110.3 |
| tcp | 36.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 49 | 0 | 100.0% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 158 | 150 | 8 | 94.9% |
| socks | 10 | 6 | 4 | 60.0% |
| trojan | 139 | 126 | 13 | 90.6% |
| vless | 258 | 158 | 100 | 61.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 30 |
| geo:ClientOSError | 29 |
| 204:TimeoutError | 16 |
| speed:TimeoutError | 16 |
| speed:ClientOSError | 12 |
| cn-block:TimeoutError | 8 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4887 |
| ConnectionRefusedError | 807 |
| gaierror | 334 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | prefer | 49 | 1.0 | 67 |
| Au1rxx-base64 | 0.97 | prefer | 381 | 0.916 | 1409 |
| Surfboard-tg-mixed | 0.802 | prefer | 106 | 0.726 | 6265 |
| DeltaKronecker-all | 0.447 | observe | 47 | 0.362 | 5522 |
| mheidari-all | 0.378 | observe | 45 | 0.289 | 20272 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5419 |
| Epodonios-all | 0.255 | observe | 0 | None | 6871 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7470 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5103 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.289 | 13 | 32 | 45 |
| DeltaKronecker-all | 0.362 | 17 | 30 | 47 |
| Surfboard-tg-mixed | 0.726 | 77 | 29 | 106 |
| Au1rxx-base64 | 0.916 | 349 | 32 | 381 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 49 | 0 | 49 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20272 | yes | 4.43 | 0 |
| SoliSpirit-all | 7470 | yes | 3.51 | 0 |
| Epodonios-all | 6871 | yes | 4.64 | 0 |
| Surfboard-tg-mixed | 6265 | yes | 2.82 | 0 |
| DeltaKronecker-all | 5522 | yes | 4.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 5419 | yes | 2.13 | 0 |
| barry-far-vless | 5410 | yes | 2.62 | 0 |
| mahdibland-V2RayAggregator | 5209 | yes | 1.02 | 0 |
| Surfboard-tg-vless | 5103 | yes | 3.28 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 59 |
| speed | 28 |
| 204 | 25 |
| cn-block | 13 |
