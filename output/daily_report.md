# AutoNodes 每日报告

生成时间：2026-07-24 03:23:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83695 |
| 去重后节点数 | 23126 |
| TCP 可达数 | 3000 |
| 真测通过数 | 893 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23126 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 31.8 |
| geo | 1.3 |
| probe | 81.2 |
| real_test | 258.5 |
| tcp | 32.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 19 | 16 | 3 | 84.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 614 | 566 | 48 | 92.2% |
| vless | 962 | 268 | 694 | 27.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 261 |
| speed:ClientOSError | 208 |
| cn-block:TimeoutError | 95 |
| geo:ClientOSError | 66 |
| 204:ProxyError | 49 |
| speed:TimeoutError | 38 |
| cn-block:ProxyError | 12 |
| geo:ProxyError | 6 |
| speed:ProxyError | 4 |
| 204:TimeoutError | 4 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4082 |
| ConnectionRefusedError | 703 |
| gaierror | 431 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.926 | prefer | 486 | 0.848 | 20024 |
| Surfboard-tg-mixed | 0.82 | prefer | 98 | 0.745 | 5375 |
| DeltaKronecker-all | 0.444 | observe | 1011 | 0.364 | 5572 |
| Au1rxx-base64 | 0.329 | observe | 2 | 1.0 | 432 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 3843 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4757 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6957 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Epodonios-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.364 | 368 | 643 | 1011 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.745 | 73 | 25 | 98 |
| mheidari-all | 0.848 | 412 | 74 | 486 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20024 | yes | 3.44 | 0 |
| SoliSpirit-all | 6957 | yes | 3.08 | 0 |
| Epodonios-all | 6509 | yes | 0.81 | 0 |
| DeltaKronecker-all | 5572 | yes | 4.27 | 0 |
| Surfboard-tg-mixed | 5375 | yes | 3.88 | 0 |
| mahdibland-V2RayAggregator | 4971 | yes | 2.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 4757 | yes | 1.94 | 0 |
| barry-far-vless | 4750 | yes | 1.13 | 0 |
| Surfboard-tg-vless | 4163 | yes | 2.25 | 0 |
| MatinGhanbari-all-sub | 3976 | yes | 2.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 333 |
| speed | 250 |
| cn-block | 108 |
| 204 | 55 |
