# AutoNodes 每日报告

生成时间：2026-08-15 01:34:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 75507 |
| 去重后节点数 | 20655 |
| TCP 可达数 | 3000 |
| 真测通过数 | 984 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 20655 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 28.9 |
| geo | 1.6 |
| probe | 61.8 |
| real_test | 182.5 |
| tcp | 33.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 171 | 161 | 10 | 94.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 540 | 529 | 11 | 98.0% |
| vless | 313 | 142 | 171 | 45.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 53 |
| geo:TimeoutError | 47 |
| cn-block:TimeoutError | 39 |
| geo:ClientOSError | 23 |
| 204:TimeoutError | 11 |
| speed:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| 204:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4556 |
| ConnectionRefusedError | 797 |
| gaierror | 267 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 737 | 0.972 | 1681 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| DeltaKronecker-all | 0.89 | prefer | 56 | 0.821 | 3485 |
| mheidari-all | 0.447 | observe | 194 | 0.366 | 15517 |
| nscl5-all | 0.446 | observe | 8 | 0.625 | 2081 |
| Surfboard-tg-mixed | 0.42 | observe | 45 | 0.333 | 5718 |
| 10ium-ScrapeCategorize-Vless | 0.3 | observe | 5 | 0.4 | 5157 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 160 |
| Pawdroid | 0.255 | observe | 1 | 1.0 | 7 |
| Epodonios-all | 0.255 | observe | 0 | None | 6388 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.333 | 15 | 30 | 45 |
| mheidari-all | 0.366 | 71 | 123 | 194 |
| 10ium-ScrapeCategorize-Vless | 0.4 | 2 | 3 | 5 |
| nscl5-all | 0.625 | 5 | 3 | 8 |
| DeltaKronecker-all | 0.821 | 46 | 10 | 56 |
| Au1rxx-base64 | 0.972 | 716 | 21 | 737 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Pawdroid | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15517 | yes | 4.23 | 0 |
| SoliSpirit-all | 7639 | yes | 2.23 | 0 |
| Epodonios-all | 6388 | yes | 4.4 | 0 |
| Surfboard-tg-mixed | 5718 | yes | 3.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 5157 | yes | 0.97 | 0 |
| barry-far-vless | 4744 | yes | 0.72 | 0 |
| Surfboard-tg-vless | 4415 | yes | 3.0 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.06 | 0 |
| mahdibland-V2RayAggregator | 3992 | yes | 2.58 | 0 |
| DeltaKronecker-all | 3485 | yes | 3.77 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 71 |
| speed | 60 |
| cn-block | 44 |
| 204 | 18 |
