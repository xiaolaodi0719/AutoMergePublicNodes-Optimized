# AutoNodes 每日报告

生成时间：2026-08-06 14:28:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 89832 |
| 去重后节点数 | 24596 |
| TCP 可达数 | 3000 |
| 真测通过数 | 475 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24596 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 41.8 |
| geo | 1.4 |
| probe | 49.9 |
| real_test | 97.6 |
| tcp | 37.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 152 | 138 | 14 | 90.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 160 | 157 | 3 | 98.1% |
| vless | 220 | 138 | 82 | 62.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 26 |
| 204:ProxyError | 20 |
| geo:TimeoutError | 20 |
| 204:TimeoutError | 12 |
| cn-block:TimeoutError | 10 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| speed:TimeoutError | 3 |
| speed:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4915 |
| ConnectionRefusedError | 811 |
| gaierror | 294 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.999 | prefer | 403 | 0.938 | 1577 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.584 | observe | 127 | 0.504 | 5904 |
| DeltaKronecker-all | 0.503 | observe | 12 | 0.583 | 5897 |
| mheidari-all | 0.389 | observe | 13 | 0.385 | 20767 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 5184 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5219 |
| Epodonios-all | 0.255 | observe | 0 | None | 6534 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7693 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.385 | 5 | 8 | 13 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.504 | 64 | 63 | 127 |
| DeltaKronecker-all | 0.583 | 7 | 5 | 12 |
| Au1rxx-base64 | 0.938 | 378 | 25 | 403 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20767 | yes | 5.42 | 0 |
| SoliSpirit-all | 7693 | yes | 3.26 | 0 |
| Epodonios-all | 6534 | yes | 5.91 | 0 |
| Surfboard-tg-mixed | 5904 | yes | 4.25 | 0 |
| DeltaKronecker-all | 5897 | yes | 4.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 5219 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 5212 | yes | 2.64 | 0 |
| xiaoji235-airport-v2ray-all | 5184 | yes | 2.48 | 0 |
| barry-far-vless | 5092 | yes | 1.36 | 0 |
| Surfboard-tg-vless | 4729 | yes | 3.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 46 |
| 204 | 37 |
| cn-block | 15 |
| speed | 5 |
