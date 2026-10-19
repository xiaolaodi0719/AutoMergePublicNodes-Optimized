# AutoNodes 每日报告

生成时间：2026-10-19 04:15:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97333 |
| 去重后节点数 | 27722 |
| TCP 可达数 | 3000 |
| 真测通过数 | 496 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27722 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 84.5 |
| geo | 1.4 |
| probe | 266.1 |
| real_test | 320.2 |
| tcp | 48.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 46 | 23 | 23 | 50.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 153 | 143 | 10 | 93.5% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 68 | 65 | 3 | 95.6% |
| vless | 420 | 242 | 178 | 57.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 73 |
| geo:ClientOSError | 31 |
| 204:ProxyError | 30 |
| speed:ClientOSError | 22 |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 14 |
| speed:TimeoutError | 14 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7016 |
| ConnectionRefusedError | 1056 |
| gaierror | 341 |
| OSError | 240 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.905 | prefer | 396 | 0.838 | 1698 |
| Surfboard-tg-mixed | 0.787 | prefer | 114 | 0.711 | 7003 |
| ermaozi | 0.518 | observe | 47 | 0.489 | 696 |
| mheidari-all | 0.481 | observe | 140 | 0.4 | 23518 |
| DeltaKronecker-all | 0.318 | observe | 17 | 0.235 | 4750 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| Epodonios-all | 0.255 | observe | 0 | None | 7467 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9820 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5523 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.235 | 4 | 13 | 17 |
| mheidari-all | 0.4 | 56 | 84 | 140 |
| ermaozi | 0.489 | 23 | 24 | 47 |
| Surfboard-tg-mixed | 0.711 | 81 | 33 | 114 |
| Au1rxx-base64 | 0.838 | 332 | 64 | 396 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23518 | yes | 4.47 | 0 |
| SoliSpirit-all | 9820 | yes | 3.25 | 0 |
| Epodonios-all | 7467 | yes | 4.85 | 0 |
| Surfboard-tg-mixed | 7003 | yes | 3.28 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.73 | 0 |
| barry-far-vless | 5700 | yes | 1.62 | 0 |
| Surfboard-tg-vless | 5523 | yes | 3.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 1.42 | 0 |
| DeltaKronecker-all | 4750 | yes | 3.69 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 0.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 106 |
| 204 | 48 |
| speed | 36 |
| cn-block | 28 |
