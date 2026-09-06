# AutoNodes 每日报告

生成时间：2026-09-06 10:42:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96057 |
| 去重后节点数 | 25365 |
| TCP 可达数 | 3000 |
| 真测通过数 | 490 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25365 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 33.1 |
| geo | 1.4 |
| probe | 85.0 |
| real_test | 115.7 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 21 | 4 | 84.0% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 161 | 152 | 9 | 94.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 23 | 21 | 2 | 91.3% |
| vless | 408 | 273 | 135 | 66.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 40 |
| geo:ClientOSError | 23 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 20 |
| speed:TimeoutError | 17 |
| geo:TimeoutError | 11 |
| 204:ProxyError | 8 |
| speed:ClientOSError | 5 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5715 |
| ConnectionRefusedError | 1000 |
| gaierror | 364 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.915 | prefer | 343 | 0.845 | 1781 |
| Surfboard-tg-mixed | 0.85 | prefer | 150 | 0.773 | 7318 |
| zhangkai | 0.839 | prefer | 22 | 0.864 | 144 |
| DeltaKronecker-all | 0.593 | observe | 7 | 1.0 | 5856 |
| mheidari-all | 0.558 | observe | 113 | 0.478 | 22388 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6965 |
| tg-oneclickvpnkeys | 0.274 | observe | 3 | 0.667 | 133 |
| peasoft-NoMoreWalls | 0.256 | observe | 1 | 1.0 | 30 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4791 |
| Epodonios-all | 0.255 | observe | 0 | None | 7771 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.478 | 54 | 59 | 113 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.773 | 116 | 34 | 150 |
| Au1rxx-base64 | 0.845 | 290 | 53 | 343 |
| zhangkai | 0.864 | 19 | 3 | 22 |
| peasoft-NoMoreWalls | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 7 | 0 | 7 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22388 | yes | 4.89 | 0 |
| SoliSpirit-all | 8223 | yes | 1.75 | 0 |
| Epodonios-all | 7771 | yes | 5.89 | 0 |
| Surfboard-tg-mixed | 7318 | yes | 3.59 | 0 |
| xiaoji235-airport-v2ray-all | 6965 | yes | 1.48 | 0 |
| barry-far-vless | 6223 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 6005 | yes | 5.09 | 0 |
| DeltaKronecker-all | 5856 | yes | 5.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 4791 | yes | 0.53 | 0 |
| mahdibland-V2RayAggregator | 4111 | yes | 1.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 61 |
| 204 | 35 |
| geo | 34 |
| speed | 22 |
