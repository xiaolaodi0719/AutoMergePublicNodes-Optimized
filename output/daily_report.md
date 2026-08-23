# AutoNodes 每日报告

生成时间：2026-08-23 12:55:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77897 |
| 去重后节点数 | 21437 |
| TCP 可达数 | 3000 |
| 真测通过数 | 777 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21437 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 39.3 |
| geo | 1.5 |
| probe | 62.8 |
| real_test | 183.3 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 209 | 190 | 19 | 90.9% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 43 | 35 | 8 | 81.4% |
| vless | 583 | 418 | 165 | 71.7% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 54 |
| cn-block:TimeoutError | 38 |
| 204:TimeoutError | 28 |
| geo:ClientOSError | 22 |
| speed:TimeoutError | 14 |
| speed:ClientOSError | 12 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 4 |
| cn-block:ProxyError | 2 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4841 |
| ConnectionRefusedError | 827 |
| gaierror | 310 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 113 | 1.0 | 144 |
| Au1rxx-base64 | 0.964 | prefer | 431 | 0.896 | 1745 |
| mheidari-all | 0.964 | prefer | 41 | 0.902 | 14522 |
| Surfboard-tg-mixed | 0.826 | prefer | 128 | 0.75 | 6399 |
| DeltaKronecker-all | 0.642 | observe | 256 | 0.562 | 5415 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4989 |
| Epodonios-all | 0.255 | observe | 0 | None | 6941 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3986 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6992 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5266 |

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
| nscl5-all | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.562 | 144 | 112 | 256 |
| Surfboard-tg-mixed | 0.75 | 96 | 32 | 128 |
| Au1rxx-base64 | 0.896 | 386 | 45 | 431 |
| mheidari-all | 0.902 | 37 | 4 | 41 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14522 | yes | 5.05 | 0 |
| SoliSpirit-all | 6992 | yes | 1.42 | 0 |
| Epodonios-all | 6941 | yes | 4.2 | 0 |
| Surfboard-tg-mixed | 6399 | yes | 3.73 | 0 |
| barry-far-vless | 5469 | yes | 0.5 | 0 |
| DeltaKronecker-all | 5415 | yes | 4.33 | 0 |
| Surfboard-tg-vless | 5266 | yes | 3.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4989 | yes | 0.71 | 0 |
| mahdibland-V2RayAggregator | 4094 | yes | 2.68 | 0 |
| MatinGhanbari-all-sub | 3986 | yes | 1.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 80 |
| cn-block | 45 |
| 204 | 42 |
| speed | 28 |
