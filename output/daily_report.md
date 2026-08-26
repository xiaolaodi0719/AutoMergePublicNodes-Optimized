# AutoNodes 每日报告

生成时间：2026-08-26 19:56:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 89590 |
| 去重后节点数 | 24386 |
| TCP 可达数 | 3000 |
| 真测通过数 | 481 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24386 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 49.5 |
| geo | 1.3 |
| probe | 49.5 |
| real_test | 101.0 |
| tcp | 39.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 21 | 1 | 95.5% |
| hysteria2 | 26 | 26 | 0 | 100.0% |
| shadowsocks | 157 | 144 | 13 | 91.7% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 24 | 22 | 2 | 91.7% |
| vless | 359 | 266 | 93 | 74.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 38 |
| speed:TimeoutError | 17 |
| 204:TimeoutError | 14 |
| speed:ClientOSError | 12 |
| cn-block:TimeoutError | 9 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5337 |
| ConnectionRefusedError | 959 |
| gaierror | 367 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.96 | prefer | 351 | 0.883 | 1979 |
| Surfboard-tg-mixed | 0.958 | prefer | 80 | 0.887 | 6645 |
| zhangkai | 0.875 | prefer | 21 | 0.905 | 144 |
| mheidari-all | 0.65 | observe | 133 | 0.571 | 19290 |
| DeltaKronecker-all | 0.349 | observe | 3 | 0.667 | 6107 |
| tg-oneclickvpnkeys | 0.32 | observe | 2 | 1.0 | 218 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4825 |
| Epodonios-all | 0.255 | observe | 0 | None | 7011 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.571 | 76 | 57 | 133 |
| DeltaKronecker-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.883 | 310 | 41 | 351 |
| Surfboard-tg-mixed | 0.887 | 71 | 9 | 80 |
| zhangkai | 0.905 | 19 | 2 | 21 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19290 | yes | 4.32 | 0 |
| SoliSpirit-all | 7313 | yes | 3.19 | 0 |
| Epodonios-all | 7011 | yes | 0.84 | 0 |
| Surfboard-tg-mixed | 6645 | yes | 2.87 | 0 |
| DeltaKronecker-all | 6107 | yes | 4.2 | 0 |
| barry-far-vless | 5698 | yes | 2.31 | 0 |
| Surfboard-tg-vless | 5444 | yes | 2.69 | 0 |
| xiaoji235-airport-v2ray-all | 5418 | yes | 2.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4825 | yes | 2.44 | 0 |
| mahdibland-V2RayAggregator | 4011 | yes | 1.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 42 |
| speed | 30 |
| 204 | 23 |
| cn-block | 17 |
