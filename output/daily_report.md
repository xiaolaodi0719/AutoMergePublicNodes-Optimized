# AutoNodes 每日报告

生成时间：2026-08-25 01:40:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83410 |
| 去重后节点数 | 23892 |
| TCP 可达数 | 3000 |
| 真测通过数 | 732 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23892 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 33.3 |
| geo | 1.5 |
| probe | 60.3 |
| real_test | 168.3 |
| tcp | 38.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 225 | 215 | 10 | 95.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 35 | 28 | 7 | 80.0% |
| vless | 883 | 439 | 444 | 49.7% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 195 |
| geo:ClientOSError | 108 |
| speed:TimeoutError | 83 |
| speed:ClientOSError | 40 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 8 |
| 204:ProxyError | 6 |
| 204:TimeoutError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5417 |
| ConnectionRefusedError | 885 |
| gaierror | 257 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 476 | 0.92 | 1713 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.9 | prefer | 176 | 0.824 | 6540 |
| mheidari-all | 0.329 | observe | 467 | 0.248 | 19487 |
| DeltaKronecker-all | 0.28 | observe | 48 | 0.188 | 5914 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4899 |
| Epodonios-all | 0.255 | observe | 0 | None | 7074 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3989 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7047 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5352 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.188 | 9 | 39 | 48 |
| mheidari-all | 0.248 | 116 | 351 | 467 |
| ninja-vless | 0.333 | 1 | 2 | 3 |
| Surfboard-tg-mixed | 0.824 | 145 | 31 | 176 |
| Au1rxx-base64 | 0.92 | 438 | 38 | 476 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19487 | yes | 4.93 | 0 |
| Epodonios-all | 7074 | yes | 4.0 | 0 |
| SoliSpirit-all | 7047 | yes | 4.78 | 0 |
| Surfboard-tg-mixed | 6540 | yes | 3.35 | 0 |
| DeltaKronecker-all | 5914 | yes | 4.12 | 0 |
| barry-far-vless | 5640 | yes | 3.04 | 0 |
| Surfboard-tg-vless | 5352 | yes | 3.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 4899 | yes | 2.42 | 0 |
| mahdibland-V2RayAggregator | 4132 | yes | 1.49 | 0 |
| MatinGhanbari-all-sub | 3989 | yes | 2.49 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 303 |
| speed | 123 |
| cn-block | 23 |
| 204 | 15 |
